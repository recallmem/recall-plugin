# Recall plugins and integrations

Long-term memory for AI agents from [Recall](https://recallmem.dev): it learns what is true about each
person from their conversations, notices when that changes, and answers with sources.

| Agent | Where | Install |
|---|---|---|
| Claude Code | [`plugins/recall-memory`](plugins/recall-memory) | `/plugin marketplace add RedSix6/recall-plugin`, then `/plugin install recall-memory@recall` |
| Codex | [`integrations/codex`](integrations/codex) | `codex plugin marketplace add RedSix6/recall-plugin`, then `codex plugin add recall-memory@recall` |
| OpenClaw | [`integrations/openclaw`](integrations/openclaw) | see its README |
| Hermes | [`integrations/hermes`](integrations/hermes) | see its README |
| Any agent with skills | [`integrations/agent-skill`](integrations/agent-skill) | see its README |

Each folder's README covers setup, settings and troubleshooting. The Claude Code plugin asks for your Recall
API key when you enable it and keeps it in your system's secure credential store. Create a key at
https://app.recallmem.dev/keys; new accounts get $5 of free credit.

Docs: https://recallmem.dev/docs · Self-hosting: https://recallmem.dev/docs#self-host ·
Licence: MIT ([LICENSE](LICENSE)).
