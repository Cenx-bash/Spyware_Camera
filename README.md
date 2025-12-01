&lt;!-- SPDX-License-Identifier: GPL-3.0-or-later --&gt;
&lt;!-- DISCLAIMER: This repository is for EDUCATIONAL PURPOSES ONLY. Misuse is illegal and unethical. --&gt;

&lt;p align="center"&gt;
  &lt;img src="https://techchip.net/wp-content/uploads/2020/04/camphish.jpg" alt="CamPhish logo" width="200"/&gt;
&lt;/p&gt;

&lt;h1 align="center"&gt;CamPhish – Ethical Camera-Access Red-Team Tool&lt;/h1&gt;

&lt;p align="center"&gt;
  &lt;a href="https://github.com/techchipnet/CamPhish/releases"&gt;&lt;img src="https://img.shields.io/github/v/release/techchipnet/CamPhish?include_prereleases"/&gt;&lt;/a&gt;
  &lt;a href="https://www.gnu.org/licenses/gpl-3.0"&gt;&lt;img src="https://img.shields.io/badge/License-GPL%20v3-blue.svg"/&gt;&lt;/a&gt;
  &lt;a href="https://www.youtube.com/techchipnet"&gt;&lt;img src="https://img.shields.io/badge/YouTube-TechChip-red?style=flat&logo=youtube"/&gt;&lt;/a&gt;
&lt;/p&gt;

---

## ⚠️ LEGAL & ETHICAL NOTICE
This project is **strictly intended for authorized penetration-testing engagements, red-team exercises, and academic research**.  
**Using CamPhish against anyone without explicit, written consent is illegal and unethical.**  
By proceeding you agree to:
1. Only deploy on devices you **own** or have **explicit permission** to test.
2. Comply with all local, state, and national laws.
3. Indemnify the authors from any misuse or damage.

---

## 📖 What is CamPhish?
CamPhish is a lightweight red-team framework that demonstrates **social-engineering** and **browser-permission** attacks.  
It spins up a local PHP server, tunnels it via **ngrok** or **Cloudflare Tunnel**, and serves a **single, convincing web page** that requests camera (and optionally GPS) permissions. If the target consents, the tool captures:
- **Still images** from the front-facing camera / webcam
- **GPS coordinates** (when available)
- **Device architecture & browser metadata**

---

## ✨ Key Features
| Feature | Description |
|---------|-------------|
| 🎭 **Multi-template engine** | Festival greeting, YouTube Live, Online meeting, or custom HTML |
| 🌍 **GPS tracking** | Optional one-click location capture with Google-Maps preview |
| 🔧 **Auto-architecture** | Detects ARM, ARM64, x86, x86_64, Apple Silicon |
| 🧹 **Clean-up mode** | One-command removal of logs, images, and temp files |
| 🚇 **Dual tunnel** | ngrok & Cloudflare Tunnel for high-availability links |
| 🖥️ **Cross-platform** | Kali, Parrot, Ubuntu, macOS, Termux, Windows-WSL |

