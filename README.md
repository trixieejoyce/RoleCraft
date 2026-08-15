# RoleCraft

### AI-Assisted Resume-to-Job Matching and Application Tailoring System

> Craft your resume. Match the role. Apply with confidence.

---

## 📌 Project Overview

RoleCraft is a web-based application designed to help job seekers improve
the alignment between their resume and a specific job posting.

Users can upload their resume and provide a target job description. The
system analyzes both sources to identify relevant skills, qualifications,
keywords, experience alignment, and potential skill gaps.

The application combines conventional software logic with artificial
intelligence to provide job-specific recommendations. Based on the analysis,
RoleCraft can assist users in tailoring their resume and generating a
job-specific cover letter.

---

## 🎯 Objectives

- Analyze a user's resume against a target job posting.
- Identify relevant and missing skills.
- Evaluate resume-to-job alignment.
- Provide an AI-assisted job-fit analysis.
- Provide ATS-oriented recommendations.
- Tailor the user's resume for a specific job.
- Generate a job-specific cover letter.
- Provide an accessible web-based application deployed through Vercel.

---

## ✨ Core Features

### Resume Management
- Upload resume
- View resume information
- Manage resume versions
- Extract resume information

### Job Post Management
- Paste job descriptions
- Extract job requirements
- Identify required and preferred qualifications

### Resume-to-Job Analysis
- Skill matching
- Keyword analysis
- Experience alignment
- Job-fit score
- Skill-gap identification

### AI-Assisted Features
- Resume parsing
- Job description analysis
- Semantic skill matching
- Skill-gap recommendations
- Resume tailoring
- Cover letter generation

### ATS-Oriented Analysis
- Keyword coverage
- Requirement coverage
- Job-specific terminology
- Resume improvement recommendations

---

## 🤖 AI Integration

RoleCraft does not rely entirely on artificial intelligence.

The system combines conventional programming techniques with AI-assisted
processing.

### Conventional Processing

- File validation
- PDF text extraction
- Database operations
- Authentication
- Keyword matching
- Score calculations
- File management
- Access control

### AI-Assisted Processing

- Resume contextual analysis
- Job description interpretation
- Semantic skill matching
- Skill-gap analysis
- Resume tailoring
- Cover letter generation

---

## 🛠 Technology Stack

### Frontend
- Next.js
- TypeScript
- Tailwind CSS
- shadcn/ui
- Recharts

### Backend
- Next.js Route Handlers
- TypeScript
- Zod

### Database and Storage
- Supabase
- PostgreSQL
- Supabase Authentication
- Supabase Storage

### Artificial Intelligence
- Gemini 2.5 Flash
- Vercel AI SDK

### Testing
- Vitest
- Playwright

### Development
- Git
- GitHub
- GitHub Projects
- Kanban

### Deployment
- Vercel

---

## REPOSITORY STRUCTURE

```text
RoleCraft/
├── .github/
├── docs/
├── public/
├── src/
│   ├── app/
│   ├── components/
│   ├── lib/
│   ├── types/
│   └── config/
├── supabase/
│   └── migrations/
├── tests/
│   ├── unit/
│   ├── integration/
│   └── e2e/
├── .env.example
├── .gitignore
├── README.md
└── package.json

