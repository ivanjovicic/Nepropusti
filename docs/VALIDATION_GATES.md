# Validation Gates

## G0 — Desk due diligence
**Status: PASSED for research baseline**

Current evidence refresh (2026-09-16):
- Serbia's current consumer-protection framework requires machine-processable price publication and supports automated price collection for comparison;
- the Ministry states that 35 large retail chains are in the daily price-publication regime;
- current open-data examples are real-time CSVs and expose fields such as product, brand, barcode, unit and price under published open-data terms;
- target-price / discount-threshold alerts already exist in the local market, so `price alert` by itself is not a differentiated wedge.

Strategic implication:
- treat public retail data as an **input advantage / timing tailwind**, not as a moat;
- validate `Embedded Watch + trusted state transition + measurable partner return`, not another comparison catalog.

## G1 — Commerce watch demand
**Status: OPEN**

Pass candidate:
- 50–100 qualified users exposed;
- >=30% create at least one real watch after understanding value;
- materially useful triggers produce >=25% action rate;
- false/stale materially wrong alerts remain <5% during controlled pilot.

Kill/pivot signal:
- <15% watch creation after clear proposition;
- users consistently prefer incumbent price tools and see no incremental value.

Additional 2026-09-16 comparison check:
- ask every qualified participant which current tool/site they would otherwise use (e.g. Cenoteka/Idealno/ePonuda/merchant site/manual search);
- count NePropusti as incremental value only when the rule/state/alert flow changes behavior, reduces repeated checking, or enables a condition the baseline tool does not solve well enough.

## G2 — Sports where-to-watch
**Status: OPEN**

Pass candidate:
- 50–100 users, narrow entity set, 4 weeks;
- recurring useful actions and week-4 retained behavior;
- reliable/licensable broadcast data path identified.

Do not treat inexpensive fixture APIs as proof that Serbia-specific broadcast mapping is solved. Broadcast rights/schedule reuse remains a separate blocking unknown.

## G3 — Embedded partner / B2B2C
**Status: OPEN**

Pass candidate:
- 20 relevant partner pitches;
- >=5 credible pilot commitments;
- >=3 partners actually publish a hosted/embedded Watch surface.

Kill signal:
- <2 real commitments after 20 strong-fit pitches.

Partner interviews must explicitly test:
- why the partner would use NePropusti rather than an internal CRM/ecommerce alert feature;
- whether cross-site Watch identity or rule handling has measurable value;
- what ROI metric matters: recovered revenue, return visits, ticket conversion, restock conversion, qualified actions;
- integration friction and owner of ongoing support/data quality.

## G4 — Alert quality
**Status: BLOCKED by G1/G2**

Define and meet error budgets for stale/false/duplicate alerts.

Minimum source-quality discipline:
- every actionable field has provenance and freshness;
- product/variant matches below confidence threshold do not trigger cross-store alerts;
- loyalty/member-only prices are not presented as universally available;
- unresolved source conflicts suppress the alert rather than guessing.

## G5 — Retention
**Status: BLOCKED**

Must show repeated useful alert actions, not only signup/watch creation.

Retention must be interpreted by watch type:
- permanent follows (sports/team/artist/venue) can support recurring retained behavior;
- temporary commerce watches should be allowed to complete/expire after purchase rather than being misclassified as churn.

## G6 — Narrow MVP
**Status: BLOCKED**

Only winning wedge + winning product shape may enter production scope.

The current research does **not** authorize:
- a general comparison catalog;
- all-category consumer app;
- broad crawler fleet;
- native mobile app;
- regional rollout.

## G7 — Monetization
**Status: BLOCKED**

Pass only with real partner payment, real affiliate/CPC agreement, or actual premium purchase — not survey intent.

For B2B2C, payment must be tied to a concrete value metric rather than generic "notifications".

## G8 — Second vertical
**Status: BLOCKED**

Cross-category expansion requires evidence that it improves retention/economics without increasing mute/unsubscribe materially.

## G9 — Native mobile
**Status: BLOCKED**

Requires proven mobile-specific retention value beyond web/email/Telegram/web push.

## G10 — Regional expansion
**Status: BLOCKED**

Requires repeatable Serbia source operations, partner acquisition and unit economics.

## Current external evidence references

- Serbian Consumer Protection Act 2026: https://www.paragraf.rs/propisi/zakon-o-zastiti-potrosaca-2026.html
- Ministry — 35 large chains / daily price publication: https://must.gov.rs/vest/sr/21850/set-trgovinskih-zakona-uredjuje-trziste-donosi-transparentnost-i-fer-odnose-i-stiti-potrosace.php
- Serbian Open Data Portal retail datasets: https://data.gov.rs/sr/datasets/cenovnici/
- Cenoteka FAQ / threshold alerts: https://cenoteka.rs/najcesca-pitanja/
- ePonuda partner model: https://www.eponuda.com/partner
- Idealno current catalog/price surfaces: https://www.idealno.rs/

Use current source values at execution time; do not hard-code a single Idealno catalog/store count because different current surfaces can show different totals.
