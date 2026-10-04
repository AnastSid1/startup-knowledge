# Data Moat

> A data moat exists when proprietary data makes your product better in a way competitors cannot easily replicate by buying the same commodity inputs.

## What it means

Many companies say they have a data moat. Few do.

A real data moat usually requires:

1. **Unique data access** — data others cannot simply buy or scrape equally well
2. **Feedback loop** — more usage creates better data, which creates better product, which attracts more usage
3. **Productized learning** — models, benchmarks, or automations that turn data into customer outcomes
4. **Durability** — the advantage persists as models and vendors commoditize

If your “data” is generic web text or the same CRM fields every competitor can import, you probably have a feature, not a moat.

## Why it matters

As AI capabilities commoditize, defensibility often shifts to proprietary workflows and proprietary data. Investors and operators look for closed loops:

```text
more customers → more unique data → better predictions/automation → more customers
```

This overlaps with [network effects](network-effects.md) when each user’s data improves the product for others.

## When founders should care

- Building AI or marketplace products that improve with volume
- Deciding what data to capture from day one
- Evaluating whether an integration strategy creates exclusive signal
- Pitching defensibility beyond “we fine-tuned a model”

## How it works

### Questions that test a data moat claim

- Can a competitor with the same foundation model match our quality in 3 months?
- What data do we have that customers cannot export to a rival tomorrow?
- Does quality improve measurably with scale in a specific domain?
- Are there privacy, contractual, or operational barriers that keep the data proprietary?

### Weak vs strong examples

| Weak | Stronger |
| --- | --- |
| “We train on public internet data” | Anonymized outcomes from thousands of completed industry workflows |
| “Users upload docs” (easily moved) | Labeled decision results tied to proprietary taxonomy over years |
| Vanity dashboards | Predictive models with proven lift competitors cannot calibrate |

## Practical example

A claims automation startup for insurers:

- every claim processed creates labeled outcomes (approved, denied, appealed, fraud flags)
- models improve triage accuracy as volume grows in each insurance line
- carriers see lower loss-adjustment expense
- switching means losing calibrated accuracy and historical pattern libraries

A new entrant can buy model APIs, but not the years of labeled claim outcomes in that niche.

## Common confusion

| Term | Difference |
| --- | --- |
| Big data | Volume alone is not a moat |
| Switching costs from stored data | Related, but a data moat is about product improvement, not only migration pain |
| Brand | Trust may accompany data leadership, but is separate |
| Algorithm secrecy | Algorithms leak; unique data often matters more |

## Related concepts

- [Moat](moat.md)
- [Network Effects](network-effects.md)
- [Switching Costs](switching-costs.md)
- [Competitive Advantage](competitive-advantage.md)
- [Flywheels](../04-growth/flywheels.md)

## Further reading

- a16z and operator essays on AI defensibility and proprietary data
- “Data network effects” discussions in marketplace/AI literature
- Privacy and data-rights constraints as practical moat boundaries
