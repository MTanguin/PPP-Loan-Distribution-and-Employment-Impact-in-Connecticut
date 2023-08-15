# PPP-Loan-Distribution-and-Employment-Impact-in-Connecticut
Connecticut's PPP Journey: Exploring Loan Distribution, Employment Impact, and Demographic Trends
#PPP Loans to Connecticut Businesses Analysis

![Interactive map](https://github.com/MTanguin/PPP-Loan-Distribution-and-Employment-Impact-in-Connecticut/assets/114210481/823a7176-c6ae-4364-9e2d-1d2936bc207e)

[Interactive Map Loan Distribution](https://mtanguin.github.io/PPP-Loan-Distribution-and-Employment-Impact-in-Connecticut//interactive_loan_distribution_map.html)

## Overview

The Paycheck Protection Program (PPP) loans have been instrumental in assisting small businesses by providing resources to maintain their payroll, rehire employees, and cover operational expenses. This project focuses on analyzing the dataset of PPP loans provided to businesses in Connecticut. The dataset includes information on loan amounts, jobs saved, National Industry Classification (NAICS) codes, and more.

## Data Sources

1. [PPP Loans to Connecticut Businesses](https://catalog.data.gov/dataset/ppp-loans-to-connecticut-businesses)

    Description: This dataset provides information about PPP loans granted to Connecticut businesses. It encompasses PPP loans granted to Connecticut businesses up to August 8, 2020. The dataset includes loans under $150,000 as well as loans of $150,000 and above.

3. [TIGER/Line Shapefile 2019: County Subdivision](https://catalog.data.gov/dataset/tiger-line-shapefile-2019-state-connecticut-current-county-subdivision-state-based)

    Description: The TIGER/Line shapefiles and related database files (.dbf) are an extract of selected geographic and cartographic information from the U.S. Census Bureau's MAF/TIGER Database. This dataset includes county subdivisions, which are the primary divisions of counties and their equivalent entities for the reporting of Census Bureau data.


## Methodology

### Data Collection

The analysis starts with the collection of the PPP loan dataset from the provided Data.gov source. The dataset may be available in various formats such as CSV, Excel, or JSON. The data is downloaded and stored in a structured format for further processing.

### Data Processing

1. **Data Cleaning**: The collected dataset undergoes thorough cleaning to handle missing values, outliers, and inconsistencies. This ensures that the subsequent analyses are based on reliable and accurate data.

2. **Data Exploration**: Initial exploratory analysis involves understanding the data's structure, summarizing key statistics, and identifying any patterns or trends that may guide subsequent analyses.

### BigQuery Analysis

For larger datasets or more complex analyses, BigQuery can be employed:

1. **Data Import**: The cleaned dataset is imported into Google BigQuery, a powerful data warehousing and querying platform.

2. **SQL Queries**: SQL queries are utilized to perform various analyses, such as calculating total loan amounts, aggregating jobs saved, and segmenting data based on NAICS codes, gender, ethnicity, and more.

### Geospatial Analysis

Geopandas's geospatial capabilities enable the mapping of loan distribution across different regions in Connecticut.

Enables interactive loan distribution map using Folium, a Python library for creating interactive maps.

### Insights and Visualizations

The analyses lead to the creation of insightful visualizations, aiding in the interpretation of findings:

1. **Graphs and Charts**: Visualizations like bar charts, pie charts, and scatter plots are generated to represent loan distribution, loan amounts, jobs saved, and other relevant metrics.

2. **Geospatial Maps**: Geographic information system (GIS) tools can be employed to create maps showcasing loan distribution by location, providing a spatial perspective.

## Analyses and Insights

1. **Loan Distribution by Loan Range**: Visualizes the distribution of loans based on various loan ranges, providing an overview of how loans are distributed across different ranges.

- Research Question: How are PPP loans distributed among different loan ranges, and what is the prevalence of loans in each range in Connecticut businesses?

  ![Loan Distribution by Loan Range](https://github.com/MTanguin/PPP-Loan-Distribution-and-Employment-Impact-in-Connecticut/assets/114210481/4fc0b308-8ff9-4f7b-a44b-ba37f12d7b75)


2. **Total Loan Amount and Jobs Saved**: Calculates the total loan amount disbursed to Connecticut businesses and the total number of jobs claimed to be saved. This insight offers a comprehensive understanding of the PPP program's employment impact.

- Research Question: What is the overall magnitude of the PPP loan disbursement to Connecticut businesses, and how many jobs were claimed to be saved through these loans?
  
  ![Total Loan Amount and Jobs Saved](https://github.com/MTanguin/PPP-Loan-Distribution-and-Employment-Impact-in-Connecticut/assets/114210481/25783059-1e95-46cc-9937-d565be1b8c83)

3. **Distribution of Business Types (NAICS Codes)**: Analyzes the distribution of businesses based on their NAICS codes, revealing industries that received the most funding and those most affected.

- Research Question: Which industries in Connecticut received the most funding through PPP loans, and which industries were particularly affected or benefited from the program?
  
  ![Top 20 Distribution of Business Types (NAICS Codes)](https://github.com/MTanguin/PPP-Loan-Distribution-and-Employment-Impact-in-Connecticut/assets/114210481/09d3033d-4570-43d0-b1f7-eb8c9e36b066)


4. **Distribution of Loan Amounts by Business Type**: Provides a visualization of loan amount distributions for different business types, aiding in the identification of average loan amounts within specific business categories.

- Research Question: How do loan amounts vary across different types of businesses in Connecticut, and what is the average loan amount for specific business categories?

![Distribution of Loan Amounts by Business Type](https://github.com/MTanguin/PPP-Loan-Distribution-and-Employment-Impact-in-Connecticut/assets/114210481/6769d120-8b4b-49cb-844e-74fe97e8ca81)


5. **Gender and Ethnicity Analysis**: Explores trends in loan distribution, loan amounts, and jobs saved based on gender and ethnicity, shedding light on potential disparities.

- Research Question: Are there any disparities in the distribution of PPP loans, loan amounts, and jobs saved based on gender and ethnicity among Connecticut businesses?

  ![Gender and Ethnicity Analysis Loan Amounts vs  Jobs Saved](https://github.com/MTanguin/PPP-Loan-Distribution-and-Employment-Impact-in-Connecticut/assets/114210481/9962f005-25c5-408a-b485-cf9960347be4)


6. **Lender Analysis**: Investigates the lenders involved in PPP loans, calculating the total loan amount distributed by each lender and highlighting their role in supporting businesses during the pandemic.

- Research Question: Which lenders played a significant role in distributing PPP loans to Connecticut businesses, and how did their loan disbursements contribute to supporting businesses during the pandemic?

  ![Top 10 LendersTotal Loan Amounts](https://github.com/MTanguin/PPP-Loan-Distribution-and-Employment-Impact-in-Connecticut/assets/114210481/dffadf12-2593-42c2-9d4d-70eff9e147e2)


7. **Geographic Analysis**: Visualizes the geographic distribution of loans across Connecticut's cities and regions, identifying areas with higher loan activity and possible contributing factors.

- Research Question: In which cities and regions of Connecticut were PPP loans most concentrated, and what factors might have contributed to the varying loan activity across different geographic areas?

  ![Distribution of PPP Loans by City in Connecticut](https://github.com/MTanguin/PPP-Loan-Distribution-and-Employment-Impact-in-Connecticut/assets/114210481/6daa407b-5f79-4931-a3a4-2d4b8b2783bc)


8. **Non-Profit vs. For-Profit Analysis**: Compares the impact of PPP loans on non-profit and for-profit organizations, examining loan amounts, jobs saved, and other metrics.

- Research Question: How does the impact of PPP loans differ between non-profit and for-profit organizations in Connecticut, considering loan amounts, jobs saved, and other relevant metrics?

  ![Non-Profit vs  For-Profit Analysis](https://github.com/MTanguin/PPP-Loan-Distribution-and-Employment-Impact-in-Connecticut/assets/114210481/6bd6be8d-22c2-4546-9e84-710662ac3ab7)

  - The results of the analysis provide insights into the comparison between non-profit and for-profit organizations regarding their loan amounts and jobs saved through PPP loans. 

    Non-Profit Metrics:

    Average Loan Amount: $42,704 Average Jobs Saved: 25 For-Profit Metrics:

    Average Loan Amount: $33,328 Average Jobs Saved: 9.6 These metrics represent the averages for loan amounts and jobs saved for both non-profit and for-profit organizations.

    Loan Amount T-Test: T-Statistic: 11.91 P-Value: ~0.00 (very close to 0) The t-test for loan amounts indicates a statistically significant difference between non-profit and for-  profit organizations in terms of the loan amounts they received. The low p-value suggests that the difference in average loan amounts between these two groups is unlikely to have occurred by chance.

    Jobs Saved T-Test: T-Statistic: 25.75 P-Value: ~0.00 (very close to 0) The t-test for jobs saved shows a highly significant difference between non-profit and for-profit organizations in terms of the number of jobs they reported saving through PPP loans. The very low p-value indicates that the difference in average jobs saved between the two groups is highly unlikely to be due to random variation.

    In summary, the analysis suggests that there are significant differences between non-profit and for-profit organizations in terms of both loan amounts received and jobs saved through PPP loans. Non-profit organizations, on average, received higher loan amounts and reported saving more jobs compared to for-profit organizations. The low p-values from the t-tests further support these findings


9. **Loan Amount vs. Jobs Saved**: Creates a scatter plot to visualize the correlation between loan amounts and the number of jobs saved, providing insights into the relationship between loan size and employment impact.

- Research Question: What is the relationship between the size of PPP loan amounts and the number of jobs claimed to be saved, and does this relationship provide insights into the employment impact of different loan sizes?

  ![Loan Amount vs Jobs Saved](https://github.com/MTanguin/PPP-Loan-Distribution-and-Employment-Impact-in-Connecticut/assets/114210481/fae564ff-ca7c-44e3-9fa5-8733261a4ff2)
  
  - Correlation Coefficient: 0.40662868403941743
  There is a positive correlation between loan size and impact on employment

  The correlation coefficient value of 0.406 suggests a positive correlation between loan size (Loan Amount) and the impact on employment (Jobs Saved). When the correlation coefficient is positive, it indicates that as one variable increases, the other variable tends to increase as well.

  In this context, a correlation coefficient of 0.406 indicates that there is a moderate positive relationship between the loan size and the impact on employment. This means that as the loan size increases, there is a tendency for the number of jobs saved to also increase. However, it's important to note that correlation does not imply causation, and other factors could be influencing this relationship.

  In summary, the positive correlation between loan size and impact on employment suggests that organizations that received larger PPP loans tend to report higher numbers of jobs saved.

10. **Time Trends**: Plots loan approval dates over time to identify trends or spikes, aiding in the understanding of demand fluctuations and program administration changes.

- Research Question: Are there any noticeable trends or spikes in the approval of PPP loans over time in Connecticut, and how do these trends correlate with changes in program administration and business demand?

  ![Time Trends Loan Approvals Over Time](https://github.com/MTanguin/PPP-Loan-Distribution-and-Employment-Impact-in-Connecticut/assets/114210481/5bf38f89-b6e7-41d5-957f-9eb1ee452d21)

  Spikes: There was a sharp increase in loan approvals in April 28, 2020 with 6400 appoved loans and another one in May 3, 2020 with 4696 counts of approved loans. These spikes could indicate periods of high demand or changes in program administration that led to increased loan processing.

  High Demand Periods: Spikes in the line plot can suggest periods of high demand for PPP loans. These periods could correspond to when businesses urgently sought financial assistance due to economic challenges or uncertainty.

  Program Changes: The sudden changes in the slope of the line might indicate alterations in the program's guidelines, eligibility criteria, or application process. Such changes could lead to shifts in the number of loan approvals

  ##### Outliers and data anomalies in the loan approval data
  
  Statistical methods and visualization techniques:

  Box Plot: Create box plots of the loan amount and number of jobs saved to identify potential outliers. Outliers are data points that significantly deviate from the rest of the data.

  Z-Score: Calculate the Z-score for the loan amount and jobs saved columns. Z-score measures how many standard deviations a data point is away from the mean. A high Z-score indicates   an outlier.

  IQR Method: Calculate the Interquartile Range (IQR) and identify data points that fall outside the 1.5 * IQR range. These are potential outliers.

  Scatter Plots: Create scatter plots between loan amount and jobs saved to visually inspect any unusual patterns or outliers.
  
  ![Outliers and data anomalies in the loan approval data](https://github.com/MTanguin/PPP-Loan-Distribution-and-Employment-Impact-in-Connecticut/assets/114210481/fb87d8c0-11dd-44eb-b2e1-64b1fc2485d2)

    The potential loan amount outliers that have been identified through the Z-score and IQR methods have significantly high Z-scores, suggesting that they deviate from the mean loan amount to a considerable extent. These outliers could be indicative of unusual loan amounts compared to the majority of the dataset.

    There are a few possible explanations for these potential loan amount outliers:

  - Large Businesses or Special Cases: Some of these large loan amounts might belong to bigger businesses or organizations with specific financial needs. They could be receiving larger loans due to their size, industry, or specific circumstances.

  - Specific Industries: Certain industries might require substantial financial assistance due to their capital-intensive nature or the challenges they faced during the economic downturn. These industries might have requested larger loan amounts to sustain their operations.

  - Data Anomalies: In some cases, data entry errors or anomalies could lead to inflated loan amounts. It's worth investigating if these outliers are due to any mistakes in data recording.

  - Government Policies or Support: The PPP program might have had different rules or support for certain sectors, leading to larger loan amounts for eligible businesses.

  - Geographical Considerations: Businesses located in areas with high living costs or affected more severely by the pandemic might require larger loans to cover their operational expenses.


## Conclusion

These analyses aim to uncover valuable insights into the distribution of PPP loans, industries that benefitted, demographic impact, and more. It is essential to ensure that all analyses are conducted with accuracy, impartiality, and alignment with project goals........

It's important to carefully investigate these potential outliers to determine their validity and whether they should be included in your analysis. Domain expertise, industry knowledge, and additional data sources could help provide context and insight into the reasons behind these unusual loan amounts.

## Disclaimer

The data provided in this repository is sourced from external websites and databases. The data is intended for educational and learning purposes only. While the creator has strived to ensure the accuracy and reliability of the data, its completeness or suitability for any specific purpose cannot be guaranteed. Users of this data are advised to independently verify its accuracy and exercise caution when using it for critical applications. The creators of this repository are not liable for any damages or losses that may arise from the use of this data.

