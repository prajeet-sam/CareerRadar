# Career Radar

> Stop looking at where the market is. Start looking at where it's moving.

Career Radar is an AI-powered career intelligence platform that continuously monitors the technology job market, GitHub ecosystems, and career progression patterns to provide students and aspiring professionals with actionable weekly insights.

Most career platforms tell you what skills are important today.

Career Radar tells you what changed this week.

Instead of static roadmaps, generic learning paths, and outdated career advice, Career Radar tracks real-world signals from the industry and transforms them into personalized recommendations.

---

# The Problem

Students are constantly told:

* Learn AI
* Learn Cloud
* Learn Cybersecurity
* Build Projects
* Contribute to Open Source

The problem is that these recommendations are static.

Technology evolves every week.

New frameworks emerge.
New skills become valuable.
Hiring requirements shift.
Career paths change.

Most students discover these changes months too late.

Meanwhile, top performers are adapting in real time.

Career Radar exists to close that gap.

---

# Core Idea

The real value is not the data.

The value is the delta.

Anyone can search:

"What skills are required for an AI Engineer?"

But almost nobody can answer:

* Which skills grew fastest this week?
* What projects are successful engineers building right now?
* Which technologies are appearing in job descriptions more frequently?
* What should I build this weekend to remain competitive?

Career Radar focuses on change detection.

Every week the platform compares fresh market data against previous snapshots and generates actionable intelligence.

---

# Key Features

## Weekly Career Intelligence Reports

Every week the platform generates a personalized report containing:

* Emerging technologies
* Rising skills
* Declining technologies
* Hiring trend changes
* New opportunities
* Personalized recommendations

Example:

RAG usage increased from 41% to 67% across tracked AI Engineer job descriptions this week.

Suggested Weekend Project:
Build a Retrieval-Augmented Generation chatbot using LangChain and ChromaDB.

---

## Career Twin Tracker

One of the platform's most powerful features.

Users can track engineers, developers, researchers, or professionals they aspire to become.

The system monitors:

* GitHub activity
* Open-source contributions
* New projects
* Repository growth
* Technology adoption

Example:

Your Career Twin:
Senior ML Engineer at Nvidia

This Week:

* Created 2 repositories
* Added Kubernetes skills
* Started contributing to a RAG project

Suggested Action:
Learn Kubernetes fundamentals.

---

## GitHub Momentum Score

Tracks personal growth over time.

Metrics include:

* Commit frequency
* Repository quality
* Open-source activity
* Documentation quality
* Project complexity
* Technology diversity

Provides a weekly score and trend analysis.

---

## Employability Score

A dynamic scoring system based on:

* Skills
* Projects
* GitHub activity
* Market demand
* Portfolio quality

Unlike traditional resume scoring systems, the score evolves with industry trends.

---

## Skill Gap Analysis

Users select a target role:

* AI Engineer
* Software Engineer
* Cybersecurity Analyst
* Bioinformatics Engineer
* Data Scientist

Career Radar compares current skills against market requirements and generates a personalized gap report.

---

## Job Trend Radar

Tracks thousands of job descriptions and identifies:

* Fast-growing skills
* Emerging technologies
* Regional hiring trends
* Salary signals
* Industry demand shifts

---

# Why Career Radar Is Different

Traditional Career Platforms:

✓ Static
✓ Generic
✓ Updated rarely

Career Radar:

✓ Dynamic
✓ Personalized
✓ Weekly Intelligence
✓ Change-Focused
✓ Data-Driven

The platform focuses on what changed rather than what exists.

---

# Architecture

Frontend

* Next.js
* TypeScript
* Tailwind CSS
* shadcn/ui

Backend

* Python
* FastAPI
* APScheduler
* PostgreSQL
* Redis

AI Layer

* OpenAI
* Ollama
* LangChain

Data Sources

* GitHub API
* Public Job Boards
* RSS Feeds
* Open Source Ecosystems

---

# Security

Security is designed into the platform from the beginning.

Features include:

* HTTP-only authentication cookies
* JWT-based sessions
* Rate limiting
* Secure API validation
* Row-level database isolation
* Encrypted credentials
* CSRF protection

---

# Database Design

users

Stores user information and preferences.

tracked_profiles

Stores tracked career twins and role models.

github_snapshots

Historical GitHub activity data.

job_snapshots

Historical job market data.

skills

Detected technologies and skills.

weekly_reports

Generated intelligence reports.

recommendations

AI-generated career suggestions.

---

# Example Weekly Report

Week 23 Report

Market Changes

* Kubernetes demand increased 18%

* LangGraph mentions increased 27%

* Agentic AI frameworks gained traction

- Traditional chatbot projects decreased

Your Progress

* 4 commits this week

* 1 repository created

* Python proficiency score increased

Recommendations

1. Build a multi-agent AI project.
2. Learn Kubernetes basics.
3. Contribute to one open-source repository.

Estimated Employability Score

78 → 84

---

# Roadmap

Phase 1

* Authentication
* GitHub Integration
* Weekly Reports

Phase 2

* Employability Scoring
* Skill Gap Analysis
* Career Twin Tracking

Phase 3

* AI Recommendation Engine
* Job Trend Radar
* Personalized Roadmaps

Phase 4

* Team Accounts
* University Dashboards
* Recruiter Insights

---

# Future Vision

Career Radar aims to become the Bloomberg Terminal for careers.

Instead of tracking stocks, it tracks opportunities.

Instead of monitoring markets, it monitors skills.

Instead of predicting companies, it predicts career trajectories.

The goal is simple:

Help ambitious students make better career decisions using real-world intelligence rather than generic advice.

---

# License

MIT License

---

Built with the belief that career growth should be driven by data, not guesswork.
