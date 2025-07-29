# Impact of Job Training Programs on Earnings

This project evaluates the **impact of job training programs on the earnings of disadvantaged workers** using **Random Forest (RF)** and **Decision Tree (DT)** models. The analysis is based on Robert Lalonde’s 1980s study of the **National Supported Work (NSW) Demonstration program**, which targeted **unemployed women, ex-drug addicts, ex-offenders, and high school dropouts**.

---

## **Business Context**
The **U.S. Department of Labor** is interested in determining whether **job training programs can causally increase earnings** for disadvantaged groups. This project combines **statistical analysis** with **machine learning** to uncover actionable insights, evaluate treatment effects, and explore how participation in training programs impacts post-training income.

---

## **Goals**
- Analyze the **effect of job training programs on annual income**.
- Perform **causal inference** by ensuring **covariate balance** between treatment and control groups.
- Apply **Decision Tree (DT)** and **Random Forest (RF)** classifiers to assess treatment effects and key variables.

---

## **Dataset**
### **Lalonde Dataset**
- Contains **background characteristics** and **annual income** of individuals, with an indicator for training program enrollment.
- **Key Variables**:
  - `treat`: Treatment status (1 = enrolled, 0 = not enrolled).
  - `re78`: Annual income after training.
  - **Covariates:** Age, education, race, marital status, and previous earnings (`re75`, `re74`).

---

## **Methods**
- **Exploratory Data Analysis (EDA)**:
  - Examined covariate balance and income distributions.
  - Identified patterns between treatment and control groups.

- **Modeling**:
  - **Decision Tree Classifier:** Interpretable splits based on covariates.
  - **Random Forest Classifier:** Ensemble approach for robust predictions.

- **Causal Analysis**:
  - Evaluated **treatment effects** and **covariate balance**.
  - Compared post-training income distributions between treated and control individuals.

---

## **Insights**
- **Covariate balance** plays a crucial role in reliable causal inference.
- **Random Forest** models performed better in capturing non-linear effects than simple decision trees.
- **Key predictors** of post-training income included **previous earnings, education, and marital status**.

---

## **Future Work**
- Experiment with **Gradient Boosting** for improved accuracy.
- Incorporate **Propensity Score Matching (PSM)** to strengthen causal claims.
- Expand the dataset with **external labor market data** for broader insights.

---



