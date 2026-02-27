# 04_bivariate_analysis
**Boxplot of Charges vs Smoker**
The boxplot shows that smokers have significantly higher medical charges compared to non-smokers. The median and overall distribution of charges are higher for smokers, indicating that smoking increases healthcare costs. Thus, smoking is a major factor affecting medical charges.
**Scatter plot of Charges vs Age**
The scatter plot shows a positive relationship between age and medical charges. As age increases, medical charges also increase. Older individuals tend to have higher healthcare expenses compared to younger individuals.
**Scatter plot of Charges vs BMI**
The scatter plot shows a moderate positive relationship between BMI and medical charges. Individuals with higher BMI tend to have higher medical expenses. However, the variation in charges suggests that BMI is not the only factor affecting medical costs.
**Boxplot of Charges vs Region**
The boxplot shows that medical charges are fairly similar across all regions. There is no significant difference in median or distribution of charges between regions. Therefore, region does not strongly affect medical expenses.
**Boxplot of Charges vs Sex**
The boxplot shows that medical charges are similar for both males and females. There is no significant difference in median or distribution of charges. Therefore, sex does not strongly affect medical expenses.
**Scatter plot of Charges vs Children**
The scatterplot shows no clear relationship between number of children and medical charges. Charges vary widely for all groups, so children do not significantly affect medical expenses.
**Statistical Tests**
**T-test (smoker vs non-smoker charges)**
There is a statistically significant difference in medical charges between smokers and non-smokers. Smokers have significantly higher medical expenses compared to non-smokers. Smoking is an important factor affecting medical charges.
**Correlation analysis**
**Findings**
Smoker : Strongest effect on charges
Age : Moderate effect
BMI : Weak effect
Children : Very weak effect
Sex : Very weak effect
Region : No effect
Correlation analysis shows that smoking has the strongest positive relationship with charges (0.786), followed by age (0.312). BMI has a weak effect, while children, sex, and region have very little or no impact. Therefore, smoking is the most important factor affecting medical charges.
**ANOVA (region vs charges)**
The ANOVA test gives a p-value of 0.0742, which is greater than 0.05. This shows that there is no significant difference in medical charges across regions. Therefore, region does not significantly affect medical expenses.
**Correlation matrix**
Smoking has the strongest impact on medical charges, followed by age and BMI. Children, sex, and region have very little or no effect. Smoking is the key factor influencing healthcare costs.
**Multicollinearity check**
All variables have VIF values close to 1, indicating no multicollinearity problem. The independent variables are not highly correlated, and the dataset is suitable for regression analysis.
