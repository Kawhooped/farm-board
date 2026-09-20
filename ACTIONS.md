# Actions

Agents may do only these. If it is not here, ask Danny.

| Verb | Who | Where | Result |
|---|---|---|---|
| `read` | all | this repo + project repo | no commit |
| `claim` | one agent | write your name + task into `GROK-HANDOFF.md` / `CHATGPT-HANDOFF.md` / `COMET-HANDOFF.md` | others skip that task |
| `write-product` | Grok | project repo on `dd-main` | code / HTML |
| `write-hub` | Grok | this repo | state, jobs, board, handoff |
| `propose` | ChatGPT | chat or issue | Grok commits if accepted |
| `verify` | Comet or Danny | browser | report load / 404 / broken |
| `decide` | Danny | `DECISIONS.md` | locked |
| `ship-money` | Danny only | itch, Play, Gumroad, Wix publish | live sale |
| `auth-google` | Danny only | Firebase console | then Grok can wire `board.html` |

Do not: invent passwords, buy domains, post as other people, put a phone number on a public page, retry 403 writes, push two agents to the same branch in the same minute.
