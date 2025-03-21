Online Advertising Effectiveness Study - A/B Testing Analysis

1. Overview

This project analyzes the effectiveness of online advertisements in increasing customer purchases on a company's website. The analysis is based on a dataset obtained from an A/B testing experiment, where 20,000 customers were subjected to either an advertisement ('ad') or a public service announcement ('psa'). The goal is to determine if exposure to advertisements leads to more purchases compared to PSAs and whether ad exposure frequency or the time of day has an impact on purchase behavior. 


2. Dataset

2.1 Source

The dataset used for this analysis is available here: 

https://www.kaggle.com/datasets/farhadzeynalli/online-advertising-effectiveness-study-ab-testing?resource=download


2.2 Dataset Structure

The dataset contains the following columns:
    • customerID: Unique identifier for each customer.
    • test_group: 'ad' (advertisement) or 'psa' (public service announcement).
    • made_purchase: Boolean indicating whether the customer made a purchase after viewing the advertisement.
    • days_with_most_ads: The day of the month the customer saw the most ads.
    • peak_ad_hours: The hour of the day when the customer saw the most ads.
    • ad_count: Total number of ads shown to the customer.


3. Analysis

3.1 Tools used in the Analysis

- Python (pandas and numpy)
- Jupyter Notebook


3.2 Structure of the Analysis

- Data Preprocessing
- Grouping and Aggregating Data
- Ad Exposure Analysis
- Comparing Ad and PSA Groups
- Analyzing Peak Ad Hours
- Time of Day Analysis
- Combining Time and Ad Exposure


3.3 Key Findings
   
- Exposure to ads led to a higher purchase rate compared to exposure to PSAs. 
- The time of day and frequency of ad exposure played significant roles in purchase behavior.

5. Usage/Installation

- Clone the repository.
- Install required Python libraries (pandas, numpy).
- Run the Jupyter Notebook for analysis.



6. Contact

For questions or contributions, please contact me through github. Thank you and enjoy ;)
