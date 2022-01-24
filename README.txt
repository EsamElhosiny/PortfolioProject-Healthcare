The Phase II clinical trial dataset for new oral insulin called Auralin.

DISCLAIMER: This Data Isn't "Real"

The Auralin and Novodra are not real insulin products. This clinical trial data was fabricated. When assessing this data, the issues that you'll detect (and later clean) are meant to simulate real-world data quality and tidiness issues.

------

That said:

- This clinical trial data for alternative insulin was inspired and closely mimics this real clinical trial for an inhaled insulin called Afrezza.
- The data quality issues in this dataset mimic real, common data quality issues in healthcare data. These issues impact quality of care, patient registration, and revenue.
- The patients in this dataset were created using this fake name generator and do not include real names, addresses, phone numbers, emails, etc.

Additional useful information:

- Insulin resistance varies person to person, which is why both starting median daily dose and ending median daily dose are required, i.e., to calculate change in dose.
- It is important to test drugs and medical products in the people they are meant to help. People of different age, race, sex, and ethnic group must be included in clinical trials. This diversity is reflected in the patients table.
- Ensuring column names are descriptive enough is an important step in acquainting yourself with the data. 'Descriptive enough' is subjective. Ideally you want short column names (so they are easier to type and read in code form) but also fully descriptive. Length vs. descriptiveness is a tradeoff and common debate (a similar debate exists for variable names). The auralin and novodra column names are probably not descriptive enough, but you'll address that later so don't worry about that for now.

