# Technical Architecture

## Recommended starting architecture

- .NET 10 / ASP.NET Core
- PostgreSQL
- React + TypeScript SEO-first web/control center
- modular monolith
- background workers
- commodity notification provider initially
- object storage only where required
- no Kubernetes/microservices at MVP

## Modules

- Identity
- Partners
- EntityGraph
- Sources
- Observations
- StateProjection
- Rules
- Matching
- AlertCandidates
- NotificationPolicy
- Delivery
- Commerce
- Sports
- Events
- Giveaways
- Trust
- Analytics
- Admin

## Pipeline

`Source/Partner -> Observation -> Normalize -> Resolve Entity -> Project State -> Detect Transition -> Evaluate Rules -> Alert Candidate -> Trust/Freshness -> Notification Policy -> Delivery -> Action Attribution`

## Reliability

Use idempotent ingestion.

Use an outbox/reliable queue pattern if alerts are persisted and dispatched asynchronously. Do not introduce a distributed broker until load/operations justify it.

## Polling

Source-specific:
- high urgency: short polling/webhook;
- medium: scheduled API/feed;
- low: daily/weekly.

## Search

PostgreSQL full-text/trigram first.

## AI

AI may:
- parse user rule to structured draft;
- suggest entity matching;
- classify/extract candidate fields.

AI may not establish price, broadcaster, eligibility or event time as authoritative fact.

## Mobile

Native app remains gated. PWA/web + email/Telegram/web push can validate demand first.
