# Data sources

Every external source used to build or demo Antibody, as required by the
hackathon data guidelines. Only sources whose terms allow commercial use.

| Source | URL | License / terms | What we used it for | Commit or date |
|---|---|---|---|---|
| Demo repository: APScheduler (branch `3.x`) | https://github.com/agronholm/apscheduler | MIT | Target codebase for the demo run (fix commit for DST-unsafe datetime arithmetic) | `1693db4` |
| Practice repository: demo-target | https://github.com/JoaquinYap/demo-target | Written by the team, no third-party code | Synthetic repo with hand-seeded twins (naive vs. aware datetime) used to rehearse Antibody runs | 2026-09-25 |

## Privacy

- No personal information is stored: Antibody files never include author names
  or emails from git history, and the demo video does not show them.
- No client data, confidential data or social media data is used.
- Postmortems used as input are written by the team for the demo bug.
