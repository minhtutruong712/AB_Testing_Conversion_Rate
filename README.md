# AB_Testing_Conversion_Rate
This project aims to provide a fundamental understanding of A/B testing application in data analysis. 
Using Python as a programming language in data exploratory and transformation process, it gave a tailored approach on data-driven methodology to
understand the results of an A/B test run by an e-commerce website. My goal is to work through these notebooks to help the company understand if they should:

- Implement the new webpage,
- Keep the old webpage, or
- Perhaps run the experiment longer to make their decision.

The main processing notebook contains 3 parts: 
- Part 1: Data Cleaning, handle inaccurate data when ingested from web.
- Part 2: Ultilize A/B testing by divide the dataset into 2 groups: control group (old page) and treatment group (new page). Each group will be used to calculate the
  conversion rate (converted = 1 indicates users converted, else 0). Use these means to form hypothesis of testing whether Ho: p_old_page >= p_new_page can be rejected or not.
- Part 3: Regression Approach to test the correlation between conversion rate and the region where the user lives.
  
