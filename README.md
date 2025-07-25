# 🚲 Yulu E-Bike Rental Data Analysis

This project explores rental data from Yulu, a shared micro-mobility service, to identify patterns in user behavior based on time, weather, season, and user type. The objective is to extract insights using exploratory data analysis and hypothesis testing.

## 📁 Dataset

- Records: 10,886
- Features include:
  - Date & Time
  - Weather indicators (temperature, humidity, windspeed)
  - User type (casual, registered)
  - Count of total rentals
  - Holiday, working day, and season info

## 📌 Objectives

- Analyze hourly and seasonal trends in bike rentals
- Evaluate how weather and calendar variables affect demand
- Identify usage patterns between registered and casual users
- Apply statistical tests to validate observed trends

## 🛠 Tools & Libraries

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scipy, Statsmodels

## 📊 Key Analysis

- 📅 **Time Segmentation**: Created morning, afternoon, evening, and night bins using datetime.
- 🌤 **Weather & Season Impact**: Compared rental volumes across weather types and seasons using grouped bar charts.
- 👤 **User Type Behavior**: Analyzed patterns for registered vs. casual users across various conditions.
- 📈 **Correlation Analysis**: Heatmap and scatterplots used to explore relationships between numerical variables.
- 📉 **Hypothesis Testing**:
  - T-tests for holidays vs non-holidays and working days
  - Kruskal-Wallis tests for seasons and weather types
  - Chi-Square tests for categorical relationships

## 🔍 Key Insights

- Rentals peak during morning (7–9 AM) and evening (5–7 PM), aligning with commute hours.
- Clear weather and summer/fall seasons have the highest rental activity.
- Registered users consistently rent more than casual users, especially on working days.
- Significant differences in rental behavior observed across seasons and weather categories.

## 📦 Project Structure

