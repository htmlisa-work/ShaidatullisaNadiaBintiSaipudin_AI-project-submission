# Employee Sentiment Analysis

## Project Introduction

This project analyzes an unlabeled dataset of employee messages to assess sentiment and engagement.  
Using natural language processing (NLP) techniques, exploratory data analysis (EDA), employee scoring and ranking, flight risk detection, and predictive modeling,  
I transformed raw communication data into actionable insights.

The goal is to help organizations understand employee sentiment trends, identify potential problem areas, recognize top performers,  
and proactively address retention risks through data-driven insights.

--- 

## Setup Instructions

1. Clone this repository or extract the provided ZIP package containing the project files.
2. Navigate to the project directory.
3. Install the required dependencies 

Make sure you have Python 3.x installed.

---

## Usage Instructions

- To run the main analysis:
  1. Open the notebook file: **FinalLLM_EmployeeSentimentAnalysis.ipynb** using Jupyter Notebook, JupyterLab, or any compatible IDE.
  2. Run all code cells sequentially, from top to bottom, to reproduce the full workflow and generate all outputs

- Ensure that the dataset `test.csv` is located in the `data/` directory.  
  If it is missing, download it from the provided dataset source and place it in that folder.

---

## Output Files

Running the analysis will generate:
- Processed `.csv` result files (e.g., sentiment labels, rankings, flight risk list)
- Visualizations saved in the `project_output/visualizations/` folder
- A final written report (if you run the export) saved in the `project_output/` directory

Make sure you check these folders after running the code!

---

## Top 3 Positive Employees 
- eric.bass@enron.com
- john.arnold@enron.com
- sally.beck@enron.com

## Top 3 Negative Employees 
- bobette.riner@ipgdirect.com
- don.baughman@enron.com
- honda.denton@enron.com

---

## Employees Flagged as Flight Risks
Full list in `flight_risk_employees.csv`
- lydia.delgado@enron.com
- john.arnold@enron.com
- patti.thompson@enron.com

*Flight risk is defined as sending 4 or more negative messages within any rolling 30-day window.*

---

## Key Insights

- **Sentiment Breakdown:** Negative messages dominate overall, with only a small fraction of neutral messages.
- **Monthly Trends:** Negative sentiment consistently outweighs positive sentiment over time.
- **Employee Behavior:** Most employees send similar message volumes, but some show consistently high negativity.
- **Flight Risk:** Several employees stand out as repeat negative communicators, triggering flight risk flags.
- **Model Performance:** The linear regression model explains ~52% of sentiment score variation — moderate predictive strength but with room for improvement.

---

## Summary and Recommendations

- **Highlight Top Contributors:** Recognize and reward consistently positive employees.
- **Address Negative Patterns:** Investigate causes behind consistently negative contributors and offer targeted support.
- **Monitor Flight Risks:** Prioritize at-risk employees for HR intervention before dissatisfaction deepens.
- **Improve Predictive Modeling:** Explore advanced machine learning models (Random Forest, Gradient Boosting) and add context features (department, team) to boost forecasting power.
- **Set Up Continuous Monitoring:** Build a real-time dashboard to track sentiment shifts week-to-week for faster reaction times.

---

## Author

👤 **Shaidatullisa Nadia Binti Saipudin**

31st May 2025

---

