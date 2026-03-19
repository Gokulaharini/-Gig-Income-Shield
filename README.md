# Gig Income Shield: AI-Powered Weekly Income Protection

🚀 Protecting gig delivery partners from income loss due to weather and external disruptions using AI-powered parametric insurance.

---

## Problem Statement
Grocery and Q-commerce delivery partners face frequent income loss when external disruptions such as extreme weather or local restrictions prevent them from working. These losses directly affect their weekly earnings, and there is currently no short-term income protection available for such situations.

---

## Target Persona
**Persona:** Grocery / Q-Commerce Delivery Partner  
**Platforms:** Zepto, Blinkit, Swiggy Instamart  
**Work Pattern:** Outdoor deliveries with a weekly earnings cycle  

---

## Coverage Scope
This platform provides insurance coverage for **loss of income due to lost working hours** caused by external disruptions.  
The solution strictly excludes coverage for health, accidents, life insurance, or vehicle repairs.

---

## Parametric Triggers
Claims are automatically triggered when predefined external conditions are met:

- **Heavy Rain:** Rainfall exceeding 20 mm/hour  
- **Extreme Heat:** Temperature exceeding 45°C  
- **Local Curfew or Zone Closure:** Government or administrative restrictions  

These triggers are monitored in real time using external data sources.

---

## Weekly Pricing Model
The insurance operates on a **weekly premium model** aligned with gig workers’ earnings:

- Average weekly income: ₹4,500 – ₹5,000  
- Weekly premium range: ₹49 – ₹69  

Premiums are dynamically adjusted using AI based on:
- Delivery zone risk  
- Historical weather patterns  
- Past claim frequency  

---

## AI & ML Integration
Artificial Intelligence is used to:

- Dynamically calculate weekly premiums using risk prediction models  
- Predict high-risk disruption periods  
- Detect fraudulent or anomalous claims through location and activity validation  

---

## Claim & Payout Workflow
- Continuous monitoring of external disruption data  
- Automatic claim initiation when parametric conditions are met  
- Zero-touch claim approval  
- Instant payout of lost income via digital payment systems (simulated)  

---

## Platform Choice
A **web-based platform** is chosen for faster onboarding, easy accessibility, and smooth demonstration during the hackathon.

---

## Planned Tech Stack
- **Frontend:** React  
- **Backend:** Node.js with Express  
- **AI/ML:** Python (Scikit-learn)  
- **Database:** MongoDB / PostgreSQL  
- **APIs:** Weather API (free tier or mock), payment gateway sandbox  

---

## Adversarial Defense & Anti-Spoofing Strategy

To defend against large-scale fraud such as GPS spoofing and coordinated fake claims, the platform uses a multi-layered AI-driven validation system that goes beyond simple location checks.

### 1. Differentiation: Genuine Worker vs Fraudster
The system differentiates real users from spoofers using:
- Consistency of location over time (no sudden unrealistic jumps)  
- Alignment with historical working zones  
- Correlation with actual disruption events in that area  

---

### 2. Data Signals Used
Instead of relying only on GPS, the system analyzes:

- Device GPS location  
- Network/IP-based location  
- Historical movement patterns  
- Login activity and session timing  
- Delivery activity (simulated platform data)  
- Weather API validation  
- Claim density in specific areas  

---

### 3. UX Balance (Fairness for Real Users)
To ensure genuine workers are not affected:

- Low-risk claims are processed instantly  
- Medium-risk claims may be delayed for validation  
- High-risk claims are flagged, not rejected immediately  

The system allows minor inconsistencies during poor network or extreme conditions.

---

### 4. Coordinated Fraud Detection
- Detects sudden spikes in claims from one region  
- Identifies multiple accounts with similar behavior patterns  
- Flags suspicious clusters using AI-based risk scoring  

---

### 5. Risk Scoring System
Each claim is assigned a risk score based on:
- Location consistency  
- Behavioral patterns  
- External data validation  
- Claim frequency  

Claims are processed based on risk level to balance speed and security.

---

## Phase-1 Scope
Phase-1 focuses on ideation, system design, workflow definition, and fraud-resistant architecture. Full automation, AI models, and payout simulations will be implemented in subsequent phases.
