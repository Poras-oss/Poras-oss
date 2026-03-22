<div align="center">

```
██████╗  ██████╗ ██████╗  █████╗ ███████╗
██╔══██╗██╔═══██╗██╔══██╗██╔══██╗██╔════╝
██████╔╝██║   ██║██████╔╝███████║███████╗
██╔═══╝ ██║   ██║██╔══██╗██╔══██║╚════██║
██║     ╚██████╔╝██║  ██║██║  ██║███████║
╚═╝      ╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝
```

### Software Development Engineer · Backend · Real-Time Systems · Cloud

[![Profile Views](https://komarev.com/ghpvc/?username=poras-oss&label=Profile%20Views&color=0a66c2&style=flat-square)](https://github.com/poras-oss)
[![Email](https://img.shields.io/badge/Email-shrivasporas%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:shrivasporas@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-poras--shrivas-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/poras-shrivas-776037195/)
[![LeetCode](https://img.shields.io/badge/LeetCode-shrivasporas-FFA116?style=flat-square&logo=leetcode&logoColor=white)](https://leetcode.com/shrivasporas)
[![GeeksforGeeks](https://img.shields.io/badge/GFG-shrivasporas-2F8D46?style=flat-square&logo=geeksforgeeks&logoColor=white)](https://auth.geeksforgeeks.org/user/shrivasporas)

</div>

---

## 👨‍💻 About Me

Backend engineer with hands-on experience building **real-time platforms**, **scalable APIs**, and **cloud infrastructure**. Currently at **DataSense Edtech**, where I ship systems that handle thousands of concurrent users — from live competitive coding arenas to automated grading pipelines.

- 🔭 Currently building real-time competition platforms & video streaming infrastructure
- 🌱 Exploring **WebRTC**, **Flutter**, and **React Native**
- ⚡ Fun fact: I once cut content upload time by **95%** with a single Python script
- 📫 Reach me at **shrivasporas@gmail.com**

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Frameworks & Libraries**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)
![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=flat-square&logo=webrtc&logoColor=white)
![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white)

**Databases**

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Platforms & Tools**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)

---

## 🚀 Featured Projects

### 🎥 HLS Video Streaming Server
> `Node.js` `FFmpeg` `AWS S3` `Redis`

End-to-end video pipeline with adaptive bitrate streaming. Transcodes uploads into HLS at **1080p / 720p / 480p** using parallel FFmpeg workers. Segments served from S3 via CDN-friendly URLs; playlist manifests cached in Redis to reduce repeated S3 reads under load.

---

### 🏪 Microservices E-Commerce Backend
> `NestJS` `RabbitMQ` `Docker` `Redis`

Fully decoupled microservices (auth, catalog, orders, notifications) with async inter-service messaging via RabbitMQ. API Gateway handles JWT auth, routing, and rate limiting. Load tested to **4,200 req/sec** on a single `t3.medium` with **p99 latency < 40ms**.

---

### 📁 P2P Real-Time File Sharing
> `Node.js` `WebRTC` `Socket.IO`

Browser-to-browser file transfer with no server bandwidth cost. Signaling via Socket.IO (SDP + ICE), chunked streaming for large files, reconnection that resumes from the exact byte offset, and WebRTC's built-in encryption for secure transfers.

---

### 🎥 Real-Time Video Chat (Omegle-like)
> `Node.js` `WebRTC` `Socket.IO`

Random video chat with optional rooms supporting **up to 6 participants** via mesh WebRTC. Event-driven recording triggered by audio spikes or motion bursts, stored for later retrieval.

---

### 🐍 Sandboxed Python Code Executor
> `Node.js` `Docker` `Python`

Secure execution engine running user code in isolated Docker containers with CPU/memory limits and timeout controls. Pre-warmed container pool for low-latency concurrent execution. Proxy layer whitelists outbound API calls so students can practice safely with real APIs.

---

## 🏆 Achievements

| Event | Result |
|---|---|
| 🥈 HackByte Hackathon — IIITDM Jabalpur | **Top 10% · 7th Place** — Fake profile detection with ML + UIDAI verification |
| 🏁 Great India Hackathon | **Finalist** — Stock market analysis platform with VR educational features |

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=poras-oss&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs?username=poras-oss&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9" height="165" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=poras-oss&theme=github-dark-blue&hide_border=true&background=0d1117&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff" />

</div>

---

<div align="center">

*Building things that scale. Breaking things that don't.* 🚀

</div>
