# Instagram_Facebook_Performance_Analysis
# Social Media Performance Analysis

## Project Overview
This project provides an analysis of **Instagram** and **Facebook** performance metrics to derive insights on engagement, reach, and effectiveness. The goal is to offer actionable recommendations to optimize content strategies and ad performance based on data-driven decisions.

### Key Areas of Focus:
- **Data Cleaning and Preparation**
- **Key Performance Metrics Calculation**
- **Data Visualization and Trends**
- **A/B Testing for Facebook Ad Creatives**
- **Predictive Model for Post Performance**
- **Final Recommendations**

## Technologies Used
- **Python**
- **pandas** (for data cleaning and analysis)
- **matplotlib** and **seaborn** (for data visualization)
- **scikit-learn** (for building predictive models and performing A/B testing)

## Project Details

### 1. **Data Cleaning & Preprocessing**
Before analysis, the dataset was cleaned by:
- Checking for missing values and removing duplicates.
- Converting date columns into proper datetime format.
- Standardizing engagement and CTR (Click-Through Rate) calculations.

### 2. **Instagram Performance Analysis**
- **Average Engagement Rate**: 570.91% (based on total likes, reach, and followers).
- **Top-Performing Post**: The post on **05-09-2024** had the highest engagement at **196.88%**.
- **Reels vs. Static Posts**: Reels performed **198% better** in terms of engagement compared to static posts, confirming that video content resonates more with the audience.

### 3. **Facebook Performance Analysis**
- **Average CTR**: 0.08%.
- **Best Performing Ad**: The ad creative on **10-04-2024** had the highest CTR of **0.06754%**.
- **Profile Reach vs. Engagement**: Further analysis is recommended to explore whether increasing reach positively impacts engagement.

### 4. **Predictive Model for Post Performance**
A predictive model was developed to estimate post performance based on historical engagement data. The model was trained using the following features:
- Total likes, page reactions, and page post engagements.
- A threshold was set to classify a post as "high-performing."

#### Model Results:
- **Logistic Regression Accuracy**: 93.6%
- **Decision Tree Accuracy**: 100%
  
**Classification Report for Logistic Regression:**
- Precision: 92% - 100%
- Recall: 80% - 100%
- F1-Score: 89% - 96%

**Classification Report for Decision Tree:**
- Precision: 100%
- Recall: 100%
- F1-Score: 100%

### 5. **A/B Testing Insights**
An A/B test was performed to compare the CTR performance of two ad creatives (Ad A vs. Ad B).
- **Average CTR for Ad A**: 0.09%
- **Average CTR for Ad B**: 0.07%

**Statistical Significance (T-Test Result)**: p-value = **0.753** (no significant difference between ad variants).

### 6. **Data Visualizations & Trends**
- Engagement trends over time.
- Comparison between reels and static posts.
- A/B test boxplot for CTR distribution.

## Final Recommendations

### Instagram:
1. **Focus on Reels**: Since they have 198% higher engagement than static posts, prioritize Reels in your content strategy.
2. **Replicate High-Performing Content**: Analyze the patterns from the top-performing post (05-09-2024) and apply similar strategies in future posts.
3. **Experiment with Posting Times**: Test different times of the day to see if posting at specific times boosts engagement.

### Facebook:
1. **Test New Ad Creatives**: Since no significant difference was found in A/B testing, experiment with new ad creatives using different headlines, images, and CTAs.
2. **Optimize Targeting**: Refine your audience targeting to improve CTR.
3. **Try New Ad Formats**: Consider experimenting with video ads and story ads to see if they perform better than static images.

## How to Run the Notebook

1. **Clone this repository** to your local machine:
   ```bash
   git clone https://github.com/your-username/myclientproject.git
