# MSCS_634_ProjectDeliverable_1
Dataset Summary:
This dataset provides a synthetic yet highly realistic snapshot of today's evolving job market, with a special emphasis on artificial intelligence (AI) and automation across various industries. 

Source: "AI-Powered Job Market Insights" from https://www.kaggle.com/datasets/uom190346a/ai-powered-job-market-insights

Size: 500 records with 10 attributes

Attributes:
  - Job Title
  - industry
  - Company size
  - Location
  - AI adoption level
  - Automation Risk
  - Required Skills
  - Salary (USD)
  - Remote Friendliness
  - Job Growth Projection


Purpose: I chose this dataset because Ai's impact on the future of work is a widely discussed topic, and I wanted to explore which jobs are most at risk of automation, how AI adoption caries across industries, and what skills are becoming more critical as AI continues to evolve.

Steps taken in Data Cleaning and Exploration:

1. Missing data check: Verified no missing values
2. Removed duplicates using the drop_duplicates() method to ensure data quality
3. Verifed column values with .unique() method to make sure there are no inconsistent labels
4. Rounded the Salary values to the nearest whole dollar for easier interpretation.
5. Identified potential salary outliers using the IQR method, kept them after reasoned judgemnt.
6. Creates count plots, pie charts, and boxplots to understand distribution and relationships.
