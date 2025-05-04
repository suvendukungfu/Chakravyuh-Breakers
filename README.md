📁** Project Title:**
Unveiling Patterns in Stellar Distances: Benford’s Law Meets Astrophysics

📋 **Project Description**
This project explores hidden patterns in a real-world astronomical dataset using statistical techniques like Benford’s Law and Z-score analysis. It is part of a course project for the Fundamentals of AI, aimed at understanding natural data distributions, detecting anomalies, and drawing meaningful insights from exploratory data analysis (EDA).

We analyze the Distance (ly) column in the Stars Dataset, investigate whether it follows Benford’s Law, and use Z-scores and box plots to detect statistical outliers. This fusion of AI, statistics, and astrophysics helps determine whether the data behaves naturally and supports the validity of observed patterns.

📚 **Dataset Used**
Source: Stars Dataset (uploaded manually)

Columns may include:

Temperature (K)

Luminosity(L/Lo)

Radius(R/Ro)

Absolute magnitude(Mv)

Star type

Star color

Spectral Class

Distance (ly)

The column Distance (ly) was specifically analyzed for Benford’s Law applicability and statistical outliers using Z-scores.

📈** Techniques Applied
✅ 1. Benford’s Law**
Extracted the first digits from the Distance (ly) values.

Calculated the frequency of each digit from 1 to 9.

Compared the observed frequency with Benford’s expected distribution.

Visualized both using bar plots.

✅ 2.** Z-Score Analysis**
Calculated the Z-score for each data point in Distance (ly).

Identified outliers (Z-score > 3 or < -3).

Plotted a box plot to visualize spread and skewness.

✅ 3.** Exploratory Data Analysis (EDA)**
Data cleaning and inspection.

Summary statistics and distribution checks.

Visualizations to support observations.

📊** Visual Outputs**
Benford’s Law Bar Graph: Observed vs Expected frequencies.

Box Plot: Distribution of Distance (ly) to highlight skewness and outliers.

Z-score Histogram: To visualize how far values deviate from the mean.

💡** Observations & Conclusion**
The dataset closely follows Benford’s Law, indicating authenticity.

Outliers detected via Z-score and box plots reflect natural astrophysical variation.

The dataset is ideal for machine learning, anomaly detection, and astrophysical modeling.

🔧** Technologies Used
Python

Pandas

NumPy

Matplotlib

Seaborn

Google Colab**
