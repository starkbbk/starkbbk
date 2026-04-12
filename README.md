<svg xmlns="http://www.w3.org/2000/svg" width="1000" height="220" viewBox="0 0 1000 220">
  <defs>
    <radialGradient id="bg" cx="50%" cy="50%" r="70%">
      <stop offset="0%" style="stop-color:#0a0a2e"/>
      <stop offset="50%" style="stop-color:#1a0533"/>
      <stop offset="100%" style="stop-color:#000000"/>
    </radialGradient>
    <radialGradient id="glow1">
      <stop offset="0%" style="stop-color:#ff00ff;stop-opacity:0.3"/>
      <stop offset="100%" style="stop-color:#ff00ff;stop-opacity:0"/>
    </radialGradient>
    <radialGradient id="glow2">
      <stop offset="0%" style="stop-color:#00ffff;stop-opacity:0.2"/>
      <stop offset="100%" style="stop-color:#00ffff;stop-opacity:0"/>
    </radialGradient>
  </defs>

  <!-- Background -->
  <rect width="1000" height="220" fill="url(#bg)"/>
  
  <!-- Nebula Glow -->
  <ellipse cx="250" cy="110" rx="200" ry="100" fill="url(#glow1)"/>
  <ellipse cx="750" cy="100" rx="180" ry="90" fill="url(#glow2)"/>
  
  <!-- ⭐ Twinkling Stars -->
  <circle cx="50" cy="30" r="1.5" fill="white">
    <animate attributeName="opacity" values="0.2;1;0.2" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="150" cy="60" r="1" fill="white">
    <animate attributeName="opacity" values="0.3;1;0.3" dur="1.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="250" cy="20" r="2" fill="#00ffff">
    <animate attributeName="opacity" values="0.1;1;0.1" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="350" cy="80" r="1" fill="white">
    <animate attributeName="opacity" values="0.4;1;0.4" dur="1.8s" repeatCount="indefinite"/>
  </circle>
  <circle cx="450" cy="15" r="1.5" fill="#ff00ff">
    <animate attributeName="opacity" values="0.2;1;0.2" dur="2.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="550" cy="50" r="1" fill="white">
    <animate attributeName="opacity" values="0.5;1;0.5" dur="1.2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="650" cy="25" r="2" fill="#00ffff">
    <animate attributeName="opacity" values="0.1;1;0.1" dur="2.8s" repeatCount="indefinite"/>
  </circle>
  <circle cx="750" cy="70" r="1" fill="white">
    <animate attributeName="opacity" values="0.3;1;0.3" dur="1.6s" repeatCount="indefinite"/>
  </circle>
  <circle cx="850" cy="35" r="1.5" fill="#ff00ff">
    <animate attributeName="opacity" values="0.2;1;0.2" dur="2.2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="950" cy="55" r="1" fill="white">
    <animate attributeName="opacity" values="0.4;1;0.4" dur="1.4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="100" cy="150" r="1" fill="white">
    <animate attributeName="opacity" values="0.3;1;0.3" dur="2.1s" repeatCount="indefinite"/>
  </circle>
  <circle cx="200" cy="180" r="1.5" fill="#00ffff">
    <animate attributeName="opacity" values="0.2;1;0.2" dur="1.7s" repeatCount="indefinite"/>
  </circle>
  <circle cx="300" cy="160" r="1" fill="white">
    <animate attributeName="opacity" values="0.5;1;0.5" dur="2.3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="400" cy="190" r="2" fill="#ff00ff">
    <animate attributeName="opacity" values="0.1;1;0.1" dur="1.9s" repeatCount="indefinite"/>
  </circle>
  <circle cx="500" cy="170" r="1" fill="white">
    <animate attributeName="opacity" values="0.4;1;0.4" dur="2.6s" repeatCount="indefinite"/>
  </circle>
  <circle cx="600" cy="200" r="1.5" fill="white">
    <animate attributeName="opacity" values="0.2;1;0.2" dur="1.3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="700" cy="185" r="1" fill="#00ffff">
    <animate attributeName="opacity" values="0.3;1;0.3" dur="2.4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="800" cy="165" r="2" fill="white">
    <animate attributeName="opacity" values="0.1;1;0.1" dur="1.8s" repeatCount="indefinite"/>
  </circle>
  <circle cx="900" cy="195" r="1" fill="#ff00ff">
    <animate attributeName="opacity" values="0.5;1;0.5" dur="2.7s" repeatCount="indefinite"/>
  </circle>
  <circle cx="80" cy="100" r="1.5" fill="white">
    <animate attributeName="opacity" values="0.2;1;0.2" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="920" cy="120" r="1" fill="white">
    <animate attributeName="opacity" values="0.4;1;0.4" dur="1.5s" repeatCount="indefinite"/>
  </circle>

  <!-- 🪐 Planet 1 (Small, Purple) -->
  <circle cx="120" cy="60" r="8" fill="#6a0dad" opacity="0.7">
    <animate attributeName="cx" values="120;130;120" dur="6s" repeatCount="indefinite"/>
  </circle>
  <ellipse cx="120" cy="60" rx="14" ry="3" fill="none" stroke="#9b59b6" stroke-width="1" opacity="0.5">
    <animate attributeName="cx" values="120;130;120" dur="6s" repeatCount="indefinite"/>
  </ellipse>

  <!-- 🪐 Planet 2 (Small, Cyan) -->
  <circle cx="880" cy="50" r="6" fill="#00bcd4" opacity="0.6">
    <animate attributeName="cy" values="50;60;50" dur="5s" repeatCount="indefinite"/>
  </circle>

  <!-- 🪐 Planet 3 (Tiny, Pink) -->
  <circle cx="50" cy="180" r="4" fill="#e91e63" opacity="0.5">
    <animate attributeName="cx" values="50;60;50" dur="7s" repeatCount="indefinite"/>
    <animate attributeName="cy" values="180;170;180" dur="7s" repeatCount="indefinite"/>
  </circle>

  <!-- 🪐 Planet 4 (Right side) -->
  <circle cx="950" cy="170" r="5" fill="#ff9800" opacity="0.5">
    <animate attributeName="cy" values="170;160;170" dur="4s" repeatCount="indefinite"/>
  </circle>

  <!-- ☄️ Shooting Star 1 -->
  <line x1="0" y1="0" x2="60" y2="30" stroke="white" stroke-width="1" opacity="0">
    <animate attributeName="opacity" values="0;0;0.8;0" dur="4s" repeatCount="indefinite" begin="0s"/>
    <animate attributeName="x1" values="200;350" dur="4s" repeatCount="indefinite" begin="0s"/>
    <animate attributeName="y1" values="10;60" dur="4s" repeatCount="indefinite" begin="0s"/>
    <animate attributeName="x2" values="230;380" dur="4s" repeatCount="indefinite" begin="0s"/>
    <animate attributeName="y2" values="20;70" dur="4s" repeatCount="indefinite" begin="0s"/>
  </line>

  <!-- ☄️ Shooting Star 2 -->
  <line x1="0" y1="0" x2="50" y2="25" stroke="#00ffff" stroke-width="1" opacity="0">
    <animate attributeName="opacity" values="0;0;0.9;0" dur="5s" repeatCount="indefinite" begin="2s"/>
    <animate attributeName="x1" values="600;750" dur="5s" repeatCount="indefinite" begin="2s"/>
    <animate attributeName="y1" values="20;70" dur="5s" repeatCount="indefinite" begin="2s"/>
    <animate attributeName="x2" values="630;780" dur="5s" repeatCount="indefinite" begin="2s"/>
    <animate attributeName="y2" values="30;80" dur="5s" repeatCount="indefinite" begin="2s"/>
  </line>

  <!-- Main Text -->
  <text x="500" y="95" text-anchor="middle" font-family="'Segoe UI', Arial, sans-serif" font-size="42" font-weight="bold" fill="#00ffff">
    Hey I'm Shivanand 👋
  </text>
  
  <!-- Subtitle -->
  <text x="500" y="140" text-anchor="middle" font-family="'Fira Code', monospace" font-size="18" fill="#ff00ff">
    Full Stack Developer | Backend Engineer | Problem Solver
  </text>

  <!-- Bottom wave -->
  <path d="M0,200 Q250,170 500,200 T1000,200 L1000,220 L0,220 Z" fill="#0D1117" opacity="0.8"/>
</svg>
<!-- TYPING SVG -->
<div align="center">

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=26&duration=3000&pause=1000&color=00FFFF&center=true&vCenter=true&width=700&height=60&lines=Full+Stack+Developer+%7C+Backend+Engineer;600%2B+LeetCode+Problems+Solved;Amazon+ML+Summer+School+2025+Selectee;Building+Systems+That+Scale!)](https://git.io/typing-svg)

<img src="https://komarev.com/ghpvc/?username=starkbbk&label=Profile%20Views&color=blueviolet&style=for-the-badge" alt="Profile Views"/>
<a href="https://github.com/starkbbk?tab=followers"><img src="https://img.shields.io/github/followers/starkbbk?label=Followers&style=for-the-badge&color=red&logo=github&logoColor=white" alt="Followers"/></a>
<a href="https://github.com/starkbbk?tab=repositories&sort=stargazers"><img src="https://img.shields.io/github/stars/starkbbk?label=Total%20Stars&style=for-the-badge&color=gold&logo=github" alt="Stars"/></a>

</div>

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" />

<!-- ═══════════════════ ABOUT ME ═══════════════════ -->

<img align="right" alt="Coding" width="400" src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif"/>

## 🧑‍💻 About Me

- 🎓 **B.Tech CSE (AI & ML)** — PSIT Kanpur | CGPA: 8.1/10
- 🧠 **Amazon ML Summer School 2025** — Top Nationwide Selectee
- 💻 **600+ LeetCode** | **5⭐ HackerRank** (Problem Solving & C++)
- 🎓 **Stanford ML Certified** (Coursera)
- ☁️ **Salesforce** Adventurer & Agentblazer Champion
- 📜 **Infosys Springboard** — DBMS Certified
- 🔭 Currently building **workflow automation** & **AI tools**
- 📫 Reach me at **starkbbk@gmail.com**

<br clear="both"/>

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" />

<!-- ═══════════════════ TECH STACK ═══════════════════ -->

<div align="center">

## ⚡ Tech Stack!

### 🧠 Languages
<table><tr><td align="center" width="96"><img src="https://techstack-generator.vercel.app/cpp-icon.svg" width="65" height="65" /><br/>C++</td><td align="center" width="96"><img src="https://techstack-generator.vercel.app/python-icon.svg" width="65" height="65" /><br/>Python</td><td align="center" width="96"><img src="https://techstack-generator.vercel.app/java-icon.svg" width="65" height="65" /><br/>Java</td><td align="center" width="96"><img src="https://techstack-generator.vercel.app/js-icon.svg" width="65" height="65" /><br/>JavaScript</td><td align="center" width="96"><img src="https://techstack-generator.vercel.app/ts-icon.svg" width="65" height="65" /><br/>TypeScript</td><td align="center" width="96"><img src="https://techstack-generator.vercel.app/mysql-icon.svg" width="65" height="65" /><br/>SQL</td></tr></table>

### 🎨 Frontend
<table><tr><td align="center" width="96"><img src="https://techstack-generator.vercel.app/react-icon.svg" width="65" height="65" /><br/>React</td><td align="center" width="96"><img src="https://techstack-generator.vercel.app/redux-icon.svg" width="65" height="65" /><br/>Redux</td><td align="center" width="96"><img src="https://techstack-generator.vercel.app/sass-icon.svg" width="65" height="65" /><br/>Sass</td><td align="center" width="96"><img src="https://techstack-generator.vercel.app/webpack-icon.svg" width="65" height="65" /><br/>Webpack</td><td align="center" width="96"><img src="https://techstack-generator.vercel.app/prettier-icon.svg" width="65" height="65" /><br/>Prettier</td><td align="center" width="96"><img src="https://techstack-generator.vercel.app/eslint-icon.svg" width="65" height="65" /><br/>ESLint</td></tr></table>

### ⚙️ Backend & Database
<table><tr><td align="center" width="96"><img src="https://techstack-generator.vercel.app/restapi-icon.svg" width="65" height="65" /><br/>REST API</td><td align="center" width="96"><img src="https://techstack-generator.vercel.app/graphql-icon.svg" width="65" height="65" /><br/>GraphQL</td><td align="center" width="96"><img src="https://techstack-generator.vercel.app/mysql-icon.svg" width="65" height="65" /><br/>MySQL</td><td align="center" width="96"><img src="https://techstack-generator.vercel.app/nginx-icon.svg" width="65" height="65" /><br/>Nginx</td></tr></table>

### ☁️ DevOps & Cloud
<table><tr><td align="center" width="96"><img src="https://techstack-generator.vercel.app/docker-icon.svg" width="65" height="65" /><br/>Docker</td><td align="center" width="96"><img src="https://techstack-generator.vercel.app/kubernetes-icon.svg" width="65" height="65" /><br/>Kubernetes</td><td align="center" width="96"><img src="https://techstack-generator.vercel.app/aws-icon.svg" width="65" height="65" /><br/>AWS</td><td align="center" width="96"><img src="https://techstack-generator.vercel.app/github-icon.svg" width="65" height="65" /><br/>GitHub</td></tr></table>

<br/>

### 🧰 Complete Toolkit

<a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=cpp,python,java,js,ts,react,nextjs,tailwind,html,css,vite,redux&perline=12&theme=dark" /></a>
<br/>
<a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=fastapi,nodejs,express,redis,postgres,mysql,mongodb,firebase,graphql,docker,kubernetes,aws&perline=12&theme=dark" /></a>
<br/>
<a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=git,github,vercel,linux,vscode,postman,figma,bootstrap,materialui,heroku,netlify,cloudflare&perline=12&theme=dark" /></a>

</div>

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" />

<!-- ═══════════════════ PROJECTS ═══════════════════ -->

<div align="center">

## 🚀 Featured Projects

</div>

<table align="center">
  <tr>
    <td width="50%">
      <h3 align="center">⚡ FlowCron</h3>
      <p align="center">
        <a href="https://flowcron.vercel.app/" target="_blank"><img src="https://img.shields.io/badge/LIVE%20DEMO-🟢-brightgreen?style=for-the-badge" /></a>
        <a href="https://github.com/starkbbk/FlowCron" target="_blank"><img src="https://img.shields.io/badge/CODE-🔗-blue?style=for-the-badge&logo=github" /></a>
      </p>
      <p align="center"><strong>Visual Workflow Automation Platform</strong></p>
      <p align="center">
        <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
        <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
        <img src="https://img.shields.io/badge/WebSocket-010101?style=flat-square&logo=socket.io&logoColor=white" />
        <img src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white" />
      </p>
      <p>
        ✦ Drag-and-drop editor with <b>15+ node types</b><br/>
        ✦ DAG execution with <b>topological sorting</b><br/>
        ✦ Real-time <b>WebSocket streaming</b><br/>
        ✦ <b>500+ daily executions</b> at 99% reliability<br/>
        ✦ <b>25+ REST endpoints</b> with JWT auth<br/>
        ✦ Deployed on <b>Vercel + Railway</b> with CI/CD
      </p>
    </td>
    <td width="50%">
      <h3 align="center">🧰 ToolboxHub</h3>
      <p align="center">
        <a href="http://lost-and-found-0lwo.onrender.com/" target="_blank"><img src="https://img.shields.io/badge/LIVE%20DEMO-🟢-brightgreen?style=for-the-badge" /></a>
        <a href="https://github.com/starkbbk/ToolBoxHub" target="_blank"><img src="https://img.shields.io/badge/CODE-🔗-blue?style=for-the-badge&logo=github" /></a>
      </p>
      <p align="center"><strong>AI Productivity Suite</strong></p>
      <p align="center">
        <img src="https://img.shields.io/badge/Next.js_14-000000?style=flat-square&logo=next.js&logoColor=white" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
        <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
        <img src="https://img.shields.io/badge/Stripe-008CDD?style=flat-square&logo=stripe&logoColor=white" />
        <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwind-css&logoColor=white" />
      </p>
      <p>
        ✦ <b>6+ AI-powered tools</b> in one platform<br/>
        ✦ Video highlighter with <b>Groq Whisper</b><br/>
        ✦ <b>Stripe</b> tiered subscriptions<br/>
        ✦ AI Text Remover with <b>EasyOCR</b><br/>
        ✦ Batch compression & <b>300 DPI PDF</b><br/>
        ✦ Real-time transcription & highlights
      </p>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <h3 align="center">🛡️ AIX-Scanner — AI Code Vulnerability Scanner</h3>
      <p align="center">
        <a href="https://ai-code-vulnerability-scanner.vercel.app/scan" target="_blank"><img src="https://img.shields.io/badge/LIVE%20DEMO-🟢-brightgreen?style=for-the-badge" /></a>
        <a href="https://github.com/starkbbk/AI-Code-Vulnerability-Scanner" target="_blank"><img src="https://img.shields.io/badge/CODE-🔗-blue?style=for-the-badge&logo=github" /></a>
      </p>
      <p align="center">
        <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
        <img src="https://img.shields.io/badge/CodeBERT-FF6F00?style=flat-square&logo=huggingface&logoColor=white" />
        <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
      </p>
      <p align="center">
        ✦ Hybrid: <b>CodeBERT + static analysis</b> · ✦ <b>94% accuracy</b> across <b>26+ vulnerabilities</b> · ✦ Auto-fix reducing time by <b>85%</b> · ✦ Monaco Editor + PDF reports · ✦ <b>10K+ records</b>
      </p>
    </td>
  </tr>
</table>

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" />

<!-- ═══════════════════ GITHUB STATS ═══════════════════ -->

<div align="center">

## 📊 GitHub Stats

<p>
  <img width="49%" src="https://github-readme-stats-sigma-five.vercel.app/api?username=starkbbk&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=00FFFF&icon_color=FF00FF&ring_color=00FFFF&count_private=true" alt="Stats"/>
  <img width="49%" src="https://streak-stats.demolab.com/?user=starkbbk&theme=radical&hide_border=true&background=0D1117&stroke=00FFFF&ring=00FFFF&fire=FF00FF&currStreakLabel=00FFFF&sideLabels=00FFFF" alt="Streak"/>
</p>

<img width="40%" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=starkbbk&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=00FFFF" alt="Languages"/>

<br/><br/>

<img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=starkbbk&bg_color=0D1117&color=00FFFF&line=FF00FF&point=FFFFFF&area_color=00FFFF&area=true&hide_border=true&custom_title=Shivanand's%20Contribution%20Graph" alt="Graph"/>

</div>

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" />

<!-- ═══════════════════ SNAKE ═══════════════════ -->

<div align="center">

## 🐍 Watch My Contributions Get Eaten!

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/starkbbk/starkbbk/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/starkbbk/starkbbk/output/github-snake.svg" />
  <img alt="snake" src="https://raw.githubusercontent.com/starkbbk/starkbbk/output/github-snake-dark.svg" />
</picture>

</div>

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" />

<!-- ═══════════════════ ACHIEVEMENTS ═══════════════════ -->

<div align="center">

## 🏆 Achievements & Certifications

| 🏆 Achievement | 📝 Details |
|:---|:---|
| 🧠 **Amazon ML Summer School 2025** | Selected among top applicants nationwide — ML, NLP, CV, RL |
| 💻 **Competitive Programming** | **600+** LeetCode problems solved · **5⭐** Problem Solving & C++ on HackerRank |
| 🎓 **Stanford University (Coursera)** | Unsupervised Learning, Recommenders & Reinforcement Learning |
| ☁️ **Salesforce Trailhead** | Adventurer & Agentblazer Champion Badge Holder |
| 📜 **Infosys Springboard** | Certified in Database Management Systems |

</div>

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" />

<!-- ═══════════════════ TROPHIES ═══════════════════ -->

<div align="center">

## 🏅 GitHub Trophies

<img src="https://github-profile-trophy.vercel.app/?username=starkbbk&theme=algolia&no-frame=true&no-bg=true&margin-w=10&column=7" />

</div>

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" />

<!-- ═══════════════════ QUOTE ═══════════════════ -->

<div align="center">

## 💭 Random Dev Quote

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical" />

</div>

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" />

<!-- ═══════════════════ CONNECT ═══════════════════ -->

<div align="center">

## 🤝 Let's Connect!

<a href="https://www.linkedin.com/in/starkbbk" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://github.com/starkbbk" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="https://leetcode.com/u/starkbbk" target="_blank"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" /></a>
<a href="https://liqui-folio.vercel.app/" target="_blank"><img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white" /></a>
<a href="mailto:starkbbk@gmail.com" target="_blank"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>

<br/><br/>

<img src="https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f15b36f63.gif" width="500" />

<br/>

<img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" width="400" />

</div>

<!-- NEON SPACE FOOTER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,2,19,24,3&height=120&section=footer" width="100%"/>
