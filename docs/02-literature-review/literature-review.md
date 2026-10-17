# Literature Review

## Existing Solutions

| Tool / Platform | What it does | Limitation (based on its public description) |
|---|---|---|
| devb.io | Generates a developer portfolio from a GitHub profile, creates an AI-written bio, and tracks GitHub activity | Does not mention SEO-optimized project descriptions or a guided multi-step form |
| Folio | Turns GitHub activity into a portfolio and an ATS-optimized resume | Focused on profiles and resumes; does not mention AI-improved project descriptions or a live preview |
| PortGen | Imports GitHub repositories, offers themes with live preview, generates an AI bio, and deploys to GitHub Pages | AI is described for bio generation only; no mention of user accounts or saved data |

## Technologies Considered

| Technology | Purpose in PortfolioGenie |
|---|---|
| React, React Hooks | Build the interface as components and manage data and state changes |
| React Router | Navigation between the builder and the live preview |
| TypeScript | Clearer, safer code with fewer type errors |
| Node.js and Express | Backend server and RESTful API |
| AI API with prompt engineering | Improve project descriptions and suggest an "About Me" section |
| GitHub API | Fetch the user's GitHub activity |
| Docker Compose | Run the frontend, backend, and database together |
| MongoDB (proposed, not final) | Store user data and projects |

## What Makes PortfolioGenie Different
- AI-generated, SEO-optimized project descriptions
- "About Me" suggestions based on the user's coding style
- User accounts with saved projects and skills, managed through a RESTful API
- A guided multi-step form for entering project details

## Note
Some features, such as GitHub import, AI bios, and live preview, already exist in other tools. PortfolioGenie's value is in combining them with SEO-focused descriptions, saved user data, and a guided workflow.

## References
1. devb.io: https://fossunited.org/hack/fosshack25/p/9kn8ebhl0e
2. Folio: https://github.com/foliohq/folio
3. PortGen: https://hunted.space/product/portgen
