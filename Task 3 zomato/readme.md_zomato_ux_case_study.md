# Zomato Mobile App – UX Analysis & Redesign Case Study
**CodeAlpha UI/UX Design Internship — Task 3**  
**Author:** Hema Sri Bandreddy  
**Role:** UX Researcher & Product Designer  
**Scope:** Educational UX Case Study & UI Overhaul (Independent Research)

---

## 📌 Executive Summary & Project Overview
This project is an independent educational UX case study conducted for the **CodeAlpha UI/UX Design Internship (Task 3)**. The study explores the mobile food discovery and ordering experience, identifies usability bottlenecks through heuristic evaluation and self-conducted cognitive walkthroughs, and proposes an 8-screen end-to-end mobile redesign.

> **Disclaimer:** This case study is conducted strictly for academic and portfolio demonstration purposes. It is not affiliated with or endorsed by Zomato Ltd. No internal analytics or proprietary data were utilized; all insights are derived from heuristic reviews and personal UX observations.

---

## 🎯 Problem Statement
Modern food delivery platforms face immense cognitive load issues:
1. **Choice Paralysis:** Cluttered home feeds overwhelming users with excessive banner ads, competing badges, and unsegmented listings.
2. **Filter Friction:** Difficulties in rapidly filtering dietary preferences (Pure Veg, Budget, Delivery Time < 30m).
3. **Fragmented Cart Editing:** Complex quantity adjustments and hidden delivery surcharge breakdowns before the final checkout screen.
4. **Information Architecture Flaws:** Lack of nutritional transparency, clear ingredient breakdowns, and allergen warnings on dish modal sheets.

---

## 🚀 Project Objectives & Goals
- **Simplify Food Discovery:** Establish a clean, uncluttered visual hierarchy on the Home and Restaurant Listing screens.
- **Enhance Dietary Clarity:** Provide prominent Veg/Non-Veg indicators and customizable dish portioning.
- **Streamline the Checkout Funnel:** Reduce cart abandonment by introducing transparent bill breakdowns, quick address selectors, and one-tap payment options.
- **Improve Delight & Tracking:** Design a live, informative order confirmation and progress tracking interface.

---

## 👥 Target Users & Personas

### Persona 1: "The Busy Corporate Professional" — Priya Sharma (28, Bangalore)
- **Context:** Works 9-to-7 at a fintech startup, orders lunch daily at her desk.
- **Pain Points:** Too much time spent scrolling through irrelevant recommendations; unpredictable delivery ETA during lunch rush.
- **Goal:** Order a healthy meal in under 3 minutes with guaranteed 30-minute delivery.

### Persona 2: "The Budget-Conscious Student" — Rohan Verma (21, Pune)
- **Context:** University hosteller ordering late-night snacks with roommates.
- **Pain Points:** Surging delivery charges, confusing discounts, and sudden coupon validation errors at checkout.
- **Goal:** Instant visibility of coupons, split-bill friendly item selections, and affordable combo meals.

---

## 🗺️ User Journey Map (Current vs. Proposed)

| Stage | Existing UX Friction | Proposed UX Improvement |
| :--- | :--- | :--- |
| **1. Discovery** | Cluttered promotions, endless banners, competing visual hierarchies. | Clean categorical pills, curated "Quick Reorder" row, and smart search bar. |
| **2. Selection** | Hidden dietary toggles and dense restaurant cards without distance cues. | Prominent Veg/Non-Veg toggle, ETA badge, and cuisine tags right on list cards. |
| **3. Customization** | Confusing add-on checkboxes with hidden additional costs. | Step-by-step modal for size, spices, and add-ons with dynamic price updates. |
| **4. Cart & Bill** | Surcharges revealed only on final step; difficult item removal. | Slide-to-remove cart items, transparent breakdown of platform fee & taxes upfront. |
| **5. Checkout & Track**| Cluttered payment options; static order confirmation text. | One-click UPI selector, delivery address pill, and live step-by-step courier ETA. |

---

## 🔬 Usability Improvements (5 Key Interventions)
1. **Simplified Food Search:** Instant predictive autocomplete with recent searches and dietary filter shortcuts.
2. **Clear Restaurant Filters:** Sticky horizontal filter pills (Rating 4.0+, Under 30 Mins, Pure Veg, Offers).
3. **Better Food Information Hierarchy:** Clean typography, calorie count badges, portion details, and high-res photography.
4. **Frictionless Cart Editing:** In-cart portion stepper buttons (`-` / `+`), clear customization chips, and one-tap promo application.
5. **Transparent Checkout & Live Status:** Upfront fee breakdown with no hidden surprises, plus real-time visual progress bar post-order.

---

## 🎨 Design System Specifications
- **Primary Color:** `#E23744` (Zomato Red)
- **Secondary Accent:** `#FFF5F5` (Soft Crimson Tint)
- **Dark Neutral (Text):** `#242424` (High-contrast Charcoal)
- **Muted Gray:** `#71717A` (Body text, subtle outlines)
- **Success Green:** `#267E3E` (Ratings, Pure Veg indicators)
- **Canvas / Dimensions:** Android Portrait `390 × 844 px`
- **Corner Radii:** Cards `16px`, Buttons `12px`, Bottom Sheets `24px`

---

## 📱 Screen Breakdown (8 Core Mobile Screens)
1. **Splash / Welcome Screen:** Clean brand introduction, delivery location quick-picker, and social sign-in.
2. **Home Screen:** Location bar, smart search, diet toggle, story circles, popular cuisines, and top-rated restaurants nearby.
3. **Restaurant Listing Screen:** Filter chips, dynamic sort controls, and rich restaurant summary cards.
4. **Restaurant Details Screen:** Hero gallery, safety ratings, cuisine tags, category tabs, and menu item cards.
5. **Food Details Screen:** High-fidelity dish showcase, calorie badge, spice levels, customizable add-ons, and floating "Add to Cart" bar.
6. **Cart Screen:** Order review, item stepper controls, delivery instructions, tip selector, and transparent billing.
7. **Checkout Screen:** Address switcher, delivery time selector, UPI/Card/COD payment gateways, and swipe-to-pay button.
8. **Order Confirmation & Tracker:** Live animated tracking timeline, delivery agent card, OTP code, and estimated delivery timer.

---

## 📂 Project Repository Structure
```text
Task3_Zomato_UX_Case_Study/
├── README.md
├── Case_Study_Report/
│   ├── Zomato_UX_Evaluation_Report.pdf
│   └── UX_Heuristic_Analysis.md
├── UX_Research/
│   ├── User_Personas/
│   │   ├── Persona_1_Priya_Sharma.png
│   │   └── Persona_2_Rohan_Verma.png
│   ├── User_Journey/
│   │   └── User_Journey_Map.png
│   └── Usability_Evaluation_Matrix.csv
├── UI_Design/
│   ├── Design_Tokens.json
│   └── Screen_Exports/
│       ├── 01_Splash_Welcome.png
│       ├── 02_Home_Feed.png
│       ├── 03_Restaurant_Listing.png
│       ├── 04_Restaurant_Details.png
│       ├── 05_Food_Customization.png
│       ├── 06_Cart_Review.png
│       ├── 07_Secure_Checkout.png
│       └── 08_Order_Confirmation.png
└── Documentation/
    └── Internship_Submission_Summary.md
```

---
*Created for CodeAlpha UI/UX Design Internship — Task 3 by Hema Sri Bandreddy.*
