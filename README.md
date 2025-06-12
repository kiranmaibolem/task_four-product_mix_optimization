# 📦 Task 4: Optimization Model – Product Mix

This notebook demonstrates how to solve a **product mix optimization** problem using **Linear Programming** with the **PuLP** library in Python.

---

## 🎯 Problem Statement

A furniture company manufactures **tables** and **chairs**. The company wants to maximize profit while being limited by available **labor hours** and **wood stock**.

* **Profit per table:** ₹50
* **Profit per chair:** ₹30
* **Labor constraint:** 3h per table, 2h per chair (Max 240 hours)
* **Wood constraint:** 2 units per table, 1 unit per chair (Max 100 units)

---

## 🧪 Tools Used

* Python 3
* [PuLP](https://pypi.org/project/PuLP/): Linear programming solver

---

## 📁 Project Files

```
project-root/
├── task4_product_mix_optimization.ipynb  # Main Jupyter notebook
├── README_task4.md                       # This file
```

---

## 🧠 Solution Approach

1. Define decision variables for number of tables and chairs
2. Build the objective function to maximize total profit
3. Add constraints (labor and wood)
4. Solve the linear program using `model.solve()`
5. Output the optimal product quantities and maximum profit

---

## ✅ Output Example

```
Status: Optimal
Tables to produce: 40.0
Chairs to produce: 60.0
Maximum Profit: 3800.0
```

---

## 📊 Insights

* The notebook gives a clear business recommendation based on constraints
* Easy to adapt to any manufacturing or budget allocation scenario

---

✅ Maintained by: `Kiranmai Bolem`
Feel free to fork or extend the model for different use-cases.
