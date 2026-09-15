# AGENTS.md — NePropusti

## Mission

Validate whether NePropusti can become a defensible and profitable structured Watch/Trigger platform before building a broad product.

## Current decision

**VALIDATE BEFORE BUILDING**

Leading wedge: **Commerce Watch / Price Truth**.

Leading product shape: **Embedded Watch Button / Hybrid B2C+B2B2C**.

Secondary wedge under parallel validation: **Sport + where-to-watch**.

## Source of truth order

1. `docs/DECISION_LOG.md`
2. `docs/VALIDATION_GATES.md`
3. `docs/ROADMAP.md`
4. `docs/PRODUCT_SPEC.md`
5. current prompt queue
6. `docs/research/2026-09-15/00_EXECUTIVE_DECISION.md`
7. supporting research

If these conflict, stop and document the conflict. Do not silently choose the most convenient interpretation.

## Evidence discipline

Every current market/data/legal claim must be classified as one of: FACT, ESTIMATE, ASSUMPTION, HYPOTHESIS, UNKNOWN.

Do not convert vendor marketing, scraped visibility, or global behavior into a Serbian fact without qualification.

## Allowed now

- source/data audits;
- partner interviews;
- user interviews;
- no-code/hosted Watch tests;
- manual commerce-watch concierge;
- manual sports where-to-watch concierge;
- partner widget mock/prototype;
- data normalization experiments;
- analytics for validation.

## Blocked now

Until corresponding gates pass, do not implement:

- broad production platform;
- native Flutter app;
- four-vertical launch;
- live-score engine;
- arbitrary web crawler fleet;
- marketplace checkout;
- ticket marketplace;
- public social/community feed;
- advanced ML/recommender;
- regional rollout;
- Kubernetes/microservices.

## Architecture after authorization

Default:

- .NET 10 / ASP.NET Core
- PostgreSQL
- React + TypeScript
- modular monolith
- background workers
- commodity notification provider
- immutable observations + materialized state
- deterministic truth before AI

## Core product model

`WATCH RULE -> OBSERVATION -> STATE -> TRANSITION -> VERIFY -> MATCH -> ALERT -> ACTION`

The product moat is not push delivery. Prefer buying commodity delivery infrastructure.

## Agent rule

No coding task becomes READY merely because it appears in long-term research. Implementation must map to a passed validation gate.
