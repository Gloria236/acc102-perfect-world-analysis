# Should Paying Players Trust Perfect World for Long-Term Spending?  
## A Financial Comparison with a Refined Peer Group

## 1. Problem & User
Many paying players spend money on in-game items, accounts, skins, characters, and other virtual content. For them, game spending may depend on whether the company is financially stable enough to support regular updates, servers, events, and long-term services.

This project asks:
**Does Perfect World appear financially strong enough, compared with similar game and digital entertainment firms, to support stable long-term game operations?**

To answer this question, the project compares Perfect World with a refined peer group of firms related to games, interactive entertainment, digital culture, media, and online services.

The target users are paying players, gaming consumers, and entry-level observers of the entertainment industry who want a simple financial signal about long-term platform stability and spending risk.

## 2. Data
The data are obtained from WRDS / CSMAR.

The project uses two main data sources:
- Financial Master Table
- Company Information Table

The analysis uses annual financial statement data from 2019 to 2024.

Key financial variables include:
- revenue
- net income
- current assets
- total assets
- current liabilities
- total liabilities
- operating cash flow.

The original WRDS / CSMAR data are not redistributed in this repository because access is restricted to authorised users.

Data accessed: April 2026.


## 3. Methods
Python is used to complete the full data analysis workflow.

The main steps are:
1. Extract Perfect World’s annual financial data from WRDS / CSMAR.
2. Clean the data by keeping annual report data and year-end observations.
3. Construct eight financial indicators:
   - revenue growth;
   - debt ratio;
   - operating cash flow to assets;
   - net profit margin;
   - return on assets;
   - current ratio;
   - asset turnover;
   - operating cash flow to net income.
4. Identify Perfect World’s WRDS / CSMAR industry category.
5. Build a refined peer group using industry classification and company-name keyword filtering.
6. Exclude Perfect World from the peer group so that the benchmark is not affected by the target company.
7. Extract and clean peer-group financial data using the same rules.
8. Calculate peer-group yearly averages.
9. Compare Perfect World with the peer-group average through tables and visualisations.
10. Use a simple rule-based scoring method to summarise the final financial signal.

## 4. Key Findings
The analysis suggests that Perfect World shows mixed but moderately strong financial performance relative to the refined peer group.

Main findings include:
- Perfect World has weaker average revenue growth than the peer group.
- Perfect World shows stronger operating cash-flow support.
- Perfect World performs better in net profit margin and return on assets.
- Perfect World’s debt ratio is very close to the peer-group average.
- Perfect World has a lower current ratio than the peer group.
- Perfect World performs slightly better in asset turnover.
- Perfect World shows stronger operating cash flow relative to net income.

Overall, Perfect World does not appear financially weak. However, its weaker revenue growth suggests potential pressure on future expansion. For paying players, this means the company may show moderate financial reliability, but it should not be treated as completely low-risk.

## 5.How to Run
To run this project:
1. Open `acc102 notebook+Qingyi Gao+2468280.ipynb`.
2. Make sure the following Python packages are installed:
   - pandas
   - numpy
   - matplotlib
3. Run the notebook cells in order.
4. Enter a valid WRDS username when prompted.
5. The notebook will extract, clean, analyse, and visualise the data.

## 6.Product link
https://video.xjtlu.edu.cn/Mediasite/MyMediasite/drafts

## 7. Limitations & Next Steps

This project has several limitations.

First, the peer group is constructed using industry classification and company-name keyword screening. Therefore, it may not perfectly represent the full game industry.

Second, some financial ratios may be affected by negative or very small denominators, especially operating cash flow to net income.

Third, financial statement data can show company-level financial capacity, but it cannot directly measure game quality, player satisfaction, product update frequency, server stability, or future strategic decisions.

Future improvements could include adding non-financial indicators, such as game release frequency, user activity, player reviews, update frequency, segment-level game revenue, and market share data.
