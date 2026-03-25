# 🏠 Real Estate AI Voice Agent

AI-powered real estate assistant that enables users to search properties, qualify leads, and book site visits using natural voice conversations.

🚀 Built using Vapi + n8n + Google Sheets

---

## 🎥 Product Demo

🚀 Real-time AI voice interaction for property search, lead capture, and booking:

<p align="center">
  <img src="demo/demo(1).gif" width="750"/>
</p>

### 📥 Full Demo (HD)

- ▶️ [Watch Demo](https://drive.google.com/file/d/1HLYoi09bnUb8kbgvZxPirqebUu0AkSjo/view?usp=drive_link)  
- ⬇️ [Download Demo (39.5 MB)](https://drive.google.com/uc?export=download&id=1HLYoi09bnUb8kbgvZxPirqebUu0AkSjo)

---

## 🎯 Features

- 🔊 Voice-based property search
- 🧠 Intelligent query understanding (location, budget, BHK, type)
- 🏠 Smart property matching & ranking
- 📋 Multi-property suggestions with selection handling
- 👤 Lead capture with property context
- 📅 Automated site visit booking (natural date/time)
- 🔁 End-to-end automation workflow

---

## 🧠 How It Works

1. User speaks query (e.g., "2 BHK in Mumbai under 70 lakhs")
2. Agent extracts structured filters
3. n8n searches property database
4. Agent presents best options
5. User selects a property
6. Lead details captured (name + phone)
7. Booking scheduled (date + time)
8. Data stored in CRM (Google Sheets)

---

## ⚙️ Tech Stack

- Vapi (Voice AI)
- n8n (Automation workflows)
- Google Sheets (Database / CRM)
- JavaScript (logic in n8n nodes)

---

## 🔄 Workflow Architecture

```
Voice Input
↓
Vapi Assistant
↓
n8n Webhook
↓
Search Properties Flow
↓
Lead Capture Flow
↓
Booking Flow
↓
Google Sheets (Leads + Bookings)
```

---

## 🧪 Example Use Case

User: "I want a 2 BHK in Mumbai around 70 lakhs"

→ Agent suggests properties  
→ User selects option  
→ Lead captured  
→ Visit booked for "next Monday at 5 PM"  

---

## 🚧 Future Improvements

- Slot availability & double booking prevention
- WhatsApp confirmation automation
- Admin dashboard for leads & bookings

## 🤝 Use Cases

- Real estate agencies
- Property marketplaces
- AI automation demos
- Voice-first applications

---

## 💡 Author

Built by Meet Koli

---

⭐ If you like this project, give it a star!
