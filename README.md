# RoleCraft

An AI-Assisted Resume-to-Job Matching and Application Tailoring System

RoleCraft is a web-based application designed to help job seekers improve
the alignment between their resume and a specific job posting.

Users can upload their resume and provide a target job description. The
system analyzes both sources to identify relevant skills, qualifications,
keywords, experience alignment, and potential skill gaps.

The application combines conventional software logic with artificial
intelligence to provide job-specific recommendations. Based on the analysis,
RoleCraft can assist users in tailoring their resume and generating a
job-specific cover letter.

##OBJECTIVES

- Analyze a user's resume against a target job posting.
- Identify relevant and missing skills.
- Evaluate resume-to-job alignment.
- Provide an AI-assisted job-fit analysis.
- Provide ATS-oriented recommendations.
- Tailor the user's resume for a specific job.
- Generate a job-specific cover letter.
- Provide an accessible web-based application deployed through Vercel.

##CORE FEATURES

Resume Management
  - Upload resume
  - View resume information
  - Manage resume versions
  - Extract resume information

Job Post Management
  - Paste job descriptions
  - Extract job requirements
  - Identify required and preferred qualifications

Resume-to-Job Analysis
  - Skill matching
  - Keyword analysis
  - Experience alignment
  - Job-fit score
  - Skill-gap identification

 AI-Assisted Features
  - Resume parsing
  - Job description analysis
  - Semantic skill matching
  - Skill-gap recommendations
  - Resume tailoring
  - Cover letter generation

ATS-Oriented Analysis
  - Keyword coverage
  - Requirement coverage
  - Job-specific terminology
  - Resume improvement recommendations


##AI INTEGRATION

RoleCraft does not rely entirely on artificial intelligence.The system combines conventional programming techniques with AI-assisted processing.

Conventional Processing
  - File validation
  - PDF text extraction
  - Database operations
  - Authentication
  - Keyword matching
  - Score calculations
  - File management
  - Access control

AI-Assisted Processing
  - Resume contextual analysis
  - Job description interpretation
  - Semantic skill matching
  - Skill-gap analysis
  - Resume tailoring
  - Cover letter generation


##TECH STACK

Frontend
  - Next.js
  - TypeScript
  - Tailwind CSS

Backend
- Next.js Route Handlers
- TypeScript
- Zod

Database and Storage
- Supabase
- PostgreSQL
- Supabase Authentication
- Supabase Storage

Artificial Intelligence
- Gemini 2.5 Flash
- Vercel AI SDK

Deployment
- Vercel

Repository Structure
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

##⚠️ Project Scope

The initial version will focus on user-provided resumes and job
descriptions.

Users will initially provide job postings through text input or
copy-and-paste.

The system will not directly scrape or integrate with third-party
platforms such as LinkedIn, JobStreet, Indeed, Upwork, or OnlineJobs.ph.

The application will not guarantee employment, interview selection, or
ATS acceptance.

AI-generated recommendations and documents should be reviewed by the
user before being submitted to an employer.
