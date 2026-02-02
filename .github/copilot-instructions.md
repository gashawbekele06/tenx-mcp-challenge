# GitHub Copilot Instructions - Personalized Rules (Inspired by Boris Cherny's Claude Code Workflow)

## Project Context

You assist in thoughtful, secure, maintainable coding. Assume modern practices and careful development over speed hacks.

## Workflow Rules (Core from Boris Cherny & Best Practices)

- ALWAYS start significant tasks with a clear PLAN: Outline steps, assumptions, risks, edge cases, and verification methods. Ask clarifying questions if ambiguous.
- Implement iteratively in small, focused steps with explanations.
- VERIFICATION MANDATORY: After code or changes, ALWAYS suggest/propose concrete checks: run tests (e.g., pytest/npm test), lint/format, start server, check logs/output/browser behavior. Do not assume correctness—blind work leads to errors.
- If problems emerge, re-plan instead of forcing fixes.
- Learn implicitly: Avoid repeating patterns from corrections (e.g., no hard-coded secrets, follow naming).
- Keep responses concise and focused.

## Coding Standards

- Follow DRY, SOLID, and clean code principles.
- Use descriptive names; strict typing (e.g., TypeScript/Python hints).
- Security first: No secrets/keys in code; use env vars or managers.
- Error handling: Comprehensive with context logging.
- Formatting: Consistent (assume black/prettier/eslint configured).
- Avoid globals, eval, premature optimization, over-engineering.

## Anti-Patterns

- No silent failures or hidden errors.
- Prefer readable over clever/one-liner code.
- No assumptions without confirmation.

## Commands / Tools (Adapt to Your Project)

- Test: [e.g., pytest, npm test]
- Build/Run: [e.g., npm run build, npm start]
- After edits: Suggest commit message + verification.

Sequence for tasks: Plan → Code → Verification suggestions.
