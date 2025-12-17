# Transition Matrices for Computing Expected Credit Loss and Stress Testing

## Project Overview

This repository contains a credit risk analytics project focused on rating transition matrices, Expected Credit Loss (ECL) computation, and stress testing for a hypothetical bank’s loan portfolio over a 10-year horizon.

The analysis follows a research-analyst style approach, combining exploratory data analysis (EDA), probability of default (PD) estimation, expected loss (EL) modeling, and scenario-based stress testing. The methodology is aligned with industry practices used in Basel and IFRS-style credit risk frameworks.

---

## Objectives

The key objectives of this project are:

- Analyze the rating composition and evolution of a credit portfolio over a 10-year period  
- Construct year-wise rating transition matrices  
- Estimate Probability of Default (PD) at both rating-level and portfolio-level  
- Compute Expected Credit Loss (EL) using given LGD and EAD assumptions  
- Evaluate cumulative default risk over medium-term (5-year) and long-term (10-year) horizons  
- Perform stress testing using:
  - LGD shock scenarios  
  - Rating downgrade scenarios  
- Identify portfolio stability and significant risk shifts using transition behavior  

---

## Key Analytical Components

### 1. Exploratory Data Analysis (EDA)

- Rating distribution across years  
- Migration patterns across rating categories  
- Identification of concentration risk and early warning signals  
- Visualization-driven insights using heatmaps, flow diagrams, and trend charts  

**Objective:** Provide a concise snapshot of portfolio quality and evolving credit risk.

---

### 2. Transition Matrix Estimation

- Year-wise borrower rating transition matrices (Year 2 to Year 10)  
- Matrix-based modeling of credit migration behavior  
- Foundation for PD estimation and cumulative default calculations  

---

### 3. Probability of Default (PD) Estimation

- Rating-level PD estimation for each year  
- Portfolio-level weighted PD calculation  
- Interpretation of PD trends and credit deterioration or improvement  

---

### 4. Expected Loss (EL) Computation

Expected Loss is calculated using the standard credit risk formula:

EL = PD × LGD × EAD


- Rating-wise and portfolio-level EL computation  
- Year-wise evolution of EL from Year 2 to Year 10  

---

### 5. Cumulative Default Risk

- Cumulative probability of default computed at:
  - End of Year 5  
  - End of Year 10  
- Long-term portfolio risk assessment using transition dynamics  

---

### 6. Stress Testing and Scenario Analysis

#### Scenario 1: LGD Stress

- Year-wise LGD shocks applied based on group-specific assumptions  
- LGD capped at 100 percent  
- Comparison of stressed EL versus baseline EL  
- Analysis of loss sensitivity to recovery assumptions  

#### Scenario 2: Rating Downgrade Shock

- Forced rating downgrades applied in Year 10  
- Same LGD and EAD assumptions retained  
- Comparison with baseline Year 10 EL  
- Assessment of downgrade-driven risk amplification  

---

### 7. Portfolio Risk Analytics (Challenger Section)

- Identification of the most stable rating category over time  
- Detection of significant shifts in portfolio risk using:
  - Transition volatility  
  - Acceleration in PD  
  - Sensitivity of EL to shocks  

---

## Tools and Technologies

- Python (primary language)
  - pandas
  - numpy
  - matplotlib
  - seaborn
- Jupyter Notebook
- Excel (validation and cross-checking)
- Word / PDF for management-style reporting  

---

## Key Takeaways

- Transition matrices provide a strong forward-looking view of credit risk  
- PD and EL evolve non-linearly due to rating migration behavior  
- Stress testing reveals tail risks not visible under baseline assumptions  
- Portfolio stability depends more on migration consistency than on static ratings  

---

## Disclaimer

This project is created solely for academic and learning purposes using hypothetical data.  
It does not represent any real bank, borrower, or confidential dataset.


