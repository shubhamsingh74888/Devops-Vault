# Contributing to DevOps Vault

Everyone can contribute. The owner reviews changes to keep the structure, quality and conventions consistent.

## Setup
1. Clone the repo and open the folder in Obsidian ("Open folder as vault"), or edit the Markdown files in any editor.
2. Do not commit personal Obsidian files (workspace.json, cache). .gitignore already covers them.

## How to contribute
1. Create a branch: git checkout -b docs/short-description
2. Add or edit notes in the right folder.
3. Start new notes from templates/note-template.md.
4. Commit and push, then open a pull request.
5. The owner reviews and merges. Never commit directly to main.

## Conventions
- Folders are numbered by area (10-Cloud, 20-Kubernetes, ...). Old material goes to 90-Archive.
- Images and attachments go in 95-Assets.
- Use normal Markdown links so notes also read well on GitHub.
- File names: short, descriptive, no special characters.
- Never include secrets, passwords or tokens.
