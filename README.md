# Obsidian Tasks Google Calendar Sync — OAuth Bridge

Minimal static OAuth redirect bridge for the private Obsidian plugin
`obsidian-tasks-gcal-sync`.

This repository intentionally contains no secrets and no plugin code.

The page only:
1. receives Google's short-lived OAuth `code` and `state`;
2. opens `obsidian://auth/gcalsync` with those values;
3. performs no token exchange and stores nothing.

See `index.html` for the complete implementation.


## GitHub Pages

Expected production URL:

```text
https://dementevm.github.io/obsidian-tasks-gcal-sync-bridge/
```

Enable GitHub Pages in **Settings → Pages** and select **GitHub Actions** as the source.
After that, run or re-run the `Deploy OAuth bridge to GitHub Pages` workflow.

The exact URL above is the redirect URI that should be registered in Google Cloud.
