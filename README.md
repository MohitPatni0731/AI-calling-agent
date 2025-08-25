# 🎙️ AI Medical Appointment Scheduler

A voice-powered AI receptionist that helps schedule medical appointments naturally and efficiently. Built with Vapi.ai, this demo showcases how AI can streamline the appointment booking process.

## 🌟 Live Demo

Try the live demo here: [AI Medical Scheduler Demo](https://mohitpatni0731.github.io/AI-calling-agent)

**🔗 Shareable Link**: https://mohitpatni0731.github.io/AI-calling-agent
**🔗 Demo video Link**: https://drive.google.com/file/d/11mpgFHwHV5ml7grLgGGBc1xJ2bt9zqt-/view?usp=sharing

## 🤖 Meet Riley - Your AI Receptionist

Riley is a friendly AI assistant that:
- Schedules new medical appointments
- Collects patient information systematically
- Offers available time slots
- Provides confirmation codes
- Handles appointment reminders

## 💡 Key Features

- **Natural Conversation**: Uses GPT-4 for human-like interactions
- **Structured Data Collection**:
  - Full Name
  - Date of Birth
  - Contact Number
  - Visit Reason
  - Preferred Date/Time
- **Smart Scheduling**: Pre-configured slots with fallback options
- **Confirmation System**: Unique booking codes (WP-XXXXX format)
- **Safety Features**: Emergency redirection and human handoff options

## 🛠️ Technology Stack

- **Voice AI Platform**: [Vapi.ai](https://vapi.ai)
- **Language Model**: OpenAI GPT-4o Cluster
- **Speech Recognition**: Deepgram Nova-3
- **Background Ambience**: Customized call center environment

## 📋 Sample Conversation Flow

```
Riley: Thank you for calling Wellness Partners. This is Riley, your scheduling assistant. How may I help you today?

You: I'd like to schedule an appointment for tomorrow.

Riley: I'll help you with that. Could you please provide your full name?

[Continues collecting information systematically...]

Riley: Perfect! I've booked your appointment for tomorrow at 10 AM with Dr. Chen. Your confirmation code is WP-12345.
```

## 🚀 Available Appointment Slots (Demo)

- Tomorrow 10:00 AM - Dr. Chen (Primary Care)
- Tomorrow 2:30 PM - NP Taylor (Primary Care)
- Day after tomorrow 3:00 PM - Dr. Rao (Urgent Care)
- Fallback: Next business day at 9:00 AM or 1:30 PM

## 💻 Try It Yourself

1. Visit our [live demo page](https://mohitpatni0731.github.io/AI-calling-agent)
2. Click the "Start" button in the widget
3. Allow microphone access when prompted
4. Start speaking with Riley!

## 🔒 Privacy & Consent

- All conversations are recorded for quality and training
- User consent is required before starting
- Data handling follows healthcare privacy best practices

## 🌐 Local Development

```bash
# Clone the repository
git clone https://github.com/mohitpatni/AI-calling-agent.git

# Navigate to the project
cd AI-calling-agent

# Serve the demo page locally
python -m http.server 8000

# Visit http://localhost:8000/docs/index.html
```

## 📝 Future Enhancements

- Multi-language support
- Integration with real calendar systems
- Expanded medical specialties
- Custom appointment slot configuration
- Real SMS/email reminder system

## 🤝 Contributing

Feel free to open issues or submit pull requests if you have suggestions for improvements!

## 📄 License

MIT License - feel free to use this demo as a starting point for your own voice AI projects.

---

Built with ❤️ by [Mohit Patni](https://github.com/mohitpatni)
