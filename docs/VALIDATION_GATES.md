# Validation Gates

Last aligned: 2026-09-16

## G0 — Desk due diligence
**Status: PASSED for research baseline**

Current evidence:
- Serbia has machine-readable/open retail-price infrastructure across major chains;
- this data is useful input, not proprietary moat;
- Tprice has already converted the same broad data opportunity into a large comparison/history/barcode product;
- Cenoteka/Idealno/ePonuda and merchant-native plugins/CRM already cover substantial price/restock territory;
- therefore a generic `price alert`, `price history`, or `back in stock email` is not differentiated by itself.

Strategic implication:
- validate merchant-distributed **size/variant/restock intent recovery** first;
- prove measurable partner return and low operational burden;
- keep price/open-data as supporting context.

## G1 — Merchant Watch demand
**Status: OPEN**

Initial trigger focus:
`SIZE_AVAILABLE` / `BACK_IN_STOCK`

Pass candidates:
- 50–100 qualified users exposed through real/high-fidelity merchant contexts;
- >=30% create at least one real watch after understanding value;
- genuinely useful triggers produce >=25% action/return rate as a candidate strong signal;
- materially wrong/stale alerts remain <5% during controlled pilot;
- users see value beyond manual checking/current merchant functionality.

Kill/pivot signals:
- <15% watch creation after clear proposition;
- current merchant/plugin/CRM solution already solves the job well enough;
- wrong/late variant state destroys trust.

Price/Price Truth can be tested as secondary conditions only after the primary pilot has a working partner surface.

## G2 — Sports where-to-watch
**Status: OPEN, lower priority**

Pass candidate:
- 50–100 users, narrow entity set, 4 weeks;
- recurring useful actions and week-4 retained behavior;
- reliable/licensable Serbia-specific broadcast data path identified;
- plausible payer/strategic role identified.

Cheap fixture APIs are not proof that broadcast mapping/reuse is solved.

## G3 — Embedded partner / B2B2C
**Status: OPEN — highest business-risk gate**

Initial ICP:
mid-market Serbian fashion/footwear ecommerce merchants with meaningful size/variant stock churn.

Pass candidate:
- 20 strong-fit partner pitches/manual audits;
- >=5 credible pilot commitments;
- >=3 partners actually publish a hosted/embedded Watch surface;
- at least two partners request continuation/expansion after observing outcomes.

Kill signal:
- <2 real commitments after 20 strong-fit pitches.

Every partner test must answer:
1. What does the merchant use today: plugin, CRM, wishlist, native app, manual process?
2. Why use NePropusti instead of a €49–59 plugin or existing CRM automation?
3. Who owns integration and source/data correctness?
4. Which metric justifies payment: recovered revenue, return visits, restock conversion, qualified actions, demand insight?
5. Can the merchant expose canonical product/variant IDs and preferably webhook/feed state?
6. Will the merchant publish a real surface?
7. What is onboarding/support time?

A credible commitment requires named owner, concrete product/page/context, agreed next step/timing and willingness to measure outcomes.

## G4 — Alert quality
**Status: BLOCKED by G1/G3**

Minimum source-quality discipline:
- every actionable field has provenance/freshness;
- merchant canonical variant ID is preferred for first pilot;
- unresolved source conflicts suppress alert rather than guessing;
- false/stale/late/duplicate alert rates are measured;
- support/dispute reasons are logged.

## G5 — Partner economics / operating burden
**Status: BLOCKED by live pilots**

Measure per partner:
- onboarding hours;
- recurring support hours;
- source/integration failures;
- active watches;
- triggered alerts;
- return actions;
- attributed conversion where available;
- estimated incremental gross profit.

Candidate healthy signal:
ongoing support can plausibly stay around <=1–2 hours/partner/month after onboarding for a standardized integration path.

This is a hypothesis, not an industry benchmark.

## G6 — Narrow MVP
**Status: BLOCKED**

Only winning trigger + winning product shape may enter production scope.

Current research does **not** authorize:
- national comparison catalog;
- general consumer super-app;
- broad crawler fleet;
- WooCommerce plugin before repeated pilot need;
- native mobile app;
- regional rollout.

## G7 — Monetization
**Status: BLOCKED**

Pass only with real commercial evidence:
- >=3 paying partners or equivalent signed paid pilots is a strong 90-day promotion signal;
- payer/budget owner identified;
- payment tied to recovered/qualified value, not generic notification volume.

Candidate pricing tests such as €99–199/month are hypotheses, not validated pricing.

`Would pay` survey intent is not a pass.

## G8 — Portable identity / second vertical
**Status: BLOCKED**

Do not assume cross-site/cross-category identity is valuable.

Test only after one merchant wedge works. Pass requires evidence that users actually adopt multiple merchants/watches/categories without higher mute/unsubscribe and that partners tolerate the identity model.

## G9 — Native mobile
**Status: BLOCKED**

Requires proven mobile-specific retention/action value beyond web/email/Telegram/web push.

## G10 — Regional expansion
**Status: BLOCKED**

Requires repeatable Serbia partner acquisition, standardized source operations, positive unit economics and evidence that country-specific data/legal work is manageable.

## 90-day promotion gate

NePropusti can justify materially higher investment only if evidence approaches:
- >=5 credible partner commitments;
- >=3 live partner surfaces;
- >=3 real paying partners/paid pilots;
- >=30% qualified watch creation;
- >=25% action rate on genuinely useful triggers as a strong candidate signal;
- <5% materially wrong/stale alerts;
- >=2 partners request continuation/expansion;
- merchant webhook/feed model meaningfully reduces data burden.

Canonical deep-dive evidence:
`docs/research/nepropusti_deep_dive_2026_09/00_EXECUTIVE_DECISION.md`
