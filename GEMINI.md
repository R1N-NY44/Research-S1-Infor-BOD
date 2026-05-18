# Vault Structure & Conventions

## Folder Organization

| Folder | Purpose | Naming Convention |
| :--- | :--- | :--- |
| **00 Inbox** | Catch-all for raw ideas, screenshots, and fleeting notes. | `Fleeting - Topic` |
| **10 Journal** | Daily logs, stand-up notes, and periodic reviews. | `YYYY-MM-DD` |
| **20 Projects** | Active engineering tasks with a defined "Done" state. | `Project Name` |
| **30 Knowledge** | The "Second Brain." Atomic technical notes and concepts. | `Topic or Concept` |
| **40 Archive** | Cold storage for finished projects and outdated info. | `Project Name (YYYY)` |
| **Templates** | Blueprints for daily notes and project scaffolding. | `Type Template` |

## Principles
- **Minimalism**: Don't over-categorize. Use tags for cross-cutting concerns.
- **Action-Oriented**: Focus on what is active now in `20 Projects`.
- **Atomic Notes**: In `30 Knowledge`, keep notes focused on a single concept.
- **Flat over Deep**: Prioritize linking (`[[Note]]`) over nesting folders.

## Developer Workflow
1. **Capture**: Quick drop in `00 Inbox` or Daily Note.
2. **Process**: Weekly review to move items to `20 Projects` or `30 Knowledge`.
3. **Retrieve**: Use Quick Switcher (`Ctrl+O`) and internal links.
