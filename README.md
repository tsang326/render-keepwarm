# render-keepwarm

A scheduled GitHub Actions workflow that pings two free Render services every
5 minutes between 2026-12-01 and 2026-12-16 (UTC), so they do not sleep while
hackathon judges try them. Outside that window each run exits at once.
