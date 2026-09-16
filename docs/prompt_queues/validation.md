# NePropusti Validation Queue

Last aligned: 2026-09-16
Status: validation only — product implementation remains blocked until gates pass.

| ID | Status | Task | Gate |
|---|---|---|---|
| NP-VAL-001 | READY | Audit Serbian retail/open-price sources | G1 |
| NP-VAL-002 | READY | Commerce Watch user validation | G1 |
| NP-VAL-003 | READY | Embedded Watch partner validation | G3 |
| NP-VAL-004 | READY | Sports where-to-watch concierge | G2 |
| NP-VAL-005 | BLOCKED | Alert-quality automation pilot | G4 |
| NP-VAL-006 | BLOCKED | Paid partner / qualified-action test | G7 |
| NP-VAL-007 | BLOCKED | Cross-category test | G8 |

## Selection rule
Run NP-VAL-001/002/003 in parallel. NP-VAL-004 can run as a lower-cost parallel track. Do not substitute coding for missing user/partner evidence.

Current evidence addendum:
`docs/research/MARKET_EVIDENCE_REFRESH_2026_09_16.md`

## NP-VAL-001 — Audit Serbian retail/open-price sources

**Goal:** determine whether current Serbian public/partner price data is good enough for trustworthy commerce-state alerts rather than merely proving that CSV files exist.

Audit at least 10–15 strong-fit retailer datasets/sources.

For each capture:
- publisher/retailer;
- legal/reuse basis and dataset license;
- format/resource URL;
- update frequency and actual observed freshness;
- product title;
- brand;
- GTIN/EAN/barcode;
- merchant SKU if present;
- package/unit fields;
- regular/current/discount/previous price fields;
- store/location granularity;
- loyalty/member price distinction;
- promotion start/end fields;
- stock/availability if any;
- historical resources/snapshots;
- schema inconsistencies and missing values.

Required analysis:
- percentage of sampled rows with usable barcode/product identity;
- whether product variants/packages can be compared safely;
- whether the public data is enough for target-price / Price Truth alerts;
- what still requires merchant feed/API/partnership;
- which source fields must never be guessed.

Do not treat open data as a moat.

Output:
- reproducible source matrix;
- sample-quality findings;
- source/reuse evidence;
- G1 data-readiness recommendation;
- explicit unsupported fields (stock, loyalty price, shipping, etc.).

## NP-VAL-002 — Commerce Watch user validation

**Goal:** test whether NePropusti changes actual checking/purchase behavior beyond existing tools.

Scope:
- 50–100 qualified users;
- concrete purchase intent or recurring-purchase use case;
- max 3–5 real watches/user during pilot.

Test separately where possible:
- exact product target price;
- trusted/historical Price Truth context;
- restock/availability;
- FMCG/unit-price or recurring product use case.

For every participant record current substitute:
- Cenoteka;
- Idealno;
- ePonuda;
- merchant site/app;
- Google/manual checking;
- other.

Do not count NePropusti as incremental value merely because the participant likes alerts.

Measure:
- watch creation;
- why they created it;
- qualifying trigger frequency;
- useful action/click;
- purchase/contact proxy where available;
- repeated-checking behavior replaced;
- mute/stop/completed watch;
- false/stale alert reports;
- whether the current substitute already solves the job.

Pass candidate remains governed by `docs/VALIDATION_GATES.md`.

## NP-VAL-003 — Embedded Watch partner validation

**Goal:** prove or kill the B2B2C distribution thesis.

Pitch 20 strong-fit merchants/sites, prioritizing businesses that:
- have meaningful ecommerce/booking intent;
- lack strong existing watch/restock tooling or have measurable gaps;
- can expose one hosted/embedded Watch surface quickly;
- can measure return/conversion outcomes.

For each partner ask:
1. Why would you use NePropusti rather than your CRM/ecommerce alert stack?
2. Who owns the integration?
3. Who owns ongoing source/data correctness?
4. What outcome would justify payment?
5. What data/identity can you provide directly?
6. Would you actually publish a test surface?
7. What would stop procurement/integration?

Count as credible commitment only:
- named owner/contact;
- concrete test page/context;
- agreed next step/timing;
- willingness to measure outcomes.

Pass candidate:
- >=5 credible commitments;
- >=3 real hosted/embedded Watch surfaces.

Kill signal:
- <2 real commitments after 20 strong-fit pitches.

No production partner portal is authorized by this task.

## NP-VAL-004 — Sports where-to-watch concierge

**Goal:** test the retention job without building live-score infrastructure.

Scope:
- 50–100 users;
- narrow entity set;
- four weeks;
- manually/semiautomatically verified fixture/broadcast/reminder flow.

Track:
- follows/user;
- broadcast lookup/action;
- reminder usefulness;
- schedule/channel corrections;
- week-4 retained behavior;
- what existing sports app/site the alert replaced.

Must separately document:
- fixture-data source;
- Serbia-specific broadcaster source;
- commercial/reuse status;
- freshness/correction handling.

Cheap fixture API availability is not evidence that broadcast mapping is solved.

## NP-VAL-005 — Alert-quality automation pilot

Blocked until G1/G2 provide a real winning wedge/source set.

Automate only the smallest successful pilot path.

Required quality metrics:
- false alert rate;
- stale alert rate;
- duplicate rate;
- late alert rate;
- source conflict/suppression;
- action rate.

Do not automate unreliable sources to increase coverage.

## NP-VAL-006 — Paid partner / qualified-action test

Blocked until a partner pilot produces attributable user actions.

Ask for real payment/contract:
- SaaS/usage fee;
- qualified action/CPC/CPA;
- paid pilot;
- white-label/API where justified.

"Would pay" is not a pass.

## NP-VAL-007 — Cross-category test

Blocked until at least one wedge has retention/value evidence.

Offer a second category to activated users and measure:
- cross-adoption;
- retention change;
- mute/unsubscribe change;
- whether one brand still makes sense.

Do not force horizontal positioning if cross-category behavior is weak.
