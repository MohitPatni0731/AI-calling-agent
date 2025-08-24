# 🩺 Voice AI Appointment Scheduler (Demo)

This project is a **Voice AI receptionist demo** built for the **AI Intern position at AI Trusted Advisors**.  
It demonstrates how a conversational voice assistant can **book, reschedule, and confirm medical appointments** in a natural, human-like way.

---

## 🎯 What This Does
- Acts as a **virtual receptionist** for a medical clinic ("Wellness Partners").
- Collects key appointment details:
  - Full Name
  - Date of Birth
  - Callback Phone
  - Visit Reason
  - Preferred Date & Time
- Offers pre-configured appointment slots (demo scheduler).
- Confirms the booking with a **unique confirmation code**.
- Provides option for **text/call reminders** (simulated in this demo).
- Polite, natural, and efficient conversation flow.

---

## ⚙️ How I Built It
This demo was created using **[Vapi.ai](https://vapi.ai/)** with:
- **OpenAI GPT-4o Cluster** for natural conversation.
- **Deepgram Nova-3** for real-time transcription.
- **Predefined scheduling logic** to offer available appointment slots.
- **Custom prompt engineering** to guide the assistant ("Riley") step by step.
- **Voice configuration** with background sound for realistic call ambience.
- **Safety & fallback logic** (emergency redirect, option to forward to human staff).

---

## 🛠️ Steps I Followed
1. **Defined Use Case** → Appointment booking for a medical clinic.
2. **Created the Voice Agent (Riley)** in Vapi:
   - System prompt crafted for scheduling workflow.
   - Configured structured data extraction for logging appointment details.
   - Added polite tone, safety handling, and idle message logic.
3. **Set Up Demo Scheduler**:
   - Tomorrow 10:00 AM with Dr. Chen (Primary Care)  
   - Tomorrow 2:30 PM with NP Taylor (Primary Care)  
   - Day after tomorrow 3:00 PM with Dr. Rao (Urgent Care)  
   - Fallback: Next business day at 9:00 AM or 1:30 PM.
4. **Configured Call Flow**:
   - Greeting → Collect details → Offer slots → Confirm → Provide code → Close politely.
5. **Tested with a sample conversation** (see transcript in repo).
6. **Embedded the widget** so the demo can be experienced directly.

---

## 📹 Demo (Try It Out!)

You can interact with the Voice AI receptionist right here:

<vapi-widget assistant-id="ab41db04-53da-43bf-ba19-3b0a0e98ff46" public-key="4ad11a04-a06c-47cd-b346-5a6fb62b2e03"></vapi-widget>

<script
  src="https://unpkg.com/@vapi-ai/client-sdk-react/dist/embed/widget.umd.js"
  async
  type="text/javascript"
></script>

---

## ✅ Example Flow
**User:** I want to schedule an appointment for tomorrow.  
**Assistant (Riley):** Sure, let’s start with your full name.  
… *(collects info step by step)*  
**Assistant:** Great, I’ve booked you for tomorrow at 10 AM with Dr. Chen. Your confirmation code is **WP-12345**.  

---

## 🚀 Tech Stack
- **Vapi.ai** → Voice AI Platform  
- **OpenAI GPT-4o** → Natural conversation  
- **Deepgram Nova-3** → Speech-to-text  
- **Custom Prompts & Scheduling Logic**  

---

## 📂 Repo Contents
- `README.md` → Project overview & demo widget  
- `config/` → Assistant configuration JSON  
- `transcripts/` → Sample call transcript  
- `docs/` → Screenshots & setup notes  

---

## 🌟 Future Improvements
- Expand to support **hotel reservations** & **HVAC service requests**.  
- Integrate with **real scheduling APIs** (Google Calendar, AthenaHealth, etc.).  
- Add **multi-language support** (English + Spanish).  

---

## ✨ About
This demo was built quickly as part of the **AI Intern hiring challenge**.  
It highlights my ability to design, configure, and deploy **voice AI agents** with natural, structured conversations.  

---
