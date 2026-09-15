# Architecture Decisions

## ADR-001 — Modular monolith first
.NET 10 + ASP.NET Core + PostgreSQL + React/TypeScript.

## ADR-002 — Immutable observations
Never overwrite source truth. Store observations and materialize current state separately.

## ADR-003 — Trigger/rule core
Domain pipeline:
`Source -> Observation -> Entity Resolution -> State -> Transition -> Rule Match -> Alert Candidate -> Trust/Policy -> Delivery`.

## ADR-004 — Commodity delivery
Use FCM/OneSignal/Knock/email provider as appropriate; do not build push infrastructure as moat.

## ADR-005 — AI is assistive, not authoritative
AI may parse rules or suggest entity matches. AI must not establish authoritative price, broadcaster, event date or giveaway eligibility.

## ADR-006 — No vector DB by default
Use deterministic identifiers/aliases/structured fields first.

## ADR-007 — No microservices/Kubernetes before measured need
Background workers and reliable outbox are sufficient initial tools if build is authorized.

## ADR-008 — Native app is gated
Web/PWA + email/Telegram/web push are enough for validation.
