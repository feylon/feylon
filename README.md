<!-- ═══════════════════════════ HEADER ═══════════════════════════ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:00dc82&height=220&section=header&text=Jamshid&fontSize=80&fontColor=ffffff&fontAlignY=38&desc=Fullstack%20Engineer%20%E2%80%A2%20Microservices%20Architect&descAlignY=60&descSize=20&animation=fadeIn" alt="Jamshid" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/feylon">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00DC82&center=true&vCenter=true&width=640&lines=I+design+systems+that+don't+fall+over.;Nuxt.js+%C2%B7+Vue+3+%C2%B7+NestJS+%C2%B7+TypeScript;Kafka+%C2%B7+Redis+%C2%B7+BullMQ+%C2%B7+gRPC+%C2%B7+Docker;Clean+code.+High+performance.+Production-ready." alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=feylon&style=for-the-badge&color=00dc82&label=PROFILE+VIEWS" alt="Profile views" />
  <a href="https://github.com/feylon?tab=followers"><img src="https://img.shields.io/github/followers/feylon?style=for-the-badge&logo=github&label=Followers&color=302b63&labelColor=0f0c29" alt="Followers" /></a>
  <img src="https://img.shields.io/badge/Tashkent-Uzbekistan-00dc82?style=for-the-badge&logo=googlemaps&logoColor=white&labelColor=0f0c29" alt="Location" />
  <a href="mailto:jamshid14092002@gmail.com"><img src="https://img.shields.io/badge/Open_to-Remote_%2F_Freelance-7c3aed?style=for-the-badge&logo=rocket&logoColor=white&labelColor=0f0c29" alt="Open to work" /></a>
</p>

<br/>

<!-- ═══════════════════════════ HERO TERMINAL ═══════════════════════════ -->
<p align="center">
  <img src="./assets/terminal.svg" alt="whoami — Jamshid, Fullstack Engineer & Microservices Architect" width="860" />
</p>

<br/>

<!-- ═══════════════════════════ ABOUT ═══════════════════════════ -->
<table align="center">
  <tr>
    <td width="68%" valign="top">

### 👨‍💻 About Me

I'm a **Fullstack Engineer** who loves the hard part of the stack — the part where thousands of events per second must land in the right place, exactly once, and the UI still feels instant.

- 🏛️ &nbsp;**Architecture** — Event-Driven, Microservices, REST &amp; gRPC APIs
- ⚡ &nbsp;**Now scaling with** — Kafka, Redis, BullMQ &amp; Docker
- 🧩 &nbsp;**Frontend** — Nuxt.js (Vue 3) with pixel-perfect, fast UIs
- 🌍 &nbsp;**Open to** — remote roles &amp; freelance projects
- 📫 &nbsp;**Reach me** — [jamshid14092002@gmail.com](mailto:jamshid14092002@gmail.com)

</td>
    <td width="32%" align="center" valign="middle">
      <img src="https://avatars.githubusercontent.com/u/129485306?v=4" alt="Jamshid" width="180" />
      <br/><br/>
      <a href="https://t.me/jamshid14092002"><img src="https://img.shields.io/badge/Let's_talk-Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white&labelColor=0f0c29" alt="Telegram" /></a>
    </td>
  </tr>
</table>

<!-- ═══════════════════════════ ARCHITECTURE ═══════════════════════════ -->
<h2 align="center">🏗️ How I Build Systems</h2>

<p align="center"><sub>A typical event-driven setup I design and ship to production</sub></p>

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#1b1745','primaryTextColor':'#e2e8f0','primaryBorderColor':'#00dc82','lineColor':'#7c3aed','secondaryColor':'#0f0c29','tertiaryColor':'#0f0c29','fontFamily':'Fira Code, monospace'}}}%%
flowchart LR
    U(["👤 Client<br/>Nuxt 3 · Vue"]) --> N["🌐 Nginx<br/>load balancer"]
    N --> G["🚪 API Gateway<br/>NestJS"]
    G -- gRPC --> A["🔐 Auth"]
    G -- gRPC --> B["📅 Booking"]
    G -- gRPC --> Q["🚦 Queue"]
    B -- event --> K{{"📨 Kafka"}}
    Q -- event --> K
    K --> W["⚙️ Workers<br/>BullMQ"]
    K --> RT["📡 Realtime<br/>WebSockets"]
    RT -. live updates .-> U
    W --> PG[("🐘 PostgreSQL")]
    W --> CH[("📊 ClickHouse")]
    A <--> R[("⚡ Redis")]
    B <--> R
```

<!-- ═══════════════════════════ TECH STACK ═══════════════════════════ -->
<h2 align="center">🚀 Tech Stack</h2>

<table align="center">
  <tr>
    <td align="center" width="150"><b>🌐 Frontend</b></td>
    <td><img src="https://skillicons.dev/icons?i=nuxtjs,vue,nextjs,tailwind,ts,js&theme=dark" alt="Nuxt, Vue, Next, Tailwind, TypeScript, JavaScript" /></td>
  </tr>
  <tr>
    <td align="center"><b>⚙️ Backend</b></td>
    <td><img src="https://skillicons.dev/icons?i=nestjs,nodejs,python,fastapi&theme=dark" alt="NestJS, Node.js, Python, FastAPI" /></td>
  </tr>
  <tr>
    <td align="center"><b>🗄️ Data &amp; Brokers</b></td>
    <td><img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,kafka,rabbitmq&theme=dark" alt="PostgreSQL, MongoDB, Redis, Kafka, RabbitMQ" /></td>
  </tr>
  <tr>
    <td align="center"><b>🛠️ DevOps</b></td>
    <td><img src="https://skillicons.dev/icons?i=docker,nginx,git,github,githubactions,linux&theme=dark" alt="Docker, Nginx, Git, GitHub, GitHub Actions, Linux" /></td>
  </tr>
</table>

<!-- ═══════════════════════════ WHAT I BUILD ═══════════════════════════ -->
<h2 align="center">🎯 What I Build</h2>

<table align="center">
  <tr>
    <td width="50%" valign="top">
      <h3>🏗️ Distributed Systems</h3>
      Microservices handling real-time data via <b>Kafka</b>, <b>WebSockets</b> and <b>gRPC</b>.
    </td>
    <td width="50%" valign="top">
      <h3>🚦 Complex Business Logic</h3>
      Advanced booking systems, smart queues (medical / CTF platforms) and real-time tracking (taxi &amp; transport).
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>⚡ Performance</h3>
      Background jobs with <b>BullMQ</b>, caching layers with <b>Redis</b>, optimized indexing in <b>PostgreSQL</b> &amp; <b>ClickHouse</b>.
    </td>
    <td width="50%" valign="top">
      <h3>🖥️ Full-Stack Magic</h3>
      Seamless <b>Vue / Nuxt</b> interfaces connected to robust <b>NestJS</b> architectures.
    </td>
  </tr>
</table>

<!-- ═══════════════════════════ PROJECTS ═══════════════════════════ -->
<h2 align="center">📌 Featured Projects</h2>

<p align="center">
  <a href="https://github.com/feylon/GoogleDocs-Nest-js-Nuxt"><img src="https://github-readme-stats.vercel.app/api/pin/?username=feylon&repo=GoogleDocs-Nest-js-Nuxt&theme=tokyonight&hide_border=true&bg_color=0f0c29&title_color=00dc82&icon_color=00dc82" alt="GoogleDocs-Nest-js-Nuxt" /></a>
  <a href="https://github.com/feylon/ctf"><img src="https://github-readme-stats.vercel.app/api/pin/?username=feylon&repo=ctf&theme=tokyonight&hide_border=true&bg_color=0f0c29&title_color=00dc82&icon_color=00dc82" alt="ctf" /></a>
  <a href="https://github.com/feylon/SMS_SERVICE"><img src="https://github-readme-stats.vercel.app/api/pin/?username=feylon&repo=SMS_SERVICE&theme=tokyonight&hide_border=true&bg_color=0f0c29&title_color=00dc82&icon_color=00dc82" alt="SMS_SERVICE" /></a>
  <a href="https://github.com/feylon/Online_shoppping_admin"><img src="https://github-readme-stats.vercel.app/api/pin/?username=feylon&repo=Online_shoppping_admin&theme=tokyonight&hide_border=true&bg_color=0f0c29&title_color=00dc82&icon_color=00dc82" alt="Online_shoppping_admin" /></a>
</p>

<!-- ═══════════════════════════ STATS ═══════════════════════════ -->
<h2 align="center">📊 GitHub Stats</h2>

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=feylon&theme=tokyonight&show_icons=true&hide_border=true&count_private=true&bg_color=0f0c29&title_color=00dc82&icon_color=00dc82" alt="GitHub stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=feylon&layout=compact&theme=tokyonight&hide_border=true&hide=css,html,jupyter%20notebook&bg_color=0f0c29&title_color=00dc82" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=feylon&theme=tokyonight&hide_border=true&background=0f0c29&ring=00dc82&fire=00dc82&currStreakLabel=00dc82" alt="GitHub streak" />
</p>

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=feylon&bg_color=0f0c29&color=ffffff&line=00dc82&point=7c3aed&area=true&area_color=00dc82&hide_border=true" alt="Activity graph" />
</p>

<details align="center">
  <summary><b>⏱️ WakaTime — coding time</b></summary>
  <br/>
  <a href="https://wakatime.com/@018c6eb7-5205-49ed-85bd-ed4c1ab37b6f">
    <img src="https://wakatime.com/badge/user/018c6eb7-5205-49ed-85bd-ed4c1ab37b6f.svg" alt="WakaTime" />
  </a>

<!--START_SECTION:waka-->
<!--END_SECTION:waka-->

</details>

<!-- ═══════════════════════════ SNAKE ═══════════════════════════ -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/feylon/feylon/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/feylon/feylon/output/github-snake.svg" />
    <img alt="Contribution snake" src="https://raw.githubusercontent.com/feylon/feylon/output/github-snake-dark.svg" />
  </picture>
</p>

<!-- ═══════════════════════════ CONNECT ═══════════════════════════ -->
<h2 align="center">🌐 Let's Connect</h2>

<p align="center">
  <a href="https://t.me/jamshid14092002"><img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" /></a>
  <a href="https://www.linkedin.com/in/jamshid14092002"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://www.instagram.com/jamshid14092002/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" /></a>
  <a href="https://x.com/jamshid14092002"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
  <a href="mailto:jamshid14092002@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<p align="center"><i>“Make it work, make it right, make it fast.” — Kent Beck</i></p>

<!-- ═══════════════════════════ FOOTER ═══════════════════════════ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00dc82,50:302b63,100:0f0c29&height=120&section=footer" alt="" width="100%" />
</p>
