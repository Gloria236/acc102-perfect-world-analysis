# Should Paying Players Trust Perfect World for Long-Term Spending?  
## A Financial Comparison with a Refined Peer Group

## 1. Problem & User
This project examines whether Perfect World appears financially strong enough to support stable long-term game operations compared with a refined peer group.

The target users are paying players who spend money on in-game items, accounts, or other virtual content and care about whether their spending will continue to hold value over time. For these users, long-term platform stability matters because weaker financial support may reduce the likelihood of stable updates, active game ecosystems, and lasting market interest.

## 2. Data
The data used in this project come from WRDS / CSMAR, mainly the financial master table and the company table.

The financial master table is used to extract Perfect World’s annual financial statement data and the financial data of the refined peer group. The company table is used to identify Perfect World’s industry classification and to help construct a more relevant peer group.

The data were accessed on 18 April 2026.

The key fields used in this project include:
- revenue
- net income
- total assets
- total liabilities
- operating cash flow
  
## 3. Methods
This project uses Python to build a clear analytical workflow from data extraction to final comparison.

### Main Python Steps
1. Extract Perfect World’s annual financial statement data from the WRDS / CSMAR financial master table.
2. Clean the raw company data by keeping one report type only, retaining year-end observations, and removing duplicate firm-year records.
3. Construct five financial indicators: revenue growth, debt ratio, operating cash flow to assets, net profit margin, and return on assets (ROA).
4. Use the WRDS / CSMAR company table to identify Perfect World’s narrower industry category.
5. Build a refined peer group by filtering candidate firms whose names are more closely related to games, interactive entertainment, and digital culture.
6. Extract and clean the peer-group financial data using the same rules applied to Perfect World.
7. Calculate yearly peer-group averages for the five indicators.
8. Compare Perfect World with the peer-group average using tables, charts, and summary statistics.
9. Use a simple rule-based summary to translate the comparison into an easy-to-understand financial signal.

The goal is to provide an accessible financial signal for users who care about long-term platform stability and spending risk.

## 4. Key Findings
- Perfect World shows relatively stronger average revenue performance than the refined peer-group average during this period.
- Perfect World has a lower average debt ratio than the peer group, suggesting relatively lower financial pressure.
- Perfect World shows stronger operating cash flow support than the peer group, indicating better operating support capacity.
- Perfect World also performs relatively better on profitability indicators such as net profit margin and ROA in this analysis.
- Overall, Perfect World appears financially stronger than the refined peer-group average, although this should be interpreted as a financial signal rather than a guarantee of future game success.

## 5. How to Run
Open the notebook and run all cells from top to bottom. 

## 6. Product Link / Demo

## 7. Limitations & Next Steps
- Company-level financial data cannot directly predict the future success of a specific game
- The peer group is refined rather than the entire game industry
- A future version could include game-level operational metrics and wider peer coverage
