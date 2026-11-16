
# Catching More Fraud Dollars with Limited Review Capacity

**Capstone Project · MS in Data Analytics, Maryville University · Gretchen Kolthoff**

A machine learning project that helps a card issuer's fraud team decide which transactions to review first, so a small team catches as many fraud dollars as possible.

**Contents:** [Problem](#the-business-problem) · [Data and key trends](#what-the-data-shows) · [Models](#models-baseline-vs-gradient-boosting) · [Dashboard](#dashboard-in-progress) · [Reflection](#reflection) · [Code](#code)

---

## The business problem

A fraud team can only review a small share of transactions each day, and rule-based screening fills that queue with legitimate purchases while missing high-dollar fraud.

**Problem statement:** Build a model that ranks card-not-present transactions by fraud risk so that, when analysts review only the riskiest **2%** of transactions, they catch as many **fraud dollars** as possible. Success is measured on a held-out final month, compared against a simple baseline model.

**Who it's for:** a fraud strategy manager (persona: *Scarlett Smith*) who sets alert thresholds, manages a fixed team of analysts, and reports fraud losses to leadership.

---
