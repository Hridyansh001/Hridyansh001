<div align="center">

<!-- Animated banner with wave effect -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Hey%2C%20I'm%20%5BYourName%5D%20👋&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Student%20Developer%20%7C%20Backend%20%7C%20Frontend%20%7C%20Fullstack&descAlignY=58&descSize=18&animation=fadeIn" />

<!-- Typing animation -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=A78BFA&center=true&vCenter=true&width=600&lines=Building+real+things+while+learning+%F0%9F%92%AA;Backend+%7C+Frontend+%7C+Fullstack+Dev;Open+Source+Enthusiast;CS+Student+on+a+mission+%F0%9F%9A%80" alt="Typing SVG" />
</a>

<br/>

<!-- Social badges -->
[![GitHub followers](https://img.shields.io/github/followers/yourusername?label=Follow&style=for-the-badge&color=7c3aed&labelColor=1e1b4b&logo=github)](https://github.com/yourusername)
[![Profile Views](https://komarev.com/ghpvc/?username=yourusername&style=for-the-badge&color=7c3aed&label=Profile+Views)](https://github.com/yourusername)
[![Discord](https://img.shields.io/badge/Discord-yourtag-7c3aed?style=for-the-badge&logo=discord&logoColor=white&labelColor=1e1b4b)](https://discord.com)

</div>

---

## 🧠 About Me

```yaml
name: "[Your Name]"
role: "Student Developer"
focus: ["Backend Development", "Frontend", "Fullstack Engineering"]
currently_learning: ["Node.js", "Express", "React", "Databases", "REST APIs"]
building: "ShadowGuard — AI Security Platform"
open_to: ["Collaborations", "Open Source", "Internships"]
fun_fact: "I debug with console.log and I'm not sorry about it 😂"
```

I'm a passionate student developer learning the ropes of **backend**, **frontend**, and **fullstack** development — one project at a time. I love building things that actually solve real problems, and I'm not afraid to get my hands dirty exploring new tech stacks.

Right now I'm deep into web security, APIs, databases, and everything in between. My biggest project so far is **ShadowGuard**, an AI-powered security platform I built to solve a real and growing problem in the age of AI tools.

---

## 🛡️ Featured Project — ShadowGuard

<div align="center">

```
███████╗██╗  ██╗ █████╗ ██████╗  ██████╗ ██╗    ██╗ ██████╗ ██╗   ██╗ █████╗ ██████╗ ██████╗
██╔════╝██║  ██║██╔══██╗██╔══██╗██╔═══██╗██║    ██║██╔════╝ ██║   ██║██╔══██╗██╔══██╗██╔══██╗
███████╗███████║███████║██║  ██║██║   ██║██║ █╗ ██║██║  ███╗██║   ██║███████║██████╔╝██║  ██║
╚════██║██╔══██║██╔══██║██║  ██║██║   ██║██║███╗██║██║   ██║██║   ██║██╔══██║██╔══██╗██║  ██║
███████║██║  ██║██║  ██║██████╔╝╚██████╔╝╚███╔███╔╝╚██████╔╝╚██████╔╝██║  ██║██║  ██║██████╔╝
╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝╚═════╝  ╚═════╝  ╚══╝╚══╝  ╚═════╝  ╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝╚═════╝
```

[![ShadowGuard License](https://img.shields.io/badge/License-MIT-7c3aed?style=for-the-badge&labelColor=1e1b4b)](./LICENSE)
[![Status](https://img.shields.io/badge/Status-Active%20Development-22c55e?style=for-the-badge&labelColor=1e1b4b)](https://github.com/yourusername/shadowguard)
[![Made with](https://img.shields.io/badge/Made%20with-Node.js%20%7C%20React-f59e0b?style=for-the-badge&labelColor=1e1b4b)](https://github.com/yourusername/shadowguard)

</div>

> **ShadowGuard** is a real-time AI security platform that prevents sensitive data leakage by scanning user prompts and uploaded documents before they are sent to AI services.

### 🔍 What it does

| Feature | Description |
|---|---|
| 🔑 **API Key Detection** | Automatically scans and flags exposed API keys and tokens |
| 🔒 **Password Scanner** | Detects hardcoded passwords and credentials in prompts |
| 🪪 **PII Detection** | Identifies personal identifiers (names, emails, phone numbers, SSNs) |
| 🗄️ **Database Credential Guard** | Catches database connection strings and credentials |
| 🎭 **Content Masking** | Masks sensitive content before it reaches AI services |
| 📋 **Incident Logging** | Logs every security event with timestamps and severity levels |
| 📊 **Admin Dashboard** | Real-time monitoring and analysis interface for administrators |
| 📄 **Document Scanner** | Scans uploaded documents (PDF, DOCX, TXT) for sensitive data |

### 🏗️ Architecture

```
┌─────────────────────────────────────────────────────────────────────┐
│                        ShadowGuard Platform                         │
│                                                                     │
│   ┌──────────────┐    ┌──────────────────┐    ┌────────────────┐   │
│   │   Frontend   │    │   Backend API    │    │  Admin Panel   │   │
│   │   (React)    │───▶│   (Node/Express) │───▶│  (Dashboard)   │   │
│   └──────────────┘    └──────────────────┘    └────────────────┘   │
│          │                     │                       │            │
│          ▼                     ▼                       ▼            │
│   ┌──────────────┐    ┌──────────────────┐    ┌────────────────┐   │
│   │   Prompt     │    │  Scanning Engine │    │   Incident     │   │
│   │   Input UI   │    │  (Regex + AI     │    │   Logger &     │   │
│   │              │    │   Pattern Match) │    │   Reporter     │   │
│   └──────────────┘    └──────────────────┘    └────────────────┘   │
│                                │                                    │
│                   ┌────────────┴────────────┐                      │
│                   │                         │                      │
│            ┌──────▼──────┐         ┌────────▼──────┐              │
│            │  Mask &     │         │  Pass to AI   │              │
│            │  Block      │         │  (if safe)    │              │
│            └─────────────┘         └───────────────┘              │
└─────────────────────────────────────────────────────────────────────┘
```

### 🛠️ Tech Stack

<div align="center">

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

</div>

### 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/yourusername/shadowguard.git

# Navigate into the project
cd shadowguard

# Install backend dependencies
npm install

# Install frontend dependencies
cd client && npm install && cd ..

# Set up environment variables
cp .env.example .env

# Start the development server
npm run dev
```

### 📁 Project Structure

```
shadowguard/
├── 📂 client/                  # React frontend
│   ├── 📂 src/
│   │   ├── 📂 components/      # Reusable UI components
│   │   ├── 📂 pages/           # Dashboard, Login, Monitor
│   │   └── 📂 hooks/           # Custom React hooks
├── 📂 server/                  # Node.js backend
│   ├── 📂 routes/              # API routes
│   ├── 📂 middleware/          # Auth, scanning middleware
│   ├── 📂 models/              # MongoDB schemas
│   ├── 📂 services/
│   │   ├── scanner.js          # Core scanning engine
│   │   ├── masker.js           # Content masking logic
│   │   └── logger.js           # Incident logging service
│   └── 📂 utils/               # Helper functions
├── 📄 .env.example
├── 📄 package.json
└── 📄 README.md
```

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=a78bfa&text_color=c9d1d9" />

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=yourusername&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&text_color=c9d1d9&langs_count=8" />

</div>

<div align="center">

<img width="90%" src="https://github-readme-streak-stats.herokuapp.com/?user=yourusername&theme=tokyonight&hide_border=true&background=0d1117&ring=a78bfa&fire=f59e0b&currStreakLabel=a78bfa&sideLabels=c9d1d9&dates=c9d1d9&currStreakNum=ffffff&sideNums=ffffff" />

</div>

<div align="center">

<img width="90%" src="https://github-readme-activity-graph.vercel.app/graph?username=yourusername&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=a78bfa&line=7c3aed&point=f59e0b" />

</div>

---

## 🧰 Tech Stack & Tools

<div align="center">

### Languages
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Backend
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20API-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

### Databases
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### Tools & DevOps
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</div>

---

## 📂 My Projects

<div align="center">

| Project | Description | Tech | Status |
|---|---|---|---|
| 🛡️ **[ShadowGuard](https://github.com/yourusername/shadowguard)** | Real-time AI security platform that prevents sensitive data leakage | Node.js, React, MongoDB | 🟢 Active |
| 🔗 **[Project Two](https://github.com/yourusername/project-two)** | A short description of what this project does | Express, MySQL | 🟡 Building |
| 📦 **[Project Three](https://github.com/yourusername/project-three)** | A short description of what this project does | React, Firebase | 🟢 Active |
| 🧪 **[Project Four](https://github.com/yourusername/project-four)** | A short description of what this project does | Python, Flask | 🔵 Learning |
| 🌐 **[Portfolio](https://github.com/yourusername/portfolio)** | My personal developer portfolio website | HTML, CSS, JS | 🟢 Live |

</div>

> 💡 **Tip:** Replace the project rows above with your real repos. Add your own descriptions, tech stacks, and links!

---

## 🎯 What I'm Currently Learning

```
📌 Backend Development
   ├── ✅ Node.js + Express (REST APIs, Middleware, Auth)
   ├── ✅ MongoDB + Mongoose
   ├── 🔄 SQL (MySQL, PostgreSQL)
   ├── 🔄 Redis for caching
   └── 📌 Microservices Architecture (coming next)

📌 Frontend Development
   ├── ✅ HTML, CSS, JavaScript
   ├── ✅ React.js
   ├── 🔄 TypeScript
   └── 🔄 Next.js

📌 Security & DevOps
   ├── ✅ JWT Authentication
   ├── ✅ Input validation & sanitization
   ├── 🔄 Docker basics
   └── 📌 CI/CD pipelines (coming next)
```

---

## 🏆 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=yourusername&theme=tokyonight&no-frame=true&no-bg=true&margin-w=8&column=7" />

</div>

---

## 📈 Contribution Graph

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yourusername/yourusername/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/yourusername/yourusername/output/github-contribution-grid-snake.svg" />
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/yourusername/yourusername/output/github-contribution-grid-snake.svg" />
</picture>

</div>

> 💡 To enable the snake animation, create a GitHub Actions workflow in your profile repo. [See guide here](https://github.com/Platane/snk)

---

## 💬 Dev Quote of the Day

<div align="center">

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" />

</div>

---

## 📬 Connect with Me

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yourusername)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourusername)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/yourusername)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:youremail@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-7c3aed?style=for-the-badge&logo=vercel&logoColor=white)](https://yourportfolio.dev)

</div>

---

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer&animation=fadeIn" />

**Thanks for visiting my profile!** If you find any of my projects helpful, please consider leaving a ⭐ — it genuinely means a lot to a student dev still on their journey. 🚀

*"The best way to learn is to build things that matter."*

</div>![](https://img.shields.io/badge/Spring_Boot-0D1117?style=flat-square&logo=springboot&logoColor=00D4FF)
![](https://img.shields.io/badge/PostgreSQL-0D1117?style=flat-square&logo=postgresql&logoColor=00D4FF)
![](https://img.shields.io/badge/Status-Active-00D4FF?style=flat-square&labelColor=0D1117)

</td>
<td width="50%" valign="top">

**🎯 PhishRadar**

> Smart phishing URL detection and threat classification platform

Because humans can't manually vet every suspicious link. Machines can.

```
├── URL scanning & analysis
├── Suspicious domain fingerprinting
├── Multi-class threat classification
├── RESTful API interface
└── ML integration (in progress)
```

![](https://img.shields.io/badge/Python-0D1117?style=flat-square&logo=python&logoColor=BC8CFF)
![](https://img.shields.io/badge/Java-0D1117?style=flat-square&logo=openjdk&logoColor=BC8CFF)
![](https://img.shields.io/badge/Spring-0D1117?style=flat-square&logo=spring&logoColor=BC8CFF)
![](https://img.shields.io/badge/Status-Active-BC8CFF?style=flat-square&labelColor=0D1117)

</td>
</tr>
</table>

---

## `cat tech_stack.json`

```json
{
  "languages":    ["Java", "C++", "Python", "JavaScript"],
  "backend":      ["Spring Boot", "REST APIs", "Microservices"],
  "databases":    ["PostgreSQL", "MySQL"],
  "tools":        ["Git", "GitHub", "Postman", "IntelliJ IDEA", "VS Code"],
  "learning":     ["Docker", "Linux", "System Design"],
  "focus_areas":  ["Cybersecurity", "AI Security", "Backend Engineering"]
}
```

<div align="center">
<img src="https://skillicons.dev/icons?i=java,cpp,python,js,spring,postgresql,mysql,git,github,postman,vscode,idea,docker,linux&perline=7&theme=dark" />
</div>

---

## `git log --stat`

<div align="center">

<img height="160em" src="https://github-readme-stats.vercel.app/api?username=Hridyansh001&show_icons=true&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=00D4FF&icon_color=00D4FF&text_color=8B949E&ring_color=00D4FF" />
<img height="160em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Hridyansh001&layout=compact&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=00D4FF&text_color=8B949E" />

<img width="100%" src="https://github-readme-streak-stats.herokuapp.com?user=Hridyansh001&theme=github-dark-blue&hide_border=true&background=0D1117&ring=00D4FF&fire=00D4FF&currStreakLabel=00D4FF&sideLabels=8B949E&dates=8B949E" />

<img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Hridyansh001&theme=github_dark" />

</div>

---

## `./roadmap --year 2026`

```
[ ]  Master Spring Boot & microservices architecture
[ ]  Deploy with Docker + CI/CD pipelines
[ ]  Crack GATE CSE 2027
[ ]  Ship ShadowGuard to production
[ ]  Contribute meaningful PRs to open source security tools
[ ]  Build a public API used by real people
```

---

## `tail -1 /etc/motto`

<div align="center">

```
┌──────────────────────────────────────────────────────┐
│                                                      │
│   "Those who cling to life die.                      │
│    Those who cling to death live."                   │
│                                                      │
└──────────────────────────────────────────────────────┘
```

</div>

---

## `ping me`

<div align="center">

[![GitHub](https://img.shields.io/badge/github-%40Hridyansh001-0D1117?style=for-the-badge&logo=github&logoColor=00D4FF&color=0D1117)](https://github.com/Hridyansh001)

*Open to collaborations on cybersecurity tools, backend systems, and anything that solves a real problem.*

<br/>

![snake gif](https://github.com/Hridyansh001/Hridyansh001/blob/output/github-contribution-grid-snake-dark.svg)

<br/>

```
  status  →  always building
  uptime  →  24 / 7
  fuel    →  music + cold coffee
```

**`⚔ Code. Break. Secure. Repeat. ⚔`**

</div>
