# PT Admin

PT Admin is the administrative skill set within **PT Workspace**. PT Video Editing (including PT Connect) is maintained in its own repository. Existing 0.2.x archives retain their historical folder and skill names for compatibility.

**More coaching. Less catching up.**

A local AI workflow for personal trainers: review client records, prepare follow-up drafts, and keep your progress between conversations.

[See the website](https://pt-workspace.vercel.app/) · [Download the preview](https://github.com/goolen988/pt-admin/releases/download/v0.2.1-preview/pt-workspace-public-v0.2.1-preview.zip) · [All releases](https://github.com/goolen988/pt-admin/releases)

## Start in your AI app

Paste this into a desktop AI session with local file access:

> Help me set up PT Admin. Read https://raw.githubusercontent.com/goolen988/pt-admin/main/START.md and walk me through my first task.

Your agent checks the environment, asks where to keep your workspace, retrieves the package and guides setup. You do not need to write code or use a terminal. Downloading the package yourself is optional.

## Current preview: v0.2.1

This first public preview packages the existing **PT Workspace Pack v0.2.1** runtime. Its local skill is called `pt-workspace`. Onboarding completion is persisted by the runtime. Return to the saved PT Workspace project for future chats; installation is project-scoped.

Included: a fictional example, explicit CSV/JSON input mapping, weekly client review, unsent follow-up drafts, local HTML reports and saved task state. Python 3.9+ and local script/file access are required. Mac with Codex local is the reference route; other hosts need a capability check.

**Kahunas Computer Use and training/nutrition-plan analysis are not included in this preview.** They are the next pilot workflow. The website's named client cards are fictional illustrations, not results from a Kahunas integration.

## Versions and your data

Each release has a versioned archive and SHA-256 checksum. Download the attached package rather than GitHub's automatically generated “Source code” ZIP, which contains only this distribution repository.

Keep your working folder between sessions. Never extract a new package over an existing client workspace. Public-channel automatic upgrades are not implemented in v0.2; its legacy updater targets the original private repository. Do not enable it or submit GitHub feedback through it during this preview. Later releases must provide a tested migration path that preserves your data.

No client records or credentials belong in this public repository or its issues. The package includes fictional examples only. Local storage does not mean the AI model processes everything offline; use only an environment and data your business permits.
