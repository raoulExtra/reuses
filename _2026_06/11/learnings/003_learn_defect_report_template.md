```yaml
title: 'Learning: Defect Report Template'
tags:
- learning
- process
- defect
- template
persona: developer
status: draft
version: V00.01.00
updated: 2026-06-11
id: LEARN-003
summary: 'Template for consistent defect observation and repair documentation.'
```

# Learning: Defect Report Template

> Version: V00.01.00

## Rule

Defect observations should follow a structured template for consistent reporting.

## Rationale

- Ensures all relevant context is captured
- Provides clear path for repair suggestions
- Enables systematic decision making

## Enforcement

**Defect Observation Template:**

**File:** 
**Line:** 
**Defect Type:** (bug, inconsistency, missing feature, etc.)

**Observed Behavior:**
```
[Describe what was observed - the actual behavior]
```

**Expected Behavior:**
```
[Describe what was expected]
```

**Context:**
```
[Additional context about when/why this matters]
```

**Suggested Repair:**

**Option 1:**
- **Change:** 
- **Impact:** 

**Option 2:**
- **Change:** 
- **Impact:** 

**User Decision:**

**Chosen Option:** 
**Reason:** 
**Alternative Considered:**

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
| V00.01.00 | 2026-06-11 | ai(kilo laguna) | Initial learning |