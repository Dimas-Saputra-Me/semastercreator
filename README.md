# 🚀 SeMasterCreator: AI-Powered Social Media Content Generated Automation with n8n

This project showcases how **n8n workflows** can fully automate the process of **content creation, transformation, and distribution** using API integrations, AI prompts, and scheduling — all without writing traditional backend code.

---

## 🌌 What It Does

This project uses a visual **n8n workflow** to:

1. 🔮 Generate content (short-video) using AI models (seedance).
2. 🗓️ Schedule and trigger publishing automatically.
3. 🔁 Format and distribute content across:
   - YouTube (Shorts with title + description)
   - Facebook Pages
   - Instagram Posts/Reels
   - TikTok (future integration)
4. 📊 Track delivery and response logs via Google Sheets/API logs.

---

## 🛠️ Built With

- ⚙️ **[n8n](https://n8n.io/)** — Visual workflow automation (self-hosted)
- 🧠 **Seedance** — For AI-driven content generation (text-to-video)
- 🌐 **Social Media APIs** — For social media publishing (via Meta and Google API)

---

## 📁 Project Structure

/ root\
├── index.html # Homepage\
├── README.md # This file\
└── workflows/ # n8n workflow templates\

---

## 🧩 n8n Workflow Overview

```plaintext
[Generate Ideas] → [Text-to-Video] → [Text-to-Music] → [Combine Video + Music] → [Log/Notify] → [Publish to Social Media] → [Log/Notify]
```

Each workflow is modular, allowing you to reuse it across platforms and customize trigger conditions or content logic.

## 📷 Live Demo
You can view the SeMasterCreator project in action:

🌐 Homepage: https://semastercreator.vercel.app

Explore our automated cosmic content across platforms by visiting our social media accounts linked on the homepage!

## 🧠 Credits & Inspirations

This project is **refactored and combined** from these amazing original creators:

- 🤖 **[RoboNuggets](https://www.youtube.com/@RoboNuggets)** — Content AI Generation Workflows  
- 🛰️ **[dainami_ai](https://www.youtube.com/@dainami_ai)** — Social Media Publishing Automation

> 🚧 *SeMasterCreator* is a unified and extended version built upon their concepts — redesigned for multi-platform publishing, AI-enhanced generation, and full automation with improved modularity.
