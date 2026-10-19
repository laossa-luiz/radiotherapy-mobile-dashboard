# 🏥 Radiotherapy & Oncology Management Analytics Dashboard

![License](https://img.shields.io/badge/License-MIT-teal.svg)
![Version](https://img.shields.io/badge/Version-v3.3_Mobile_Fix-0d9488.svg)
![Stack](https://img.shields.io/badge/Tech-HTML5_%7C_TailwindCSS_%7C_Chart.js_%7C_JS-38bdf8.svg)
![AI-Powered](https://img.shields.io/badge/Development-AI_Co--Pilot-8b5cf6.svg)

An interactive, responsive web application designed for clinical, operational, and financial monitoring of Radiotherapy and Oncology services. Built from a healthcare professional's perspective using **HTML5, Tailwind CSS, JavaScript, and Chart.js**, co-engineered with **Generative AI** as a development assistant.

---

## 💡 Project Background & Technological Evolution

The project originally started as a **Power BI** dashboard built to track oncological treatments and clinical KPIs. 

However, **when opening and testing the dashboard on a mobile device, a critical UX issue was identified**: the interface became truncated, navigation felt clunky on smaller screens, and stacked filter boxes obscured key metrics and charts.

To solve this mobile usability bottleneck, the entire application was refactored and rebuilt from scratch into a **Native Responsive Web Application** with an emphasis on **Mobile-First UX**.

### 📱 Key Mobile UX Improvements
* **100% Fluid & Responsive Grid:** Adapts automatically across smartphones, tablets, and desktop displays.
* **Collapsible Filter Drawers (`<details>`):** Allows mobile users to collapse filters on demand to immediately view KPIs and analytical charts.
* **Overflow Protection (`overflow-x: hidden`):** Prevents horizontal scrolling bugs and cut-off UI elements on mobile screens.
* **Mobile-Optimized Data Tables & Modals:** Clean horizontal scrolling and card-based modal views for patient medical records.

---

## 🚀 Key Features

### 📊 Clinical & Operational KPIs
* **Active Patients:** Live tracking of ongoing radiation treatment plans.
* **Delivered Sessions & Avg. Duration:** Daily fraction counts and machine occupancy time per fraction.
* **Medical Wait Time:** Interval (in days) between simulation/diagnosis and the 1st fraction (aligned with oncology clinical guidelines).
* **LINAC Occupancy & DQA Compliance:** Linear accelerator uptime and Medical Physics Quality Assurance pass rate (Gamma Index).

### 🎯 Multi-Dimensional Filters
Dynamic, real-time filtering across multiple clinical parameters:
* **Period / Year** (2025, 2026, Quarters)
* **Unit / Treatment Center** (Main Center, South Unit, North Center)
* **Tumor Site** (Breast, Prostate, Lung/Thorax, Head & Neck, Pelvis, CNS)
* **Radiation Technique** (VMAT/RapidArc, IMRT, 3D-CRT, SBRT/SRS, High-Dose-Rate Brachytherapy)
* **Linear Accelerator (LINAC)** (Elekta Versa HD, Varian TrueBeam, Varian Halcyon)
* **Payer / Health Insurance** (Public/SUS, Private Health Plans, Out-of-Pocket)

### 💡 Automated Clinical Insights Engine
Generates real-time analytical alerts based on active filter selections (e.g., predominant tumor sites, highest LINAC workload, high-precision technique adoption).

### 📋 Patient Records & Treatment Plan Table
* Instant search by patient name, ID, attending physician, or radiation technique.
* Column sorting and dynamic pagination.
* Fraction progress visual indicators (`Fractions Delivered / Prescribed Dose in Gy`).
* Detailed record view modal with DQA physics approval status.
* Single-click CSV export for filtered datasets.

---

## 🛠️ Tech Stack

* **HTML5 & CSS3 (Tailwind CSS):** Modern glassmorphism UI design with medical-themed color palettes.
* **JavaScript (ES6+ Vanilla):** Reactive state management, KPI calculations, and dynamic DOM manipulation.
* **Chart.js:** Responsive line, doughnut, and horizontal/vertical bar charts.
* **Lucide Icons:** Vector icon library.
* **AI Copilot (Prompt Engineering):** Accelerated code structuring, component design, and clinical domain logic mapping.

---
