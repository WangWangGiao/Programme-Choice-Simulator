# 📊 Programme Choice Simulator
### STTHK2133 Modeling & Simulation | Individual Assignment #1

An interactive decision-support tool designed to simulate and predict undergraduate programme selection using a **Discrete Choice Perspective**. This project implements a **Multinomial Logit (Softmax)** model to analyze how student priorities and uncertainty influence university enrollment.

---

## 🚀 Project Overview
This simulation focuses on **Aiman**, a pre-university student in Malaysia, who must choose between six academic paths. The model evaluates choices based on perceived utility, factoring in both deterministic elements like exam results and subjective preferences like personal interest.

### Core Logic & Assumptions
* **Utility Function ($U_i$):** A weighted linear combination of six factor scores.
* **Choice Probabilities:** Derived via the **Softmax** function to reflect uncertainty and competing priorities.
* **IIA Assumption:** The model assumes the Independence of Irrelevant Alternatives.

---

## 🛠️ Technical Implementation
* **Environment:** HTML & JavaScript, deployed as a self-contained interactive web interface.
* **Algorithm:** Numerically stable Multinomial Logit.
* **Visualizations** (powered by Chart.js):
    * Probability Distribution Bar Charts.
    * Weighted Utility Score Comparisons.
    * Factor Contribution Heatmaps.
    * Sensitivity Analysis (Weight Variation).

---

## 🖥️ Interface
The system is implemented as a single interactive web-based interface using HTML and JavaScript. A tabbed structure separates the input controls from the output charts to reduce clutter and improve readability. Users can dynamically adjust both programme ratings and factor weights via sliders, with all four visualizations updating simultaneously upon confirmation. Sensitivity analysis is integrated directly into the dashboard to provide deeper insight into model behaviour.

---

## 📋 Evaluated Factors & Importance
The model processes the following weights to determine the final selection probability:

| Factor | Weight | Description |
| :--- | :--- | :--- |
| **Interest** | 30% | How much he likes the field |
| **Future Career** | 25% | Job opportunities and salary potential |
| **Exam Results** | 20% | How well his results match the entry requirements |
| **Location** | 10% | Distance from home / preferred city |
| **Fees** | 10% | Less funds to pay for the programme |
| **Willingness to Explore** | 5% | Openness to trying something new |

---

## 📈 Model Insights
This system allows for the **flexible adjustment of both factor weights and programme ratings**, enabling users to observe how final decision outcomes change under different simulated scenarios. By dynamically modifying these inputs, users can perform sensitivity analysis to identify which factors most significantly influence student enrollment trends and behavioral patterns.
