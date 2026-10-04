# Gross Margin

> Gross margin is the percentage of revenue left after direct costs of delivering the product or service.

## What it means

```text
Gross margin % = (Revenue − Cost of goods sold / cost to serve) / Revenue
```

Example: $100 revenue, $20 direct delivery cost → 80% gross margin.

For SaaS, COGS-like costs often include:

- hosting/infrastructure
- third-party model/API fees
- payment processing (sometimes)
- customer-specific onboarding labor if tightly tied to delivery
- support costs (policy varies; be consistent)

Do not hide all engineering in COGS — but do not pretend GPU/API costs are zero either.

## Why it matters

Gross margin determines how much fuel you have for sales, product, and R&D. Low margins make [CAC](cac.md) payback harder and limit scaling.

Software often targets high gross margins (for example 70–90%+), but AI-heavy or services-heavy models may run lower — especially early.

## When founders should care

- Pricing and packaging decisions
- Choosing vendors/models with usage costs
- Planning sales capacity (you can only spend what margin allows)
- Fundraising narratives about scalability

## How it works

Segment margins by product and customer type. A “good blended margin” can hide an unprofitable enterprise onboarding segment.

### AI example

| Item | Per customer / month |
| --- | --- |
| Price | $200 |
| Model/API cost | $60 |
| Infra | $10 |
| Gross profit | $130 |
| Gross margin | 65% |

If usage rises faster than pricing, margins compress — consider usage-based pricing or efficiency work.

## Practical example

A startup sells for $500/mo but includes white-glove onboarding that costs $2,000 in labor amortized poorly across short-lived customers. Reported hosting margin looks high; true contribution margin after onboarding is weak. They either productize onboarding or charge an implementation fee.

## Common confusion

| Term | Difference |
| --- | --- |
| Net margin | After all operating expenses |
| Contribution margin | Often after variable acquisition/delivery costs; define clearly |
| Burn | Cash spend; related but different |

## Related concepts

- [Unit Economics](../08-strategy/unit-economics.md)
- [LTV](ltv.md)
- [CAC](cac.md)
- [Payback Period](payback-period.md)
- [Business Model](../08-strategy/business-model.md)

## Further reading

- SaaS gross margin definitions from reputable finance/operator guides
- AI cost/margin posts from practitioners (fast-changing area)
