# Machine Learning-Driven Risk Profiling for Antimicrobial Resistance (AMR)

An advanced, data-driven machine learning pipeline designed to profile clinical and behavioral risks associated with Antimicrobial Resistance (AMR). This project leverages R programming and decision tree classification to model patient risk and predict resistance outcomes based on patient adherence, exposure levels, and prior failures.

---

## 👤 Author Information
* **Name:** MD SHAHRIN PARVEZ  
* **Department:** Department of Statistics  
* **Institution:** National University, Bangladesh  

---

## 📌 Project Overview
Antimicrobial Resistance (AMR) is one of the leading global public health threats. This project constructs a predictive model using **Decision Tree Classification** (`rpart`) to stratify patient risk levels. By analyzing behavioral factors such as self-medication, incomplete dosage courses, and yearly antibiotic exposure, the model maps out clinical pathways that lead to high resistance probability.

### Key Features:
* **Synthetic Clinical Cohort Generation:** Simulates realistic patient profiles ($N = 3,240$) based on epidemiological patterns.
* **Feature Engineering:** Computes customized behavioral risk scores based on self-medication tendencies and therapy adherence.
* **Supervised Machine Learning:** Employs recursive partitioning (`rpart`) for tree-based binary classification.
* **Interactive Data Visualization:** Generates a highly interpretable, color-coded clinical decision tree (`rpart.plot`) with optimized text sizing for presentation.

---

## 🛠️ Tech Stack & Packages
* **Language:** R (v4.0+)
* **Libraries Used:**
  * `tidyverse` (Data manipulation & cleaning)
  * `rpart` (Decision tree model construction)
  * `rpart.plot` (Professional tree visualization)

---

## 🚀 How to Run the Project

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/your-username/AMR-Risk-Profiling.git](https://github.com/your-username/AMR-Risk-Profiling.git)
