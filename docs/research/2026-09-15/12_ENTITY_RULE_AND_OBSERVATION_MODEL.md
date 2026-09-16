# Entity, Rule & Observation Model

## Canonical primitives

### Entity
A thing the user can follow: product variant, team, athlete, artist, venue, organizer, brand.

### Opportunity/Event
A stateful occurrence: fixture, event, giveaway, offer.

### SourceIdentity
Mapping from canonical entity to a source's identifier.

### Observation
Immutable source fact at a point in time.

### State
Materialized best-current view.

### Transition
Change between states.

### WatchRule
User condition evaluated against a state/transition.

### AlertCandidate
Potential alert before trust/frequency/policy gates.

## Example commerce

`Product -> Variant -> MerchantOffer -> PriceObservation -> PriceState -> THRESHOLD_CROSSED`

## Example sports

`Team -> Fixture -> BroadcastObservation -> FixtureState -> BROADCAST_CONFIRMED`

## Rule DSL

Initial operators:
- EQ/IN;
- LT/LTE/GT/GTE;
- CHANGED;
- BECAME_AVAILABLE;
- NEW_MATCH;
- BEFORE;
- WITHIN_RADIUS;
- PERCENT_DROP.

Do not make arbitrary scripting public in MVP.

## State history

Immutable observations are critical. They make price history, corrections, source disputes and schedule changes auditable.
