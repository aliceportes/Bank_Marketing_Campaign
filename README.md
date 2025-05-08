# Bank Marketing Campaign Analysis
---

## Overview
This project dives into data from a bank’s past marketing campaign to understand what factors influence a client's decision to subscribe to a term deposit. The goal is to uncover patterns that can help the bank improve its strategy and run more effective future campaigns.

Using a mix of exploratory data analysis (EDA) and machine learning, I explored how different features and client profile impacted the campaign’s success. The final outcome is a set of insights and a predictive model that can support smarter, more targeted marketing efforts going forward.

---

## Project Structure

- `bank.csv`: The dataset used in this project. [Bank Marketing Dataset on Kaggle](https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset)
- `bank_marketing_analysis.ipynb`: Jupyter Notebook containing the full analysis, visualizations, and model training.
- `visuals/`: Saved figures from the notebook for easier reference or presentations.

---

## Key Steps

1. **Data Cleaning**  
   - Converted categorical columns  
   - Flagged outliers and engineered new features

2. **Exploratory Data Analysis (EDA)**  
   - Analyzed distributions and deposit success rates by job, age, education, and more  
   - Uncovered behavioral patterns tied to contact method, timing, and frequency

3. **Modeling**  
   - Compared Logistic Regression and Random Forest

---

## Tools Used

- Python
    * Pandas
    * Seaborn
    * Matplotlib
    * Scikit-learn
      
---

## Key Insights
After analyzing client data and campaign results, and training predictive models several patterns stood out:

- **Account balance** was the strongest indicator of whether a client would subscribe. Higher balances correlated with a higher success rate.
- **Age and job type** showed distinct behaviors—retired clients and students had higher subscription rates, while blue-collar clients were less likely to say yes.
- **Clients without loans** (housing or personal) were more inclined to subscribe, suggesting that financial flexibility influences decision-making.
- **Contact method and duration** mattered—cellular was the most effective, and calls lasting 2–3 minutes had the highest success rates
- **Timing of contact** also played a key role: success rates were higher in March, October, and December, while May (despite high volume) had the lowest.

These insights can help shape future marketing efforts to be more targeted and cost-efficient.

---

## Conclusion

By combining exploratory data analysis with machine learning, this project uncovered meaningful patterns in how clients respond to marketing campaigns. 

The insights from this project help marketing teams decide who to target, when to reach out, and how frequently. It reinforces the importance of data-driven strategies in running more effective and engaging campaigns.

Thank you for checkig out my project!

