# Trigger Taxonomy & Platform Thesis

## Platform thesis

NePropusti should be modeled around triggers, not verticals.

`WATCH RULE -> OBSERVATION -> STATE -> TRANSITION -> VERIFY -> MATCH -> ALERT -> ACTION`

## Core trigger families

- `NEW_MATCH`: a newly discovered item satisfies a saved rule.
- `THRESHOLD_CROSSED`: numeric condition becomes true.
- `AVAILABILITY_CHANGED`: unavailable -> available.
- `TIME_APPROACHING`: temporal deadline or start window reached.
- `STATUS_CHANGED`: rescheduled/cancelled/channel-added/etc.
- `CONTENT_CHANGED`: material terms or rules changed.
- `MILESTONE_REACHED`: tournament/competition stage condition becomes true.

## Permanent vs temporary watches

Permanent watches:
- team;
- athlete;
- artist;
- venue;
- brand.

Temporary watches:
- buy a TV;
- wait for a shoe size;
- job search;
- property search;
- travel fare.

Temporary watches should support expiry, snooze and “completed/purchased”.

## Why this abstraction matters

A shared trigger platform can support multiple verticals without forcing them into one launch. The architecture can be horizontal while the product remains vertical until cross-category behavior is proven.

## Kill condition for horizontal brand

If second-category adoption is weak and broad messaging reduces activation, keep shared infrastructure but split consumer surfaces/brands.
