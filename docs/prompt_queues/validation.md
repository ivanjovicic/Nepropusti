# NePropusti Validation Queue

Last aligned: 2026-09-16
Status: validation only — product implementation remains blocked until gates pass.

Latest decision research:
`docs/research/nepropusti_deep_dive_2026_09/00_EXECUTIVE_DECISION.md`

| ID | Status | Task | Gate |
|---|---|---|---|
| NP-VAL-003 | READY — PRIMARY | Merchant size/variant/restock partner validation | G3 |
| NP-VAL-002 | READY — PRIMARY | User behavior on live/high-fidelity size/restock Watch | G1 |
| NP-VAL-001 | READY — SUPPORTING | Audit Serbian retail/open-price sources | G1 / later price conditions |
| NP-VAL-004 | READY — LOWER PRIORITY | Sports where-to-watch concierge | G2 |
| NP-VAL-005 | BLOCKED | Alert-quality automation pilot | G4 |
| NP-VAL-006 | BLOCKED | Paid partner / qualified-action test | G7 |
| NP-VAL-007 | BLOCKED | Cross-category / portable identity test | G8 |

## Selection rule

Run NP-VAL-003 and NP-VAL-002 as the highest-information work. NP-VAL-001 remains useful supporting evidence. NP-VAL-004 can continue only as a low-cost parallel concierge.

Do not substitute coding for missing user/partner evidence.

## NP-VAL-003 — Merchant size/variant/restock partner validation

**Goal:** prove or kill merchant-distributed intent recovery.

Audit/pitch 20 strong-fit merchants, prioritizing mid-market fashion/footwear and then baby/toys/specialist retail.

For each partner capture:
- current platform/stack if known;
- wishlist/favorites;
- existing back-in-stock/size alerts;
- CRM/email/SMS/Viber/push tooling;
- current workaround;
- owner/ecommerce decision maker;
- one concrete product/variant context for a pilot;
- ability to provide canonical product/variant ID;
- ability to provide stock transition through feed/webhook/manual pilot;
- ability to measure alert return/action/conversion.

Mandatory question:
> Why would you use NePropusti rather than a €49–59 plugin or your existing CRM?

Count as credible commitment only:
- named owner/contact;
- concrete test page/context;
- agreed next step/timing;
- willingness to publish a real surface;
- willingness to measure outcomes.

Pass candidate:
- >=5 credible commitments;
- >=3 live hosted/embedded Watch surfaces.

Kill signal:
- <2 real commitments after 20 strong-fit pitches.

No production partner portal/plugin is authorized by this task.

## NP-VAL-002 — Size/restock user validation

**Goal:** test whether a user actually delegates repeated checking and acts when the requested variant becomes available.

Primary test:
`SIZE_AVAILABLE` / `BACK_IN_STOCK`

Pilot experience may be hosted/no-code.
No mandatory NePropusti account.

Scope:
- 50–100 qualified users across real/high-fidelity merchant contexts;
- max 1–3 meaningful active watches/user in first pilot;
- exact size/variant/product state captured explicitly.

Measure:
- watch creation;
- current substitute/manual behavior;
- trigger frequency;
- useful return click/action;
- purchase/contact proxy where available;
- time-to-action;
- false/stale/late alert;
- completed watch;
- repeat watch creation;
- user preference for merchant-only vs portable identity.

Strong candidate signals remain governed by `docs/VALIDATION_GATES.md`.

Secondary price-threshold tests may be added only if they do not dilute the primary trigger experiment.

## NP-VAL-001 — Audit Serbian retail/open-price sources

**Goal:** establish trustworthy source/reuse/data-quality facts for supporting price conditions; do not use this task to justify a comparison-catalog build.

Audit at least 10–15 strong-fit retailer datasets/sources.

For each capture:
- legal/reuse basis and license;
- resource URL/format;
- freshness;
- product title/brand/barcode/unit;
- price fields;
- store/location granularity;
- loyalty distinction;
- promotion dates;
- stock if any;
- history/snapshots;
- schema/missing-value issues.

Required empirical outputs:
- actual sampled barcode completeness;
- duplicate/identity problems;
- safe vs unsafe cross-store matches;
- exact fields that still require merchant feed/API.

Do not infer stock from price files.

## NP-VAL-004 — Sports where-to-watch concierge

**Goal:** test retention without building live-score infrastructure.

Scope:
- 50–100 users;
- narrow entity set;
- four weeks;
- manually/semi-automatically verified fixture/broadcast/reminder flow.

Must separately document fixture source, Serbia-specific broadcaster source, commercial/reuse status and correction/freshness handling.

Do not automate until rights/data path and payer role are credible.

## NP-VAL-005 — Alert-quality automation pilot

Blocked until G1/G3 provide a real winning merchant/trigger/source set.

Automate only the smallest successful pilot path.

Required metrics:
- false alert;
- stale alert;
- late alert;
- duplicate;
- source conflict/suppression;
- action rate;
- partner support incidents.

Prefer merchant webhook/feed over scraping where possible.

## NP-VAL-006 — Paid partner / qualified-action test

Blocked until a live partner pilot creates attributable actions.

Ask for real payment/contract:
- paid pilot;
- SaaS fee;
- qualified action/CPA where appropriate;
- white-label/API only when requested.

Candidate test bands such as €99–199/month are hypotheses.

`Would pay` is not a pass.

A strong 90-day promotion signal is >=3 real paying partners/paid pilots tied to measured value.

## NP-VAL-007 — Portable identity / cross-category test

Blocked until one merchant wedge has proven behavior and partner value.

Test:
- second merchant watch adoption;
- optional portable NePropusti identity uptake;
- second category only later;
- retention change;
- mute/unsubscribe change;
- partner acceptance of identity model.

Do not force one consumer brand/network effect if behavior does not support it.
