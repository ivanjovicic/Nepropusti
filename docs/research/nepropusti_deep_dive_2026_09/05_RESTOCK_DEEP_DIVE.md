# Restock / Size Availability Deep Dive

## Why stronger than generic price-drop for the first partner pilot

### User intent
The user cannot buy because the exact variant is unavailable.

### Merchant intent
The merchant already paid to acquire the visitor and lost conversion due to inventory state.

### Trigger truth
Inventory transition is conceptually binary and easier to explain than “real discount”.

### Attribution
A post-alert click/order can be associated with a watch ID.

## Best initial categories

1. footwear;
2. fashion;
3. baby/toys;
4. gaming/collectibles;
5. selected specialist retail.

## Biggest weakness

Restock is already a cheap plugin feature.

Therefore NePropusti must not sell:
“we can email people when stock returns.”

It must test:
- hosted/embedded setup without internal development;
- variant-level rule handling;
- email + optional other service channels;
- waitlist/demand dashboard;
- conversion attribution;
- optional portable cross-store user profile.

## Merchant-data model

Best source:
merchant webhook/feed.

Avoid first-pilot dependence on:
- scraping stock labels;
- inferred inventory;
- generic page diff.

## Product minimalism

Pilot UI:
`Obavesti me kada broj 42 bude dostupan`

Input:
email or Telegram destination.

No mandatory account.

Backend can initially be manual/no-code/concierge if needed to prove behavior.
