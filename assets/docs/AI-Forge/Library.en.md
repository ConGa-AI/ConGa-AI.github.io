# Library

Public guide: [GitHub · Library](https://github.com/ConGa-AI/AI-Forge/blob/main/docs/en/library.md)

The sidebar label is **Data library**.

![Library](/assets/ai-forge/library.png)

After files are in a dataset, launched assistants can search them. Pick a dataset on the left; files appear as a list.

If you are not connected, the service key has not passed vectorizing checks, or the vector database is not ready, the page lists the missing steps and lets you jump there.

## Create a dataset

1. Type a name under **New dataset**, e.g. `product-docs`.
2. Click **Create**.

Size comes from the vectorizing service on the channel. There is no field to edit. If the service behind the key changes later, create a new dataset. The red **Delete** button removes the whole dataset.

## Import files

1. Pick the dataset.
2. Click the **Add files** area (**Choose files**).
3. Click **Start import**.

The stages are **Reading** → **Reading figures** → **Vectorizing** → **Writing**. You can pick several files at once. If one file fails, others may still succeed.

## Inspect and delete a document

![Document contents](/assets/ai-forge/library-view.png)

Click a row to open **Document contents**. Search passages, then read **Searchable text**. **Original** appears only when it differs from the searchable text. Some formats cannot be previewed; the app shows a location instead.

**Delete document** removes every passage of that file from the dataset.

## Using it with an assistant

Enable **Local library** on [MCP](/docs/AI-Forge/MCP), apply, then launch from [Agents](/docs/AI-Forge/Agents) and ask in ordinary language.
