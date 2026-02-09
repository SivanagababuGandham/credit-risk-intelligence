====================================================================
README.md
Project Overview, Business Context, Outcomes
====================================================================

PROJECT OVERVIEW
--------------------------------------------------------------------
This project presents an end-to-end exploratory data analysis of
customer credit data within the Paisa Bazaar ecosystem.

The analysis focuses on understanding what drives credit score
outcomes and how those drivers can be translated into actionable
business intelligence.

The work is exploratory, risk-driven, and designed to support
downstream modeling and policy decisions.


BUSINESS CONTEXT
--------------------------------------------------------------------
PaisaBazaar operates at the intersection of customers and multiple
lending institutions.

Credit score is the dominant decision signal influencing:
  - Loan approval or rejection
  - Interest rate pricing
  - Credit limits and exposure
  - Portfolio-level risk assessment
  - Lender confidence and trust

Credit scores are often consumed as final outcomes rather than
explainable signals, limiting visibility into why risk exists.


BUSINESS PROBLEM
--------------------------------------------------------------------
Using credit scores as black boxes introduces three key risks:

1) Mispriced risk
   High-risk customers may be under-priced, while low-risk customers
   may be over-penalized.

2) Missed low-risk growth
   Behaviorally strong customers may be rejected due to historical
   scores.

3) Reactive risk control
   Risk is identified only after score deterioration, rather than
   through early behavioral signals.


OBJECTIVE OF THIS ANALYSIS
--------------------------------------------------------------------
The objective of this analysis is not to replace or challenge
credit scores.

Instead, it aims to:
  - Explain and decompose credit score outcomes into observable
    financial and behavioral drivers
  - Validate whether customer behaviors align with score-based
    risk segmentation
  - Surface actionable behavioral levers that improve decision
    quality, risk control, and growth outcomes


KEY OUTCOME
--------------------------------------------------------------------
Credit score variation in this portfolio is driven primarily by
customer behavior, not income or demographics alone.

This conclusion is validated across univariate, bivariate, and
multivariate analysis layers and forms the foundation for credit
score classification and prediction models.
