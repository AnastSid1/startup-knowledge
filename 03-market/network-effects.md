# Network Effects

> A network effect exists when a product becomes more valuable to each user as more users join or participate.

## What it means

In a network-effect business, usage creates value for other users — not only for the company.

Classic forms:

| Type | Idea | Example pattern |
| --- | --- | --- |
| Direct | More users ↔ more value for same-side users | Messaging apps |
| Indirect / two-sided | More supply helps demand and vice versa | Marketplaces |
| Data network effects | More usage improves product quality for all | Fraud models, recommendations |
| Local | Value densifies in a city/graph cluster | Ride-hail liquidity in a city |
| Platform | More complementary integrations increase value | App ecosystems |

Not every social or collaborative feature is a true network effect. If value does not increase with network size, it may just be a useful multiplayer feature.

## Why it matters

Strong network effects can create powerful [moats](moat.md): winners take more share because the product with the densest network is simply more useful.

They also create cold-start problems: early networks are weak, so [wedge](../01-product/wedge.md) and density strategies matter.

## When founders should care

- Designing marketplaces, social products, collaboration tools, platforms
- Choosing geography/segment launch order (liquidity first)
- Evaluating defensibility in fundraising
- Deciding whether [virality](../04-growth/virality.md) and network effects are related or distinct in your model

## How it works

### Density over vanity scale

10,000 users scattered worldwide may create zero network value.  
1,000 users in one profession in one city may create a lot.

### Cross-side vs same-side

Marketplace:

```text
More buyers → better for sellers → more sellers → better for buyers
```

Collaboration SaaS:

```text
More teammates in a workspace → better for each teammate
```

### Negative network effects

Congestion, spam, low-quality supply, or noisy feeds can reduce value as the network grows. Moderation and quality controls are part of network strategy.

## Practical example

A freelance marketplace for specialized Shopify developers.

**Weak launch:** open globally to all freelancers and all merchants → thin liquidity everywhere.

**Network-aware launch:**

1. Recruit 50 vetted Shopify Plus experts in North America.
2. Acquire merchants with Shopify Plus hiring needs in the same market.
3. Ensure fast match rates and reviews.
4. Expand to adjacent skills after density is real.

As reviews and successful hires accumulate, merchants prefer the marketplace with proven specialists — a network + brand combination.

## Common confusion

| Term | Difference |
| --- | --- |
| Virality | Growth mechanism via sharing; not identical to network value |
| Multiplayer features | May help retention without true network compounding |
| Economies of scale | Cost-side advantage; network effects are value-side |
| Data moat | Overlaps when data improves with network usage |

## Related concepts

- [Moat](moat.md)
- [Virality](../04-growth/virality.md)
- [Flywheels](../04-growth/flywheels.md)
- [Growth Loops](../04-growth/growth-loops.md)
- [Data Moat](data-moat.md)
- [Wedge](../01-product/wedge.md)

## Further reading

- NFX Network Effects Manual (conceptual reference)
- Marketplace liquidity writing from a16z and operators
- Platform strategy classics (Eisenmann, Parker, Van Alstyne)
