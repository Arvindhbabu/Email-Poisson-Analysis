📧 Email Data Analysis using Poisson Distribution

Welcome to the **Email Poisson Distribution Analysis Project**!  
This project models the number of emails received per day using **Poisson Distribution** — a powerful statistical tool to predict the probability of a number of events happening in a fixed interval.

---

🎯 Objective

- Collect data of emails received by multiple persons over a week.
- Calculate the **average rate (λ)** of emails per day.
- Apply the **Poisson probability formula** to find the likelihood of receiving exactly `k` emails on a given day.
- Visualize the probability distribution using graphs.

---

🛠 Technologies Used

- **Python 3.10+**
- **NumPy** (Numerical calculations)
- **Matplotlib** (Data Visualization)
- **SciPy** (Poisson Distribution from stats module)

---

📚 Statistical Concept: Poisson Distribution

The **Poisson Distribution** models the probability of a given number of events happening in a fixed interval, provided the events happen independently at a constant average rate.

**Formula:**  
\[
P(X = k) = \frac{λ^k e^{-λ}}{k!}
\]

Where:
- \( λ \) = Average number of emails per day (mean)
- \( k \) = Specific number of emails we want to find the probability for

---

📈 Project Workflow

1. Dataset of emails received per day is loaded for multiple persons.
2. Overall average number of emails (`λ`) is calculated.
3. User inputs any value of `k`.
4. Program computes:
   - Probability \( P(X = k) \)
   - Percentage chance
5. A beautiful bar graph of the Poisson distribution is displayed.

---

📋 Sample Dataset

| Person   | Monday | Tuesday | Wednesday | Thursday | Friday | Saturday | Sunday |
|----------|--------|---------|-----------|----------|--------|----------|--------|
| Person A | 9      | 11      | 10        | 13       | 8      | 12       | 10     |
| Person B | 8      | 10      | 9         | 11       | 7      | 8        | 9      |
| Person C | 10     | 12      | 11        | 14       | 9      | 13       | 12     |

---

