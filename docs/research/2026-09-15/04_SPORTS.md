# Sports / Where-to-Watch Analysis

## Recommended sports job

Do not build a live-score competitor.

Test:

> **Tell me when a team/player I care about plays, where I can legally watch it in Serbia, and alert me if the schedule or broadcaster changes.**

## Why it is attractive

- recurring frequency;
- permanent follows;
- habitual retention;
- clear timing;
- high urgency;
- notifications are naturally expected.

## Why it is risky

Fixture data is relatively easy. Reliable **geo-specific broadcast/stream data** is the hard layer.

API-Football publishes a $19/month Pro tier with 7,500 requests/day. Sportmonks starts at €29/month for 5 leagues and exposes extensive fixture/team/player data. Neither price point by itself solves Serbian broadcast rights mapping.

## Competitive defense

SofaScore/Flashscore can copy broadcaster labels. Therefore the defensible part cannot be only `TV_CHANNEL`.

Potential differentiators:
- source-provenance and freshness;
- multi-sport Serbian broadcast mapping;
- change alerts;
- partner embeds on clubs/publishers/broadcasters;
- unified watch identity with non-sports conditions.

## MVP test

50–100 users; only 5–10 high-interest entities:
- Red Star basketball;
- Partizan basketball;
- Serbia football/basketball;
- Djokovic;
- optionally F1.

Manually/semiautomatically send:
- fixture confirmation;
- broadcaster confirmation;
- one reminder;
- schedule/broadcast correction if changed.

Measure:
- follows per user;
- useful alert action;
- week-4 retention;
- false/stale alert rate;
- how often user would otherwise have searched.

## Gate

Do not scale sport until broadcast source rights and operational freshness are documented.
