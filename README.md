# email-drafting-rules

Two Claude skills that make every drafted email and Microsoft Teams reply humanized, concise, professional, to the point, and built only on verified facts.

## Skills in this repository

- **email-drafting-rules**: rules for writing emails.
- **teams-chat-reply-rules**: the same standard for Teams chat and channel replies, adapted for chat (one to three sentences, no greetings or sign-offs, tone matched to the conversation).

## What they do

- **Style:** natural wording, no filler, the ask comes early.
- **Fact gathering:** extracts every checkable claim and verifies it in its authoritative source (Outlook, Teams, Jira, calendar, meeting notes, files).
- **Verification techniques:** two-source triangulation, recency check, primary over secondhand, detail checks, and confidence labelling.
- **Final cross-check:** a re-read against sources before the draft is handed over.
- **Verification note:** each draft comes with a claim / source / status summary, so you can see what is solid before you send.

## Install

Install either skill or both. Each folder is one skill.

**Claude apps (claude.ai, desktop, Cowork):** download this repository as a ZIP, then upload the skill folder you want as a skill in Settings > Capabilities > Skills.

**Claude Code:** copy the skill folder into `~/.claude/skills/`.

## Requirements

The skills check facts in whichever sources you have connected. Connect your email, chat, and ticketing tools for full coverage. Facts in a source that is not connected are reported as "Could not check" instead of being guessed.

## License

MIT
