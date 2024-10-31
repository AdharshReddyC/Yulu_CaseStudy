# 🚲 Yulu Electric Cycle Demand Analysis

## 📖 Project Overview

This project analyzes factors affecting the demand for Yulu's shared electric cycles in the Indian market. Yulu, a leading micro-mobility provider, offers sustainable, user-friendly commute solutions aimed at easing urban traffic congestion. Due to a recent dip in revenue, Yulu seeks insights into what influences the demand for their shared electric cycles, aiming to optimize operations and increase user engagement.

## 📊 Dataset

- **Dataset Link**: [yulu_data.txt](https://drive.google.com/file/d/1hmAfdy1DiyIant66I6U_NNdWscG7f3EB/view?usp=sharing) 

### Column Descriptions:
- **datetime**: Date and time of data capture
- **season**: Season (1: Spring, 2: Summer, 3: Fall, 4: Winter)
- **holiday**: Whether the day is a holiday (1: Yes, 0: No)
- **workingday**: Indicator if day is neither weekend nor holiday (1: Yes, 0: No)
- **weather**: Coded weather conditions:
  - 1: Clear or partly cloudy
  - 2: Misty/cloudy
  - 3: Light snow/rain
  - 4: Heavy rain/snow
- **temp**: Temperature (°C)
- **atemp**: Feels-like temperature (°C)
- **humidity**: Humidity level
- **windspeed**: Wind speed
- **casual**: Count of casual users
- **registered**: Count of registered users
- **count**: Total count of rented cycles (casual + registered)

## 🧠 Key Concepts

- **Exploratory Data Analysis (EDA)**: Understanding patterns and relationships within the dataset.
- **Bi-Variate Analysis**: Examining pairwise relationships, such as season and demand.
- **Hypothesis Testing**: Using statistical tests to validate assumptions:
  - **2-Sample T-Test**: Evaluating if working days impact demand.
  - **ANOVA**: Assessing differences in demand across weather and seasons.
  - **Chi-Square Test**: Checking dependency between weather and season.

## 🔍 Analysis and Findings

1. **Exploratory Data Analysis (EDA)**:
   - Reviewed data structure, data types, and handled any missing values.
   - Visualized the distribution of variables and examined relationships with demand.
   - Noted trends such as seasonal variations in demand and effects of weather conditions.

2. **Hypothesis Testing**:
   - **2-Sample T-Test**: Confirmed if demand differs between working and non-working days.
   - **ANOVA**: Tested for significant demand variation across seasons and weather conditions.
   - **Chi-Square Test**: Examined weather dependency on season to understand demand patterns.
   - Set significance level (alpha), tested assumptions of normality, and interpreted p-values to draw insights.

3. **Actionable Insights**:
   - Highlighted variables significantly impacting demand for Yulu cycles.
   - Provided recommendations for optimizing Yulu zone locations and timing based on weather, season, and working-day patterns.

## 📝 Conclusion

This project offers a data-driven understanding of Yulu's electric cycle demand, pinpointing key factors influencing user behavior. Findings can guide operational strategies and marketing efforts to boost ridership and revenue.

## 💡 Future Work

- Explore advanced statistical methods or machine learning for more precise demand forecasting.
- Incorporate real-time weather and traffic data to enhance prediction accuracy.
- Investigate further dependencies between user types (casual vs. registered) and demand influencers.

## 📧 Contact

For further details or collaboration, feel free to reach out:

- **Email**: adharshreddy.c@gmail.com
- **LinkedIn**: [ adharshreddyc](https://www.linkedin.com/in/adharshreddyc/)
