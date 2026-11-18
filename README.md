# email-drafting-rules

A Claude skill that makes every drafted email humanized, concise, professional, to the point, and built only on verified facts.

## What it does

- **Style:** natural wording, no filler, the ask comes early.
- **Fact gathering:** extracts every checkable claim and verifies it in its authoritative source (Outlook, Teams, Jira, calendar, meeting notes, files).
- **Verification techniques:** two-source triangulation, recency check, primary over secondhand, detail checks, and confidence labelling.
- **Final cross-check:** a sentence-by-sentence re-read against sources before the email is handed over.
- **Verification table:** each draft comes with a claim / source / status table, so you can see what is solid before you send.

## Install

**Claude apps (claude.ai, desktop, Cowork):** download this repository as a ZIP, then upload the `email-drafting-rules` folder as a skill in Settings > Capabilities > Skills.

**Claude Code:** copy the `email-drafting-rules` folder into `~/.claude/skills/`.

## Requirements

The skill checks facts in whichever sources you have connected. Connect your email, chat, and ticketing tools for full coverage. Facts in a source that is not connected are reported as "Could not check" instead of being guessed.

## License

MIT
