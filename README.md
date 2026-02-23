📊 Customer Sign-Up Behaviour & Data Quality Audit

📌 Project Overview

This project analyzes customer sign-up data for a SaaS company (Rapid Scale) to evaluate user acquisition trends and assess data quality issues. The goal is to support Marketing and Onboarding teams with actionable insights.

🛠 Tools Used

* Python

* Pandas

* NumPy

* Matplotlib / Seaborn

* Jupyter Notebook

🔍 Key Data Cleaning Steps

* Converted signup_date to datetime

* Removed duplicate customer_id records (1 duplicate removed → 299 rows remaining)

* Standardized inconsistent categorical values (e.g., PRO → Pro)

* Handled missing values in age, region, and gender

* Converted non-numeric age values to NaN and imputed using median

(See notebook for implementation)

📈 Key Insights

* Google was the top acquisition source last month.

* The Pro plan was the most selected subscription tier.

* Users aged 25–50 preferred Pro & Premium plans.

* Younger users (<35) were more likely to opt into marketing.

* "Unknown" region values indicated data collection gaps.

💡 Business Recommendations

* Improve mandatory region data capture.

* Focus upsell campaigns on the 25–50 age segment.

* Develop tailored engagement strategies for 50+ users.

⚠️ Data Quality Risks Identified

* Missing or inconsistent values in age, region, and gender.

* Improperly formatted categorical entries.

* Risk of inaccurate marketing segmentation due to incomplete demographics.

📂 Files Included

* Jupyter Notebook

* Cleaned dataset

* Final PDF report
<img width="712" height="352" alt="image" src="https://github.com/user-attachments/assets/9dfa27d3-0541-48ce-9124-dbd27479bc2d" />

<img width="568" height="352" alt="image" src="https://github.com/user-attachments/assets/877f5824-bb24-417e-8348-3f5f83f3c011" />

<img width="568" height="352" alt="image" src="https://github.com/user-attachments/assets/346a135c-72fa-4435-8f20-7e8864bd24f8" />

