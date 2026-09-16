# Documentation Index

Last aligned: 2026-09-16

## Canonical execution docs
1. `../README.md`
2. `PRODUCT_SPEC.md`
3. `VALIDATION_GATES.md`
4. `ROADMAP.md`
5. `DECISION_LOG.md`
6. `ARCHITECTURE_DECISIONS.md`
7. `OPPORTUNITY_BACKLOG.md`
8. `prompt_queues/README.md`
9. `prompt_queues/validation.md`

## Latest decision research — read for market/business tasks

`research/nepropusti_deep_dive_2026_09/`

Start with:
- `00_EXECUTIVE_DECISION.md`
- `02_TPRICE_AND_PRICE_COMPETITOR_TEARDOWN.md`
- `04_TRIGGER_ECONOMICS.md`
- `08_EMBEDDED_WATCH_PARTNER_ECONOMICS.md`
- `18_FAILURE_MODES_AND_KILL_CRITERIA.md`
- `19_UPDATED_SCORECARD.md`
- `20_SCORE_IMPROVEMENT_LEVERS.md`
- `SOURCES.md`

This deep dive supersedes the older first-wedge ranking where they conflict. It does not authorize product implementation.

## Research baseline
`research/2026-09-15/`

Contains the original `00`–`22` due-diligence package plus `SOURCES.md`. Preserve it as historical evidence/context.

## Market evidence refresh
`research/MARKET_EVIDENCE_REFRESH_2026_09_16.md`

Useful for the first 2026 open-price/competitor update; the deep dive above is newer and more specific.

## Reproducible data
Original baseline:
- `../data/nepropusti_wedge_scores.csv`
- `../data/nepropusti_product_shape_scores.csv`
- `../data/nepropusti_unit_economics.csv`
- `../data/nepropusti_competitor_matrix.csv`
- `../data/nepropusti_data_source_matrix.csv`

Latest deep-dive models:
- `research/nepropusti_deep_dive_2026_09/data/merchant_watch_feature_audit.csv`
- `research/nepropusti_deep_dive_2026_09/data/trigger_economics.csv`
- `research/nepropusti_deep_dive_2026_09/data/partner_segment_scores.csv`
- `research/nepropusti_deep_dive_2026_09/data/product_shape_scores.csv`
- `research/nepropusti_deep_dive_2026_09/data/updated_scorecard.csv`
- `research/nepropusti_deep_dive_2026_09/data/score_improvement_levers.csv`

## Evidence/run logs
See `../.ai/runs/`.

## Rule
Research explains why. Canonical execution state lives in README, Product Spec, Validation Gates, Roadmap, Decision Log and the current validation queue.

Do not let an older research ranking override a newer accepted decision without explicitly recording the conflict.
