# ReadMe

> Group project for team-4 for Data Science Stats.

## Background Readings

Our group is assigned to do ANCOVA analysis. To understand ANCOVA, it is important to understand ANOVA and Regression first. ANCOVA is simply ANOVA + Regression.
1. https://www.graphpad.com/guides/the-ultimate-guide-to-anova
2. https://statisticsbyjim.com/anova/ancova/

## How to do ANCOVA analysis
### Steps in ANCOVA:
1. **Check Assumptions**:
    - Linearity: The relationship between the covariate and the dependent variable should be linear.
    - Homogeneity of regression slopes: The relationship between the covariate and the dependent variable should be the same across all groups.
    - Normality and homogeneity of variance (similar to ANOVA).
2. **Run the Analysis**:
    - Perform ANCOVA to compare the adjusted means of the diets while controlling for starting weight.
    - The output will provide the adjusted means and indicate if there are significant differences between the diets after accounting for starting weight.