# Model Equations and Parameter Interpretations

**Student Name:** Amrut Kotasthane  
**Student ID:** bitsom_ba_2511321  

---

## 1. Simple Regression Equations
*   **Simple Model 1 (Marketing Spend):**
    $$\text{monthly\_sales} = 560,777.35 + 2.13 \times \text{marketing\_spend}$$
*   **Simple Model 2 (Footfall):**
    $$\text{monthly\_sales} = 446,410.58 + 35.68 \times \text{footfall}$$

---

## 2. Multiple Regression Equation
$$\text{monthly\_sales} = 86,602.87 
+ 1.21 \times \text{marketing\_spend}
+ 27.33 \times \text{footfall}
+ 3062.13 \times \text{inventory\_availability\_pct}
+ -3438.29 \times \text{competitor\_distance\_km}
+ 12439.13 \times \text{customer\_rating}
+ 3509.19 \times \text{staff\_count}
+ 15174.42 \times \text{holiday\_flag}
+ 9948.76 \times \text{region\_North}
+ 21082.10 \times \text{region\_South}
+ 25292.05 \times \text{region\_West}
+ -24476.21 \times \text{store\_type\_High\_Street}
+ -11852.81 \times \text{store\_type\_Mall}
+ -44692.78 \times \text{store\_type\_Residential}$$

---

## 3. Dummy Variable Reference Categories
*   **Region Reference Category:** **East** (dropped first dummy category).
    *   *West Region Coefficient:* **+25,292.05** ($p = 0.007$, significant). This means stores in the West generate **$25,292.05** more in monthly sales on average than stores in the East, holding other variables constant.
*   **Store Type Reference Category:** **Airport** (dropped first dummy category).
    *   *High Street Coefficient:* **-24,476.21** ($p = 0.008$, significant). High Street stores generate significantly lower sales compared to Airport stores.
