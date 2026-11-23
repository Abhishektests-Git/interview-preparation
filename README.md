# Interview Preparation

Study material for SDET interviews, built while preparing.

## CI/CD Pipeline Animation

An animated conveyor-belt explainer of the full CI/CD process:

- A build travels station to station: Developer → Jenkins (Git webhook) → Build (Maven) → QA environment → Sanity check → Test cases → The Gate → Production
- **Scenario A:** all test cases pass in QA — the same build is promoted to production
- **Scenario B:** a test fails — defect raised, build loops back to the developer, fix re-enters as a new build, retest + regression run again before it can go live
- A "How Jenkins works" section: server, job/pipeline, stages, agent, triggers, reports

Open `index.html` in any browser, or view it live on GitHub Pages.

---
Created with ♡ by Aevi
