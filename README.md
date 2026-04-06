# xAID Claude Code Plugins

Internal plugin marketplace for the xAID team.

## Setup

Add this marketplace:

```
/plugins marketplace add ismakov-dh/claude-plugins-xaid
```

## Available Plugins

### xaid-shared-skills

Shared team skills — radiology report grading, sales analysis, reporting, workflow automation.

```
/plugins install xaid-shared-skills@claude-plugins-xaid
```

### vibe-deploy

Build and deploy vibecoded apps to bare metal servers:

- `/vibe` — Load platform constraints before building an app. Ensures the app uses only supported infrastructure (HTTP, PostgreSQL, cron).
- `/deploy` — Deploy apps to bare metal servers via SSH. Handles database provisioning, routing, rollback.

```
/plugins install vibe-deploy@claude-plugins-xaid
```

### qagent

Automated UI and behavior testing — Claude orchestrates browser interactions, verifies state changes, and evolves test cases from failures.

- `/qagent:test` — Execute test flows defined in `qagent.json`
- `/qagent:plan` — Preview test execution without running tests
- `/qagent:explore` — Interactive QA testing with browser exploration
- `/qagent:merge` — Merge discovered test cases into target branch
- `/qagent:report` — Re-send results from the last test run

```
/plugins install qagent@claude-plugins-xaid
```
