# Agent Skills (Public)

This repository contains Agent Skills, following the Agent Skills spec:

- https://agentskills.io/what-are-skills
- https://agentskills.io/specification
- https://agentskills.io/integrate-skills

## Layout

Each skill is a folder that contains a `SKILL.md` file with YAML frontmatter (`name`, `description`, etc.) followed by Markdown instructions.

Example:

```text
my-skill/
  SKILL.md
  scripts/        (optional)
  references/     (optional)
  assets/         (optional)
```

## Notes

- Skill directory names should match the `name` in `SKILL.md` (lowercase letters, numbers, hyphens).
- Keep long documentation in `references/` and load it on demand.
