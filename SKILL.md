---
name: feature-prioritization
description: >
  Use when the Product Manager needs to evaluate and rank multiple features,
  requests, or campaign elements by impact and effort. Triggered when the backlog
  has competing priorities or when the CEO asks for a prioritized roadmap.
  Produces a ranked list with clear rationale.
---

# Feature prioritization

## Purpose
Prioritization answers: what do we work on first and why? It prevents the team from spreading effort across too many things and gives the Creative Director a clear sequence to plan creative work around.

## Framework: Impact / Effort matrix

For each item, score:
- **Impact** (1-5): effect on the primary business objective
- **Effort** (1-5): time and resources required (5 = most effort)
- **Priority score**: Impact ÷ Effort (higher = do first)

## Output structure

```
## Prioritization — [Context: Q3 roadmap / Campaign features / Backlog]

### Ranked list

| # | Item | Impact | Effort | Score | Recommendation |
|---|------|--------|--------|-------|----------------|
| 1 | [Item A] | 5 | 2 | 2.5 | Do now |
| 2 | [Item B] | 4 | 2 | 2.0 | Do now |
| 3 | [Item C] | 4 | 3 | 1.3 | Plan for next sprint |
| 4 | [Item D] | 2 | 4 | 0.5 | Deprioritize |
| 5 | [Item E] | 1 | 5 | 0.2 | Drop or revisit |

---

### Rationale

**Item A — [name]**
Why high impact: [specific reason tied to business objective]
Why low effort: [specific reason]
Dependency: [what must exist first, if anything]

[repeat for top 3 items]

---

### What we are NOT doing (and why)
[List deprioritized items with brief rationale — this prevents them from coming back without new information]

---

### Assumptions
[List any assumptions that, if wrong, would change the ranking]

---

### Decision needed
[If any item requires CEO or CD input before proceeding, flag it explicitly]
```

## Rules
- Score every item on the same criteria — don't mix frameworks mid-list.
- Always include a "not doing" section. Without it, deprioritized items keep resurfacing.
- Assumptions must be explicit. If the market changes or data comes in that invalidates an assumption, the list gets re-ranked.
- The Product Manager recommends — the CEO or CD makes the final call. Always present this as a recommendation, not a decision.
