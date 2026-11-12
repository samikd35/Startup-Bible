# Startup Bible

Startup Bible helps founders decide what to test or build from customer conversations, public research, and their own hypotheses. It works as a project skill in Codex, Cursor, and Claude Code. Pasted notes are enough to get started.

| You bring | Startup Bible helps you |
| --- | --- |
| A conversation with a clear problem, success measure, and customer commitment | Draft a pilot with scope, responsibilities, measurement, and open terms. |
| Discovery notes with an unresolved goal | Ask the one question that changes the pilot and draft the parts you can already use. |
| Public research or a founder hypothesis | Choose a small validation step you can start with public sources or your own materials. |

For a roadmap recommendation, the skill looks for a recurring problem in the target market and a gap that a simpler approach leaves open. When specialist help would improve the result, it looks for an available skill by capability. The product owner approves build work, and the customer sponsor approves what their team commits to.

## Quick start

1. Clone the repository.

   ```sh
   git clone https://github.com/samikd35/Startup-Bible.git
   cd Startup-Bible
   ```

2. Open the project in Codex, Cursor, or Claude Code. Select the `startup-bible` skill in a new chat or ask for it by name.
3. Try this prompt or paste your own notes.

   > Use Startup Bible to draft a pilot proposal from the “Ready to draft” example in `examples/pilot-conversations.md`.

## Use it in another project

Copy the [canonical `startup-bible` folder](.agents/skills/startup-bible/) into your project at the path for your client.

| Client | Destination from the project root |
| --- | --- |
| Codex or Cursor | `.agents/skills/startup-bible/` |
| Claude Code | `.claude/skills/startup-bible/` |

This repository includes a Claude Code entry point that loads the shared skill. For another project, copy the canonical folder into the destination above.

## Optional project features

Enable each feature separately for the project where you want it.

### Project journal

Ask Startup Bible to log a run or enable logging in your project instructions. `startup/runs.md` records evidence, recommendations, and outcomes. `startup/decisions.md` records accepted choices and their rationale. This repository ignores `startup/` so the journal stays local.

### Background guidance

Add this instruction to the project instructions your client loads.

> Enable Startup Bible background guidance for this project. Before finishing a turn where I paste new discovery notes or ask you to read a discovery source, load the Startup Bible skill and run its checkpoint in this chat.

Guidance appears in the same chat when new evidence could change what to test or build, or when a missing decision blocks the next step. To pause it, replace the instruction with “Pause Startup Bible background guidance for this project.”

### Weekly skill reviews

Where your client supports scheduling, create a weekly review and give it access to the project skill and the journal you want reviewed. You can also request a review on demand. When the evidence supports a change, the review presents the proposed edit and comparison results for maintainer approval.

## Behavior checks

Use the same prompts to compare two skill versions. The checks cover a ready pilot, an unresolved goal, pasted public research, a quiet checkpoint, and the opt-in settings. [Run the behavior checks](examples/skill-checks.md)
