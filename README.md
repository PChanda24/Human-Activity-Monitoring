# Human Activity Monitoring using Time Series Analysis

## Dataset
The dataset consists of accelerometer data for 15 subjects, which can be accessed [here](https://sensor.informatik.uni-mannheim.de/#dataset_realworld). Each subject's data includes three axes / directions (x, y, z) for various activities.

## Tasks

### Task 1: Graph-Based Analysis
1. **Methods Applied**:
    - Natural Visibility Graph (NVG)
    - Horizontal Visibility Graph (HVG)
2. **Metrics Computed**:
    - Average Degree
    - Network Diameter
    - Average Path Length
3. **Data Points**:
    - Sample size of 1024 data points (from 1000 to 2024) for each time series
4. **Visualizations**:
    - Scatter plots of average degree vs. network diameter for walking and running, and climbing up and climbing down, for each accelerometer signal and for each method (HVG & NVG).

### Task 2: Entropy and Complexity Analysis
1. **Metrics Computed**:
    - Permutation Entropy
    - Complexity
2. **Parameters Varied**:
    - Embedded Dimension: 3, 4, 5, 6
    - Embedded Delay: 1, 2, 3
    - Signal Length: 1024, 2048, 4096
3. **Visualizations**:
    - Scatter plots of permutation entropy vs. complexity for walking and running, and climbing up and climbing down.

## Skills and Topics Covered
- **Exploratory Data Analysis (EDA)**: Conducting EDA to uncover patterns and insights.
- **Data Preprocessing**: Handling missing values, duplicates, and feature scaling.
- **Graph-Based Analysis**: Implementing NVG and HVG to analyze time series data.
- **Metric Computation**: Calculating average degree, network diameter, and average path length.
- **Entropy and Complexity Analysis**: Computing permutation entropy and complexity with varying parameters.
- **Data Visualization**: Creating scatter plots using Matplotlib and Seaborn.
- **Python Programming**: Utilizing Python libraries like Pandas, NumPy, and Matplotlib.

## Learnings

- **Comprehensive Time Series Analysis:** Successfully transformed accelerometer time series data into complex networks using NVG and HVG, and conducted in-depth analysis of metrics to reveal structural differences in the data.

- **Detailed Entropy and Complexity Study:** Conducted extensive analysis of permutation entropy and complexity across various parameters, and explored the impact of these parameters, providing detailed insights into the data's randomness and complexity.

- **Effective Data Preprocessing and Visualization:** Improved data pre-processing skills, including handling missing values and scaling, and enhanced data visualization skills, including creating scatter plots to clearly illustrate relationships between metrics, highlighting patterns and trends associated with different activities. 

- **Real-World Application and Practical Skills:** Applied theoretical knowledge to real human activity data, demonstrating practical implementation skills and gaining valuable experience in handling and analyzing real-world datasets.

## Results
In this project, we successfully applied NVG and HVG to the time series data, computed the relevant metrics, and visualized the results. The entropy and complexity analysis provided further insights into the structure of the activities.
