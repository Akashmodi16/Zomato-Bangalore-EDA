Zomato Bangalore Restaurant Analysis (Exploratory Data Analysis)
📌 Project Overview

This project presents a comprehensive Exploratory Data Analysis (EDA) of the Zomato Bangalore restaurant dataset (51,717 records) to identify key factors influencing customer ratings and satisfaction.

The objective was not just to visualize the data, but to extract business-relevant insights using structured cleaning, feature engineering, correlation analysis, and location-based performance evaluation.

🎯 Problem Statement

What factors influence restaurant ratings in Bangalore?

Specifically:

Does pricing affect customer satisfaction?

Do service features (table booking, online ordering) impact ratings?

Which geographic locations perform best?

Is premium positioning associated with higher ratings?

🧹 Data Cleaning & Preparation

The dataset contained several real-world inconsistencies:

Converted rating column from string format ("4.1/5", "NEW", "-") to numeric values

Removed non-informative entries

Cleaned pricing column by removing comma separators

Encoded categorical features (online_order, book_table)

Handled missing values strategically

Segmented restaurants into Budget, Mid-Range, and Premium categories

Filtered locations based on minimum restaurant count to ensure statistical reliability

Generated a processed dataset (zomato_cleaned.csv)

This reflects real-world data preprocessing workflows.

📊 Key Analytical Findings
1️⃣ Overall Market Behavior

Average restaurant rating: 3.7

Most ratings cluster between 3.4 and 4.0

This indicates a moderately competitive and relatively stable dining market.

2️⃣ Pricing vs Rating

Correlation between cost and rating: 0.385 (moderate positive)

Budget (≤ ₹500): Avg rating = 3.58

Mid-Range (₹500–1500): Avg rating = 3.84

Premium (₹1500+): Avg rating = 4.16

Insight: Higher-priced restaurants tend to deliver better customer experience, but pricing alone does not guarantee high ratings.

3️⃣ Impact of Service Experience

Restaurants offering table booking show significantly higher ratings:

Without table booking: 3.62

With table booking: 4.14

These establishments also have ~3x higher average cost.

Insight: Structured dining experience and service quality strongly influence customer satisfaction.

4️⃣ Convenience vs Experience

Online ordering impact:

Without online ordering: 3.66

With online ordering: 3.72

Minimal difference observed.

Insight: Convenience features contribute marginally compared to experiential factors like ambience and service quality.

5️⃣ Geographic Performance

Top-performing locations (filtered by restaurant volume):

Lavelle Road (4.14)

Koramangala 3rd Block (4.02)

St. Marks Road (4.02)

These are premium commercial and nightlife hubs.

Insight: Location prestige and target demographic play a significant role in perceived restaurant quality.

🧠 Business Conclusion

Customer satisfaction in Bangalore’s restaurant market is primarily driven by:

Premium positioning

Structured service experience

Location advantage

Ambience and service quality

Convenience factors such as online ordering show comparatively limited influence.

This analysis demonstrates how structured EDA can translate raw operational data into actionable business insights.

🛠 Tools & Technologies

Python

Pandas

NumPy

Matplotlib

Jupyter Notebook

🚀 Career Objective

I am actively seeking opportunities in:

Data Analyst

Business Analyst

Business Intelligence roles

This project reflects my ability to:

Clean and transform messy real-world datasets

Perform statistical analysis

Derive business-focused insights

Communicate findings clearly and professionally
