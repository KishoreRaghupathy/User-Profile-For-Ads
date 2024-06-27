# User Profiling for Ads

This project focuses on analyzing user profiles for advertising purposes. It includes data preprocessing, exploratory data analysis (EDA), clustering of users based on their behavior and demographics, and visualization of the results.

## Dataset

The dataset `profiles_details_for_ads.csv` contains user profile information including:

- Age
- Gender
- Education Level
- Income Level
- Device Usage
- Time Spent Online (hrs/weekday)
- Time Spent Online (hrs/weekend)
- Likes and Reactions
- Click-Through Rates (CTR)
- Conversion Rates
- Ad Interaction Time (sec)
- Top Interests

## Project Structure

1. **Data Loading and Initial Inspection**
   - Load the dataset and display basic information.
   - Handle missing values.

2. **Exploratory Data Analysis (EDA)**
   - Visualize distributions of key demographic variables such as age, gender, education level, and income level.
   - Analyze device usage distribution.
   - Examine user online behavior and ad interaction metrics.

3. **Interest Analysis**
   - Analyze and visualize the most common user interests.

4. **User Clustering**
   - Preprocess data using standard scaling and one-hot encoding.
   - Apply K-Means clustering algorithm to identify user segments.
   - Analyze cluster characteristics.

5. **Visualization of Clusters**
   - Use radar charts to visualize user segments based on their online behavior and ad interaction metrics.

## Dependencies

- Python 3.x
- pandas
- seaborn
- matplotlib
- scikit-learn
- plotly

## Usage

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/user-profiling-for-ads.git
   ```

2. **Install the required packages:**

   ```bash
   pip install pandas seaborn matplotlib scikit-learn plotly
   ```

3. **Run the Jupyter Notebook:**

   Open the notebook `User Profiling for ads.ipynb` and run all the cells to perform the analysis.

## Results

- **Demographic Analysis:**
  - Visualizations of age, gender, education level, and income level distributions.

- **User Behavior Analysis:**
  - Insights into device usage and time spent online.
  - Analysis of user interactions with ads, including likes, CTR, conversion rates, and ad interaction time.

- **Interest Analysis:**
  - Identification of the most common interests among users.

- **User Segmentation:**
  - Five distinct user segments identified:
    - Weekend User
    - Engaged Professionals
    - Low-Key Users
    - Active Explorers
    - Budget Browsers

- **Radar Chart Visualization:**
  - Visual representation of user segments based on their behavior and interaction with ads.

## Conclusion

This project provides a comprehensive analysis of user profiles, which can help in designing targeted advertising strategies. The clustering of users allows for a deeper understanding of different user segments, enabling more personalized and effective advertising.

## Acknowledgments

Special thanks to the contributors and the open-source community for their valuable tools and resources.

