# Skill: Schema-Driven Validation

Validation rules must be derived from the active workflow schema only.

Authoritative sources for validation:
- The active workflow specification
- The active input guide for that workflow
- Explicit per-workflow include and extra key lists

Global field metadata alone is not sufficient to require a value.

Fields outside the active workflow schema must never trigger required-field errors.
