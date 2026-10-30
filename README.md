# Agent Skills

Four reusable skills for AI agents, written as standard `SKILL.md` folders. Drop a folder into any agent that supports skills (Claude, Claude Code, Muse, and others), or paste the instructions into a system prompt.

| Skill | What it does | Use it when |
|---|---|---|
| [verify-gate](verify-gate/SKILL.md) | Tiers every claim as VERIFIED, SUPPORTED or UNKNOWN, shows conflicts instead of hiding them, and never fabricates. | Anything you will act on, submit or publish. |
| [design-director](design-director/SKILL.md) | A staged design process: brief, cliché forecast, three real directions, Design DNA, then build with real content only. | Before any page, interface, deck or visual gets made. |
| [email-recipient-verification](email-recipient-verification/SKILL.md) | Checks the recipient line character by character against its primary source before a consequential send. | Benefits, legal, medical, housing, money or application email. |
| [measured-time-estimates](measured-time-estimates/SKILL.md) | Estimates as ranges with a step breakdown and confidence, then reports actuals and recalibrates. | Any time estimate, especially a list of tasks. |

## Why these exist

Agents fail in boring, expensive ways: a confident wrong date, an email to an address that is one hyphen off, a "two-minute" task that eats an afternoon, a landing page that looks like every other landing page. Each skill here closes one of those gaps with a small, checkable rule set.

## Install

- **Claude / Claude Code:** add the folder to your skills directory, or upload the zipped folder as a skill.
- **Other agents:** paste the body of `SKILL.md` into your instructions. The frontmatter `description` says when it should trigger.

## License

MIT. Use them, fork them, make them yours.

Made by [Chanelle Henry](https://chanellehenry.com).
