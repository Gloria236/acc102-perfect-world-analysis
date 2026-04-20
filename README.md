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
- company code
- company name
- accounting period
- report type
- industry classification
- 
## 3. Methods
- Extract Perfect World annual financial data from WRDS/CSMAR
- Clean the data to keep annual year-end observations only
- Build a refined peer group using WRDS/CSMAR industry information and company-name filtering
- Calculate five indicators: revenue growth, debt ratio, OCF/assets, net profit margin, and ROA
- Compare Perfect World with the refined peer-group average

## 4. Key Findings
- Perfect World shows stronger average revenue performance than the refined peer-group average during this period
- Perfect World has a lower average debt ratio than the peer group
- Perfect World shows stronger operating cash flow support than the peer group
- Overall, Perfect World appears financially stronger than the refined peer-group average in this analysis

## 5. How to Run
Open the notebook and run all cells from top to bottom.  
WRDS access is required for full reproduction.

## 6. Product Link / Demo
Add your 1–3 minute demo video link here.

## 7. Limitations & Next Steps
- Company-level financial data cannot directly predict the future success of a specific game
- The peer group is refined rather than the entire game industry
- A future version could include game-level operational metrics and wider peer coverage
