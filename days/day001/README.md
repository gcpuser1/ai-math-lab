# Day 001 — How would you represent and predict latency?

Status: not started. These are original diagnostic questions, intentionally unsolved.

## Purpose

Find the starting point in algebra, functions, graphs, units and uncertainty. This is placement, not a pass/fail gate. Write "not sure" and show your reasoning when needed. Do not look up methods before the first attempt.

Use paper or a whiteboard. No Python installation required. Allow 60–90 minutes for the attempt, then 20–30 minutes for discussion and recording evidence.

## Real problem

A toy service has these synthetic observations:

| Concurrent requests x | Observed latency y (ms) |
|---|---|
| 10 | 30 |
| 20 | 50 |
| 30 | 70 |

We want to predict latency at 40 concurrent requests.

1. Sketch the observations with labelled axes and units.
2. Propose a rule. Explain each number in the rule.
3. Predict latency at 40. What assumptions make the prediction reasonable?
4. Should we trust the same rule at 10,000 requests? Explain.
5. A second measurement at 20 requests is 54 ms. Does this disprove your rule? What might you change?

## Prerequisite probes

### A — Algebra and change

For y = 3x + 2:
- Find y when x = 4.
- Solve for x when y = 20.
- If x rises by 0.1, how much does y change? Explain without just substituting twice.

### B — Scaling and graphs

A queue doubles every minute and starts with 5 requests.
- Write the first five values, including time zero.
- Propose a rule for time t.
- Contrast the shape with a queue gaining 5 requests per minute.
- What question does a logarithm help answer here? Skip if unfamiliar.

### C — Vectors and units

Two service descriptions are A = (3, 4) and B = (6, 8).
- Give a possible meaning to the two coordinates.
- Sketch them as arrows and describe their relationship.
- If coordinate 1 is seconds and coordinate 2 is megabytes, is ordinary arrow length automatically a meaningful comparison?
- What changes if seconds are recorded as milliseconds?

### D — Uncertain evidence

Only 1 of 100 requests fails. A detector labels every request as successful.
- What percentage does it classify correctly?
- Does this make it useful for finding failures?
- What else would you measure?

### E — Explain back

Choose one rule from your work:
- Explain why it works.
- State an assumption.
- Construct a case where it fails.
- Give a different situation where the same reasoning helps.

## Record and next step

Use ../../templates/session.md. Record uncertainty, help received and confidence. Leave progress.csv at not_started until you actually attempt the session.

The next lesson is selected from your reasoning. Possible repairs include equation manipulation, graph slope, function notation, units or proportionality. No answer key is included to preserve the diagnostic.
