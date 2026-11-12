#  CollabNest
![CollabNest Technical Workflow](./src/track3.png)
### Grow Together, Create Better.
## 📑 Table of Contents

1. [Brief One-Line Summary](#1-brief-one-line-summary)
2. [Problem Statement](#2-problem-statement)
3. [Dataset](#-3-dataset)
4. [Tools and Technologies](#4-tools-and-technologies)
5. [Method-Workflow](#5-method-workflow)
6. [Technical Architecture](#6-technical-architecture)
7. [Demo](#7-demo)
8. [Unique Selling Proposition](#8-unique-selling-proposition)
9. [Author & Contact](#9-author--contact)



## 1. Brief One-Line Summary

**CollabNest** is an AI-powered platform designed to help small and aspiring content creators understand their audience, make informed content decisions and improve their growth journey. It also features an **AI-powered Daily Planner** that helps creators organize their daily tasks, track their mental well-being, monitor their content growth and maintain a **healthy balance** between personal well-being and content creation.
<p align="center">
  <img src="./src/Burnout-to-Balance.png" width="500" alt="CollabNest Technical Workflow">
</p>



## 2. Problem Statement

Small content creators often struggle with:

- Understanding audience feedback.
- Experiencing burnout, stress and loss of motivation.
- Maintaining consistency while balancing daily responsibilities.
- Switching between multiple platforms for ideas, insights and content planning.
'''


**Our Solution:**

CollabNest brings audience intelligence, AI-powered content planning and creator growth tracking into one platform.

```mermaid

flowchart TD
    A(["🚀 COLLABNEST"]) --> B["Creator Dashboard"]

    B --> C["Audience Intelligence"]
    B --> D["AI Content Assistant"]
    B --> E["AI Daily Planner"]
    B --> F["Growth Tracker"]

    C --> C1["Comment Analysis"]
    C1 --> C2["Sentiment & Feedback Detection"]
    C2 --> C3["Likes, Complaints & Audience Needs"]
    C3 --> C4["Actionable Audience Insights"]

    D --> D1["Content Idea Generation"]
    D1 --> D2["Trending Topic Suggestions"]
    D2 --> D3["Personalized Content Recommendations"]

    E --> E1["Daily Task Management"]
    E1 --> E2["Time & Energy-Based Scheduling"]
    E2 --> E3["Well-being Check-ins"]
    E3 --> E4["Balanced Content Routine"]

    F --> F1["Content Performance"]
    F1 --> F2["Growth & Progress Monitoring"]
    F2 --> F3["Progress Timeline"]

    C4 --> G["Unified Creator Insights"]
    D3 --> G
    E4 --> G
    F3 --> G

    G --> H(["🌟 Smarter Decisions & Sustainable Growth"])

    %% Color definitions
    classDef main fill:#581c87,stroke:#e9d5ff,color:#ffffff,stroke-width:4px
    classDef dashboard fill:#312e81,stroke:#a5b4fc,color:#ffffff,stroke-width:3px
    classDef audience fill:#075985,stroke:#38bdf8,color:#ffffff,stroke-width:3px
    classDef assistant fill:#9d174d,stroke:#f9a8d4,color:#ffffff,stroke-width:3px
    classDef planner fill:#115e59,stroke:#5eead4,color:#ffffff,stroke-width:3px
    classDef growth fill:#9a3412,stroke:#fdba74,color:#ffffff,stroke-width:3px
    classDef audienceSub fill:#0c4a6e,stroke:#7dd3fc,color:#ffffff,stroke-width:2px
    classDef assistantSub fill:#701a75,stroke:#f0abfc,color:#ffffff,stroke-width:2px
    classDef plannerSub fill:#134e4a,stroke:#99f6e4,color:#ffffff,stroke-width:2px
    classDef growthSub fill:#7c2d12,stroke:#fed7aa,color:#ffffff,stroke-width:2px
    classDef finalNode fill:#166534,stroke:#86efac,color:#ffffff,stroke-width:3px

    %% Apply colors
    class A main
    class B dashboard
    class C audience
    class D assistant
    class E planner
    class F growth
    class C1,C2,C3,C4 audienceSub
    class D1,D2,D3 assistantSub
    class E1,E2,E3,E4 plannerSub
    class F1,F2,F3 growthSub
    class G,H finalNode

    %% Arrow styling
    linkStyle default stroke:#a78bfa,stroke-width:2.5px

```



## 📊 3. Dataset

```mermaid
%%{init: {"flowchart": {"nodeSpacing": 18, "rankSpacing": 35, "wrappingWidth": 550}, "theme": "dark"}}%%
flowchart LR
    A(("👥<br/>CREATOR"))

    A --- B["🧠 Mental Well-being Data<br/>Energy levels · Mood · Available hours · Break preferences"]
    A --- C["📊 Content Data<br/>Creator niche · Audience feedback · Engagement · Trends"]
    A --- D["🏆 Creator Profiles<br/>Name & bio · Platforms · Audience size · Interests"]
    A --- E["📅 Planning Data<br/>Daily goals · Time slots · Deadlines · Task status"]
    A --- F["👥 Collaboration Data<br/>Requests · Interests · Applications · Availability"]

    classDef center fill:#32105C,stroke:#B65CFF,color:#FFFFFF,stroke-width:3px
    classDef mental fill:#281344,stroke:#B65CFF,color:#E9D5FF,stroke-width:1.5px
    classDef content fill:#281344,stroke:#A855F7,color:#E9D5FF,stroke-width:1.5px
    classDef profile fill:#281344,stroke:#FF9B83,color:#FFFFFF,stroke-width:1.5px
    classDef planning fill:#281344,stroke:#C084FC,color:#FFFFFF,stroke-width:1.5px
    classDef collab fill:#172E3C,stroke:#35D6C2,color:#FFFFFF,stroke-width:1.5px

    class A center
    class B mental
    class C content
    class D profile
    class E planning
    class F collab

    linkStyle 0 stroke:#B65CFF,stroke-width:2px
    linkStyle 1 stroke:#A855F7,stroke-width:2px
    linkStyle 2 stroke:#FF9B83,stroke-width:2px
    linkStyle 3 stroke:#C084FC,stroke-width:2px
    linkStyle 4 stroke:#35D6C2,stroke-width:2px
```





**🤖 AI-Powered Data Processing:** Powered by **Google Gemini AI**, ColllabNest analyses user inputs to generate intelligent market insights, creative content ideas and personalised weekly schedules, prioritising mental well-being and sustainable creator growth.

## 🛠️ 
## 4. Tools and Technologies

- **AI Integration:** Google Gemini AI (Gemini Flash models) – for market opportunity analysis, creative content suggestions and AI-powered weekly planning.
- **Database & Backend Services:** Supabase – for storing creator profiles, weekly plans, daily tasks and collaboration data.
- **API Development:** REST APIs – for creator discovery, collaboration requests, open listings and weekly plan management.
- **Frontend:** HTML5, CSS3
- **Programming Languages:** HTML, CSS, TypeScript
- **Development Tools:** Git, GitHub and Visual Studio Code.

## 5. Method-Workflow

 Technology Integration:

Supabase  --->  Data Storage

Gemini AI  --->  AI-Powered Suggestions

REST APIs  --->  Backend Communication


![CollabNest Technical Workflow](./src/workflow.png)

## 7. Demo

[🎥 View Project Demo](https://drive.google.com/file/d/11YIesYsHbxcgAKbCkrL9Ze3T4LT4zyH-/view?usp=drivesdk)

## 8. Unique Selling Proposition

## 📊 Feature Comparison Matrix

CollabNest combines creator networking, collaboration, AI-powered content planning, progress tracking, and creator well-being into a single platform.

The following table compares CollabNest with existing platforms in the content creator market.

- ✅ Supported feature
- ❌ Not a core advertised feature

| Features | CollabNest | Instagram Creator Marketplace | TikTok One | Collabstr | Buffer | Later |
|---|:---:|:---:|:---:|:---:|:---:|:---:|
| Creator Discovery | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ |
| Similar Niche Matching | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ |
| Matching by Audience Size | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ |
| Creator-to-Creator Networking | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ |
| Community Discussions & Idea Sharing | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ |
| Collaboration Opportunities | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ |
| AI Weekly Content Planner | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ |
| Energy-Based Content Scheduling | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ |
| Burnout Prevention Support | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ |
| Content Progress Timeline | ✅ | ❌ | ❌ | ❌ | ✅ | ✅ |
| Views & Follower Growth Tracking | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| Creator Growth Insights | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |

### 🌟 What Makes CreatorConnect Unique?

Unlike platforms that primarily focus on influencer marketing, brand partnerships, or social media management, CreatorConnect brings essential creator growth tools together in one place.

- 🤝 **Smart Networking:** Connect with creators who share similar interests, niches, and audience sizes.
- 🚀 **Collaboration Hub:** Find collaboration partners and grow through mutual support.
- 🤖 **AI Weekly Planner:** Generate personalized content plans based on available time and energy levels.
- ❤️ **Burnout Prevention:** Encourage realistic goals, breaks, and sustainable content creation.
- 📈 **Progress Timeline:** Track content creation efforts, views, and follower growth.

Our mission is not just to help creators gain followers, but to help them grow together without burning out.
