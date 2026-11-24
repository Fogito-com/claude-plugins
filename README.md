# Fogito plugins for Claude

The official **Fogito** plugin for Claude. It connects Claude to your Fogito account so you can find and work with your tasks, projects, people, notes, Drive files and other Fogito services in plain language.

## Install in Claude Code

```
/plugin marketplace add Fogito-com/claude-plugins
/plugin install fogito@fogito
```

Then run `/mcp`, select **fogito** and sign in with your Fogito account.

## Use it in claude.ai, Claude Desktop or mobile

Add a custom connector under **Settings → Connectors** with this URL:

```
https://app.fogito.com/api/mcp/claude
```

## What you get

- **Fogito connector** at `https://app.fogito.com/api/mcp/claude`. You sign in on Fogito's own page and choose which services Claude may use.
- **`fogito` skill**: guidance that helps Claude pick the right Fogito tools and handle confirmations correctly.

## Privacy and safety

- The plugin contains no credentials. Sign-in, service switches and consent happen on the Fogito sign-in page; Claude never sees your password.
- Claude only gets the services you switch on, and Fogito's own permissions still decide what you can see.
- Any change to your data needs a real click on a **Confirm** card. Claude can't confirm on your behalf.
- You can disconnect at any time from Claude's connector settings.

## Support

https://fogito.com
