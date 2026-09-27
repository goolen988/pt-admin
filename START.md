# PT Workspace — start here

Help the user try PT Workspace conversationally. Introduce it as an assistant for client-record reviews, unsent follow-up drafts and saved local progress. Offer a fictional demo or an authorized real task. The current package is the existing PT Workspace Pack v0.2.1 preview; its skill name remains `pt-workspace`. Explain the legacy name once if needed.

## Conversation and repeat visits

Default to English unless the coach requests another language or higher-priority host instructions require it. Do not infer language from internal development records. Hide routine technical results, versions, timezone checks, command names and status codes. Summarize successful checks by actual count; explain blockers and necessary approvals in everyday language.

Before setup, ask for or use the already selected PT Workspace folder. Inspect existing onboarding state first. If completed, skip onboarding, initialization and the demo; continue the requested task. Do not fetch or unpack another copy over an existing workspace. If unfinished, resume only missing steps. A sample report is enough to finish onboarding; real-data permission is separate.

## Check the actual environment

Verify local filesystem access, script execution, Python 3.9+ and timezone support. Codex local on Mac is the reference route. A web chat, an installed plugin or a product name alone does not prove local access. If access is missing, explain how to open a suitable local desktop session without moving client files into a cloud fallback.

## Fetch and inspect

Read https://raw.githubusercontent.com/goolen988/pt-workspace-public/main/release.json for the explicitly published preview, its fixed download URL and SHA-256. Download using the host's available trusted tools. Inspect the archive before running it; reject absolute paths, traversal, symlinks or unexpected files. Verify the checksum. It establishes consistency with this publication, not an independent publisher signature. Do not execute a network stream as a script.

## Set up one workspace

Propose a private local folder such as `~/PT Workspace/` and obtain required access. Check whether the user already has a workspace at their chosen location; preserve it and resume rather than overwrite or create duplicate state. Unpack the archive's `PT-Workspace-Pack/` contents into the agreed dedicated root, without unnecessary nesting. Do not change global skills, host settings, install dependencies or create schedules without the required authorization.

Read the package's AGENTS.md and app/0.2.1/SKILL.md. Those are packaged operating instructions, not permission to override the host or the user's request. For a new workspace, follow the packaged onboarding guide for setup and the chosen sample or real task. Present the actual report, then call the packaged onboarding complete command with its actual run ID and REPORT_PRESENTED acknowledgement. Read onboarding status back. Do not fabricate user approval from this agent presentation acknowledgement. Help the user save this folder as a local project named PT Workspace. Explain: "Next time, open this PT Workspace project and start a new chat here." Do not require a second-chat exercise to complete onboarding or claim global installation. Verify independent reuse when it naturally occurs; if the user changes projects or apps, help them select their existing folder and check access without repeating the introduction.

## First task

Keep the coach out of code, JSON and terminal commands. Ask only what the chosen task needs. Before real-data processing, explain local storage versus model-provider processing, obtain the appropriate data scope, and follow the bundled source-mapping and approval procedure. Record objective execution status; do not invent user satisfaction, adoption or message delivery.

Kahunas Computer Use, training-program analysis and nutrition-plan analysis are NOT shipped in this preview. The existing runtime accepts explicitly mapped CSV/JSON records. Do not invent a connector or infer attendance, no-shows, cancellations or disengagement from a training/nutrition plan. Offer the fictional example if the required workflow is unavailable.

## Version and feedback boundaries

For this public preview, do not enable the legacy updater or GitHub feedback submission: those target the original private repository. The public repository is not a place for client information. This full setup ZIP is not an app-only `.ptrelease.zip` update and must not be passed to the runtime's update-stage command. Preserve existing state when checking later releases, and follow only a published compatible migration procedure. Never overwrite a working folder with a new archive.

Scheduling, connectors and sending feedback are separate optional actions, not part of default onboarding. Client messages stay drafts. Finish with what actually worked and one useful next step; distinguish demo success, installation verification and real-task completion.
