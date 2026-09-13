<div align="center">

# âš¡ SanzX â€” Embedded Systems & Firmware Engineer

### *Self-taught. Bare-metal minded. Building silicon dreams one interrupt at a time.*

![Status](https://img.shields.io/badge/Status-High%20School%20Student-blueviolet?style=for-the-badge)
![Focus](https://img.shields.io/badge/Focus-Embedded%20Systems%20%7C%20Firmware%20%7C%20IoT-orange?style=for-the-badge)
![Goal](https://img.shields.io/badge/Target-PENS%20(Politeknik%20Elektronika%20Negeri%20Surabaya)-blue?style=for-the-badge)

![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-000000?style=flat-square&logo=freertos&logoColor=white)
![Edge AI](https://img.shields.io/badge/Edge%20AI-ff69b4?style=flat-square)

</div>

---

## ðŸ§  About Me

> *"I don't just write code â€” I fight for every byte of RAM."*

I'm a high school student who fell in love with the space between hardware and software â€” the place where a single misplaced `volatile` keyword can crash a whole system, and where a well-placed DMA transfer can make a $3 microcontroller feel like magic.

Everything here is **self-taught**: no bootcamp, no formal curriculum â€” just datasheets, forum threads at 2 AM, and a lot of bricked boards along the way.

My core interests:

- ðŸ”© **Hardware-level optimization** â€” squeezing performance out of OPI PSRAM, flirting with bare-metal programming when Arduino abstractions get in the way
- ðŸ§µ **Real concurrency** â€” FreeRTOS dual-core task management, mutexes, and race-condition hunting on the ESP32-S3
- ðŸ¤– **Edge AI/ML** â€” running inference and even *on-device learning* locally, without leaning on the cloud for every decision

ðŸŽ“ **Next chapter:** I'm aiming to continue my studies at **PENS (Politeknik Elektronika Negeri Surabaya)** â€” Indonesia's premier ground for electronics engineers â€” to turn this self-taught foundation into formal, rigorous expertise.

---

## ðŸª The Accretion Journey

> Like a planet forming from dust and debris colliding over millions of years, every project below **accreted** onto the skills of the last. Nothing here was built in isolation â€” each device is a fossil record of what I learned building the one before it.

```
G-BOX â†’ AI-Pocket â†’ Media Hub â†’ SANZXCAM â†’ RYNE Engine â†’ Accretion Phone
 (2D)      (IoT)      (Color)    (Vision)     (Edge ML)     (The OS)
```

<br>

### ðŸ•¹ï¸ 01 â€” G-BOX *(The Genesis)*

<table>
<tr>
<td width="30%" valign="top">

**Platform**
- ðŸ§  ESP32
- ðŸ–¥ï¸ OLED 128Ã—64 SSD1306 (I2C)

</td>
<td width="70%" valign="top">

My **first custom handheld console** â€” and the place where it all began. This was pure fundamentals: building a real game loop from scratch, pushing pixels manually to a monochrome buffer, wrestling with array-based memory management, and relearning trigonometry (`sin`/`cos`) not for a math test, but to make 2D physics actually *feel* right.

**Shipped games:** Flappy Bird â€¢ Space Invaders â€¢ Asteroids

</td>
</tr>
</table>

> ðŸ’¡ *Lesson learned: if you can render a bird flapping through pipes on a 128Ã—64 screen with no game engine, you can render almost anything.*

<br>

### ðŸ“¡ 02 â€” ESP32-C3 Ultra Edition / AI-Pocket v1.0

<table>
<tr>
<td width="30%" valign="top">

**Platform**
- ðŸ§  ESP32-C3 SuperMini
- ðŸ–¥ï¸ OLED 128Ã—64

</td>
<td width="70%" valign="top">

My first real dive into **the internet and power efficiency**. This is where hardware and firmware started talking to each other directly:

- ðŸ”‹ **Battery Guardian** â€” a physical voltage-divider circuit paired with firmware to monitor and catch battery drain/leakage in real time
- âŒ¨ï¸ A custom **6-button virtual keyboard** for full text input, wired up to query **Google Gemini 2.0 Flash**
- ðŸ“» An internet-free **radio messaging system** built on **ESP-NOW Mesh Networking**

</td>
</tr>
</table>

> ðŸ’¡ *Lesson learned: you don't need Wi-Fi to build a network â€” you need a protocol and a reason to talk to your neighbors.*

<br>

### ðŸŽ¬ 03 â€” ESP32-S3 Media Hub v9.1

<table>
<tr>
<td width="30%" valign="top">

**Platform**
- ðŸ§  ESP32-S3 N16R8
- ðŸ–¥ï¸ TFT ST7789 (320Ã—170)

</td>
<td width="70%" valign="top">

Leveling up to **color displays** and real web data processing:

- ðŸŽžï¸ `.mjpeg` video playback via **DMA**, powered by **LovyanGFX** & **JPEGDEC**
- ðŸ›°ï¸ Real-time API integrations: **ISS Tracker**, **NASA APOD**, and **Groq AI** (parsed with `ArduinoJson`)
- ðŸ§© 2D game AI using a **Breadth-First Search (BFS)** pathfinding algorithm for enemy movement in Pacman and Tank Battle

</td>
</tr>
</table>

> ðŸ’¡ *Lesson learned: BFS isn't just a whiteboard interview question â€” it's what makes a Pacman ghost feel like it's actually hunting you.*

<br>

### ðŸ“· 04 â€” SANZXCAM v6.1 *(Terminal Aesthetic Camera)*

<table>
<tr>
<td width="30%" valign="top">

**Platform**
- ðŸ§  ESP32-S3
- ðŸ“¸ 16-bit DVP Camera
- ðŸ§­ MPU6050 Gyroscope
- ðŸ–¥ï¸ ILI9341 Display

</td>
<td width="70%" valign="top">

A deep dive into **image processing and system stability**:

- ðŸŒ€ **Kalman Filtering** sensor fusion on the gyroscope for real-time **Electronic Image Stabilization (EIS)** on the viewfinder
- ðŸŒ¤ï¸ **HDR Triple Capture** for wider dynamic range shots
- ðŸï¸ A **Dynamic Island**â€“style UI with **sprite-based restoration** to keep animations buttery smooth without tearing
- ðŸ§  On-device analysis via **Gemini 2.5 Flash Lite** (Mood Reader, ANPR/plate recognition)
- ðŸ” A working **steganography** feature â€” hiding encrypted payloads inside a JPEG's **COM marker** and a BMP's **LSB bits**

</td>
</tr>
</table>

> ðŸ’¡ *Lesson learned: stabilizing a handheld viewfinder with a $2 gyroscope taught me more about sensor fusion than any tutorial ever could.*

<br>

### ðŸŽ§ 05 â€” RYNE Engine â€” Bluetooth Music Player v1.4.0

<table>
<tr>
<td width="30%" valign="top">

**Platform**
- ðŸ§  ESP32-WROVER
- ðŸ–¥ï¸ OLED SSD1306
- ðŸ”Š Bluetooth Speaker (A2DP Source)

</td>
<td width="70%" valign="top">

The **big leap into local Edge Machine Learning**:

- ðŸ§® A **Softmax Multiclass Vibe Classifier** â€” a genuinely self-learning model living in PSRAM that **retrains itself every 5 minutes**, inferring the user's mood from skip-rate and volume patterns
- ðŸŽ² **RYNE-CRS**, a custom recommendation algorithm (deliberately *not* UCB1) built on **Bayesian probability** and a **power-law curiosity** model to balance familiar vs. novel tracks
- ðŸ˜ƒ Expressive **face animations on the OLED**, synced with a dedicated **FreeRTOS task on Core 1** that watches the audio buffer's health to keep playback glitch- and race-condition-free

</td>
</tr>
</table>

> ðŸ’¡ *Lesson learned: an AI model doesn't need a data center â€” it needs a well-scoped problem and a PSRAM chip that isn't afraid of a little math.*

<br>

### ðŸ“± 06 â€” Accretion Phone â€” *running nyx OS v84* **(The Masterpiece)**

<table>
<tr>
<td width="30%" valign="top">

**Platform**
- ðŸ§  ESP32-S3
- ðŸ–¥ï¸ ILI9341 (Resistive Touch)
- ðŸ§­ MPU6050
- ðŸ’¾ SD Card (SDIO 1-bit)

</td>
<td width="70%" valign="top">

The **culmination of every project above** â€” a fully custom smartphone-like device, built from the ground up on the bare Arduino framework across **13,000+ lines of code, with no real OS underneath**.

- ðŸ”’ **Lock screen** with a genuine glassmorphism effect
- ðŸ  **Home screen** with smooth momentum scrolling (low-pass velocity + decay) and a flicker-free wallpaper â€” thanks to aggressive **double buffering / canvas sprite** optimization in PSRAM
- ðŸ“¦ **26 built-in applications**
- ðŸ¤– **Gemini AI integration**, including voice dictation via an **INMP441 mic** and a **hand-written manual JSON parser** (no `ArduinoJson`) to save every possible byte of RAM
- ðŸ“¡ **OTA updates** over Wi-Fi or SD card
- ðŸŽ® A dedicated **Game Mode** running *"Inferno"* â€” a **3D raycasting FPS** in the spirit of DOOM/Wolfenstein, holding a stable **16 FPS** with persistent **autosave to SD card**

</td>
</tr>
</table>

> ðŸ’¡ *This isn't just a phone. It's every lesson from G-BOX to RYNE Engine, compressed into a device that fits in your pocket.*

---

## ðŸ› ï¸ Tech Stack

<table>
<tr>
<td valign="top" width="25%">

**Languages**

![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)

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
- SSD1306 Â· ST7789 Â· ILI9341
- MPU6050 Â· INMP441
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

## ðŸ”— Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/)
[![Instagram](https://img.shields.io/badge/Instagram-%40sanzx__project.id-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/sanzx_project.id)

</div>

---

<div align="center">

> *"Mastery isn't a single breakthrough â€” it's accretion. It's ten thousand small, unglamorous hours of debugging, rewiring, and rewriting, quietly fusing together until one day the dust becomes a planet."*

**â€” SanzX**

</div>