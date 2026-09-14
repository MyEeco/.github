
<p align="center">
  <img src="https://img.shields.io/badge/Echo-Audio%20%26%20Creator%20Streaming-6C5CE7?style=for-the-badge" alt="Echo" />
</p>

<h1 align="center">Echo</h1>
<p align="center"><b>Audio and creator streaming, built for African markets.</b></p>

<p align="center">
  <a href="https://myeeco.com"><img src="https://img.shields.io/badge/Website-myeeco.com-000000?style=for-the-badge&logo=googlechrome&logoColor=white"></a>
  <a href="https://www.linkedin.com/company/myeecoapp/"><img src="https://img.shields.io/badge/myeecoapp-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://x.com/myeecoapp"><img src="https://img.shields.io/badge/myeecoapp-000000?style=for-the-badge&logo=x&logoColor=white"></a>
</p>

---

### The Problem

Podcast and live-audio platforms built for US/EU networks and payment rails don't hold up well for African users — high data costs, inconsistent connectivity, and payment methods that assume a Western banking stack. Creators in these markets are underserved by tools built for someone else's infrastructure conditions.

### What We're Building

Echo combines **on-demand podcast listening**, **live audio broadcasting**, and **offline-first playback** in a single cross-platform product — designed from the ground up around African network and payment realities rather than retrofitted for them.

-  **Listen Together** — synchronized shared listening sessions with server-authoritative playback sync
-  **Live audio broadcasting** — low-latency RTMP ingestion with real-time listener presence and chat
-  **Offline-first mobile** — built for intermittent connectivity, not against it
-  **Creator tools** — a dedicated desktop studio for streamers and podcasters

### How It's Built

| Layer | Stack |
|---|---|
| Backend | Elixir/Phoenix, PostgreSQL, Redis, RTMP/FFmpeg/HLS pipeline |
| Mobile | React Native (Expo), custom native modules for media session & audio capture |
| Desktop (Creator Studio) | Tauri 2 + React, Rust audio engine (`cpal`, `fdk-aac`) |
| Infrastructure | AWS (`af-south-1` — Cape Town), Nginx, PM2 |

We run our own infrastructure in Cape Town rather than defaulting to US-East, specifically to cut the latency African streamers see on live audio — a decision made after measuring real frame loss on the more common setup.

### Stage

Built solo over 8+ months, now scaling to a small cross-functional team across mobile, backend, desktop, and design. Actively expanding platform capabilities ahead of broader launch.

### Team

Founded by **Adeyeye Seyi**, **Innocents Ugo**, **Tolu Smith**

---

<p align="center"><i>Interested in what we're building? Reach out — <a href="mailto:ultra@myeeco.com">ultra@myeeco.com</a></i></p>
