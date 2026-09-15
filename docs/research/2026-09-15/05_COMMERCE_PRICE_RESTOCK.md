# Commerce, Price Truth & Restock

## Strategic finding

Commerce is the most important new addition because Serbia's 2026 regulatory/data environment materially lowers one historical barrier: access to current machine-readable retail price data.

The Ministry stated on 31 Aug 2026 that 35 large retail chains are now subject to daily price-list publication rules. The 2026 Consumer Protection framework requires published machine-readable price lists, real-time updates when prices change, and explicitly requires enabling automated software tools to collect price data for comparisons.

Open-data datasets already expose CSV resources with combinations of category, product name, brand, barcode, unit and price fields; multiple datasets state real-time frequency and historical/monthly snapshots.

## What this does NOT mean

It does not automatically create a product catalog, stock truth, ecommerce checkout, shipping cost or clean cross-retailer product identity.

## Strongest commerce wedge

### Price Truth / verified deal intelligence

Not:
`price comparison`.

Instead:
- what is the current observed price?
- what is the applicable legal/reference previous-price concept?
- what is the historical observed low?
- is the claimed discount materially unusual?
- did the user's threshold become true?

## Direct competition

- Idealno already has price-drop notification and price movement.
- Cenoteka already supports desired-price / discount-threshold alerts.
- ePonuda has a large merchant network and CPC economics.

Therefore:
`Notify me under X` alone is commodity.

## Potential differentiation

1. cross-retailer state normalization;
2. transparent provenance;
3. historical truth/explainability;
4. embedded partner Watch button;
5. cross-domain watch identity;
6. rule engine beyond a single product page;
7. combination of price + restock + coupon + time expiry.

## Restock

Restock may be stronger than price-drop for:
- fashion sizes;
- limited electronics;
- tickets;
- high-demand launches.

Shopify's app ecosystem currently lists dozens of stock-alert apps with price-drop features; leading products sell on recovered revenue and embedded `Notify Me` widgets. This is strong B2B validation of the pattern.

## Required product identity

Never compare across retailers unless confidence is adequate.

Canonical model:
`Product -> Variant -> Package -> GTIN/EAN -> MerchantOffer`.

## Pilot categories

Run two separate pilots:

### High-ticket
electronics / appliances / baby gear.

Higher transaction value, lower purchase frequency.

### FMCG recurring
coffee / diapers / detergent / pet food.

Higher frequency, lower monetization per action; barcode/unit-price are more useful.

Do not mix success criteria.

## Hard gates

- dataset/reuse audit;
- identity accuracy;
- freshness;
- legal wording of “real discount”;
- affiliate/CPC/partner monetization validation.
