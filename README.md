# A-B-Testing-on-Different-Versions-of-a-Website

# A/B Testing Project README

## Business Case
In this project, I conducted an A/B test to evaluate the effectiveness of a new webpage design (treatment) compared to the old webpage design (control) in terms of conversion rates. The goal is to determine whether the new design leads to a statistically significant increase in conversions compared to the old design.

## Data Description
The dataset used in this project contains the following columns:
- `user_id`: Unique identifier for each user.
- `timestamp`: Timestamp of user interaction.
- `group`: Indicates whether the user was in the control or treatment group.
- `landing_page`: Indicates whether the user landed on the old or new webpage.
- `converted`: Binary variable indicating whether the user converted (1) or not (0).

## Exploratory Data Analysis (EDA)
We performed an exploratory data analysis to gain insights into the dataset, including:
- Summary statistics for numeric variables.
- Distribution of categorical variables.
- Visualization of conversion rates by group and landing page.
- Hypothesis testing to compare conversion rates between groups.

## Hypotheses
- Null Hypothesis (\(H_0\)): The conversion rate for the treatment group is equal to or less than the conversion rate for the control group.
- Alternative Hypothesis (\(H_1\)): The conversion rate for the treatment group is greater than the conversion rate for the control group.

## Statistical Tests
We used two statistical tests to compare conversion rates between the control and treatment groups:
1. Z-test for Proportions: A test to compare the proportion of conversions in two independent groups.
2. Chi-square Test: A test to assess the association between two categorical variables.

## Results
Both the Z-test for proportions and the chi-square test yielded p-values greater than the significance level (\(\alpha = 0.05\)). Therefore, we failed to reject the null hypothesis, indicating insufficient evidence to suggest a significant difference in conversion rates between the control and treatment groups.

## Conclusion
Based on the results of the A/B test, we did not find evidence to support the effectiveness of the new webpage design in increasing conversions compared to the old design. Further analysis and experimentation may be necessary to explore other factors or variables that could influence conversion rates.



## License
This project is licensed under the [MIT License](LICENSE).
