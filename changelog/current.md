# Changelog (Unreleased)

Record image-affecting changes to `manager/`, `worker/`, `openclaw-base/` here before the next release.

---

- feat(manager): add find-worker.sh to consolidate worker availability check (registry + state + lifecycle + SOUL.md) into a single script call
- fix(manager): lifecycle-worker.sh idle detection now considers infinite tasks — Workers with active infinite tasks are no longer auto-stopped
- fix(manager): HEARTBEAT.md Steps 5/6 updated to treat infinite tasks as active for idle detection and anomaly checks
- feat(manager): task-management SKILL.md adds finite vs infinite decision guide for the Agent
- fix(manager): TOOLS.md clarifies copaw runtime vs deployment mode (copaw ≠ remote), adds Deployment column to runtime table
- feat(manager): TOOLS.md task-management fewshot now includes infinite task trigger scenario
