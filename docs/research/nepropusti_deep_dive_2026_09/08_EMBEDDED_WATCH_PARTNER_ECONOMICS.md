# Embedded Watch Partner Economics

## Why a merchant might pay

Only if NePropusti produces measurable incremental value.

Candidate formula:

`incremental gross profit from recovered users - NePropusti fee > 0`

## Simple break-even examples

At €20 incremental gross profit per recovered order:

- €99/month requires about 5 incremental orders;
- €199/month requires about 10 incremental orders.

These are illustrative assumptions, not Serbian benchmark data.

## Integration ladder

### Level 0 — hosted link
Use for validation.
No platform plugin required.

### Level 1 — JS button
Merchant supplies:
- product/variant ID;
- current state;
- canonical URL.

### Level 2 — feed/API
Useful for many products/variants.

### Level 3 — webhook
Preferred for:
- inventory changed;
- price changed;
- promotion state.

### Level 4 — SDK / white-label
Only after multiple paying partners request it.

## Attribution

Minimal:
- watch ID;
- alert ID;
- signed/UTM redirect;
- return click;
- optional order/conversion webhook.

Do not require invasive cross-site tracking for MVP.

## Pricing experiment

Test:
- €99/month pilot;
- €199/month with analytics/volume;
- or qualified-action fee.

Avoid per-notification pricing as primary value signal; merchants pay for outcomes, not messages.
