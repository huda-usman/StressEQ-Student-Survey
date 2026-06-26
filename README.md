<div align="center">
  <br />
  <p align="center">
    <!-- Floating Sparkle Animation -->
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" width="90" height="90">
      <g>
        <animateTransform attributeName="transform" type="translate" values="0,4; 0,-6; 0,4" dur="4s" repeatCount="indefinite" />
        <path d="M50 15 C50 35 35 50 15 50 C35 50 50 65 50 85 C50 65 65 50 85 50 C65 50 50 35 50 15 Z" fill="#8B5CF6" />
        <path d="M50 25 C50 40 40 50 25 50 C40 50 50 60 50 75 C50 60 60 50 75 50 C60 50 50 40 50 25 Z" fill="#A78BFA" />
        <circle cx="50" cy="50" r="4" fill="#FFFFFF" />
      </g>
      <ellipse cx="50" cy="92" rx="14" ry="2" fill="#C084FC" opacity="0.3">
        <animate attributeName="rx" values="14; 9; 14" dur="4s" repeatCount="indefinite" />
        <animate attributeName="opacity" values="0.3; 0.15; 0.3" dur="4s" repeatCount="indefinite" />
      </ellipse>
    </svg>
  </p>
  <h1 align="center" style="color: #6D28D9;">🧠 StressEQ: Student Survey</h1>
  <p align="center"><b>AI-Powered Student Stress Detection & Burnout Forecaster</b></p>
  <p align="center"><i>An intelligent, anonymous platform designed for university students to report stress factors, forecast burnout risk, and access personalized mental health support.</i></p>
  
  <p align="center">
    <a href="#"><img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge&logo=github&logoColor=white&color=8B5CF6" alt="Status"/></a>
    <a href="#"><img src="https://img.shields.io/badge/Stack-HTML5%20%7C%20CSS3%20%7C%20JS-blue?style=for-the-badge&logo=javascript&logoColor=white&color=7C3AED" alt="Stack"/></a>
    <a href="#"><img src="https://img.shields.io/badge/License-MIT-lightgrey?style=for-the-badge&color=A78BFA" alt="License"/></a>
  </p>
  <br />
</div>

---

## 📋 Overview

**StressEQ** is a multi-step web survey designed for university students to anonymously report academic, lifestyle, and wellbeing factors that contribute to stress. The collected data is used to validate an AI model that detects rising stress levels and recommends personalized interventions before burnout sets in.

The survey integrates **clinically validated screeners (PHQ-9, GAD-7)** alongside lifestyle and demographic questions, wrapped in a clean, gamified, mobile-friendly UI. Upon completion, students can generate a personalized Certificate of Participation.

---

## 🎯 Key Features

- 🎯 **10-Section Adaptive Survey:** Covers demographics, academics, sleep, lifestyle, finances, health, personal context, and wellbeing.
- 💾 **Auto-Save Progress:** Responses persist via `localStorage`, so users can resume without losing data.
- 📊 **Live BMI Calculator:** Real-time feedback with WHO/CDC and teen-specific percentile logic.
- 🚨 **Built-in Crisis Support:** Automatic detection of self-harm risk indicators with compassionate resource prompts.
- 🎉 **Engaging UX:** Progress bar, milestone toasts, confetti celebration, and a custom certificate generator.
- 🏆 **Certificate of Participation:** 
  - Auto-generated, downloadable PNG certificate for each respondent.
  - Customizable with the student's name and stamped with their unique **Anonymous Response ID**.
  - High-resolution, client-side rendering with responsive desktop-to-mobile scaling using `html2canvas`.
- 📱 **Fully Responsive:** Optimized for both desktop and mobile devices.
- 🔒 **Anonymous by Design:** No names linked to data; optional email opt-in only.

---

## 🛠️ Tech Stack

| Layer       | Technology              |
|-------------|--------------------------|
| **Markup**  | HTML5                    |
| **Styling** | CSS3 (custom, no framework) |
| **Logic**   | Vanilla JavaScript        |
| **Storage** | Browser `localStorage`    |
| **Export**  | `html2canvas` (certificate PNG generation) |

---

## 🔐 Privacy & Ethics

- All responses are stored under a randomized anonymous ID.
- No personally identifiable data is required to complete the survey.
- Sensitive questions (e.g. substance use, mental health) include skip options.
- Crisis-related responses trigger supportive resource messaging, not penalization.

---

## 🤝 Contributing

This is a Final Year Project (FYP) built to support AI research into student stress detection.

---

## 📬 Contact

Built by **[huda-usman](https://github.com/huda-usman)** and **[Khansa972](https://github.com/Khansa972)** as part of the StressEQ research initiative.

---

<div align="center">
  <h3 style="color: #7C3AED;">✨ Empowering Academic Wellbeing ✨</h3>
  <p><i>Validating AI models to detect rising stress levels and recommend personalized interventions before burnout.</i></p>
  <br/>
  <sub style="color: #8B5CF6;">Made with care for student mental health 💙</sub>
</div>
