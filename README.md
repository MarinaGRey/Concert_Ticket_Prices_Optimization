# Concert Revenue Maximization: Linear and Discrete Optimization Problem

## Project Overview
This project focuses on solving a ticket pricing optimization problem for a concert in Madrid. Using optimization techniques such as linear programming and mixed-integer programming (MIP), the goal is to determine the optimal ticket prices that maximize revenue while adhering to constraints like seating capacity, ticket demand, and pricing policies.

This project has been made in collaboration with [Miguel Fernández Lara](https://github.com/mifer29)

---

## Table of Contents
1. [Problem Statement](#problem-statement)
2. [Dataset](#dataset)
3. [Approach](#approach)
4. [Implementation](#implementation)
5. [Results](#results)
6. [Sensitivity Analysis](#sensitivity-analysis)
7. [Conclusions](#conclusions)

---

## Problem Statement
The project addresses a real-world scenario where concert organizers must set ticket prices to maximize revenue for an upcoming event in a Madrid stadium. The problem involves:
- Multiple seating sections with different capacities and pricing tiers.
- Constraints such as maximum/minimum ticket prices and revenue targets.

---

## Dataset
The dataset contains:
- Seating capacities for various sections.
- Pricing ranges for different ticket types.
- Historical data and demand patterns (if applicable).

---

## Approach
The problem is divided into two parts:
1. **Linear Optimization**:
   - Formulate the problem as a linear programming model.
   - Define constraints for pricing and capacity.

2. **Mixed-Integer Programming (MIP)**:
   - Extend the model to include discrete decisions.
   - Explore scenarios such as bundled pricing and discounts.

---

## Implementation
The project uses Python and the following libraries:
- **Pyomo**: For modeling optimization problems.
- **Pandas**: For data processing.
- **Matplotlib/Seaborn**: For visualization.

**Key Steps**:
1. Define problem variables and constraints.
2. Formulate objective functions.
3. Implement and solve models.
4. Analyze results and sensitivities.

---

## Results
- **Revenue Optimization**: Achieved a significant increase in revenue through optimized pricing.
- **Insights**: Identified key sections and ticket types contributing most to revenue.
- **Comparison**: Analyzed differences between linear and MIP solutions.

---

## Sensitivity Analysis
- Evaluated how changes in demand or constraints affect the optimal pricing.
- Insights into price elasticity and its impact on revenue.

---

## Conclusions
- Optimization is a powerful tool for revenue management.
- Linear models provide a quick solution, but MIP offers greater flexibility for real-world scenarios.
- Future work could involve dynamic pricing models or integration with real-time sales data.

---
