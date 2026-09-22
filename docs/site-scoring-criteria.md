# Site Scoring Criteria

## Context

Symmetry needs a consistent way to decide which language Wikipedia editions should be prioritized for article gap analysis.

At the moment, there is no shared rubric in the repository for comparing language sites. This makes it harder to explain why one language edition should be investigated before another, especially when multiple candidate languages may have useful gaps compared with English Wikipedia.

This document creates a first-pass scoring template for prioritizing language Wikipedia sites. The goal is not to make a final decision automatically, but to give the team a repeatable starting point for discussion.

## Purpose

The scoring criteria are intended to help the team:

- compare candidate language Wikipedia editions using the same categories;
- document why a site was prioritized;
- avoid repeating the same research in future tasks;
- make gap-analysis decisions easier to review;
- support future planning for multilingual Wikipedia analysis work.

## Scoring Scale

Each criterion is scored from 1 to 5.

| Score | Meaning |
|---:|---|
| 1 | Very low priority or weak fit |
| 2 | Low priority or limited fit |
| 3 | Medium priority or reasonable fit |
| 4 | High priority or strong fit |
| 5 | Very high priority or excellent fit |

The final score is calculated using a weighted average.

```text
weighted score = criterion score * criterion weight
```

## Review Questions

- Are these the right criteria for prioritizing language Wikipedia sites?
- Should any criterion have a higher or lower weight?
- What data source should we use for speaker count and edit activity?
- Should this scoring template be used manually, or should it later be converted into a JSON/config file? 