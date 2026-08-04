# sales-data-analysis

\# Sales Data Analysis



Exploratory data analysis of a real-world sales transactions dataset (2003–2005), 

uncovering revenue trends, top-performing product lines, and key markets.



\## Dataset



\- Source: \[Sample Sales Data](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data) (Kaggle)

\- 2,823 transactions across 25 columns, including order details, product line, 

&#x20; customer, and geographic information

\- Contains real-world data quality issues (missing values in address, state, 

&#x20; and territory fields), handled during analysis



\## Tools Used



\- Python (pandas, matplotlib)

\- Google Colab



\## Key Findings



\- \*\*Total revenue\*\*: $10,032,628.85 across the dataset period

\- \*\*Top product line\*\*: Classic Cars generated $3.9M in revenue — more than double 

&#x20; the next closest category (Vintage Cars, $1.9M)

\- \*\*Top market\*\*: USA led all countries with $3.6M in revenue, followed by Spain 

&#x20; ($1.2M) and France ($1.1M)

\- \*\*Revenue trend\*\*: Peaked in 2004 ($4.7M); 2005 figures are partial (data 

&#x20; coverage ends mid-year)



\## Visualizations



\*\*Revenue by Product Line\*\*

!\[Revenue by Product Line](revenue\_by\_product.png)



\*\*Monthly Revenue Trend\*\*

!\[Monthly Revenue Trend](monthly\_revenue\_trend.png)



\## Files



\- `analysis.ipynb` — full analysis notebook (data loading, cleaning, analysis, charts)

\- `sales\_data\_sample.csv` — raw dataset

\- `revenue\_by\_product.png`, `monthly\_revenue\_trend.png` — exported charts



\## What I Learned



Practiced core data analysis workflow: loading and inspecting real-world data, 

identifying and handling missing values, aggregating data with pandas groupby, 

and building clear visualizations to communicate findings.

