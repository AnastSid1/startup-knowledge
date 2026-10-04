# Unit Economics

> Unit economics measure whether a business makes money on a fundamental unit — usually a customer, account, or transaction — after the costs to acquire and serve it.

## What it means

Unit economics zoom in from company-level P&L to one unit’s profitability.

For SaaS, the unit is often a customer:

- revenue and gross profit per customer
- [CAC](../06-finance/cac.md)
- [LTV](../06-finance/ltv.md)
- [LTV:CAC](../06-finance/ltv-cac.md)
- [payback period](../06-finance/payback-period.md)

For marketplaces, the unit may be a transaction or an active buyer/seller.

Healthy unit economics mean growth can eventually pay for itself. Weak unit economics mean scaling spend accelerates losses.

## Why it matters

You can grow into a disaster. Unit economics tell you whether growth is valuable.

They also guide:

- channel choice
- pricing
- target [ICP](../02-customers/icp.md)
- funding needs and [runway](../06-finance/runway.md) planning

## When founders should care

- Before scaling paid acquisition
- When preparing Seed+ / Series A metrics
- When margins look fine overall but a segment is toxic
- When deciding enterprise vs SMB focus

Pre-PMF, directional unit economics matter more than precise dashboards. Post-PMF, precision matters more.

## How it works

### Core SaaS sketch

```text
Gross profit per customer / month = ARPU × gross margin %
CAC payback (months) ≈ CAC / monthly gross profit per customer
LTV ≈ (ARPU × gross margin %) / monthly churn   (simple model)
```

See detailed pages for assumptions and pitfalls.

### Segment your units

Average unit economics can hide the truth:

| Segment | CAC | Monthly GP | Payback | Verdict |
| --- | --- | --- | --- | --- |
| SMB self-serve | $180 | $45 | 4 months | Scale |
| Mid-market sales-assisted | $6,000 | $400 | 15 months | Careful |
| Bad-fit enterprise pilots | $20,000 | $250 | 80 months | Stop |

## Practical example

Customer pays $200/mo. [Gross margin](../06-finance/gross-margin.md) 80% → $160 monthly gross profit. CAC $960.

```text
Payback = 960 / 160 = 6 months
```

If monthly logo churn is 2.5%:

```text
Simple LTV ≈ 160 / 0.025 = $6,400
LTV:CAC ≈ 6400 / 960 ≈ 6.7x
```

That looks healthy — if churn and margin assumptions hold and expansion is ignored (expansion would make it better).

## Common confusion

| Mistake | Better approach |
| --- | --- |
| Using revenue instead of gross profit | Include cost to serve |
| Blended averages only | Segment by channel and ICP |
| Ignoring payback timing | Cash timing can kill you even with high LTV |
| Declaring victory pre-retention | LTV needs retention evidence |

## Related concepts

- [CAC](../06-finance/cac.md)
- [LTV](../06-finance/ltv.md)
- [LTV:CAC](../06-finance/ltv-cac.md)
- [Payback Period](../06-finance/payback-period.md)
- [Gross Margin](../06-finance/gross-margin.md)
- [Business Model](business-model.md)
- [Burn Rate](../06-finance/burn-rate.md)

## Further reading

- SaaS metrics guides from Bessemer, OpenView, and ChartMogul-style educators
- Sequoia / a16z financial planning primers
- Marketplace unit economics write-ups (contribution margin per transaction)
