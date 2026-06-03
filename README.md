# Greggs PLC — Leveraged Buyout Model

## Overview
A leveraged buyout analysis of Greggs PLC (LSE: GRG), built from scratch using real financial data extracted directly from annual reports (FY2022–FY2025). 
No templates used.

## Investment Recommendation
**Do Not Invest at Current Terms**

At a 14.0x EV/EBITDA entry multiple the transaction generates a MOIC of 1.33x and IRR of 7.36% over a 4 year hold period — significantly below typical PE 
return thresholds of 2.5x and 20% respectively.

Free cash flow covers less than 0.3x of annual interest expense in every projected year, causing debt to grow from £2,458m to £2,901m at exit. 
The deal does not work at current terms.

## Model Structure

| Tab | Contents |
|---|---|
| Cover | Investment recommendation and model summary |
| Assumptions | Operating, cash flow and deal assumptions with rationale |
| Income Statement | FY2022–FY2025 historical + FY2026–FY2029 projected |
| Balance Sheet | FY2022–FY2025 historical reference |
| Debt Schedule | Interest, FCF, shortfall and closing debt by year |
| Returns | Sources & Uses, Purchase Price Bridge, Exit Value, MOIC, IRR, Scenario Analysis, IRR and MOIC Sensitivity Tables |

## Key Returns

| Metric | Bear Case | Base Case | Bull Case |
|---|---|---|---|
| MOIC | 1.05x | 1.33x | 1.62x |
| IRR | 1.34% | 7.36% | 12.79% |

## IRR Sensitivity — Entry vs Exit Multiple

| | Exit 12x | Exit 13x | Exit 14x | Exit 15x |
|---|---|---|---|---|
| Entry 12x | 7.98% | 11.86% | 15.38% | 18.60% |
| Entry 13x | 3.61% | 7.65% | 11.28% | 14.59% |
| Entry 14x | -0.64% | 3.59% | 7.36% | 10.77% |
| Entry 15x | -4.82% | -0.35% | 3.58% | 7.12% |

## MOIC Sensitivity — Entry vs Exit Multiple

| | Exit 12x | Exit 13x | Exit 14x | Exit 15x |
|---|---|---|---|---|
| Entry 12x | 1.36x | 1.57x | 1.77x | 1.98x |
| Entry 13x | 1.15x | 1.34x | 1.53x | 1.72x |
| Entry 14x | 0.97x | 1.15x | 1.33x | 1.51x |
| Entry 15x | 0.82x | 0.99x | 1.15x | 1.32x |

Even at the most optimistic scenario — Entry 12x, Exit 15x — MOIC reaches only 1.98x and IRR only 18.6%, both still below PE thresholds of 2.5x and 20%.

## Key Findings
- Greggs carries no significant financial debt pre-LBO
- FCF covers less than 0.3x of annual interest expense across all projected years
- Heavy Capex programme (13.3% of revenue in FY2025) is the primary constraint on debt serviceability
- Standard 60% leverage tested and found unsustainable
- Deal requires entry below 10x or material Capex reduction to generate acceptable returns

## Assumptions Summary

| Assumption | FY2026E | FY2027E | FY2028E | FY2029E |
|---|---|---|---|---|
| Revenue Growth | 6.0% | 5.5% | 5.0% | 4.5% |
| EBITDA Margin | 16.5% | 16.5% | 16.5% | 16.5% |
| Capex % Revenue | 12.0% | 11.0% | 10.0% | 10.0% |
| Tax Rate | 25.0% | 25.0% | 25.0% | 25.0% |

## Deal Structure

| Parameter | Value |
|---|---|
| Entry EV/EBITDA | 14.0x |
| Exit EV/EBITDA | 14.0x |
| Equity Contribution | 50% |
| Debt Contribution | 50% |
| Hold Period | 4 years |
| Entry EV | £4,820.2m |
| Total Debt at Entry | £2,458.3m |
| Total Debt at Exit | £2,901.3m |

## Data Sources
- Greggs PLC Annual Report 2025
- Greggs PLC Annual Report 2023
- London Stock Exchange: GRG

## Tools
- Microsoft Excel
- Built from blank spreadsheet — no templates used

## Notes
Interest expense is held in the debt schedule rather than flowing through the income statement to avoid an unresolved circular reference.
In a production model this would be resolved using iterative calculation in Excel.

Balance sheet projections are excluded. 
Historical data (FY2022–FY2025) is included 
for reference only.

## About
Built as a portfolio project to demonstrate LBO 
modelling capability for finance analyst applications. 
All assumptions are documented with rationale.
