# A/B Testing for Conversion Rate Optimization
This project aims to conduct an A/B test to evaluate the effectiveness of a new design in improving the conversion rate compared to the old design. The project follows a structured approach to analyze the results and draw meaningful conclusions.
![image](https://github.com/Aftabbs/A-B-Testing-for-Conversion-Rate-Optimization/assets/112916888/f8b80625-837d-4a3a-8cc3-2401d2e275dc)

# Project Overview
The goal of the project is to determine whether the new design leads to a statistically significant increase in the conversion rate compared to the old design. The following steps were followed:

- Data Cleaning: The dataset was cleaned to remove any duplicate user sessions.

- Sample Size Determination: Power analysis was conducted to calculate the required sample size for each group, considering the desired effect size, statistical power, and significance level.

- Sampling: Simple random sampling was performed to obtain equal-sized samples for the control and treatment groups.

- Conversion Rate Analysis: The conversion rates for each group were calculated, along with standard deviation and standard error.

- Hypothesis Testing: A z-test was conducted to test the null hypothesis that there is no significant difference in conversion rates between the two groups.

- Results Interpretation: The p-value and confidence intervals were analyzed to determine the statistical significance and practical significance of the results.

# Results and Conclusion
The analysis revealed that the new design did not result in a statistically significant improvement in the conversion rate compared to the old design. The p-value obtained (0.732) was much higher than the significance level of 0.05, indicating insufficient evidence to reject the null hypothesis.

Furthermore, the confidence interval for the treatment group included the baseline conversion rate but did not include the target value. This suggests that the new design is more likely to have a similar conversion rate to the baseline, rather than achieving the desired uplift.

Based on these findings, it is concluded that the new design is not likely to be an improvement over the old design. Further iterations and improvements may be necessary to achieve the desired conversion rate.

# Usage
The project code and analysis can be found in the Jupyter Notebook provided in this repository. The notebook includes detailed explanations of each step and can serve as a reference for conducting A/B testing for conversion rate optimization.

# Dependencies
The following libraries were used in this project:

numpy
pandas
seaborn
scikit-learn
statsmodels
Make sure these dependencies are installed to execute the code successfully.

# Future Improvements
Although the results did not show a significant improvement in the conversion rate, there are several areas for future improvement:

- Increase Sample Size: Consider increasing the sample size to achieve higher statistical power and detect smaller differences in conversion rates.

- Iterative Testing: Conduct iterative A/B testing with further design modifications to identify potential improvements and optimize the conversion rate.

- Segment Analysis: Perform a segmentation analysis to understand if specific user segments respond differently to the new design.
 
- User Feedback: Gather qualitative feedback from users to identify potential usability issues or areas for improvement.







