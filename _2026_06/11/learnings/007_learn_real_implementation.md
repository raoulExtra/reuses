```yaml
title: 'Learning: Real Implementation for Meaningful Tests'
tags:
- learning
- testing
- implementation
- real-filesystem
persona: developer
status: draft
version: V00.01.00
updated: 2026-06-11
id: LEARN-007
```

# Learning: Real Implementation for Meaningful Tests

> Version: V00.01.00

## Rule

Tests must implement against real functionality and database, not stubs or mocks, to provide meaningful verification.

## Rationale

- Stubbed implementations give false confidence
- Real functionality reveals path, permission, and timing issues
- Database operations behave differently with real data
- Integration tests must exercise actual code paths

## Enforcement

- Use real functionality in tests
- Use real SQLite database
- Test actual file creation, modification, deletion
- Verify real path resolution and error handling

## Filename Convention

Learning files follow the naming pattern: `NNN_learn_<descriptive_name>.md`

- `NNN` - Three-digit sequence number
- `learn_` - Prefix
- `<descriptive_name>` - Lowercase with underscores

## Change History

| Version | Date | Author | Reason |
|---------|------|--------|--------|
| V00.01.00 | 2026-06-11 | ai(kilo laguna) | Initial learning |