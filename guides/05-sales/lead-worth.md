# Lead Worth

> Lead worth is the expected economic value of a lead entering your funnel, based on conversion probabilities and the value of a won customer.

## What it means

Lead worth answers: “How much can I afford to pay for a lead (or click, or MQL) and still have healthy economics?”

It connects marketing spend to revenue reality.

Basic expected-value idea:

```text
Lead worth ≈ P(lead → customer) × Customer gross profit value
```

For subscription businesses, customer value is often related to [LTV](../06-finance/ltv.md) or first-year gross profit, depending on how conservative you want to be.

This is related to, but distinct from, [product worth](../01-product/product-worth.md) (value to the customer). Lead worth is value to *your company* of a prospect.

## Why it matters

Without lead worth math, teams either:

- underinvest in channels that would work, or
- overpay for junk leads that never convert

It also improves debates between marketing and sales: not all leads are equal; ICP-fit leads are worth more.

## When founders should care

- Running paid acquisition
- Buying lists, sponsorships, or partner leads
- Setting SDR capacity and lead SLAs
- Comparing channels with different conversion rates

## How it works

### Worked example

Assumptions:

- lead → qualified opp: 30%
- opp → closed-won: 20%
- overall lead → customer: 0.30 × 0.20 = 6%
- LTV gross profit: $4,000
- target LTV:CAC = 3x ⇒ max CAC = $4,000 / 3 ≈ $1,333

```text
Max affordable cost per lead ≈ max CAC × P(lead → customer)
= $1,333 × 0.06 ≈ $80
```

If a webinar lead costs $120 and converts at the same rate, economics fail unless conversion or LTV is better for that channel.

### Segment lead worth

| Lead type | Lead → customer | GP LTV | Approx lead worth |
| --- | --- | --- | --- |
| ICP inbound demo request | 15% | $6,000 | $900 |
| Generic ebook download | 1% | $3,000 | $30 |
| Partner-referred ICP | 18% | $6,000 | $1,080 |

## Practical example

A startup buys LinkedIn leads at $70 each. Blended close rate is 2%. LTV GP is $3,500. Expected value ≈ $70? Wait:

```text
Expected GP per lead = 0.02 × $3,500 = $70
Cost per lead = $70
```

That is roughly break-even before sales salaries and cash-payback timing — usually too tight. They either improve targeting/conversion or cut the channel.

## Common confusion

| Term | Difference |
| --- | --- |
| Product worth | Value created for customer |
| CAC | Cost per acquired customer; lead worth helps set lead costs consistent with CAC targets |
| MQL score | Operational ranking; lead worth is economic expected value |
| CPL | What you pay; lead worth is what it’s worth |

## Related concepts

- [Product Worth](../01-product/product-worth.md)
- [CAC](../06-finance/cac.md)
- [LTV](../06-finance/ltv.md)
- [LTV:CAC](../06-finance/ltv-cac.md)
- [Conversion Rate](../06-finance/conversion-rate.md)
- [Paid Acquisition](../04-growth/paid-acquisition.md)
- [ICP](../02-customers/icp.md)

## Further reading

- Performance marketing expected-value models
- SaaS funnel economics from OpenView / Bessemer-style metrics guides
- Sales ops writing on lead scoring vs economics
