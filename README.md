<p align="center">
    <img align="center" src="img.jpg" />
</p>

# <h1 align="center">Hi 👋, I'm JAYMEEN VAGHELA</h1>
###
<p align="center">
<h3 align="center">An aspiring full stack developer and computer engineering student<br><br>
    Behind every great product is a backend that keeps pushing upward.</h3>
</p>

---
### Current Focus :

- 🔭 Building **[TRINETRA](https://github.com/jaymeen07-r/TRINETRA-public)** — intelligent systems with deep tech vision  
- 🌱 Learning Node.js & scalable backend architectures  
- 💡 Computer Engineering Student | Founder @ TRINETRA  
- 🚀 Passionate about AI, system design & futuristic interfaces


---
### About Me :

I'm currently pursuing my Bachelor of Engineering in Computer Engineering, with a strong focus on backend development
and AI-driven system design. My academic journey is rooted in the legacy of Vidush Somany Institute of Technology and
Research, a constituent of Kadi Sarva Vishwavidyalaya Gandhinagar, which carries over a century of philanthropic
excellence in education. This heritage inspires my commitment to innovation, empathy, and purpose-driven computing.
Alongside my academics, I am the Founder of TRINETRA which is an AI-driven misinformation detection Android application
designed to help users identify fake, misleading, or manipulated content across digital platforms. Built with a vision
to ensure digital safety, authenticity, and trust, TRINETRA empowers people to make informed decisions in an era where
misinformation spreads faster than truth.


---
### Languages and Tools:

<p align="center">
    <a href="https://www.python.org" target="_blank" rel="noreferrer"><img
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg"
            alt="python" width="40" height="40" /></a>
    <a href="https://nodejs.org" target="_blank" rel="noreferrer"><img
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg"
            alt="nodejs" width="40" height="40" /></a>
    <a href="https://www.php.net" target="_blank" rel="noreferrer"><img
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php"
            width="40" height="40" /></a>
    <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"><img
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg"
            alt="html5" width="40" height="40" /></a>
    <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"><img
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg"
            alt="css3" width="40" height="40" /></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"><img
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg"
            alt="javascript" width="40" height="40" /></a>
    <a href="https://www.figma.com/" target="_blank" rel="noreferrer"><img
            src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40" /></a>
    <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"><img
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg"
            alt="mongodb" width="40" height="40" /></a>
    <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"><img
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg"
            alt="aws" width="40" height="40" /> </a>
    <a href="https://firebase.google.com/" target="_blank" rel="noreferrer"><img
            src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40"
            height="40" /></a>
</p>
<p align="center">
    <a href="https://www.docker.com/" target="_blank" rel="noreferrer"><img
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg"
            alt="docker" width="40" height="40" /></a>
    <a href="https://flutter.dev" target="_blank" rel="noreferrer"><img
            src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" alt="flutter" width="40"
            height="40" /></a>
    <a href="https://git-scm.com/" target="_blank" rel="noreferrer"><img
            src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40" /></a>
    <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"><img
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40"
            height="40" /></a>
    <a href="https://www.linux.org/" target="_blank" rel="noreferrer"><img
            src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux"
            width="40" height="40" /></a>
</p>


<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Radar Chart - Skills</title>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <style>
        * {
            font-family: Agency FB;
        }
        .chart-box {
            width: 350px;
            padding: 30px;
            border-radius: 20px;
            background: #2a2a2a;
            box-shadow: 0px 0px 20px rgba(255, 136, 0, 0.2);
            text-align: center;
        }
        .chart-box h2 {
            margin-bottom: 20px;
            color: #ff8a00;
        }
        canvas {
            width: 100% !important;
            height: 100% !important;
        }
    </style>
</head>
<body>
    <div class="chart-box">
        <h2>Skill Level Visualization</h2>
        <canvas id="skillRadar"></canvas>
    </div>
    <script>
        const ctx = document.getElementById('skillRadar').getContext('2d');
        new Chart(ctx, {
            type: 'radar',
            data: {
                labels: [
                    'Python',
                    'Node.js',
                    'php',
                    'Html',
                    'Css',
                    'Java Script',
                    'C',
                    'Flutter',
                    'Figma',
                ],
                datasets: [{
                    label: 'My Skills',
                    data: [95, 60, 50, 90, 85, 85, 60, 80, 50],
                    fill: true,
                    backgroundColor: 'rgba(255, 136, 0, 0.3)',
                    borderColor: '#ff8a00',
                    pointBackgroundColor: '#ff8a00',
                    pointBorderColor: '#fff',
                    pointHoverBackgroundColor: '#fff',
                    pointHoverBorderColor: '#ff8a00',
                    borderWidth: 2
                }]
            },
            options: {
                responsive: true,
                scales: {
                    r: {
                        angleLines: { color: '#444' },
                        grid: { color: '#333' },
                        suggestedMin: 0,
                        suggestedMax: 100,
                        ticks: { display: false },
                        pointLabels: { color: 'white', font: { size: 14 } }
                    }
                },
                plugins: {
                    legend: {
                        labels: { color: 'white' }
                    },
                    tooltip: {
                        callbacks: {
                            label: function (context) {
                                const value = context.raw;
                                let level = '';
                                if (value <= 50) {
                                    level = 'Beginner';
                                } else if (value <= 80) {
                                    level = 'Intermediate';
                                } else {
                                    level = 'Advanced';
                                }
                                return `${level} (${value})`;
                            }
                        }
                    }
                }
            }
        });
    </script>


</body>

</html>

---
### Notable Projects :

- **TRINETRA** – INDIA'S First AI Tool for Combate Misinformation.
- **V.A.S.U.** – Virtual Assitant with next level OS integration.
- **V.I.D.Y.A.** – A deep-learning intelligence for limitless understanding.

### Other Projects :

- **P.A.R.T.I.C.L.E.** – A modular virtual OS core for intelligent assistants.
- **Classsight Pilot** – AI-Based Automatic Report & Document Generator.
- **SkyWave Flights** – A modular virtual OS core for intelligent assistants.

- **College Hackathon Projects**<br>
– **Gen AI Exchange Hackathon 2025** – AI-Based Tool for Combate Misinformation.<br>
– **SIH Hackathon 2025** – TrueHealth Network - A Digital Bridge Across the Entire Healthcare System.<br>
– **SSIP Hackathon 2025** – FactWeb AI - AI-Based Help Bot for Information Retrieval from Web Content.<br>
– **ImpactThon 2025** – Programmable Atomic Radial Task Interface & Command Logic Engine.


---
### Connect with me :

<p align="center" style="margin-bottom: 50px;">
    <a href="https://instagram.com/jaymeen_vaghela_264" target="_blank">
        <img src="https://img.shields.io/badge/Instagram-ff0000?style=for-the-badge&logo=instagram&logoColor=white" />
    </a>
    <a href="https://www.linkedin.com/in/jaymeen-vaghela" target="_blank">
        <img src="https://img.shields.io/badge/LinkedIn-0077b5?style=for-the-badge&logo=linkedin&logoColor=white" />
    </a>
    <a href="mailto:jaymeenvaghela07@gmail.com" target="_blank">
        <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
    </a>
    <a href="https://github.com/jaymeen07-r" target="_blank">
        <img src="https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white" />
    </a>
</p>


---
