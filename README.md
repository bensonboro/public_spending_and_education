# Project title
- The Effect of public-school expenditure on pupil's Performance.

# Research question
- Does higher public expenditure per pupil improve pupil's average test score?

# Methodology
- I first explored the dataset using descriptive data analysis techniques, generating summary statistics and graphical presentations. Then, I used OLS techniques with robust standard errors to estimate the effect of expenditure per pupil on pupil's average test scores. In addition, I tested different functional forms and checked for heteroskedasticity using the White test. I did the analysis on Stata

# Key Finding
- The study found a positive and significant association between public expenditure and performance. Increasing expenditure per pupil by one percent is associated with an 0.089 point increase in pupil performance.

- Though the estimated model is well-specified and homoskedastic, it suffers from endogeneity problems. Unobserved factors such as parental education and income are likely to have positive association with both expenditure per pupil and performance. This renders the effect of public expenditure upward biased.

# Repository content
- `educAnalysis_dofile.do` # Stata code for data analysis
- `Report_expenditure_and_pupil_performance.pdf` # Data interpretation report
- `educ_finance.log`  # Stata logfile
