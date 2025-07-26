This project evaluates the impact of job training programs on the earnings of disadvantaged workers using Random Forest (RF) and Decision Tree (DT) models. The analysis is based on Robert Lalonde’s 1980s study of the National Supported Work (NSW) Demonstration program, which targeted unemployed women, ex-drug addicts, ex-offenders, and high school dropouts.

Business Context:

The Department of Labor is interested in determining whether job training programs can causally increase earnings for disadvantaged groups. This project uses statistical analysis and machine learning techniques to uncover actionable insights from the dataset.

Goals:

Analyze the effect of job training programs on annual income. Explore causal inference by ensuring covariate balance. Apply classification models (Decision Trees and Random Forests) to assess treatment effects.

Dataset:


Lalonde Dataset:

Contains background characteristics and annual income of individuals, with indicators for training program enrollment.

Key variables:

Treatment status (enrolled vs. not enrolled)

Annual income:

Covariates: age, education, race, marital status, previous earnings

Methods:


Exploratory Data Analysis (EDA):

Examining covariate balance and income distributions.

Identifying patterns between treatment and control groups.

Modeling:

Decision Tree Classifier – interpretable splits based on key covariates.

Random Forest Classifier – ensemble method for robust predictions.

Causal Analysis:

Matching and balancing covariates.

Estimating treatment effects.

Insights:

Importance of covariate balance in causal inference.

Model performance comparisons between RF and DT.

Key variables influencing post-training earnings.

Future Work:

Experiment with Gradient Boosting for improved accuracy. Incorporate Propensity Score Matching (PSM) for stronger causal claims. Expand dataset with external labor market data.
