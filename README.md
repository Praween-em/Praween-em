<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Praveen Kumar's GitHub Profile</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700;900&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            padding: 0;
            /* Applying the solid yellow background to the entire page for the screenshot */
            background-color: #FFD700; /* A vibrant gold yellow */
            font-family: 'Inter', sans-serif;
            color: #000000;
        }
        .profile-container {
            max-width: 980px; /* Mimic GitHub's typical content width */
            margin: 0 auto; /* Center the content */
            padding: 20px;
            background-color: rgba(255, 255, 255, 0.95); /* Slightly transparent white for content sections */
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Subtle shadow for depth */
            margin-top: 20px; /* Space from the top of the page */
            margin-bottom: 20px;
        }
        h1, h2, h3 {
            color: #000000;
        }
        strong {
            color: #1a73e8; /* Blue accent for strong text */
        }
        .separator {
            width: 100%;
            height: 5px;
            background-color: #1A1A1A;
            margin: 40px 0;
            border-radius: 2px;
        }
        table {
            width: 100%;
            border-collapse: separate; /* Use separate to allow border-spacing */
            border-spacing: 20px 0; /* Space between table cells */
            max-width: 900px;
            margin: 0 auto;
            border-radius: 10px;
            overflow: hidden; /* Ensures rounded corners are applied to content */
            border: none; /* Remove default table borders */
        }
        table td {
            background-color: #1A1A1A;
            padding: 25px;
            border-radius: 15px;
            border: 2px solid #00FFFF; /* Cyan border for project cards */
            vertical-align: top;
            color: #F0F0F0; /* Light text color for dark backgrounds */
            box-sizing: border-box; /* Include padding and border in the element's total width and height */
        }
        table th, table td:first-child { /* Styling for skill table headers/first column */
            background-color: #1A1A1A;
            color: #FFFFFF;
            padding: 15px;
            font-weight: bold;
            font-size: 1.2em;
            border-bottom: 1px solid #333;
            text-align: center;
        }
        table img {
            margin: 5px;
        }
        a {
            color: #00FFFF; /* Vibrant cyan for links */
            text-decoration: none;
            font-weight: bold;
        }
        a:hover {
            text-decoration: underline;
        }
        /* Flexbox for badges to ensure consistent spacing */
        .badge-container {
            display: flex;
            justify-content: center;
            gap: 10px; /* Space between badges */
            margin-bottom: 20px;
        }
    </style>
</head>
<body>

    <div class="profile-container">

        <!-- Header Section -->
        <div align="center" style="margin-bottom: 40px;">
            <h1 style="font-size: 3em; margin-bottom: 10px; font-weight: 900;">PRAVEEN KUMAR: CHARGED & READY!</h1>
            <p style="font-size: 1.2em; margin-bottom: 20px;">Your friendly neighborhood coder, sparking innovation.</p>
            
            <!-- Social Badges -->
            <div class="badge-container">
                <img src="https://img.shields.io/github/followers/Praween-em?label=Followers&style=for-the-badge&logo=github&color=000000" alt="GitHub Followers"> 
                <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin&color=1a73e8" alt="LinkedIn">
            </div>
        </div>

        <div class="separator"></div>

        <!-- About Me Section -->
        <div style="margin-bottom: 40px;">
            <h2 style="font-size: 2em; margin-bottom: 15px; text-align: center;">💡 MY CORE OUTPUT</h2>
            <p style="line-height: 1.6; text-align: center; max-width: 800px; margin: 0 auto; font-size: 1.1em;">
                Hey there! I'm a <strong>super-charged developer</strong> on a mission to create code that's totally "off the hook!" My journey through the digital world is like a non-stop Saturday morning cartoon, filled with new challenges and epic <strong>level-up moments</strong>. I've got a solid playbook of skills but I'm always tuning in to learn the next big thing. My goal? To build solutions that are not just functional, but <strong>da bomb! 💣</strong>
            </p>
        </div>

        <div class="separator"></div>

        <!-- Projects Section -->
        <div style="margin-bottom: 40px;">
            <h2 style="font-size: 2em; margin-bottom: 15px; text-align: center;">🚀 PROJECTS: MISSION LOG</h2>
            <table width="100%">
                <tr align="center">
                    <!-- Project Card 1 -->
                    <td>
                        <h3 style="color: #FFFFFF; font-size: 1.5em; margin-bottom: 10px;"><strong>Intelligent Surveillance System</strong></h3>
                        <!-- Placeholder image for project demo - Remember to replace with actual GIF/screenshot -->
                        <img src="https://placehold.co/300x150/000000/FFFFFF?text=Project+Demo" alt="Intelligent Surveillance System Demo" style="border-radius: 8px; margin-bottom: 15px; max-width: 100%; height: auto;">
                        <p style="color: #F0F0F0; line-height: 1.5; font-size: 1em;">A high-tech system for smart monitoring! Built to be the ultimate watchdog for any digital fortress, offering advanced threat detection.</p>
                        <a href="https://github.com/Praween-em/Intelligent-Surveillance-System" style="color: #00FFFF; text-decoration: none; font-weight: bold; display: inline-block; margin-top: 15px;">
                            <b>➡️ View Mission Details</b>
                        </a>
                    </td>
                    <!-- Project Card 2 -->
                    <td>
                        <h3 style="color: #FFFFFF; font-size: 1.5em; margin-bottom: 10px;"><strong>toletu</strong></h3>
                        <!-- Placeholder image for project demo - Remember to replace with actual GIF/screenshot -->
                        <img src="https://placehold.co/300x150/000000/FFFFFF?text=Project+Demo" alt="Toletu App Demo" style="border-radius: 8px; margin-bottom: 15px; max-width: 100%; height: auto;">
                        <p style="color: #F0F0F0; line-height: 1.5; font-size: 1em;">My awesome "To-Let" application for finding your next spot! It's the coolest way to search for rentals with ease.</p>
                        <a href="https://github.com/Praween-em/toletu" style="color: #00FFFF; text-decoration: none; font-weight: bold; display: inline-block; margin-top: 15px;">
                            <b>➡️ View Mission Details</b>
                        </a>
                    </td>
                </tr>
            </table>
        </div>

        <div class="separator"></div>

        <!-- Skills Section -->
        <div style="margin-bottom: 40px;">
            <h2 style="font-size: 2em; margin-bottom: 15px; text-align: center;">🧰 MY TOOLKIT</h2>
            <table width="100%">
                <tr>
                    <td><strong>LANGUAGES</strong></td>
                    <td style="border-bottom: 1px solid #333;">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="45"/>
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" title="TypeScript" alt="TypeScript" width="45"/>
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" title="Python" alt="Python" width="45"/>
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original.svg" title="Java" alt="Java" width="45"/>
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/cplusplus/cplusplus-original.svg" title="C++" alt="C++" width="45"/>
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" title="HTML5" alt="HTML5" width="45"/>
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" title="CSS3" alt="CSS3" width="45"/>
                    </td>
                </tr>
                <tr>
                    <td><strong>FRONTEND</strong></td>
                    <td style="border-bottom: 1px solid #333;">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" title="React" alt="React" width="45"/>
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/angular/angular-original.svg" title="Angular" alt="Angular" width="45"/>
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vuejs/vuejs-original.svg" title="Vue.js" alt="Vue.js" width="45"/>
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/tailwindcss/tailwindcss-original.svg" title="Tailwind CSS" alt="Tailwind CSS" width="45"/>
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/bootstrap/bootstrap-original.svg" title="Bootstrap" alt="Bootstrap" width="45"/>
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/sass/sass-original.svg" title="SASS" alt="SASS" width="45"/>
                    </td>
                </tr>
                <tr>
                    <td><strong>BACKEND</strong></td>
                    <td style="border-bottom: 1px solid #333;">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nodejs/nodejs-original-wordmark.svg" title="Node.js" alt="Node.js" width="45"/>
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/express/express-original.svg" title="Express" alt="Express" width="45"/>
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/django/django-plain.svg" title="Django" alt="Django" width="45"/>
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/flask/flask-original.svg" title="Flask" alt="Flask" width="45"/>
                    </td>
                </tr>
                <tr>
                    <td><strong>DATABASES</strong></td>
                    <td style="border-bottom: 1px solid #333;">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mongodb/mongodb-original.svg" title="MongoDB" alt="MongoDB" width="45"/>
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" title="PostgreSQL" alt="PostgreSQL" width="45"/>
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original.svg" title="MySQL" alt="MySQL" width="45"/>
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/sqlite/sqlite-original.svg" title="SQLite" alt="SQLite" width="45"/>
                    </td>
                </tr>
                <tr>
                    <td><strong>TOOLS & PLATFORMS</strong></td>
                    <td>
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" title="Git" alt="Git" width="45"/>
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/github/github-original.svg" title="GitHub" alt="GitHub" width="45"/>
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" title="Docker" alt="Docker" width="45"/>
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postman/postman-original.svg" title="Postman" alt="Postman" width="45"/>
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vscode/vscode-original.svg" title="VS Code" alt="VS Code" width="45"/>
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/figma/figma-original.svg" title="Figma" alt="Figma" width="45"/>
                    </td>
                </tr>
            </table>
        </div>

        <div class="separator"></div>

        <!-- GitHub Stats Section -->
        <div style="margin-bottom: 40px;">
            <h2 style="font-size: 2em; margin-bottom: 15px; text-align: center;">📊 PERFORMANCE DASHBOARD</h2>
            <p align="center">
                <img src="https://github-readme-stats.vercel.app/api?username=Praween-em&show_icons=true&theme=tokyonight&border_radius=20" alt="Praween's GitHub Stats" />
                <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Praween-em&layout=compact&theme=tokyonight&border_radius=20" alt="Top Languages" />
            </p>
        </div>

        <div class="separator"></div>

        <!-- Connect Section -->
        <div style="margin-bottom: 20px;">
            <h2 style="font-size: 2em; margin-bottom: 15px; text-align: center;">📞 LET'S CONNECT!</h2>
            <p style="text-align: center; font-size: 1.1em;">Got a cool idea or just wanna chat about tech? My signal is always on!</p>
            <p align="center" style="margin-top: 20px;">
                <a href="https://www.linkedin.com/in/praveen-kumar-a00420280/" target="_blank"><img src="https://img.icons8.com/color/48/000000/linkedin-circled--v1.png" alt="LinkedIn" style="margin: 0 10px;"/></a>
                &nbsp;
                <a href="mailto:YOUR_EMAIL_HERE@example.com"><img src="https://img.icons8.com/color/48/000000/new-post.png" alt="Gmail" style="margin: 0 10px;"/></a>
                &nbsp;
                <!-- Replace with your actual Twitter handle or remove if not applicable -->
                <a href="https://twitter.com/YOUR_TWITTER_HANDLE" target="_blank"><img src="https://img.icons8.com/color/48/000000/twitter-circled--v1.png" alt="Twitter" style="margin: 0 10px;"/></a>
            </p>
        </div>

    </div> <!-- End of profile-container -->

</body>
</html>
