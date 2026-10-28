# OnStage for Gemini CLI

Connect [OnStage](https://getonstage.app) to Gemini CLI and ask about your team in plain language: who is serving this Sunday, which songs you used most this year, or plan next month's events.

## Install

```bash
gemini extensions install https://github.com/OnStageApp/onstage-gemini-extension
```

Start Gemini CLI, run `/mcp auth onstage`, sign in to OnStage, pick your team and approve access.

Only team owners and admins can connect. The assistant acts as you, with your permissions in OnStage.

Full guide and the list of what the assistant can do: https://web.getonstage.app/connect-ai

## Disconnect

```bash
gemini extensions uninstall onstage
```

To have a connection revoked on our side, write to contact@getonstage.app.
