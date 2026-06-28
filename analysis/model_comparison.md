# Model Comparison Report

**Student Name:** Amrut Kotasthane  
**Student ID:** bitsom_ba_2511321  

---

## 1. Summary Comparison Table
| Model Name | Independent Variables | R-squared | Adj. R-squared | F-pvalue | Significant Predictors |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Simple Regression 1** | `marketing_spend` | 0.1672 | 0.1646 | 2.48e-14 | `marketing_spend` ($p < 0.001$) |
| **Simple Regression 2** | `footfall` | 0.7363 | 0.7355 | 4.75e-94 | `footfall` ($p < 0.001$) |
| **Multiple Regression** | All variables (including dummies) | 0.8569 | 0.8504 | 1.307e-119 | `marketing_spend`, `footfall`, `competitor_distance_km`, `staff_count` |

---

## 2. Business usefulness & Limitations
*   **Simple OLS 1 (Marketing Spend):** Tells us that marketing spend alone explains **16.7%** of store sales. Useful for quick marketing budget estimation but suffers from omitted variable bias.
*   **Simple OLS 2 (Footfall):** Explains **73.6%** of sales. Indicates strong traffic association, but footfall is an intermediate outcome, not a direct operational input.
*   **Multiple Regression:** Explains **85.69%** of the variance. This model provides an actionable framework for resource allocation because it accounts for other factors simultaneously, showing that discounting is statistically weak while marketing and staffing are highly effective.
*   **Limitations:** The model cannot capture local store events, visual merchandising quality, or stockouts not recorded in the inventory metric.
