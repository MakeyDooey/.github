<div align="center">
<img src=https://github.com/MakeyDooey/.github/blob/main/profile/MakeyDooeyLogo_transparent.png width=300px>
</div>

# MAKEY DOOEY

![Status](https://img.shields.io/badge/Status-Open--Source-brightgreen?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Industrial--Grade-blue?style=for-the-badge)
![Focus](https://img.shields.io/badge/Focus-Sustainability-leaf?style=for-the-badge&color=2ecc71)

> **The bridge between hobbyist microcontrollers and industrial PLCs.**
> An end-to-end development platform for real-time control applications, designed with sustainability and robustness in mind.

[**Website**](https://makeydooey.github.io/Software/) | [**Email**](mailto:makeydooey@gmail.com) 

---

## 🏗️ The Ecosystem

MakeyDooey is built for **hard real-time determinism**. Our modular "Totem" system allows for seamless replacement and low-power operation via interlocking, DIN-rail mountable enclosures.

### 🛠️ The Hardware Lineup

| Module | Role | Key Features |
| :--- | :--- | :--- |
| **🧙‍♂️ ShamanLink** | The Programmer | SWD/UART bridge, ultra-low power, IDE gateway. |
| **🗿 Main Totem** | The Brain | Base development board for core logic unit. |
| **⚙️ Motor Totem** | The Muscle | High-current control with built-in drivers for fine motion. |

---

## 🧠 Technical Architecture

Our performance is driven by a **Heterogeneous Dual-Core** firmware architecture to guarantee safety-critical timing.

![Architecture Diagram](https://github.com/MakeyDooey/.github/blob/main/profile/system%20architecture.png)

### Why Dual-Core?
* **M7 Management Core:** Runs a CLI built on **FreeRTOS** for flexible IDE communication.
* **M4 Determinism Core:** Runs a **bare-metal loop** using shared memory to ensure hard real-time execution.
* **Totem Bus:** A common shared bus allowing modules to be daisy-chained with minimal setup.

---

## 🦾 Showcase: The Prosthetic Hand

To demonstrate the precision of the MakeyDooey platform, we’ve developed a flagship demo: **A robotic prosthetic hand.**

* **The Goal:** Perform fine motor gestures required for Rock-Paper-Scissors.
* **The Tech:** Real-time gesture orchestration via the Main Totem and Motor Totem.

---

## 📂 Key Repositories
> ### [💾 Firmware](https://github.com/MakeyDooey/Firmware-ShamanLink)
> Explore the dual-core implementation, shared memory logic, and Totem Bus drivers.
> ### [💻 Software](https://github.com/MakeyDooey/Software)
> Access our WCAG 2.2 compliant PWA IDE built with React and Electron.
> ### [🛠️ Hardware](https://github.com/MakeyDooey/Hardware)
> Access the files to all of our custom hardware. 

---
## 👥 Main Contributors

The core team behind the MakeyDooey ecosystem.

[![](https://img.shields.io/badge/@LeoMattosMartins-808080?style=flat-square)](https://github.com/LeoMattosMartins)
[![](https://img.shields.io/badge/@DomMurphy--git-ADD8E6?style=flat-square)](https://github.com/DomMurphy-git)
[![](https://img.shields.io/badge/@KoenLin-00008B?style=flat-square)](https://github.com/KoenLin)
[![](https://img.shields.io/badge/@vik802-800080?style=flat-square)](https://github.com/vik802)
[![](https://img.shields.io/badge/Jonny--Wu13-FFC0CB?style=flat-square)](https://github.com/Jonny-Wu13)
[![](https://img.shields.io/badge/@BenjaminJoseph123-FFA500?style=flat-square)](https://github.com/BenjaminJoseph123)

---

<div align="center">

`Created with ❤️ for a sustainable, open-source industrial future.`

</div>

<div align="right">
  <img src=https://github.com/MakeyDooey/.github/blob/main/profile/WikeMazowski_transparent.png width=60px>
</div>
