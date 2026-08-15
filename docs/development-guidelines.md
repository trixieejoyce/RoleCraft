# Development Guidelines

## Branch Naming

Use the following format:

feature/feature-name
fix/bug-name
refactor/component-name
test/test-name
docs/documentation-name

Examples:

feature/resume-upload
feature/job-analysis
fix/pdf-validation
docs/project-overview

---

## Commit Naming

Use:

feat(scope): description
fix(scope): description
test(scope): description
docs: description
refactor(scope): description
chore: description

Examples:

feat(resume): add resume upload
feat(ai): add resume parser
fix(resume): validate PDF file size
test(ai): add resume parser tests
docs: update project overview

---

## File Naming

Use kebab-case for files.

Examples:

resume-upload.tsx
job-details.tsx
match-score.tsx
resume-parser.ts

React components should use PascalCase.

Examples:

ResumeUpload
JobDetails
MatchScore

Variables and functions should use camelCase.

Examples:

resumeData
calculateMatchScore()

Database tables and columns should use snake_case.

Examples:

resume_versions
user_id
created_at

---

## Pull Requests

Every feature should be developed in its own branch.

Developers should create a Pull Request before merging into the main
branch.

At least one other team member should review the Pull Request.

Do not directly push feature work to main.

---

## Kanban

Tasks are managed through GitHub Projects.

Workflow:

BACKLOG
→ READY
→ IN PROGRESS
→ CODE REVIEW
→ TESTING
→ DONE

Use BLOCKED when a task cannot continue because of a dependency or
technical issue.
