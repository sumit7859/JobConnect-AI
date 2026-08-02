# JobConnect AI — Smart Job Portal

A production-ready, AI-powered job portal built with Next.js, React, TypeScript, Tailwind CSS, and Bolt Database. Features intelligent job matching, resume analysis, career suggestions, and interview preparation — all wrapped in a premium, fully responsive UI with dark/light mode.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Live Demo Account](#live-demo-account)
- [Getting Started](#getting-started)
- [Environment Variables](#environment-variables)
- [Database Schema](#database-schema)
- [AI Engine](#ai-engine)
- [Project Structure](#project-structure)
- [Pages](#pages)
- [Deployment](#deployment)
- [Scripts](#scripts)
- [License](#license)

---

## Overview

JobConnect AI connects talent with opportunity using AI-driven matching. Candidates get personalized job recommendations, a resume score with actionable feedback, and AI-generated interview prep. Recruiters can post jobs, manage applicants, and track hiring pipelines — all in one place.

## Features

### Candidate
- Register / Login with email and password
- Build a professional profile (skills, experience, education, certifications, portfolio)
- Upload / paste resume for AI analysis
- Resume Builder with download
- Search and filter jobs (category, type, work mode, salary, sort)
- Save jobs for later
- Apply to jobs with optional cover letter
- Track application status (pending → reviewing → shortlisted → interviewed → hired/rejected)
- AI job recommendations with match score (0–100) and skill-gap analysis
- AI career suggestions based on profile
- AI resume score with section-level suggestions
- AI interview preparation questions per job

### Recruiter
- Register as a recruiter
- Create and edit a company profile (logo, website, industry, size, location)
- Post, edit, close, and delete jobs
- View all applicants across jobs
- Update applicant status (shortlist, reject, schedule interview, hire)
- Dashboard analytics (active jobs, total applicants, shortlisted, hired)

### General
- Fully responsive (mobile, tablet, desktop)
- Dark & light mode with system detection
- SEO-optimized with metadata
- Premium UI with animations and micro-interactions
- Secure row-level security on all database tables
- Real-time data via Bolt Database

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Next.js 13 (App Router), React 18, TypeScript |
| Styling | Tailwind CSS, shadcn/ui components |
| Icons | Lucide React |
| Backend / Database | Bolt Database (PostgreSQL) |
| Auth | Bolt Database Auth (email/password, JWT, bcrypt hashing) |
| AI | Custom TypeScript AI engine (resume scoring, matching, recommendations) |
| Fonts | Inter, Plus Jakarta Sans (Google Fonts) |

## Live Demo Account

A demo recruiter account is pre-seeded with sample companies and jobs:

