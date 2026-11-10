<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=230&section=header&text=Lalan%20Kumar&fontSize=62&fontColor=ffffff&fontAlignY=38&desc=Autonomous%20AI%20%C2%B7%20Full-Stack%20%C2%B7%20Robotics&descSize=20&descAlignY=60" width="100%" alt="Lalan Kumar header" />

<a href="https://lalankr.in">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1200&color=00E5FF&center=true&vCenter=true&width=760&height=50&lines=B.Tech+Mechanical+Engineering+%40+IIT+Madras;Making+AI+that+acts%2C+software+that+ships;Machines+that+move%2C+code+that+scales;Offline-first+PWAs+%7C+Edge+compute+%7C+Embedded+C%2B%2B" alt="typing animation" />
</a>

<br/>

[![Website](https://img.shields.io/badge/lalankr.in-portfolio-00E5FF?style=for-the-badge&logo=googlechrome&logoColor=white)](https://lalankr.in)
[![Live Portal](https://img.shields.io/badge/me26b.lalankr.in-live_in_production-7C4DFF?style=for-the-badge&logo=pwa&logoColor=white)](https://me26b.lalankr.in)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-lalankr08-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/lalankr08)
[![Instagram](https://img.shields.io/badge/Instagram-lalankr.08-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/lalankr.08)

![Profile views](https://komarev.com/ghpvc/?username=lalankr08&label=Profile+views&color=00b8d4&style=flat-square)

</div>

---

## About

```python
class Lalan:
    name      = "Lalan Kumar"
    handle    = "lalankr08"
    studying  = "B.Tech, Mechanical Engineering @ IIT Madras (2026-2030)"
    building  = ["autonomous AI pipelines", "full-stack web apps", "Android apps", "robotics"]
    approach  = "ship end to end: design, firmware, backend, deploy"
    won       = "1st place, Smart Bengal Hackathon 2023"
    reach_me  = "https://lalankr.in"
```

---

## Currently building

| Project | What it is | Stack |
|---|---|---|
| [ME26B Batch Portal](https://me26b.lalankr.in) | Installable, offline-first PWA for my whole batch: timetable, mess menu, notices, events, cached course material, plus an AI assistant ("Agent Zero") | React 19, TypeScript, Vite, Firebase, Cloudflare Workers + R2 |
| Lecture Notes Pipeline | Lecture audio, PPTs and PDFs in; LaTeX, Markdown notes and a Q&A vector store out | Python, FastAPI, WhisperX, Gemini Flash, Supabase pgvector |
| ESP32 PID Approach Robot | Closed-loop ultrasonic distance control, stops exactly 25.0 cm from an obstacle | ESP32, C++, PID, ESP-NOW |

---

## Architecture: ME26B Batch Portal

```mermaid
flowchart LR
    U[Student device<br/>installable PWA] -->|Workbox cache<br/>4-day sliding window| SW[Service Worker]
    U -->|auth + realtime sync| FB[(Cloud Firestore<br/>multi-tab offline)]
    U -->|login| AU[Firebase Auth]
    FB -->|push| FCM[Firebase Cloud Messaging]
    FCM --> U
    U -->|files| CW[Cloudflare Workers]
    CW --> R2[(Cloudflare R2<br/>zero egress)]
    U -->|voice + text| AZ[Agent Zero]
    AZ --> GQ[Groq Whisper v3 Turbo]
    AZ --> GM[Gemini Flash]
```

---

## Tech stack

### Languages
<p>
  <img src="https://skillicons.dev/icons?i=python,cpp,c,ts,js,java,php,html,css&perline=9" alt="languages" />
</p>

### Frontend and mobile
<p>
  <img src="https://skillicons.dev/icons?i=react,vite,tailwind,androidstudio,figma&perline=9" alt="frontend" />
</p>

`React 19` `TypeScript` `Vite` `Tailwind v4` `WebGL / GLSL shaders` `Workbox PWA` `PDF.js` `Android SDK (Java, XML)`

### Backend, cloud and data
<p>
  <img src="https://skillicons.dev/icons?i=nodejs,fastapi,firebase,supabase,postgres,cloudflare&perline=9" alt="backend" />
</p>

`FastAPI` `Cloudflare Workers` `Cloudflare R2` `Cloud Firestore` `Firebase Auth + FCM` `Supabase pgvector`

### AI and ML
<p>
  <img src="https://skillicons.dev/icons?i=python,opencv&perline=9" alt="ai" />
</p>

`Whisper / WhisperX` `Gemini Flash` `Groq` `OpenCV` `CNNs` `Vector search (pgvector)` `LLM agents and pipelines`

### Embedded and robotics
<p>
  <img src="https://skillicons.dev/icons?i=arduino,raspberrypi,c,cpp&perline=9" alt="embedded" />
</p>

`ESP32` `ESP-NOW` `Raspberry Pi Pico (RP2040)` `MicroPython` `PID control` `L298N / H-bridge motor drivers` `UART` `PWM`

### Tools
<p>
  <img src="https://skillicons.dev/icons?i=git,github,linux,vscode,latex&perline=9" alt="tools" />
</p>

`Git` `GitHub` `Linux` `VS Code` `LaTeX` `FFmpeg` `Discord / Telegram APIs`

---

## Highlights

| Year | Milestone |
|---|---|
| 2026 | Joined IIT Madras, B.Tech Mechanical Engineering |
| 2026 | Shipped the ME26B Batch Portal to production |
| 2026 | ESP32 ultrasonic PID robot |
| 2025 | CSES algorithm solutions in C++ (graphs, DP, segment trees) |
| 2023 | 1st prize, Smart Bengal Hackathon: real-time emotion detector (OpenCV, CNNs) |
| 2021 | Live cricket score Android widget, about 500 installs on Google Play |
| 2021-22 | Phone-controlled robot car (Pico, MicroPython, native Android app) |

---

## GitHub stats

<div align="center">

<img src="https://streak-stats.demolab.com?user=lalankr08&theme=tokyonight&hide_border=true&background=0d1117" alt="streak" />

<br/>

![Public repos](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2Flalankr08&query=%24.public_repos&label=Public%20repos&color=00b8d4&style=for-the-badge&logo=github)
![Followers](https://img.shields.io/github/followers/lalankr08?label=Followers&color=7C4DFF&style=for-the-badge&logo=github)
![Top language](https://img.shields.io/github/languages/top/lalankr08/CSES?label=Most%20solved%20in&color=f34b7d&style=for-the-badge&logo=cplusplus&logoColor=white)

</div>

---

## Contribution snake

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/lalankr08/lalankr08/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/lalankr08/lalankr08/output/github-snake.svg" />
    <img alt="contribution snake" src="https://raw.githubusercontent.com/lalankr08/lalankr08/output/github-snake-dark.svg" />
  </picture>
</div>

---
---

<div align="center">



[lalankr.in](https://lalankr.in) | [LinkedIn](https://linkedin.com/in/lalankr08) | [Instagram](https://instagram.com/lalankr.08)

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=110&section=footer" width="100%" alt="footer" />

</div>
