# Customer Behavior Data Analysis

I built this project to dig into how customers actually shop what they buy, how much they spend, and which groups behave differently using a dataset of around 3,900 purchases. The goal was to go from raw, messy data all the way to a clean, interactive dashboard that someone could actually use to make decisions.

## What this project covers

- Cleaning and prepping the raw shopping data (Python)
- Writing SQL queries to pull out revenue, segments, and trends
- Building an interactive Power BI dashboard to visualize the findings
- Summarizing everything into a business problem document and presentation

## The dataset

18 columns, ~3,900 customer purchases. It includes things like purchase amount, category, season, age group, gender, subscription status, and shipping type basically enough to slice customer behavior a bunch of different ways.

## The dashboard

Here's what the final Power BI dashboard looks like:

![Customer Behavior Dashboard](https://github.com/Tejaskadu2203/Customer_Behavior_Data_Analysis/blob/main/customer_behavior_dashboard.pbix)

A few things it surfaces at a glance:
- **3.9K customers**, averaging **$59.76** per purchase, with an average review rating of **3.75**
- **73% of customers aren't on a subscription** — only 27% are, which says a lot about where the growth opportunity might be
- **Clothing** leads both revenue and sales by category, with Accessories not far behind
- **Young Adults and Middle-aged customers** drive the most revenue and sales, while Seniors and Adults trail behind
- You can filter everything by season, age group, gender, category, subscription status, and shipping type to dig deeper into any segment

## What's in this repo

| File | What it is |
|---|---|
| `Business Problem Document.pdf` | The problem statement and objectives behind this analysis |
| `Customer Shopping Behavior Analysis.pdf` | Write-up of the findings |
| `Customer-Shopping-Behavior-Analysis.pptx` | Presentation version of the analysis |
| `customer_behavior.sql` | SQL queries used to explore revenue and segments |
| `customer_behavior_dashboard.pbix` | The Power BI dashboard file |
| `customer_shopping_behavior.csv` | The raw dataset |
| `project.ipynb` | Python notebook for cleaning and prepping the data |

## Tools used

Python (pandas) for cleaning, SQL for analysis, and Power BI for the dashboard.

## How to use this

1. Clone the repo
2. Open `project.ipynb` to see the data cleaning steps
3. Check `customer_behavior.sql` for the queries behind the numbers
4. Open `customer_behavior_dashboard.pbix` in Power BI Desktop to explore the dashboard yourself

## License

This project is licensed under the MIT License see the `LICENSE` file for details.

---

If you spot something interesting in the data or have ideas for extending this, feel free to open an issue or reach out.
