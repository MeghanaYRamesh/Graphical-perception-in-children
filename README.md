# Graphical-perception-in-children
A statistical analysis to understand the factors that affect the graphical perception in children of age 10 to 12 years

*Breif information about the analysis:* \
This study addresses the gap in visualization design guidelines tailored for children's cognitive processes. Focusing on graphical perception, the project explores how age and gender influence the visual perception of angles in children aged 8-10. The dataset comprises 57 observations, analyzing MeanAngleAbsError. Two models are proposed: a fixed-effect model with interaction and a fixed-effect model without interaction. Results indicate that both age and gender independently influence mean angle absolute error, with no strong evidence supporting an interaction effect. Pairwise comparisons reveal significant differences in MeanAngleAbsError between females and males. The study contributes empirical evidence for age-appropriate visualization design guidelines, enhancing children's learning experiences. The fixed-effect model without interaction is considered the final model, offering insights into factors influencing angle estimation abilities in children. Future work includes incorporating additional factors like grades and occupations for a more comprehensive analysis.

*Data:* \
The data used in this study is present in the Data folder where child_data_unprocessed.csv is the original data \
The dataset comprises 57 observations, each uniquely identified by a participant ID, with participants falling into two distinct groups: Children (aged 8-12) and Adults (aged 18-29). Within the Children group, there are 33 participants, with 14 females and 19 males, while the adult group consists of 24 participants, with 11 females and 13 males. Age, recorded as a natural number, varies within the specified age ranges for each group. Additionally, gender is represented as a binary categorical variable, distinguishing between male and female participants. The participants' academic grades are captured categorically or numerically, ranging from grades 2 to 6. The dataset includes various measures of perceptual accuracy, represented by vectors of 19 nonnegative numbers (ranging from 0 to 100) for each of the following attributes: POCAAbsError (Position along a common axis), POUAAbsError (Position along an unaligned axis), LengthAbsError, AngleAbsError, and AreaAbsError \
The child_data.csv is the data after processing according to the needs of the analysis.
Data preparation involves creating a new variable, MeanAngleAbsError, simplifying analysis. Treatment means plot reveals trends in age and gender impact on angle estimation.

*Models implemented:* \
Two models are proposed - fixed-effect model with and without interaction. The fixed-effect model with interaction includes factors for age, gender, and their interaction. The fixed-effect model without interaction considers age and gender as separate factors without assuming interaction effects.

*Results:* \
The fixed-effect model with interaction shows significant gender differences but no age effect. Residual analysis indicates non-normal distribution. Pairwise comparisons confirm gender differences. The fixed-effect model without interaction identifies significant age and gender effects. Residuals are normally distributed, suggesting a better fit.

*Discussions:* \
Results indicate that age and gender independently influence mean angle error rates. Considering participants as random does not significantly improve results. Calculating the overall mean of errors leads to similar conclusions, except for gender-age interaction, suggesting further investigation.

*Conclusion:*\
This study offers valuable insights into age-appropriate visualization design for children. The fixed-effect model without interaction is considered the final model, providing guidance for educators and designers to create impactful visualizations tailored to children's cognitive processes. Future work includes exploring additional factors to refine the understanding of visual measurement abilities.


*To run the code:* \
Use child_data.csv from Data folder and project_f.rmd 
The rmd file includesincorporates result interpretation and plots to enhance comprehension.


