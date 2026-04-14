# DSA 210 – Analyzing and Predicting Procrastination Behavior Using Daily Digital Habits

## Project Overview
This project investigates how daily digital habits (social media usage, screen time, sleep, study hours) relate to procrastination behavior. The goal is to identify key patterns and build predictive models for procrastination levels.

## Dataset
- **Source:** Self-collected daily tracking data (March 3 – April 13, 2026)
- **Size:** 42 daily observations
- **Features:**
  - `sleep_hours` – Hours of sleep per night
  - `study_hours` – Hours spent studying
  - `screen_time` – Total daily screen time (hours)
  - `social_media_time` – Social media usage (hours)
  - `planned_tasks` – Number of tasks planned for the day
  - `completed_tasks` – Number of tasks actually completed
  - `stress_level` – Self-reported stress level (1–10)
  - `procrastination_score` – Composite procrastination score (1–10)

## Repository Structure
```
├── procrastination_data.csv       # Dataset
├── procrastination_analysis.ipynb # Main analysis notebook (EDA + hypothesis tests)
├── requirements.txt               # Python dependencies
└── README.md                      # This file
```

## How to Reproduce
1. Clone this repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open and run the notebook:
   ```bash
   jupyter notebook procrastination_analysis.ipynb
   ```

## Milestones
- [x] Milestone 1 (Apr 14): Data collection, EDA, hypothesis testing
- [ ] Milestone 2 (May 5): Machine learning models
- [ ] Final Report (May 18)
