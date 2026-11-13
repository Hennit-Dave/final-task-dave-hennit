# Final Graduation Task, Dave Hennit

- Primary role: Design engineer
- Secondary role: UI/UX designer
- Positioning: I am a design engineer who builds polished web and mobile apps for early-stage startups.
- Working hours: 1pm to 9pm WAT (full UK overlap, US East mornings and early afternoon)

## Part 1: Job preparation
- GitHub profile: https://github.com/Hennit-Dave
- LinkedIn: https://www.linkedin.com/in/dave-hennit
- Portfolio: https://www.davebuilds.design
- Job post analysis + skill gaps: [job-posts.md](./job-posts.md)
- Lead tracker (view-only): https://docs.google.com/spreadsheets/d/1TZTkKmbPBNSnFwDaLNNwZSpem-U5D6YX7Gqkea-bkwc/edit?usp=sharing
- Message library: https://docs.google.com/spreadsheets/d/1TZTkKmbPBNSnFwDaLNNwZSpem-U5D6YX7Gqkea-bkwc/edit#gid=2 (in progress, reply rates fill in once messages are sent)
- Daily log: https://docs.google.com/spreadsheets/d/1TZTkKmbPBNSnFwDaLNNwZSpem-U5D6YX7Gqkea-bkwc/edit#gid=1

## Open source contributions

**Pull requests opened during this task**

| PR | Project | What it does | Status |
|---|---|---|---|
| [Time-Tracker #359](https://github.com/HafidIdrissi/Time-Tracker/pull/359) | Local Time Tracker | Isolates right-to-left window titles with `<bdi dir="auto">` in report tables, with an HTMLParser regression test. All 5 CI checks passing, including Windows | Merged 9 Oct 2026 |
| [OpsiMate #1148](https://github.com/OpsiMate/OpsiMate/pull/1148) | OpsiMate | Fixes the action-run metric so successful runs are counted as `success` instead of `error`, with a Vitest regression test | Merged 11 Oct 2026 |

**Earlier merged PR (before this task)**

| PR | Project | What it does | Status |
|---|---|---|---|
| [Time-Tracker #338](https://github.com/HafidIdrissi/Time-Tracker/pull/338) | Local Time Tracker | Documentation PR closing #322, with a validation script and 96 passing tests | Merged |

**Edge project:** Local Time Tracker — small project, responsive maintainer, two contributions.

**5 issues saved for future contributions**

1. [OpsiMate #1122](https://github.com/OpsiMate/OpsiMate/issues/1122) — associate form labels with their inputs (accessibility)
2. [OpsiMate #1125](https://github.com/OpsiMate/OpsiMate/issues/1125) — `aria-expanded` on group chevron, plus component dedupe
3. [Valibot #1693](https://github.com/open-circle/valibot/issues/1693) — `isoTimestamp` accepts strings `new Date()` cannot parse
4. [halloween.js #1](https://github.com/rogulia/halloween.js/issues/1) — light-theme `--fg-faint` fails WCAG AA contrast
5. [Time-Tracker #349](https://github.com/HafidIdrissi/Time-Tracker/issues/349) — stale version number in the installer licence notice


## LinkedIn posts

**Week of 6 Oct**
1. Merged PR — right-to-left title isolation in Local Time Tracker: https://lnkd.in/p/dZJNMxPd
2. What 10 design engineer job posts actually ask for: https://lnkd.in/p/dTyCJurt
3. Two merged PRs in a week, and the three things that made them merge fast: https://lnkd.in/p/d3TcBvtd

**Week of 13 Oct**
1 Two Agents, One Set of Rules:https://lnkd.in/p/d5yxG3tK
2. When Offline Changes Should Wait:https://lnkd.in/p/dqJmquxa
3. Importance of ADRs:https://lnkd.in/p/dCrXma2G

**Week of 20 Oct**
1.Why my login server keeps attackers guessing, on purpose: https://lnkd.in/p/d78H_d6F
2.My free database fell asleep, and my login broke: https://lnkd.in/p/d-krDBKv
3.First real team invite email.- https://lnkd.in/p/d-8C-Q-W

**Week of 27 Oct**
1.A failed response doesn’t always mean a failed request- https://lnkd.in/p/dtbbu6Np
2.Five retries arrived together. Two came back as conflicts- https://lnkd.in/p/d8UhDhC4
3.My test payment ended up in the wrong database- https://lnkd.in/p/d4bREn87



## Part 2: Mobile apps 

### Rota
- **Repo:** https://github.com/Hennit-Dave/rota
- **Android build (preview APK):** https://expo.dev/accounts/hennitdave/projects/rota/builds/a7d7a16c-6699-493a-b139-c7ce640d1c9f
- **Deployed backend:** https://api.rota.davebuilds.design/health
- **Architecture diagram:** https://github.com/Hennit-Dave/rota/blob/main/docs/ARCHITECTURE.md
- **Tests:**
  - Permissions: https://github.com/Hennit-Dave/rota/blob/main/server/src/teams/permissions.unit.test.ts
  - Team isolation: https://github.com/Hennit-Dave/rota/blob/main/server/src/teams/team-security.integration.test.ts
  - Proration: https://github.com/Hennit-Dave/rota/blob/main/server/src/billing/proration.unit.test.ts
- **Load test report:** https://github.com/Hennit-Dave/rota/blob/main/load-tests/REPORT.md
- **Docs:**
  - README: https://github.com/Hennit-Dave/rota/blob/main/README.md
  - Architecture: https://github.com/Hennit-Dave/rota/blob/main/docs/ARCHITECTURE.md
  - Security: https://github.com/Hennit-Dave/rota/blob/main/docs/SECURITY.md
  - Sharding: https://github.com/Hennit-Dave/rota/blob/main/docs/SHARDING.md
  - App state: https://github.com/Hennit-Dave/rota/blob/main/docs/STATE.md
  - Decisions (ADRs): https://github.com/Hennit-Dave/rota/tree/main/docs/decisions
  - Learning log: https://github.com/Hennit-Dave/rota/blob/main/LEARNING-LOG.md
  - Submission checklist: https://github.com/Hennit-Dave/rota/blob/main/SUBMISSION.md
- **Demo video:** https://lnkd.in/p/dn2k73bD
- **LinkedIn post:** https://lnkd.in/p/dn2k73bD


### Matinee
- **Repo:**
  - Mobile: https://github.com/Hennit-Dave/matinee-mobile
  - Server: https://github.com/Hennit-Dave/matinee-server
- **Android build:**
- **Deployed backend:**
- **Figma:** https://www.figma.com/design/76VKO0l9gGt5YMNYtH8yvM
- **Docs:**
  - README (mobile): https://github.com/Hennit-Dave/matinee-mobile/blob/main/README.md
  - README (server): https://github.com/Hennit-Dave/matinee-server/blob/main/README.md
  - Architecture: ARCHITECTURE.md — not written yet (required deliverable → matinee-server)
  - Traffic management:TRAFFIC.md — not written yet (required deliverable → matinee-server)
  - Sharding (plan only):SHARDING.md — not written yet (required deliverable → matinee-server)
  - Components:https://github.com/Hennit-Dave/matinee-mobile/blob/main/docs/COMPONENTS.md
  - Design study (5 apps):https://github.com/Hennit-Dave/matinee-mobile/blob/main/docs/DESIGN-STUDY.md
  - Decisions (ADRs):https://github.com/Hennit-Dave/matinee-server/tree/main/docs/decisions
  - Learning log (mobile):https://github.com/Hennit-Dave/matinee-mobile/blob/main/LEARNING-LOG.md
  - Learning log (server):https://github.com/Hennit-Dave/matinee-server/blob/main/LEARNING-LOG.md
- **Load test report:**
- **Demo video:**
- **LinkedIn post:**
- Case study:

## Part 3: System design
- DESIGN.md / Diagram / Prototype / Load test + failure drill / Walkthrough / Mock interview notes:

## Part 4: RAG
- RAG-NOTES.md / Diagram / Repo / Deployed app / EVALUATION.md / Demo video / Posts: