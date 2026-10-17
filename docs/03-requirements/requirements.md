# Requirements Gathering

## Stakeholder Analysis

| Stakeholder | Needs |
|---|---|
| Junior developers (main users) | A simple way to create a professional portfolio |
| Recruiters and hiring managers | Clear, well-presented projects and an "About Me" section |
| Lecturer / mentor | Complete documentation and a working project |
| Development team | Clear tasks and maintainable code |

## User Stories

1. As a new user, I want to sign up and log in, so that my data and projects are saved privately.
   - *Acceptance criteria:* I can only see and edit my own portfolio data.
2. As a junior developer, I want to enter my project details through a multi-step form, so that the process is not overwhelming.
   - *Acceptance criteria:* I can go back to a previous step without losing my data.
3. As a user, I want to add, edit, and delete my projects and skills, so that my portfolio stays up to date.
   - *Acceptance criteria:* Changes are saved and still appear when I log in again.
4. As a user, I want to connect my GitHub account, so that my GitHub activity is used to personalize my portfolio content.
   - *Acceptance criteria:* The platform shows the GitHub data it fetched and uses it in the generated content.
5. As a user, I want AI to improve my project descriptions, so that they read better and rank better in search.
   - *Acceptance criteria:* I can see the suggested text and accept or edit it.
6. As a user, I want a suggested "About Me" section, so that I do not have to write it from scratch.
   - *Acceptance criteria:* I can review and edit it before publishing.
7. As a user, I want a live preview, so that I can check how my portfolio looks.
   - *Acceptance criteria:* The preview updates after I change my data.

## Functional Requirements

- User sign up and login
- Multi-step form for entering personal information, skills, and projects
- Create, read, update, and delete projects through a RESTful API (Node.js and Express)
- Analysis of the user's GitHub activity
- AI-generated, SEO-optimized project descriptions
- AI-suggested "About Me" section based on the user's coding style
- Live preview of the portfolio
- Navigation between the builder and the preview (React Router)
- Publishing the portfolio (optional, to be decided by the team)

## Proposed Pages

Landing Page, Sign Up / Login, Dashboard, Personal Information, Skills, Projects, GitHub Integration, AI Assistant, Portfolio Builder, Live Preview. These pages are a proposal for the final product, not a fixed list.

## Non-functional Requirements

- **Performance:** fast page loads and quick content generation
- **Usability:** simple, responsive interface following accessibility guidelines
- **Maintainability:** clean, typed code (TypeScript) following industry-standard conventions
- **Security:** user data is protected, and the AI API key is stored on the backend only, never in the frontend code
- **Reliability:** errors from the AI or GitHub services are handled with clear messages
