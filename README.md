# Credit Card Approval – Bias & Fairness Audit  

This project conducts a **fairness and bias audit** on a credit card approval dataset. The main objective is to assess whether sensitive attributes such as **Gender, Ethnicity, and Citizenship** unfairly influence approval outcomes, evaluate fairness metrics, apply bias mitigation strategies, and provide recommendations aligned with **ethical AI practices**.  

---

## Project Objectives  
- Audit the dataset for potential **bias and discrimination**.  
- Evaluate fairness using multiple **fairness metrics**.  
- Apply **bias mitigation techniques**.  
- Provide **recommendations** for ethical AI adoption.  

---

## Dataset  
- **Source:** Kaggle – [Credit Card Approval Clean Data](https://www.kaggle.com/datasets/samuelcortinhas/credit-card-approval-clean-data)
- **Sensitive Attributes:** Gender, Ethnicity, Citizenship  
- **Target Variable:** Approval (1 = approved, 0 = not approved)  

---

## Methods  

### 1. Data Cleaning & Preprocessing  
- Standardized numerical and categorical features.  
- Isolated sensitive attributes for fairness checks.  

### 2. Bias Analysis  
- Compared approval rates across groups.  
- Identified disparities in outcomes.  

### 3. Fairness Metrics  
- **Demographic Parity**  
- **Equal Opportunity**  
- **Disparate Impact Ratio**  

### 4. Bias Mitigation Techniques  
- Reweighing  
- Pre-processing transformations  
- Fairness-aware classifiers  

---

## Findings  

### Bias Analysis  
- **Gender:** Males had higher approval rates compared to females.  
- **Ethnicity:** Certain ethnic groups were disadvantaged with lower approval rates.  
- **Citizenship:** Non-citizens had significantly lower approval rates.  

### Fairness Metrics  

| Metric             | Finding                                   | Bias Detected |
|--------------------|-------------------------------------------|---------------|
| Demographic Parity | Approval rates unequal across groups       | Yes |
| Equal Opportunity  | Qualified applicants treated unequally     | Yes |
| Disparate Impact   | Females & non-citizens < 0.8 ratio threshold | Yes |

### Bias Mitigation Results  
- Disparities reduced after applying **reweighing** and **fairness-aware models**.  
- Fairness metrics showed **measurable improvement**.  

---

## Recommendations  
- Use **fairness-aware algorithms** in production systems.  
- Conduct **regular audits** with fairness metrics.  
- Collect **more representative datasets** to reduce systemic bias.  
- Implement **explainability techniques** for transparency.  
- Adopt **ethical AI guidelines** in financial decision-making.  

---

## 📌 Conclusion  
The audit revealed **systematic bias** against women, certain ethnic groups, and non-citizens.  
While mitigation techniques improved fairness, **long-term solutions** require better data practices, continuous monitoring, and ethical AI adoption.  

This project demonstrates the importance of **responsible AI** in credit and financial systems.  

