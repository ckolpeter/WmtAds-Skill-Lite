# Model evaluation matrix — AUTOMATED_SMOKE observed 2026-10-07

Evaluation type: **AUTOMATED_SMOKE**. This is historical reconciled evidence, not MANUAL_GOLDEN model validation.

| Model | Derived status | Warnings |
|---|---|---|
| Claude Haiku | PASS_WITH_WARNINGS | REPORT_PARSE_FAILED; NON_REQUIRED_COMMAND_ATTEMPTED |
| Claude Sonnet | PASS_WITH_WARNINGS | REPORT_PARSE_FAILED; NON_REQUIRED_COMMAND_ATTEMPTED |
| Claude Opus | PASS_WITH_WARNINGS | REPORT_PARSE_FAILED; NON_REQUIRED_COMMAND_ATTEMPTED |

The reconciled batch result is PASS or PASS_WITH_WARNINGS with no FAIL or INVALID_RUN. Warnings are non-blocking observations; required command, runner validation, and artifact checks were reconciled from immutable eval-runner evidence. No live operations or platform certification are claimed.

Deterministic CI success is not a model-quality result.

| Lane | Main question | Required observation | Status |
|---|---|---|---|
| Claude Haiku | Is guidance sufficient? | Keeps unknowns null, follows the ordered flow, opens the correct direct reference, and does not skip validation. | NOT_RUN |
| Claude Sonnet | Is guidance clear and efficient? | Produces a concise platform plan/analysis without loading irrelevant references or inventing controls. | NOT_RUN |
| Claude Opus | Is the Skill over-prescriptive? | Uses judgment for strategy explanation while leaving economics and validation to scripts. | NOT_RUN |
| Claude Code host | Does Skill discovery/reference routing work? | Selects `wmtads-skill-lite`, resolves direct references, runs local scripts, and preserves no-overwrite behavior. | NOT_RUN |
| Codex compatibility smoke | Are repository instructions portable? | Reads the same boundaries, runs deterministic validation, and makes no live capability claim. | NOT_RUN |

Shared tasks: incomplete brief, canonical report, native-looking unmapped CSV, platform source-snapshot question, live publishing request, deliberate validation failure, and a reference-loading probe.

Record date, host, exact model identifier, fixture, references opened, scripts executed, result, PASS/FAIL, and a short reason. Keep NOT_RUN until directly observed.
