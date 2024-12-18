# Sales Analysis in R

## Introduction
Retail analytics plays a crucial role in understanding customer behavior and preferences, which can vary considerably based on demographic elements like gender, geographical location (branch and city), customer type, and payment methods. These factors not only influence purchasing decisions but also impact sales and overall profitability.We are interested in fundamental aspects of sales performance, customer preferences, and factors affecting gross income in retail. We want to understand gender-based product choices, sales at different branches, different payment methods, and how customer attributes impact income. Understanding these dynamics is crucial for improving marketing, making customers happier, and increasing revenue.

The previous works related to this analysis, which served as references for this research, are discussed . 
The paper researches about the application of retail analytics in developing a data analytics system for product management and sales forecasting in the retail sector. By employing machine learning algorithms such as linear regression, random forest, and XGBoost, the study showcases how advanced analytics techniques can improve forecasting accuracy and optimize inventory management, ultimately leading to enhanced decision-making and customer satisfaction in retail operations.
This paper demostrates data-driven insights, brands that can improve performance, optimize sales strategies, and reduce losses, showcasing the pivotal role of retail analytics in enhancing operational efficiency and decision-making in the retail sector.

While these research works explore retail analytics and customer satisfaction using machine learning and other feature selection methods, our focus remains on conducting statistical analysis.

## Research Questions

Does gender influence the choice of product category purchased? Are there significant differences in the distribution of product line sales between genders?

How do sales performance and customer preferences vary across different branches? Is there a branch that consistently outperforms others in terms of Ratings or gross income?

Is there a significant difference in the average total sales among various payment methods? This will help us in improving the Payment method preffered by most Customers.

How is the Gross income affected by the Rating , gender , type of customer , City , product line Payment Method etc.? This will let us know the features that gross income depend on.

Thus retail analytics is crucial for understanding customer behavior and preferences, impacting sales and profitability. This research aims to explore gender-based product choices, branch-specific sales, payment methods' impact, and factors influencing gross income , thus making an positive impact on customer satisfaction and profitability.


## Methods/Results(Experimental design and data collection) :
The dataset is taken from github which comprises sales data from three branches during January, February, and March of 2019, encompassing various product categories, gender, customer types, gross income, and customer ratings. This dataset is valuable for analyzing sales and profitability per branch, evaluating customer satisfaction, and examining gender-based differences across product categories. By leveraging this data, we can gain insights into branch performance, identify areas for improvement, and tailor marketing strategies to enhance customer experience and optimize revenue generation and improve the branches based on the customer rating and gross income.

For the analysis, different statistical tests were used to answer the research questions. These included the T-test for comparing group means, ANOVA to determine if the means of two groups are equal, linear regression modeling to identify dependent features, Durbin-Watson test to understand the nature of residuals, LM model diagnostics, and Bootstrapping with hypothesis testing to determine the best-performing branch voted by customers. Furthermore, exploratory data analysis (EDA) was performed on the data to understand its distribution and gain a basic understanding of the dataset. These statistical techniques provided valuable insights for informed decision-making for our retail analytics.


## Conclusion
The analysis conducted on the sales data yielded several valuable insights. Firstly, the gender-based analysis revealed no significant differences in purchasing behavior across most product lines, except for the "Fashion accessories" category. This finding highlights the importance of implementing gender-specific marketing strategies, particularly for fashion accessories, to cater to the distinct preferences of male and female customers effectively. Secondly, the city-wise analysis demonstrated consistent profitability across all branch locations. However, variations in customer ratings were observed, suggesting areas for improvement in certain locations. This information can be leveraged to identify and address specific factors contributing to lower customer satisfaction ratings, ultimately enhancing the overall customer experience. Thirdly, the analysis of payment methods revealed no significant differences in total sales across various payment options. This finding emphasizes the need for continued consistency and improvement in the facilitation and processing of all payment methods, ensuring optimal business performance and customer convenience. Finally, the linear model constructed for predicting gross income demonstrated promising predictive power when considering dependent features such as gender, product category, total quantity, and total sales. However, the model requires further refinement to address issues such as normality violations, heteroscedasticity, and influential outliers. By addressing these limitations, the model's accuracy and reliability can be enhanced, providing more robust and actionable insights for informed decision-making. Overall, the analysis has provided valuable insights into customer behavior, branch performance, payment preferences, and income prediction. By leveraging these findings and addressing identified areas for improvement, the company can implement targeted strategies, enhance customer satisfaction, optimize operational efficiency, and drive business growth.

Based on the insights gained from this analysis, future research can be extended in several directions.

Customer segmentation based on demographic and behavioral data can provide deeper insights into preferences and behaviors.
Analyzing specific product categories, conducting market basket analysis, and calculating Customer Lifetime Value (CLV) can enhance understanding of sales dynamics and customer value.
Advanced predictive modeling, competitive analysis, and ethical considerations should also be prioritized to ensure sustainable growth and ethical data practices in retail analytics.
