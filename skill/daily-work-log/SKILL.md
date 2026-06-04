---
name: daily-work-log
description: Turn rough work notes into a concise daily work log, weekly summary, or brag-doc material while avoiding confidential employer/customer details. Use when the user wants to record what they did at work, summarize impact, prepare performance-review evidence, or convert daily notes into structured professional accomplishments.
---

# Daily Work Log

Create lightweight work logs that are useful later for weekly updates, performance reviews, brag docs, and project retrospectives.

## Core Rule

Do not preserve confidential details. Generalize employer-specific, customer-specific, incident-specific, unreleased, or access-controlled information unless the user explicitly says it is safe to keep.

## Daily Log Workflow

When the user gives rough notes for a work day:

1. Extract concrete work items.
2. Group them into:
   - shipped / progressed work;
   - communication and coordination;
   - decisions and tradeoffs;
   - blockers and risks;
   - impact evidence;
   - tomorrow's next steps.
3. Rewrite in first person if it is a personal log.
4. Keep claims factual and specific.
5. Mark unclear claims as assumptions instead of inventing details.
6. Remove or generalize sensitive names, metrics, links, and internal identifiers.

## Output Shape

Use this structure unless the user requests another format:

```markdown
# YYYY-MM-DD Work Log

## Shipped / Progressed

-

## Communication / Coordination

-

## Decisions / Tradeoffs

-

## Blockers / Risks

-

## Impact Evidence

-

## Tomorrow

-

## Brag-doc Seeds

-
```

## Weekly Summary Workflow

When summarizing a week:

1. Group daily notes by project/theme.
2. Identify outcomes, not just activity.
3. Separate shipped work, collaboration, leadership, technical depth, and operational cleanup.
4. Pull out metrics only if they are safe and verified.
5. End with next week's priorities.

## Brag-doc Guidance

Good brag-doc bullets include:

- action;
- scope;
- difficulty or constraint;
- result or impact;
- collaboration or leadership, when relevant.

Prefer:

> Led cross-functional coordination for a time-sensitive project milestone, clarified ownership across contributors, and reduced delivery risk by turning ambiguous work into explicit next steps.

Avoid:

> Worked hard on many things.

## Safety Checks

Before finalizing, ask whether the output contains:

- internal project names;
- restricted links;
- customer names or data;
- unreleased product details;
- confidential metrics;
- employee-sensitive information;
- credentials or secrets.

If yes, generalize or remove them.
