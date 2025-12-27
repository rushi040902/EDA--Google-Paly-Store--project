Google Play Store Apps - Exploratory Data Analysis (EDA)
📌 Project Overview
Google Play Store (formerly Android Market) is the official app store for Google-certified Android devices. With the rapid growth of the Android ecosystem, this project performs an Exploratory Data Analysis on a dataset of 10,000+ web-scraped apps to obtain valuable market insights. The goal is to clean, process, and analyze the data to understand user preferences, app ratings, and category trends.

📂 Files in this Repository
Pandas--Google Play Store Part-1.ipynb → Initial data cleaning and exploration.

Pandas--Google Play Store Part-2.ipynb → Advanced analysis and top-performing app insights.

googleplaystore.csv → The raw dataset from Kaggle.

Google play store EDA Project Complete Solutions.txt → A summary of analysis questions and logic.

EDA Description.docx → Project background and documentation.

🛠 Technologies Used
Python

Pandas (Data manipulation and cleaning)

NumPy (Numerical operations)

Matplotlib (Data visualization)

📊 Key Analysis
Data Cleaning: Handling null values, removing special characters (like + and ,) from the Installs column, and converting data types.

Rating Analysis: Calculating the average app rating and finding categories with the highest user satisfaction.

Popularity Metrics: Identifying the top 5 apps with the highest reviews and maximum installs (e.g., Facebook, Subway Surfers).

Market Distribution: Analyzing the ratio of Free vs. Paid apps and their average ratings.

Category Insights: Finding the total number of unique categories and identifying niche genres with perfect 5-star ratings.

▶ How to Run
Clone this repository to your local machine.

Ensure you have the googleplaystore.csv file in the same directory as the notebooks.

Install the required libraries if you haven't already: pip install pandas numpy matplotlib.

Open the .ipynb files using Jupyter Notebook, VS Code, or Google Colab.

Run the cells sequentially to see the data processing and insights.

Pro-Tip for your GitHub:
If you want to make your repository stand out, you can take a screenshot of one of the charts you made (like the Category Rating bar chart) and add it to the bottom of your README using: ![Analysis Visualization](./your_image_name.png)
