# Skill: Negative Requirement Enforcement

Explicitly enforce the following invariants:

- Planning workflows must NOT require Analysis or Reprocessing inputs.
- Analysis workflows must NOT require Planning or Reprocessing inputs.
- Reprocessing workflows must NOT require Planning or Analysis inputs.

If any validation path violates these constraints, it must be refactored.
