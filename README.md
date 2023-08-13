# PPP-Loan-Distribution-and-Employment-Impact-in-Connecticut
Connecticut's PPP Journey: Exploring Loan Distribution, Employment Impact, and Demographic Trends
#PPP Loans to Connecticut Businesses Analysis

![Interactive map](https://github.com/MTanguin/PPP-Loan-Distribution-and-Employment-Impact-in-Connecticut/assets/114210481/823a7176-c6ae-4364-9e2d-1d2936bc207e)



## Overview

The Paycheck Protection Program (PPP) loans have been instrumental in assisting small businesses by providing resources to maintain their payroll, rehire employees, and cover operational expenses. This project focuses on analyzing the dataset of PPP loans provided to businesses in Connecticut. The dataset includes information on loan amounts, jobs saved, National Industry Classification (NAICS) codes, and more.

## Data Source

The dataset used for this analysis is sourced from [Data.gov](https://catalog.data.gov/dataset/ppp-loans-to-connecticut-businesses). It encompasses PPP loans granted to Connecticut businesses up to August 8, 2020. The dataset includes loans under $150,000 as well as loans of $150,000 and above.

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

3. **Geospatial Analysis**: BigQuery's geospatial capabilities enable the mapping of loan distribution across different regions in Connecticut.

### Insights and Visualizations

The analyses lead to the creation of insightful visualizations, aiding in the interpretation of findings:

1. **Graphs and Charts**: Visualizations like bar charts, pie charts, and scatter plots are generated to represent loan distribution, loan amounts, jobs saved, and other relevant metrics.

2. **Geospatial Maps**: Geographic information system (GIS) tools can be employed to create maps showcasing loan distribution by location, providing a spatial perspective.

## Analyses and Insights

1. **Loan Distribution by Loan Range**: Visualizes the distribution of loans based on various loan ranges, providing an overview of how loans are distributed across different ranges.

- Research Question: How are PPP loans distributed among different loan ranges, and what is the prevalence of loans in each range in Connecticut businesses?

2. **Total Loan Amount and Jobs Saved**: Calculates the total loan amount disbursed to Connecticut businesses and the total number of jobs claimed to be saved. This insight offers a comprehensive understanding of the PPP program's employment impact.

- Research Question: What is the overall magnitude of the PPP loan disbursement to Connecticut businesses, and how many jobs were claimed to be saved through these loans?

3. **Distribution of Business Types (NAICS Codes)**: Analyzes the distribution of businesses based on their NAICS codes, revealing industries that received the most funding and those most affected.

- Research Question: Which industries in Connecticut received the most funding through PPP loans, and which industries were particularly affected or benefited from the program?


4. **Distribution of Loan Amounts by Business Type**: Provides a visualization of loan amount distributions for different business types, aiding in the identification of average loan amounts within specific business categories.

Research Question: How do loan amounts vary across different types of businesses in Connecticut, and what is the average loan amount for specific business categories?

5. **Gender and Ethnicity Analysis**: Explores trends in loan distribution, loan amounts, and jobs saved based on gender and ethnicity, shedding light on potential disparities.

- Research Question: Are there any disparities in the distribution of PPP loans, loan amounts, and jobs saved based on gender and ethnicity among Connecticut businesses?

6. **Lender Analysis**: Investigates the lenders involved in PPP loans, calculating the total loan amount distributed by each lender and highlighting their role in supporting businesses during the pandemic.

- Research Question: Which lenders played a significant role in distributing PPP loans to Connecticut businesses, and how did their loan disbursements contribute to supporting businesses during the pandemic?

7. **Geographic Analysis**: Visualizes the geographic distribution of loans across Connecticut's cities and regions, identifying areas with higher loan activity and possible contributing factors.

- Research Question: In which cities and regions of Connecticut were PPP loans most concentrated, and what factors might have contributed to the varying loan activity across different geographic areas?

8. **Non-Profit vs. For-Profit Analysis**: Compares the impact of PPP loans on non-profit and for-profit organizations, examining loan amounts, jobs saved, and other metrics.

- Research Question: How does the impact of PPP loans differ between non-profit and for-profit organizations in Connecticut, considering loan amounts, jobs saved, and other relevant metrics?

9. **Time Trends**: Plots loan approval dates over time to identify trends or spikes, aiding in the understanding of demand fluctuations and program administration changes.

- Research Question: Are there any noticeable trends or spikes in the approval of PPP loans over time in Connecticut, and how do these trends correlate with changes in program administration and business demand?

10. **Loan Amount vs. Jobs Saved**: Creates a scatter plot to visualize the correlation between loan amounts and the number of jobs saved, providing insights into the relationship between loan size and employment impact.

- Research Question: What is the relationship between the size of PPP loan amounts and the number of jobs claimed to be saved, and does this relationship provide insights into the employment impact of different loan sizes?

## Conclusion

These analyses aim to uncover valuable insights into the distribution of PPP loans, industries that benefitted, demographic impact, and more. It is essential to ensure that all analyses are conducted with accuracy, impartiality, and alignment with project goals........



.......
