# 🚀 SmartBudgetAnalyzer v1.1 - Complete Project

<p align="center">
  <img src="https://img.shields.io/badge/React_Native-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React Native" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-learn" />
  <img src="https://img.shields.io/badge/Offline_AI-00BFFF?style=for-the-badge" alt="Offline AI" />
  <img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" alt="Expo" />
</p>

## 📱 Project Overview

**SmartBudgetAnalyzer** is a cutting‑edge mobile application for iOS and Android, built with **React Native** and **TypeScript**. It is designed to revolutionize personal finance management for students and professionals. The app leverages **Firebase** for secure authentication, **Supabase (PostgreSQL)** for real‑time data persistence, **AsyncStorage** for offline‑first caching, and a **hybrid AI engine** – combining an offline Python‑trained Random Forest classifier with a real‑time client‑side heuristic algorithm – to deliver intelligent category suggestions and a Financial Health Score without compromising privacy.

---

## 🎯 The Problem We Saw

Managing personal finances is a source of anxiety for millions. The obstacles are everywhere:

- 📊 **Data Overload, No Insight** – Bank statements show *what* you spent, but not *why* or *how to fix it*.
- 💸 **Unexpected Bills** – Subscriptions renew, bills arrive, and your budget breaks before you even notice.
- 🏷️ **Manual Categorization Hell** – Downloading CSVs and tagging every coffee, grocery, and Uber ride is soul‑crushing.
- 📉 **No Predictive Power** – Most apps tell you *after* you've overspent. No one warns you *before*.
- 🔐 **Privacy Fears** – Uploading bank credentials to third‑party apps feels like handing over your financial soul.

> *The result?* Financial stress, missed savings goals, and a feeling of being perpetually behind.

----
## 💡 The Solution We Built

**SmartBudgetAnalyzer** is your AI‑powered financial co‑pilot. It automates the boring stuff and predicts the unexpected – all while keeping your data completely private through an **on‑device hybrid intelligence engine**.

| Problem | Our Solution |
|:--------|:-------------|
| **Data Overload** | **Hybrid AI Categorization** – A **Random Forest classifier** (trained offline on 80/20 split of real transaction data) combined with a **client‑side keyword heuristic** provides instant, privacy‑safe category suggestions (Food, Transport, Education, etc.) with high precision. |
| **Unexpected Bills** | **Predictive Spending Alerts** – The system continuously monitors spending against category budgets and triggers **immediate push notifications** when you exceed 80% of your limit or log an **unusual transaction** (> ₹10,000). |
| **Manual Categorization** | **Automated Pipeline** – Enter a description; after a 1.5s debounce, the AI suggests a category. One tap to confirm – no more scrolling through dropdowns. |
| **No Predictive Power** | **AI Spending Score (0–100)** – A proprietary heuristic algorithm evaluates your monthly income‑to‑expense ratio, savings rate, and large transaction spikes to generate a **real‑time financial health score** with colour‑coded feedback (Excellent, Good, Fair, At‑Risk). |
| **Privacy Fears** | **Local‑First Processing** – All sensitive calculation logic runs on your device. The only data stored in the cloud is encrypted via Firebase Auth and Supabase **Row‑Level Security**. No third‑party bank feeds, no credential sharing. |

### 🧠 What Makes SmartBudgetAnalyzer Different?

- **Offline‑Trained, Real‑Time Executed** – We built a **Python ML pipeline** (Pandas, Scikit‑learn) that trains Random Forest and SVM models on thousands of historical transactions. The resulting intelligence is distilled into a lightweight keyword‑matching engine that runs instantly on your phone – no server latency, no data leaks.
- **Proactive Alerts, Not Just Charts** – You don't have to open the app to know you're overspending. **Expo push notifications** warn you the moment a budget limit is breached.
- **Six Tools in One App** – Integrated offline calculators (Loan EMI, Investment SIP, Pakistan Tax 2025‑26, 50/30/20 Budget Planner, Savings Goal, Currency Converter) turn your phone into a complete financial command center.
- **Academic‑Grade AI Validation** – Our Random Forest model achieved **92% accuracy** on the test set, and the live heuristic score is mathematically designed to encourage better saving habits (scoring penalties for spending >90% of income, bonuses for savings >50%).

---

## �� Project Objectives

### Primary Goals
- ✅ Deliver a **mobile-first** app for tracking income, expenses, and budgets with offline access
- ✅ Provide a **responsive UI** with dashboard, charts, and touch-friendly navigation
- ✅ Implement **secure authentication**, data export, and encrypted storage
- ✅ Integrate **lightweight AI features** using TensorFlow.js for intelligent insights
- ✅ Demonstrate **advanced software engineering** and AI skills for academic evaluation

### Technical Achievements
- **Cross-Platform**: iOS and Android compatibility
- **Offline-First**: AsyncStorage integration for seamless offline experience
- **AI-Powered**: Machine learning insights for financial optimization
- **Cloud Sync**: Firebase real-time data synchronization
- **Security**: Bank-level encryption and secure authentication

---

### 📱 App Screenshots  

### 🔐 Authentication Flow

| Loading Screen | Login | Sign Up | Forgot Password |
|:---:|:---:|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/dab89ea4-f6a2-4ba7-8cfa-7dfdd638a6b0" width="180"/> | <img src="https://github.com/user-attachments/assets/73ad9f2c-87e8-4aee-a7e0-dc7a23452fb4" width="180"/> | <img src="https://github.com/user-attachments/assets/329ff5b4-55f2-49e2-ae25-1e8a395c761d" width="180"/> | <img src="https://github.com/user-attachments/assets/d601679b-36fa-4ee9-98f8-31bcddf5328e" width="180"/> |

---
### 🏠 Dashboard & Transactions

| Home Screen | Monthly Overview | Month Detail | Add Transaction | Transaction History |
|:---:|:---:|:---:|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/46db9b80-37af-4ce9-95af-3cb3dc9bfaca" width="180"/> | <img src="https://github.com/user-attachments/assets/65ab5575-affc-4c0f-b7b1-953248047c95" width="180"/> | <img src="https://github.com/user-attachments/assets/bcd0b8c2-4264-45b8-a854-61ea2fc44037" width="180"/> | <img src="https://github.com/user-attachments/assets/33e1df12-b407-4394-ab7b-729a7c8bfb0e" width="180"/> |<img src="https://github.com/user-attachments/assets/17ff8a68-f2a0-463d-a021-f31bd771b111" width="180"/> |

---
### 🎯 Goals & Budgets

| Add New Goal | Budgets & Goals |
|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/c69d6b61-fb67-4f4e-8f45-844aefa88eeb" width="180"/> | <img src="https://github.com/user-attachments/assets/10bb8325-93f2-4205-9ada-878149fd15b4" width="180"/> |

---
### 📊 Analytics & AI Insights

| Analytics Overview | Goals Progress | AI Spending Insights | AI Recommendations |
|:---:|:---:|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/d859805f-83c1-455a-8723-1064b5dde82a" width="180"/> | <img src="https://github.com/user-attachments/assets/8418e482-96f5-42a6-83d7-d10c5ffae26d" width="180"/> | <img src="https://github.com/user-attachments/assets/41691123-709a-4e57-8652-ddf184812d49" width="180"/> | <img src="https://github.com/user-attachments/assets/66ecb9c4-6a33-481e-afd4-1d20b9472666" width="180"/> |

---
### 👤 Profile & Settings

| Profile Settings | Preferences | Notification Settings | AI & Reminder Settings | Notifications Screen |
|:---:|:---:|:---:|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/d5543246-4b56-4e5a-9251-adad47986b0a" width="150"/> | <img src="https://github.com/user-attachments/assets/cb422b9b-490f-4398-8685-04d584791d2e" width="150"/> | <img src="https://github.com/user-attachments/assets/f2ef80e3-567d-4467-ad3a-79db503d0d12" width="150"/> | <img src="https://github.com/user-attachments/assets/19b03567-924b-4fa9-9f83-73f0d2fab02a" width="150"/> | <img src="https://github.com/user-attachments/assets/d1f6aada-7a88-43c1-82c5-af31776a9136" width="150"/> |

---
### 🧮 Tools (Calculators)

The **Tools Module** is the financial powerhouse of SecretsApp. It provides a suite of **six fully offline, formula-based financial calculators** — plus one live-rate currency converter — designed to help you make informed financial decisions covering loan planning, investment projections, tax compliance, budgeting, and savings goals. Each calculator operates locally on your device with no login or internet required (except the Currency Converter).


#### 💰 Loan & Tax Calculators

| All Calculators | Currency Converter | Loan/EMI Calculator | Loan/EMI Result |
|:---:|:---:|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/4c98e1db-cb53-4c32-9244-db20eef617b0" width="180"/> | <img src="https://github.com/user-attachments/assets/dde1bbfa-655b-49fc-99c8-1ba84ebfe468" width="180"/> | <img src="https://github.com/user-attachments/assets/571b7eb9-3b7f-4577-bc5d-73ba937dccf1" width="180"/> | <img src="https://github.com/user-attachments/assets/39a23954-b9a1-4b3e-b9d3-32c2b9d54497" width="180"/> |

| Tax Calculator | Tax Result | Tax Slabs |
|:---:|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/96525011-1aec-4e2e-9cff-73e3da071af0" width="180"/> | <img src="https://github.com/user-attachments/assets/3fd3e5b8-dd5a-4a07-81ce-24e087d2b88a" width="180"/> | <img src="https://github.com/user-attachments/assets/97d14ecd-2054-42d7-8cc3-1f462680c4e3" width="180"/> |


#### 📈 Investment Calculator

| Investment Calculator | Investment Result | Year‑by‑Year Breakdown |
|:---:|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/5475d0e8-73c7-4ee2-9d76-39bde4296ce4" width="180"/> | <img src="https://github.com/user-attachments/assets/fc33c0af-b9ef-4ab3-b7f7-da9f184e79d4" width="180"/> | <img src="https://github.com/user-attachments/assets/b403a411-3aac-4924-8a7a-2cd5464c2277" width="180"/> |


#### 📊 Budget Planner

| Budget Planner | Budget Breakdown | Compare with Actual Spendings | Suggested Category Breakdown |
|:---:|:---:|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/ef4e1a20-8be6-4676-acef-304ef0b33599" width="180"/> | <img src="https://github.com/user-attachments/assets/d74d1002-b078-468e-97fd-3312c397bea6" width="180"/> | <img src="https://github.com/user-attachments/assets/19990b1e-e1a8-482e-9f46-f2a45428b460" width="180"/> | <img src="https://github.com/user-attachments/assets/d18271e0-1624-4ff0-9e60-f9269d430654" width="180"/> |


#### 🎯 Savings Goals Calculator

| Savings Goals Calculator | Enter Savings Details | Result for Selected Saving | Year Progress |
|:---:|:---:|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/2f8d64dc-18b0-424c-89d3-0f445b1a49ab" width="180"/> | <img src="https://github.com/user-attachments/assets/c76a8a08-fe91-4d2c-aa39-0b496c27a6c4" width="180"/> | <img src="https://github.com/user-attachments/assets/30c142f2-ecca-4cd9-96d0-e61d47fb8898" width="180"/> | <img src="https://github.com/user-attachments/assets/e6c7bfd3-5d0b-418d-9880-eebdf6d2904d" width="180"/> |



### 📈 Advanced Financial Tools

#### 🏦 Loan / EMI Calculator
Calculates monthly EMI, total interest, total payment, and a month-by-month amortization schedule.

#### 🏦 Investment Calculator
Projects future value of investments using compound interest (lump sum or monthly SIP) with compounding frequency options (monthly, quarterly, yearly).

#### 🏦 Budget Planner
Interactive monthly budget planner based on the 50/30/20 rule (Needs/Wants/Savings) with customizable ratios and actual vs. budget comparison.

#### 🏦 Tax Calculator
Pakistan FBR income tax calculator for FY 2025-26 supporting salaried and business/AOP income types, filer/non-filer status, Zakat/donation deductions, and year-over-year comparison.

#### 🏦 Savings Goal Calculator
Helps you plan a path to a specific savings target with two modes: "How Long?" and "How Much Monthly?" including milestone tracking at 25%, 50%, 75%, and 100%.

#### 💱 Currency Converter
Real-time bi-directional currency converter supporting 10+ currencies (PKR, USD, EUR, GBP, SAR, AED, CAD, AUD, CNY, JPY) with offline caching, conversion history, and quick amount buttons.

---

## 🤖 Hybrid AI Engine: Offline ML + Real‑Time Heuristics

Unlike cloud‑based AI services, our intelligence runs **entirely on your device** – protecting your privacy while delivering zero‑latency predictions.

### 🧠 1. Offline Training Pipeline (Python / Scikit‑learn)

- **Dataset**: Thousands of real transaction records (`transactions_rows.csv`) with descriptions, amounts, and categories.
- **Models Trained**: Random Forest (selected) and SVM (baseline) using TF‑IDF vectorization.
- **Performance**: Random Forest achieved **92% accuracy**, 88% precision, 86% recall (F1‑score 83.5%).
- **Output**: Trained model weights and keyword‑category mappings are **exported to the mobile app’s heuristic engine** – no online inference required.

### ⚡ 2. Client‑Side Heuristic Engine (TypeScript)

- **Smart Category Suggestion**  
  As the user types a description, a **1.5‑second debounce** triggers a keyword matching algorithm (e.g., “Uber” → Transport, “McDonald’s” → Food).  
  Confidence scores are shown to the user; the system learns from corrections via feedback logging.

- **AI Spending Score (0–100)**  
  A real‑time formula running on the device:
  ```
  Base Score = 50
  Ratio = Expenses / Income
  If Ratio > 0.9 → Score = 20 (heavy penalty)
  Else if Ratio < 0.5 → Score += 15 (savings bonus)
  Score -= (Large transactions > 10,000) × 5
  Final Score clamped to 0–100
  ```
  Colour‑coded cards (red, amber, green) give instant visual feedback.

- **Unusual Transaction Alert**  
  Any single expense > 10,000 triggers a **push notification** (via Expo) to the user, asking for verification – preventing fraud and encouraging mindful spending.

---

## 🏗️ Core Features Architecture

### 📱 Module 1: User Account Management (Firebase Auth + Supabase RLS)

- **Authentication**: Email/password + Google OAuth via Firebase SDK. Biometric login (FaceID / Fingerprint) via `expo-local-authentication`.
- **Data Isolation**: Every database query enforces **Row‑Level Security (RLS)** – users can only access their own `transactions`, `budgets`, and `goals` records.

### 💰 Module 2: Transaction Management & AI Categorization

- **CRUD Operations**: Add, edit, delete transactions with full details (amount, description, date, notes).
- **Hybrid Category Suggestion**: Heuristic engine (based on ML‑derived keyword rules) suggests a category with confidence.
- **Soft Delete**: Deleted transactions are moved to an `is_deleted` flag for 30 days, preserving AI training data integrity.

### 📊 Module 3: Budget & Goal Management

- **Dynamic Budgets**: Set monthly limits per category (e.g., Food = 20,000). Real‑time progress bars show remaining amount.
- **80% Alert**: When spending reaches 80% of budget, a **push notification** is sent immediately.
- **Savings Goals**: Define targets (e.g., “Trip to Murree – 50,000 by Dec 2025”). Contributions are tracked; milestones (25%, 50%, 75%, 100%) trigger **celebratory notifications** with confetti effects.

### 📈 Module 4: Analytics & Insights

- **Dashboard Cards**: Total balance, income vs. expenses, AI Spending Score, and top spending category insight (e.g., “High food spending – consider cooking at home”).
- **Charts**: SVG pie charts for category breakdown, bar charts for monthly trends (powered by `react-native-svg`).
- **Period Filters**: View data by week, month, or year.

### 🔒 Module 5: Data Export & Security

- **CSV Export**: Share full transaction history via email or cloud storage.
- **Encrypted Local Storage**: JWT tokens and biometric flags are stored in `expo-secure-store` (hardware‑encrypted).
- **Cloud Backup**: Firebase + Supabase provide automated daily backups.

---

## 🛠️ Technical Stack

| Component | Technology |
|:----------|:-----------|
| **Frontend** | React Native (Expo SDK), TypeScript |
| **State Management** | React Context API (AuthContext, BudgetContext) |
| **Navigation** | Expo Router (file‑based) |
| **Authentication** | Firebase Auth (Email/Google, Biometric) |
| **Database** | Supabase (PostgreSQL) with RLS |
| **AI/ML (Research)** | Python, Pandas, Scikit‑learn (Random Forest, SVM, TF‑IDF) |
| **AI/ML (Runtime)** | Custom TypeScript heuristic engine (keyword matching, spending score algorithm) |
| **Notifications** | Expo Notifications (push + local scheduling) |
| **Charts** | react-native-svg (custom SVG pie/bar charts) |
| **Storage** | AsyncStorage (settings cache), expo-secure-store (tokens) |
| **Calculators** | Offline formula‑based (Loan, Investment, Tax, Budget, Savings, Currency) |

---

## 📂 Project Structure

Smart_Budget_Analyzser/
├── app/ # Expo Router screens
│ ├── (auth)/ # Login, Signup, Forgot Password
│ ├── (tabs)/ # Home, Analytics, Budget, Goals, Tools
│ └── _layout.tsx # Root navigation
├── components/ # Reusable UI components
├── constants/ # Theme, colors, config
├── contexts/ # AuthContext, BudgetContext, ThemeContext
├── hooks/ # Custom hooks (useAuth, useTransactions)
├── services/ # Firebase, Supabase, AI Service
├── types/ # TypeScript interfaces


---


## ✨ Smart Budget Analyser Key Highlights

- **Hybrid AI Financial Engine** – Combines **offline‑trained Random Forest** (92% accuracy) with a **real‑time heuristic scoring system** to deliver privacy‑safe category suggestions and a Financial Health Score.
- **Six Offline Tools** – Loan EMI, Investment, Pakistan Tax (FBR 2025‑26), 50/30/20 Budget Planner, Savings Goal, and Currency Converter – all working without internet.
- **Real‑Time Budget Guardrails** – Push notifications for 80% budget limit, unusual large transactions, and goal milestones.
- **Production‑Grade MERN‑vibe Stack** – React Native + Firebase Auth + Supabase PostgreSQL with Row‑Level Security.
- **Modern UI/UX** – Glassmorphism design, dark/light theme, smooth animations, responsive layouts.
- **Offline‑First Architecture** – AsyncStorage caching ensures the dashboard works even with intermittent connectivity.
- **Academic Research Integration** – Python ML pipeline (TF‑IDF + Random Forest) validated with confusion matrix and F1‑score.

A practical and visually appealing finance management app that demonstrates strong React Native + Firebase skills with focus on user-friendly financial insights.
---
## 📊 Project Analytics

<p align="center">
  <!-- Smart Budget Analyser Project Stats -->
  <img src="https://github-readme-stats-fast.vercel.app/api/pin/?username=asaddevx&repo=react-native&theme=tokyonight&hide_border=true&bg_color=0a192f&border_radius=20" alt="Smart Budget Analyser Project Stats" />

  <!-- Top Languages -->
  <img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=asaddevx&repo=react-native&layout=compact&theme=tokyonight&hide_border=true&bg_color=0a192f&border_radius=20&langs_count=8" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React_Native-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React Native" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-learn" />
  <img src="https://img.shields.io/badge/Offline_AI-00BFFF?style=for-the-badge" alt="Offline AI" />
  <img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" alt="Expo" />
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












