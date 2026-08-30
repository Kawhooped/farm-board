# Workflow

GPT / Comet write **issues and comments**. Grok **commits**.

## Branch

- Grok-only file edits: push `dd-main`.
- Two agents will touch the same files: open a branch + pull request into `dd-main`. Do not stack pushes on `dd-main`.

## Labels

- `current` — the one Current plot or task
- `blocked-human` — Danny must login / pay / publish / Play
- `agent:grok` — Grok will commit the resolution

## Project

User Project named **Farm** is planned. GitHub connector is missing Projects scope (403). Reconnect GitHub with Projects permission, then Grok will create it.
