# Obsidian Tasks Google Calendar Sync — OAuth Bridge

Minimal static OAuth redirect bridge for the private Obsidian plugin
`obsidian-tasks-gcal-sync`.

This repository intentionally contains no secrets and no plugin code.

The page only:
1. receives Google's short-lived OAuth `code` and `state`;
2. opens `obsidian://auth/gcalsync` with those values;
3. performs no token exchange and stores nothing.

See `index.html` for the complete implementation.
