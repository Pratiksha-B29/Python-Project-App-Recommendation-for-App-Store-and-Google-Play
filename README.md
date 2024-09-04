# Python-Project-App-Recommendation-for-App-Store-and-Google-Play

## Project Overview
This project aims to identify profitable mobile app profiles for the App Store and Google Play markets. As data analysts at a company that specializes in building Android and iOS mobile apps, our goal is to enable our team of developers to make data-driven decisions about the types of apps they should focus on developing.

We focus exclusively on apps that are free to download and install, as our main source of revenue comes from in-app advertisements. Therefore, the number of users is a critical factor in determining the profitability of an app. This project analyzes data from both the App Store and Google Play to understand which types of apps attract the most users and, consequently, generate the most revenue.

## Project Steps
**1. Opening and Exploring the Data:**
  
  We started by loading and exploring datasets from the App Store and Google Play to understand their structure and the information they contain.


**2. Deleting Incorrect Data:**
  
  We identified and removed incorrect or irrelevant data entries that could skew our analysis.


**3. Removing Duplicate Entries:**
 
  We checked for duplicate entries and removed them to ensure our analysis was based on unique app profiles.


**4 .Filtering Non-English Apps:**
  
  Since our target audience primarily uses English, we filtered out non-English apps to focus on relevant data.


**5. Isolating Free Apps:**
  
  As we only build free apps, we filtered the datasets to include only those apps that are free to download and install.


**6. Determining the Most Common Apps by Genre:**
 
  We analyzed the data to identify the most common genres of apps in both markets, helping us understand current trends.


**7. Identifying the Most Popular Apps by Genre on the App Store:**
 
  We evaluated the popularity of different genres on the App Store based on user ratings and other relevant metrics.


**8. Identifying the Most Popular Apps by Genre on Google Play:**
  
  Similarly, we analyzed the popularity of various genres on Google Play to find out which types of apps are trending in that market.

## Findings & Conclusion

After thorough analysis, we recommend creating an app based on a popular book, ideally a recent publication. Both the App Store and Google Play markets have a significant number of library and book-related apps, so to stand out, our app should offer additional features such as:

- **Daily Quotes :** Inspirational or memorable quotes from the book delivered daily.

- **Audio Version :** An integrated audiobook feature for users who prefer listening.

- **Interactive Quizzes :** Fun quizzes related to the book’s content.

- **Community Forum :** A space where readers can discuss the book, share thoughts, and engage with others.

By offering these features, we believe the app will attract a larger user base, making it profitable through in-app ads on both platforms.

## How to Use This Project

- **Data Source :** The datasets used for this analysis can be found here.

- **Notebook :** The Jupyter notebook containing all the steps, from data cleaning to analysis, is available in this repository.

- **Results :** The key insights and recommendations are summarized in the notebook and in this README.

## Requirements
- Python 3.8 or higher

- Jupyter Notebook

- Pandas

- NumPy

