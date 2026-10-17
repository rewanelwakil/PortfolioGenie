# Risk Assessment & Mitigation Plan

| # | Risk | Likelihood | Impact | Mitigation |
|---|---|---|---|---|
| 1 | GitHub or AI API rate limits or unavailable data | Medium | High | Cache fetched data and handle errors with clear messages |
| 2 | AI-generated text is low quality or inaccurate | Medium | High | Refine prompts and let users review and edit before publishing |
| 3 | Not enough time before deadlines | High | High | Build the core features first and postpone extras |
| 4 | Team members work on conflicting code | Medium | Medium | Use GitHub branches and pull requests |
| 5 | Unclear tasks between team members | Medium | Medium | Define roles clearly and review progress regularly |
| 6 | AI API key exposed in the frontend or on GitHub | Low | High | Keep the key on the backend only and never commit it to the repository |
| 7 | Team is learning many technologies at once (React, TypeScript, Node.js, Express) | High | Medium | Build a simple version first, then add the backend, database, and AI step by step |
