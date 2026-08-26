# Connection

Public guide: [GitHub · Connection](https://github.com/ConGa-AI/AI-Forge/blob/main/docs/en/connection.md)

![Connection](/assets/ai-forge/connection.png)

Three parts: **Identity → Connect → Key**. The step row on the page shows which parts are done. Finish them in order. Connection and authorization happen on this screen.

## Username

Enter the name your admin assigned, then **Save**. That is this computer’s identity on the channel.

## Authorize

![Authorize](/assets/ai-forge/authorize.png)

**Authorize** shows this computer’s authorization key. Click **Copy key**. Do not select the shortened text on screen. Send the full line to an admin, then **Connect**.

## Connect button

| Status | What to do |
|---|---|
| Disconnected | Save the name, finish authorization, then connect |
| Connecting / reconnecting | Wait; it retries on a flaky network |
| Connected | You can paste the service key |
| Unauthorized | Ask the admin to allow this computer |
| Remote unreachable | Check the network, then Retry |
| Server verification failed | Contact an admin; do not ignore this |

**Disconnect** if you need to leave for a while.

## Service key

You can verify only after connect succeeds. Paste the key, then **Save & verify**. The page shows whether **Answering** and **Vectorizing** work, and **Vector width** used on import (you do not type that).

Paste it only here. The window passes it into assistants it launches.

If a key is already stored, use **Verify again**.
