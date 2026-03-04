# Gig Income Shield – AI-Powered Weekly Income Protection for Delivery Partners

## Problem Statement
Grocery and Q-commerce delivery partners face frequent income loss when external disruptions such as extreme weather or local restrictions prevent them from working. These losses directly affect their weekly earnings, and there is currently no short-term income protection available for such situations.

## Target Persona
**Persona:** Grocery / Q-Commerce Delivery Partner  
**Platforms:** Zepto, Blinkit, Swiggy Instamart  
**Work Pattern:** Outdoor deliveries with a weekly earnings cycle

## Coverage Scope
This platform provides insurance coverage for **loss of income due to lost working hours** caused by external disruptions.  
The solution strictly excludes coverage for health, accidents, life insurance, or vehicle repairs.

## Parametric Triggers
Claims are automatically triggered when predefined external conditions are met:
- **Heavy Rain:** Rainfall exceeding 20 mm/hour  
- **Extreme Heat:** Temperature exceeding 45°C  
- **Local Curfew or Zone Closure:** Government or administrative restrictions  

These triggers are monitored in real time using external data sources.

## Weekly Pricing Model
The insurance operates on a **weekly premium model** aligned with gig workers’ earnings:
- Average weekly income: ₹4,500 – ₹5,000  
- Weekly premium range: ₹49 – ₹69  
- Premiums are dynamically adjusted using AI based on:
  - Delivery zone risk
  - Historical weather patterns
  - Past claim frequency

## AI & ML Integration
Artificial Intelligence is used to:
- Dynamically calculate weekly premiums using risk prediction models  
- Detect fraudulent or anomalous claims through location and activity validation  
- Predict high-risk periods based on historical and forecasted disruption data  

## Claim & Payout Workflow
- Continuous monitoring of external disruption data  
- Automatic claim initiation when parametric conditions are met  
- Zero-touch claim approval  
- Instant payout of lost income via digital payment systems (simulated)

## Platform Choice
A **web-based platform** is chosen for faster onboarding, easy accessibility across devices, and smooth demonstration during the hackathon.

## Planned Tech Stack
- **Frontend:** React  
- **Backend:** Node.js with Express  
- **AI/ML:** Python (Scikit-learn)  
- **Database:** MongoDB / PostgreSQL  
- **APIs:** Weather API (free tier or mock), payment gateway sandbox  

## Phase-1 Scope
Phase-1 focuses on ideation, system design, workflow definition, and risk modeling. Full automation, AI models, fraud detection, and payout simulations will be implemented in subsequent phases.
