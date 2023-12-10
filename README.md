# Graphical-perception-in-children
A statistical analysis to understand the factors that affect the graphical perception in children of age 10 to 12 years

*Abstract:* \
This study bridges the gap in visualization guidelines for children by investigating the impact of age and gender on angle perception in 8-12-year-olds. Analyzing MeanAngleAbsError in a dataset of 57 observations, we propose two models. Results show independent effects of age and gender, with no strong evidence for interaction. Pairwise comparisons reveal significant gender differences, contributing empirical evidence for age-appropriate visualization design guidelines.

*Introduction:* \
Effective visualization design is crucial in education, yet current guidelines focus on adults. This study, inspired by previous work, explores how age and gender influence angle perception in children. The goal is to inform the development of age-appropriate visualization guidelines for enhanced learning experiences.

*Methods:* \
Using multi-variable linear regression, we test the hypothesis that age and gender affect mean angle error rates. The dataset comprises 57 observations with demographic details and perceptual accuracy measures. Data preparation involves creating a new variable, MeanAngleAbsError, simplifying analysis. Treatment means plot reveals trends in age and gender impact on angle estimation.

*Models:* \
Two models are proposed - fixed-effect model with and without interaction. The fixed-effect model with interaction includes factors for age, gender, and their interaction. The fixed-effect model without interaction considers age and gender as separate factors without assuming interaction effects.

*Results:* \
The fixed-effect model with interaction shows significant gender differences but no age effect. Residual analysis indicates non-normal distribution. Pairwise comparisons confirm gender differences. The fixed-effect model without interaction identifies significant age and gender effects. Residuals are normally distributed, suggesting a better fit.

*Discussions:* \
Results indicate that age and gender independently influence mean angle error rates. Considering participants as random does not significantly improve results. Calculating the overall mean of errors leads to similar conclusions, except for gender-age interaction, suggesting further investigation.

*Limitations and Future Work:* \
The analysis can be extended by incorporating additional factors like grades and occupations. Including subjects such as Math, English, and Art grades for children, and occupations for adults, can provide a more comprehensive understanding of visual measurement influences.

*Conclusion:*
This study offers valuable insights into age-appropriate visualization design for children. The fixed-effect model without interaction is considered the final model, providing guidance for educators and designers to create impactful visualizations tailored to children's cognitive processes. Future work includes exploring additional factors to refine the understanding of visual measurement abilities.
