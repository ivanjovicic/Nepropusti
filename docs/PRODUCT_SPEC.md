# Product Spec — Validation Baseline

Last aligned: 2026-09-16  
Status: pre-MVP hypothesis; full implementation is not authorized.

## Product thesis

NePropusti helps users stop repeatedly checking websites by watching trusted structured state for them.

`watch -> observe -> verified transition -> useful alert -> action`

## Primary job under validation

> **Tell me only when a condition I care about becomes true, with enough trust/context that I can act immediately.**

## Leading first wedge — merchant size/variant/restock intent recovery

The first high-information validation job is:

> A shopper wants a specific unavailable size/variant/product. A merchant-hosted or embedded Watch captures that intent, a trusted merchant state transition triggers a service alert, and the user returns to the merchant through an attributable action.

Candidate first triggers:

```text
SIZE_AVAILABLE
BACK_IN_STOCK
```

Why first:
- immediate user intent;
- clear state transition;
- direct merchant ROI;
- strong fit for fashion/footwear and specialist inventory;
- does not require national cross-store product matching to prove the first B2B value.

Important: restock itself is commodity. NePropusti must prove managed intent recovery, low-friction integration, measurable return actions and potentially portable Watch identity — not merely email delivery.

## Initial partner ICP hypothesis

Mid-market Serbian fashion/footwear ecommerce merchant with:
- meaningful traffic;
- size/variant stock churn;
- reachable owner/ecommerce manager;
- WooCommerce/custom or similarly integrable stack;
- incomplete or underused item-level Watch automation;
- ability to expose a real product-page pilot and measure return/conversion outcomes.

## Product-shape hypothesis

### Hosted/Embedded Watch + hybrid B2B2C

Validation sequence:

```text
hosted Watch link
-> simple embedded/JS surface
-> merchant feed/webhook if pilot proves value
-> plugin/SDK/white-label only after repeated partner demand
```

Identity rule for the first pilot:
- merchant owns the customer relationship by default;
- NePropusti acts as the Watch/rule/delivery/attribution service;
- no mandatory NePropusti account;
- portable cross-site identity is optional/later and must be validated.

## Price/open-data role

Price Truth, target price, historical context and public retail data remain supporting capabilities, not the primary product identity.

Do not compete as:
- a national grocery price catalog;
- a better Tprice/Idealno/Cenoteka/ePonuda;
- a generic price-history site.

Public retail data is a timing/input advantage only.

## Secondary validation wedge

Sport + where-to-watch may be tested for recurring retention. Do not build live scores or a broadcaster database before data rights/freshness and payer value are proven.

## Separate adjacency

NePropusti Pro / professional deadline alerts (grants, subsidies, public calls, tenders, scholarships, regulatory deadlines) may have higher WTP, but must remain a separate validation track with different buyer/source/pricing assumptions.

## North Star candidates

Consumer/service layer:
**Useful Alert Actions per Active Watcher**

Partner layer:
**Attributed Return / Recovered Actions per Live Partner Surface**

## Non-goals

Current evidence does not authorize:
- generic comparison catalog;
- all-category consumer app;
- broad crawler fleet;
- native mobile app;
- social feed;
- marketplace checkout;
- regional rollout;
- merchant portal before real pilot demand.

Canonical deep-dive evidence:
`docs/research/nepropusti_deep_dive_2026_09/00_EXECUTIVE_DECISION.md`
