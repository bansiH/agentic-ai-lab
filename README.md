# Agentic AI Lab

A hands-on portfolio for building, evaluating, securing, and operating practical AI agents.

## Learning path

1. **No-code** — prove the agent loop with Make/n8n-style automation.
2. **Low-code** — add LLM extraction, tool calls, state, validation, and human approval.
3. **Medium-code** — introduce custom orchestration, deterministic business logic, evaluation, and reusable skills.
4. **Production patterns** — observability, idempotency, access control, safety, regression testing, and operational runbooks.

## Portfolio agents

- 00 — Hello World Agent
- 01 — Email Triage Agent
- 02 — Household Expense Tracker
- 03 — Financial Research / Decision-Support Copilot
- 04 — Retirement Scenario Planner
- 05 — Utility / Bill Monitor

## Design principles

- Automate the work, not the judgment.
- Facts in, narration out.
- Deterministic logic for consequential decisions.
- Human-in-the-loop for consequential actions.
- Read-only access wherever possible.
- External content is untrusted input.
- Every agent should be observable, testable, and stoppable.

## Repository structure

See `docs/architecture`, `docs/learning-path`, and the individual `agents/*` directories.

## Getting started

The first exercise is intentionally no-code. See:

`agents/00-hello-world/README.md`

No secrets, credentials, personal financial data, or production integrations belong in this repository.
