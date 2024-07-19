# 🎯 A/B Testing

![image](https://github.com/user-attachments/assets/9c47b68e-8445-4da9-b88e-8dfdd67a82a4)

This project focuses on conducting an A/B test to examine the effectiveness of an advertisement displayed to a test group compared to a general public service announcement. The goal is to analyze the conversion rates and uncover patterns and trends that can inform future advertising strategies.

<br>

Give this repository a ⭐ if you liked it, since it took me time to understand and implement this. <br>
Made with ❤️ by <b>Om Rajesh Chitmalwar<b>

<br>

## 🗓️ Project Duration
May 2024 - May 2024 

<br>

## 🔍 Key Features
### 📂 Data Columns
- `user_id`: Unique identifier for each user
- `test_group`: Indicator of whether the user is in the test group (ad displayed) or control group (public service announcement)
- `converted`: Indicator of whether the user converted (1) or not (0)
- `total_ads`: Total number of ads shown to the user
- `most_ads_day`: Day of the week with the highest ad displays
- `most_ads_hour`: Hour of the day with the most ad displays

<br>

## 🛠️ Data Analysis Steps
### Exploratory Data Analysis (EDA)
1. Dataset Exploration:
   - Load and inspect the dataset to understand its structure and content.
   - Clean and preprocess the data as necessary.

<br>

2. Visualization:
   - Create visualizations to explore the relationship between the `test_group` and `converted` variables.
   - Use stacked bar charts to compare conversion rates between the test and control groups.
   - Generate pie charts to show the distribution of conversion status within each group.
   - Utilize box plots to visualize the distribution of `total_ads` across converted and non-converted users.
  
<br>   

3. Day and Hour Analysis:
   - Analyze the `most_ads_day` and `most_ads_hour` variables to identify the day of the week and hour of the day with the highest ad displays.
   - Pair these variables with the `converted` status to explore any patterns.

<br>

### Statistical Hypothesis Testing
1. Chi-Squared Test of Independence:
   - Perform a chi-squared test to assess the relationship between categorical variables (`test_group` and `converted`).
   - Determine if there is a significant association between being in the test group and the conversion rate.

<br>

2. Mann-Whitney U Test:
   - Conduct a Mann-Whitney U test to compare the distributions of the `total_ads` variable between converted and non-converted users.
   - Provide statistical validation for any observed differences in ad exposure between the two groups.

<br>

## 💼 Skills Utilized
- Data Cleaning and Manipulation 🧹
- Exploratory Data Analysis (EDA) 📊
- Data Visualization 🎨
- Python Programming 🐍
- Statistical Analysis 📊
- Hypothesis Testing 📉

<br>

## 📥 Getting Started
1. Clone the repository: <pre> git clone https://github.com/omrajeshchitmalwar/A-B-Testing.git
2. Navigate to the project directory: <pre> cd AB-Testing

<br>

## 🌟 Acknowledgements
Special thanks to the data providers and the Python community for their support and documentation.

<br>

## 📬 Contact
For any questions or feedback, please reach out to omrajeshchitmalwar@gmail.com.

