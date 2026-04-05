# CalamitySense

## Status

This project is currently under active development.  
Core features and workflows are implemented, while additional enhancements and optimizations are continuously being added.

---

## Overview

CalamitySense is an interactive disaster preparedness platform designed to transform how students learn and respond to real-world emergencies.

Instead of passive, only theory-based learning, the platform enables a hands-on, simulation-driven experience where users:

- Learn through structured modules  
- Practice through decision-based drills  
- Respond using real-time alerts and guidance  

The objective is to bridge the gap between awareness and action — ensuring users are prepared when it matters most.

---

## Live Demo

https://calamity-sense-ctn7.vercel.app/

---

## Vision

CalamitySense aims to reimagine disaster education as an engaging, continuous, and experience-driven process, addressing the limitations of static guidelines and infrequent drills.

---

## Platform Highlights

- Integrated learning, simulation, and real-time response system  
- Personalized, region-specific disaster education  
- Gamified learning experience for sustained engagement 
- Community-driven awareness and collaboration  
- Scalable system for institutions and large user bases  

---

## Unique Selling Points (USP)

### 1. Engagement Through Gamification

CalamitySense ensures that learning is not a one-time activity but a continuous process.

- Streak-based learning to encourage consistency  
- XP system to track growth and progress  
- Leaderboards to introduce healthy competition  
- Badges and achievements to reward milestones over time  

This transforms disaster preparedness into an engaging and habit-forming experience.

---

### 2. Region-Specific Personalized Learning

The platform adapts learning content based on the user's location.

- Recommends modules relevant to regional risks  
- Focuses on disasters most likely to occur in that area  
- Ensures practical and context-aware preparedness  

This makes learning relevant, targeted, and immediately applicable.

---

### 3. Simulation-Based Learning Approach

Instead of passive reading, users actively participate in:

- Scenario-based disaster drills  
- Time-sensitive decision-making situations  
- Real-time feedback and performance evaluation  

This builds instinctive response capability, not just theoretical understanding.

---

### 4. Community-Driven Disaster Preparedness

CalamitySense introduces a social layer to preparedness.

- Users can report local hazards in real time  
- Form clubs focused on disaster awareness  
- Organize charitable and awareness events  
- Participate in competitions and workshops  
- Create support groups for individuals affected by disasters  

This fosters a collaborative ecosystem focused on safety and resilience.

---

### 5. Dashboard System (Based on user role)

- Student Dashboard for tracking progress, performance, and engagement  
- Admin Dashboard (RBAC) for monitoring institutional preparedness and identifying at-risk users  

---

## Core Features

### Learning Modules

- Structured modules covering earthquake, flood, fire, and non-natural disasters  
- Includes videos, articles, and interactive lessons  
- Personalized recommendations based on location  
- Learning objectives, prerequisites, and progress tracking  

---

### Virtual Disaster Drills

- Scenario-based simulations with time-bound decisions  
- Real-life emergency situations  
- Instant feedback with explanations  
- Performance tracking and improvement insights  

---

### Emergency Alerts System

- Location-based disaster alerts  
- Real-time safety instructions  
- Quick actions such as emergency contact access and guidance  

---

### Rewards and Gamification

- XP-based progression system  
- Levels, badges, and achievements  
- Leaderboards and streak tracking  

---

### Community Hub

- Share updates and disaster-related information  
- Report hazards in real time  
- Create clubs and organize events  
- Participate in competitions and awareness initiatives  
- Build support networks for affected individuals  

---

### Student Dashboard (Learner Side)

- Tracks learning progress and drill performance  
- Displays achievements and engagement metrics  
- Provides a clear view of preparedness level  

---

### Admin Dashboard (Institutional Side)

- Role-Based Access Control  
- Monitor engagement and preparedness levels  
- Identify at-risk users  
- Analyze trends and activity distribution  

---

## Disaster Coverage (Region-Specifc & Currently In Display)

- Earthquake Safety  
- Flood Emergency Response  
- Fire Safety in Schools  
- Non-natural disasters (infrastructure and emergency scenarios)  

---

## Technology Stack

- **Frontend Framework:** Next.js (App Router)  
- **Language:** TypeScript  
- **Styling:** Tailwind CSS  
- **UI Components:** shadcn/ui  
- **Icons:** Lucide React  

- **Backend & Logic:** Next.js API Routes / Server Actions  
- **State Management:** React Hooks  

- **Core System Features:**
  - Scenario-based simulation engine (for drills)  
  - Role-Based Access Control (RBAC)  
  - Location-based content recommendation system  

---

## Project Structure

```

/app
├── learn
├── drills
├── alerts
├── rewards
├── community
├── dashboard
├── admin
└── page.tsx

/components
├── ui
├── cards
└── layout

````

---

## How It Works

1. User selects a learning module  
2. Completes structured lessons (via articles, videos, quizzes, etc based on the kind of learning the user prefers)  
3. Practices through virtual drills  
4. Receives instant feedback and performance scores  
5. Tracks progress and earns rewards  
6. Stays informed through alerts and community  

---

## Local Setup

### Prerequisites

- Node.js (v18 or later)  
- npm or yarn  
- Git  

---

### Installation

```bash
git clone https://github.com/fatimahasan-82/CalamitySense.git
cd CalamitySense
npm install
````

---

### Run Development Server

```bash
npm run dev
```

Open: [http://localhost:3000](http://localhost:3000)

---

### Production Build (Optional)

```bash
npm run build
npm run start
```

---

## Use Cases

* School and college safety education
* Disaster preparedness training programs
* Academic and hackathon projects
* Public awareness initiatives

---

## Future Enhancements

* AI-based personalized recommendations
* Integration with real-time disaster APIs
* Mobile-first optimization
* Offline emergency support

---

## Developer Note

CalamitySense is an evolving platform focused on improving disaster preparedness through engaging, practical, and community-driven learning.

---

## License

This project is intended for educational and non-commercial use. You are free to modify and build upon it.

---

If you find this project useful, consider giving it a star.

---
