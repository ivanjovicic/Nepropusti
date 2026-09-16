# Executive Decision

Research cut-off: **2026-09-16**

## Verdict

**CONTINUE, BUT NARROW WEDGE**

NePropusti still deserves validation, but the deep dive weakens the previous broad `Commerce Watch / Price Truth` thesis.

The strongest updated formulation is:

> **NePropusti is a merchant-distributed intent-recovery layer for user-requested state changes — start with stock/size/variant availability, prove measurable return actions, and only later earn a portable cross-site Watch identity.**

## Five kill questions

1. **Do existing products already solve the highest-value triggers?**  
   Yes, often. WooCommerce and Shopify ecosystems already offer cheap restock/price alerts, while Tprice/Cenoteka/Idealno/ePonuda cover price/comparison jobs. This kills “alerts themselves” as a moat.

2. **Would merchants embed a third-party Watch surface?**  
   Unknown. This remains the most important business question. Existing plugins/CRM are cheap, so NePropusti needs either lower integration friction or materially better ROI/cross-site value.

3. **Can trusted state be maintained without becoming a data-ops company?**  
   Only if the winning path moves toward merchant feed/webhook for stock/variant state. Broad crawling/open-data normalization alone creates too much ongoing identity/quality work.

4. **Does one portable cross-site Watch identity create recurring consumer value?**  
   Plausible, not proven. It is a later moat candidate, not an MVP assumption.

5. **Is monetization strong enough for partner sales?**  
   Plausible at ~€99–199/month or outcome-linked pricing if recovered revenue is measurable. No payment evidence exists yet.

## Tprice changes the thesis

The Serbian Open Data Portal published Tprice on 7 September 2026 with 100k+ products, 25+ chains, 5k+ daily promotions and up to six months of history. Tprice's own current site now claims 300k+ products, 50+ stores and Serbia + Croatia.

Therefore:

**Open-price ingestion + barcode + price history + comparison is already becoming commodity.**

NePropusti should not attempt to win by being a better grocery price catalog.

## Strongest trigger

The trigger-economics model ranks:

1. **SIZE_AVAILABLE — 8.08/10**
2. **BACK_IN_STOCK — 8.03/10**
3. `DEADLINE_SOON` — 7.77/10, but this belongs to separate NePropusti Pro research.
4. `TICKETS_ON_SALE` — 7.73/10
5. `PRICE_BELOW_X` — 7.55/10

These are analytical scores, not empirical conversion data.

### Why size/restock wins for core validation

- immediate user intent;
- clear event/state;
- direct merchant revenue attribution;
- high value in footwear/fashion/specialist stock;
- does not require cross-store product matching to prove the first B2B value;
- can move from manual/hosted pilot to merchant webhook/feed.

The weakness: restock itself is commodity. The product must be **managed intent recovery + portable rules/identity + measurable ROI**, not “we send back-in-stock email”.

## First partner ICP

**Mid-market Serbian fashion/footwear ecommerce merchant with meaningful size/variant stock churn, enough traffic to create waitlists, and incomplete item-level alert automation.**

Prefer:
- owner/ecommerce manager can approve a pilot;
- WooCommerce/custom stack;
- one product/variant can be integrated quickly;
- merchant can expose inventory state and conversion/postback;
- no enterprise procurement.

## Identity recommendation

Do not insist that NePropusti owns the customer.

Initial model:

> **Merchant owns the customer relationship by default; NePropusti is processor/service layer; user can optionally upgrade to a portable NePropusti Watch identity.**

Mandatory NePropusti accounts would increase activation friction and partner resistance.

## Updated score

Previous portfolio score: **7.22/10**  
Deep-dive score: **6.83/10**

The score drops because:
- Tprice quickly eroded the open-price differentiation;
- cheap merchant-native WooCommerce/Shopify alert tooling is widespread;
- CRM/email/push infrastructure is inexpensive;
- data/partner operations remain heavy;
- willingness-to-pay is still hypothetical.

## Maximum defensible score after 90 days

Normal strong validation could move it to roughly **7.4–7.6**.

It could approach **~8.0** only with unusually strong proof:
- ≥5 credible partner commitments;
- ≥3 live partner Watch surfaces;
- ≥3 real paying partners around €99–199/month or equivalent outcome pricing;
- user activation ≥30%;
- useful triggered action ≥25%;
- materially wrong/stale alerts <5%;
- at least two partners ask to continue/expand;
- partner data/webhooks reduce ongoing data burden;
- evidence that the portable/cross-site layer produces value beyond a €49–59 plugin.

## Could it replace AgentsWatch as portfolio #1?

**Not today.**

AgentsWatch deep-dive score is currently 7.80.

NePropusti should replace it only if the above commercial evidence is achieved while AgentsWatch fails its external/commercial gate.

# IF THIS WERE MY MONEY

**Would I spend the next 6–12 months on NePropusti?** ONLY IF SPECIFIC GATES PASS.

**Strongest user problem:** high-intent user repeatedly checks whether a specific variant/stock/condition became actionable  
**Strongest trigger:** SIZE_AVAILABLE / BACK_IN_STOCK  
**First partner ICP:** mid-market Serbian fashion/footwear ecommerce  
**Best product shape:** merchant-embedded/hosted Watch + hybrid optional portable identity  
**Reason partner pays:** measurable recovered revenue and demand insight without building/operating rule/delivery logic  
**Consumer role:** utility identity/watchlist, not destination content app  
**Data advantage:** 2026 machine-readable retail data is a useful input/timing tailwind, not a moat  
**Moat candidate:** partner network + portable Watch identity + trusted state/action history + privacy-safe aggregate demand  
**Biggest competitor:** merchant-native CRM/plugin stack for B2B; Tprice/Idealno/Cenoteka/ePonuda for price jobs  
**Biggest operating risk:** data correctness + partner integration/support overwhelms SaaS leverage  
**Highest-value experiment next week:** 10 merchant interviews using one clickable `Notify me for size/restock` hosted pilot and ask for a real product-page test  
**Score today:** 6.83/10  
**Maximum defensible score after 90 days:** 7.5 normally; ~8.0 only with unusually strong paid/live-pilot evidence  
**Could it replace AgentsWatch as portfolio #1?** Yes only if it proves paid partner distribution/ROI while AgentsWatch fails external value/WTP gates.

**NEPROPUSTI DECISION: CONTINUE, BUT NARROW WEDGE**
