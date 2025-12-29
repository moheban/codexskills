# Skill: UI Visibility vs Validation Scope Separation

UI visibility does NOT define validation scope.

Validation scope is defined ONLY by:
- The active workflow
- The active workflow schema

UI helpers may improve user experience but must never be relied upon for correctness or validation gating.
