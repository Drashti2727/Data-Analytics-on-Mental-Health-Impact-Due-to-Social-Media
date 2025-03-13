# Social Media & Mental Health Analysis 📊

## Overview  
This project analyzes the impact of **social media usage** on **mental health indicators**, focusing on user behavior, engagement patterns, and correlations with mental well-being. The study aims to uncover insights into social media's role in emotional and psychological states.

## Dataset Details  
The dataset (**social_media_usage_updated.csv**) contains **23 columns**:

| Column Name | Description |
|------------|-------------|
| **User_ID** | Unique identifier for each user |
| **Age_Group** | Age category of the user |
| **Platform_Used** | Social media platform used |
| **Daily_Screen_Time** | Time spent on social media per day (in minute) |
| **Active_Hours** | Active hours of the user per day |
| **Number_of_Posts_Per_Day** | Number of posts made per day |
| **Number_of_Likes_Received** | Total likes received on posts |
| **Number_of_Comments_Received** | Total comments received on posts |
| **Number_of_Shares** | Total shares of posts |
| **Number_of_Followers** | Total followers of the user |
| **Number_of_Accounts_Followed** | Total accounts followed by the user |
| **Time_Spent_on_Videos** | Time spent watching videos (in minutes) |
| **Time_Spent_on_Images** | Time spent viewing images (in minutes) |
| **Time_Spent_on_Text_Posts** | Time spent reading text posts (in minutes) |
| **Number_of_Ads_Clicked** | Number of advertisements clicked |
| **Content_Exposure_Type** | Type of content the user is most exposed to |
| **Exposure_to_Negative_Content** | Whether the user is exposed to negative content (Yes/No) |
| **Engagement_Score** | User engagement level based on interactions |
| **Use_of_Anonymous_Accounts** | Whether the user uses anonymous accounts (Yes/No) |
| **Fear_of_Missing_Out_Score** | Score representing user's Fear of Missing Out (FOMO) level |
| **Self_Reported_Satisfaction_Level** | User’s self-reported satisfaction level |
| **Suicide_Ratio_Age_Group** | Suicide statistics for the user's age group |
| **Depression_Ratio_Age_Group** | Depression statistics for the user's age group |

> **🔹 Note:** This dataset is collected for analytical purposes and does not represent real-world clinical data.

## Key Insights  

### 🛠 Handling Data Issues  
👉 Identified and managed missing values in key behavioral metrics.  
👉 Detected and adjusted outliers in **Daily_Screen_Time** and **Engagement_Score** to ensure data accuracy.  

### 📊 Mental Health & Social Media Trends  
📌 Correlation between **Daily Screen Time** and **Depression Ratio**.  
📌 Influence of **Exposure to Negative Content** on **Self-Reported Satisfaction Levels**.  
📌 Platform-wise **Engagement Score** comparison.  

### 🔍 Behavioral Patterns & FOMO  
- Relationship between **FOMO Score** and excessive social media engagement.  
- Analyzed the role of **likes, shares, and comments** in perceived satisfaction levels.  

## 🛠️ Technologies Used  
- **🐍 Python** (Pandas, NumPy, Matplotlib, Seaborn)  
- **📓 Jupyter Notebook** for data analysis  
