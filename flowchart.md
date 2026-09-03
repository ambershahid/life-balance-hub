# 🔄 Life Balance Hub - App Flowchart

<p align="center">
  <img src="https://img.shields.io/badge/Flow-User%20Journey-7F5AF0?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/AI-Powered-2CB67D?style=for-the-badge"/>
</p>

This diagram shows how a user interacts with Life Balance Hub from login to daily wellness.

---

## 1. Main App Flow

```mermaid
flowchart TD
    A[🚀 App Launch] --> B{First Time User?}
    
    B -->|Yes| C[Onboarding & Goal Setup]
    B -->|No| D[Login / Dashboard]
    
    C --> D
    
    D --> E[📊 Main Dashboard]
    
    E --> F[AI Wellness Assistant]
    E --> G[Habit & Goal Tracker]
    E --> H[Health Monitoring]
    E --> I[Analytics & Reports]
    E --> J[Settings & Profile]
    
    F --> K[AI Chat + Mood Check-in]
    K --> L[Personalized Suggestions]
    L --> E
    
    G --> M[Add/Complete Habits]
    M --> N[Update Streaks]
    N --> E
    
    H --> O[Log Water, Sleep, Exercise]
    O --> P[Get Health Insights]
    P --> E
    
    I --> Q[View Charts & Balance Score]
    Q --> R[Weekly AI Report]

    
   