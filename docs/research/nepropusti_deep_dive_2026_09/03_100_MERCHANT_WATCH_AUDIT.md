# 50-Merchant Public Watch-Feature Audit

The master prompt requested approximately 50–100 Serbian ecommerce sites.

This research package includes **50 merchant rows** in:
`data/merchant_watch_feature_audit.csv`

## Method limitation

This is a **public-source reconnaissance**, not a logged-in manual checkout/product-page test for all 50 merchants.

Statuses are deliberately conservative:

- `VERIFIED_PARTIAL`: a related feature such as Wishlist/Favorites/availability/CRM is publicly visible.
- `NOT_FOUND_PUBLIC`: no proactive item-condition Watch feature was found in accessible indexed evidence; **this is not proof it does not exist**.
- `UNKNOWN`: evidence was insufficient.

Do not convert UNKNOWN/NOT_FOUND into sales claims.

## Useful observed pattern

Among larger Serbian merchants, related primitives are common:
- wishlists/favorites;
- newsletters;
- loyalty;
- SMS/Viber/email marketing;
- stock/store availability.

What is much less consistently visible in public evidence is:
- explicit variant/size restock subscription;
- target-price condition;
- cross-channel item-specific Watch;
- portable watchlist across merchants;
- merchant-visible unmet-demand analytics.

## Important counterweight

WooCommerce/Shopify merchants can add these features cheaply via plugins.

Therefore merchant absence is not enough.

The pitch must prove one of:
- faster managed setup;
- better multi-trigger UX;
- better conversion attribution;
- portable user Watch identity;
- cross-channel delivery;
- demand intelligence.

## Best audit follow-up

NP-VAL-003 should convert 20 rows into **manual/interactive merchant audits** and explicitly document:
- current stack;
- current plugin/CRM;
- actual missing job;
- willingness to publish a live test.

The 50-row CSV is a lead/reconnaissance map, not proof of an untapped market.
