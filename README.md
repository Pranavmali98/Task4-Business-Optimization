# Task 4 – Business Optimization using Linear Programming

**Internship:** CODTECH Data Science  
**Task:** Solve a business problem using optimization techniques  
**Tools Used:** Python, PuLP, Jupyter Notebook  

---

## Objective

The goal of this task is to demonstrate how **optimization techniques**, specifically **Linear Programming**, can be used to solve real-world business problems efficiently using Python.

This repository contains **two different business optimization examples**, each modeled, solved, and analyzed using the **PuLP** library.

---

## Optimization Technique Used

- **Linear Programming (LP)**
- **Solver:** PuLP (CBC Solver)
- **Decision Variables, Constraints, Objective Function**

---

## Project Structure

Task-4-Optimization/
│── Production_Optimization.ipynb
│── Transportation_Optimization.ipynb
│── README.md

---

## Example 1: Production Optimization (Profit Maximization)

### Problem Description
A manufacturing unit produces two products:
- Product A
- Product B

Each product requires machine hours and generates profit.  
The company has limited machine hours and production capacity.

### Objective
**Maximize total profit** while satisfying:
- Machine hour constraints
- Maximum production limits
- Non-negative production quantities

### Key Concepts Applied
- Profit maximization
- Resource constraints
- Production limits

### Outcome
The optimal number of units for each product is determined to achieve **maximum profit** without violating constraints.

---

## Example 2: Transportation Optimization (Cost Minimization)

### Problem Description
A logistics company transports goods from:
- 2 Warehouses  
to  
- 3 Retail Stores  

Each warehouse has limited supply, and each store has a fixed demand. Transportation costs vary between routes.

### Objective
**Minimize total transportation cost** while ensuring:
- All store demands are met
- Warehouse supply limits are respected

### Key Concepts Applied
- Cost minimization
- Supply-demand balance
- Multi-source multi-destination optimization

### Outcome
An optimal shipping plan is obtained that minimizes total logistics cost.

---

## Technologies Used

- Python 3.x
- PuLP
- Jupyter Notebook

---

## Learning Outcomes

- Formulated real-world business problems mathematically
- Implemented linear programming models in Python
- Interpreted optimization results for business decision-making
- Understood profit maximization and cost minimization strategies

---

## How to Run the Project

1. Clone the repository
```bash
git clone <[your-repo-link](https://github.com/Pranavmali98/Task4-Business-Optimization)>
```

2. Install dependencies
```bash
pip install pulp
```

3. Open Jupyter Notebook
```bash
jupyter notebook
```

4. Run either notebook:
   - Task4-Ex-1
   - Task4-Ex-2

## Conclusion

This task demonstrates how optimization techniques can significantly improve business efficiency by making data-driven decisions.
Linear Programming proves to be a powerful tool for solving both production and logistics problems.

## Author

/*Pranav Mali*/
CODTECH Data Science Intern
