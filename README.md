# My Gym Log

A cute, phone-first workout logger. It knows what day it is, walks through
that day's split one exercise at a time (pre-filled with current baselines),
flags PRs on the spot, and produces a paste-ready summary for chat.

## Files

- `index.html` — the whole app (no build step, no backend)
- `mascot.webp` — the kawaii dumbbell mascot

## Hosting (GitHub Pages, free)

1. Push these files to the repo's main branch.
2. Repo Settings → Pages → Source: Deploy from a branch → Branch: main, folder: / (root).
3. The site goes live at `https://<username>.github.io/<repo>/`.

## Notes

- History is stored in the browser's localStorage on the phone.
- Baselines live in the `SPLIT` object at the top of the script in `index.html`;
  update them there whenever a PR sticks.
