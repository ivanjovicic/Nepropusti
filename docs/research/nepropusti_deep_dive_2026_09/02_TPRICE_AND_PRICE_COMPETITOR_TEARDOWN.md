# Tprice and Price Competitor Teardown

## Tprice

### Verified public facts

Open Data Portal publication (7 Sep 2026):
- 100+ cities;
- 100,000+ products;
- 5,000+ daily promotions/discounts;
- 25+ retail chains;
- up to 6 months of price history;
- name search and barcode scanning.

Current Tprice site:
- 50+ stores;
- 300K+ products;
- 400+ cities;
- Serbia and Croatia;
- 6 months of history.

The difference in counts is timing/product expansion, not a contradiction to resolve by choosing one number.

## Strategic impact

Tprice has already demonstrated:
`public retailer data -> normalization -> consumer app -> comparison/history/barcode`

This removes a major early-mover assumption from NePropusti.

## Cenoteka

Desired-price / discount-threshold alerts already exist.

Implication:
`PRICE_BELOW_X` is not a unique product.

## Idealno

Price comparison/history/discount context are mature user jobs.

Implication:
Do not make historical-price presentation the main product.

## ePonuda

Current partner page reports:
- 700+ merchant partners;
- 5M+ active offers;
- four markets;
- merchant catalog/feed integration;
- CPC monetization.

Implication:
NePropusti should not compete as another traffic/catalog aggregator.

## Merchant-native stack

WooCommerce official marketplace already has:
- $59/year Back In Stock extension;
- $49/year Notify Me Plus with restock + price drop + new arrivals;
- $49/year Price Drop Notifier with target price/percentage threshold.

Omnisend provides low-cost email/web-push/SMS/custom-event automation.

## Conclusion

Price comparison, price history, threshold alerts, delivery infrastructure and basic restock are **commodity building blocks**.

The surviving question is:

> Can one merchant-embedded Watch layer recover more intent, support more useful rules and create portable user value with lower operational friction than the merchant's existing plugin/CRM stack?
