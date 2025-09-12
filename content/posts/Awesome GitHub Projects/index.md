+++
date = '2025-09-03T18:40:10-07:00'
draft = false
title = 'Awesome GitHub Projects'
description = "A curated collection of interesting and high-quality projects I discovered on GitHub."
summary = "Showcasing inspiring open-source work that caught my attention on GitHub."
tags = ["open-source", "posts"]
+++

# Awesome GitHub Projects 🚀

This page is dedicated to showcasing interesting, inspiring, or technically impressive projects I’ve discovered on GitHub.  
Each entry follows a simple format for consistency.

---

### 📌 Project: [OctoBot](https://github.com/Drakkar-Software/OctoBot)

**Description:**  
OctoBot is an open-source cryptocurrency trading bot designed to provide flexible, automated trading strategies. It supports multiple exchanges, offers backtesting capabilities, and enables both beginners and advanced users to experiment with algorithmic trading.  

**Why It’s Interesting:**  
OctoBot stands out because it integrates AI-powered prediction models into trading strategies. Most notably, it allows users to connect to **custom LLMs** via a configurable base URL—making it possible to use alternatives beyond OpenAI models. This flexibility includes support for local AI setups like **Ollama**, which means traders can experiment with running their own prediction models locally. Such extensibility opens the door to more privacy, cost efficiency, and creativity in designing AI-driven trading systems.  

**Tech Stack:**  
- Languages: Python  
- Tools: Docker, AsyncIO, WebSocket, REST APIs  

**Key Features:**  
- Custom **LLM base URL** for predictions (connect to any AI model, not only OpenAI)  
- Seamless integration with **Ollama** for local LLM trading predictions  
- Multi-exchange support with real-time market data  
- Strategy customization with backtesting and simulation  
- Active open-source community and continuous development  


**My Contribution:**
![Github Issue](Screenshot-2025-09-12-15.04.34.png)

---

### 📌 Project: [RustDesk](https://github.com/rustdesk/rustdesk)

**Description:**  
RustDesk is a free, open-source remote desktop software written in Rust. It provides a full-featured alternative to commercial tools like TeamViewer or AnyDesk, enabling secure remote access, desktop sharing, file transfer, and screen control. Unlike many competitors, RustDesk is completely transparent and community-driven, ensuring users retain control over their data and connections.

**Why It’s Interesting:**  
What makes RustDesk stand out is its **ease of deployment** and **flexibility**. By default, it supports both **relay (proxy) connections** and **direct peer-to-peer connections**, meaning it can work reliably across firewalls and NAT environments. For users who want full privacy and independence, hosting a personal RustDesk server is straightforward: running a single lightweight Docker container is often all it takes. This setup not only provides greater control over remote sessions but also removes the need for expensive monthly subscriptions to proprietary remote desktop software—often saving $10 or more per month.  

RustDesk is also designed with **convenience and accessibility** in mind. Its user-friendly interface makes it approachable for non-technical users, while its cross-platform support (Windows, macOS, Linux, iOS, and Android) ensures it fits into almost any environment. The project has an active open-source community that continuously improves stability, performance, and features.

**Tech Stack:**  
- Language: Rust (core implementation)  
- UI: Flutter for cross-platform interfaces  
- Tools: Docker, WebRTC, NAT traversal technologies  

**Key Features:**  
- 🔑 End-to-end encryption for secure remote sessions  
- 🔄 Support for both relay and direct P2P connections  
- 🐳 Easy self-hosting with a simple Docker container  
- 💻 Cross-platform: Windows, macOS, Linux, iOS, Android  
- 📂 File transfer, clipboard sync, and multi-monitor support  
- 🌍 Open-source, with an active and fast-growing community  



<!-- ## Template for Each Project

### 📌 Project: [Project Name](https://github.com/username/repo)

**Description:**  
_A short summary of what this project does (2–3 sentences)._

**Why It’s Interesting:**  
_A brief note on why I found this project valuable or inspiring (e.g., unique idea, strong technical implementation, great documentation, etc.)._

**Tech Stack:**  
- Language(s):  
- Framework/Tools:  

**Key Features:**  
- Feature 1  
- Feature 2  
- Feature 3  

---

## Example (Placeholder)

### 📌 Project: [Example Project](https://github.com/example/example)

**Description:**  
This is a placeholder project description. It explains what the project does in a concise way.  

**Why It’s Interesting:**  
I found it inspiring because of its elegant implementation and practical use case.  

**Tech Stack:**  
- Languages: Python, JavaScript  
- Tools: Docker, Flask  

**Key Features:**  
- Clean architecture  
- Great documentation  
- Active community support -->
