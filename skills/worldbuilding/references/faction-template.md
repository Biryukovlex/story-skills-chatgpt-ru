> Адаптация для ChatGPT: читать и отвечать по-русски; применять [русские нормы](russian-chatgpt.md). Команды `story` требуют отдельно установленного CLI и необязательны для текстовой работы.

# Faction Template

Use this template when creating a faction file at `worldbuilding/factions/{faction-name-kebab}.md`.

```yaml
---
name: "{Faction Name}"
type: {family|guild|government|military|religion|company|community|criminal|other}
status: {active|hidden|declining|defeated|disbanded|unknown}
members:
  - {character-kebab}
locations:
  - {location-kebab}
tags:
  - {tag-1}
---
```

## Purpose

What this faction wants and why it exists.

## Power Base

Resources, influence, territory, legitimacy, secrets, rituals, or leverage.

## Members

Important members and their roles.

## Conflicts

Internal divisions and external opposition.
