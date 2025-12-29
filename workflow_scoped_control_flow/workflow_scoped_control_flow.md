# Skill: Workflow-Scoped Control Flow Analysis

When modifying or analyzing code:

1. Identify all workflow or mode switches (e.g., Planning, Analysis, Reprocessing).
2. For each workflow:
   - Trace which functions are executed.
   - Identify which variables are parsed, validated, or required.
3. Ensure that required-field validation is enforced ONLY within the active workflow branch.
4. Detect and refactor unconditional parsing or validation that spans multiple workflows.
5. A value required in one workflow must not be required in any other workflow unless explicitly stated.

If validation or parsing is not explicitly scoped to the active workflow, it must be corrected.
