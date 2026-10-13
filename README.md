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

[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/platane/platane/main.yml?label=action&style=flat-square)](https://github.com/Platane/Platane/actions/workflows/main.yml)
[![GitHub release](https://img.shields.io/github/release/platane/snk.svg?style=flat-square)](https://github.com/platane/snk/releases/latest)
[![GitHub marketplace](https://img.shields.io/badge/marketplace-snake-blue?logo=github&style=flat-square)](https://github.com/marketplace/actions/generate-snake-game-from-github-contribution-grid)
![type definitions](https://img.shields.io/npm/types/typescript?style=flat-square)
![code style](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)

Generates a snake game from a github user contributions graph

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg"
  />
  <img
    alt="github contribution grid snake animation"
    src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg"
  />
</picture>

Pull a github user's contribution graph.
Make it a snake Game, generate a snake path where the cells get eaten in an orderly fashion.

Generate a [gif](https://github.com/Platane/snk/raw/output/github-contribution-grid-snake.gif) or [svg](https://github.com/Platane/snk/raw/output/github-contribution-grid-snake.svg) image. Colors can [be](https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-ocean.svg) [customized](https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-grey.svg).

Available as github action. It can automatically generate a new image each day. Which makes for great [github profile readme](https://docs.github.com/en/free-pro-team@latest/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme)

## Usage

### **github action**

```yaml
- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:           A preset of color, one of [github, github-dark, github-light]
    #  - color_snake:       Color of the snake
    #  - color_dots:        Coma separated list of dots color.
    #                       The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                       Exactly 5 colors are expected.
    #  - color_background:  Color of the background (for gif only)
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9&color_background=#aaaaaa
```

[example with cron job](https://github.com/Platane/Platane/blob/master/.github/workflows/main.yml#L26-L33)

### **svg**

If you are only interested in generating a svg (not a gif), consider using this faster action: `uses: Platane/snk/svg-only@v3`

### **dark mode**

![dark mode](https://github.com/user-attachments/assets/6b900b64-0cdc-43f0-a234-e11dba8e786e)

For **dark mode** support on github, use this [special syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#specifying-the-theme-an-image-is-shown-to) in your readme.

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="github-snake.svg" />
  <img alt="github-snake" src="github-snake.svg" />
</picture>
```

### **interactive demo**

<a href="https://platane.github.io/snk">
  <img height="300px" src="https://user-images.githubusercontent.com/1659820/121798244-7c86d700-cc25-11eb-8c1c-b8e65556ac0d.gif" ></img>
</a>

[platane.github.io/snk](https://platane.github.io/snk)

### **npm package**

```ts
import { generateSnakeAnimation } from "generate-snake-animation";

const outputs = [
  {
    format: "svg",
    drawOptions: {
      // ..
    },
  },
];

const results = await generateSnakeAnimation(
  {
    platform: "github", // supports github, gitlab and forgejo (codeberg)
    username: "platane",
    githubToken: process.env.GITHUB_TOKEN,
  },
  outputs,
);

fs.writeFileSync("snake.svg", results[0]);
```

or with npx

```sh
npx generate-snake-animation@3 --forgejo_user codeberg.org/JasterV --output snake.svg?palette=codeberg
```

## Implementation

[solver algorithm](./packages/solver/README.md)

## Contribution Policy

This project does not accept pull request.

Reporting or fixing issues is appreciated, but change in the API or implementation should be discussed in issue first and is likely not going be greenlighted.


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
