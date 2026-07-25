<h1 align="center">Hi there, I'm Anthony Nelson 👋</h1>
<h3 align="center">Full-Stack Engineer · Backend & Infrastructure</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=2EA043&center=true&vCenter=true&width=600&lines=Backend-leaning+Full-Stack+Engineer;Building+production+MERN+platforms+solo;DNS+infrastructure+from+scratch;Docker+%7C+CI%2FCD+%7C+Self-hosted+Deployments" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="mailto:anthony@anthonynelson.in"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="#" target="_blank"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" /></a>
</p>

---

### 🧭 About Me

I'm a backend-leaning full-stack engineer who's been building and shipping **real products** — not just side projects. I've singlehandedly architected, deployed, and maintained a production MERN platform, built DNS infrastructure from scratch, containerized deployment pipelines, and automated everything from backups to CI/CD.

I genuinely enjoy the infrastructure side of things as much as the code itself. 🐳🔧

- 🔭 Currently building the internal platform at **Ocellus Business & Services** as the sole engineer
- 🌱 Deep into DNS systems, container orchestration, and self-hosted infra
- ⚡ Deploy via `git push` — CI/CD with GitHub Actions + Watchtower
- 📍 Based in Mumbai, India

---

### 🛠️ Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Redux%20Toolkit-764ABC?style=flat-square&logo=redux&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
  <br/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/BullMQ-CC0000?style=flat-square" />
  <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" />
  <br/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/BIND9-8A2BE2?style=flat-square" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/Cloudflare%20Tunnel-F38020?style=flat-square&logo=cloudflare&logoColor=white" />
  <br/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" />
  <img src="https://img.shields.io/badge/Puppeteer-40B5A4?style=flat-square&logo=puppeteer&logoColor=white" />
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white" />
</p>

---

### 💼 Experience

**Software Developer** · Ocellus Business & Services, Mumbai — *Apr 2026 – Present*
- Sole engineer on the team — built an internal MERN platform from scratch, including an admin panel with 20+ features used company-wide
- Built an invoice generator with live preview (Puppeteer) that auto-generates PDFs, replacing the old manual process
- Containerized the full platform with Docker, deployed on a bare Linux server via Cloudflare Tunnel — zero exposed ports, zero cloud hosting costs
- Wired up JWT auth + RBAC across all endpoints, automated Rclone backups, and set up CI/CD with GitHub Actions + Watchtower

**Backend Developer (Intern)** · SIES College of Arts, Science and Commerce — *Nov 2025 – Jan 2026*
- Designed and built REST APIs in Python (FastAPI) as the data layer between frontend and SQL database
- Implemented RBAC to manage permissions across user types
- Collaborated cross-functionally on API contracts and delivered on schedule

---

### 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

**🌐 DnsTitle**
Multi-tenant DNS management platform, built solo.
- Automated domain verification, subdomain provisioning, and full DNS record lifecycle management
- Redis + BullMQ workers handle BIND9 operations async — failed jobs fail loudly, nothing breaks silently
- Nginx reverse proxy for scalable multi-tenant routing
- Fully Dockerized: API, worker, BIND9, Nginx, Redis each in their own container

`Node.js` `React` `MongoDB` `Redis` `BIND9` `Docker` `Nginx`

</td>
<td width="50%" valign="top">

**📦 Hosting Platform**
A mini PaaS, built solo.
- Automates app deployment + full container lifecycle (build, start, stop, restart, monitor) via Dockerode
- MongoDB stores deployment metadata, container state, per-user resource records
- Per-user container isolation for secure, stable workloads
- Real-time error logging across every container — deployment failures are never silent

`Node.js` `Express` `MongoDB` `Docker` `Dockerode`

</td>
</tr>
</table>

---

### 🎓 Education

**B.Sc. Information Technology** — SIES College (Autonomous), Navi Mumbai · *Graduated 2026*
GPA: 7.92/10 · 🏆 2nd Place, Inter-College Hackathon

---

### 📫 Reach Me

<p align="left">
📧 anthony@anthonynelson.in &nbsp;|&nbsp; 📱 +91-8591537405 &nbsp;|&nbsp; 📍 Mumbai, India
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=anthonynelson&label=Profile%20Views&color=2ea043&style=flat" alt="profile views" />
</p>
