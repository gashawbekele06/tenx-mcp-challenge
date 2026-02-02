# Tenx MCP Challenge Report - Gashaw

## Task 1: Setup

[Same as before – detailed, no issues after reloads/headers check.]

## Task 2: Research & Rules

- Primary: Boris Cherny's Jan/Feb 2026 thread (plan mode first, verification critical, self-update CLAUDE.md after mistakes, parallel worktrees, concise rules ~2.5k tokens).
- Additional: GitHub Docs/Blog (repo-wide instructions, natural language, sections for stack/standards); VS Code Docs (auto-apply to chat/gen); Cursor Docs (composable .mdc, <500 lines, globs); Anthropic Claude Code best practices (concise CLAUDE.md, /init starters); Wiz Blog (security rules); Reddit/Medium (emphatic phrasing, cross-tool reuse).
- Changes: Started basic standards → added planning/verification (Boris) → emphatic "ALWAYS" + security (GitHub/Wiz) → concise sections (Cursor tip).
- Testing: 8+ prompts; v1 skipped planning → v3 consistent outlines/tests. Copilot: Global adherence good but verbose ignored; Cursor sim (forum examples): Scoped rules more precise.

## What Worked

- Planning/verification mandates → Copilot outlines + suggests checks (matches Boris 2-3x quality boost).
- Concise + emphatic → Reliable vs. vague drafts.
- Personal focus (deliberate progress) → Aligns outputs with my careful style.

## What Didn't Work / Troubleshooting

- v1/v2: Skipped on simple prompts → "ALWAYS" + sequence fixed.
- MCP: Detection delay → Reload + header validation.
- Verbose rules: Diluted focus → Trimmed <300 lines.

## Insights Gained

Rules align AI to my intent: Without planning, hasty code (mismatch thoughtful process); with Boris-style verification + emphatic directives, outputs mirror step-by-step + testable reasoning. Copilot static vs. Cursor modular (globs better for scoping) vs. Claude dynamic self-update. Phrasing critical—"ALWAYS" enforces better. Iteration + diverse sources (GitHub/Cursor/Anthropic) show rules evolve: minimal start → test/refine → better alignment/expectation match.
