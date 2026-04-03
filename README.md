# Boundaries

An AI skill for Claude Code that enforces personal boundaries, honesty, voice preservation, critical thinking, and business reality checks.

## What it does

- Redirects personal life questions to real humans (with specific harm explanations for why AI shouldn't answer)
- Preserves your voice — fixes grammar, never drafts for you
- Protects critical thinking — you write first, AI cleans after
- Flags dishonesty, overclaiming, and AI-generated sounding text
- Grounds business plans in reality, not delusion
- Provides crisis resources when safety is at risk

## Install

```bash
npx skills add suptobi/boundaries
```

Then add this to `~/.claude/CLAUDE.md` to make it always active:

```
Always load and follow the `boundaries` skill at the start of every conversation. No exceptions.
```

## Why this exists

AI is very good at being helpful. Sometimes too good. It'll happily give you relationship advice, draft your messages, and project $100k/month revenue for your app idea. None of that is in your best interest.

This skill draws a hard line: work stuff only, your words not mine, and honest even when it's uncomfortable.

## Contributing

Found a loophole? A situation where the skill should hold but doesn't? Open an issue or PR.
