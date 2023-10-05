# Indian-Startup-Funding-Analysis
Exploratory Data Analysis

🚀 Insights into Indian Startup Funding! 📈🇮🇳



Have you ever wondered how the funding ecosystem changes over time in India? 🔄 Do cities play a major role in shaping startup funding? 🏙️ Which industries are favored by investors for funding? 🤝 Who are the important investors in the Indian ecosystem? 💼 And how much funds do startups generally receive in India? 💰



Let's dive into an analysis of the Indian startup funding dataset to uncover these intriguing questions! 📊🔍



📚 Dataset Overview:

The dataset contains information on funding received by Indian startups from January 2015 to August 2017. It includes startup names, industry verticals, sub-verticals, city locations, investors' names, investment types, funding amounts, and more. Let's explore this dataset together!



✅ Data Cleaning and Preprocessing:

We begin by cleaning and preparing the dataset to ensure accurate analysis. Steps include:

1️⃣ Removing leading/trailing spaces and converting text to lowercase.

2️⃣ Handling missing values: We replace 'undisclosed' and 'unknown' funding amounts with NaN, convert the 'Amount in USD' column to numeric format, and fill missing values with the median amount.

3️⃣ Dropping irrelevant columns: We remove the 'Remarks' column, which has many missing values, and the 'Sr No' column.

4️⃣ Filtering out rows with missing values.

5️⃣ Formatting the date column: We replace incorrect characters, convert it to datetime format, and filter out invalid dates (NaT values).

6️⃣ Adding a 'Year' column by extracting the year from the formatted date.



📅 Temporal Analysis:

To understand the funding ecosystem's evolution, we examine the distribution of funding over time. We analyze the unique dates and their corresponding funding counts to identify trends and patterns.



🌆 City-wise Analysis:

Next, we explore the significance of cities in the funding landscape. We standardize city names and locations, ensuring consistent representation. We then examine the unique city values to gain insights into the role of different cities in funding startups.



💼 Investor Analysis:

We investigate the key investors in the Indian ecosystem. By analyzing the 'Investors Name' column, we identify prominent investors who contribute to startup funding and play a vital role in shaping the ecosystem.



💸 Funding Amount Analysis:

Finally, we explore the funding amounts received by startups in India. We analyze the distribution of funding across different investment types, industries, and cities. This analysis provides valuable insights into the funding patterns and preferences of investors.



📊 Visualizations:

To enhance our understanding, we utilize powerful visualizations throughout the analysis. We leverage popular libraries such as seaborn, numpy, and matplotlib to create informative plots that depict funding trends, city roles, industry preferences, and more.



Stay tuned as we unravel the fascinating world of Indian startup funding! 🎉💼📈



#IndianStartups #FundingEcosystem 