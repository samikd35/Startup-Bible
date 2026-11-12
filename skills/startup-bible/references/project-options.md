# Project options

Paths under `startup/` are relative to the project using Startup Bible. Enable each optional feature separately.

## Project records

When the user asks to log the run or the project has enabled logging, append a dated note to `startup/runs.md`. Record the trigger, skill revision when known, evidence and output links, what supported or weakened the proposal, the proposed action, and any correction or outcome. For pasted notes without a link, keep a brief attributed summary. Keep source notes where they live. When logging is enabled or requested, record accepted choices in `startup/decisions.md` with the approver, rationale, and what would prompt a revisit. Use existing project records when equivalent.

## Opt-in background guidance

To enable the checkpoint, add this instruction to the project instructions your agent reads.

> Enable Startup Bible background guidance for this project. Before finishing a turn where I paste new discovery notes or ask you to read a discovery source, load the Startup Bible skill and run its checkpoint in this chat.

To pause it, replace that instruction with “Pause Startup Bible background guidance for this project.”

Check once before finishing a turn where the user pastes new discovery notes or asks you to read a discovery source. Run this checkpoint only when the project has explicitly enabled it and it is active. Direct invocation of the discovery workflow is always available.

Surface guidance only if the new evidence could change what to test or build, or a missing decision blocks the next step. If the turn already addresses the decision or the evidence adds nothing material, add no guidance. In the same project chat, show the trigger, link or attribute the evidence, and give one suggested next step or one focused question.

Opting in covers reading selected sources and giving advice. Get the user's approval before acting on a suggestion to change an agreed pilot scope or roadmap, start build work, contact a customer, or connect another private source. If logging is enabled, record the suggestion as pending.

## Skill reviews

Run on demand when asked. Run on a weekly cadence only for projects that have separately opted in to a schedule. Where your client supports scheduling, use its scheduling controls to give the run access to the project skill and the journal you want reviewed.

1. **Find evidence for an edit.** Check runs, corrections, and outcomes added or updated since the previous review. Look for a recurring correction, an outcome that exposes a weakness, or one consequential failure you can reproduce. Use targeted public research when it bears on a specific change. Stay quiet in a scheduled review when the evidence warrants no proposal.
2. **Compare versions.** Draft the exact edit and test it alongside the current instructions on the same inputs with pass criteria set first. Replay the issue and check a ready pilot, an unresolved pilot goal, pasted public research, and a checkpoint that should stay quiet. Verify client-specific changes in the affected client. Report per-version results and mark any checks you could not run as unverified.
3. **Present the proposal for approval.** Give the evidence, proposed edit, and test results to the skill maintainer, normally the project owner or a named delegate. Apply or publish the change with the maintainer's approval for that action. In an enabled or requested project journal, record the review decision and rationale and link the revision once applied.
