# Embedded Widget, Extension & API

## Embedded Watch Button

Minimum conceptual API:

`createWatch(entity, trigger, threshold?, channel?)`

Partner context:
- partner id;
- canonical entity id or source id;
- current state;
- canonical action URL;
- signed source/webhook capability.

User context:
- explicit watch condition;
- channel;
- timing/frequency;
- expiry.

## Partner integration levels

### Level 0 — Link
Partner links to hosted NePropusti watch setup.

### Level 1 — JS widget
Embeddable branded/unbranded Watch button.

### Level 2 — Partner feed/webhook
Partner pushes state changes.

### Level 3 — SDK/API
Native integration plus attribution.

## Browser extension

Use as fallback:
- capture current URL;
- detect candidate entity;
- propose structured watch.

If confidence is low, generic page watch may be offered with clearly lower trust, but must never become the core source architecture.

## API

Future API:
- create/update/delete watch;
- list watches;
- emit observation/state change;
- fetch aggregate partner analytics.

## MCP

Future assistant use:
“Watch this laptop under €700.”
MCP calls structured Watch API; it does not replace the source/trust engine.
