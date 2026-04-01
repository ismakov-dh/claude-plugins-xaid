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
