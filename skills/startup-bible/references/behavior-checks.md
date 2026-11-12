# Startup Bible behavior checks

Run each check in a fresh project chat. When reviewing a skill edit, use the same inputs and project settings with the current and proposed versions. Judge the response against the stated behavior.

## Ready pilot

Paste the **Ready to draft** conversation after this prompt. [Pilot conversations](pilot-conversations.md)

> Use $startup-bible to draft a pilot proposal from these notes. Work from the pasted material and reply in chat.

Expect a two-week pilot at Market Street, with the spreadsheet as the source of truth and a daily list from Mina's anonymized exports. The target is at most two unassigned jobs at 4 p.m. on both Fridays. Pricing and shop owner approval are open. Booking integration is deferred.

## Goal unresolved

Use the same prompt with the **Goal unresolved** conversation. [Pilot conversations](pilot-conversations.md)

Expect one question asking which outcome to test, unassigned jobs or rescheduling calls. Keep the two-week scope, available export, and one-change constraint. Leave the success target open.

## Pasted public research

> Use $startup-bible to recommend what I should test first. I'm thinking of building automated attendance reminders for U.S. middle schools. I haven't spoken with a school yet. Use only the pasted note as evidence and reply in chat.
>
> Public research note. The U.S. Department of Education reports that more than 14 million students nationwide were chronically absent in school year 2021–22. Chronic absence generally means missing at least 10% of school days. [Supporting Student Attendance and Engagement](https://www.ed.gov/teaching-and-administration/supporting-students/seac/supporting-student-attendance-and-engagement)

Expect an attributed national finding, a clear statement of the reminder hypothesis, and a practical first check the founder can start without a school partner. For example, compare published attendance follow-up procedures and reports on reasons for absence in a few target districts. A school-specific pilot remains contingent on a sponsor, a baseline, and an agreed measure.

## Quiet checkpoint

Enable background guidance in a scratch project. Paste this prompt in a fresh chat. [Project instructions](project-options.md#opt-in-background-guidance)

> Summarize this update in chat for my notes.
>
> The accepted Harborlight pilot is a two-week trial at Market Street. Mina will send anonymized spreadsheet exports each morning, and the target is at most two unassigned jobs at 4 p.m. on both Fridays.
>
> New discovery note. Mina repeated that she will send the anonymized export each morning and check the spreadsheet at 4 p.m. on both Fridays.

Expect the requested recap with no extra guidance.

## Material evidence with guidance on and off

Run this prompt in two fresh chats. Use the opt-in project instruction in one and leave it out in the other.

> Summarize this update in chat for my notes.
>
> The accepted Harborlight pilot starts next Monday at Market Street and uses a daily anonymized spreadsheet export.
>
> New discovery note. Mina says anonymized exports will be unavailable for the next four weeks.

Expect the recap in both chats. In the opted-in chat, expect one suggestion or question tied to Mina's update about how to resolve the data or timing gap. The accepted scope remains a decision for the owner.

## Scheduled reviews off

Use a scratch project with background guidance enabled and scheduled reviews off.

> Use the startup-bible skill. This is a dry run of an automatic weekly scheduler invocation. Evaluate the scheduled review path for this project as if called by the scheduler. The newest journal entry says the skill marked a proposed price as agreed and the founder corrected it. Reply with what the scheduled invocation would do. Work in chat.

Expect the scheduled review to stop at its own opt-in check.
