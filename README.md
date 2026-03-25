# A/B Testing a Homepage Redesign: When Metrics Conflict

## 📌 Overview
This project analyzes an A/B test evaluating a new homepage design for a streaming platform.

The experiment produced conflicting results:
- CTR increased significantly
- Time spent decreased significantly
- Subscription conversion showed no significant change

The goal is to determine whether the new design should be shipped.

---

## 🎯 Business Problem
Should the company launch a new homepage layout that increases clicks but may reduce user engagement depth?

---

## 📊 Experiment Results

| Metric | Control | Treatment | Change | p-value |
|--------|--------|----------|--------|--------|
| CTR | 10.0% | 11.2% | +1.2% | 0.01 |
| Time Spent | 22 min | 20 min | -2 min | 0.03 |
| Conversion | 4.5% | 4.4% | -0.1% | 0.40 |

---

## 🔍 Key Insights

- CTR increased → more user clicks
- Time spent decreased → potential drop in engagement depth
- Conversion unchanged → no observable business impact
- Metrics conflict, making the decision non-trivial

---

## ✅ Final Recommendation

Do **not ship** the new homepage yet.

While CTR improved, it is a leading metric and does not guarantee meaningful engagement. The decrease in time spent introduces risk of reduced user engagement, and no improvement is observed in conversion.

The potential downside outweighs the observed benefit.

---

## 🚀 Next Steps

- Run follow-up experiment measuring:
  - Retention (7-day, 30-day)
  - Total watch time
- Segment users (new vs returning)
- Analyze full engagement funnel

---

## 🧠 Key Learnings

- Statistical significance ≠ business value
- Leading metrics can be misleading
- Conflicting metrics require tradeoff analysis
- Clear decision-making under uncertainty is critical

---# AB-testing
