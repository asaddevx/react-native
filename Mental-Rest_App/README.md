
# 🧠 Mind Space

[![Expo](https://img.shields.io/badge/Expo-54.0.12-blue?logo=expo&logoColor=white)](https://expo.dev/)
[![React Native](https://img.shields.io/badge/React_Native-0.81.4-61DAFB?logo=react&logoColor=black)](https://reactnative.dev/)
[![Firebase](https://img.shields.io/badge/Firebase-12.4.0-FFCA28?logo=firebase&logoColor=black)](https://firebase.google.com/)
[![Gemini AI](https://img.shields.io/badge/Gemini_AI-Google-8E75FF?logo=googlegemini&logoColor=white)](https://ai.google.dev/)

**Mind Space** is a sophisticated mental wellness ecosystem built with React Native. It combines AI-driven therapy insights, mood analytics, and a supportive community to help users navigate their mental health journey with precision and privacy.
---

## 🎯 The Problem We Saw

Millions of people struggle silently with their mental health every day. The barriers are real:

- 😰 **Stigma & Judgment** — Fear of being labeled "weak" prevents people from seeking help
- 💸 **Therapy is Expensive** — Professional sessions cost $100–$250 per hour, out of reach for most
- 📱 **Fragmented Solutions** — Meditation apps, journaling tools, and mood trackers exist in isolation
- ⏰ **No 24/7 Support** — Mental health crises don't follow business hours
- 🔐 **Privacy Concerns** — People fear their most vulnerable thoughts being exposed or sold

> *The result?* Silent suffering, delayed intervention, and preventable crises.

---
## 💡 The Solution We Built

**Mind Space** is not just another wellness app — it's a **complete mental ecosystem** designed to remove every barrier mentioned above:

| Problem | Our Solution |
|:--------|:-------------|
| **Stigma** | Anonymous community posting + optional identity hiding |
| **Cost** | 100% free AI-powered therapy companion (Gemini AI) |
| **Fragmentation** | All-in-one: Mood + Journal + Chat + Resources + Community |
| **24/7 Support** | AI companion available anytime, anywhere |
| **Privacy** | Biometric lock + encrypted journal entries + Firebase security rules |

### 🧠 What Makes Mind Space Different?

- **AI That Listens, Not Just Responds** — Gemini AI doesn't give generic advice. It analyzes sentiment patterns and offers context-aware guidance tailored to your emotional state.
- **Crisis Detection** — When language indicates severe distress, the app immediately surfaces emergency helplines and local resources.
- **Your Data, Your Rules** — Journal entries are encrypted. Community posts can be anonymous. Biometric lock keeps curious eyes away.
- **From Loneliness to Belonging** — The AI-moderated community ensures supportive interactions while filtering harmful content.

---
## 📸 App Preview

<div align="center">

### 🔐 Authentication Flow

| Loading Screen | Home Screen | Login | Sign Up | Forgot Password |
|:---:|:---:|:---:|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/751a88aa-cf36-4f21-a1b0-f7df60d5b876" width="150"/> | <img src="https://github.com/user-attachments/assets/f9e35794-3d8e-4612-b8f1-b681b75ca292" width="150"/> | <img src="https://github.com/user-attachments/assets/f90f4602-0cb0-485d-9240-156cba4d5196" width="150"/> |<img src="https://github.com/user-attachments/assets/fa17811c-1bf9-43d8-87fb-b469ea05ad4b" width="150"/> |<img src="https://github.com/user-attachments/assets/63b4f640-9c8a-4f5e-a625-236d411ee479" width="150"/> |

---

### 🏠 Dashboard & Journals

| User Dashboard | Journals | Profile Settings |
|:---:|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/2210afcc-c9c7-44ec-b6f0-5fc65e31803d" width="180"/> | <img src="https://github.com/user-attachments/assets/bd87c6d0-92db-4c96-afe2-7c134edd061d" width="180"/> | <img src="https://github.com/user-attachments/assets/34c7e883-1695-410d-be01-ec5587ae5734" width="180"/> |

---

### 🧠 Core Wellness Features

| Mood Tracker | AI Chat | Resources | Community |
|:---:|:---:|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/fb7f5268-e194-4233-a2ac-e4ff55d39e84" width="180"/> | <img src="https://github.com/user-attachments/assets/29292a8a-7e28-4f87-b857-72a0fdce42ea" width="180"/> |<img src="https://github.com/user-attachments/assets/d3f6ee33-094b-45aa-b1b8-532d0192a3f9" width="180"/> | <img src="https://github.com/user-attachments/assets/49709643-0a5c-4671-8bde-fcb09f7add08" width="180"/> |

<br>

*✨ Your complete wellness companion ✨*

</div>

---

## 🚀 Key Features

* **🤖 AI Mental Health Companion:** Integrated Google Gemini AI for context-aware wellness guidance and crisis detection.
* **📊 Advanced Mood Analytics:** Track moods (1-10 scale) against 12+ life factors like sleep, work, and relationships.
* **🔐 Secure Journaling:** Private, encrypted thought-logging with mood-tagging and favorite functionality.
* **🌐 Supportive Community:** An AI-moderated social space for sharing tips, stories, and milestones anonymously or publicly.
* **📚 Resource Hub:** Smart-categorized wellness articles and exercises generated and updated via AI.
* **🔑 Biometric Security:** Fingerprint/FaceID integration for sensitive data protection.

---

## 🛠️ Technical Stack

| Category | Technology |
| :--- | :--- |
| **Frontend** | React Native (Expo SDK 54), TypeScript |
| **Navigation** | Expo Router (File-based) |
| **Backend** | Firebase (Auth, Firestore, Storage) |
| **Intelligence** | Google Gemini Generative AI |
| **Styling** | Expo Linear Gradient, Native StyleSheet |
| **Charts** | React Native Chart Kit |

---

## 📂 Project Structure (Core)

```bash
app/
├── (auth)/       # Authentication flow (Login, Register, Biometrics)
├── (tabs)/       # Main Navigation (Home, Mood, Chat, Journal, Community)
├── community/    # Community Feed & Interaction logic
└── services/     # AI, Firebase, and Photo processing logic
```
## 📦 Key Dependencies

| Package | Purpose |
|:--------|:--------|
| `expo` | React Native framework |
| `expo-router` | File-based navigation |
| `firebase` | Auth, Firestore, Storage |
| `@google/generative-ai` | Gemini AI integration |
| `react-native-chart-kit` | Mood analytics charts |
| `react-native-reanimated` | Smooth animations |
| `react-native-keychain` | Biometric security |
| `zustand` | State management |

---
## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)


---

## ✨ Mental-Rest App Key Highlights

- **AI-Powered Mental Wellness Companion** — A calming React Native mobile app designed to support mental health and emotional well-being
- **Gemini AI Integration** — Intelligent sentiment analysis and personalized mental health insights using Google’s Gemini AI
- **Mood Tracking & Journaling** — Daily mood logging with AI-generated reflections and recommendations
- **Relaxation & Mindfulness Features** — Guided breathing exercises, calming sounds, and peaceful UI
- **Modern TypeScript Architecture** — Clean, type-safe codebase with Zustand for state management
- **Smooth Animations** — Beautiful transitions powered by Reanimated 3
- **Cross-Platform Excellence** — Consistent and responsive experience on both iOS and Android
- **Privacy-First Design** — Sensitive emotional data handled with care and local-first principles

A thoughtful and intelligent mental wellness application that combines AI with empathetic design to help users improve their emotional health.
---
## 📊 Project Analytics

<p align="center">
  <!-- Mental-Rest App Project Stats -->
  <img src="https://github-readme-stats-fast.vercel.app/api/pin/?username=asaddevx&repo=react-native&theme=tokyonight&hide_border=true&bg_color=0a192f&border_radius=20" alt="Mental-Rest App Project Stats" />

  <!-- Top Languages -->
  <img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=asaddevx&repo=react-native&layout=compact&theme=tokyonight&hide_border=true&bg_color=0a192f&border_radius=20&langs_count=8" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React_Native-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React Native" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Gemini_AI-8E75FF?style=for-the-badge" alt="Gemini AI" />
  <img src="https://img.shields.io/badge/Zustand-FF4081?style=for-the-badge" alt="Zustand" />
  <img src="https://img.shields.io/badge/Reanimated-FF6F00?style=for-the-badge" alt="Reanimated" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B67F?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="NativeWind" />
  <img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" alt="Expo" />

  <p align="center">
  <img src="https://img.shields.io/badge/Built_With-React_Native-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Powered_By-Gemini_AI-8E75FF?style=flat-square&logo=googlegemini&logoColor=white" />
  <img src="https://img.shields.io/badge/Backend-Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black" /> 
  <img src="https://img.shields.io/badge/Security-Biometric-00C853?style=flat-square&logo=fingerprint&logoColor=white" />  
  </p>  
</p>

---

## 📫 Connect with the Architect

<div align="center">
  <p><strong>SYSTEMS_STATUS: ReactNative_System_OPERATIONAL 🟢</strong></p>
  <p>Let's build something disruptive. 🚀</p>

  <a href="https://asad-lime-six.vercel.app/">
    <img src="https://img.shields.io/badge/VIEW_PORTFOLIO-282c34?style=for-the-badge&logo=vercel&logoColor=61AFEF" alt="Portfolio" />
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/asad-ullah-5475a4352/">
    <img src="https://img.shields.io/badge/LINKEDIN-282c34?style=for-the-badge&logo=linkedin&logoColor=0A66C2" alt="LinkedIn" />
  </a>
  &nbsp;
  <a href="mailto:asadullah.devop@gmail.com">
    <img src="https://img.shields.io/badge/SEND_EMAIL-282c34?style=for-the-badge&logo=gmail&logoColor=E06C75/n/n" alt="Email" />
  </a>
</div>




<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=23272e&height=30&section=footer" />
</p>

---

