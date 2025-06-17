**Big Data Analytics: Crop Prediction**
This project applies big data and data science techniques to analyze agricultural production and enable accurate crop prediction. Using a structured dataset, various exploratory and predictive methods are used to identify patterns and recommend suitable crops based on soil and climate conditions.

**Dataset Summary**
The dataset consists of 2,200 records and includes the following features:

N: Nitrogen content in soil

P: Phosphorus content in soil

K: Potassium content in soil

Temperature: Measured in degrees Celsius

Humidity: Relative humidity in percentage

pH: Soil pH level

Rainfall: Measured in millimeters

Label: Crop name (target variable)

The dataset is clean and contains no missing values.

**Exploratory Data Analysis
General statistics for the dataset:**

Nitrogen (N): 50.55

Phosphorus (P): 53.36

Potassium (K): 48.15

Temperature: 25.62°C

Humidity: 71.48%

pH: 6.47

Rainfall: 103.46 mm

This analysis provides an overview of the environmental and soil conditions across all crops.

**Crop-Wise Feature Summary**
The project includes an interactive module where users can select a crop and view its minimum, average, and maximum values for each feature. This helps in understanding the optimal growing conditions for specific crops.

**Feature Comparison**
A feature comparison tool allows users to select any individual feature and view its average value across all crop types. This enables analysis of how certain environmental or soil factors vary by crop.

**Feature Distributions**
Each feature is visualized using distribution plots to highlight its overall range, central tendency, and skewness. These plots help assess how uniformly or unevenly values are distributed across the dataset.

**Clustering Analysis**
Using the Elbow Method, four optimal clusters are identified, and K-Means clustering is applied to group crops with similar growing conditions. This clustering provides insight into groups of crops that thrive under comparable environmental factors.

**Visualizations**
The following plots and visual summaries are included in the project:

Bar plot of feature means

Average value comparison across crop types

Distribution plots of all features

Confusion matrix from model evaluation

All visual assets are included in the repository under the Visualizations folder.

**Model Training and Evaluation**
The dataset is divided into training and testing sets using an 80:20 ratio. A Logistic Regression model is trained on the data and evaluated using the following metrics:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

Detailed classification report for each crop class

This step measures how well the model predicts crop types based on soil and weather features.

**Crop Prediction**
The trained model can predict the most suitable crop for any given input of environmental and soil conditions. This tool serves as a valuable decision aid for farmers or agricultural planners.

**Conclusion**
This project demonstrates how data analytics and machine learning can be applied to agriculture for improved decision-making. By analyzing relationships between climate, soil composition, and crop types, the project offers insights into optimal farming practices. The resulting prediction model can be used to guide crop selection based on measurable conditions, supporting sustainable and informed agricultural development.

Let me know if you'd like this turned into a README.md file or need a version with sample code or interactive features added.








