# Decision Log

## D-001 — Triggers, not categories
**Accepted.** Architecture/product reasoning starts from state changes and Watch rules, not from “sport + deals + giveaways + events”.

## D-002 — Do not build a super-app first
**Accepted.** MVP gets one primary job and at most one supporting wedge after evidence.

## D-003 — Commerce Watch / Price Truth was the leading first wedge
**Superseded on 2026-09-16 by D-014.** Price/open-data remains useful supporting context, but is no longer the first product wedge after the Tprice/merchant-native competitive deep dive.

## D-004 — Embedded Watch Button is the leading product shape
**Refined by D-015.** Partner distribution remains the leading route, but initial identity should be merchant-owned/hybrid rather than requiring NePropusti ownership.

## D-005 — Sport is a retention experiment, not live-score scope
**Accepted.** Test when + where-to-watch; live scoring stays out.

## D-006 — Notification delivery is commodity
**Accepted.** Build source intelligence, entity/rule/state/trust. Buy/use push/email infrastructure.

## D-007 — Target-price alone is not differentiation
**Accepted.** Cenoteka/Idealno/Tprice and others already cover substantial price-tracking territory.

## D-008 — Giveaways are initially acquisition/trust, not core monetization
**Active hypothesis.** Official-source verification makes them interesting, but repeat business is unproven.

## D-009 — Generic web monitoring is fallback only
**Accepted.** Do not become a localized Visualping/Distill.

## D-010 — Cross-category brand must be earned
**Accepted.** Shared architecture does not prove a shared consumer brand.

## D-011 — Serbian open-price regime is a timing/data-access advantage, not a moat
**Accepted.** Public data is non-proprietary input infrastructure.

## D-012 — Embedded Watch must beat or complement merchant-native CRM/alert tooling
**Accepted validation guardrail.** A merchant commitment counts only when there is a concrete reason to use NePropusti instead of existing plugin/CRM and a willingness to publish a real surface.

## D-013 — Current competitor counts must be dated/ranged, not timeless constants
**Accepted evidence rule.** Current surfaces change; preserve dated evidence and avoid false precision.

## D-014 — Size/variant/restock becomes the leading first validation trigger
**Status: Accepted validation hypothesis**  
**Date: 2026-09-16**

The deep dive found that open-price ingestion/history/comparison is already commoditizing rapidly through Tprice and existing comparison products, while merchant-native price/restock plugins are inexpensive.

The first high-information test is therefore:

`unavailable size/variant -> user creates Watch -> trusted merchant stock transition -> service alert -> attributable return/action`

Reason:
- clearer state;
- immediate intent;
- direct partner ROI;
- avoids universal cross-store identity for the first pilot.

Restock itself is not the moat.

## D-015 — Merchant-owned relationship first; portable Watch identity must be earned
**Status: Accepted validation hypothesis**  
**Date: 2026-09-16**

For initial pilots:
- merchant owns customer relationship;
- NePropusti acts as service/processor layer;
- no mandatory NePropusti account;
- portable cross-site identity is optional/later.

Reason: reduce activation friction and partner resistance; validate cross-site value before claiming network effects.

## D-016 — First partner ICP is mid-market fashion/footwear ecommerce
**Status: Accepted validation hypothesis**  
**Date: 2026-09-16**

Prioritize merchants with size/variant stock churn, enough traffic, reachable owner/ecommerce manager and incomplete item-level alert automation.

Do not start with large enterprises whose CRM/loyalty stacks and procurement burden obscure the basic value test.

## D-017 — Deep-dive investment score is 6.83/10, not proof
**Status: Decision evidence**  
**Date: 2026-09-16**

The score fell from the earlier portfolio model because competition, data operations and merchant-native alternatives are stronger than previously modeled.

Score can improve only through real partner/user/payment evidence, not added features.

Canonical evidence:
`docs/research/nepropusti_deep_dive_2026_09/`
