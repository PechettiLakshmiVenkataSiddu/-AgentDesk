# AgentDesk

This repository is the source used to recreate the same project in a new empty repository named `agentdesk`.

## Rebuild in a new empty `agentdesk` repo

1. Create an empty repository named `agentdesk`.
2. Clone it locally.
3. Copy this project content into that clone.
4. Commit and push.

Example:

```bash
git clone <your-new-agentdesk-repo-url> agentdesk
rsync -av --exclude ".git" /path/to/-AgentDesk/ agentdesk/
cd agentdesk
git add .
git commit -m "Initialize AgentDesk project"
git push origin main
```
