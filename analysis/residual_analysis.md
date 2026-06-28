# Residual Analysis

**Student Name:** Amrut Kotasthane  
**Student ID:** bitsom_ba_2511321  

---

## 1. Top 5 Positive Residual Stores (Model Under-Predicts Sales)
These stores generated substantially higher sales than predicted based on their operational metrics:
| store_id   | region   | store_type   |   monthly_sales |   predicted_sales |   residual |
|:-----------|:---------|:-------------|----------------:|------------------:|-----------:|
| STR-1058   | East     | High Street  |          870937 |            759887 |   111050   |
| STR-1028   | East     | Mall         |          713611 |            610562 |   103049   |
| STR-1073   | East     | Residential  |          813317 |            721401 |    91916   |
| STR-1051   | East     | Airport      |          787716 |            701300 |    86415.1 |
| STR-1026   | East     | Mall         |          625514 |            540162 |    85352.5 |

*   **Business Meaning:** These stores represent outperformers. They possess unmodeled advantages, such as superior local store management, visual layout superiority, or lack of local competitors that are not captured by competitor distance.

---

## 2. Top 5 Negative Residual Stores (Model Over-Predicts Sales)
These stores underperformed significantly relative to what the model predicted they should have achieved:
| store_id   | region   | store_type   |   monthly_sales |   predicted_sales |   residual |
|:-----------|:---------|:-------------|----------------:|------------------:|-----------:|
| STR-1023   | South    | Mall         |          627172 |            763972 |  -136800   |
| STR-1017   | West     | High Street  |          685379 |            805326 |  -119947   |
| STR-1012   | West     | Residential  |          595468 |            709942 |  -114475   |
| STR-1007   | West     | Mall         |          800452 |            912321 |  -111869   |
| STR-1060   | West     | Mall         |          721079 |            808037 |   -86957.3 |

*   **Business Meaning:** These stores underperform. They are likely facing unmodeled challenges, such as road construction nearby blocking traffic, poor customer service leading to lost visits, or regional supply chain bottlenecks.
