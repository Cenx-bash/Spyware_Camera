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

