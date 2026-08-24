# Investment KPI & ROI Tracking System

## Project Overview

The **Investment KPI & ROI Tracking System** is a non-coding Financial Analysis and Corporate Finance project designed to help management evaluate investment performance, compare planned vs actual results, identify underperforming investments, and support capital-allocation decisions.

The model simulates an investment portfolio for **ApexNova Technologies Ltd.** and evaluates 150 investment records across multiple business categories and departments.

The project demonstrates practical skills in:

- Financial Analysis
- Investment Analysis
- Corporate Finance
- FP&A
- Financial Modelling
- ROI Analysis
- NPV Analysis
- IRR Analysis
- Payback Period
- Budget vs Actual Analysis
- Risk-Return Analysis
- Scenario Analysis
- KPI Dashboarding
- Management Reporting

---

## Business Problem

Companies invest significant capital in technology, expansion, equipment, automation, marketing, product development, training and infrastructure.

However, management needs to continuously answer:

- Are investments generating the expected returns?
- Which investments are exceeding their ROI targets?
- Which projects are underperforming?
- Where are cost overruns occurring?
- Which departments receive the most capital?
- Which investments create the highest financial benefit?
- Which investments have attractive risk-return characteristics?
- Where should future capital be allocated?

This project provides a structured system to answer these questions.

---

## Objective

The objective is to build a practical investment-performance tracking system that:

1. Tracks investment capital.
2. Calculates financial KPIs.
3. Measures actual ROI against target ROI.
4. Evaluates NPV and IRR.
5. Measures Payback Period.
6. Compares budgeted vs actual investment.
7. Evaluates revenue and cost-saving achievement.
8. Analyses risk vs return.
9. Performs best/base/worst-case scenario analysis.
10. Provides management recommendations.
11. Supports capital-allocation decisions through an executive dashboard.

---

## Company Scenario

**Company:** ApexNova Technologies Ltd.

**Industry:** Technology & Business Solutions

**Illustrative Annual Revenue:** ₹1,850 Cr

**Illustrative Annual Investment Budget:** ₹300 Cr

**Financial Year:** FY2025-26

### Investment Categories

- Technology
- Marketing
- Product Development
- Expansion
- Equipment
- Automation
- Training
- Infrastructure

### Departments

- Sales
- Marketing
- Operations
- IT
- HR
- Finance
- Product
- Supply Chain

---

## Dataset

The project contains **150 realistic investment records**.

The dataset includes:

- Investment ID
- Investment Name
- Investment Category
- Department
- Region
- Start Date
- End Date
- Initial Investment
- Additional Investment
- Total Investment
- Budgeted Investment
- Actual Investment
- Expected Revenue
- Actual Revenue
- Expected Cost Savings
- Actual Cost Savings
- Expected Return
- Actual Return
- Net Benefit
- ROI
- Target ROI
- ROI Variance
- Payback Period
- NPV
- IRR
- Discount Rate
- Investment Status
- Risk Level
- Performance Rating
- Decision Recommendation

---

## Key Financial KPIs

### Total Investment

Total capital deployed across all investment projects.

**Total Investment = Initial Investment + Additional Investment**

### Net Benefit

**Net Benefit = Actual Revenue + Actual Cost Savings − Total Investment**

### ROI

**ROI = Net Benefit / Total Investment**

ROI measures the financial benefit generated relative to the capital invested.

### ROI Variance

**ROI Variance = Actual ROI − Target ROI**

This identifies whether an investment is performing above or below its approved target.

### Revenue Achievement

**Revenue Achievement % = Actual Revenue / Expected Revenue**

### Cost Saving Achievement

**Cost Saving Achievement % = Actual Cost Savings / Expected Cost Savings**

### Investment Variance

**Investment Variance = Actual Investment − Budgeted Investment**

### Investment Variance %

**Investment Variance % = Investment Variance / Budgeted Investment**

---

## ROI Analysis

The model compares actual ROI against target ROI.

Investment performance is classified as:

- Significantly Above Target
- Above Target
- On Target
- Below Target
- Significantly Below Target

ROI should not be used as the only investment decision metric because two projects can have similar ROI but very different investment sizes, risk levels, cash-flow patterns and recovery periods.

---

## NPV Analysis

Net Present Value measures the present value of future investment benefits after considering the time value of money.

### Interpretation

**NPV > 0**

The investment is expected to create value at the selected discount rate.

**NPV = 0**

The investment is approximately value-neutral.

**NPV < 0**

The investment does not generate sufficient value under the modeled assumptions.

---

## IRR Analysis

Internal Rate of Return represents the discount rate at which the investment's NPV becomes zero.

IRR can be compared with:

- Required Rate of Return
- Cost of Capital
- Hurdle Rate
- Alternative Investment Opportunities

IRR should not be used alone when projects differ significantly in size or cash-flow timing.

---

## Payback Period

Payback Period measures how quickly the investment recovers its capital.

A simplified calculation used in the model is:

**Payback Period = Total Investment / Annual Financial Benefit**

Payback is useful for understanding recovery speed, but it does not fully account for the time value of money or benefits received after the payback point.

---

## ROI vs NPV vs IRR vs Payback

| Metric | Measures | Main Advantage | Limitation |
|---|---|---|---|
| ROI | Return efficiency | Simple and easy to understand | Ignores timing and investment scale |
| NPV | Value creation | Considers time value of money | Depends on discount-rate assumptions |
| IRR | Investment return rate | Useful for comparing return rates | Can be misleading for unusual cash flows |
| Payback | Capital recovery speed | Easy liquidity/recovery measure | Ignores benefits after payback |

---

## Budget vs Actual Analysis

The model compares approved investment budgets with actual capital deployed.

Investments are analysed for:

- Within Budget
- Moderate Overrun
- Significant Overrun

Cost overruns can reduce ROI and may also negatively affect NPV.

---

## Investment Category Analysis

The model compares:

- Technology
- Marketing
- Product Development
- Expansion
- Equipment
- Automation
- Training
- Infrastructure

Metrics include:

- Capital Invested
- Financial Benefit
- ROI
- NPV
- Payback
- Risk

This helps management identify categories that deserve additional capital and categories that require review.

---

## Department Analysis

Investments are evaluated across:

- Sales
- Marketing
- Operations
- IT
- HR
- Finance
- Product
- Supply Chain

The analysis identifies:

- Highest capital allocation
- Highest ROI
- Lowest ROI
- Largest cost overruns
- Highest financial benefit

---

## Risk-Return Analysis

Investments are evaluated using return and risk.

The model considers:

### High Return + Low Risk

Potential priority investments.

### High Return + High Risk

Potentially attractive but require stronger governance.

### Low Return + Low Risk

Stable but may provide limited value.

### Low Return + High Risk

Potential candidates for restructuring, review or exit.

---

## Scenario Analysis

Three scenarios are modelled:

### Best Case

- Revenue increases by 12%
- Cost savings increase by 12%
- Costs reduce by 6%

### Base Case

Current expected assumptions.

### Worst Case

- Revenue decreases by 18%
- Cost savings decrease by 22%
- Costs increase by 10%

The scenarios help management understand how changes in assumptions can affect:

- Financial Benefit
- Net Benefit
- ROI
- NPV
- Payback

---

## Investment Performance Dashboard

The executive dashboard contains:

### KPI Cards

- Total Investment
- Total Financial Benefit
- Average ROI
- Total NPV
- Investments Above Target
- Investments Below Target

### Visualisations

- Investment vs Return
- ROI by Investment Category
- Target ROI vs Actual ROI
- Department-wise Capital Allocation
- Investment Performance Trend
- Risk vs Return Matrix
- Budget vs Actual Investment
- NPV vs IRR
- Payback Period
- Top Investment Ranking

### Filters

- Year
- Department
- Region
- Investment Category
- Risk Level
- Investment Status

---

## Management Recommendations

The model supports recommendations such as:

1. Increase capital allocation toward investments consistently exceeding target ROI.
2. Review projects with significant budget overruns.
3. Closely monitor high-return/high-risk investments.
4. Restructure investments with persistent underperformance.
5. Review negative-NPV projects before committing additional capital.
6. Improve investment approval assumptions using historical project performance.
7. Conduct periodic post-investment reviews.
8. Use multiple KPIs rather than ROI alone for capital-allocation decisions.

---

## Investment Decision Framework

The investment decision process follows:

**Investment Opportunity**

↓

**Capital Required**

↓

**Expected Cash Flows**

↓

**ROI**

↓

**NPV**

↓

**IRR**

↓

**Payback**

↓

**Risk**

↓

**Strategic Fit**

↓

**INVEST / REVIEW / REJECT**

---

## Excel Workbook Structure

The Excel model contains:

1. `Raw_Data`
2. `Investment_Master`
3. `ROI_Analysis`
4. `NPV_IRR`
5. `Budget_vs_Actual`
6. `Department_Analysis`
7. `Risk_Return`
8. `Scenario_Analysis`
9. `KPI_Summary`
10. `Dashboard`

---

## Tools Used

- Microsoft Excel
- Financial Modelling
- Corporate Finance
- FP&A
- Investment Analysis
- Data Analysis
- KPI Development
- Dashboard Design
- Scenario Analysis

The dataset is also structured to be suitable for future Power BI implementation.

---

## Power BI Extension

The Excel model can be imported into Power BI for:

- Interactive dashboards
- Drill-down analysis
- Dynamic filters
- KPI cards
- Investment ranking
- Department analysis
- Category analysis
- Risk-return analysis
- Management reporting

---

## Key Learning Outcomes

This project demonstrates practical ability to:

- Structure financial datasets
- Build investment models
- Calculate financial KPIs
- Perform ROI analysis
- Evaluate NPV and IRR
- Analyse investment risk
- Perform variance analysis
- Build scenarios
- Create management dashboards
- Translate financial data into business recommendations

---

## Future Scope

### Practical Enhancements

- ERP integration
- Automated investment data feeds
- Rolling investment forecasts
- Automated management reporting
- Investment alerts
- Power BI integration

### Advanced Enhancements

- Monte Carlo simulation
- Sensitivity analysis
- Predictive ROI forecasting
- AI-assisted investment commentary
- Portfolio optimization
- Automated capital-allocation recommendations

---

## Conclusion

The Investment KPI & ROI Tracking System converts raw investment data into a structured financial decision-support model.

It demonstrates how a Financial Analyst or FP&A professional can combine financial modelling, KPI analysis, variance analysis, risk assessment and dashboarding to support management decisions and improve capital allocation.

---

## Portfolio

**Project Type:** Financial Analyst / Corporate Finance / FP&A

**Dataset:** 150 investment records

**Primary Tool:** Microsoft Excel

**Future BI Tool:** Power BI

**Project Focus:** Investment Performance, ROI, NPV, IRR, Payback and Capital Allocation
