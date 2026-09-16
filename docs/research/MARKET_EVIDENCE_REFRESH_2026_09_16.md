# NePropusti Market Evidence Refresh — 2026-09-16

Status: current evidence addendum
Purpose: tighten the evidence behind the commerce/Embedded Watch thesis without changing validation-first governance.

## Confirmed current findings

### 1. Serbia retail-price data is a real timing advantage

The 2026 Serbian consumer-protection framework requires machine-processable price publication, real-time updates and support for automated software collection for comparison.

The Ministry states that the daily publication regime now covers 35 large retail chains.

Current Open Data Portal examples expose real-time CSV data with fields such as:
- product/category;
- brand;
- barcode;
- unit;
- price.

Some datasets expose historical/monthly snapshot resources and are published under the Serbian Open Data License.

### 2. This is not a moat by itself

The same legal/open data can be used by competitors.

Therefore NePropusti must not position raw price access as its defensible advantage.

The value to validate is:

`trusted source -> canonical state -> user rule -> meaningful transition -> alert -> measurable action`

### 3. Price alerts are already competitive

Cenoteka already supports desired-price / discount-threshold notifications.

Idealno already exposes large-scale price-comparison and price-movement/discount surfaces.

Current Idealno surfaces can show different live catalog/store totals, so documentation should not hard-code one exact count without a dated snapshot.

### 4. ePonuda is both competitor and market proof

ePonuda reports:
- 700+ merchant partners;
- 5M+ active offers;
- multi-country regional presence.

This supports the thesis that merchants will pay for high-intent shopping traffic, but does **not** prove they will pay NePropusti.

### 5. Embedded Watch remains the highest-value product-shape hypothesis

The B2B2C question is not:

> Do merchants like notifications?

It is:

> Will a merchant let NePropusti own or co-own the Watch/rule relationship because it produces measurable incremental return traffic/conversion more cheaply or more effectively than the merchant's existing CRM/ecommerce stack?

This must be tested with real integration commitments.

## Required validation implications

1. Every commerce user test must record the current substitute tool/workaround.
2. Every partner pitch must ask why internal CRM/merchant alert tooling is insufficient.
3. Open-price data should be audited for product identity, store scope, loyalty/member pricing, history and freshness before production use.
4. A target-price alert alone is not sufficient product differentiation.
5. Wrong/stale price and identity-match alerts must have explicit error budgets.
6. Do not enter sports implementation until a licensable Serbia-specific broadcast-data path is found.

## Sources

- Serbian Consumer Protection Act 2026: https://www.paragraf.rs/propisi/zakon-o-zastiti-potrosaca-2026.html
- Ministry — 35 large chains: https://must.gov.rs/vest/sr/21850/set-trgovinskih-zakona-uredjuje-trziste-donosi-transparentnost-i-fer-odnose-i-stiti-potrosace.php
- Open Data Portal retail datasets: https://data.gov.rs/sr/datasets/cenovnici/
- Cenoteka FAQ: https://cenoteka.rs/najcesca-pitanja/
- ePonuda Partner: https://www.eponuda.com/partner
- Idealno: https://www.idealno.rs/

Use fresh values at execution time because retailer/data/catalog coverage can change.
