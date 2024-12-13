# Data_Analytics_Assignement_upliance.ai
"This project analyzes user behavior in relation to their cooking sessions and orders. It involves data preprocessing, merging multiple datasets, and visualizing the relationships between session duration, order amounts, dish popularity, and demographic factors."

Introduction
"This project focuses on merging three datasets: user details, cooking sessions, and order details. The goal is to analyze user behavior by examining order frequency, popular dishes, and the influence of demographic factors. We used Python libraries such as Pandas, Matplotlib, and Seaborn to clean the data, perform exploratory data analysis (EDA), and visualize key insights."

Data Description
UserDetails.xlsx: Contains user-related information such as user_id, name, age, location, etc.
CookingSessions.xlsx: Contains session-related information such as session_id, session start, session end, session duration, etc.
OrderDetails.xlsx: Contains order information like order_id, user_id, order date, dish name, order amount, etc.

Preprocessing Steps
Dropped duplicate values.
Filled missing values with appropriate data (e.g., using median for numerical columns).
Converted date columns to datetime format.
Merged datasets using session_id and user_id.

Analysis
Orders per user: Analyzed the number of orders placed by each user.
Popular dishes: Identified the top dishes based on order frequency.
Demographic factors: Explored how age influences order behavior.

Visualizations
Bar plots: These show the most popular dishes and orders by age group.
Scatter plots: Displayed relationships between session duration and order amounts.
Heatmaps: Showed the correlation between session duration and order amounts.

Requirements
Python 3.x
pandas
NumPy
matplotlib
seaborn
