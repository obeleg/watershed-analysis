# Watershed Analysis

## Introduction
A local government operates a small park near its city hall and uses attendance to measure its workload for budgeting purposes. The city manager has concerns about low park attendance and has tasked an analyst to determine if the park's budget request is justified. This analysis involves calculating various descriptive statistics and assessing their implications for park attendance. Additionally, data from the Environmental Protection Agency’s (EPA) Index of Watershed Indicators is utilized to perform further statistical analysis.

## Data Source
The primary data sources for this project include:

- Park attendance records, collected over 25 randomly selected days from the past year.
- The Watershed dataset, derived from variables and data incorporated within the EPA’s Index of Watershed Indicators.

## Data Description

### Park Attendance Data
The park attendance data consists of daily visitor counts for 25 randomly selected days, with figures as follows: 5, 3, 10, 1, 2, 3, 4, 3, 5, 100, 4, 3, 2, 4, 25, 150, 3, 3, 5, 4, 8, 7, 10, 15, and 30.

### Watershed Data
The Watershed dataset includes various environmental indicators such as the percentage of samples exceeding conventional pollution standards (Conpolut) and the number of fish and wildlife advisories (Advisory). The dataset is used to compute descriptive statistics and analyze regional pollution data.

## Summary of Analysis
The analysis involved calculating the mean, median, and mode of park attendance to understand visitor patterns. For the Watershed dataset, descriptive statistics were computed for Conpolut and Advisory variables, both overall and regionally. Additionally, a new variable combining toxic and conventional pollution levels was created and analyzed.

## Key Questions Answered

1. **What are the central tendencies of park attendance data?**
   - The mean, median, and mode were calculated to provide insights into typical attendance and the impact of extreme values.
   
2. **How do pollution levels vary across different regions?**
   - Descriptive statistics for Conpolut and Advisory variables were analyzed regionally to understand pollution patterns.

3. **What is the overall quality of watersheds based on vulnerability and quality indicators?**
   - A bar chart was created to visualize watershed quality categorized by vulnerability levels.

## Findings

- **Park Attendance Analysis:**
  - The mean attendance was 16.36 visitors per day, indicating a high average influenced by outliers.
  - The median attendance of 4 visitors per day provided a more accurate representation of typical daily attendance.
  - The mode of 3 visitors per day highlighted the most frequently occurring attendance value.

- **Watershed Data Analysis:**
  - The mean percentage of samples exceeding conventional pollution standards (Conpolut) was approximately 20.79%, with a median of 19.32%.
  - The mean number of advisories (Advisory) was about 4.80, with a median of 3.
  - Regional analysis showed varying pollution levels, with Region 3 having the highest combined pollution levels (Toxicon + Conpolut).

These findings suggest that while mean attendance figures are skewed by extreme values, the median and mode offer more reliable insights into typical park usage. The watershed analysis highlights significant regional differences in pollution levels, informing targeted environmental management strategies.

