

<p align="center">
<a href=""><img title="Python3" src="https://img.shields.io/badge/Python-3-yellow?style=for-the-badge&logo=python"></a>
<a href=""><img title="Flask" src="https://img.shields.io/badge/Backend-Flask-black?style=for-the-badge&logo=flask"></a>
<a href=""><img title="MongoDB" src="https://img.shields.io/badge/Database-MongoDB-green?style=for-the-badge&logo=mongodb"></a>

</p>

# 🛡️ CyberX

### *Understanding, Preventing, and Responding to Cyberbullying in Real-Time*

---

## 🚨 Problem Statement

Cyberbullying involves posting, sharing, or spreading harmful, abusive, hateful, or offensive content online.

In today’s digital world, toxic content spreads faster than moderation systems can react.
A single viral post can trigger:

* Online harassment
* Hate speech
* Public shaming
* Threats and abuse
* Mental health impact

Current moderation systems suffer from:

1. Heavy reliance on manual moderators
2. Delayed response time
3. Poor scalability
4. Lack of contextual understanding
5. Reactive moderation instead of proactive prevention

CyberX aims to solve this problem using AI-powered real-time cyberbullying detection and reporting.

---

# ✨ Getting Started

CyberX is a **multi-layered cyber-forensic framework** designed to detect, moderate, analyze, and report offensive content across social media platforms.

The framework combines:

* 🧠 Natural Language Processing (BERT)
* 👁️ Computer Vision (ResNet)
* ⚡ Real-time browser protection
* 📊 Dashboard-based forensic monitoring
* 🛡️ Smart reporting and moderation tools

---

## ⚙️ What Did We Use?

<a href="https://huggingface.co/"><img height="42" src="https://i.imgur.com/4bUNd79.png" /></a>

---

# 🌟 Key Features

* [x] Real-time toxicity detection on social media posts/comments
* [x] Browser extension that automatically blurs harmful content
* [x] BERT-based text toxicity classification
* [x] ResNet-based offensive image analysis
* [x] Centralized forensic reporting dashboard
* [x] WhatsApp harmful chat detection
* [x] Instagram toxic comment analysis
* [x] Twitter/X cyberbullying monitoring
* [x] YouTube live comment moderation
* [x] Reporting portal for harmful content
* [x] AI-powered severity scoring system
* [x] Docker-based scalable deployment
* [x] Custom social media sandbox platform (Viraly)

<img width="972" height="547" alt="Screenshot 2026-05-07 at 11 34 16 AM" src="https://github.com/user-attachments/assets/cc25e421-7dc8-4e92-8de7-dee9ef6554a4" />


---

# 🧠 Text Toxicity Prediction 💬

CyberX uses a transformer-based **Toxic-BERT** model trained for multi-label toxicity classification.

### Detects:

1. **toxic** → rude or disrespectful language
2. **severe_toxic** → extremely hateful content
3. **obscene** → vulgar or profane language
4. **threat** → threats of violence or harm
5. **insult** → personal attacks or demeaning content
6. **identity_hate** → attacks on race, religion, gender, etc.

### Why BERT?

We chose BERT because it:

* Understands contextual meaning
* Detects sarcasm and implicit hate
* Reduces false positives
* Uses transformer encoders + attention mechanisms
* Supports scalable real-time moderation

```text
Text Input: You are a stupid person.
======================
Toxic: 0.92
Insult: 0.81
Threat: 0.04
======================
Result: Toxic and insulting content detected.
Action: Content blurred and flagged.
```

---

# 📷 Obscene Image Classification

CyberX also analyzes harmful media using **ResNet-based Computer Vision models**.

### Detects:

* NSFW content
* Offensive visuals
* Harmful media patterns
* Explicit or abusive imagery

### Features:

* Contextual image moderation
* Media + text correlation
* Real-time scanning support
* Integrated dashboard reporting

---

# 🛡️ CyberX Shield — Browser Extension

CyberX Shield acts as a real-time protection layer for users.

### Features:

* Dynamically scans content while scrolling
* Blurs only harmful sections instead of blocking entire pages
* Click-to-reveal mechanism
* Detects newly loaded content instantly
* Links text with associated media for contextual moderation

### Supported Platforms

* YouTube
* Twitter/X
* Instagram
* WhatsApp Web
* Facebook

---

# 📊 Dashboard & Reporting Portal

CyberX includes a centralized forensic dashboard for moderation and reporting.

### Capabilities

* AI-based forensic scoring
* Evidence tracking
* Platform-specific moderation reports
* Toxicity severity analysis
* Real-time monitoring
* Complaint management
* Cross-platform reporting

---

# 🏗️ Architecture Overview

```text
Browser Extension / Social Platforms
                ↓
        Reporting Backend
                ↓
      NLP + Image AI Models
                ↓
             MongoDB
                ↓
     Admin Dashboard & Reports
```

### Workflow

1. Browser extension captures harmful content.
2. Backend APIs process reports.
3. BERT + ResNet models analyze toxicity.
4. Results stored in MongoDB.
5. Dashboard visualizes insights and reports.

---

# ⚙️ Tech Stack

| Category          | Technology                     |
| ----------------- | ------------------------------ |
| Frontend          | HTML, CSS, JavaScript          |
| Backend           | Flask                          |
| Database          | MongoDB                        |
| NLP               | HuggingFace Transformers, BERT |
| Computer Vision   | ResNet                         |
| Deployment        | Docker                         |
| APIs              | REST APIs                      |
| Browser Extension | Chrome Extension APIs          |

---

# 🔮 Future Scope

* 🎙️ Voice & audio toxicity detection
* 🌍 Multilingual moderation (Hinglish + regional languages)
* ⚡ Real-time moderation APIs
* 🚔 Cybercrime portal integration
* 🧠 Explainable AI (XAI)
* 📈 AI-powered threat prioritization

---

# 👩‍💻 Contributors

| Ananya Bajpai                | Ananya Bhardwaj        | Anushree Jain       | Gauri Aggarwal       |
| ---------------------------- | ---------------------- | ------------------- | -------------------- |
| Reporting Portal & Extension | BERT Toxicity Pipeline | Flask APIs & Viraly | MongoDB & Dashboard  |
| Real-time detection modules  | NLP Model Integration  | Backend Execution   | Backend Optimization |

<img width="972" height="539" alt="Screenshot 2026-05-07 at 11 31 47 AM" src="https://github.com/user-attachments/assets/39211222-e4c3-45ed-9ca7-b059a07e245f" />


---

# 🙌 Acknowledgements

Special thanks to:

* Ms. Devanshi Wangoo


---

# 📌 Vision

> "Cyberbullying is no longer just a social issue — it is a digital safety challenge."

CyberX aims to create a safer, smarter, and more responsible digital ecosystem.

---

# ⭐ Support

If you found this project impactful:

🌟 Star the repository
🍴 Fork the project
📢 Share it with others

---

<p align="center">
  Built with ❤️ by <b>TEAM JEET</b>
</p>

![wave](http://cdn.thekrishna.in/img/common/border.png)

