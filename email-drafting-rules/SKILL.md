---
name: "email-drafting-rules"
description: "Use whenever drafting, rewriting, or replying to any email on the user's behalf: enforces a humanized, concise, professional, fact-verified style with a final cross-check before delivery."
---

# Email drafting rules

These are standing rules for every email written on the user's behalf. They apply to new emails, replies, follow-ups, and rewrites, whether or not the user repeats them.

## Style

Every email must be:

- **Humanized**: it reads like a real person wrote it. Natural phrasing, no robotic or templated wording, no filler openers or stock closing lines.
- **Concise**: as short as the message allows. No repetition, no padding.
- **Professional**: courteous and business-appropriate in tone.
- **To the point**: the purpose or the ask comes early. One clear message per email.
- **Legitimate and factual**: every claim, date, number, name, status, and commitment is real and verified. Never invent or assume a fact.

## Fact gathering before drafting

Start with **claim extraction**: list every checkable item the email will contain (names, dates, times, numbers, ticket IDs, statuses, deadlines, and commitments made by the user or others). Each one must be traced to a source before it is stated as fact.

Then collect those facts from the user's real sources. Check every source that could be relevant, not only the first one that answers:

- Outlook: the email thread, earlier correspondence, calendar entries
- Microsoft Teams: chats and channel messages
- Jira: ticket status, assignee, dates, comments
- Any other connected source that holds the facts (SharePoint, Drive, meeting notes and transcripts, and so on)

Then apply these verification techniques:

1. **Source of truth per fact type.** Verify each fact in its authoritative home, not from a mention elsewhere: ticket status, assignee, and due dates in Jira; what someone said or agreed to in the original Outlook email or Teams message; meeting dates, times, and attendees in the calendar; decisions and action items in meeting notes or transcripts; document contents and versions in the file itself.
2. **Two-source triangulation.** Confirm important facts (deadlines, commitments, money, deliverables) in a second independent source. If sources conflict, do not pick one silently; raise the conflict with the user.
3. **Recency check.** Note the timestamp of each fact and look for anything newer that overrides it (a later reply, a rescheduled meeting, a reopened ticket). The latest dated evidence wins, and the user is told about the discrepancy.
4. **Primary over secondhand.** A report of what someone said is not proof. Find the person's own message. If only the secondhand version exists, attribute it in the email ("as per the colleague's update") instead of stating it as fact.
5. **Detail checks.** Verify name spellings, correct recipients, weekday matching the date, time zones (use the user's own time zone), totals adding up, ticket numbers, and that any attachment mentioned is the right version.
6. **Confidence labelling.** Sort every fact into verified (source found), conflicting (sources disagree), or unverified (no source or source not connected). Only verified facts go in as plain statements. Conflicting and unverified facts go to the user as questions before the draft is final. Never fill a gap with a guess.

## Final cross-check before handing over

Before presenting the final email, review it once more:

1. **Facts**: go through the email sentence by sentence and match every name, date, time, number, ticket ID, status, and commitment back to its source. Confirm nothing has changed since it was gathered, and that editing has not altered a fact (for example "by Friday" becoming "on Friday").
2. **Wording**: check tone, grammar, spelling, clarity, recipient names, and that the subject line matches the body. Remove anything ambiguous or that could be misread.
3. **Completeness**: the email answers what was asked and the ask or next step is clear.

Only then give the user the email. Alongside it, add a short verification table with three columns: the claim in the email, the source it was checked against, and its status (Verified, Conflict, or Could not check). Keep it brief, and call out anything that was agreed verbally or lives in a source that is not connected, so the user is never caught out later.
