# Tenx MCP Challenge - Gashaw

## Setup (Task 1)

- IDE: VS Code
- Installed GitHub Copilot + Copilot Chat.
- Created `.vscode/mcp.json` with URL https://mcppulse.10academy.org/proxy, name "tenxfeedbackanalytics", headers X-Device:"windows" (or your OS), X-Coding-Tool:"vscode".
- Authenticated via GitHub redirect.
- Verified: Tools visible in Copilot Chat; tested prompt confirmed connection.
- Active: Workspace kept open for logging.

## Rules Research & Changes (Task 2)

- Studied Boris Cherny's Jan 2026 thread (via X summaries): Emphasis on planning, verification, shared CLAUDE.md updates after mistakes, subagents/parallel, concise rules.
- Community patterns: Concise files (<100 lines), explicit planning/verification loops, mistake-proofing.
- Created `.github/copilot-instructions.md` with sections: Workflow (plan → code → verify), Standards, Anti-patterns.
- Changes: Added strong "ALWAYS plan" and verification mandates; adapted Claude-focused tips to Copilot.

## What Worked

- Planning rule → Copilot now outlines steps first in responses.
- Verification suggestions → Prompts include test/run commands automatically.
- Concise structure → Better adherence vs. longer drafts.

## What Didn't Work / Troubleshooting

- Initial MCP: No start button → Reloaded VS Code, re-checked mcp.json syntax.
- Copilot skipped planning on simple prompts → Added "ALWAYS" emphasis and tested iteratively.
- If MCP auth failed: Cleared browser cache, re-authorized GitHub app.

## Insights Gained

Rules shift AI from generic autocomplete to aligned partner. Explicit planning/verification matches thoughtful style (reduces hasty/buggy code). Iterative testing shows phrasing matters—"ALWAYS" > soft suggestions. Boris's self-updating rules concept inspires long-term improvement (Copilot learns implicitly via repeated use).
