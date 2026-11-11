# kobonow.com

Static one-page site. Every commit to `main` auto-deploys to https://kobonow.com (Vercel project kobo-deploy).

## How to update (for Claude)

1. Edit `index.html` (all text, CSS and JS is in this one file).
2. Commit to `main` with a short message.
3. Wait about 1 minute, then check https://kobonow.com.

## Rules

- Keep `vercel.json` and `favicon.svg` as they are.
- Do not add secrets or API keys (the repo is public).
- To undo: revert the last commit, or ask Fahad to promote an older deployment in Vercel.
