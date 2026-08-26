# Data setup

Public guide: [GitHub · Data setup](https://github.com/ConGa-AI/AI-Forge/blob/main/docs/en/data.md)

![Data setup](/assets/ai-forge/data.png)

This screen covers two things: the **Vector database** on this computer, and **which file types** it can read.

Terms: [Overview · Terms](/docs/AI-Forge/Overview#terms).

## Vector database

Turns files into searchable private data that stays on this computer.

| Status | What you can do |
|---|---|
| Not installed | Click **Install & start** |
| Installing / starting | Wait |
| Ready | Create datasets on [Library](/docs/AI-Forge/Library) |
| Stopped | Click Install & start again |
| Failed | Retry; if it still fails, quit the app and try again |

If you skip install, assistants still launch, but you cannot import files.

The trash control is **Remove**. The confirmation says the install **and every dataset on this computer** will be deleted.

## Format modules

Turn on only the types you will import. Built-in **Text & Markdown** cannot be turned off (**Built in**).

| Module | Extensions shown |
|---|---|
| Text & Markdown | `.txt`, `.md`, `.markdown`, `.rst`, `.log` |
| Code & config | Common source and config |
| Tables | `.csv`, `.tsv` |
| PDF documents | `.pdf` |
| Office documents | `.docx`, `.pptx`, `.xlsx` |
| PCB layer files | `.gbr`, `.gtl`, … |
