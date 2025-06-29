# Project Charter
**Project Name:** Cost of Living Dashboard – Sydney Suburbs  
**Author:** Esther Hoh
**Date:** 2025-06-30

---

## 1. Project Objective
Analyze and visualize how the cost of living varies across Sydney suburbs—focusing on housing, transport, utilities, and essentials—to highlight affordability challenges and trends.

---

## 2. Scope
**In Scope**  
- Data collection for median rent, petrol prices, electricity & water bills, and CPI (food).  
- Standardize and merge by suburb/postcode.  
- Develop composite Cost-of-Living Index and individual indicator views.  
- Build interactive dashboard (Tableau Public).  
- Publish code, data samples, and write-up.

**Out of Scope**  
- Forecasting future costs.  
- Analysis of suburbs outside Greater Sydney.  
- Detailed childcare or healthcare costs (unless added later).

---

## 3. Deliverables
1. **Master dataset** (CSV/Excel) with all indicators by suburb & date  
2. **Exploratory notebooks** (Python/R) showing EDA and index calculation  
3. **Interactive dashboard** published online  
4. **Executive brief** (PDF) summarizing methodology and key insights  
5. **GitHub repo** with `README.md`, code folders, and data samples

---

## 4. Key Milestones
- **Charter finalized**: 2025-06-30  
- **Data acquisition & tracking**: by 2025-07-07  
- **Data cleaning & integration**: by 2025-07-14  
- **Exploratory analysis & index calculation**: by 2025-07-21  
- **Dashboard prototype**: by 2025-07-28  
- **Final dashboard & write-up**: by 2025-08-04  
- **Publish & share**: by 2025-08-07  
(will be adjusted)

---

## 5. Data Sources
| Indicator                  | Source                                                           | Format        |
|----------------------------|------------------------------------------------------------------|---------------|
| Median weekly rent         | Domain Rental Report / ABS                                        | CSV, HTML     |
| Petrol price (avg per L)   | NSW FuelCheck API                                                | JSON/CSV      |
| Electricity bill (avg)     | ACCC / AER reports                                               | PDF → CSV     |
| Water charges (avg)        | Sydney Water pricing tables                                      | CSV           |
| CPI: Food & bev.           | ABS Consumer Price Index                                         | XLSX/CSV      |
| Postcode ↔ Suburb mapping  | ABS concordance files                                            | CSV           |

---

## 6. Success Criteria
- Dashboard loads smoothly and is fully interactive.  
- At least one clear affordability insight (e.g., top 5 least affordable suburbs).  
- Code repository is well-organized and reproducible.  
- Peers or supervisors can replicate steps using provided documentation.

---

## 7. Risks & Mitigations
| Risk                              | Likelihood | Mitigation                              |
|-----------------------------------|------------|-----------------------------------------|
| Incomplete suburb coverage        | Medium     | Use concordance; fill gaps with ABS data |
| API rate limits or access issues  | Low        | Cache downloads; maintain CSV backups   |
| Data format inconsistencies       | High       | Write robust cleaning scripts; log issues |

---

## 8. Version History
| Date       | Version | Changes                         | Author |
|------------|---------|---------------------------------|--------|
| 2025-06-30 | 0.1     | Initial charter draft           | Esther |


