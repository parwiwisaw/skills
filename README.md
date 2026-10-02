# Skills

Personal AI skills for Claude Code and other coding agents.

## Skills

| Skill | Description |
| --- | --- |
| [developer-speak](skills/developer-speak/SKILL.md) | Answers developer questions answer-first, with structure (steps, tables, Mermaid) that mirrors the problem. |

## Claude Code

Plugins bundle related skills. Install one with:

```text
/plugin marketplace add parwiwisaw/skills
/plugin install <plugin>@parwiwisaw-skills
```

## npx skills

Install a single skill from your project directory:

```sh
npx skills add parwiwisaw/skills --skill <skill>
```

## Layout

```text
skills/<skill>/SKILL.md                      standalone skills
plugins/<plugin>/.claude-plugin/plugin.json  plugin manifest
plugins/<plugin>/skills/<skill>/SKILL.md     skills bundled in a plugin
.claude-plugin/marketplace.json              lists plugins for /plugin marketplace
```
