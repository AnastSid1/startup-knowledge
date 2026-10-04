# Cohorts

> A cohort is a group of users or customers who started around the same time (or share another defining trait), tracked together to see how their behavior evolves.

## What it means

Instead of looking at blended totals, cohort analysis asks: “How did users who signed up in January behave over the next 12 weeks?”

Common cohort types:

- signup week/month cohorts
- first-purchase cohorts
- channel cohorts (paid vs organic)
- ICP segment cohorts

## Why it matters

Blended metrics hide truth. Overall MRR can rise while recent cohorts get worse. Cohorts reveal retention reality, payback timing, and whether product changes helped.

## When founders should care

- As soon as you have repeated signups over time
- When evaluating PMF
- When changing onboarding/pricing
- When computing empirical [LTV](ltv.md)

## How it works

### Retention cohort table (concept)

| Signup week | W0 | W1 | W4 | W8 |
| --- | --- | --- | --- | --- |
| Jan 6 | 100% | 42% | 28% | 24% |
| Jan 13 | 100% | 50% | 33% | 30% |

Flattening curves suggest a retained core. Continued decay to zero suggests weak fit.

### Revenue cohorts

Track each customer cohort’s recurring revenue over months, including expansion and churn.

## Practical example

After a new onboarding release, March cohorts show week-4 retention rising from 22% to 31%. Blended MAU barely moved that month because old users dominate — cohort view proves the win.

## Common confusion

Cohorts are not only for retention. You can cohort by sales win rate, payback, or invite rate too. Also, small cohorts are noisy — don’t overreact to n=12.

## Related concepts

- [Retention](retention.md)
- [Churn](churn.md)
- [LTV](ltv.md)
- [Activation](activation.md)
- [Product-Market Fit](../01-product/product-market-fit.md)

## Further reading

- Cohort analysis tutorials from product analytics educators
- SaaS revenue cohort charts in investor updates (good practice)
