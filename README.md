# California
California Housing Price

California Housing Price Prediction

Name: Monika K
Technique Used: Linear Regression & Multiple Linear Regression
Language: Python

 Project Overview

This project focuses on predicting California housing prices using Linear Regression and Multiple Linear Regression techniques. The dataset contains demographic, geographic, and housing-related features such as income, age, rooms, population, and location details.

The objective is to:

Explore and analyze the dataset

Preprocess data and handle outliers

Build regression models

Compare model performance

Validate regression assumptions

📂 Dataset Description

The dataset includes the following features:

Feature	Description
Income	Median income of households
Age	Housing median age
Rooms	Average number of rooms
Bedrooms	Average number of bedrooms
Population	Population in the area
Occupancy	Average household occupancy
Latitude	Geographic latitude
Longitude	Geographic longitude
Cost	Median house value (target variable)
🛠 Libraries Used

pandas

numpy

matplotlib

seaborn

scikit-learn

scipy

🔹 Step 1: Data Manipulation

Loaded the California housing dataset

Renamed the target column to Cost

Performed basic data inspection (head, info, describe)

Checked for missing values and duplicates

🔹 Step 2: Exploratory Data Analysis (EDA)

Calculated statistical measures (mean, median, min, max, standard deviation)

Visualizations:

Histogram of housing cost

Scatter plot (Income vs Cost)

Correlation heatmap

Key insight:

Income shows strong positive correlation with housing cost

Rooms and Bedrooms show multicollinearity

🔹 Step 3: Preprocessing & Outlier Detection

Applied Standard Scaling

Detected outliers using IQR method

Removed outliers for:

Income

Rooms

Verified results using boxplots

🔹 Step 4: Train-Test Split

Performed normal train-test split (80:20)

Applied stratified sampling based on income groups

Verified that income distribution is preserved across splits

🔹 Step 5: Regression Models
🔸 Linear Regression

Used Income as the independent variable

R² Score: 0.47

🔸 Multiple Linear Regression

Used all features except Cost

R² Score: 0.61

 Result:
Multiple Linear Regression performs better than Simple Linear Regression.

🔹 Step 6: Assumption Checking

Regression assumptions were validated using:

Linearity plot

Independence of residuals

Homoscedasticity plot

Normality check (Histogram & Q–Q plot)

✔ All assumptions were reasonably satisfied.
 Model Comparison
Model	R² Score
Linear Regression	0.47
Multiple Regression	0.61
Conclusion
Income is the most influential factor in predicting housing prices

Multiple Linear Regression provides better predictive accuracy

Proper preprocessing and outlier handling significantly improve model performance
