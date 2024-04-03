# Analysis on Bank Marketing

## Problem Statement
The Bank Marketing campaigns of a Portuguese banking institution struggle to understand why some customers take the subscription while others don't. This lack of insight hampers campaign effectiveness, leading to suboptimal subscription rates. For this, we can identify the factors that cause the customers to tend to take the subscription, as well as the reasons behind a customer not taking the subscription using Python programming and data analysis techniques and Python libraries such as NumPy and Pandas as well as visualization methods using the same.

## Description
The dataset consists of 4,521 rows and 17 columns which contain demographic details of a customer as well as details about certain campaigns. As there were double quotes (“”) all over the data in the CSV file, it could not be read directly into a dataframe in the desired manner. For this, we first read the file and removed all the double quotes from the text. We wrote the text back into the file and then we imported it. The customers who have '-1' in 'pdays' column which tells the number of days since a particular customer was contacted before are the people who were not contacted before. Thus, we replaced the '-1' values to 'NaN' in the column.

## Outcome
Various analysis and visualization techniques were used to analyze the factors responsible for a successful campaign and valuable insights were listed for future campaigns.

## Key Skills Used
Pandas, Pre-processing, Variable Analysis, Visualization, NumPy, Python, Data Wrangling, Programming, Analytical Skills, Data Science
