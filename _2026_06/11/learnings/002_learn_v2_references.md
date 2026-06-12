```yaml
title: 'Learning: v2 Reference Consistency'
tags:
- learning
- flow_mind
- v3
- references
persona: developer
status: draft
version: V00.02.00
updated: 2026-06-11
id: LEARN-002
summary: 'Keep file path references and logical inheritance names distinct in v3 flows.'
```

# Learning: v2 Reference Consistency

> Version: V00.02.00

## Rule

Header `extends:` uses relative path while Flow block `extends:` uses logical name.

## Rationale

- Header path is for file resolution (FR-FM-V3-PATH-01)
- Flow block name is for logical inheritance
- The v2 base template name in YAML frontmatter is `flow_base_v2`
- The v3 requirements mandate reuse of v2 parsing/validation logic while supporting path resolution with arguments

## Enforcement

**Chosen:** Keep both references distinct
- Header: `../v2/010_flow_base` (file path)
- Flow: `flow_base_v2` (logical inheritance name)

**Impact:** Correct separation of file resolution vs inheritance semantics

## Filename Convention

Learning files follow the naming pattern: `NNN_learn_<descriptive_name>.md`

- `NNN` - Three-digit sequence number (001, 002, etc.)
- `learn_` - Prefix indicating this is a learning document
- `<descriptive_name>` - Lowercase with underscores, describing the topic

**Examples:**
- `001_learn_flow_patterns.md`
- `005_learn_unimplemented_requi.md`
- `010_learn_testing_convention.md`

**Deriving good filenames:**
1. Start with sequence number (check existing files for next available)
2. Use `learn_` as prefix
3. Describe the learning in 2-4 words
4. Convert to lowercase with underscores
5. No special characters or spaces

## Change History

| Version | Date | Author | Reason |
|---------|------|--------|--------|
| V00.02.00 | 2026-06-11 | ai(kilo laguna) | Updated to follow template |
| V00.01.00 | 2026-06-11 | ai(kilo laguna) | Initial learning |