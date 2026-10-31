# Awesome-Software-Development-Project-Tracking

# Top Software Development Project Tracking Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Issue Tracking, Sprint Planning & Self-Hosted Engineering Workflows*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Software Development Project Tracking**. These tools enable engineering teams to plan sprints, track issues and bugs, manage roadmaps, and ship software predictably—connecting daily development work to product strategy without drowning in process overhead.

**Examples** include Jira Software, Linear, GitHub Issues, GitLab, Shortcut, Azure Boards, Monday dev, ClickUp, Pivotal Tracker, and Height (the category leaders).

**Open-source emphasis**: Software Development Project Tracking is a domain where open-source tooling is **genuinely competitive for core issue tracking and sprint workflows**. **Plane** is the standout—a self-hostable Jira/Linear alternative with 59k+ GitHub stars, AGPL-3.0 licensed, and actively maintained with 449 commits in the last 90 days . It provides work items, cycles (sprints), modules, pages (wiki), and five layout views (List, Board, Spreadsheet, Gantt, Calendar) . **OpenProject** offers a more traditional project management approach with Gantt charts and portfolio views, GPL-3.0 licensed . **Taiga** provides agile Scrum/Kanban boards with MPL-2.0 licensing, though with fewer recent commits . **Huly** attempts an all-in-one workspace combining project management, chat, and docs—EPL-2.0 licensed and very actively maintained . The critical caveat: **Height has been discontinued** , and **Pivotal Tracker's open-source drop-in replacement (cm42-central) has only 328 stars** with a health score of 4.2/10—suggesting limited community momentum .

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Jira Software](https://www.atlassian.com/software/jira)**  
  The enterprise standard for software project tracking; Scrum/Kanban boards, backlogs, roadmaps, and deep integration with the Atlassian ecosystem. Powerful but often criticized for configuration complexity.

- **[Linear](https://linear.app/)**  
  The modern, keyboard-first issue tracker beloved by startups; fast, opinionated, with cycles, projects, and a clean interface. Positioned as the anti-Jira for product teams.

- **[GitHub Issues](https://github.com/features/issues)**  
  Native issue tracking within GitHub; issues, labels, milestones, and project boards tightly integrated with repositories and pull requests. Free for public repos and included in paid plans.

- **[GitLab](https://about.gitlab.com/)**  
  DevOps platform with built-in issue tracking, boards, epics, and milestones; deeply integrated with GitLab CI/CD and merge requests.

- **[Shortcut](https://shortcut.com/)**  
  Project management for software teams (formerly Clubhouse); stories, epics, iterations, and a clean workflow focused on developer productivity.

- **[Azure Boards](https://azure.microsoft.com/en-us/products/devops/boards)**  
  Work tracking within Azure DevOps; backlogs, boards, sprints, and queries with deep integration into Microsoft's development toolchain.

- **[Monday dev](https://monday.com/)**  
  Software development template within monday.com's work OS; customizable boards and automations for product and engineering teams.

- **[ClickUp](https://clickup.com/)**  
  All-in-one productivity platform with tasks, docs, goals, and multiple views; flexible but broad rather than engineering-focused.

- **[Pivotal Tracker](https://www.pivotaltracker.com/)**  
  **Discontinued**—Pivotal Tracker was shut down; listed as a historical reference. Its open-source drop-in replacement (cm42-central) exists but has limited community momentum .

- **[Height](https://height.app/)**  
  **Discontinued**—Height announced shutdown; listed as a historical reference .

## Open-Source GitHub Projects

### Modern Jira/Linear Alternatives

- **[Plane](https://github.com/makeplane/plane)**  
  The most mature open-source **Jira/Linear/Monday/ClickUp alternative** (AGPL-3.0, 59k+ GitHub stars, 449 commits/90d) . Features: **Work Items** with rich text and sub-items, **Cycles** (sprints) with burn-down charts, **Modules** for grouping related work, **Pages** for wiki/docs with AI assistance, five layout views (List, Board, Spreadsheet, Gantt, Calendar), **Intake** for triaging incoming requests, and integrations with GitHub, GitLab, Slack, and Sentry . Imports from Jira, Linear, Asana, ClickUp, and Monday. **Version 1.3.0** adds Gitea authentication, a Project Summary API, and closes several security vulnerabilities . Railway one-click deployment bundles PostgreSQL, Redis, RabbitMQ, and MinIO . **The strongest open-source foundation for engineering teams replacing Jira or Linear**—but self-hosting requires 4GB RAM minimum (8GB recommended) and operational ownership .

- **[Huly](https://github.com/hcengineering/platform)**  
  Open-source **all-in-one project management platform** positioned as a self-hostable alternative to Linear, Jira, Slack, and Notion (EPL-2.0, 28k GitHub stars, 33 commits/90d) . Combines project tracking, team chat, virtual office, and collaborative docs in a single workspace. **Best for teams wanting an integrated workspace** rather than a focused issue tracker—each module is less deep than dedicated tools.

- **[Kaneo](https://github.com/usekaneo/kaneo)**  
  Fast, simple open-source project management (MIT, 9.5k GitHub stars, 1,228 commits/90d—the most actively developed option in this list) . Features Board, List, Calendar, and Gantt views; subtasks, dependencies, labels, comments, and time tracking; custom columns and fields with rules; GitHub/Gitea integration; REST API, CLI, and **MCP for AI assistants**. **Best for teams wanting focused task management without workspace bloat**—the highest development velocity among open-source options.

### Traditional Project Management

- **[OpenProject](https://github.com/opf/openproject)**  
  Full-featured open-source project management platform (GPL-3.0, 16k GitHub stars, 4,284 commits/90d) . Features Gantt charts, Agile boards (Kanban/Scrum), time tracking, roadmaps, and portfolio views. **Best for traditional project management** with detailed planning—heavier than Plane or Kaneo but more comprehensive for non-software projects.

- **[Taiga](https://github.com/kaleidos-ventures/taiga)**  
  Agile project management tool for Scrum and Kanban teams (MPL-2.0, 859 GitHub stars, 30 commits/90d) . Features epics, user stories, tasks, issues, and sprint management. **Best for teams wanting a focused Agile tool**—but development pace is slower than Plane or Kaneo.

- **[Leantime](https://github.com/Leantime/leantime)**  
  Lean project management system for small teams and startups (AGPL-3.0, 12k GitHub stars, 105 commits/90d) . Features kanban boards, Gantt charts, goal tracking, time tracking, and idea management. **Best for startups** wanting an integrated project management + strategy tool.

### Pivotal Tracker Replacement

- **[cm42-central](https://github.com/Codeminer42/cm42-central)**  
  Fork of the Fulcrum project—a **Pivotal Tracker drop-in replacement** (AGPL-3.0, 328 GitHub stars) . **Critical caveat**: health score of **4.2/10** from Open Source Insights, indicating limited community activity and maintenance. **Only recommended for teams already committed to the Pivotal Tracker workflow** who need a self-hosted continuation—evaluate maintenance risk carefully before adoption.

### Additional Strong Open-Source Options

- **OneDev** — All-in-one DevOps platform with Git management, issue tracking, and CI/CD (MIT, 15k GitHub stars, 379 commits/90d) . **Best for teams wanting an integrated Git + issues + CI platform** rather than a standalone tracker.
- **4ga Boards** — Straightforward real-time kanban boards (MIT, 730 GitHub stars, 29 commits/90d) . **Best for simple kanban** without sprint or roadmap complexity.
- **ZenTao** — Agile Scrum project management (AGPL-3.0, 1.7k GitHub stars, 1,888 commits/90d—very actively maintained) . **Best for teams wanting a comprehensive Scrum tool** with QA and bug tracking integration.

**Frameworks for building custom systems**: For **modern engineering teams replacing Jira/Linear**, Plane is the strongest option with the most active development and feature depth . For **maximum development velocity and simplicity**, Kaneo . For **integrated workspace with chat and docs**, Huly . For **traditional project management with Gantt**, OpenProject . For **Pivotal Tracker refugees**, cm42-central (accepting maintenance risk) . No open-source project matches Jira's **enterprise configuration depth** or Linear's **polished UX** out of the box—choose based on whether you need depth (Plane, OpenProject) or speed (Kaneo).

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Project tracking platforms handling engineering data must comply with organizational security policies; **self-hosted solutions place full responsibility for security patches, backups, and uptime on the operator**.
- **Open-source software project tracking is mature for core issue tracking and sprint workflows**—Plane provides a production-grade Jira/Linear alternative with active development , and Kaneo offers a lightweight, fast-moving option . However, **Height is discontinued** , and **Pivotal Tracker's open-source replacement has limited community momentum** . Choose based on whether you need feature depth (Plane) or simplicity (Kaneo), and verify maintenance status before adoption.
- Verify license terms for commercial use; Plane uses AGPL-3.0 , Kaneo uses MIT , Huly uses EPL-2.0 , and OpenProject uses GPL-3.0 .

---

**Made for engineering managers, product teams, and developers choosing their project tracking stack.**  
Let's make software development tracking more open, but with clear eyes about the discontinued tools and the maintenance momentum that separates viable options from abandoned ones.
