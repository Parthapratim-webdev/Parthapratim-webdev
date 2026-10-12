<h1 align="center">
  ⚡ Hey, I'm Partha Pratim Mallick ⚡
</h1>

<h3 align="center">
  💻 Full Stack Developer • Problem Solver • Hackathon Enthusiast
</h3>
<p align="center">
  <img src="https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white"/>
</p>

<p align="center">
  <a href="mailto:YOUR-EMAIL">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://github.com/YOUR-USERNAME">
    <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white"/>
  </a>
  <a href="YOUR-LINKEDIN-URL">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"/>
  </a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=3000&pause=1000&center=true&vCenter=true&width=600&lines=Full+Stack+Developer;DSA+Problem+Solver;Hackathon+Enthusiast;Building+Real-World+Projects" />
</p>

---

## 👨‍💻 About Me

I'm a Computer Science student and Full Stack Developer passionate
about building practical and user-friendly applications.

I enjoy solving DSA problems, developing web projects,
participating in hackathons, and learning new technologies.

Currently, I'm focusing on Full Stack Development,
problem solving, and real-world projects.

<h2 align="center">💻 Code. Create. Innovate. 🚀</h2>

<h2 align="center">💻 Coding in Progress</h2>

<img width="900" height="600" alt="coding-boy" src="https://github.com/user-attachments/assets/ebe7158a-668a-4c80-9a0f-784f65f047be" />
<p align="center">
  <img src="./coding-boy.gif"
       alt="Developer coding on a laptop"
       width="750">

  ---

<h2 align="center">🐍 Contribution Snake</h2>

<p align="center">
  <img
    src="https://raw.githubusercontent.com/YOUR-USERNAME/Parthapratim-webdevE/output/github-snake.svg"
    alt="GitHub Contribution Snake"
    width="100%"
  />
</p>

---
</p>
name: Generate Contribution Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  generate:
    runs-on: ubuntu-latest

    permissions:
      contents: write

    steps:
      - name: Generate Snake Animation
        uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-snake.svg?palette=github-dark
            dist/github-snake.gif?color_snake=#39d353&color_dots=#161b22,#0e4429,#006d32,#26a641,#39d353

      - name: Publish Snake Animation
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

## 🏆 Achievements

- 💻 Solved 300+ DSA problems on LeetCode
- 🏅 LeetCode 100 Days Coding
- 🚀 Participated in Smart India Hackathon
- 🌐 Built multiple web development projects
- 📚 Continuously learning Full Stack Development

---

## 🛠️ What I Do

- 🌐 Build responsive web applications
- 💻 Develop frontend interfaces
- ⚙️ Build backend applications
- 🧠 Solve DSA problems
- 🚀 Develop hackathon projects
- 🔧 Work with APIs and databases

---

## 💻 Languages

<p>
  <img src="https://skillicons.dev/icons?i=c,cpp,python,js" />
</p>

## 🎨 Frontend

<p>
  <img src="https://skillicons.dev/icons?i=html,css,js,react" />
</p>

## ⚙️ Backend

<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express,flask" />
</p>

## 🗄️ Database

<p>
  <img src="https://skillicons.dev/icons?i=mysql,mongodb,firebase" />
</p>

## ☁️ Cloud & Tools

<p>
  <img src="https://skillicons.dev/icons?i=aws,git,github,vscode" />
</p>

---

## 🚀 Featured Projects

### 🎵 Music Playlist Website
Spotify-inspired music playlist frontend.

### 📷 Camera Web Application
A browser-based camera application.

### 📊 Smart Attendance System
A web-based attendance management project.

### 🏥 MediGuide AI
An AI-assisted healthcare platform project.

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Parthapratim-webdev&show_icons=true&theme=tokyonight" />
</p>

## 🔥 GitHub Streak

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Parthapratim-webdev&theme=tokyonight" />
</p>

---

## 🌐 Connect With Me

<p align="center">
  <a href="https://github.com/Parthapratim-webdev">
    GitHub
  </a>
  •
  <a href="https://www.linkedin.com/in/partha-pratim-mallick-5917183a8/">
    LinkedIn
  </a>
</p>

---

<p align="center">
  ⭐ Thanks for visiting my profile!
</p>
