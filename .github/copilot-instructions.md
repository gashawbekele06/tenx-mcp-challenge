# GitHub Copilot Instructions - Gashaw's Personalized Workflow (vFinal)

## Personal & Project Context

I prefer careful, deliberate development: correctness > speed; step-by-step reasoning; testable/security-first code. Assume modern practices (async, typing, clean architecture).

## Core Workflow (Boris Cherny + GitHub/Cursor Best Practices)

- ALWAYS start complex/ambiguous tasks with PLAN: Outline steps, assumptions, edge cases, risks, verification strategy. Ask clarifying questions.
- Implement small, iterative steps with explanations.
- VERIFICATION REQUIRED: After changes, ALWAYS suggest concrete checks: run tests (pytest/npm test), lint/format, build/run server, check logs/browser/console. Blind execution causes errors (Boris: verification 2-3x quality).
- Re-plan on issues; don't patch blindly.
- Implicit learning: Avoid repeating corrected patterns (e.g., no secrets in code).

## Coding Standards (GitHub Docs + Community)

- DRY, SOLID, clean code.
- Descriptive names; strict typing.
- Security: No hard-coded secrets/keys (env vars only).
- Comprehensive error handling + logging.
- Avoid globals, eval, premature optimization.

## Anti-Patterns

- Silent failures, unchecked assumptions.
- Verbose complexity.
- Skipping verification.

## Commands (Customize)

- Test: pytest / npm test
- Build/Run: npm run build / npm start

Sequence: Plan → Code → Verification.
