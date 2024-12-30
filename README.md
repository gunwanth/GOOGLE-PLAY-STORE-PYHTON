# GOOGLE-PLAY-STORE-PYHTON
# Google Play Store Analysis Project

## Overview
This project focuses on analyzing data from the Google Play Store to gain insights into app performance, user reviews, and other key metrics. The analysis incorporates data cleaning, transformation, exploratory data analysis (EDA), sentiment analysis, and interactive visualizations. Additionally, machine learning models are employed to predict app success metrics, and an interactive dashboard provides an engaging way to explore the insights.

## Objectives
1. **Data Cleaning and Loading**: Import and clean Google Play Store data to ensure accuracy and reliability.
2. **Data Transformation**: Create new features like log-transformed install counts, categorized ratings, and calculated revenue metrics.
3. **Exploratory Data Analysis (EDA)**: Visualize trends in app categories, ratings, and review counts.
4. **Sentiment Analysis**: Analyze user reviews to determine sentiment (positive, negative, neutral) and its impact on app performance.
5. **Interactive Visualization**: Develop dynamic and interactive visualizations for an engaging user experience.
6. **Machine Learning**: Build predictive models to forecast app success metrics such as user ratings, reviews, and install counts.
7. **Dashboard Creation**: Create a user-friendly dashboard to visualize insights interactively.

## Key Features
### 1. Data Loading and Cleaning
- Imported datasets include app data and user reviews.
- Cleaned and processed missing or inconsistent data using Python libraries like Pandas.

### 2. Data Transformation
- Applied transformations such as log-transformed install counts and derived revenue metrics.
- Categorized ratings into groups for better analysis.

### 3. Exploratory Data Analysis (EDA)
- Conducted EDA using Matplotlib and Seaborn.
- Created visualizations such as:
  - Distribution of app ratings.
  - Trends in app categories.
  - Correlation between installs and user reviews.

### 4. Sentiment Analysis
- Utilized the Natural Language Toolkit (NLTK) to analyze user review sentiment.
- Extracted polarity and subjectivity scores to quantify user feedback.

### 5. Interactive Visualization
- Built interactive graphs using Plotly, such as:
  - Revenue trends.
  - Install count visualizations.
  - Sentiment analysis dashboards.

### 6. Machine Learning
- Developed predictive models using:
  - Random Forest for predicting installs and ratings.
  - Linear Regression for revenue prediction.
- Evaluated models with metrics such as R² and Mean Absolute Error.

### 7. Dashboard Creation
- Built an interactive dashboard using Streamlit to:
  - Display key insights from the analysis.
  - Allow users to filter and explore data dynamically.

## File Structure
- **Data**: Contains raw and cleaned datasets (`Cleaned_Play_Store_Data.csv`, `Cleaned_User_Reviews.csv`).
- **Notebooks**: Jupyter notebooks for detailed analysis and visualization.
- **Scripts**: Python scripts for dashboard and machine learning models.
- **HTML Visualizations**: Pre-generated interactive graphs.

## Tools and Technologies
- **Python Libraries**: Pandas, NumPy, Matplotlib, Seaborn, NLTK, Plotly, Scikit-learn.
- **Dashboard Framework**: Streamlit.
- **Visualization**: Plotly and Matplotlib for static and interactive graphs.

## Results
- Identified the top-performing app categories based on installs and ratings.
- Highlighted the impact of user sentiment on app success.
- Built predictive models to forecast app performance metrics.
- Created an interactive dashboard for easy exploration of insights.

## Future Work
- Enhance predictive modeling with advanced algorithms.
- Incorporate real-time data updates into the dashboard.
- Add features like keyword extraction for detailed sentiment analysis.

## How to Run
1. Clone the repository and install the required libraries.
2. Run the Jupyter notebooks to reproduce the analysis.
3. Launch the Streamlit dashboard using:
   ```
   streamlit run dashboard.py
   ```

## Conclusion
This project demonstrates the power of data analysis, visualization, and machine learning in deriving actionable insights from app store data. By combining advanced analytics and interactive tools, it provides a comprehensive overview of app performance and user engagement on the Google Play Store.
