# Notification & Retention Strategy

## Notification quality is the product

A delivered push is not success.

Track:
- precision;
- freshness;
- false-alert rate;
- duplicate rate;
- late-alert rate;
- action rate;
- mute rate.

## Explainable alert contract

Every alert should answer:
1. What changed?
2. Why did I get this?
3. How fresh/trusted is it?
4. What can I do now?

## Notification budget

Users have limited attention.

Defaults should differ by trigger:
- target price: instant only when condition becomes true;
- generic deals: digest;
- sport: confirmation/change/reminder;
- event: on-sale/critical change/reminder;
- giveaway: high-match + deadline.

## Temporary watches

Shopping/travel/listing watches should expire or be completed after purchase/goal.

## Activation

Signup is not activation.

Best candidate activation:
**first useful alert action**.

## North Star

**Useful Alert Actions per Weekly Active Follower**

Always expose vertical submetrics so a high-volume weak vertical cannot hide poor quality elsewhere.

## Delivery

Prefer build-vs-buy:
- FCM is no-cost for cloud messaging;
- OneSignal has a free tier and current Growth pricing from $19 platform fee plus usage;
- Knock offers advanced workflow/preference infrastructure.

Build source/matching/trust intelligence, not commodity push delivery.
