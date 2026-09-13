<div align="center">

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=26&duration=3000&pause=800&color=A855F7&center=true&vCenter=true&width=650&lines=Embedded+Systems+%26+Firmware+Engineer;Self-taught.+Bare-metal+minded.;Building+silicon+dreams+one+interrupt+at+a+time." alt="Typing SVG" />

![Status](https://img.shields.io/badge/Status-High%20School%20Student-blueviolet?style=for-the-badge)
![Focus](https://img.shields.io/badge/Focus-Embedded%20Systems%20%7C%20Firmware%20%7C%20IoT-orange?style=for-the-badge)
![Goal](https://img.shields.io/badge/Target-PENS%20(Politeknik%20Elektronika%20Negeri%20Surabaya)-blue?style=for-the-badge)

<img src="https://komarev.com/ghpvc/?username=your-github-username&label=Profile%20Views&color=blueviolet&style=flat-square" alt="Profile views" />

</div>

<!--
  ⚠️ GANTI SEMUA "your-github-username" DI FILE INI DENGAN USERNAME GITHUB ASLI KAMU
  supaya visitor counter & stats card di bawah berfungsi.
-->

---

## 🧠 About Me

> *"I don't just write code — I fight for every byte of RAM."*

I'm a high school student who fell in love with the space between hardware and software — the place where a single misplaced `volatile` keyword can crash a whole system, and where a well-placed DMA transfer can make a $3 microcontroller feel like magic.

Everything here is **self-taught**: no bootcamp, no formal curriculum — just datasheets, forum threads at 2 AM, and a lot of bricked boards along the way.

<table>
<tr>
<td>

🔩 **Hardware-level optimization**
OPI PSRAM tuning, bare-metal programming when Arduino abstractions get in the way

</td>
<td>

🧵 **Real concurrency**
FreeRTOS dual-core task management, mutexes, race-condition hunting on ESP32-S3

</td>
<td>

🤖 **Edge AI/ML**
On-device inference *and* on-device learning — no cloud dependency

</td>
</tr>
</table>

🎓 **Next chapter:** aiming to continue my studies at **PENS (Politeknik Elektronika Negeri Surabaya)** to turn this self-taught foundation into formal, rigorous expertise.

<details>
<summary>🌱 <b>Currently exploring</b> (click to expand)</summary>
<br>

- 🔬 Deeper bare-metal ESP-IDF programming (peeling back the Arduino layer)
- 🧠 On-device TinyML model compression
- 🖥️ Custom bootloader & OTA reliability for the Accretion Phone
- 📡 Low-power mesh networking patterns

</details>

---

## 🪐 The Accretion Journey

> Like a planet forming from dust and debris colliding over millions of years, every project below **accreted** onto the skills of the last. Nothing here was built in isolation — each device is a fossil record of what I learned building the one before it.

```mermaid
graph LR
    A[🕹️ G-BOX<br/>2D Game Loop] --> B[📡 AI-Pocket<br/>IoT + Power]
    B --> C[🎬 Media Hub<br/>Color + Web]
    C --> D[📷 SANZXCAM<br/>Vision + Sensors]
    D --> E[🎧 RYNE Engine<br/>Edge ML]
    E --> F[📱 Accretion Phone<br/>The OS]

    style A fill:#1a1a2e,stroke:#a855f7,color:#fff
    style B fill:#1a1a2e,stroke:#a855f7,color:#fff
    style C fill:#1a1a2e,stroke:#a855f7,color:#fff
    style D fill:#1a1a2e,stroke:#a855f7,color:#fff
    style E fill:#1a1a2e,stroke:#a855f7,color:#fff
    style F fill:#1a1a2e,stroke:#ffd700,color:#fff
```

<br>

<details open>
<summary>

### 🕹️ 01 — G-BOX *(The Genesis)*

</summary>
<br>

| | |
|---|---|
| **Platform** | ESP32 · OLED 128×64 SSD1306 (I2C) |
| **Games shipped** | Flappy Bird · Space Invaders · Asteroids |

My **first custom handheld console** — and the place where it all began. Pure fundamentals: building a real game loop from scratch, pushing pixels manually to a monochrome buffer, wrestling with array-based memory management, and relearning trigonometry (`sin`/`cos`) not for a math test, but to make 2D physics actually *feel* right.

> 💡 *Lesson learned: if you can render a bird flapping through pipes on a 128×64 screen with no game engine, you can render almost anything.*

</details>

<details>
<summary>

### 📡 02 — ESP32-C3 Ultra Edition / AI-Pocket v1.0

</summary>
<br>

| | |
|---|---|
| **Platform** | ESP32-C3 SuperMini · OLED 128×64 |

My first real dive into **the internet and power efficiency**:

- 🔋 **Battery Guardian** — physical voltage-divider circuit + firmware to catch battery drain/leakage in real time
- ⌨️ Custom **6-button virtual keyboard** for full text input, wired to **Google Gemini 2.0 Flash**
- 📻 Internet-free **radio messaging** built on **ESP-NOW Mesh Networking**

> 💡 *Lesson learned: you don't need Wi-Fi to build a network — you need a protocol and a reason to talk to your neighbors.*

</details>

<details>
<summary>

### 🎬 03 — ESP32-S3 Media Hub v9.1

</summary>
<br>

| | |
|---|---|
| **Platform** | ESP32-S3 N16R8 · TFT ST7789 (320×170) |

Leveling up to **color displays** and real web data processing:

- 🎞️ `.mjpeg` video playback via **DMA**, powered by **LovyanGFX** & **JPEGDEC**
- 🛰️ Real-time APIs: **ISS Tracker**, **NASA APOD**, **Groq AI** (parsed with `ArduinoJson`)
- 🧩 2D game AI using **BFS pathfinding** for enemy movement in Pacman & Tank Battle

> 💡 *Lesson learned: BFS isn't just a whiteboard interview question — it's what makes a Pacman ghost feel like it's actually hunting you.*

</details>

<details>
<summary>

### 📷 04 — SANZXCAM v6.1 *(Terminal Aesthetic Camera)*

</summary>
<br>

| | |
|---|---|
| **Platform** | ESP32-S3 · 16-bit DVP Camera · MPU6050 · ILI9341 |

A deep dive into **image processing and system stability**:

- 🌀 **Kalman Filtering** sensor fusion for real-time **Electronic Image Stabilization**
- 🌤️ **HDR Triple Capture** for wider dynamic range
- 🏝️ **Dynamic Island**–style UI with sprite-based restoration for tear-free animation
- 🧠 On-device analysis via **Gemini 2.5 Flash Lite** (Mood Reader, ANPR)
- 🔐 Working **steganography** — payloads hidden in a JPEG's COM marker & a BMP's LSB bits

> 💡 *Lesson learned: stabilizing a handheld viewfinder with a $2 gyroscope taught me more about sensor fusion than any tutorial ever could.*

</details>

<details>
<summary>

### 🎧 05 — RYNE Engine — Bluetooth Music Player v1.4.0

</summary>
<br>

| | |
|---|---|
| **Platform** | ESP32-WROVER · OLED SSD1306 · Bluetooth A2DP Source |

The **big leap into local Edge Machine Learning**:

- 🧮 **Softmax Multiclass Vibe Classifier** — a self-learning model in PSRAM that **retrains every 5 minutes**, inferring mood from skip-rate & volume
- 🎲 **RYNE-CRS**, a custom recommendation algorithm (*not* UCB1) built on **Bayesian probability** + a **power-law curiosity** model
- 😃 Expressive **OLED face animations**, synced with a **FreeRTOS Core 1 task** watching audio buffer health for glitch-free playback

> 💡 *Lesson learned: an AI model doesn't need a data center — it needs a well-scoped problem and a PSRAM chip that isn't afraid of a little math.*

</details>

<details>
<summary>

### 📱 06 — Accretion Phone — *running nyx OS v84* **(The Masterpiece)**

</summary>
<br>

| | |
|---|---|
| **Platform** | ESP32-S3 · ILI9341 (Resistive Touch) · MPU6050 · SD Card (SDIO 1-bit) |
| **Codebase** | 13,000+ lines · zero real OS underneath |
| **Apps built-in** | 26 |

The **culmination of every project above**:

- 🔒 **Lock screen** with genuine glassmorphism
- 🏠 **Home screen** with momentum scrolling (low-pass velocity + decay), flicker-free thanks to aggressive **double buffering / canvas sprite** optimization in PSRAM
- 🤖 **Gemini AI integration** — voice dictation via **INMP441 mic** + hand-written manual JSON parser (no `ArduinoJson`) to save RAM
- 📡 **OTA updates** over Wi-Fi or SD card
- 🎮 **Game Mode**: *"Inferno"*, a 3D raycasting FPS à la DOOM/Wolfenstein, stable **16 FPS**, persistent autosave to SD

> 💡 *This isn't just a phone. It's every lesson from G-BOX to RYNE Engine, compressed into a device that fits in your pocket.*

</details>

---

## 🛠️ Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=cpp,c,arduino,py,git,github" alt="Skill icons" />

</div>

<table>
<tr>
<td valign="top" width="25%">

**Languages**
- C++ · C
- Python

</td>
<td valign="top" width="25%">

**Frameworks & Libraries**
- Arduino Core
- FreeRTOS
- LovyanGFX
- JPEGDEC
- ArduinoJson

</td>
<td valign="top" width="25%">

**Hardware / Chips**
- ESP32 / C3 / S3 / WROVER
- SSD1306 · ST7789 · ILI9341
- MPU6050 · INMP441
- OPI PSRAM

</td>
<td valign="top" width="25%">

**Tools & Services**
- Google Gemini API
- Groq AI API
- ESP-NOW
- Git & GitHub

</td>
</tr>
</table>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=your-github-username&show_icons=true&theme=radical&hide_border=true&count_private=true" alt="GitHub Stats" height="165" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=your-github-username&theme=radical&hide_border=true" alt="GitHub Streak" height="165" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=your-github-username&theme=react-dark&hide_border=true" alt="Contribution Graph" width="100%" />

</div>

---

## 🔗 Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/your-github-username)
[![Instagram](https://img.shields.io/badge/Instagram-%40sanzx__project.id-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/sanzx_project.id)

</div>

---

<div align="center">

> *"Mastery isn't a single breakthrough — it's accretion. It's ten thousand small, unglamorous hours of debugging, rewiring, and rewriting, quietly fusing together until one day the dust becomes a planet."*

**— SanzX**

<br>

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=14&duration=4000&pause=1000&color=6B7280&center=true&vCenter=true&width=500&lines=Thanks+for+scrolling+this+far.+Now+go+build+something.+%F0%9F%9A%80" alt="Footer" />

</div>
