# Claude skills

Skills for Claude (claude.ai and Claude Code), used at MIX2.AI. Each folder in `skills/` is one skill: a `SKILL.md` plus optional `references/`.

| Skill | Use it for |
|---|---|
| `no-bullshit-strategy` | Strategy, positioning, differentiation, critiquing a strategy (Alex M H Smith) |
| `never-split-the-difference` | Negotiations, sales objections, difficult conversations (Chris Voss) |
| `wordmark-logo` | Type-led logo and wordmark design |

## Using them
- **Claude Code:** link each folder into `~/.claude/skills/` (for example `ln -s ~/claude-skills/skills/<name> ~/.claude/skills/<name>`). Claude picks a skill automatically when a request matches its description, or you can call it by name, e.g. `/no-bullshit-strategy`.
- **claude.ai:** zip a skill folder and upload it under Settings → Capabilities → Skills.
- **Transcripts:** `references/transcripts/` in the strategy and negotiation skills is for source transcripts (e.g. from YouTube talks). Add them there to deepen the skill.
