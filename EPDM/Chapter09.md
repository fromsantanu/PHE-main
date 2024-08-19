### Chapter 9: Measures of Association: Relative Risk and Odds Ratio

#### 9.1 Introduction

In analytical epidemiology, understanding the relationship between exposures and health outcomes is essential for identifying risk factors and establishing causality. **Measures of association** are statistical tools that quantify the strength of the relationship between an exposure and an outcome. Two of the most commonly used measures in epidemiological research are **Relative Risk (RR)** and **Odds Ratio (OR)**. This chapter explores these measures in detail, explaining their calculation, interpretation, and application in different study designs.

#### 9.2 Relative Risk (RR)

##### 9.2.1 Definition

**Relative Risk (RR)**, also known as the **Risk Ratio**, is a measure that compares the risk of a health outcome among individuals exposed to a particular factor with the risk among those who are not exposed. It is commonly used in cohort studies where the incidence of a disease can be directly measured.

##### 9.2.2 Calculation

Relative Risk is calculated using the following formula:


$\text{Relative Risk (RR)} = \frac{\text{Risk in the exposed group}}{\text{Risk in the unexposed group}}$


Where:
- **Risk in the exposed group** = \(\frac{\text{Number of exposed individuals who develop the outcome}}{\text{Total number of exposed individuals}}\)
- **Risk in the unexposed group** = \(\frac{\text{Number of unexposed individuals who develop the outcome}}{\text{Total number of unexposed individuals}}\)

##### 9.2.3 Interpretation

- **RR = 1**: The risk of the outcome is the same in both the exposed and unexposed groups, indicating no association between the exposure and the outcome.
- **RR > 1**: The risk of the outcome is higher in the exposed group compared to the unexposed group, suggesting that the exposure may be a risk factor for the outcome.
- **RR < 1**: The risk of the outcome is lower in the exposed group compared to the unexposed group, suggesting that the exposure may have a protective effect.

##### 9.2.4 Application

Relative Risk is most commonly used in **cohort studies** because these studies track the incidence of disease over time. It is a direct measure of how much more (or less) likely an exposed individual is to develop the outcome compared to an unexposed individual. 

**Example**: Suppose researchers conduct a cohort study to investigate the relationship between smoking and lung cancer. If the incidence of lung cancer among smokers (the exposed group) is 30 per 1,000 individuals per year, and the incidence among non-smokers (the unexposed group) is 10 per 1,000 individuals per year, the Relative Risk would be:


$RR = \frac{30/1000}{10/1000} = 3.0$


This indicates that smokers are three times more likely to develop lung cancer than non-smokers.

#### 9.3 Odds Ratio (OR)

##### 9.3.1 Definition

**Odds Ratio (OR)** is a measure of association that compares the odds of an outcome occurring in the exposed group to the odds of it occurring in the unexposed group. The Odds Ratio is commonly used in case-control studies where the incidence of the disease is not directly measurable, but the odds can be estimated.

##### 9.3.2 Calculation

The Odds Ratio is calculated using the following formula:


$\text{Odds Ratio (OR)} = \frac{\text{Odds of outcome in exposed group}}{\text{Odds of outcome in unexposed group}}$


Where:
- **Odds of outcome in exposed group** = \(\frac{\text{Number of exposed individuals with the outcome}}{\text{Number of exposed individuals without the outcome}}\)
- **Odds of outcome in unexposed group** = \(\frac{\text{Number of unexposed individuals with the outcome}}{\text{Number of unexposed individuals without the outcome}}\)

Alternatively, in a 2x2 contingency table:


$\text{Odds Ratio (OR)} = \frac{(A/C)}{(B/D)} = \frac{AD}{BC}$


Where:
- **A** = Number of cases with exposure
- **B** = Number of controls with exposure
- **C** = Number of cases without exposure
- **D** = Number of controls without exposure

##### 9.3.3 Interpretation

- **OR = 1**: The odds of the outcome are the same in both the exposed and unexposed groups, indicating no association.
- **OR > 1**: The odds of the outcome are higher in the exposed group, suggesting a positive association between the exposure and the outcome.
- **OR < 1**: The odds of the outcome are lower in the exposed group, suggesting a negative association (protective effect) between the exposure and the outcome.

##### 9.3.4 Application

Odds Ratio is primarily used in **case-control studies** because these studies do not follow participants over time and therefore cannot measure the incidence of disease. Instead, the OR provides an estimate of the relative risk when the disease is rare.

**Example**: In a case-control study investigating the relationship between asbestos exposure and mesothelioma, suppose 40 out of 50 mesothelioma cases (the exposed group) had a history of asbestos exposure, while 10 out of 50 controls (the unexposed group) had such a history. The Odds Ratio would be:


$OR = \frac{(40 \times 40)}{(10 \times 10)} = \frac{1600}{100} = 16.0$


This suggests that individuals with a history of asbestos exposure are 16 times more likely to develop mesothelioma than those without such exposure.

#### 9.4 Relative Risk vs. Odds Ratio

While both Relative Risk and Odds Ratio are used to measure the association between exposure and outcome, they are applied in different contexts and interpreted differently:

- **Study Design**: Relative Risk is generally used in cohort studies, while Odds Ratio is used in case-control studies. In cross-sectional studies, either measure can be used depending on the study design and objectives.
- **Interpretation**: Relative Risk provides a direct measure of risk, whereas the Odds Ratio measures the odds and is an approximation of the Relative Risk, particularly when the outcome is rare.
- **When to Use**: Use Relative Risk when the incidence data are available and you can measure the risk directly. Use Odds Ratio in case-control studies where incidence data are not available, or in situations where the outcome is rare, and the OR closely approximates the RR.

#### 9.5 Limitations of Relative Risk and Odds Ratio

While Relative Risk and Odds Ratio are powerful tools, they have limitations:

##### 9.5.1 Limitations of Relative Risk

- **Not Applicable in Case-Control Studies**: Relative Risk requires incidence data, which are typically not available in case-control studies.
- **May Be Misleading with High Outcome Incidence**: When the outcome is common, the Relative Risk can overestimate the strength of association.

##### 9.5.2 Limitations of Odds Ratio

- **Interpretation Complexity**: The Odds Ratio can be more challenging to interpret than Relative Risk, especially for non-epidemiologists. The odds are not intuitive for most people.
- **Overestimation of Risk**: In case-control studies where the outcome is not rare, the Odds Ratio can overestimate the actual risk, making the association appear stronger than it is.

#### 9.6 Practical Considerations

When choosing between Relative Risk and Odds Ratio in your analysis, consider the following:

- **Study Design**: Use RR in cohort studies and OR in case-control studies.
- **Outcome Frequency**: If the outcome is rare (e.g., less than 10%), the OR will approximate the RR, making the OR a reasonable measure even in non-case-control studies.
- **Audience**: Consider your audience when presenting results. If your audience is unfamiliar with odds, consider explaining the OR in terms of increased or decreased likelihood.

#### 9.7 Conclusion

Relative Risk and Odds Ratio are fundamental measures of association in analytical epidemiology, providing insights into the relationship between exposures and outcomes. While they serve similar purposes, their application depends on the study design and the nature of the data. Understanding how to calculate, interpret, and apply these measures is essential for conducting rigorous epidemiological research and making informed public health decisions.

#### 9.8 Key Terms
- **Relative Risk (RR)**: A measure of association that compares the risk of a health outcome in the exposed group to the risk in the unexposed group, typically used in cohort studies.
- **Odds Ratio (OR)**: A measure of association that compares the odds of a health outcome in the exposed group to the odds in the unexposed group, commonly used in case-control studies.
- **Incidence**: The rate at which new cases of a disease occur in a population over a specific period.
- **Risk**: The probability that an individual will develop a disease or health outcome over a specified period.
- **Odds**: The likelihood that an event will occur compared to the likelihood that it will not.

---

This chapter provides a comprehensive understanding of Relative Risk and Odds Ratio, key measures of association in analytical epidemiology. Mastery of these concepts is essential for interpreting the results of epidemiological studies and applying them to public health practice.
