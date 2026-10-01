# Healthcare Analytics for Doctor Visits

An exploratory data analysis project that looks at which factors are linked to how often people visit a doctor.

## Problem Statement
Most people rarely see a doctor, but a small group visits again and again. This project compares personal, health, financial and insurance factors to find what sets frequent visitors apart.

## Dataset
- 5,190 records, 13 columns, no missing values
- Target: `visits` (number of doctor visits)
- Personal: `gender`, `age`
- Financial: `income`
- Health: `illness`, `reduced`, `health`, `nchronic`, `lchronic`
- Insurance: `private`, `freepoor`, `freerepat`

Note: `age` and `income` are scaled values (age 0.19 means about 19 years).

## Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

## What I Did
1. Loaded and cleaned the data
2. Checked the distribution of doctor visits
3. Compared visits across gender, age, illness, health score, reduced-activity days, chronic conditions, income and insurance type
4. Built a correlation heatmap to find the strongest factors

## Key Findings
- About 80% of people had zero doctor visits
- Women visit more than men on average
- Visits increase with age and with the number of illnesses
- Days of reduced activity show the strongest link to visits
- Private insurance makes almost no difference

These are patterns in the data, not proof of cause.

## How to Run
```bash
git clone https://github.com/<your-username>/healthcare-analytics-doctor-visits.git
cd healthcare-analytics-doctor-visits
pip install pandas numpy matplotlib seaborn jupyter
jupyter lab
```
Open `Health.ipynb` and run all cells.

## Author
Balaji Sahu
