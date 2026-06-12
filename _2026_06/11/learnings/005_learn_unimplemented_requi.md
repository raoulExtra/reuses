```yaml
title: 'Learning: Unimplemented Requirements'
tags:
- learning
- requirement
- process
- checklist
persona: developer
status: draft
version: V00.01.00
updated: 2026-06-11
id: LEARN-005
summary: 'Unimplemented requirements should never have "- [x]" checked.'
```

# Learning: Unimplemented Requirements

> Version: V00.01.00

## Rule

Unimplemented requirements must never have `- [x]` (checked). Only implemented/fulfilled requirements should be checked.

## Rationale

- Checkboxes indicate implementation status
- Checked = implemented/fulfilled
- Unchecked = pending/not implemented
- Accidentally checking unimplemented requirements causes confusion in tracking

## Enforcement

- Review requirement files before committing
- Ensure all `- [x]` boxes have corresponding implementation
- Use `- [ ]` for pending requirements
- Update to `- [x]` only after implementation is complete

## Change History

| Version | Date | Author | Reason |
|---------|------|--------|--------|
| V00.01.00 | 2026-06-11 | ai(kilo laguna) | Initial learning |