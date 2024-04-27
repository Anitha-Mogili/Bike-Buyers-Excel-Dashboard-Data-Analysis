# About the Data:
The data set was downloaded from Kaggle. It is sales data of a bike company operating in three major regions like United states, Europe and the Pacific. It comprises of 13 distinct columns and 1027 rows. This dataset contains variables like age, sex, marital status, homeowner, children and their bike sale decision.

# Original Dataset:
![image](https://github.com/Anitha-Mogili/Bike-Sales-Excel-Dashboard-Data-Analysis/assets/64921654/852fdf0a-e7c1-4419-b3b4-e639c96b51af)


# Data Cleaning:
The first step was performing these data cleaning tasks, to ensure that the Bike Sales dataset is accurate, consistent, and ready for further analysis, enabling meaningful insights to be extracted and actionable decisions to be made:

**Removing Duplicates:** Identifying and eliminating duplicate entries in the dataset to prevent skewing of analysis results.

**Formatting:** Changed the format of the income column in order to obtain better visualization.

**Standardizing data:** Using Find and Replace renamed the records in Marital Status Column from ‘M’ and ‘S’ to ‘Married’ and ‘Single’ for better understanding. The same was done with Gender Column renaming the records ‘M’ and ‘F’ to ‘Male’ and ‘Female'.

**Grouping and Aggregating:** Used Nested IF statements on the Age Column to group/create Age Brackets such Adolescent (Age below 31), Middle Age (Age between 31 and 54), Old (Age above 54).

# Cleaned Dataset:
![image](https://github.com/Anitha-Mogili/Bike-Sales-Excel-Dashboard-Data-Analysis/assets/64921654/afbf581d-3155-4e47-af48-c519867d4008)


# Pivot Tables:
Pivot tables were utilized to aggregate and summarize the data, enabling easy exploration and identification of trends. The pivot tables allow for dynamic grouping, filtering, and calculation of metrics, providing valuable insights into the Bike Sales patterns and associated factors.

# Excel Dashboard:
An Excel dashboard was created to present key findings and visualizations from the data analysis. The dashboard includes interactive charts, tables, filters and pivot tables to provide an intuitive and comprehensive view of the data.
Inserted three slicers in order to be able to filter the data making the dashboard interactive. These slicers would filter the dashboard by Marital status, Region and Education, thus revealing more details about the data when a particular filter is applied.

 ![image](https://github.com/Anitha-Mogili/Bike-Sales-Excel-Dashboard-Data-Analysis/assets/64921654/b32cc723-bfc2-478d-8359-d6adb130b4c1)


# Insights:
•	The Commute Distance played a major role in a making decision of whether purchasing a bike or not. People who lived closed to their workplace took the top place of Sales. 

•	On an overall, there is an equal proportion of sales among male and female customers. Male has 50% while female 50%. But if we filter by Region: In Europe Females lead the Sales by making 55% sales. In Pacific it is the opposite with Male leading the sales and in the United States it is an equal proportion.

•	Majority of our customers are Middle Aged (31–54 years), followed by Old Aged (>54 years). Adolescents (<31 years) makes up a little proportion of the total sales

•	The Average income showed a significant difference in the sales. With this we can assume that the bikes weren’t affordable for all income groups.

# Recommendations:
•	The Bike Company should keep this in mind and in order to gain more customers introduce new features like electric bikes at low/affordable price range to target both average income as well as people who live far away from their workplace.

•	The company should prioritize targeting United Sates and Middle Aged customers as they made up the majority of their customer base. But also, not neglecting the other groups by advertising more, bringing new models suitable for Adolescents and old aged people.
