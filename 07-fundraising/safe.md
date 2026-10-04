# SAFE (Simple Agreement for Future Equity)

> A SAFE is an investment contract — popularized by Y Combinator — where an investor provides capital now in exchange for the right to receive equity later, usually at a future priced round.

## What it means

SAFE stands for Simple Agreement for Future Equity. It is **not** debt (unlike many convertible notes). There is typically no interest and no maturity date in the standard YC forms (check the exact version you use).

Common terms:

- **Valuation cap:** maximum company valuation used to calculate conversion price
- **Discount:** % discount to the next round price
- **MFN** (sometimes): most-favored-nation clause
- **Post-money vs pre-money SAFE:** affects ownership math and dilution clarity

Post-money SAFEs make ownership per SAFE easier to reason about at issue time.

> Not legal advice. Use counsel and the official YC SAFE documents when issuing.

## Why it matters

SAFEs let early-stage companies raise quickly with less legal complexity than a priced round. They defer valuation fights — partially — until a priced round, while still needing a cap/discount framework.

Founders must still understand ownership: “simple” paperwork can create surprising dilution stacks if many SAFEs pile up.

## When founders should care

- Pre-seed / seed fundraising
- Bridge rounds
- Any time speed and lower legal overhead matter
- Before signing — model ownership scenarios

## How it works

### Post-money SAFE ownership sketch

If an investor invests $500k on a $10M **post-money** cap SAFE (simplified):

```text
Ownership at conversion (approx, if converting at cap) ≈ 500k / 10M = 5%
```

Multiple SAFEs stack. If you issue many post-money SAFEs, founders and employees dilute accordingly before the priced round.

### Conversion triggers

Typically convert at a priced equity round (and have rules for liquidity/dissolution events). Read the document.

## Practical example

Round building:

1. Raise $1.5M across SAFEs at a $12M post-money cap
2. Later raise a Series A at a $30M pre-money priced round
3. SAFE investors convert using the better of cap/discount mechanics per their docs
4. Cap table updates; option pool refresh may also dilute — see [term sheet](term-sheet.md)

Founders who modeled only the Series A price without SAFE stack ownership get surprised.

## Common confusion

| Term | Difference |
| --- | --- |
| Convertible note | Debt-like; often interest + maturity |
| Priced equity | Shares issued now at a valuation |
| Pre-money vs post-money SAFE | Ownership math differs — use current YC explanations |
| Cap = current valuation | Cap is a conversion ceiling mechanism, not a full priced valuation ritual |

## Related concepts

- [Valuation](valuation.md)
- [Dilution](dilution.md)
- [Cap Table](cap-table.md)
- [Pre-Seed](pre-seed.md)
- [Seed](seed.md)
- [Bridge Round](bridge-round.md)

## Further reading

- [Y Combinator SAFE documents and explainer](https://www.ycombinator.com/documents)
- Counsel primers comparing SAFE vs note vs priced rounds
