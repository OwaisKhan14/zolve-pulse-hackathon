# Zolve Pulse — INFORMS × Zolve Hackathon 2026

## Problem Statement
Financial apps are highly transactional — users only open them to check balances or make payments. This leads to low engagement, weak financial habits, and limited retention. **Zolve Pulse** transforms Zolve's transaction data into a social, gamified engagement layer that gives users a reason to return daily.

## Solution Overview
**Zolve Pulse** is a new tab within the Zolve app that provides:

- **Peer Pulse Dashboard** — Anonymized spending comparisons against fellow university students (segmented by cohort: all students, graduate, undergrad, school-specific). Users see how their dining, groceries, transport, and shopping spend stacks up against peers.
- **Credit Score Tracker** — Animated credit score visualization with utilization benchmarking against peer averages.
- **Dynamic Weekly Challenges** — Auto-generated challenges based on the user's weakest spending category, incentivized with cashback multipliers. Challenges are anchored in social proof ("78% of UTD students paid early").
- **AI Financial Guide** — A live AI-powered coach (powered by Claude) that contextually understands the user's financial data and provides personalized, actionable advice for international students building U.S. credit.
- **Credit Journey** — Milestone tracker showing credit-building progress (First Swipe → On-Time Payments → Low Utilization → Score Goals).
- **Daily Check-ins & Streaks** — Habit loop mechanic encouraging daily app opens with streak tracking.

## Why This Wins for Zolve
Zolve has **100K+ students** and real transaction data. Peer Pulse turns that data from a byproduct into a product — a **strategic data moat** no competitor without this user base can replicate. The feature directly increases DAU/WAU through social comparison (curiosity-driven returns), gamified challenges (action-driven returns), and AI coaching (value-driven returns).

## Features
- Peer spending comparison with cohort segmentation (All UTD / Grad / Undergrad / JSOM)
- Animated credit score ring with utilization benchmarking
- Dynamic challenge generation based on user's weakest spending category
- Live AI coach with contextual financial data awareness
- Credit journey milestone tracker (4/6 milestones demo)
- Daily check-in with streak counter and global state updates
- 1.5x cashback boost indicator (global reward hook)
- Zolve-native UI design matching the production app

## Tech Stack
- **Frontend:** React (JSX) with inline styling
- **AI Engine:** Anthropic Claude API (claude-sonnet-4-20250514)
- **Design:** Zolve brand-matched UI (Inter font, orange accent system, light theme)
- **State Management:** React hooks (useState, useEffect, useCallback)
- **Animations:** CSS keyframes + requestAnimationFrame for credit ring

## Team
- Owais — UT Dallas, Naveen Jindal School of Management

## How to Run
1. Open the `index.html` file in any modern browser
2. Or visit the live demo: [[GitHub Pages link after deployment]](https://owaiskhan14.github.io/zolve-pulse-hackathon/)
3. The AI Guide feature requires internet connectivity for Claude API calls

## Demo Instructions
- **Pulse Tab:** View credit score, check in (tap the check-in card), scroll to see peer comparisons, accept the weekly challenge
- **Journey Tab:** View credit-building milestones
- **AI Guide Tab:** Chat with the live AI financial coach — try asking "What's credit utilization?" or "Am I spending too much?"
- **Hidden Reset:** Tap the avatar icon (top-left) to reset all demo state

## Phase 2 Roadmap
- Percentage-based spending views (% of budget toggle)
- Real-time cohort segmentation with live Zolve transaction data
- Push notification nudges for streaks and challenges
- Spotify Wrapped-style weekly financial reports
- Share cards for social media ("I'm in the top 30% of savers at UTD")
- Backend API routing for production security
- Full WCAG accessibility audit
