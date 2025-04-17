# optimizing-profitability
Profit optimization strategy using linear programming and Excel Solver for a hardware company's expansion. Includes constraints analysis, sensitivity evaluation, and decision support modeling.

Optimizing Profitability: Strategic Expansion Analysis

This project presents a linear programming solution to help a Northern hardware company optimize inventory allocation and maximize profit as it prepares to launch a new distribution center. The analysis considers budget constraints, warehouse space, and marketing goals while identifying the most profitable product mix.

---

##  Objectives
- Maximize total monthly profit from product sales
- Determine optimal inventory levels under budget and space limits
- Incorporate marketing constraints into the decision-making model
- Conduct sensitivity analysis to evaluate potential profitability under changing scenarios

---

##  Linear Programming Model

**Objective Function:**  
Maximize profit = 219.99x₁ + 299.99x₂ + 379.99x₃ + 142.99x₄

**Decision Variables:**  
- x₁ = Pressure Washers  
- x₂ = Go-Karts  
- x₃ = Generators  
- x₄ = Water Pumps

**Constraints:**  
- Budget: 349.99x₁ + 379.99x₂ + 530x₃ + 500x₄ ≤ 130,000  
- Space: 25x₁ + 40x₂ + 25x₃ + 6.25x₄ ≤ 12,300 sq ft  
- Promotion Rule 1: 0.7x₁ + 0.7x₂ − 0.3x₃ − 0.3x₄ ≥ 0  
- Promotion Rule 2: x₃ − 2x₄ ≥ 0  
- Non-negativity: x₁, x₂, x₃, x₄ ≥ 0

---

##  Key Results
- **Optimal Monthly Profit:** $60,391.82  
- **Optimal Inventory Mix:**  
  - Pressure Washers: 0  
  - Go-Karts: 146.9  
  - Generators: 228.5  
  - Water Pumps: 114.2  
- **Insight:** Pressure Washers yielded no profit and were excluded from the optimal solution

---

##  Sensitivity Analysis
- **Budget:** Shadow price = $0 → current $130,000 budget is sufficient  
- **Warehouse Space:** Shadow price = $11.03 → each extra square foot yields ~$11 more in profit  
- **Additional Investment:** $35,740 budget increase = ~$23,596 more in profit  
- **Recommendation:** Expand warehouse to 12,866.5 sq ft for optimal return

---

##  Tools Used
- Microsoft Excel Solver for LP modeling and scenario testing
- Business analytics methodology for constraint formulation and profitability evaluation

---

##  Files Included
- `Profit_Optimization_Model.xlsx` – Linear programming model & Solver configuration  
- `Profit_Optimization_Report.doc` – Final report with full analysis and recommendations  
- `README.md` – This documentation

---

## 📌 Summary
By integrating optimization techniques with sensitivity insights, this project enables data-driven decision-making for profitable expansion. It provides a reusable framework for inventory planning and resource allocation under real-world constraints.
