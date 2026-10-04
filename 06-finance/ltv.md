# LTV (Customer Lifetime Value)

> LTV estimates the total gross profit (sometimes revenue) a customer generates over their entire relationship with your company.

## What it means

A simple SaaS model:

```text
LTV ≈ (ARPU × Gross margin %) / Monthly churn rate
```

Example:

- ARPU = $100/mo
- Gross margin = 80% → $80 monthly gross profit
- Monthly churn = 2.5%
- LTV ≈ 80 / 0.025 = **$3,200**

This model assumes constant ARPU and churn — useful for direction, not destiny.

More advanced models include expansion, contraction, discounting cash flows, and cohort-specific retention curves.

## Why it matters

LTV sets an upper bound on rational acquisition spend. Without LTV thinking, teams scale channels that cannot pay back.

LTV also highlights retention and monetization as growth levers — not only new logos.

## When founders should care

- When setting CAC targets
- When comparing segments/channels
- After you have enough retention data to avoid fantasy math
- In pricing and expansion roadmap decisions

Be careful computing LTV with two months of data and declaring victory.

## How it works

### Revenue LTV vs gross-profit LTV

Prefer **gross-profit LTV** for unit economics. Revenue LTV overstates what you can spend on CAC.

### Expansion-aware view

If customers expand, effective LTV rises. Net revenue retention above 100% can make “logo churn” less scary — but logo churn still matters for learning and concentration risk.

### Cohort method (better)

Track each cohort’s cumulative gross profit over time and watch the curve approach a plateau. That empirical LTV beats a formula with guessed churn.

See [cohorts](cohorts.md).

## Practical example

SMB segment:

- ARPU $80, margin 85%, monthly churn 3.5% → LTV ≈ 68 / 0.035 ≈ $1,943

Mid-market:

- ARPU $600, margin 80%, monthly churn 1.2% → LTV ≈ 480 / 0.012 = $40,000

These segments can support very different sales motions and CAC.

## Common confusion

| Mistake | Better |
| --- | --- |
| Using 1/churn with unstable churn | Wait for cohort evidence |
| Ignoring margin | Use contribution/gross profit |
| Lifetime in years guessed from vibes | Use retention curves |
| Confusing LTV with [product worth](../01-product/product-worth.md) | One is company economics; one is customer value |

## Related concepts

- [CAC](cac.md)
- [LTV:CAC](ltv-cac.md)
- [Churn](churn.md)
- [Retention](retention.md)
- [Gross Margin](gross-margin.md)
- [Cohorts](cohorts.md)

## Further reading

- SaaS LTV critiques and best practices from finance operators
- Cohort-based retention analysis guides
