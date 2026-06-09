# vibe-coding-hackathon-2026-code-with-utkarsh
Hackathon team repository for Code with Utkarsh - [hackindia-team:vibe-coding-hackathon-2026:code-with-utkarsh]

# 🌊 PranAI - AI Mental Wellness for Indian Students

> **⚠️ Hackathon Submission Notice:** This is a **demo/prototype** version developed for the Vibe Coding Hackathon 2026. The app demonstrates core concepts with simulated AI responses and mock data. Full production version with real-time AI integration is under active development.

[![Hackathon](https://img.shields.io/badge/Hackathon-Vibe%20Coding%202026-blue)]()
[![Flutter](https://img.shields.io/badge/Flutter-3.x-blue)]()
[![Firebase](https://img.shields.io/badge/Firebase-Demo-orange)]()
[![Status](https://img.shields.io/badge/Status-Prototype-yellow)]()

## 🎯 Problem Statement

**The Silent Crisis in Indian Education**

- **87%** of Indian students experience exam-related anxiety
- **1 in 4** teenagers report feeling persistently sad or hopeless  
- **70%** never seek help due to stigma, lack of access, or fear of judgment
- **₹1500-3000/session** - Traditional therapy is unaffordable for most families

**The Gap:** Parents want to help but are often left in the dark. Students want support but fear being judged.

## 💡 Our Solution: PranAI

**PranAI** (Sanskrit for "life force" / "breath of life") is an AI-powered mental wellness platform that bridges the gap between students and parents through:

| Feature | Description | Status |
|---------|-------------|--------|
| 🤖 **AI Companions** | 24/7 available AI friends with different personalities | ✅ Demo Ready |
| 👨‍👩‍👧‍👦 **Parent Alerts** | Real-time notifications for concerning emotional patterns | ✅ Demo Ready |
| 🎮 **Gamified Wellness** | Shell collection, daily streaks, achievements | ✅ Demo Ready |
| 🛡️ **Safety System** | 4-level prankster detection & parent verification | ✅ Demo Ready |
| 📊 **Daily Summaries** | AI-generated wellbeing insights for parents | ✅ Demo Ready |

## 🏗️ Tech Stack
┌─────────────────────────────────────────────────────────────┐
│ Frontend │
│ Flutter / Dart │
├─────────────────────────────────────────────────────────────┤
│ Backend │
│ Firebase (Auth, Firestore, FCM) │
├─────────────────────────────────────────────────────────────┤
│ AI/ML │
│ Mock AI Responses (Demo) │
│ (GPT-5.4 Mini API planned for production) │
├─────────────────────────────────────────────────────────────┤
│ Notifications │
│ Local Notifications (Demo) / FCM (planned) │
└─────────────────────────────────────────────────────────────┘


## 📱 Features Demonstrated

### 👤 Student Side

| Feature | Description | Demo Status |
|---------|-------------|-------------|
| AI Chat Interface | Chat with 4 unique AI personalities (Alex, Jordan, Taylor, Casey) | ✅ Working |
| Emotional Analysis | Demo keyword-based emotion detection | ✅ Working |
| Ocean-themed UI | Calming visual design with animations | ✅ Working |
| Parent Status Card | Shows parent connection status | ✅ Working |
| Shell Collection | Earn shells for positive habits | ✅ Working |
| Daily Streaks | Track consistency and achievements | ✅ Working |

### 👨‍👩‍👧 Parent Side

| Feature | Description | Demo Status |
|---------|-------------|-------------|
| Real-time Alerts | Push notifications for student concerns | ✅ Working |
| Insight Dashboard | View child's emotional wellness trends | ✅ Working |
| Actionable Tips | "Say this, try this" suggestions | ✅ Working |
| Emergency Helplines | Quick access to crisis resources | ✅ Working |
| Daily Summaries | AI-generated wellbeing reports | ✅ Working |

### 🛡️ Safety Features

| Feature | Description | Demo Status |
|---------|-------------|-------------|
| 4-Level Prankster Detection | Progressive warnings and consequences | ✅ Working |
| Parent Verification | Mandatory parent contact for pranksters | ✅ Working |
| Emergency Protocols | Clear steps + helpline integration | ✅ Working |

## 🔄 Demo Flow

### Scenario 1: Student Stress → Parent Alert
Student logs in → Opens AI chat with "Alex"

Types: "I'm really stressed about my upcoming exams"

AI responds with empathetic message

Parent receives push notification instantly

Parent views insight: "Your child seems to be under exam pressure"

Parent gets actionable tip: "Say 'I love you no matter what marks you get'"


### Scenario 2: Student Achievement → Parent Celebration
Student shares: "I finally finished my project!"

AI detects positive pattern

Parent receives celebration alert

Suggested response: "I'm proud of your hard work!"


## 📸 UI Preview

### Student Dashboard
┌─────────────────────────────────┐
│ 🌊 PranAI Ocean │
│ ┌─────────────────────────┐ │
│ │ 😊 Mood: 85% Positive │ │
│ │ 😴 Sleep: 72% Good │ │
│ │ 🧘 Meditation: 14 days │ │
│ │ 🤖 AI Sessions: 52 │ │
│ └─────────────────────────┘ │
└─────────────────────────────────┘



### AI Chat Interface
┌─────────────────────────────────┐
│ 🤖 Alex ● online │
│ ┌─────────────────────────┐ │
│ │ Alex: Hi! How are you │ │
│ │ feeling today? 🧘 │ │
│ └─────────────────────────┘ │
│ ┌─────────────────────────┐ │
│ │ User: I'm stressed │ │
│ └─────────────────────────┘ │
│ ┌─────────────────────────┐ │
│ │ Alex: Take a deep breath│ │
│ │ You've got this. 🧘 │ │
│ └─────────────────────────┘ │
└─────────────────────────────────┘


### Parent Dashboard
┌─────────────────────────────────┐
│ 🏡 House Harbor │
│ ┌─────────────────────────┐ │
│ │ Today's Emotional Weather│ │
│ │ 😊 Calm & Happy │ │
│ │ Stress: 3/10 │ │
│ └─────────────────────────┘ │
│ 🔔 New Insight Available │
└─────────────────────────────────┘

## 🚀 Demo Credentials

| Role | Email | Password |
|------|-------|----------|
| **Student** | utkarsh@test.com | any |
| **Parent** | parent@test.com | any |

> **Note:** These are demo accounts for testing. All data is mock data.

## 📂 Project Structure
lib/
├── screens/
│ ├── ai_chat/ # AI companion chat system
│ │ ├── ai_chat_interface.dart
│ │ ├── ai_chat_home.dart
│ │ └── ai_character_creator.dart
│ ├── parent/ # Parent dashboard & alerts
│ │ ├── parent_dashboard.dart
│ │ └── parent_notifications_screen.dart
│ ├── chat/ # Student chat system
│ │ ├── chat_hub_screen.dart
│ │ ├── friend_chat_screen.dart
│ │ └── add_friend_screen.dart
│ └── auth/ # Authentication flows
├── services/ # Firebase, AI, Notifications
├── models/ # Data models
└── widgets/ # Reusable components

text

## 🛠️ Local Setup (for judges)

```bash
# Clone repository
git clone https://github.com/HackIndiaXYZ/vibe-coding-hackathon-2026-code-with-utkarsh.git

# Navigate to project
cd prana

# Install dependencies
flutter pub get

# Run the app
flutter run
📊 Impact Metrics (Projected for Full Version)
Metric	Target
Students reached (Year 1)	50,000+
Reduction in unreported issues	85%
Parent satisfaction rate	90%
Cost to students	₹0 (Free)

🎯 What Makes PranAI Unique
Feature	Other Apps	PranAI
Parent involvement	❌ No	✅ Yes
Real-time alerts	❌ No	✅ Yes
Privacy protection	❌ Often compromised	✅ Parents never see chats
Indian context	❌ Western focus	✅ Designed for Indian students
Cost	💰 Expensive	🆓 Free


🔮 Future Roadmap (Post-Hackathon)

Phase 1: Real GPT API integration for natural conversations

Phase 2: Video call support with AI characters

Phase 3: Peer support groups for students

Phase 4: Professional counselor integration

Phase 5: Regional language support (Hindi, Tamil, Telugu, etc.)

⚠️ Important Note for Judges
**This is a DEMO/PROTOTYPE version developed for the Vibe Coding Hackathon 2026. The app demonstrates:**

✅ Working UI/UX flows
✅ Functional parent alert system
✅ Simulated AI responses (keyword-based)
✅ Push notification system
✅ Complete navigation and screens

Currently in demo mode with:

Mock AI responses (not real GPT)

Local notifications (not cloud FCM)

Simulated data

Full production version would include:

Real GPT-5.4 Mini API integration

Cloud-based push notifications

Real-time database sync

Scalable backend infrastructure

👥 Team
Team Code with Utkarsh

Utkarsh - Lead Developer (Full-stack Flutter + Firebase)
