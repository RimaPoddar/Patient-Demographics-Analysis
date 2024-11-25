# **Patient-Demographics-Analysis**

## **Overview**
This project involves analyzing patient demographics from a healthcare dataset. The goal is to clean the data, extract meaningful insights, and visualize trends related to gender distribution, age statistics, and age group segmentation. The analysis provides a foundation for better understanding the population and supports data-driven decision-making in healthcare.

---

## **Features**
The project includes:
- **Data Cleaning**: Removing irrelevant columns, handling missing values, and standardizing data.
- **Descriptive Analysis**: Calculating statistics for age and gender distribution.
- **Age Group Segmentation**: Categorizing patients into defined age groups for deeper insights.
- **Visualizations**: Creating charts and graphs for better representation of trends.

---

## **Dataset**
The dataset contains patient details, including:
- Gender  
- Age  
- Date of Birth (`Dob`)  
- Other demographic information  

Irrelevant columns such as `Age Days`, `Religion`, and `Nationality` were removed during data cleaning to focus on key insights.

---

## **Technologies Used**
- **Python**: For data processing and analysis.  
- **Pandas**: For data manipulation.  
- **Matplotlib** and **Seaborn**: For creating visualizations.  

---

## **Steps of Analysis**
1. **Data Loading**: Loaded the Excel dataset into a Pandas DataFrame.
2. **Data Cleaning**:  
   - Dropped irrelevant columns.  
   - Calculated missing ages from the `Dob` column.  
   - Standardized gender values.  
3. **Gender Distribution**: Counted the number of male and female patients.  
4. **Age Summary**: Calculated the mean, median, and range of ages.  
5. **Age Grouping**: Categorized patients into groups like **Child**, **Teen**, **Young Adult**, etc.  
6. **Visualizations**: Created pie charts and bar plots to visualize trends.  

---

## **Key Insights**
- **Gender Distribution**: The dataset has a balanced distribution of males and females.  
- **Age Range**: The average patient age is approximately **30 years**, with a range from **0 to 88 years**.  
- **Age Groups**: Most patients fall into the **Young Adult** and **Adult** categories, representing a majority of the dataset.  

---
