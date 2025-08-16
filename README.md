<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <title>Play Video Once</title>
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <style>
    body { font-family: system-ui, -apple-system, "Segoe UI", Roboto, sans-serif;
           display:flex; min-height:100vh; align-items:center; justify-content:center;
           background:#111; color:#eee; margin:0; }
    .container { max-width:900px; width:100%; padding:16px; text-align:center; }
    video { width:100%; height:auto; border-radius:8px; background:#000; }
    button { margin-top:12px; padding:8px 12px; font-size:16px; cursor:pointer;
             border-radius:6px; border:1px solid #444; background:#0e639c; color:#fff; }
    button:disabled { opacity:0.5; cursor:not-allowed }
  </style>
</head>
<body>
  <div class="container">
    <!-- Replace src with your video path (mp4/webm) -->
    <video id="myVideo" preload="metadata" controls>
      <source src="Untitled_design(1).mp4" type="video/mp4">
      Your browser does not support the video element.
    </video>

    <!-- Visible play button ensures play works on mobile/desktop -->
    <div>
      <button id="playOnceBtn">Play Once</button>
    </div>

    <p id="note" style="opacity:.8;margin-top:8px;font-size:13px;">
      The video will play one time. After it ends it will pause and cannot be replayed.
    </p>
  </div>

  <script>
    const video = document.getElementById('myVideo');
    const btn = document.getElementById('playOnceBtn');
    const note = document.getElementById('note');

    // hasPlayed becomes true when the video has completed its first full playback
    let hasPlayed = false;

    // When Play Once button clicked: start playback if not already played
    btn.addEventListener('click', async () => {
      if (hasPlayed) return;
      try {
        // Some browsers require user gesture; using button covers that
        await video.play();
        btn.disabled = true; // prevent repeated clicks while playing
      } catch (err) {
        console.warn('Playback prevented by browser autoplay policy:', err);
        note.textContent = 'Playback blocked — please click Play on the video controls.';
      }
    });

    // When the video ends => mark as played, pause, disable controls/button so it can't be replayed
    video.addEventListener('ended', () => {
      hasPlayed = true;
      video.pause();
      // disable controls to prevent replay from UI (optional)
      video.controls = false;
      btn.disabled = true;
      note.textContent = 'Video finished playing once. Replay disabled.';
    });

    // If user tries to play after it already played once, immediately pause
    video.addEventListener('play', () => {
      if (hasPlayed) {
        // Immediately stop any further play attempts
        video.pause();
        btn.disabled = true;
        note.textContent = 'Replay disabled.';
      }
    });

    // Optional: prevent seeking to replay — block seeking after finished
    video.addEventListener('seeking', () => {
      if (hasPlayed) {
        // Force seek back to end (prevent replay)
        video.currentTime = video.duration;
      }
    });

    // If you want autoplay (muted) uncomment these lines — note browsers block autoplay unless muted:
    // video.muted = true;
    // video.autoplay = true;
    // video.play().catch(()=>{/* ignored — user gesture required on many browsers */});
  </script>
</body>
</html>
