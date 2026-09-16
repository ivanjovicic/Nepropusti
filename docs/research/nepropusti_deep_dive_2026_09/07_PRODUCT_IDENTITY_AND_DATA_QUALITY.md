# Product Identity and Data Quality

## Verified schema-level strength

Current Serbian Open Data Portal retail datasets describe fields including:
- category;
- product name;
- brand;
- barcode;
- unit;
- price;
- VAT;
- price-list type.

They are published as real-time CSV datasets under open-data terms for multiple retailers.

## Important limitation

This research runtime could verify dataset metadata/schema but could not reliably fetch and inspect raw CSV rows from all retailer resources.

Therefore it would be false precision to claim:
- X% barcode completeness;
- exact duplicate GTIN rate;
- package mismatch rate.

Those metrics remain **NP-VAL-001 empirical work**.

## Identity model

Use distinct entities:

`Product`
`Variant`
`Package`
`MerchantOffer`
`StoreAvailability`

Useful keys:
- GTIN/EAN when present;
- manufacturer model;
- normalized brand/name;
- size/color/volume;
- merchant SKU;
- package/unit quantity.

## Safety rule

No cross-store actionable alert if identity confidence is below threshold.

Never guess:
- same product from similar title only;
- loyalty eligibility;
- stock;
- shipping;
- exact variant.

## Strategic consequence

For the first B2B restock/size pilot, avoid cross-store entity resolution entirely.

Use the merchant's own stable product/variant ID.

This reduces data burden and improves reliability.
