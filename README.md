<img width="1862" height="1082" alt="image" src="https://github.com/user-attachments/assets/84ce7e11-671a-4d9f-bf43-9e24d1501a59" /># 🌌 Clauzey 2.0 (CLAUZEY-V1)

<div align="center">

![Clauzey Hero Banner](<img width="1862" height="1082" alt="image" src="https://github.com/user-attachments/assets/d01716e4-560d-433e-8cfc-b4630daa1bd6" />
)

### **Next-Generation Multi-LLM Orchestration Desktop Engine**
*Local-First • Privacy-Centric • Multi-Agent Consensus • Ultra-Lightweight*

[![Release](https://img.shields.io/badge/Official%20Release-v2.0.0-blue.svg?style=for-the-badge&logo=github)](https://github.com/devanshd07o/CLAUZEY-V1/releases)
[![Platform](https://img.shields.io/badge/Platform-Windows%20x64-0078D6.svg?style=for-the-badge&logo=windows)](https://github.com/devanshd07o/CLAUZEY-V1/releases)
[![Security](https://img.shields.io/badge/Security-Local--First%20%7C%20Zero--Telemetry-22C55E.svg?style=for-the-badge&logo=shield)](https://github.com/devanshd07o/CLAUZEY-V1#%EF%B8%8F-safety-privacy--security-architecture)
[![License](https://img.shields.io/badge/Evaluation-2--Month%20Free%20Trial-F59E0B.svg?style=for-the-badge)](https://github.com/devanshd07o/CLAUZEY-V1)

---

### [🚀 Download Windows Installer (`Clauzey-Setup-2.0.0.exe`)](https://github.com/devanshd07o/CLAUZEY-V1/releases)
#### [⚡ Download Standalone Portable (`Clauzey-Portable-2.0.0.exe`)](https://github.com/devanshd07o/CLAUZEY-V1/releases)

[✨ Features](#-key-features) • [🖼️ Interface Showcase](#%EF%B8%8F-interface-showcase) • [🛡️ Safety & Security](#%EF%B8%8F-safety-privacy--security-architecture) • [📥 Installation Guide](#-installation-guide) • [⚙️ Low-End PC Boost](#-low-end-pc-performance-mode)

</div>

---

## 📖 What is Clauzey?

**Clauzey 2.0** is a desktop engine that orchestrates today's leading AI models on your machine:

* **Claude** (Anthropic): Sonnet 5 on free accounts, up to Opus 5 / Fable 5.1 on paid
* **ChatGPT** (OpenAI): GPT-5.6 Luna on free accounts, GPT-6 Astra / GPT-5.6 Sol on paid
* **DeepSeek**: V4.1 Flash / V4 series
* **Grok** (xAI): Grok 4.x family (Grok 4.6 on paid)
* **Perplexity**: Sonar-powered live web search with citations
* **Gemini** (Google): Gemini 3.6 Flash family

*Models run through your own logged-in sessions or your own API keys. Which exact model you get depends on your account tier.*

Instead of juggling 6 browser tabs and dealing with fragmented context, Clauzey gives you a unified, luxury command center where frontier models work together in **specialized multi-agent councils**, **parallel comparisons**, and **automated fallback synthesis**.

---

## 🖼️ Interface Showcase

### 1. Multi-Model Parallel Orchestration (Live Comparison)
Compare responses from Claude 3.7, GPT-4o, and DeepSeek R1 side-by-side with rich syntax-highlighted code execution blocks and instant copy tooling.
![Multi Model Orchestration](assets/screenshots/01_multi_model_orchestration.png)

---

### 2. Council War Room (Consensus Blueprint & Interactive Data Tables)
Deploy multi-agent deliberation: **Chief Architect (Claude)**, **Live Web Intel (Perplexity)**, and **Chaos Lead (DeepSeek)** deliberate in parallel to compile an authoritative production blueprint with interactive tables.
![Council War Room](assets/screenshots/02_council_war_room.png)

---

### 3. Developer Identity & Onboarding Flow
Personalize your AI collaboration environment with custom developer persona grounding, technical domain calibration, and directive refinement.
![Developer Onboarding](assets/screenshots/03_developer_onboarding.png)

---

### 4. Appearance & Typography Studio (25+ Programming Fonts)
Switch between 30+ precision light/dark themes and 25+ curated coding fonts with instant live preview.
![Appearance & Typography](assets/screenshots/04_settings_appearance.png)

---

## 🛡️ Safety, Privacy & Security Architecture

Clauzey was built with a non-negotiable **Local-First, Zero-Trust** security foundation:

### 🔒 1. 100% Local SQLite Persistence (Zero Telemetry)
* **No Telemetry, No Analytics, No External Tracking**: Every single prompt, response, code snippet, and session is stored exclusively in your local SQLite database (`%APPDATA%\Clauzey\clauzey.db`).
* **Offline-Ready Data Layer**: Clauzey does not send telemetry pings, behavioral tracking data, or prompt analytics to any central server. Your data stays on your hardware.

### 🛡️ 2. Isolated Chromium Session Partitions
* Each AI provider operates inside an isolated Chromium WebContents partition (`persist:clauzey_*`).
* Authentication cookies, session tokens, and localStorage entries are strictly compartmentalized. Google accounts, Claude logins, and OpenAI sessions cannot share state, leak cookies, or cross-track activity.

### 🕶️ 3. Stealth Anti-Bot Masquerading
* Built-in real Chromium User-Agent emulation (`Chrome/132.0.6834.196`) and automated flag stripping (`disable-blink-features: AutomationControlled`).
* Seamless "Continue with Google" OAuth flows without COOP/COEP interference, preventing bot detection or account flags during web-session routing.

### 🔑 4. Zero-Leak Credential Vault
* When utilizing Bring-Your-Own-Key (BYOK) APIs (Anthropic, OpenAI, Groq, Perplexity, OpenRouter), keys are transmitted strictly via secure HTTP headers (`x-goog-api-key`, `Authorization: Bearer`).
* Credentials are never exposed in URL query parameters and never output to debug logs or crash dumps.

### ⏱️ 5. Tamper-Proof Monotonic License Guard
* Includes a built-in **2-Month Free Evaluation Period** (active through **November 21, 2026**).
* Uses local monotonic clock drift checks to prevent system clock rollbacks, without requiring an invasive internet "phone-home" requirement.

---

## ⚡ Key Features

| Mode / Feature | Architectural Description |
| :--- | :--- |
| **Council War Room** | 3 specialized frontier models collaborate simultaneously (Architect + Live Web Intel + Chaos Lead) to synthesize an authoritative Consensus Blueprint. |
| **Super Mixture-of-Agents (MoA)** | Multi-layer ensemble where proposer models generate diverse candidate drafts before a master synthesizer unifies the optimal response. |
| **Parallel Compare** | Ask any prompt across up to 6 frontier models simultaneously and compare output depth, speed, and accuracy side-by-side. |
| **Sequential Relay** | Chain multiple models where output from one step automatically primes the context of the next specialist. |
| **Low-End PC Performance Mode** | 1-click toggle in Settings that disables transitions, strips GPU backdrop blurs, and halts WebGL canvas loops for instant 60 FPS operation on budget laptops. |
| **Integrated Code Runner** | Sandboxed native runner for executing code snippets directly from the chat interface. |
| **Live Typography Sync** | Real-time font switching across 25+ curated coding fonts (JetBrains Mono, Fira Code, Inter, Plus Jakarta Sans, Victor Mono). |
| **Global Quick Capsule** | Summon Clauzey instantly from anywhere on your desktop via global shortcut (`Ctrl+Alt+Space` / `Cmd+Alt+Space`). |

---

## 🚀 Low-End PC Performance Mode

Have a budget laptop or low-end machine? Clauzey includes a dedicated **Performance Boost Mode**:
* **Transitions Clamped to 0ms**: Eliminates UI latency and animation lag.
* **GPU Blurs Stripped**: Removes costly `backdrop-filter: blur(...)` shaders.
* **Canvas Loops Paused**: Suspends real-time WebGL/2D fluid dot waves during typing and idle.
* **Opaque High-Contrast Surfaces**: Replaces heavy semi-transparent glass with crisp, readable solid theme layers.

Toggle it anytime in **Settings ➔ Appearance ➔ Smooth Animations & Motion**.

---

## 📥 Installation Guide

### Option 1: Standard Windows Installer (Recommended)
1. Download **[`Clauzey-Setup-2.0.0.exe`](https://github.com/devanshd07o/CLAUZEY-V1/releases)** from the Releases section.
2. Double-click the installer:
   * Select your preferred install location (defaults to user directory with zero admin UAC prompt needed).
   * Automatically creates Desktop and Start Menu shortcuts.
3. Launch Clauzey and start orchestrating!

### Option 2: Standalone Portable Binary
1. Download **[`Clauzey-Portable-2.0.0.exe`](https://github.com/devanshd07o/CLAUZEY-V1/releases)**.
2. Run directly from your Desktop, SSD, or USB flash drive without installing.
3. All user data is isolated inside a self-contained data directory.

---

## 📋 System Requirements

* **Operating System**: Windows 10 (64-bit) or Windows 11 (64-bit)
* **Processor**: Intel Core i3 / AMD Ryzen 3 or higher
* **Memory**: 4 GB RAM (2 GB with Low-End PC Performance Mode enabled)
* **Disk Space**: 400 MB free space

---

## 📄 License & Evaluation

Clauzey 2.0 is distributed with a **2-Month Free Evaluation License** valid through **November 21, 2026**.

To request enterprise licenses, custom model integrations, or developer activation keys (`CLAUZEY-PRO-2026`), contact the developer via the in-app About tab.

---

<div align="center">

**[Download Clauzey 2.0 for Windows](https://github.com/devanshd07o/CLAUZEY-V1/releases)**

*Developed with ❤️ by Devansh • Supreme Multi-LLM Desktop Computing*

</div>
