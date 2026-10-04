# Viral Coefficient (k)

> The viral coefficient (k) estimates how many new users each existing user generates through viral actions in one cycle.

## What it means

In a simple model:

```text
k = (invites sent per user) × (conversion rate of invites)
```

If each user sends 2 invites and 30% accept and become users:

```text
k = 2 × 0.30 = 0.6
```

Interpretation:

- **k < 1:** viral growth alone decays without other acquisition
- **k = 1:** each user replaces themselves (still need other growth for expansion; timing matters)
- **k > 1:** theoretically explosive viral growth (rare to sustain)

Cycle time matters as much as k. A k of 0.8 with a 2-day cycle can outperform a k of 1.1 with a 120-day cycle for early momentum.

## Why it matters

k turns vague “we’re viral” claims into a measurable system. It shows whether to invest in invite rate, invite conversion, or cycle time.

Even with k < 1, virality can still meaningfully reduce blended CAC.

## When founders should care

- When invites/shares are core to the product
- When modeling organic growth contributions
- When debugging a viral loop’s weak step
- Rarely as a vanity KPI for non-viral products

## How it works

### Extended view

```text
k = i × c
```

Where:

- `i` = invites (or exposures) per user per cycle
- `c` = conversion from invite/exposure to new user (ideally activated user)

Better models use **activated** users, not raw signups.

### Worked example

Cohort of 1,000 activated users in a week:

- average invites: 1.5
- invite accept → signup: 40%
- signup → activation: 50%
- effective conversion to activated user: 0.40 × 0.50 = 0.20

```text
k = 1.5 × 0.20 = 0.30
```

Next viral wave ≈ 1,000 × 0.30 = 300 activated users, then 90, then 27… — helpful, not self-sustaining. Pair with content/paid for compounding.

### Improve k

| Lever | Example |
| --- | --- |
| Increase invites | Make collaboration necessary for value |
| Increase conversion | Better invite landing experience |
| Shorten cycle | Faster time-to-invite after signup |
| Improve activation | Recipients reach aha quickly |

## Practical example

A whiteboard tool requires sharing a board to get feedback. Designers invite clients. Clients sometimes become users themselves. Product instruments invite sends, accept rate, and activation to compute k weekly by cohort.

## Common confusion

| Mistake | Better |
| --- | --- |
| Counting spammy invites | Measure qualified activated users |
| Ignoring cycle time | Model speed and k together |
| Assuming k>1 is required | Partial virality still valuable |
| Confusing with NPS | Different concept |

## Related concepts

- [Virality](virality.md)
- [Viral Loops](viral-loops.md)
- [Referral Loops](referral-loops.md)
- [Activation](../06-finance/activation.md)
- [CAC](../06-finance/cac.md)

## Further reading

- Early consumer growth literature on k-factor modeling
- Modern PLG analytics practices for invite funnels
