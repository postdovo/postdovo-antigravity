# PostDovo for Antigravity

Lets your agent work with your [PostDovo](https://postdovo.com) account: see your connected social accounts and posts, write posts and save them as drafts, schedule them, and publish them after the agent has shown you exactly what will go out and where.

This plugin holds no password, token or key. It only tells Antigravity where PostDovo's server is (`https://app.postdovo.com/mcp`). The first time it connects, a browser window opens: sign in to PostDovo and approve what the agent may do.

## Install

```bash
agy plugin install https://github.com/postdovo/postdovo-antigravity
```

Then ask: "Which social accounts do I have connected in PostDovo?"

## Good to know

- You need a PostDovo account with at least one social account connected inside PostDovo. The plugin cannot connect new ones.
- Publishing always shows a preview first and waits for your confirmation. A published post cannot be changed or taken back through the plugin.
- You can switch drafts, scheduling and publishing off, or disconnect, at any time in PostDovo on the Ai Agents page.

## Updates

Each release raises `version` in `plugin.json`.
