# AI Forge user guide

The same product guide is also on GitHub:  
[GitHub · English guide](https://github.com/ConGa-AI/AI-Forge/blob/main/docs/en/README.md)

Download:  
[Latest release](https://github.com/ConGa-AI/AI-Forge/releases/latest)

![Status](/assets/ai-forge/status.png)

## What this document is for

AI Forge is a desktop window. It connects this computer to the channel, launches assistants, can store local files in a searchable library, and can write local tools into assistant settings.

Connection, authorization, and assistant install all happen in the app. These pages match the screens and screenshots. Follow the window.

## Terms

| Term | Meaning |
|---|---|
| **Channel** | The private connection from this computer to the service. Status shows it as **Channel**. |
| **Authorization key** | Proves **this computer** may use the channel. Created under Connection → **Authorize**. Use **Copy key** and send the full line to an admin. |
| **Service key** | Proves **you** may use answering and vectorizing. Issued by an admin. Paste it only on Connection. |
| **Answering** | Questions, answers, writing code. Status: **Answering**. Connection: **Answering**. |
| **Vectorizing** | Turns files into searchable meaning, not just keyword match. Status: **Vectorizing**. Connection: **Vectorizing**, plus **Vector width**. |
| **Vector database** | A private store on **this computer**. Badge: **Vectors**. Readiness: **Database**. Data setup card: **Vector database**. |
| **Dataset** | A named box. Pick one on Data library, then import. |
| **Agent** | The assistant that edits your project. It opens in a **new window** in the folder you chose. The six labels are OpenCode, Claude Code, Codex, Grok Build, Hermes Agent, and Pi. |
| **Recent projects** | At most 10 shortcuts. Click to launch. They do not show in-progress work and do not close that window. |
| **MCP** | Tools written into assistants at launch: **Local library**, optional **Browser control**, and channel services this key may use. |

Do not mix the two keys. Always use **Copy key**; do not select the shortened line on screen.

## Reading order

1. [Install and download](/docs/AI-Forge/Install)
2. [First-time setup](/docs/AI-Forge/FirstRun)
3. [Status](/docs/AI-Forge/Status)
4. [Connection](/docs/AI-Forge/Connection)
5. [Agents](/docs/AI-Forge/Agents)
6. [MCP](/docs/AI-Forge/MCP)
7. [Data setup](/docs/AI-Forge/Data)
8. [Library](/docs/AI-Forge/Library)
9. [FAQ](/docs/AI-Forge/FAQ)

## Four steps are enough the first time

1. Save the username. Copy the authorization key to an admin.
2. After connect succeeds, paste and verify the service key.
3. (Recommended) Install the local vector database.
4. Pick an agent, add a project folder, click to launch.

After the key works, open MCP for the local library or browser control. Keys `1`–`6` switch the six sidebar screens.
