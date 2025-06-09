# Multiple Linear Regression Analysis of Survival Time
## Description
This repository contains R code for a comprehensive multiple linear regression (MLR) analysis aimed at modeling the survival time (SurvTime) of patients undergoing liver surgery. The model uses the predictors: Blood Clotting Score (BCS), Prognostic Index (PI), Enzyme Function Test Score (EF), and Liver Function Test Score (LF) from the dataset LiverStudy.csv.
The analysis includes:
	•	Fitting full and reduced MLR models
	•	Model selection via forward, backward, and stepwise approaches
	•	Diagnostic checks for normality, constant variance, and multicollinearity
	•	Variable transformations (logarithmic, square root, inverse, polynomial) to satisfy model assumptions
	•	Residual analysis and formal statistical tests including Shapiro-Wilk and Breusch-Pagan tests
	•	Box-Cox transformation to determine the optimal response transformation
	•	Identification and treatment of influential points and outliers using R-student residuals, leverage, DFFITS, Cook’s Distance, and DFBETAS
	•	Refitting models after removing influential observations to evaluate impact on the model
## Files
	•	MLR analysis.Rmd or MLR analysis.R: Main RMarkdown or R script with full annotated analysis
	•	LiverStudy.csv: Dataset containing patient data
## Installation and Setup
To run this analysis, ensure you have R (version 4.0 or higher) installed along with the following R packages:
```r
install.packages(c("lmtest", "car", "ggplot2", "GGally", "MASS", "flextable", "broom"))

Usage
	1	Place LiverStudy.csv in your working directory.
	2	Open and run the analysis.Rmd or analysis.R file in R or RStudio to reproduce the analysis, generate tables, and figures.
	3	Follow the annotated code for detailed steps and interpretation.

If you want, I can help you save this as a ready-to-upload README.md file — just ask!

