<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Lee Hueckstaedt | Information Technology Professional</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header class="site-header">
        <div class="container">
            <h1 class="name">Lee Hueckstaedt</h1>
            <p class="tagline">Information Technology • Web Design • Cybersecurity</p>

            <div class="contact">
                <a href="mailto:Hueckstaedtlee@gmail.com">Hueckstaedtlee@gmail.com</a> · 
                <span>Brookfield, WI</span> · 
                <a href="https://www.linkedin.com/in/lee-hueckstaedt-623868298" target="_blank">LinkedIn</a> ·
                <span>715-892-9883</span>
            </div>
        </div>
    </header>

    <main class="container">

        <!-- SUMMARY -->
        <section>
            <h2>Professional Summary</h2>
            <p>
                Motivated and disciplined IT professional with a 3.9 GPA and hands-on experience in 
                web design, cybersecurity, and network systems. Former U.S. Army Sergeant with proven 
                leadership overseeing a 10-member squad in high-pressure environments. Passionate 
                about building responsive, user-friendly webpages and developing secure digital 
                solutions that combine accessibility, performance, and strong technical design.
            </p>
        </section>

        <!-- EDUCATION -->
        <section>
            <h2>Education</h2>

            <div class="item">
                <h3>Bachelor of Science in Information Technology</h3>
                <p class="item-location">University of Wisconsin–Milwaukee</p>
                <p class="item-dates">Expected Graduation: March 2026 | GPA: 3.9</p>
            </div>

            <div class="item">
                <h3>Associate’s Degree in Criminal Justice</h3>
                <p class="item-location">Nicolet Area Technical College – Rhinelander, WI</p>
            </div>
        </section>

        <!-- INTERNSHIP -->
        <section>
            <h2>Internship</h2>
            <div class="item">
                <h3>Ovation Jewish Home – IT Department</h3>
                <p class="item-dates">Spring 2024 | Milwaukee, WI</p>
                <ul>
                    <li>Supported daily IT operations, troubleshooting hardware, software, and connectivity issues.</li>
                    <li>Assisted in network infrastructure upgrades and workstation rollouts.</li>
                    <li>Collaborated with senior technicians to improve data management and internal systems.</li>
                </ul>
            </div>
        </section>

        <!-- MILITARY -->
        <section>
            <h2>Military Experience</h2>

            <div class="item">
                <h3>U.S. Army – 4th Infantry Division</h3>
                <p class="item-dates">Sergeant | Infantry (MOS) | 2004–2009</p>
                <p>Deployment: Iraq (2006)</p>

                <ul>
                    <li>Led a 10-member squad in tactical operations, logistics, and field communications.</li>
                    <li>Trained and mentored soldiers in teamwork, safety, and mission execution.</li>
                </ul>

                <h4>Awards & Honors</h4>
                <ul>
                    <li>Purple Heart</li>
                    <li>Combat Infantry Badge</li>
                    <li>Iraq Campaign Medal</li>
                    <li>Operation Enduring Freedom Badge</li>
                    <li>Army Commendation Medal</li>
                    <li>Army Good Conduct Medal</li>
                    <li>Global War on Terrorism Service Medal</li>
                    <li>National Defense Service Medal</li>
                    <li>Army Service Ribbon</li>
                    <li>Overseas Service Ribbon</li>
                    <li>Expert Rifle Marksmanship Badge (40/40)</li>
                    <li>Driver & Mechanic Badge</li>
                </ul>
            </div>
        </section>

        <!-- PROJECTS -->
        <section>
            <h2>Projects</h2>

            <div class="item">
                <h3>HandScribe (Senior Capstone Project)</h3>
                <ul>
                    <li>Developing an ASL-to-text mobile app with real-time sign recognition and animated avatar translation.</li>
                    <li>Working with a four-person team on UI design, front-end development, and system integration.</li>
                </ul>
            </div>

            <div class="item">
                <h3>Non-profIT Project</h3>
                <ul>
                    <li>Collaborated on a class project providing IT support for nonprofit organizations.</li>
                    <li>Helped analyze client needs, design secure websites, and recommend technology improvements to strengthen community engagement.</li>
                </ul>
            </div>
        </section>

        <!-- COURSEWORK -->
        <section>
            <h2>Relevant Coursework</h2>
            <ul class="two-column">
                <li>Web Design I & II</li>
                <li>Web Application Development</li>
                <li>Information Security I</li>
                <li>Ethical Hacking I</li>
                <li>Cisco Routing & Switching I</li>
                <li>Database & Information Retrieval Systems</li>
                <li>Systems Analysis</li>
                <li>Human Factors in Information Seeking</li>
                <li>Project Teams</li>
                <li>Senior Capstone</li>
            </ul>
        </section>

        <!-- SKILLS -->
        <section>
            <h2>Technical Skills</h2>

            <div class="skills-grid">
                <ul>
                    <li>TCP/IP, DNS, DHCP</li>
                    <li>Cisco Routers, EIGRP</li>
                    <li>Kali Linux, Nmap</li>
                    <li>Metasploitable, Bettercap</li>
                    <li>Wireshark</li>
                </ul>

                <ul>
                    <li>HTML5, CSS3, JavaScript</li>
                    <li>Responsive Design</li>
                    <li>GitHub</li>
                    <li>VirtualBox, VMware</li>
                    <li>Windows & Linux Systems</li>
                </ul>

                <ul>
                    <li>Leadership</li>
                    <li>Teamwork</li>
                    <li>Problem-Solving</li>
                    <li>Adaptability</li>
                    <li>Analytical Thinking</li>
                </ul>
            </div>
        </section>

        <!-- INTERESTS -->
        <section>
            <h2>Professional Interests</h2>
            <p>
                Driven to advance in cybersecurity, network defense, and web development. Enthusiastic about designing 
                functional, visually appealing, and secure webpages that improve accessibility and user experience.
            </p>
        </section>

    </main>

    <footer class="site-footer">
        <div class="container">
            <p>&copy; <span id="year"></span> Lee Hueckstaedt</p>
        </div>

        <script>
            document.getElementById('year').textContent = new Date().getFullYear();
        </script>
    </footer>

</body>
</html>
