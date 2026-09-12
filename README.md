# Analysis Preregistration

## 1. Research Question

Does the number of hours students study per week during the four weeks preceding an examination significantly predict their examination scores?

## 2. Population

The target population is students who participate in academic examinations.

The unit of analysis is the individual student.

## 3. Exposure

The primary exposure is weekly study time, measured in hours per week during the four weeks preceding the examination.

## 4. Comparator

Students studying fewer than 10 hours per week will be compared with students studying 10 or more hours per week for the categorical comparison.

The primary analysis will treat study hours as a continuous variable.

## 5. Outcome

The primary outcome is examination score, measured on a 0–100 scale.

## 6. Observation Window

Study hours will be measured during the four weeks preceding the examination. The examination score will correspond to the examination taken immediately after this observation period.

## 7. Hypotheses

### Null Hypothesis (H0)

There is no statistically significant relationship between weekly study hours and examination scores.

### Alternative Hypothesis (H1)

Higher weekly study hours are associated with higher examination scores.

The expected direction of the association is positive.

## 8. Inclusion Criteria

Participants must:

* Have a recorded weekly study-hour value.
* Have a valid examination score.
* Belong to the defined student population.
* Have observations corresponding to the specified observation window.

## 9. Exclusion Criteria

The following observations will be excluded:

* Missing study-hour values.
* Missing examination scores.
* Duplicate records.
* Negative study hours.
* Examination scores outside the valid 0–100 range.

The number and reason for excluded observations will be recorded.

## 10. Variables

| Variable       | Role              | Measurement |
| -------------- | ----------------- | ----------- |
| Study Hours    | Primary predictor | Hours/week  |
| Exam Score     | Primary outcome   | 0–100       |
| Attendance     | Control variable  | Percentage  |
| Previous Score | Control variable  | 0–100       |

## 11. Transformations

Study hours and examination scores will initially be analyzed on their original scales.

No transformation will be applied unless required because of substantial violations of model assumptions.

Any transformation made after the preregistration will be documented as a deviation.

## 12. Missing Data

Observations with missing values for the primary predictor or outcome will be excluded from the primary analysis.

The number of missing observations and exclusions will be reported.

## 13. Statistical Analysis

Descriptive statistics will include:

* Sample size
* Mean
* Median
* Standard deviation
* Minimum
* Maximum

A scatter plot will be generated to examine the relationship between study hours and examination scores.

Pearson correlation will be used to estimate the linear association.

A linear regression model will then be fitted:

Exam Score = β0 + β1(Study Hours) + ε

If control variables are available, a multiple linear regression model will be fitted:

Exam Score = β0 + β1(Study Hours) + β2(Attendance) + β3(Previous Score) + ε

## 14. Statistical Significance

The significance level will be:

α = 0.05

A p-value below 0.05 will be considered statistically significant.

## 15. Effect Sizes

The following effect sizes will be reported:

* Pearson correlation coefficient (r)
* Regression coefficient for study hours (β1)
* R² for the regression model

## 16. Uncertainty Intervals

95% confidence intervals will be reported for the correlation and regression coefficients.

## 17. Assumption Checks

The following assumptions will be evaluated:

* Linearity
* Independence of observations
* Normality of residuals
* Homoscedasticity
* Influential observations

## 18. Robustness Checks

If the assumptions of Pearson correlation are substantially violated, Spearman rank correlation will be reported as a robustness analysis.

Influential observations will also be examined.

Any additional analysis not specified in this preregistration will be documented as a deviation.

## 19. Stopping Rule

The analysis will use all eligible observations available in the predefined dataset after applying the inclusion and exclusion criteria.

No observations will be removed based on their effect on statistical significance.

## 20. Deviations

All deviations from this preregistration will be documented with:

* Timestamp
* Description of deviation
* Reason for deviation
* Potential impact on the analysis

No deviations are recorded at the time of preregistration.
