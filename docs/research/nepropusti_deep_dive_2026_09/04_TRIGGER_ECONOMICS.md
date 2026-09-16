# Trigger Economics

Reproducible matrix:
`data/trigger_economics.csv`

## Core result

The strongest core trigger candidates are:

| Trigger | Analytical score |
|---|---:|
| SIZE_AVAILABLE | 8.08 |
| BACK_IN_STOCK | 8.03 |
| TICKETS_ON_SALE | 7.73 |
| PRICE_BELOW_X | 7.55 |
| PRICE_DROP_PERCENT | 7.19 |
| REAL_DISCOUNT | 6.73 |
| BROADCAST_CONFIRMED | 6.29 |

`DEADLINE_SOON` also scores highly, but it is a separate NePropusti Pro adjacency with different buyers and should not contaminate consumer-commerce validation.

## Why size/variant availability wins

It combines:
- urgency;
- clear state transition;
- high-intent purchase;
- direct partner ROI;
- natural fashion/footwear use case;
- no need for cross-store canonical matching to validate the first pilot.

## Why it is not a moat

WooCommerce/Shopify plugins already do restock.

The trigger is the **entry job**, not the defensibility.

## Recommended first experiment

One merchant.
One category.
One state:
`variant size unavailable -> size becomes available -> user alert -> merchant return -> attributable action`.

Do not test six triggers at once.
