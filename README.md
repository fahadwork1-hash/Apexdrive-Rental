# 🏎️ ApexDrive UAE — Luxury Supercar Rental & VIP Fleet Dispatch

[![License: MIT](https://img.shields.io/badge/License-MIT-emerald.svg)](LICENSE)
[![RTA Commercial Operator](https://img.shields.io/badge/Dubai_RTA-Operator_%239831-0f172a.svg)](https://rta.ae)
[![HTML5 / Tailwind](https://img.shields.io/badge/Stack-HTML5_%7C_Tailwind_CSS_%7C_Vanilla_JS-38bdf8.svg)](https://tailwindcss.com)
[![Bilingual](https://img.shields.io/badge/i18n-English_%26_العربية_(RTL)-10b981.svg)](#)

ApexDrive UAE is a high-performance, VIP digital rental dispatch and asset monetization web platform tailored specifically for Dubai's luxury automotive market. It combines an exotic 40-vehicle fleet showroom, real-time estimator, instant WhatsApp dispatching, cross-tab reactive operations desk, and an investor yield simulator.

---

## 🌟 Key Features

### 1. 🏎️ 40-Model Verified Supercar Dataset
* **8 World-Class Marques (5 Models Each):**
  * **Porsche:** 911 Carrera 4S, 911 GT3 RS, Taycan Turbo S, Cayenne Turbo GT, Panamera GTS
  * **Ferrari:** F8 Tributo Spider, Roma V8 Coupe, 296 GTB Hybrid, SF90 Stradale, Portofino M
  * **Lamborghini:** Huracán Evo Spyder, Urus Performante, Huracán STO, Revuelto V12, Aventador SVJ
  * **Rolls-Royce:** Ghost Series II, Cullinan Black Badge, Phantom VIII, Dawn Cabriolet, Spectre Electric
  * **Mercedes-Benz:** AMG G63 BiTurbo, Maybach S680 V12, AMG GT Coupe, SL63 Roadster, GLE 63S
  * **Land Rover:** Range Rover Autobiography LWB, Sport SV Edition, Defender 110 V8, Velar P400, Defender 130 V8
  * **BMW:** M4 Competition, M8 Gran Coupe, 760i xDrive, X6 M Competition, XM Label Red
  * **Audi:** RS6 Avant, R8 V10 Spyder, RSQ8 Carbon Edition, RS7 Sportback, e-tron GT RS

### 2. 🔍 Dedicated Car Detail Showroom View (VIP Specs Modal)
* Interactive modal displaying complete mechanical metrics:
  * Power Output (HP) & 0–100 km/h acceleration
  * Realistic Top Speed ratings (up to 340 km/h)
  * Dual-clutch / PDK transmission details
  * Luggage & passenger seating capacity
* **Dubai Rental Inclusions & Badges:**
  * 250 KM/Day Complimentary Mileage allowance
  * Official RTA Commercial CDW Comprehensive Insurance coverage
  * VIP Valet Handover at DXB Airport (Terminals 1, 2, 3) & Palm Jumeirah
  * Transparent refundable security deposit hold guidelines

### 3. 📲 Direct WhatsApp Booking Engine
* Direct one-touch WhatsApp reservation routing:
  * Formats custom, bilingual pre-filled messages (Client name, Vehicle, Pickup Date, Duration, Handover Hub, Total AED).
  * Opens direct chat with business dispatch without intermediary share pickers.

### 4. 📊 Live Dispatcher Desk (`admin.html`)
* Operations control dashboard:
  * Real-time metrics: Total Bookings, Pending Confirmation, Confirmed Dispatches.
  * **Cross-Tab Reactive Sync:** Listens to `storage` events across browser tabs—when a user reserves on `index.html`, the booking immediately prepends to the Dispatcher Table without page refresh.
  * **Investor Leads Table:** Displays supercar owners seeking commercial fleet placement.

### 5. 📈 Investor & Asset Management Portal (`investor.html`)
* Supercar monetization simulation for high-net-worth vehicle owners in Dubai:
  * Dynamic Yield Simulation Slider (12 to 28 days rented per month).
  * Calculates Gross Turnover, 30% Platform Fee, 5% Maintenance Reserve, Net Monthly Disbursal, and Net Annual Cap Rate (ROI).
  * Partner placement application form with local storage lead capture.

### 6. 🌐 Dual-Language Architecture & RTL Support
* Instant toggle between **English** and **العربية (Arabic)**.
* Dynamically sets `dir="rtl"` and loads Google font **Cairo** for Arabic typography, with persistent `localStorage` memory.
* Dual currency support: **AED (United Arab Emirates Dirham)** and **USD ($)**.

---

## 📁 Repository Structure

```text
apexdrive-rental/
├── index.html        # Main Customer Portal, Showcase, Estimator, Booking Modal & AI Concierge
├── fleet.html        # Complete 40-Car Inventory Catalog & Search
├── investor.html     # Supercar Monetization & Yield Simulator
├── admin.html        # Dispatcher Operations Control & Live Leads Board
├── js/
│   └── data.js       # Master Fleet Dataset (40 Vehicles across 8 Brands)
├── .gitignore        # System & local ignore rules
└── README.md         # Documentation & architecture guide
```

---

## 🛠️ Technology Stack

* **Frontend:** HTML5, Vanilla JavaScript (ES6+), Tailwind CSS (Modern Utility Framework)
* **Typography:** Plus Jakarta Sans (English) & Cairo (Arabic) via Google Fonts
* **State & Storage:** Web Storage API (`localStorage`) with cross-tab reactive event listeners
* **Vector Assets & Icons:** Scalable inline SVG badges, official WhatsApp branding, custom AD monogram favicon
* **Deployment:** Zero-build static architecture; ready for instant deployment on Vercel, Netlify, or GitHub Pages.

---

## 🚀 Quick Start / Local Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/fahadwork1-hash/Apexdrive-Rental.git
   cd Apexdrive-Rental
   ```

2. **Open in browser:**
   Double-click `index.html` or run a local lightweight static server:
   ```bash
   npx serve .
   # or
   python3 -m http.server 8000
   ```

3. **Open pages:**
   * Customer Showcase: `http://localhost:8000/index.html`
   * Fleet Catalog: `http://localhost:8000/fleet.html`
   * Investor Portal: `http://localhost:8000/investor.html`
   * Dispatcher Desk: `http://localhost:8000/admin.html`

---

## 👨‍💻 Engineering & Architecture

* **Lead Architecture & Engineering:** Fahad Rasheed
* **Platform:** ApexDrive Digital Fleet Systems
* **Registry Context:** Dubai Department of Economy & Tourism / RTA Commercial Transport Framework
