# 🏠 StayMate — AI Co-Host for Airbnb Hosts

**StayMate** is an AI-powered virtual co-host that automates guest communication and streamlines operations for Airbnb and short-term rental hosts.  
It integrates GPT and Gemini language models to deliver instant, personalized replies and workflow automation — giving hosts more time and better guest experiences.

---

## 🚀 Features
- 🤖 AI Guest Messaging (inquiries, check-in/out, FAQs)
- ⚡ Instant 3-second response times using GPT/Gemini APIs
- 🔁 Automated workflows via Zapier and LangChain
- 🧭 Smart scheduling for cleanings and maintenance
- 💬 Custom tone & personality per host

---

## 🧠 Tech Stack
- **Languages:** Python, JavaScript  
- **Frameworks:** Flask, FastAPI  
- **AI Models:** GPT-4, Gemini  
- **Automation Tools:** Zapier, LangChain  
- **Cloud:** AWS (Lambda, S3), Firebase  
- **Database:** PostgreSQL  

---
## 🧪 Live Testing Examples

These screenshots show real automation tests conducted with an Airbnb host account using StayMate’s AI Co-Host system.

- Auto-replied guest inquiries within **3 seconds**
- Personalized check-in and check-out messages
- Triggered cleaning task reminders post-departure
- Host received summary confirmation email after setup

(*All examples anonymized to protect guest privacy*)

---

## 🧩 Architecture
```mermaid
graph TD;
    User-->StayMate_UI;
    StayMate_UI-->StayMate_API;
    StayMate_API-->AI_Models;
    StayMate_API-->Database;
    AI_Models-->Response;
    Database-->Automation;
    Automation-->Host_Notifications;


