# Project Spec -- Weekplanner Improvement Project

## Problem Statement
The Weekplanner is a functional single-file React 18 web app for tracking weekly work/free hours against an 8h/day (40h/week) target. It works but has not been evaluated through a structured product lens. We need to determine what improvements, features, or changes would make it truly useful and polished for its primary user -- a professional who needs to track weekly hours for work reporting.

## Target User + Context
- **Who:** Kevin, a professional who needs to report weekly working hours
- **Situation:** Tracks Mon-Fri hours, splitting time between "Werk" (work) and "Vrij" (free/leave) each day
- **Goal:** Quick, accurate weekly hour tracking that feels native/polished and serves work reporting needs

## Success Metrics
- [ ] To be defined during Define phase
- Initial hypothesis: reduced friction in weekly reporting, increased trust in data accuracy, feel of a polished native tool

## Chosen Concept Direction
_Empty until Develop phase_

## Prototype Scope + Flow
_Empty until Deliver phase_

## Known Constraints
- **Platform:** Single-file HTML/React 18 app (CDN-loaded, Babel transpiled in-browser)
- **Tech:** Tailwind CSS via CDN, localStorage for persistence, no backend
- **Design system:** iOS 26 Liquid Glass / Apple HIG styling
- **Language:** Dutch UI
- **Scope:** Must remain a single-file web app (no build tooling, no server)
- **Timeline:** Not specified -- quality over speed

## Current App Capabilities
- Weekly summary with Screen Time-style stacked bar chart (work=blue, free=teal)
- Day cards with Werk + Vrij hour inputs (Mon-Fri)
- 8h/day target with green/red status indicators
- Week navigation (prev/next/today) with segmented control
- localStorage persistence across sessions
- URL-based week sharing (base64-encoded)
- Toast notification for link copy
- Mobile-first responsive layout
- Today highlighting (blue tint on current day card)

## Open Risks / Questions
- Is "Werk + Vrij = 8h" the right mental model, or does the user think differently about their hours?
- Is the current level of detail (per-day, two categories) enough or too much?
- What happens to the data? Is copy-paste / manual reporting the end goal, or is there a system to feed into?
- Are there edge cases not handled (sick days, holidays, part-time schedules)?
- Is the URL sharing feature actually used?

## Phase History
_No phases completed yet_
