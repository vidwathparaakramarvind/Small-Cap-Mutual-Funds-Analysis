# Small-cap Mutual Funds – Performance & Risk Analysis (India)

This repository contains a *team project* analysing a set of Indian small-cap mutual funds from the point of view of an investor:

- How have they performed across different time horizons?
- How much risk and drawdown did that performance come with?
- Are there meaningful differences in how they are positioned?
- Where could diversification or rebalancing help?

The entire analysis currently lives in an Excel workbook so that all calculations, intermediate sheets and final tables are visible in one place.

> *Note:* GitHub cannot show formulas or multiple sheets in the browser.  
> To see the full model, *download and open the Excel file locally.*

---

## 1. Project context

- *Type:* Team project for a college course on investments / portfolio management.  
- *Focus:* Indian *small-cap mutual funds* (regular plans, growth options).  
- *Goal:* Understand small-cap funds not just by “who has the highest return”, but by *risk, behaviour in bad markets and portfolio role*.

Each team member worked on different parts (data collection, cleaning, metrics, interpretation) and combined everything into one Excel model and presentation.


## 2. Universe and data

- *Universe:* a selection of Indian small-cap mutual funds (exact list in the Excel file, usually on a “Funds” or “Summary” sheet).  
- *Data used:*
  - Historical *NAV* data for each fund.  
  - Scheme details such as launch date, category, AUM and basic characteristics.  
- *Frequency:* daily or monthly NAVs (depending on availability from the source).  
- *Period covered:* multiple years of history, long enough to capture at least one strong drawdown and a recovery phase.

All of this is organised into input sheets inside the Excel workbook (for example, NAV Data, Fund Info, etc.).



## 3. Questions this project asks

The workbook is set up to help answer questions like:

### Performance

- Which funds have delivered the highest returns over 1Y/3Y/5Y (and other horizons)?  
- How consistent have these returns been over time?

### Risk & drawdowns

- How volatile is each fund?  
- How deep were the worst drawdowns?  
- Which funds recovered faster from big falls?

### Comparisons

- How do small-cap funds compare against each other on the *risk–return trade-off*, not just raw return?  
- Do larger AUM / older funds behave differently from newer, smaller funds?

### Portfolio thinking

- Are there pairs or small baskets of funds that together give a better *diversification of risk*?  
- How might an investor combine or rotate between funds rather than betting on a single “winner”?


## 4. Methodology 

The detailed formulas and steps are all visible sheet-by-sheet in the Excel file, but at a high level the workflow is:

1. *Data ingestion*  
   - Import NAV histories for all selected small-cap funds.  
   - Standardise fund names, dates and formats.

2. *Return calculations*  
   - Convert NAVs into periodic returns (daily, weekly or monthly).  
   - Aggregate into multi-horizon returns:
     - point-to-point returns (e.g. 1-year, 3-year, 5-year),  
     - and/or rolling returns over different windows.

3. *Risk and drawdown metrics*  
   - Compute volatility measures (standard deviation, etc.).  
   - Identify maximum and significant drawdowns.  
   - Compare how each fund behaved in periods of stress.

4. *Comparative analysis*  
   - Rank funds by different metrics:
     - absolute returns,  
     - risk-adjusted measures,  
     - depth / duration of drawdowns.  
   - Highlight funds that balance return and risk reasonably well rather than only focusing on the top-returning fund.

5. *Interpretation *  
   - Summarise key findings:
     - which funds stand out positively or negatively,  
     - how results line up with each fund’s style / positioning,  
     - what an investor should be cautious about with small-cap exposure in general.
---

## Team project note

This analysis was completed as a *team effort* for a college course.  
Responsibilities were shared across:

- data collection and cleaning,  
- metric design and calculation,  
- visualisation and summary tables,  
- interpretation and presentation.

This repository is simply a *clean home* for the final Excel model so that it can be revisited, extended or audited later.


## Disclaimer

- This project is *educational*, created as part of a college course.  
- It is *not investment advice* and does not recommend buying or selling any particular fund.  
- Data is taken from public sources and may contain errors or be incomplete.  
- Past performance is not indicative of future results.

If you notice issues in the data, formulas or interpretation, or if you have suggestions for better ways to analyse this universe, feedback is very welcome.
