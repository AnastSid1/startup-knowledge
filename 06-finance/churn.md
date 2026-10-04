# Churn

> Churn is the rate at which customers (or revenue) leave over a period.

## What it means

Two core views:

| Type | Question | Example |
| --- | --- | --- |
| Logo churn | What % of customers canceled? | 5 of 100 customers leave → 5% |
| Revenue churn | What % of recurring revenue was lost from cancellations/contraction? | Lost $5k of $100k MRR → 5% |

**Gross revenue churn** looks at losses before expansion.  
**Net revenue churn** includes expansion; net can be negative when expansion exceeds losses (often discussed via net revenue retention >100%).

```text
Monthly logo churn ≈ Customers lost / Customers at start
```

## Why it matters

Churn compounds painfully. High growth cannot paper over a leaky bucket forever. Churn also drives [LTV](ltv.md) and influences valuation quality.

## When founders should care

- From the first cohort renewals/cancellations
- Before scaling acquisition
- When onboarding quality is uncertain
- Continuously after PMF as a core health metric

## How it works

### Approximate lifetime

```text
Average lifetime (months) ≈ 1 / monthly churn
```

2% monthly churn ⇒ ~50-month average lifetime (rough, assumes constant hazard).

### Diagnose churn

- never activated (onboarding failure)
- activated but weak habit
- lost champion
- poor fit ICP
- competitor displacement
- price value mismatch

Fixing “churn” without diagnosis wastes roadmap capacity.

## Practical example

MRR $100,000.

- cancellations lose $4,000
- downgrades lose $1,000
- expansions add $6,000

Gross revenue churn = 5%.  
Net new from existing base = +$1,000 (NRR style health).

Still investigate why $5k left — expansion elsewhere can mask a product problem in a segment.

## Common confusion

| Term | Difference |
| --- | --- |
| Retention | Inverse lens; see [retention](retention.md) |
| Logo vs revenue churn | Can tell opposite-looking stories |
| Churn vs contraction | Contraction is partial revenue loss |

## Related concepts

- [Retention](retention.md)
- [LTV](ltv.md)
- [Activation](activation.md)
- [Cohorts](cohorts.md)
- [Product-Market Fit](../01-product/product-market-fit.md)

## Further reading

- SaaS churn analysis guides from ChartMogul/ProfitWell-style educators
- First Round / operator posts on churn diagnosis
