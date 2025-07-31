# 🎯 Darts Performance Analysis with Expected Win Chance

---

## 🎯 Goal

To adapt a well-known concept from other sports — **Expected Win Chance** — to darts, with the aim of developing **advanced metrics** that shed light on in-match decision-making and player reliability.

---

## 🧠 Hypothesis

By analyzing throw-by-throw decision-making and outcomes, it is possible to **quantify changes in win probability** during a darts match and identify which **target areas** are most impactful for each player.

---

## 📊 Data

- Manually-gathered throw-by-throw data from the **2025 PDC World Darts Championship Final**
- Historical checkout success rates for professional darts players
- Focused on identifying:
  - Impactful decisions on each turn
  - Which board targets increased win chances the most

---

## 🧪 Methods

- Gathered historical checkout data to calculate **expected checkout success rates**
- Used these to create a new metric: **Expected Win Chance**, updated after each turn
- Developed a secondary metric, **Clutchness**, to evaluate which areas of the board players used to **maximize increase in win probability**
- Analyzed how decision-making on critical throws impacted match outcomes
- Used to explain Luke Littler’s win vs. Michael van Gerwen

&nbsp;

<img src="Highlighted%20Visuals/Expected%20Win%20Points.png" width="50%">

- This graph shows win points above expected per leg, which is the sum of the win percentage points that each player accumulated throughout the leg minus the sum of the expected win percentage points from the checkouts they attempted

---

## 🏁 Outcome

- The model revealed **nuanced strategic tendencies**, uncovering how Littler gained small but consistent edges by targeting **high-leverage areas**.  
- The **Expected Win Chance** and **Clutchness** metrics uncovered meaningful insights not previously available in darts analytics.

&nbsp;

<img src="Highlighted%20Visuals/Littler%20Clutchness.png" width="50%">

&nbsp;

<img src="Highlighted%20Visuals/Van%20Gerwen%20Clutchness.png" width="50%">

Further explanations and visual summaries can be found in the **Report** tab.

---

