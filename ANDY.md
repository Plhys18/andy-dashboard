# Andy Dashboard

Live URL: https://plhys18.github.io/andy-dashboard/
Repo: https://github.com/Plhys18/andy-dashboard
Local path: /workspace/projects/dashboard/ (or full: groups/main/projects/dashboard/)

## How to update

Edit `index.html`, then:
```
git add . && git commit -m "..." && git push
```
GitHub Actions deploys automatically in ~10 seconds.

## Planned modules

- Portfolio value (connect my-wallets.json, fetch live prices)
- Node monitor (ping DePIN nodes, show uptime)
- Task list (sync with open tasks)
- Daily briefing widget

## Structure

Single `index.html` — no build step, no dependencies. Keep it that way unless a module genuinely needs JS frameworks.
