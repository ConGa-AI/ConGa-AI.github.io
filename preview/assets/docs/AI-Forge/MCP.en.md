# MCP

Public guide: [GitHub · MCP](https://github.com/ConGa-AI/AI-Forge/blob/main/docs/en/mcp.md)

![MCP](/assets/ai-forge/mcp.png)

This screen detects MCP servers this key can use on the channel, then writes local tools and channel servers into agent configs. Finish [Connection](/docs/AI-Forge/Connection) first, including a saved service key.

## Buttons

| Button | What it does |
|---|---|
| **Detect again** | Ask the channel for the current list |
| **Apply to agents** | Write enabled items into assistant config files. The **next launch** picks them up |

## Local library

Tagged **Local**. Search documents imported on this computer. Assistants can use it after the vector database is ready and files exist in [Library](/docs/AI-Forge/Library).

## Optional local tools: Browser control

On screen: **Browser control**, product line **Browser Use MCP**, badge **Optional**.

1. Click **Download and install** if it says **Not downloaded**.
2. When it says **Downloaded — ready to enable**, turn the switch on.
3. Click **Apply to agents**.
4. Launch the assistant again. It can open a local browser, walk through pages, and read what is on screen.

The trash control is **Remove**: it deletes this tool’s install files only. Node.js 22 or newer may be required.

## Channel services

After the key is verified, servers allowed for this key appear here, tagged **Channel**. Items you cannot use show **Key not allowed**. The list depends on your administrator.
