# First-time setup

Public guide: [GitHub · First-time setup](https://github.com/ConGa-AI/AI-Forge/blob/main/docs/en/first-run.md)

Follow the sidebar: Connection → Agents.  
[Status](/docs/AI-Forge/Status) tells you the next step. Connection and authorization happen in the window. Data setup and MCP can wait until the key works.

## 1. Save the username

1. Open **Connection**.
2. Enter the username your admin gave you.
3. Click **Save**.

A wrong name makes connect fail later.

## 2. Authorize this computer

![Authorize](/assets/ai-forge/authorize.png)

1. Click **Authorize**.
2. Click **Copy key** (the full line; do not select the shortened text on screen).
3. Send that line to an admin.
4. Come back after they finish.

**Done when:** the admin says this computer is allowed.

## 3. Connect and paste the service key

![Connection](/assets/ai-forge/connection.png)

Click **Connect**. Wait until the status is **Connected**.

1. Paste the **service key** from your admin (not the authorization key).
2. Click **Save & verify**.

When it works, **Answering** and **Vectorizing** both show **Available**, and **Vector width** is filled in. The key is passed into assistants you launch later. If a key is already stored, use **Verify again**.

**Unauthorized** means the admin has not allowed this computer, or you did not copy the full authorization key. **Remote unreachable** means check the network, then **Retry**.

**Done when:** the channel is up, and both answering and vectorizing are available.

## 4. Install the local vector database (recommended)

A prompt may appear the first time: **Install a local vector database?** Choose **Install**, or **Later** / **Never**. You can still click **Install & start** on [Data setup](/docs/AI-Forge/Data).

If you skip, assistants still launch, but you cannot create datasets or import files.

## 5. Launch the first assistant

Open **Agents**, pick an assistant, click **Add folder**, then click the folder name or **Launch**. Details: [Agents](/docs/AI-Forge/Agents).

## 6. (Optional) MCP

After the key works, open [MCP](/docs/AI-Forge/MCP). Turn on **Local library**. To let an assistant open a local browser, download **Browser control**, enable it, then **Apply to agents**. The next launch picks it up.
