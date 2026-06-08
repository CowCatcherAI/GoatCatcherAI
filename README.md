# GoatCatcherAI 🐐

As part of the **CowCatcherAI** open-source ecosystem, **GoatCatcherAI** is the newest member of the family. This repository is specifically tailored for goat and sheep farmers, focusing on automated **kidding (birth) detection** and **heat/estrus detection (mounting behavior)**.

By combining computer vision and local AI agents, GoatCatcherAI provides real-time insights and instant notifications to help farmers protect their livestock during crucial moments.

---

## 🔄 How it Works

📷 Kidding Pen Camera  ──→ 🤖 AI Computer Vision (YOLO) ──→ ⚡ Event Detection (Kidding / Mounting) ──→ 💽 Save Event Image ──→  📲 Telegram Notification with Image & AI Reasoning

---

## 🚀 Features & Technology

We combine multiple cutting-edge, open-source technologies to create a reliable monitoring system that runs on the core [AI Detector](https://github.com/ESchouten/ai-detector) software:

* **Computer Vision:** Powered by **Ultralytics YOLO** for real-time tracking and behavior detection (mounting, restlessness, labor positions).
* **Thermal Imaging Support:** Optimized for IP cameras with thermal lenses. This allows the system to accurately detect heat signatures of the doe/ewe and the newborn kid, identify the exact moment of birth, and perform a final check to confirm the newborn is alive and moving.
* **Local AI Agents:** Integrates with lightweight, locally hosted vision-language models like **Qwen 2.5-VL / Qwen 3.0** and **Moondream AI** (fine-tuned with kidding/lambing context) to analyze images. Alternatively, it can connect to cloud-based LLM APIs.
* **Smart Alerts:** Instant Telegram notifications including the captured image and the AI agent's expert reasoning.

---

## 🤝 Join the Movement: Looking for Beta Testers! 📢

GoatCatcherAI is currently in **active development**, and we need your help to make it perfect! 

Are you a **goat or sheep farmer**, researcher, or tech enthusiast? We are actively looking for interested partners to:
* Test the software in real-world kidding pens.
* Help collect and annotate data to train an ultra-accurate model for goats and sheep.

📩 **Interested?** Reach out to us at: **cowcatcherai@gmail.com** and help us bring smart farming to the caprine community!

---

## 🌿 The CowCatcherAI Family

GoatCatcherAI runs on top of the shared family codebase. Check out the other repositories:

* **[Main CowCatcherAI Repo](https://github.com/CowCatcherAI/CowCatcherAI):** The origin of the project (focused on cattle).
* **[AI Detector](https://github.com/ESchouten/ai-detector):** The main software base and core detection engine used by GoatCatcherAI.
* **[Annotation Helper](https://github.com/JacobsFarm/annotation_helper_cowcatcherai):** Tooling to help annotate images for training our models.

---

## 📄 License

This project uses the **GNU Affero General Public License v3.0 (AGPL-3.0)**. It is based on Ultralytics YOLO and is fully open source.

> ⚠️ **IMPORTANT NOTICE:** This software and its trained models are **NOT authorized for commercial use or distribution** without explicit permission.

---

## 🙏 Acknowledgments

This project is made possible by the amazing [Ultralytics YOLO](https://github.com/ultralytics/ultralytics) library. Their state-of-the-art computer vision technology forms the foundation of our behavior detection. 

**Thank you, Ultralytics team!** 🚀 For making cutting-edge AI technology available to help farmers worldwide.

---

## 🤝 Contributing

This is an open-source project. You may modify, improve, and adapt it to your specific farm setup. Contributions are highly welcome via Pull Requests!

<img width="2048" height="2048" alt="GoatCatcherAI Mascot" src="https://github.com/user-attachments/assets/ffdb8a70-6aa4-4ae3-b6da-7813b5b9fa7b" />
