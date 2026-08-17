# Smytten Match — Know What to Try

> **An independent product teardown and prototype exploring how Smytten can reduce decision friction in its trial journey.**

🔗 **Prototype:** [Add Prototype Link]
📄 **Product Teardown:** [Add PDF Link]

---

## The Problem

Smytten has already made trying unfamiliar products easier through its trial-first model. But when users encounter several similar products addressing the same need, the challenge shifts from **finding products to deciding which one to try**.

For example, searching for a need such as *brightening serum* can surface multiple products with overlapping claims, requiring users to compare reviews, price, brand familiarity, and Trial Points before making a choice.

### Product Opportunity

**How might Smytten help users move from “Try Before You Buy” to “Know What to Try”?**

---

## My Hypothesis

Users with a clear need but no strong brand preference may spend disproportionate effort comparing similar products before redeeming a Trial Point.

If Smytten can reduce this decision effort through relevant and explainable recommendations, it could make the trial journey more confident and actionable.

> *This is a hypothesis to validate, not a claim about existing user behaviour at scale.*

---

## Proposed Solution — Smytten Match

**Smytten Match** is a lightweight, opt-in recommendation experience that helps users find the most relevant products for their specific need.

### How it works

**1. Choose a need**
Select a concern such as Hydration, Acne Care, or Oil Control.

**2. Add 1–2 preferences**
Provide relevant inputs such as skin/hair type and budget.

**3. Get 2–4 matched products**
Products are ranked using existing metadata, tags, ratings, and user preferences.

**4. Understand the recommendation**
Each recommendation includes a simple **“Why this match?”** explanation.

**5. Try it directly**
Users can move directly from the recommendation to trial redemption.

---

## MVP Scope

The first version intentionally keeps the solution simple and testable.

### Must Have

* Need-based entry point across 2–3 categories
* Tag-based product matching
* 2–4 ranked recommendations
* “Why this match?” explanation
* One-tap trial redemption
* Post-trial “Was this a good match?” feedback

### Not in V1

* ML-based ranking
* Trial-history personalization
* Cross-category routines

The goal is to **validate the product hypothesis before adding technical complexity.**

---

## Product Thinking

The solution focuses on improving **decision confidence**, rather than simply adding another discovery surface.

| Today                             | Opportunity                       |
| --------------------------------- | --------------------------------- |
| Browse a broad catalogue          | Start with a specific need        |
| Compare multiple similar products | Receive a focused shortlist       |
| Decide using multiple signals     | Get an explainable recommendation |
| Trial after comparison            | Move directly to trial            |

The underlying product idea is:

> **Smytten has solved “try before you buy.” The opportunity is to also solve “know what to try.”**

---

## Success Metrics

### Primary Metric

**Recommendation-to-Trial Conversion Rate**

### Secondary Metrics

* Recommendation CTR
* Trial-to-Full-Size Purchase Conversion
* Repeat Usage of Smytten Match

### Guardrails

* Recommendation dissatisfaction
* Product diversity
* Match-flow exit rate

These metrics are proposed for validating the feature and are **not claims about Smytten's current internal metrics.**

---

## Experiment Design

### Control

Existing category browsing experience.

### Treatment

Existing browsing + **Find Your Match** entry point.

### Primary Evaluation

Compare:

**Recommendation → Trial conversion**
vs.
**Browse → Trial conversion**

The experiment should run long enough to capture the downstream trial-to-purchase journey rather than optimizing only for initial clicks.

---

## What I Would Validate First

Before investing heavily in development, I would:

1. Analyse the existing browsing-to-trial funnel.
2. Interview 5–8 recent trial users about how they selected their last trial.
3. Check whether Smytten already has an existing recommendation or quiz mechanism.
4. Compare trial-to-full-size conversion across categories.
5. Test a low-fidelity clickable prototype with 5–10 users.

---

## Disclaimer

This is an **independent product teardown and prototype created for a Product Management Internship application.**

It is not affiliated with or endorsed by Smytten. Company facts referenced in the teardown are based on publicly available information; product ideas, hypotheses, and recommendations are my own.
