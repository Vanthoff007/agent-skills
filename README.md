# agent-skills

A personal collection of agent skills I use, packaged as a Claude Code plugin.
Each skill is a folder under `skills/` containing a `SKILL.md` file with
instructions for the agent.

## Skills

| Skill | What it does |
| --- | --- |
| [socratic-tutor](skills/socratic-tutor/SKILL.md) | Strict Socratic tutor: diagnostic, a 0-5 skill map, one question at a time, spaced review and a final assessment. Trigger with "teach me X". |

## Install (Claude Code)

    /plugin marketplace add Vanthoff007/agent-skills
    /plugin install agent-skills@vanthoff007-skills

Update later with:

    /plugin marketplace update vanthoff007-skills

## Other agents and chatbots

Copy a skill folder into your agent's skills directory, or paste the body of
its `SKILL.md` into a chat or system prompt.

## Adding a skill

1. Create `skills/<skill-name>/SKILL.md` with `name` and `description` frontmatter.
2. Bump `version` in `.claude-plugin/plugin.json`.
3. Push, then run `/plugin marketplace update vanthoff007-skills`.

## Licensing

Each skill keeps its own license file inside its folder where one applies.
