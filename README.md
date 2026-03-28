# Atlas — Job Intelligence System

> Find the right role. Not just more roles.

Atlas is a precision-driven job discovery platform that filters noise, scores relevance, and surfaces only high-signal opportunities — built with a strong focus on product thinking, clean UX, and deterministic logic.

---

## Why Atlas Exists

Most job platforms optimize for **volume**.
Atlas optimizes for **relevance**.

Instead of scrolling through hundreds of listings, users get:

* Structured filtering
* Transparent match scoring
* Daily curated opportunities

---

## Core Capabilities

### Intelligent Match Scoring

Every job is evaluated using a deterministic scoring engine.

Signals include:

* Keyword relevance
* Skill overlap
* Location & work mode alignment
* Experience match
* Recency of posting
* Source credibility

Each job receives a **0–100 match score**, enabling fast decision-making.

---

### Clean, Signal-First Dashboard

* Card-based layout with only decision-relevant data
* No clutter, no distractions
* Smooth interactions, no page reloads

Each job includes:

* Match score badge
* Source indicator
* Salary + experience
* Quick actions (View / Save / Apply)

---

### Preference-Driven Personalization

Users define:

* Role keywords
* Skills
* Preferred locations
* Work mode
* Experience level
* Minimum match threshold

All preferences persist locally and auto-load seamlessly.

---

### Advanced Filtering System

Multi-filter system using strict AND logic:

* Keyword search
* Location
* Mode
* Experience
* Source
* Status

Sorting:

* Latest
* Match score
* Salary

---

### Job Lifecycle Tracking

Track progress across:

* Not Applied
* Applied
* Rejected
* Selected

Includes:

* Persistent state
* Visual feedback
* Status-based filtering

---

### Daily Digest Engine (9AM Simulation)

Generates top 10 opportunities based on:

1. Match score (descending)
2. Recency (ascending)

Features:

* Email-style layout
* Copy to clipboard
* One-click email draft

---

### Built-in Validation System

Atlas includes an internal checklist to ensure:

* Matching logic works correctly
* Persistence is stable
* Filters behave as expected

A **Ship Lock system** prevents deployment until all checks pass — enforcing engineering discipline.

---

## Design Philosophy

Atlas follows a strict, premium design system:

* Calm, minimal interface
* Serif-based hierarchy for clarity
* Off-white canvas (#F7F6F3)
* Deep red accent (#8B0000)
* No gradients, no visual noise
* Generous whitespace
* Predictable interactions

The goal: **clarity over decoration**.

---

## Architecture

* Single Page Application (SPA)
* Route-based structure
* Shared navigation shell
* Fully client-side (no backend)

---

## Storage Model

| Feature        | Storage Key             |
| -------------- | ----------------------- |
| Preferences    | jobTrackerPreferences   |
| Saved Jobs     | jobTrackerSaved         |
| Job Status     | jobTrackerStatus        |
| Daily Digest   | jobTrackerDigest_{date} |
| Test Checklist | jobTrackerTestStatus    |

---

## Tech Stack

* HTML5, CSS3, JavaScript
* LocalStorage for persistence
* Vercel for deployment
* SPA routing configuration

---

## Running the Project

```bash
# Clone repository
git clone https://github.com/your-username/atlas-job-intelligence.git

# Open directly
index.html
```

---

## What This Project Demonstrates

* Strong product thinking (not just feature building)
* Clean UI system design
* Deterministic logic implementation
* State management without external libraries
* Real-world UX problem solving

---

## Future Scope

* Backend integration
* Real-time job APIs
* Authentication
* Automated email digests
* AI-assisted job matching

---

## Author

Revanth Yerraguntla

---

> Built with intent. Designed for clarity. Structured for scale.
