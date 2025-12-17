# Evergreen Checklist (Frozen Static)

This repo is intentionally **frozen**.

## What must always remain true

- CSS/JS files are **content-hashed**
- Static assets use **immutable caching**
- HTML is **revalidated** (not immutable)
- No Node/tooling dependencies are introduced

## If you ever redeploy / migrate hosting

1. Confirm hashed assets are requested (no plain `style.css` / `main.js`)
2. Confirm asset response header:
   - `Cache-Control: public, max-age=31536000, immutable`
3. Confirm HTML response header:
   - `Cache-Control: no-cache, must-revalidate`
4. Confirm there are **no 404s** in Network tab
5. Confirm HTTPS + HSTS are enabled

## Changes policy

- JS/CSS changes: **Not allowed**
- Any functional change: create a new repo or a versioned successor.
