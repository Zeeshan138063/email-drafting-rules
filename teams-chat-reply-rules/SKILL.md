---
name: "teams-chat-reply-rules"
description: "Use whenever drafting or rewriting a Microsoft Teams chat or channel reply on the user's behalf: enforces a short, human, professional, fact-verified message with a final cross-check before delivery."
---

# Teams chat reply rules

These are standing rules for every Teams chat or channel message written on the user's behalf: replies, follow-ups, status updates, and new messages. They apply whether or not the user repeats them. For emails, use the email-drafting-rules skill instead.

## Read the conversation first

Before drafting, read the recent messages in the chat or channel thread so the reply fits what was actually said:

- Identify exactly what is being asked and by whom. Answer that, not something nearby.
- Check whether someone has already answered, or whether the user already replied, so the message does not repeat or contradict it.
- Match the tone of the conversation: more relaxed in a 1:1 with a teammate, more careful in a client or leadership channel.

## Style

Chat is not email. Every reply must be:

- **Humanized**: it sounds like the user typing to a colleague. Natural, conversational wording. No robotic or templated phrasing.
- **Short**: usually one to three sentences. Lead with the answer or the ask. If it needs more than a short paragraph, break it into a few brief lines or suggest a call or email instead.
- **Professional**: friendly but business-appropriate. No slang that could be misread, and no emojis unless the user asks or the conversation already uses them.
- **To the point**: no greeting lines, no sign-offs, no subject, no "hope you're well". A first name or an @mention at the start is enough when the message needs to be directed at someone.
- **Legitimate and factual**: every date, number, name, status, and commitment is real and verified. Never invent or assume a fact.

## Fact gathering before drafting

Start with **claim extraction**: list every checkable item the reply will contain (names, dates, times, numbers, ticket IDs, statuses, deadlines, and commitments). Each one must be traced to a source before it is stated as fact.

Check every source that could be relevant:

- Microsoft Teams: this thread and related chats and channels
- Outlook: emails and calendar entries
- Jira: ticket status, assignee, dates, comments
- Any other connected source that holds the facts (SharePoint, Drive, meeting notes and transcripts, and so on)

Then apply these verification techniques:

1. **Source of truth per fact type.** Verify each fact in its authoritative home: ticket status, assignee, and due dates in Jira; what someone said or agreed to in their original message or email; meeting dates, times, and attendees in the calendar; decisions and action items in meeting notes or transcripts; document contents and versions in the file itself.
2. **Two-source triangulation.** Confirm important facts (deadlines, commitments, money, deliverables) in a second independent source. If sources conflict, do not pick one silently; raise the conflict with the user.
3. **Recency check.** Look for anything newer that overrides a fact (a later message, a rescheduled meeting, a reopened ticket). The latest dated evidence wins, and the user is told about the discrepancy.
4. **Primary over secondhand.** A report of what someone said is not proof. Find the person's own message. If only the secondhand version exists, attribute it in the reply instead of stating it as fact.
5. **Detail checks.** Verify name spellings, the right person being @mentioned, weekday matching the date, time zones (use the user's own time zone), and ticket numbers.
6. **Confidence labelling.** Sort every fact into verified, conflicting, or unverified. Only verified facts go in as plain statements. Conflicting and unverified facts go to the user as questions before the reply is final. Never fill a gap with a guess.

A reply with no checkable facts (a simple acknowledgement or thanks) needs no source checks, only the wording check below.

## Final cross-check before handing over

Before presenting the reply, review it once more:

1. **Facts**: match every name, date, time, number, ticket ID, status, and commitment back to its source, and confirm nothing has changed since it was gathered.
2. **Wording**: check tone, grammar, spelling, and clarity. Remove anything that could be misread, since chat messages are read quickly and often without context.
3. **Fit**: it answers what was asked, does not commit the user to anything they did not agree to, and is safe for everyone in that chat or channel to see.

Only then give the user the reply, ready to paste. Below it, add a brief verification note: which sources were checked, and anything that is conflicting or could not be verified. Use a claim / source / status table only when the reply contains three or more facts; otherwise one line is enough. Do not send the message on the user's behalf unless they explicitly ask.
