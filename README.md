# Story Structures

A Claude skill. Recommend and compare fiction structures, turn notes into outlines and synopses, and diagnose or revise plots while preserving the author's canon and creative choices.

## What's inside

- `story-structures/SKILL.md`
- `story-structures/references/evaluation-cases.md`
- `story-structures/references/output-templates.md`
- `story-structures/references/selection-and-comparison.md`
- `story-structures/references/sources.md`
- `story-structures/references/structure-guide.md`

## Install

### Claude app (claude.ai, desktop, mobile)

1. Download this repo as a ZIP (**Code > Download ZIP**) and unzip it.
2. Zip the `story-structures` folder on its own, so the ZIP contains `story-structures/SKILL.md`.
3. In Claude's settings, open the Skills section, upload that ZIP, and turn the skill on.

### Claude Code

```bash
git clone https://github.com/bogsdav/story-structures.git
mkdir -p ~/.claude/skills
cp -r story-structures/story-structures ~/.claude/skills/
```

Restart Claude Code. The skill loads automatically when a request matches its description.

## Try it

- "Which structure fits my mystery novella? Here are my notes."
- "Turn this premise into a chapter outline and a one-page synopsis."
- "My second act sags. Diagnose the plot and suggest revisions."

## License

MIT. See [LICENSE](LICENSE).
