# Startup Bible

Startup Bible helps founders decide what to test or build from customer conversations, public research, and their own hypotheses. It works as a project skill in Codex, Cursor, and Claude Code. Pasted notes are enough to get started.

## Install

Run this from the project where you want to use Startup Bible.

```sh
npx skills add samikd35/Startup-Bible --skill startup-bible
```

The Skills CLI requires Node.js 22.20 or later. Choose Codex, Cursor, or Claude Code when prompted. To select one directly, append `--agent codex`, `--agent cursor`, or `--agent claude-code`. Update a project installation with `npx skills update --project startup-bible`.

## Try it

Start a new chat in the project and select `startup-bible` or ask for it by name. Paste your notes after this prompt.

> Use Startup Bible to draft a pilot proposal from the notes below. If one unresolved decision would change the scope, ask me that question.

To try it with sample notes, paste the [Ready to draft conversation](skills/startup-bible/references/pilot-conversations.md#ready-to-draft).

## What it does

| You bring | Startup Bible helps you |
| --- | --- |
| A conversation with a clear problem, success measure, and customer commitment | Draft a pilot with scope, responsibilities, measurement, and open terms. |
| Discovery notes with an unresolved goal | Ask the one question that changes the pilot and draft the parts you can already use. |
| Public research or a founder hypothesis | Choose a small validation step you can start with public sources or your own materials. |

For a roadmap recommendation, the skill looks for a recurring problem in the target market and a gap that a simpler approach leaves open. When specialist help would improve the result, it looks for an available skill by capability. The product owner approves build work, and the customer sponsor approves what their team commits to.

## Manual installation

Copy the entire [skill folder](skills/startup-bible/) into your project at the destination for your client.

| Client | Destination from the project root |
| --- | --- |
| Codex or Cursor | `.agents/skills/startup-bible/` |
| Claude Code | `.claude/skills/startup-bible/` |

## Optional project features

Each project can opt in separately to a journal, background guidance in its chat, and weekly skill reviews. Reviews propose evidence-backed edits for maintainer approval. [Project options and setup](skills/startup-bible/references/project-options.md)

## Behavior checks

Use the bundled prompts to compare two skill versions. They cover a ready pilot, an unresolved goal, pasted public research, a quiet checkpoint, and the opt-in settings. [Run the behavior checks](skills/startup-bible/references/behavior-checks.md)
