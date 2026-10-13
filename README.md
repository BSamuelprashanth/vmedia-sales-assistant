# ⚡ VMedia Sales Console — Ultimate Edition

> A production-grade, feature-rich web assistant engineered for high-efficiency sales operations. Designed to eliminate tab-switching mid-call by centralizing customer intake, dynamic speed sizing, provincial tax calculations, call duration tracking, and compliance scripting into a single-page interface.

---

## 🌟 Overview

The **VMedia Sales Console** is a high-performance client-side application built specifically for customer care and sales representatives. Drawing from real-world telecom experience, it bridges the gap between fast-paced customer interactions and rigorous data collection accuracy. 

By unifying multiple workflows into a single responsive screen, the console reduces Handle Time (AHT) while ensuring complete regulatory compliance and accurate billing calculations.

---

## 🚀 Key Features & Architectural Highlights

### 1. ⏱️ Precision Call Timer & Audio Alerts
* **Interactive Countdown:** Features an integrated 3-minute interactive call countdown timer to help agents pace discovery calls effectively.
* **Web Audio API Integration:** Custom frequency audio beeps alert agents at critical time milestones without requiring external audio files.
* **Session Persistence:** Automatically logs session state and timer data using browser `localStorage` to prevent accidental data loss on page refresh.

### 2. ⚡ Dynamic Speed Sizing Calculator
* Automatically estimates and recommends optimal internet speed tiers based on real-time household inputs (number of connected devices, streaming habits, gaming, and remote work requirements).
* Built using a scalable multiplier engine ($15 \text{ Mbps}$ base factor per high-demand device).

### 3. 🧮 Live Provincial Tax Calculator
* Real-time calculation of federal and provincial taxes (**GST, PST, HST, QST**) across all Canadian provinces and territories.
* Instant rate updating that ensures accurate quote generation before checkout or order placement.

### 4. 📋 One-Tap Clipboard Automation
* Instant copy triggers for individual customer fields (Name, Phone, Address, Account ID) or a comprehensive multi-line text package.
* Streamlines CRM data entry by formatting data instantly for copy-pasting directly into internal ticketing systems.

### 5. ✓ Call Progress Checklist & Script Repository
* **Compliance Tracker:** Interactive progress checklist ensuring agents cover mandatory disclosures (discovery, terms & conditions, 3-email overview, and closing).
* **Script Library:** Built-in modal library providing one-tap copying for standard compliance scripts, rebuttal handling, payment instructions, and closing statements.

### 6. 🌓 Persistent Theme Engine
* Fully responsive design system featuring smooth CSS transitions between custom Light and Dark modes.
* Automatically detects system preferences and retains theme settings via local storage.

---

## 🛠️ Tech Stack & Design System

* **Frontend Architecture:** Pure HTML5, Semantic DOM structure.
* **Styling & UI:** Advanced CSS3 (CSS Variables, Flexbox/Grid, Glassmorphism UI components, custom keyframe animations).
* **Logic & Interactivity:** Vanilla JavaScript (ES6+, DOM Manipulation, Event Delegation, Web Audio API, LocalStorage API).
* **Design Philosophy:** Tokenized design system optimized for high-density information display and zero-latency interaction.

---

## 📂 Repository Structure

```text
📦 vmedia-sales-assistant
├── 📄 index.html          # Complete standalone single-page application (HTML, CSS, JS)
└── 📄 README.md           # Comprehensive project documentation
