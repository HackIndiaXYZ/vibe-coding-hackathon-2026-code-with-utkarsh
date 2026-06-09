# vibe-coding-hackathon-2026-code-with-utkarsh
Hackathon team repository for Code with Utkarsh - [hackindia-team:vibe-coding-hackathon-2026:code-with-utkarsh]


## PranAI - AI Mental Wellness for Indian Students

**Project:** PranAI  
**Team:** Code with Utkarsh  
**Hackathon:** Vibe Coding Hackathon 2026  
**Status:** Demo/Prototype
```

# 🌊 PranAI - AI Mental Wellness for Indian Students
# PranAI means---> "Intelligence that nurtures your life energy."
> **⚠️ Hackathon Submission Notice:** Demo/Prototype version for Vibe Coding Hackathon 2026. Full production version with real-time AI integration in development.

<div align="center">

[![Hackathon](https://img.shields.io/badge/Hackathon-Vibe%20Coding%202026-blue)]()
[![Flutter](https://img.shields.io/badge/Flutter-3.x-blue)]()
[![Firebase](https://img.shields.io/badge/Firebase-Demo-orange)]()
[![Status](https://img.shields.io/badge/Status-Prototype-yellow)]()

</div>

---

## 🎯 Problem Statement

| Statistic | Reality |
|-----------|---------|
| **87%** | Indian students experience exam-related anxiety |
| **1 in 4** | Teenagers feel persistently sad or hopeless |
| **70%** | Never seek help due to stigma or fear |
| **₹1500-3000** | Cost of traditional therapy per session |

**The Gap:** Parents want to help but are left in the dark. Students want support but fear judgment.

---

## 💡 Our Solution: PranAI

> *PranAI* (Sanskrit for "life force") - AI-powered mental wellness platform

| Feature | Description | Status |
|---------|-------------|--------|
| 🤖 **AI Companions** | 24/7 AI friends with different personalities | ✅ Demo Ready |
| 👨‍👩‍👧‍👦 **Parent Alerts** | Real-time notifications for emotional patterns | ✅ Demo Ready |
| 🎮 **Gamified Wellness** | Shell collection, streaks, achievements | ✅ Demo Ready |
| 🛡️ **Safety System** | 4-level prankster detection & verification | ✅ Demo Ready |
| 📊 **Daily Summaries** | AI-generated wellbeing insights for parents | ✅ Demo Ready |

---

## 🏗️ Tech Stack

```
┌─────────────────────────────────────────────────────────────┐
│                      FRONTEND                               │
│                    Flutter / Dart                           │
├─────────────────────────────────────────────────────────────┤
│                       BACKEND                               │
│              Firebase (Auth, Firestore)                     │
├─────────────────────────────────────────────────────────────┤
│                      AI / ML                                │
│      Mock AI Responses (Demo) / GPT API (Planned)           │
├─────────────────────────────────────────────────────────────┤
│                    NOTIFICATIONS                            │
│        Local Notifications (Demo) / FCM (Planned)           │
└─────────────────────────────────────────────────────────────┘
```

---

## 📱 Features Demonstrated

### 👤 Student Side

| Feature | Description | Status |
|---------|-------------|--------|
| AI Chat Interface | 4 unique personalities | ✅ Working |
| Emotional Analysis | Keyword-based detection | ✅ Working |
| Ocean-themed UI | Calming visual design | ✅ Working |
| Shell Collection | Earn shells for habits | ✅ Working |
| Daily Streaks | Track consistency | ✅ Working |

### 👨‍👩‍👧 Parent Side

| Feature | Description | Status |
|---------|-------------|--------|
| Real-time Alerts | Push notifications | ✅ Working |
| Insight Dashboard | Wellness trends | ✅ Working |
| Actionable Tips | "Say this" suggestions | ✅ Working |
| Emergency Helplines | Crisis resources | ✅ Working |

### 🛡️ Safety Features

| Feature | Description | Status |
|---------|-------------|--------|
| 4-Level Prankster Detection | Progressive warnings | ✅ Working |
| Parent Verification | Mandatory contact | ✅ Working |
| Emergency Protocols | Helpline integration | ✅ Working |

---

## 🔄 Demo Flow

### 📚 Scenario 1: Student Stress → Parent Alert

```
1. Student logs in → Opens AI chat with "Alex"
2. Types: "I'm really stressed about my upcoming exams"
3. AI responds with empathetic message
4. Parent receives push notification instantly
5. Parent views insight & actionable tip
```

### 🎉 Scenario 2: Student Achievement → Parent Celebration

```
1. Student shares: "I finally finished my project!"
2. AI detects positive pattern
3. Parent receives celebration alert
4. Suggested response: "I'm proud of your hard work!"
```

---

## 📸 UI Preview

### 🏠 Student Dashboard

```
┌─────────────────────────────────────┐
│         🌊 PranAI Ocean             │
├─────────────────────────────────────┤
│  😊 Mood Tracking      ████████░ 85%│
│  😴 Sleep Quality      ███████░░ 72%│
│  🧘 Meditation Streak  14 days      │
│  🤖 AI Sessions        52 sessions  │
└─────────────────────────────────────┘
```

### 💬 AI Chat Interface

```
┌─────────────────────────────────────┐
│  🤖 Alex                    ● online│
├─────────────────────────────────────┤
│  ┌───────────────────────────────┐  │
│  │ Alex: Hi! How are you         │  │
│  │ feeling today? 🧘             │  │
│  └───────────────────────────────┘  │
│  ┌───────────────────────────────┐  │
│  │ User: I'm stressed about      │  │
│  │ my exams                      │  │
│  └───────────────────────────────┘  │
│  ┌───────────────────────────────┐  │
│  │ Alex: Take a deep breath.     │  │
│  │ You've got this. 🧘           │  │
│  └───────────────────────────────┘  │
└─────────────────────────────────────┘
```

### 🏡 Parent Dashboard

```
┌─────────────────────────────────────┐
│         🏡 House Harbor             │
├─────────────────────────────────────┤
│  Today's Emotional Weather          │
│  ┌───────────────────────────────┐  │
│  │  😊 Calm & Happy              │  │
│  │  Stress Level: 3/10           │  │
│  │  Sleep Quality: Excellent     │  │
│  └───────────────────────────────┘  │
│                                      │
│  🔔 New Insight Available            │
│  ┌───────────────────────────────┐  │
│  │ "Your child seems to be       │  │
│  │  handling stress well today"  │  │
│  └───────────────────────────────┘  │
└─────────────────────────────────────┘
```

---

## 📂 Project Structure

```
lib/
├── screens/
│   ├── ai_chat/          # AI companion chat system
│   │   ├── ai_chat_interface.dart
│   │   ├── ai_chat_home.dart
│   │   └── ai_character_creator.dart
│   ├── parent/           # Parent dashboard & alerts
│   │   ├── parent_dashboard.dart
│   │   └── parent_notifications_screen.dart
│   ├── chat/             # Student chat system
│   │   ├── chat_hub_screen.dart
│   │   ├── friend_chat_screen.dart
│   │   └── add_friend_screen.dart
│   └── auth/             # Authentication flows
├── services/             # Firebase, AI, Notifications
├── models/               # Data models
└── widgets/              # Reusable components
```

---

## 🚀 Demo Credentials

| Role | Email | Password |
|------|-------|----------|
| 👨‍🎓 **Student** | utkarsh@test.com | any |
| 👨‍👩‍👧 **Parent** | parent@test.com | any |

> **Note:** Demo accounts for testing. All data is mock data.

---

## 🛠️ Local Setup

```bash
# Clone repository
git clone https://github.com/HackIndiaXYZ/vibe-coding-hackathon-2026-code-with-utkarsh.git

# Navigate to project
cd prana

# Install dependencies
flutter pub get

# Run the app
flutter run
```

---

## 📊 Impact Metrics (Projected)

| Metric | Target |
|--------|--------|
| Students reached (Year 1) | 50,000+ |
| Reduction in unreported issues | 85% |
| Parent satisfaction rate | 90% |
| Cost to students | **₹0 (Free)** |

---

## 🎯 What Makes PranAI Unique

| Feature | Other Apps | **PranAI** |
|---------|------------|-------------|
| Parent involvement | ❌ No | ✅ **Yes** |
| Real-time alerts | ❌ No | ✅ **Yes** |
| Privacy protection | ❌ Compromised | ✅ **Parents never see chats** |
| Indian context | ❌ Western focus | ✅ **Designed for Indian students** |
| Cost | 💰 Expensive | 🆓 **Free** |

---

## 🔮 Future Roadmap

- [ ] **Phase 1:** Real GPT API integration
- [ ] **Phase 2:** Video call support with AI characters
- [ ] **Phase 3:** Peer support groups for students
- [ ] **Phase 4:** Professional counselor integration
- [ ] **Phase 5:** Regional language support

---

## ⚠️ Important Note for Judges

**This is a DEMO/PROTOTYPE** for Vibe Coding Hackathon 2026.

### ✅ Working in Demo:
- UI/UX flows
- Parent alert system
- Push notifications
- Complete navigation
- Simulated AI responses

### 🔄 Demo Mode Features:
- Mock AI responses (keyword-based)
- Local notifications
- Simulated data

### 🚀 Production Version Will Include:
- Real GPT-5.4 Mini API
- Cloud push notifications (FCM)
- Real-time database sync
- Scalable backend infrastructure

---

## 👥 Team

### **Code with Utkarsh**

| Role | Name |
|------|------|
| Lead Developer | Utkarsh |

*Full-stack Flutter + Firebase development*

---

## 📝 License

MIT License - See [LICENSE](LICENSE) file

---

<div align="center">

**Made with ❤️ for India's Students**

*"Mental wellness is not a luxury, it's a necessity"*


</div>
```

---

