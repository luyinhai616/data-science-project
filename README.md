# Tourism and Consumer Prices in Macao (2010–2025)

## Research Question
How are monthly visitor arrivals associated with Macao's Composite Consumer Price Index (CPI) from 2010 to 2025?

## Data Sources
Data come from the **Macao Statistics and Census Service (DSEC)**:
- [Monthly visitor arrivals](https://www.dsec.gov.mo/ts/#!/step2/PredefinedReport/en-US/18)
- [Composite CPI](https://www.dsec.gov.mo/ts/#!/step2/PredefinedReport/en-US/14)
- [CPI by goods and services sections](https://www.dsec.gov.mo/ts/#!/step2/PredefinedReport/en-US/15)

The data are publicly accessible. Check DSEC's reuse terms before redistributing the Excel files.

## Methods and Tools
I used **Python, Pandas, Matplotlib, Seaborn, and Jupyter Notebook** to clean and combine monthly data, create visualizations, and examine correlations. The analysis covers 192 months and compares the periods before, during, and after COVID-19.

## Key Findings
- Visitor arrivals fell sharply during COVID-19, while CPI remained relatively stable.
- The overall correlation between visitor arrivals and CPI was weak (**r = -0.084**), but the relationship differed across periods.
- Visitor arrivals alone do not explain changes in Macao's consumer prices.

## Limitation
Correlation does **not** prove causation. Other factors, such as rents, wages, and global inflation, may affect CPI. Visitor arrivals and CPI are only indirect measures of tourism pressure and residents' quality of life.

## How to Run
1. Install the required packages: `pip install pandas numpy matplotlib seaborn openpyxl statsmodels jupyter`
2. Download the DSEC Excel data, save them as `visitor_arrivals.xlsx` and `cpi_data.xlsx`, and place them beside the notebook. The workbook sheets must match the notebook's expected layout.
3. Create a `figures` folder, open the `.ipynb` file in Jupyter Notebook, and run all cells.
