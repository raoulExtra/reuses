```yaml
title: 'Learning Template'
tags:
- learning
- template
persona: developer
status: active
version: V00.01.00
updated: 2026-06-11
id: TEMPLATE-001
summary: 'Template for creating new learning documents.'
```

# Learning Template

> Version: V00.01.00

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

## Learning Document Structure

```yaml
title: 'Learning: <TITLE>'
tags:
- learning
- <tags>
persona: <persona>
status: draft
version: V00.01.00
updated: <DATE>
id: LEARN-NNN
summary: '<SUMMARY>'
```

## Change History

| Version | Date | Author | Reason |
|---------|------|--------|--------|
| V00.01.00 | 2026-06-11 | ai(kilo laguna) | Initial template |