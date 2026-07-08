# Agent Skills

A collection of skills for AI coding agents. Skills are packaged instructions and scripts that extend agent capabilities.

Skills follow the [Agent Skills](https://agentskills.io/) format.

[![skills.sh](https://skills.sh/b/ricardocasares/skills)](https://skills.sh/ricardocasares/skills)

## Available Skills

### elm-patterns

Idiomatic Elm patterns for data modeling, type-system techniques, and TEA application structure. Covers all 25 patterns from [Elm Patterns](https://sporto.github.io/elm-patterns/) by Sebastian Porto, organized behind a symptom-based routing table.

**Use when:**

- Writing or reviewing Elm code
- Modeling data with custom types, `Maybe`, or `Result`
- Designing module APIs (builder pattern, opaque types)
- Structuring TEA applications (Model/Msg/update/view)
- Handling parent-child communication in nested TEA
- Making update functions testable

**Categories covered:**

- Data modeling and API design (type blindness, minimize booleans, impossible states, parse don't validate, builder pattern, type iterator)
- Type-system techniques (railway, pipeline builder, opaque types, phantom types, combinators)
- TEA architecture (reusable views, nested TEA, child outcome, translator, global actions, effects pattern, update return pipeline)

## Installation

```bash
npx skills add ricardocasares/skills
```

## Usage

Skills are automatically available once installed. The agent will use them when relevant tasks are detected.

**Examples:**

```
Model a request that can be loading or loaded in Elm
```

```
Review this Elm module for anti-patterns
```

```
My child page needs to notify its parent after saving
```

## Skill Structure

Each skill contains:

- `SKILL.md` - Instructions for the agent
- `scripts/` - Helper scripts for automation (optional)
- `references/` - Supporting documentation (optional)

## License

MIT
