# Data Sources, Licensing & Trust

## Principle

`Visible on the web` != `licensed for commercial reuse`.

Each source must have:
- acquisition mode;
- terms/license;
- refresh expectation;
- data ownership;
- attribution requirement;
- caching/storage rules;
- commercial display rights.

## Preferred hierarchy

1. partner webhook/feed;
2. official open data;
3. official regulator/organizer source;
4. licensed provider;
5. trusted aggregator with agreement;
6. permitted crawl;
7. generic page monitor fallback.

## Serbia structural advantage

The 2026 retail-price publication framework is unusually important because the Consumer Protection law requires machine-readable publishing and permits automated software collection for price comparison; datasets on data.gov.rs expose current retailer data under published dataset terms/licenses.

Before production, audit exact license per dataset and distinguish statutory access from downstream commercial-use terms.

## Sports blocking unknown

Broadcast mapping rights, logos, and schedule reuse need source-by-source review. Fixture API access does not imply broadcaster data rights.

## Giveaways

Regulator organizer/date data can establish official-source provenance. Detailed prize/rules data should still come from organizer rules.

## Source conflicts

Never silently pick.

Resolver considers:
- authority;
- freshness;
- source confidence;
- field-specific priority.

Suppress alert if conflict is materially unresolved.
