# Global Macro Economic Simulations and Financial Market Responses

v6 · IRF · evaluation

**Open the typeset report (this is the document):** https://robomacro.com/GlobalMacroTrainingDataset/uk_housing_25/

GitHub and Hugging Face show `.html` as source code. That is not the report. Read it on robomacro.com, or keep scrolling this page.

## What's the impact of UK housing -25%

### Active treatment

```json
{
  "housing": {
    "UK": -0.25
  }
}
```

### Assumptions

- Every path is a model impulse response versus baseline, not a forecast.
- The solver and weights are not included.
- English never enters the solver.

### Summary

This report traces the model response to a -25% United Kingdom housing shock. Every path is an impulse response versus an unchanged baseline — not a forecast and not market data. The question was: What's the impact of UK housing -25%

United Kingdom sees a -3.27% GDP peak at Q20, with CPI -0.70pp over three years and equities -8.09%. Netherlands sees a -0.15% GDP peak at Q20, with CPI -0.04pp over three years and equities -0.38%. Switzerland sees a -0.14% GDP peak at Q14, with CPI -0.04pp over three years and equities -0.53%. Germany sees a -0.12% GDP peak at Q14, with CPI -0.04pp over three years and equities -0.22%.

The remaining countries are smaller spillovers and are covered in the chapters that follow. This material is a model-based summary and is not financial advice.

### Countries by GDP impact

- [UK — United Kingdom](#uk--united-kingdom) · GDP -3.27% Q20
- [NL — Netherlands](#nl--netherlands) · GDP -0.15% Q20
- [CH — Switzerland](#ch--switzerland) · GDP -0.14% Q14
- [DE — Germany](#de--germany) · GDP -0.12% Q14
- [FR — France](#fr--france) · GDP -0.10% Q14
- [US — United States](#us--united-states) · GDP -0.09% Q12
- [NO — Norway](#no--norway) · GDP -0.07% Q16
- [SE — Sweden](#se--sweden) · GDP -0.07% Q20
- [ES — Spain](#es--spain) · GDP -0.07% Q14
- [AU — Australia](#au--australia) · GDP -0.06% Q13
- [CA — Canada](#ca--canada) · GDP -0.06% Q12
- [JP — Japan](#jp--japan) · GDP -0.06% Q13
- [SA — Saudi Arabia](#sa--saudi-arabia) · GDP -0.04% Q13
- [AR — Argentina](#ar--argentina) · GDP +0.04% Q20
- [PL — Poland](#pl--poland) · GDP -0.04% Q13
- [ZA — South Africa](#za--south-africa) · GDP -0.04% Q11
- [CN — China](#cn--china) · GDP -0.04% Q11
- [IT — Italy](#it--italy) · GDP -0.03% Q13
- [TR — Turkey](#tr--turkey) · GDP -0.03% Q10
- [MY — Malaysia](#my--malaysia) · GDP -0.02% Q12
- [IN — India](#in--india) · GDP -0.02% Q9
- [TH — Thailand](#th--thailand) · GDP -0.02% Q12
- [BR — Brazil](#br--brazil) · GDP -0.02% Q10
- [MX — Mexico](#mx--mexico) · GDP -0.02% Q10
- [KR — South Korea](#kr--south-korea) · GDP -0.02% Q10
- [NG — Nigeria](#ng--nigeria) · GDP -0.02% Q9
- [RU — Russia](#ru--russia) · GDP -0.02% Q10
- [CL — Chile](#cl--chile) · GDP -0.01% Q10
- [CO — Colombia](#co--colombia) · GDP -0.01% Q9
- [ID — Indonesia](#id--indonesia) · GDP -0.01% Q9

![UK GDP](charts/global_UK_Y.png)

![NL GDP](charts/global_NL_Y.png)

![CH GDP](charts/global_CH_Y.png)

![DE GDP](charts/global_DE_Y.png)

![US Equity Index](charts/global_US_equity.png)

![US Policy Rate](charts/global_US_i.png)

## UK — United Kingdom

The main impact of a -25% United Kingdom housing shock on United Kingdom would be a large drop in GDP of 3.27% by Q20. Equities peak at -8.09% in Q20.

Demand and trade. Consumption peaks at -2.09 % vs baseline in Q20, from +0.00 in Q1 to -2.09 in Q20. Investment peaks at -8.84 % vs baseline in Q20, from +0.00 in Q1 to -8.84 in Q20. Net Exports peaks at +0.21 % vs baseline in Q20, from +0.00 in Q1 to +0.21 in Q20. Gov Spending peaks at +0.67 % vs baseline in Q20, from +0.00 in Q1 to +0.67 in Q20. Gov Debt peaks at -0.28 % vs baseline in Q20, from +0.00 in Q1 to -0.28 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Currency Strength peaks at +0.24 % vs baseline in Q20, from +0.00 in Q1 to +0.24 in Q20.

Labour. Employment peaks at -3.38 % vs baseline in Q20, from +0.00 in Q1 to -3.38 in Q20. Unemployment peaks at +2.06 pp in Q20, from +0.00 in Q1 to +2.06 in Q20. Real Wages peaks at -1.97 % vs baseline in Q20, from +0.00 in Q1 to -1.97 in Q20.

Prices. The three-year CPI impulse is -0.70 percentage points. CPI Inflation peaks at -0.17 pp in Q20, from +0.00 in Q1 to -0.17 in Q20. Domestic Infl. peaks at -0.12 pp in Q20, from +0.00 in Q1 to -0.12 in Q20. Marginal Cost peaks at -1.96 % vs baseline in Q20, from +0.00 in Q1 to -1.96 in Q20.

Financial conditions. Policy Rate peaks at -0.32 pp (annualized) in Q20, from +0.00 in Q1 to -0.32 in Q20. Govt 2Y Yield peaks at -0.42 pp (annualized) in Q20, from -0.02 in Q1 to -0.42 in Q20. Govt 5Y Yield peaks at -0.60 pp (annualized) in Q20, from -0.12 in Q1 to -0.60 in Q20. Govt 10Y Yield peaks at -0.84 pp (annualized) in Q20, from -0.38 in Q1 to -0.84 in Q20. Bond Price peaks at +2.21 % vs baseline in Q20, from +0.00 in Q1 to +2.21 in Q20. Equity Index peaks at -8.09 % vs baseline in Q20, from +0.00 in Q1 to -8.09 in Q20. Tobin's Q peaks at -6.19 % vs baseline in Q20, from +0.00 in Q1 to -6.19 in Q20. House Prices peaks at -27.63 % vs baseline in Q20, from +0.00 in Q1 to -27.63 in Q20. Bank Credit peaks at -9.55 % vs baseline in Q20, from +0.00 in Q1 to -9.55 in Q20. Credit Spread peaks at +0.12 pp in Q20, from +0.00 in Q1 to +0.12 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.62 % vs baseline in Q20, from +0.00 in Q1 to -0.62 in Q20. Services GDP peaks at -2.59 % vs baseline in Q20, from +0.00 in Q1 to -2.59 in Q20. Capital Stock peaks at -0.50 % vs baseline in Q20, from +0.00 in Q1 to -0.50 in Q20.

Timing. By Q20 GDP is still -3.27% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/UK_Y.png)

![CPI Inflation](charts/UK_pi_cpi.png)

![Equity Index](charts/UK_equity.png)

![House Prices](charts/UK_P_H.png)

![Bank Credit](charts/UK_credit_supply.png)

![Investment](charts/UK_I.png)

![Tobin's Q](charts/UK_Q.png)

![Employment](charts/UK_N.png)

![Services GDP](charts/UK_gdp_services.png)

![Bond Price](charts/UK_Q_B.png)

![Consumption](charts/UK_C.png)

![Unemployment](charts/UK_unemployment.png)

[Q1–Q20 JSON for United Kingdom](numbers/UK.json)

## NL — Netherlands

The main impact of a -25% United Kingdom housing shock on Netherlands would be a moderate drop in GDP of 0.15% by Q20. Equities peak at -0.38% in Q20.

Demand and trade. Consumption peaks at -0.09 % vs baseline in Q20, from +0.00 in Q1 to -0.09 in Q20. Investment peaks at -0.41 % vs baseline in Q20, from +0.00 in Q1 to -0.41 in Q20. Net Exports peaks at +0.01 % vs baseline in Q9, from -0.00 in Q1 to +0.00 in Q20. Gov Spending peaks at +0.03 % vs baseline in Q20, from +0.00 in Q1 to +0.03 in Q20. Gov Debt peaks at +0.04 % vs baseline in Q20, from +0.00 in Q1 to +0.04 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Currency Strength peaks at -0.03 % vs baseline in Q20, from -0.00 in Q1 to -0.03 in Q20.

Labour. Employment peaks at -0.14 % vs baseline in Q20, from +0.00 in Q1 to -0.14 in Q20. Unemployment peaks at +0.10 pp in Q20, from +0.00 in Q1 to +0.10 in Q20. Real Wages peaks at -0.13 % vs baseline in Q20, from +0.00 in Q1 to -0.13 in Q20.

Prices. The three-year CPI impulse is -0.04 percentage points. CPI Inflation peaks at -0.01 pp in Q13, from -0.00 in Q1 to -0.01 in Q20. Domestic Infl. peaks at -0.00 pp in Q13, from -0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.09 % vs baseline in Q20, from +0.00 in Q1 to -0.09 in Q20.

Financial conditions. Policy Rate peaks at +0.00 pp (annualized) in Q1, from +0.00 in Q1 to +0.00 in Q20. Govt 2Y Yield peaks at +0.00 pp (annualized) in Q1, from +0.00 in Q1 to +0.00 in Q20. Govt 5Y Yield peaks at +0.00 pp (annualized) in Q1, from +0.00 in Q1 to +0.00 in Q20. Govt 10Y Yield peaks at +0.00 pp (annualized) in Q1, from +0.00 in Q1 to +0.00 in Q20. Bond Price peaks at +0.07 % vs baseline in Q19, from -0.00 in Q1 to +0.07 in Q20. Equity Index peaks at -0.38 % vs baseline in Q20, from +0.00 in Q1 to -0.38 in Q20. Tobin's Q peaks at -0.28 % vs baseline in Q20, from +0.00 in Q1 to -0.28 in Q20. House Prices peaks at -0.18 % vs baseline in Q20, from +0.00 in Q1 to -0.18 in Q20. Bank Credit peaks at -0.27 % vs baseline in Q20, from +0.00 in Q1 to -0.27 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.02 % vs baseline in Q11, from +0.00 in Q1 to -0.01 in Q20. Services GDP peaks at -0.11 % vs baseline in Q20, from +0.00 in Q1 to -0.11 in Q20. Capital Stock peaks at -0.03 % vs baseline in Q20, from +0.00 in Q1 to -0.03 in Q20.

Timing. By Q20 GDP is still -0.15% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/NL_Y.png)

![CPI Inflation](charts/NL_pi_cpi.png)

![Equity Index](charts/NL_equity.png)

![Investment](charts/NL_I.png)

![Tobin's Q](charts/NL_Q.png)

![Bank Credit](charts/NL_credit_supply.png)

![House Prices](charts/NL_P_H.png)

![Employment](charts/NL_N.png)

![Real Wages](charts/NL_w.png)

![Services GDP](charts/NL_gdp_services.png)

![Unemployment](charts/NL_unemployment.png)

![Consumption](charts/NL_C.png)

[Q1–Q20 JSON for Netherlands](numbers/NL.json)

## CH — Switzerland

The main impact of a -25% United Kingdom housing shock on Switzerland would be a moderate drop in GDP of 0.14% by Q14. Equities peak at -0.53% in Q14.

Demand and trade. Consumption peaks at -0.10 % vs baseline in Q15, from +0.00 in Q1 to -0.09 in Q20. Investment peaks at -0.34 % vs baseline in Q13, from -0.00 in Q1 to -0.28 in Q20. Net Exports peaks at +0.01 % vs baseline in Q14, from +0.00 in Q1 to +0.01 in Q20. Gov Spending peaks at +0.03 % vs baseline in Q14, from +0.00 in Q1 to +0.03 in Q20. Gov Debt peaks at -0.08 % vs baseline in Q20, from +0.00 in Q1 to -0.08 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Currency Strength peaks at -0.07 % vs baseline in Q20, from +0.00 in Q1 to -0.07 in Q20.

Labour. Employment peaks at -0.14 % vs baseline in Q19, from +0.00 in Q1 to -0.14 in Q20. Unemployment peaks at +0.10 pp in Q19, from +0.00 in Q1 to +0.10 in Q20. Real Wages peaks at -0.09 % vs baseline in Q20, from +0.00 in Q1 to -0.09 in Q20.

Prices. The three-year CPI impulse is -0.04 percentage points. CPI Inflation peaks at -0.00 pp in Q7, from +0.00 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q7, from +0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.08 % vs baseline in Q14, from +0.00 in Q1 to -0.07 in Q20.

Financial conditions. Policy Rate peaks at -0.04 pp (annualized) in Q20, from +0.00 in Q1 to -0.04 in Q20. Govt 2Y Yield peaks at -0.05 pp (annualized) in Q20, from -0.01 in Q1 to -0.05 in Q20. Govt 5Y Yield peaks at -0.05 pp (annualized) in Q20, from -0.02 in Q1 to -0.05 in Q20. Govt 10Y Yield peaks at -0.04 pp (annualized) in Q18, from -0.03 in Q1 to -0.04 in Q20. Bond Price peaks at +0.31 % vs baseline in Q20, from -0.00 in Q1 to +0.31 in Q20. Equity Index peaks at -0.53 % vs baseline in Q14, from +0.00 in Q1 to -0.48 in Q20. Tobin's Q peaks at -0.23 % vs baseline in Q13, from -0.00 in Q1 to -0.20 in Q20. House Prices peaks at -0.16 % vs baseline in Q20, from +0.00 in Q1 to -0.16 in Q20. Bank Credit peaks at -0.35 % vs baseline in Q20, from +0.00 in Q1 to -0.35 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.01 % vs baseline in Q13, from -0.00 in Q1 to -0.00 in Q20. Services GDP peaks at -0.11 % vs baseline in Q14, from +0.00 in Q1 to -0.10 in Q20. Capital Stock peaks at -0.02 % vs baseline in Q20, from +0.00 in Q1 to -0.02 in Q20.

Timing. By Q20 GDP is still -0.12% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/CH_Y.png)

![CPI Inflation](charts/CH_pi_cpi.png)

![Equity Index](charts/CH_equity.png)

![Bank Credit](charts/CH_credit_supply.png)

![Investment](charts/CH_I.png)

![Bond Price](charts/CH_Q_B.png)

![Tobin's Q](charts/CH_Q.png)

![House Prices](charts/CH_P_H.png)

![Employment](charts/CH_N.png)

![Services GDP](charts/CH_gdp_services.png)

![Consumption](charts/CH_C.png)

![Unemployment](charts/CH_unemployment.png)

[Q1–Q20 JSON for Switzerland](numbers/CH.json)

## DE — Germany

The main impact of a -25% United Kingdom housing shock on Germany would be a moderate drop in GDP of 0.12% by Q14. Equities peak at -0.22% in Q14.

Demand and trade. Consumption peaks at -0.07 % vs baseline in Q15, from +0.00 in Q1 to -0.07 in Q20. Investment peaks at -0.33 % vs baseline in Q14, from +0.00 in Q1 to -0.31 in Q20. Net Exports peaks at +0.03 % vs baseline in Q13, from -0.00 in Q1 to +0.02 in Q20. Gov Spending peaks at +0.03 % vs baseline in Q14, from +0.00 in Q1 to +0.02 in Q20. Gov Debt peaks at +0.02 % vs baseline in Q20, from +0.00 in Q1 to +0.02 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Currency Strength peaks at -0.05 % vs baseline in Q20, from -0.00 in Q1 to -0.05 in Q20.

Labour. Employment peaks at -0.12 % vs baseline in Q20, from +0.00 in Q1 to -0.12 in Q20. Unemployment peaks at +0.08 pp in Q20, from +0.00 in Q1 to +0.08 in Q20. Real Wages peaks at -0.12 % vs baseline in Q20, from +0.00 in Q1 to -0.12 in Q20.

Prices. The three-year CPI impulse is -0.04 percentage points. CPI Inflation peaks at -0.01 pp in Q13, from -0.00 in Q1 to -0.01 in Q20. Domestic Infl. peaks at -0.01 pp in Q13, from -0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.07 % vs baseline in Q14, from +0.00 in Q1 to -0.07 in Q20.

Financial conditions. Policy Rate peaks at +0.00 pp (annualized) in Q1, from +0.00 in Q1 to +0.00 in Q20. Govt 2Y Yield peaks at +0.00 pp (annualized) in Q1, from +0.00 in Q1 to +0.00 in Q20. Govt 5Y Yield peaks at +0.00 pp (annualized) in Q1, from +0.00 in Q1 to +0.00 in Q20. Govt 10Y Yield peaks at +0.00 pp (annualized) in Q1, from +0.00 in Q1 to +0.00 in Q20. Bond Price peaks at +0.07 % vs baseline in Q19, from -0.00 in Q1 to +0.07 in Q20. Equity Index peaks at -0.22 % vs baseline in Q14, from +0.00 in Q1 to -0.20 in Q20. Tobin's Q peaks at -0.23 % vs baseline in Q14, from +0.00 in Q1 to -0.21 in Q20. House Prices peaks at -0.14 % vs baseline in Q20, from +0.00 in Q1 to -0.14 in Q20. Bank Credit peaks at -0.32 % vs baseline in Q20, from +0.00 in Q1 to -0.32 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.02 % vs baseline in Q10, from +0.00 in Q1 to -0.01 in Q20. Services GDP peaks at -0.08 % vs baseline in Q14, from +0.00 in Q1 to -0.08 in Q20. Capital Stock peaks at -0.02 % vs baseline in Q20, from +0.00 in Q1 to -0.02 in Q20.

Timing. By Q20 GDP is still -0.11% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/DE_Y.png)

![CPI Inflation](charts/DE_pi_cpi.png)

![Equity Index](charts/DE_equity.png)

![Investment](charts/DE_I.png)

![Bank Credit](charts/DE_credit_supply.png)

![Tobin's Q](charts/DE_Q.png)

![House Prices](charts/DE_P_H.png)

![Employment](charts/DE_N.png)

![Real Wages](charts/DE_w.png)

![Unemployment](charts/DE_unemployment.png)

![Services GDP](charts/DE_gdp_services.png)

![Marginal Cost](charts/DE_mc.png)

[Q1–Q20 JSON for Germany](numbers/DE.json)

## FR — France

The main impact of a -25% United Kingdom housing shock on France would be a moderate drop in GDP of 0.10% by Q14. Equities peak at -0.21% in Q14.

Demand and trade. Consumption peaks at -0.06 % vs baseline in Q15, from +0.00 in Q1 to -0.05 in Q20. Investment peaks at -0.28 % vs baseline in Q14, from +0.00 in Q1 to -0.26 in Q20. Net Exports peaks at +0.01 % vs baseline in Q11, from -0.00 in Q1 to +0.01 in Q20. Gov Spending peaks at +0.02 % vs baseline in Q14, from +0.00 in Q1 to +0.02 in Q20. Gov Debt peaks at +0.08 % vs baseline in Q20, from +0.00 in Q1 to +0.08 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Currency Strength peaks at -0.06 % vs baseline in Q20, from -0.00 in Q1 to -0.06 in Q20.

Labour. Employment peaks at -0.10 % vs baseline in Q20, from +0.00 in Q1 to -0.10 in Q20. Unemployment peaks at +0.07 pp in Q20, from +0.00 in Q1 to +0.07 in Q20. Real Wages peaks at -0.08 % vs baseline in Q20, from +0.00 in Q1 to -0.08 in Q20.

Prices. The three-year CPI impulse is -0.04 percentage points. CPI Inflation peaks at -0.01 pp in Q13, from -0.00 in Q1 to -0.01 in Q20. Domestic Infl. peaks at -0.00 pp in Q13, from -0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.06 % vs baseline in Q14, from +0.00 in Q1 to -0.06 in Q20.

Financial conditions. Policy Rate peaks at +0.00 pp (annualized) in Q1, from +0.00 in Q1 to +0.00 in Q20. Govt 2Y Yield peaks at +0.00 pp (annualized) in Q1, from +0.00 in Q1 to +0.00 in Q20. Govt 5Y Yield peaks at +0.00 pp (annualized) in Q1, from +0.00 in Q1 to +0.00 in Q20. Govt 10Y Yield peaks at +0.00 pp (annualized) in Q1, from +0.00 in Q1 to +0.00 in Q20. Bond Price peaks at +0.08 % vs baseline in Q19, from -0.00 in Q1 to +0.08 in Q20. Equity Index peaks at -0.21 % vs baseline in Q14, from +0.00 in Q1 to -0.19 in Q20. Tobin's Q peaks at -0.20 % vs baseline in Q14, from +0.00 in Q1 to -0.18 in Q20. House Prices peaks at -0.12 % vs baseline in Q20, from +0.00 in Q1 to -0.12 in Q20. Bank Credit peaks at -0.25 % vs baseline in Q20, from +0.00 in Q1 to -0.25 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.01 % vs baseline in Q8, from +0.00 in Q1 to +0.01 in Q20. Services GDP peaks at -0.08 % vs baseline in Q14, from +0.00 in Q1 to -0.07 in Q20. Capital Stock peaks at -0.02 % vs baseline in Q20, from +0.00 in Q1 to -0.02 in Q20.

Timing. By Q20 GDP is still -0.10% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/FR_Y.png)

![CPI Inflation](charts/FR_pi_cpi.png)

![Equity Index](charts/FR_equity.png)

![Investment](charts/FR_I.png)

![Bank Credit](charts/FR_credit_supply.png)

![Tobin's Q](charts/FR_Q.png)

![House Prices](charts/FR_P_H.png)

![Employment](charts/FR_N.png)

![Gov Debt](charts/FR_B.png)

![Real Wages](charts/FR_w.png)

![Bond Price](charts/FR_Q_B.png)

![Services GDP](charts/FR_gdp_services.png)

[Q1–Q20 JSON for France](numbers/FR.json)

## US — United States

The main impact of a -25% United Kingdom housing shock on the United States would be only a small drop in GDP of 0.09% by Q12. Equities peak at -0.25% in Q11.

Demand and trade. Consumption peaks at -0.06 % vs baseline in Q13, from +0.00 in Q1 to -0.04 in Q20. Investment peaks at -0.17 % vs baseline in Q10, from -0.00 in Q1 to -0.05 in Q20. Net Exports peaks at +0.00 % vs baseline in Q13, from +0.00 in Q1 to +0.00 in Q20. Gov Spending peaks at +0.02 % vs baseline in Q12, from +0.00 in Q1 to +0.01 in Q20. Gov Debt peaks at -0.02 % vs baseline in Q14, from +0.00 in Q1 to -0.01 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Currency Strength peaks at +0.07 % vs baseline in Q14, from +0.01 in Q1 to +0.04 in Q20.

Labour. Employment peaks at -0.10 % vs baseline in Q15, from +0.00 in Q1 to -0.08 in Q20. Unemployment peaks at +0.06 pp in Q16, from +0.00 in Q1 to +0.05 in Q20. Real Wages peaks at -0.10 % vs baseline in Q20, from +0.00 in Q1 to -0.10 in Q20.

Prices. The three-year CPI impulse is -0.04 percentage points. CPI Inflation peaks at -0.01 pp in Q14, from +0.00 in Q1 to -0.01 in Q20. Domestic Infl. peaks at -0.00 pp in Q14, from +0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.05 % vs baseline in Q12, from +0.00 in Q1 to -0.03 in Q20.

Financial conditions. Policy Rate peaks at -0.07 pp (annualized) in Q17, from +0.00 in Q1 to -0.07 in Q20. Govt 2Y Yield peaks at -0.07 pp (annualized) in Q14, from -0.01 in Q1 to -0.06 in Q20. Govt 5Y Yield peaks at -0.06 pp (annualized) in Q10, from -0.04 in Q1 to -0.04 in Q20. Govt 10Y Yield peaks at -0.04 pp (annualized) in Q8, from -0.04 in Q1 to -0.04 in Q20. Bond Price peaks at +0.45 % vs baseline in Q17, from -0.00 in Q1 to +0.43 in Q20. Equity Index peaks at -0.25 % vs baseline in Q11, from +0.00 in Q1 to -0.14 in Q20. Tobin's Q peaks at -0.12 % vs baseline in Q10, from -0.00 in Q1 to -0.04 in Q20. House Prices peaks at -0.07 % vs baseline in Q20, from +0.00 in Q1 to -0.07 in Q20. Bank Credit peaks at -0.28 % vs baseline in Q20, from +0.00 in Q1 to -0.28 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.03 % vs baseline in Q14, from -0.00 in Q1 to -0.02 in Q20. Services GDP peaks at -0.07 % vs baseline in Q12, from +0.00 in Q1 to -0.04 in Q20. Capital Stock peaks at -0.01 % vs baseline in Q20, from +0.00 in Q1 to -0.01 in Q20.

Timing. By Q20 GDP is still -0.06% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/US_Y.png)

![CPI Inflation](charts/US_pi_cpi.png)

![Equity Index](charts/US_equity.png)

![Bond Price](charts/US_Q_B.png)

![Bank Credit](charts/US_credit_supply.png)

![Investment](charts/US_I.png)

![Tobin's Q](charts/US_Q.png)

![Real Wages](charts/US_w.png)

![Employment](charts/US_N.png)

![Currency Strength](charts/US_RER.png)

![House Prices](charts/US_P_H.png)

![Policy Rate](charts/US_i.png)

[Q1–Q20 JSON for United States](numbers/US.json)

## NO — Norway

The main impact of a -25% United Kingdom housing shock on Norway would be only a small drop in GDP of 0.07% by Q16. Equities peak at -0.14% in Q15.

Demand and trade. Consumption peaks at -0.04 % vs baseline in Q17, from +0.00 in Q1 to -0.04 in Q20. Investment peaks at -0.15 % vs baseline in Q12, from -0.00 in Q1 to -0.13 in Q20. Net Exports peaks at -0.04 % vs baseline in Q20, from +0.00 in Q1 to -0.04 in Q20. Gov Spending peaks at -0.01 % vs baseline in Q20, from +0.00 in Q1 to -0.01 in Q20. Gov Debt peaks at +0.02 % vs baseline in Q20, from +0.00 in Q1 to +0.02 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Currency Strength peaks at +0.16 % vs baseline in Q20, from +0.00 in Q1 to +0.16 in Q20.

Labour. Employment peaks at -0.08 % vs baseline in Q20, from +0.00 in Q1 to -0.08 in Q20. Unemployment peaks at +0.05 pp in Q20, from +0.00 in Q1 to +0.05 in Q20. Real Wages peaks at -0.07 % vs baseline in Q20, from +0.00 in Q1 to -0.07 in Q20.

Prices. The three-year CPI impulse is -0.01 percentage points. CPI Inflation peaks at -0.00 pp in Q20, from +0.00 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q20, from +0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.04 % vs baseline in Q16, from +0.00 in Q1 to -0.04 in Q20.

Financial conditions. Policy Rate peaks at -0.05 pp (annualized) in Q20, from +0.00 in Q1 to -0.05 in Q20. Govt 2Y Yield peaks at -0.05 pp (annualized) in Q20, from -0.01 in Q1 to -0.05 in Q20. Govt 5Y Yield peaks at -0.05 pp (annualized) in Q20, from -0.03 in Q1 to -0.05 in Q20. Govt 10Y Yield peaks at -0.05 pp (annualized) in Q20, from -0.04 in Q1 to -0.05 in Q20. Bond Price peaks at +0.30 % vs baseline in Q20, from -0.00 in Q1 to +0.30 in Q20. Equity Index peaks at -0.14 % vs baseline in Q15, from +0.00 in Q1 to -0.13 in Q20. Tobin's Q peaks at -0.11 % vs baseline in Q12, from -0.00 in Q1 to -0.09 in Q20. House Prices peaks at -0.08 % vs baseline in Q20, from +0.00 in Q1 to -0.08 in Q20. Bank Credit peaks at -0.13 % vs baseline in Q20, from +0.00 in Q1 to -0.13 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.06 % vs baseline in Q19, from -0.00 in Q1 to -0.06 in Q20. Services GDP peaks at -0.04 % vs baseline in Q16, from +0.00 in Q1 to -0.04 in Q20. Capital Stock peaks at -0.01 % vs baseline in Q20, from +0.00 in Q1 to -0.01 in Q20.

Timing. By Q20 GDP is still -0.07% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/NO_Y.png)

![CPI Inflation](charts/NO_pi_cpi.png)

![Equity Index](charts/NO_equity.png)

![Bond Price](charts/NO_Q_B.png)

![Currency Strength](charts/NO_RER.png)

![Investment](charts/NO_I.png)

![Bank Credit](charts/NO_credit_supply.png)

![Tobin's Q](charts/NO_Q.png)

![House Prices](charts/NO_P_H.png)

![Employment](charts/NO_N.png)

![Real Wages](charts/NO_w.png)

![Manuf. GDP](charts/NO_gdp_manufacturing.png)

[Q1–Q20 JSON for Norway](numbers/NO.json)

## SE — Sweden

The main impact of a -25% United Kingdom housing shock on Sweden would be only a small drop in GDP of 0.07% by Q20. Equities peak at -0.19% in Q20.

Demand and trade. Consumption peaks at -0.04 % vs baseline in Q20, from +0.00 in Q1 to -0.04 in Q20. Investment peaks at -0.17 % vs baseline in Q15, from +0.00 in Q1 to -0.17 in Q20. Net Exports peaks at +0.01 % vs baseline in Q10, from -0.00 in Q1 to +0.00 in Q20. Gov Spending peaks at +0.01 % vs baseline in Q20, from +0.00 in Q1 to +0.01 in Q20. Gov Debt peaks at +0.04 % vs baseline in Q20, from +0.00 in Q1 to +0.04 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Currency Strength peaks at -0.04 % vs baseline in Q20, from -0.00 in Q1 to -0.04 in Q20.

Labour. Employment peaks at -0.07 % vs baseline in Q20, from +0.00 in Q1 to -0.07 in Q20. Unemployment peaks at +0.05 pp in Q20, from +0.00 in Q1 to +0.05 in Q20. Real Wages peaks at -0.08 % vs baseline in Q20, from +0.00 in Q1 to -0.08 in Q20.

Prices. The three-year CPI impulse is -0.03 percentage points. CPI Inflation peaks at -0.01 pp in Q20, from -0.00 in Q1 to -0.01 in Q20. Domestic Infl. peaks at -0.00 pp in Q20, from -0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.04 % vs baseline in Q20, from +0.00 in Q1 to -0.04 in Q20.

Financial conditions. Policy Rate peaks at -0.02 pp (annualized) in Q20, from +0.00 in Q1 to -0.02 in Q20. Govt 2Y Yield peaks at -0.03 pp (annualized) in Q20, from -0.00 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at -0.03 pp (annualized) in Q20, from -0.01 in Q1 to -0.03 in Q20. Govt 10Y Yield peaks at -0.03 pp (annualized) in Q20, from -0.02 in Q1 to -0.03 in Q20. Bond Price peaks at +0.15 % vs baseline in Q20, from +0.00 in Q1 to +0.15 in Q20. Equity Index peaks at -0.19 % vs baseline in Q20, from +0.00 in Q1 to -0.19 in Q20. Tobin's Q peaks at -0.12 % vs baseline in Q15, from +0.00 in Q1 to -0.12 in Q20. House Prices peaks at -0.08 % vs baseline in Q20, from +0.00 in Q1 to -0.08 in Q20. Bank Credit peaks at -0.13 % vs baseline in Q20, from +0.00 in Q1 to -0.13 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.01 % vs baseline in Q9, from +0.00 in Q1 to +0.00 in Q20. Services GDP peaks at -0.05 % vs baseline in Q20, from +0.00 in Q1 to -0.05 in Q20. Capital Stock peaks at -0.01 % vs baseline in Q20, from +0.00 in Q1 to -0.01 in Q20.

Timing. By Q20 GDP is still -0.07% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/SE_Y.png)

![CPI Inflation](charts/SE_pi_cpi.png)

![Equity Index](charts/SE_equity.png)

![Investment](charts/SE_I.png)

![Bond Price](charts/SE_Q_B.png)

![Bank Credit](charts/SE_credit_supply.png)

![Tobin's Q](charts/SE_Q.png)

![Real Wages](charts/SE_w.png)

![House Prices](charts/SE_P_H.png)

![Employment](charts/SE_N.png)

![Unemployment](charts/SE_unemployment.png)

![Services GDP](charts/SE_gdp_services.png)

[Q1–Q20 JSON for Sweden](numbers/SE.json)

## ES — Spain

The main impact of a -25% United Kingdom housing shock on Spain would be only a small drop in GDP of 0.07% by Q14. Equities peak at -0.11% in Q13.

Demand and trade. Consumption peaks at -0.04 % vs baseline in Q15, from +0.00 in Q1 to -0.04 in Q20. Investment peaks at -0.19 % vs baseline in Q14, from +0.00 in Q1 to -0.17 in Q20. Net Exports peaks at +0.01 % vs baseline in Q12, from -0.00 in Q1 to +0.01 in Q20. Gov Spending peaks at +0.01 % vs baseline in Q14, from +0.00 in Q1 to +0.01 in Q20. Gov Debt peaks at +0.01 % vs baseline in Q20, from +0.00 in Q1 to +0.01 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Currency Strength peaks at -0.06 % vs baseline in Q20, from -0.00 in Q1 to -0.06 in Q20.

Labour. Employment peaks at -0.07 % vs baseline in Q20, from +0.00 in Q1 to -0.07 in Q20. Unemployment peaks at +0.03 pp in Q20, from +0.00 in Q1 to +0.03 in Q20. Real Wages peaks at -0.06 % vs baseline in Q20, from +0.00 in Q1 to -0.06 in Q20.

Prices. The three-year CPI impulse is -0.03 percentage points. CPI Inflation peaks at -0.01 pp in Q12, from -0.00 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q12, from -0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.04 % vs baseline in Q14, from +0.00 in Q1 to -0.04 in Q20.

Financial conditions. Policy Rate peaks at +0.00 pp (annualized) in Q1, from +0.00 in Q1 to +0.00 in Q20. Govt 2Y Yield peaks at +0.00 pp (annualized) in Q1, from +0.00 in Q1 to +0.00 in Q20. Govt 5Y Yield peaks at +0.00 pp (annualized) in Q1, from +0.00 in Q1 to +0.00 in Q20. Govt 10Y Yield peaks at +0.00 pp (annualized) in Q1, from +0.00 in Q1 to +0.00 in Q20. Bond Price peaks at +0.08 % vs baseline in Q19, from -0.00 in Q1 to +0.08 in Q20. Equity Index peaks at -0.11 % vs baseline in Q13, from +0.00 in Q1 to -0.10 in Q20. Tobin's Q peaks at -0.13 % vs baseline in Q14, from +0.00 in Q1 to -0.12 in Q20. House Prices peaks at -0.08 % vs baseline in Q20, from +0.00 in Q1 to -0.08 in Q20. Bank Credit peaks at -0.17 % vs baseline in Q20, from +0.00 in Q1 to -0.17 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.01 % vs baseline in Q20, from +0.00 in Q1 to +0.01 in Q20. Services GDP peaks at -0.05 % vs baseline in Q14, from +0.00 in Q1 to -0.05 in Q20. Capital Stock peaks at -0.01 % vs baseline in Q20, from +0.00 in Q1 to -0.01 in Q20.

Timing. By Q20 GDP is still -0.06% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/ES_Y.png)

![CPI Inflation](charts/ES_pi_cpi.png)

![Equity Index](charts/ES_equity.png)

![Investment](charts/ES_I.png)

![Bank Credit](charts/ES_credit_supply.png)

![Tobin's Q](charts/ES_Q.png)

![Bond Price](charts/ES_Q_B.png)

![House Prices](charts/ES_P_H.png)

![Employment](charts/ES_N.png)

![Real Wages](charts/ES_w.png)

![Currency Strength](charts/ES_RER.png)

![Services GDP](charts/ES_gdp_services.png)

[Q1–Q20 JSON for Spain](numbers/ES.json)

## AU — Australia

The main impact of a -25% United Kingdom housing shock on Australia would be only a small drop in GDP of 0.06% by Q13. Equities peak at -0.14% in Q12.

Demand and trade. Consumption peaks at -0.04 % vs baseline in Q14, from +0.00 in Q1 to -0.04 in Q20. Investment peaks at -0.13 % vs baseline in Q11, from -0.00 in Q1 to -0.08 in Q20. Net Exports peaks at -0.01 % vs baseline in Q20, from +0.00 in Q1 to -0.01 in Q20. Gov Spending peaks at +0.01 % vs baseline in Q13, from +0.00 in Q1 to +0.01 in Q20. Gov Debt peaks at -0.04 % vs baseline in Q20, from +0.00 in Q1 to -0.04 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Currency Strength peaks at +0.14 % vs baseline in Q16, from +0.00 in Q1 to +0.13 in Q20.

Labour. Employment peaks at -0.07 % vs baseline in Q17, from +0.00 in Q1 to -0.07 in Q20. Unemployment peaks at +0.04 pp in Q18, from +0.00 in Q1 to +0.04 in Q20. Real Wages peaks at -0.08 % vs baseline in Q20, from +0.00 in Q1 to -0.08 in Q20.

Prices. The three-year CPI impulse is -0.02 percentage points. CPI Inflation peaks at -0.00 pp in Q12, from +0.00 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q12, from +0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.04 % vs baseline in Q13, from +0.00 in Q1 to -0.03 in Q20.

Financial conditions. Policy Rate peaks at -0.04 pp (annualized) in Q20, from +0.00 in Q1 to -0.04 in Q20. Govt 2Y Yield peaks at -0.04 pp (annualized) in Q18, from -0.01 in Q1 to -0.04 in Q20. Govt 5Y Yield peaks at -0.04 pp (annualized) in Q14, from -0.02 in Q1 to -0.04 in Q20. Govt 10Y Yield peaks at -0.04 pp (annualized) in Q13, from -0.03 in Q1 to -0.04 in Q20. Bond Price peaks at +0.28 % vs baseline in Q20, from -0.00 in Q1 to +0.28 in Q20. Equity Index peaks at -0.14 % vs baseline in Q12, from +0.00 in Q1 to -0.11 in Q20. Tobin's Q peaks at -0.09 % vs baseline in Q11, from -0.00 in Q1 to -0.06 in Q20. House Prices peaks at -0.06 % vs baseline in Q20, from +0.00 in Q1 to -0.06 in Q20. Bank Credit peaks at -0.17 % vs baseline in Q20, from +0.00 in Q1 to -0.17 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.05 % vs baseline in Q15, from -0.00 in Q1 to -0.04 in Q20. Services GDP peaks at -0.05 % vs baseline in Q13, from +0.00 in Q1 to -0.04 in Q20. Capital Stock peaks at -0.01 % vs baseline in Q20, from +0.00 in Q1 to -0.01 in Q20.

Timing. By Q20 GDP is still -0.05% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/AU_Y.png)

![CPI Inflation](charts/AU_pi_cpi.png)

![Equity Index](charts/AU_equity.png)

![Bond Price](charts/AU_Q_B.png)

![Bank Credit](charts/AU_credit_supply.png)

![Currency Strength](charts/AU_RER.png)

![Investment](charts/AU_I.png)

![Tobin's Q](charts/AU_Q.png)

![Real Wages](charts/AU_w.png)

![Employment](charts/AU_N.png)

![House Prices](charts/AU_P_H.png)

![Manuf. GDP](charts/AU_gdp_manufacturing.png)

[Q1–Q20 JSON for Australia](numbers/AU.json)

## CA — Canada

The main impact of a -25% United Kingdom housing shock on Canada would be only a small drop in GDP of 0.06% by Q12. Equities peak at -0.13% in Q12.

Demand and trade. Consumption peaks at -0.04 % vs baseline in Q13, from +0.00 in Q1 to -0.03 in Q20. Investment peaks at -0.11 % vs baseline in Q10, from +0.00 in Q1 to -0.06 in Q20. Net Exports peaks at -0.03 % vs baseline in Q20, from -0.00 in Q1 to -0.03 in Q20. Gov Spending peaks at +0.01 % vs baseline in Q11, from +0.00 in Q1 to +0.00 in Q20. Gov Debt peaks at -0.01 % vs baseline in Q20, from +0.00 in Q1 to -0.01 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Currency Strength peaks at +0.10 % vs baseline in Q20, from -0.00 in Q1 to +0.10 in Q20.

Labour. Employment peaks at -0.06 % vs baseline in Q16, from +0.00 in Q1 to -0.06 in Q20. Unemployment peaks at +0.04 pp in Q17, from +0.00 in Q1 to +0.04 in Q20. Real Wages peaks at -0.07 % vs baseline in Q20, from +0.00 in Q1 to -0.07 in Q20.

Prices. The three-year CPI impulse is -0.03 percentage points. CPI Inflation peaks at -0.00 pp in Q11, from -0.00 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q11, from -0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.04 % vs baseline in Q12, from +0.00 in Q1 to -0.03 in Q20.

Financial conditions. Policy Rate peaks at -0.04 pp (annualized) in Q17, from -0.00 in Q1 to -0.04 in Q20. Govt 2Y Yield peaks at -0.04 pp (annualized) in Q14, from -0.01 in Q1 to -0.04 in Q20. Govt 5Y Yield peaks at -0.04 pp (annualized) in Q10, from -0.03 in Q1 to -0.03 in Q20. Govt 10Y Yield peaks at -0.03 pp (annualized) in Q9, from -0.03 in Q1 to -0.03 in Q20. Bond Price peaks at +0.27 % vs baseline in Q17, from +0.00 in Q1 to +0.25 in Q20. Equity Index peaks at -0.13 % vs baseline in Q12, from +0.00 in Q1 to -0.09 in Q20. Tobin's Q peaks at -0.08 % vs baseline in Q10, from +0.00 in Q1 to -0.04 in Q20. House Prices peaks at -0.06 % vs baseline in Q20, from +0.00 in Q1 to -0.06 in Q20. Bank Credit peaks at -0.13 % vs baseline in Q20, from +0.00 in Q1 to -0.13 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.04 % vs baseline in Q14, from +0.00 in Q1 to -0.03 in Q20. Services GDP peaks at -0.04 % vs baseline in Q12, from +0.00 in Q1 to -0.03 in Q20. Capital Stock peaks at -0.01 % vs baseline in Q20, from +0.00 in Q1 to -0.01 in Q20.

Timing. By Q20 GDP is still -0.04% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/CA_Y.png)

![CPI Inflation](charts/CA_pi_cpi.png)

![Equity Index](charts/CA_equity.png)

![Bond Price](charts/CA_Q_B.png)

![Bank Credit](charts/CA_credit_supply.png)

![Investment](charts/CA_I.png)

![Currency Strength](charts/CA_RER.png)

![Tobin's Q](charts/CA_Q.png)

![Real Wages](charts/CA_w.png)

![Employment](charts/CA_N.png)

![House Prices](charts/CA_P_H.png)

![Policy Rate](charts/CA_i.png)

[Q1–Q20 JSON for Canada](numbers/CA.json)

## JP — Japan

The main impact of a -25% United Kingdom housing shock on Japan would be only a small drop in GDP of 0.06% by Q13. Equities peak at -0.15% in Q13.

Demand and trade. Consumption peaks at -0.04 % vs baseline in Q14, from +0.00 in Q1 to -0.03 in Q20. Investment peaks at -0.15 % vs baseline in Q12, from +0.00 in Q1 to -0.12 in Q20. Net Exports peaks at +0.01 % vs baseline in Q12, from -0.00 in Q1 to +0.01 in Q20. Gov Spending peaks at +0.01 % vs baseline in Q13, from +0.00 in Q1 to +0.01 in Q20. Gov Debt peaks at -0.02 % vs baseline in Q20, from +0.00 in Q1 to -0.02 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Currency Strength peaks at -0.24 % vs baseline in Q20, from -0.01 in Q1 to -0.24 in Q20.

Labour. Employment peaks at -0.06 % vs baseline in Q18, from +0.00 in Q1 to -0.06 in Q20. Unemployment peaks at +0.04 pp in Q18, from +0.00 in Q1 to +0.04 in Q20. Real Wages peaks at -0.05 % vs baseline in Q20, from +0.00 in Q1 to -0.05 in Q20.

Prices. The three-year CPI impulse is -0.06 percentage points. CPI Inflation peaks at -0.01 pp in Q9, from -0.00 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q9, from -0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.03 % vs baseline in Q13, from +0.00 in Q1 to -0.03 in Q20.

Financial conditions. Policy Rate peaks at -0.01 pp (annualized) in Q20, from +0.00 in Q1 to -0.01 in Q20. Govt 2Y Yield peaks at -0.01 pp (annualized) in Q20, from -0.00 in Q1 to -0.01 in Q20. Govt 5Y Yield peaks at -0.01 pp (annualized) in Q16, from -0.00 in Q1 to -0.01 in Q20. Govt 10Y Yield peaks at -0.01 pp (annualized) in Q13, from -0.01 in Q1 to -0.01 in Q20. Bond Price peaks at +0.10 % vs baseline in Q19, from +0.00 in Q1 to +0.10 in Q20. Equity Index peaks at -0.15 % vs baseline in Q13, from +0.00 in Q1 to -0.12 in Q20. Tobin's Q peaks at -0.11 % vs baseline in Q12, from +0.00 in Q1 to -0.08 in Q20. House Prices peaks at -0.06 % vs baseline in Q20, from +0.00 in Q1 to -0.06 in Q20. Bank Credit peaks at -0.18 % vs baseline in Q20, from +0.00 in Q1 to -0.18 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.07 % vs baseline in Q20, from +0.00 in Q1 to +0.07 in Q20. Services GDP peaks at -0.04 % vs baseline in Q13, from +0.00 in Q1 to -0.03 in Q20. Capital Stock peaks at -0.01 % vs baseline in Q20, from +0.00 in Q1 to -0.01 in Q20.

Timing. By Q20 GDP is still -0.05% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/JP_Y.png)

![CPI Inflation](charts/JP_pi_cpi.png)

![Equity Index](charts/JP_equity.png)

![Currency Strength](charts/JP_RER.png)

![Bank Credit](charts/JP_credit_supply.png)

![Investment](charts/JP_I.png)

![Tobin's Q](charts/JP_Q.png)

![Bond Price](charts/JP_Q_B.png)

![Manuf. GDP](charts/JP_gdp_manufacturing.png)

![Employment](charts/JP_N.png)

![House Prices](charts/JP_P_H.png)

![Real Wages](charts/JP_w.png)

[Q1–Q20 JSON for Japan](numbers/JP.json)

## SA — Saudi Arabia

The main impact of a -25% United Kingdom housing shock on Saudi Arabia would be only a small drop in GDP of 0.04% by Q13. Equities peak at -0.16% in Q12.

Demand and trade. Consumption peaks at -0.03 % vs baseline in Q14, from +0.00 in Q1 to -0.03 in Q20. Investment peaks at -0.06 % vs baseline in Q8, from -0.00 in Q1 to -0.00 in Q20. Net Exports peaks at -0.07 % vs baseline in Q20, from +0.00 in Q1 to -0.07 in Q20. Gov Spending peaks at -0.03 % vs baseline in Q20, from +0.00 in Q1 to -0.03 in Q20. Gov Debt peaks at -0.09 % vs baseline in Q20, from +0.00 in Q1 to -0.09 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Currency Strength peaks at +0.06 % vs baseline in Q20, from +0.00 in Q1 to +0.06 in Q20.

Labour. Employment peaks at -0.05 % vs baseline in Q18, from +0.00 in Q1 to -0.05 in Q20. Unemployment peaks at +0.02 pp in Q17, from +0.00 in Q1 to +0.02 in Q20. Real Wages peaks at -0.05 % vs baseline in Q20, from +0.00 in Q1 to -0.05 in Q20.

Prices. The three-year CPI impulse is -0.02 percentage points. CPI Inflation peaks at -0.00 pp in Q9, from +0.00 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q9, from +0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.03 % vs baseline in Q13, from +0.00 in Q1 to -0.02 in Q20.

Financial conditions. Policy Rate peaks at -0.07 pp (annualized) in Q17, from +0.00 in Q1 to -0.07 in Q20. Govt 2Y Yield peaks at -0.07 pp (annualized) in Q14, from -0.01 in Q1 to -0.06 in Q20. Govt 5Y Yield peaks at -0.06 pp (annualized) in Q10, from -0.04 in Q1 to -0.04 in Q20. Govt 10Y Yield peaks at -0.04 pp (annualized) in Q8, from -0.04 in Q1 to -0.04 in Q20. Bond Price peaks at +0.34 % vs baseline in Q17, from -0.00 in Q1 to +0.33 in Q20. Equity Index peaks at -0.16 % vs baseline in Q12, from +0.00 in Q1 to -0.13 in Q20. Tobin's Q peaks at -0.04 % vs baseline in Q8, from -0.00 in Q1 to -0.00 in Q20. House Prices peaks at -0.05 % vs baseline in Q20, from +0.00 in Q1 to -0.05 in Q20. Bank Credit peaks at -0.07 % vs baseline in Q20, from +0.00 in Q1 to -0.07 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.02 % vs baseline in Q20, from +0.00 in Q1 to -0.02 in Q20. Services GDP peaks at -0.02 % vs baseline in Q13, from +0.00 in Q1 to -0.02 in Q20. Capital Stock peaks at -0.00 % vs baseline in Q20, from +0.00 in Q1 to -0.00 in Q20.

Timing. By Q20 GDP is still -0.04% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/SA_Y.png)

![CPI Inflation](charts/SA_pi_cpi.png)

![Equity Index](charts/SA_equity.png)

![Bond Price](charts/SA_Q_B.png)

![Gov Debt](charts/SA_B.png)

![Net Exports](charts/SA_NX.png)

![Bank Credit](charts/SA_credit_supply.png)

![Policy Rate](charts/SA_i.png)

![Govt 2Y Yield](charts/SA_y2.png)

![Govt 5Y Yield](charts/SA_y5.png)

![Currency Strength](charts/SA_RER.png)

![Investment](charts/SA_I.png)

[Q1–Q20 JSON for Saudi Arabia](numbers/SA.json)

## AR — Argentina

The main impact of a -25% United Kingdom housing shock on Argentina would be only a small rise in GDP of 0.04% by Q20. Equities peak at +0.12% in Q20.

Demand and trade. Consumption peaks at +0.02 % vs baseline in Q20, from +0.00 in Q1 to +0.02 in Q20. Investment peaks at +0.11 % vs baseline in Q20, from -0.00 in Q1 to +0.11 in Q20. Net Exports peaks at -0.03 % vs baseline in Q20, from +0.00 in Q1 to -0.03 in Q20. Gov Spending peaks at -0.01 % vs baseline in Q20, from +0.00 in Q1 to -0.01 in Q20. Gov Debt peaks at +0.01 % vs baseline in Q20, from +0.00 in Q1 to +0.01 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Currency Strength peaks at -0.05 % vs baseline in Q20, from +0.00 in Q1 to -0.05 in Q20.

Labour. Employment peaks at +0.02 % vs baseline in Q20, from +0.00 in Q1 to +0.02 in Q20. Unemployment peaks at -0.01 pp in Q20, from +0.00 in Q1 to -0.01 in Q20. Real Wages peaks at -0.02 % vs baseline in Q14, from +0.00 in Q1 to -0.00 in Q20.

Prices. The three-year CPI impulse is -0.03 percentage points. CPI Inflation peaks at -0.00 pp in Q9, from +0.00 in Q1 to +0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q9, from +0.00 in Q1 to +0.00 in Q20. Marginal Cost peaks at +0.03 % vs baseline in Q20, from +0.00 in Q1 to +0.03 in Q20.

Financial conditions. Policy Rate peaks at -0.02 pp (annualized) in Q10, from +0.00 in Q1 to +0.01 in Q20. Govt 2Y Yield peaks at -0.02 pp (annualized) in Q7, from -0.01 in Q1 to +0.02 in Q20. Govt 5Y Yield peaks at +0.02 pp (annualized) in Q20, from -0.01 in Q1 to +0.02 in Q20. Govt 10Y Yield peaks at +0.01 pp (annualized) in Q19, from +0.00 in Q1 to +0.01 in Q20. Bond Price peaks at +0.05 % vs baseline in Q10, from -0.00 in Q1 to -0.02 in Q20. Equity Index peaks at +0.12 % vs baseline in Q20, from -0.00 in Q1 to +0.12 in Q20. Tobin's Q peaks at +0.08 % vs baseline in Q20, from -0.00 in Q1 to +0.08 in Q20. House Prices peaks at +0.03 % vs baseline in Q20, from +0.00 in Q1 to +0.03 in Q20. Bank Credit peaks at -0.03 % vs baseline in Q20, from +0.00 in Q1 to -0.03 in Q20. Credit Spread peaks at +0.01 pp in Q20, from +0.00 in Q1 to +0.01 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.03 % vs baseline in Q20, from -0.00 in Q1 to +0.03 in Q20. Services GDP peaks at +0.02 % vs baseline in Q20, from +0.00 in Q1 to +0.02 in Q20. Capital Stock peaks at +0.00 % vs baseline in Q20, from +0.00 in Q1 to +0.00 in Q20.

Timing. By Q20 GDP is still +0.04% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/AR_Y.png)

![CPI Inflation](charts/AR_pi_cpi.png)

![Equity Index](charts/AR_equity.png)

![Investment](charts/AR_I.png)

![Tobin's Q](charts/AR_Q.png)

![Bond Price](charts/AR_Q_B.png)

![Currency Strength](charts/AR_RER.png)

![Bank Credit](charts/AR_credit_supply.png)

![Net Exports](charts/AR_NX.png)

![House Prices](charts/AR_P_H.png)

![Manuf. GDP](charts/AR_gdp_manufacturing.png)

![Marginal Cost](charts/AR_mc.png)

[Q1–Q20 JSON for Argentina](numbers/AR.json)

## PL — Poland

The main impact of a -25% United Kingdom housing shock on Poland would be no material drop in GDP of 0.04% by Q13. Equities peak at -0.05% in Q10. This has almost no impact on Poland.

![GDP](charts/PL_Y.png)

![CPI Inflation](charts/PL_pi_cpi.png)

![Equity Index](charts/PL_equity.png)

![Investment](charts/PL_I.png)

![Bond Price](charts/PL_Q_B.png)

![Bank Credit](charts/PL_credit_supply.png)

![Tobin's Q](charts/PL_Q.png)

![Real Wages](charts/PL_w.png)

![House Prices](charts/PL_P_H.png)

![Employment](charts/PL_N.png)

![Services GDP](charts/PL_gdp_services.png)

![Marginal Cost](charts/PL_mc.png)

[Q1–Q20 JSON for Poland](numbers/PL.json)

## ZA — South Africa

The main impact of a -25% United Kingdom housing shock on South Africa would be only a small drop in GDP of 0.04% by Q11. Equities peak at -0.13% in Q11.

Demand and trade. Consumption peaks at -0.02 % vs baseline in Q12, from +0.00 in Q1 to -0.02 in Q20. Investment peaks at -0.09 % vs baseline in Q9, from +0.00 in Q1 to -0.04 in Q20. Net Exports peaks at +0.01 % vs baseline in Q20, from -0.00 in Q1 to +0.01 in Q20. Gov Spending peaks at +0.01 % vs baseline in Q11, from +0.00 in Q1 to +0.00 in Q20. Gov Debt peaks at -0.04 % vs baseline in Q20, from +0.00 in Q1 to -0.04 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Currency Strength peaks at +0.06 % vs baseline in Q20, from -0.00 in Q1 to +0.06 in Q20.

Labour. Employment peaks at -0.04 % vs baseline in Q16, from +0.00 in Q1 to -0.04 in Q20. Unemployment peaks at +0.01 pp in Q14, from +0.00 in Q1 to +0.01 in Q20. Real Wages peaks at -0.07 % vs baseline in Q20, from +0.00 in Q1 to -0.07 in Q20.

Prices. The three-year CPI impulse is -0.02 percentage points. CPI Inflation peaks at -0.00 pp in Q11, from -0.00 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q11, from -0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.02 % vs baseline in Q11, from +0.00 in Q1 to -0.01 in Q20.

Financial conditions. Policy Rate peaks at -0.02 pp (annualized) in Q14, from -0.00 in Q1 to -0.02 in Q20. Govt 2Y Yield peaks at -0.02 pp (annualized) in Q11, from -0.00 in Q1 to -0.01 in Q20. Govt 5Y Yield peaks at -0.02 pp (annualized) in Q8, from -0.01 in Q1 to -0.01 in Q20. Govt 10Y Yield peaks at -0.01 pp (annualized) in Q8, from -0.01 in Q1 to -0.01 in Q20. Bond Price peaks at +0.08 % vs baseline in Q14, from +0.00 in Q1 to +0.07 in Q20. Equity Index peaks at -0.13 % vs baseline in Q11, from +0.00 in Q1 to -0.06 in Q20. Tobin's Q peaks at -0.06 % vs baseline in Q9, from +0.00 in Q1 to -0.03 in Q20. House Prices peaks at -0.05 % vs baseline in Q20, from +0.00 in Q1 to -0.05 in Q20. Bank Credit peaks at -0.12 % vs baseline in Q20, from +0.00 in Q1 to -0.12 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.02 % vs baseline in Q12, from +0.00 in Q1 to -0.02 in Q20. Services GDP peaks at -0.03 % vs baseline in Q11, from +0.00 in Q1 to -0.02 in Q20. Capital Stock peaks at -0.01 % vs baseline in Q20, from +0.00 in Q1 to -0.01 in Q20.

Timing. By Q20 GDP is still -0.02% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/ZA_Y.png)

![CPI Inflation](charts/ZA_pi_cpi.png)

![Equity Index](charts/ZA_equity.png)

![Bank Credit](charts/ZA_credit_supply.png)

![Investment](charts/ZA_I.png)

![Bond Price](charts/ZA_Q_B.png)

![Real Wages](charts/ZA_w.png)

![Currency Strength](charts/ZA_RER.png)

![Tobin's Q](charts/ZA_Q.png)

![House Prices](charts/ZA_P_H.png)

![Employment](charts/ZA_N.png)

![Gov Debt](charts/ZA_B.png)

[Q1–Q20 JSON for South Africa](numbers/ZA.json)

## CN — China

The main impact of a -25% United Kingdom housing shock on China would be only a small drop in GDP of 0.04% by Q11. Equities peak at -0.06% in Q10.

Demand and trade. Consumption peaks at -0.03 % vs baseline in Q12, from +0.00 in Q1 to -0.01 in Q20. Investment peaks at -0.07 % vs baseline in Q9, from +0.00 in Q1 to +0.01 in Q20. Net Exports peaks at +0.02 % vs baseline in Q18, from -0.00 in Q1 to +0.02 in Q20. Gov Spending peaks at +0.01 % vs baseline in Q11, from +0.00 in Q1 to +0.00 in Q20. Gov Debt peaks at -0.05 % vs baseline in Q20, from +0.00 in Q1 to -0.05 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Currency Strength peaks at +0.01 % vs baseline in Q17, from -0.00 in Q1 to +0.01 in Q20.

Labour. Employment peaks at -0.03 % vs baseline in Q17, from +0.00 in Q1 to -0.03 in Q20. Unemployment peaks at +0.01 pp in Q14, from +0.00 in Q1 to +0.01 in Q20. Real Wages peaks at -0.07 % vs baseline in Q20, from +0.00 in Q1 to -0.07 in Q20.

Prices. The three-year CPI impulse is -0.04 percentage points. CPI Inflation peaks at -0.00 pp in Q11, from -0.00 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q11, from -0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.02 % vs baseline in Q11, from +0.00 in Q1 to -0.01 in Q20.

Financial conditions. Policy Rate peaks at -0.03 pp (annualized) in Q18, from +0.00 in Q1 to -0.03 in Q20. Govt 2Y Yield peaks at -0.03 pp (annualized) in Q15, from -0.00 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at -0.03 pp (annualized) in Q10, from -0.02 in Q1 to -0.02 in Q20. Govt 10Y Yield peaks at -0.02 pp (annualized) in Q6, from -0.02 in Q1 to -0.01 in Q20. Bond Price peaks at +0.17 % vs baseline in Q18, from +0.00 in Q1 to +0.16 in Q20. Equity Index peaks at -0.06 % vs baseline in Q10, from +0.00 in Q1 to -0.01 in Q20. Tobin's Q peaks at -0.05 % vs baseline in Q9, from +0.00 in Q1 to +0.00 in Q20. House Prices peaks at -0.03 % vs baseline in Q18, from +0.00 in Q1 to -0.03 in Q20. Bank Credit peaks at -0.06 % vs baseline in Q20, from +0.00 in Q1 to -0.06 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.01 % vs baseline in Q11, from +0.00 in Q1 to +0.00 in Q20. Services GDP peaks at -0.02 % vs baseline in Q11, from +0.00 in Q1 to -0.01 in Q20. Capital Stock peaks at -0.00 % vs baseline in Q19, from +0.00 in Q1 to -0.00 in Q20.

Timing. By Q20 GDP is still -0.02% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/CN_Y.png)

![CPI Inflation](charts/CN_pi_cpi.png)

![Equity Index](charts/CN_equity.png)

![Bond Price](charts/CN_Q_B.png)

![Investment](charts/CN_I.png)

![Real Wages](charts/CN_w.png)

![Bank Credit](charts/CN_credit_supply.png)

![Gov Debt](charts/CN_B.png)

![Tobin's Q](charts/CN_Q.png)

![House Prices](charts/CN_P_H.png)

![Policy Rate](charts/CN_i.png)

![Govt 2Y Yield](charts/CN_y2.png)

[Q1–Q20 JSON for China](numbers/CN.json)

## IT — Italy

The main impact of a -25% United Kingdom housing shock on Italy would be no material drop in GDP of 0.03% by Q13. Equities peak at -0.03% in Q10. This has almost no impact on Italy.

![GDP](charts/IT_Y.png)

![CPI Inflation](charts/IT_pi_cpi.png)

![Equity Index](charts/IT_equity.png)

![Currency Strength](charts/IT_RER.png)

![Bond Price](charts/IT_Q_B.png)

![Investment](charts/IT_I.png)

![Bank Credit](charts/IT_credit_supply.png)

![Tobin's Q](charts/IT_Q.png)

![Real Wages](charts/IT_w.png)

![House Prices](charts/IT_P_H.png)

![Employment](charts/IT_N.png)

![Manuf. GDP](charts/IT_gdp_manufacturing.png)

[Q1–Q20 JSON for Italy](numbers/IT.json)

## TR — Turkey

The main impact of a -25% United Kingdom housing shock on Turkey would be only a small drop in GDP of 0.03% by Q10. Equities peak at +0.05% in Q20.

Demand and trade. Consumption peaks at -0.02 % vs baseline in Q10, from +0.00 in Q1 to -0.00 in Q20. Investment peaks at -0.05 % vs baseline in Q8, from -0.00 in Q1 to +0.03 in Q20. Net Exports peaks at +0.02 % vs baseline in Q13, from +0.00 in Q1 to +0.02 in Q20. Gov Spending peaks at +0.00 % vs baseline in Q10, from +0.00 in Q1 to -0.00 in Q20. Gov Debt peaks at -0.02 % vs baseline in Q18, from +0.00 in Q1 to -0.02 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Currency Strength peaks at +0.03 % vs baseline in Q9, from +0.00 in Q1 to +0.01 in Q20.

Labour. Employment peaks at -0.02 % vs baseline in Q14, from +0.00 in Q1 to -0.02 in Q20. Unemployment peaks at +0.01 pp in Q12, from +0.00 in Q1 to +0.00 in Q20. Real Wages peaks at -0.05 % vs baseline in Q20, from +0.00 in Q1 to -0.05 in Q20.

Prices. The three-year CPI impulse is -0.02 percentage points. CPI Inflation peaks at -0.00 pp in Q12, from +0.00 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q12, from +0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.02 % vs baseline in Q10, from +0.00 in Q1 to +0.00 in Q20.

Financial conditions. Policy Rate peaks at -0.02 pp (annualized) in Q13, from +0.00 in Q1 to -0.01 in Q20. Govt 2Y Yield peaks at -0.02 pp (annualized) in Q10, from -0.00 in Q1 to -0.01 in Q20. Govt 5Y Yield peaks at -0.01 pp (annualized) in Q6, from -0.01 in Q1 to -0.00 in Q20. Govt 10Y Yield peaks at -0.01 pp (annualized) in Q6, from -0.01 in Q1 to -0.00 in Q20. Bond Price peaks at +0.07 % vs baseline in Q13, from -0.00 in Q1 to +0.04 in Q20. Equity Index peaks at +0.05 % vs baseline in Q20, from -0.00 in Q1 to +0.05 in Q20. Tobin's Q peaks at -0.04 % vs baseline in Q8, from -0.00 in Q1 to +0.02 in Q20. House Prices peaks at -0.02 % vs baseline in Q15, from +0.00 in Q1 to -0.02 in Q20. Bank Credit peaks at -0.06 % vs baseline in Q20, from +0.00 in Q1 to -0.06 in Q20. Credit Spread peaks at +0.01 pp in Q20, from +0.00 in Q1 to +0.01 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.01 % vs baseline in Q8, from -0.00 in Q1 to +0.00 in Q20. Services GDP peaks at -0.02 % vs baseline in Q10, from +0.00 in Q1 to +0.00 in Q20. Capital Stock peaks at -0.00 % vs baseline in Q15, from +0.00 in Q1 to -0.00 in Q20.

Timing. The GDP response has mostly faded by Q18 (Q20 is +0.00%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/TR_Y.png)

![CPI Inflation](charts/TR_pi_cpi.png)

![Equity Index](charts/TR_equity.png)

![Bond Price](charts/TR_Q_B.png)

![Bank Credit](charts/TR_credit_supply.png)

![Real Wages](charts/TR_w.png)

![Investment](charts/TR_I.png)

![Tobin's Q](charts/TR_Q.png)

![Currency Strength](charts/TR_RER.png)

![House Prices](charts/TR_P_H.png)

![Gov Debt](charts/TR_B.png)

![Employment](charts/TR_N.png)

[Q1–Q20 JSON for Turkey](numbers/TR.json)

## MY — Malaysia

The main impact of a -25% United Kingdom housing shock on Malaysia would be no material drop in GDP of 0.02% by Q12. Equities peak at -0.05% in Q10. This has almost no impact on Malaysia.

![GDP](charts/MY_Y.png)

![CPI Inflation](charts/MY_pi_cpi.png)

![Equity Index](charts/MY_equity.png)

![Bond Price](charts/MY_Q_B.png)

![Real Wages](charts/MY_w.png)

![Gov Debt](charts/MY_B.png)

![Investment](charts/MY_I.png)

![House Prices](charts/MY_P_H.png)

![Tobin's Q](charts/MY_Q.png)

![Employment](charts/MY_N.png)

![Bank Credit](charts/MY_credit_supply.png)

![Net Exports](charts/MY_NX.png)

[Q1–Q20 JSON for Malaysia](numbers/MY.json)

## IN — India

The main impact of a -25% United Kingdom housing shock on India would be only a small drop in GDP of 0.02% by Q9. Equities peak at +0.05% in Q20.

Demand and trade. Consumption peaks at -0.01 % vs baseline in Q10, from +0.00 in Q1 to +0.00 in Q20. Investment peaks at +0.05 % vs baseline in Q20, from -0.00 in Q1 to +0.05 in Q20. Net Exports peaks at +0.01 % vs baseline in Q12, from +0.00 in Q1 to +0.01 in Q20. Gov Spending peaks at +0.00 % vs baseline in Q9, from +0.00 in Q1 to -0.00 in Q20. Gov Debt peaks at -0.03 % vs baseline in Q17, from +0.00 in Q1 to -0.03 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Currency Strength peaks at -0.02 % vs baseline in Q20, from +0.00 in Q1 to -0.02 in Q20.

Labour. Employment peaks at -0.02 % vs baseline in Q15, from +0.00 in Q1 to -0.01 in Q20. Unemployment peaks at +0.00 pp in Q11, from +0.00 in Q1 to -0.00 in Q20. Real Wages peaks at -0.05 % vs baseline in Q20, from +0.00 in Q1 to -0.05 in Q20.

Prices. The three-year CPI impulse is -0.04 percentage points. CPI Inflation peaks at -0.01 pp in Q11, from +0.00 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q11, from +0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.01 % vs baseline in Q9, from +0.00 in Q1 to +0.00 in Q20.

Financial conditions. Policy Rate peaks at -0.03 pp (annualized) in Q13, from +0.00 in Q1 to -0.02 in Q20. Govt 2Y Yield peaks at -0.03 pp (annualized) in Q10, from -0.01 in Q1 to -0.01 in Q20. Govt 5Y Yield peaks at -0.02 pp (annualized) in Q6, from -0.02 in Q1 to -0.01 in Q20. Govt 10Y Yield peaks at -0.01 pp (annualized) in Q1, from -0.01 in Q1 to -0.00 in Q20. Bond Price peaks at +0.16 % vs baseline in Q13, from -0.00 in Q1 to +0.10 in Q20. Equity Index peaks at +0.05 % vs baseline in Q20, from +0.00 in Q1 to +0.05 in Q20. Tobin's Q peaks at +0.04 % vs baseline in Q20, from -0.00 in Q1 to +0.04 in Q20. House Prices peaks at -0.02 % vs baseline in Q14, from +0.00 in Q1 to -0.01 in Q20. Bank Credit peaks at -0.06 % vs baseline in Q20, from +0.00 in Q1 to -0.06 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.01 % vs baseline in Q20, from -0.00 in Q1 to +0.01 in Q20. Services GDP peaks at -0.01 % vs baseline in Q9, from +0.00 in Q1 to +0.00 in Q20. Capital Stock peaks at -0.00 % vs baseline in Q12, from +0.00 in Q1 to +0.00 in Q20.

Timing. The GDP response has mostly faded by Q17 (Q20 is +0.01%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/IN_Y.png)

![CPI Inflation](charts/IN_pi_cpi.png)

![Equity Index](charts/IN_equity.png)

![Bond Price](charts/IN_Q_B.png)

![Bank Credit](charts/IN_credit_supply.png)

![Investment](charts/IN_I.png)

![Real Wages](charts/IN_w.png)

![Tobin's Q](charts/IN_Q.png)

![Policy Rate](charts/IN_i.png)

![Govt 2Y Yield](charts/IN_y2.png)

![Gov Debt](charts/IN_B.png)

![Govt 5Y Yield](charts/IN_y5.png)

[Q1–Q20 JSON for India](numbers/IN.json)

## TH — Thailand

The main impact of a -25% United Kingdom housing shock on Thailand would be no material drop in GDP of 0.02% by Q12. Equities peak at -0.04% in Q9. This has almost no impact on Thailand.

![GDP](charts/TH_Y.png)

![CPI Inflation](charts/TH_pi_cpi.png)

![Equity Index](charts/TH_equity.png)

![Bond Price](charts/TH_Q_B.png)

![Real Wages](charts/TH_w.png)

![Investment](charts/TH_I.png)

![Gov Debt](charts/TH_B.png)

![House Prices](charts/TH_P_H.png)

![Tobin's Q](charts/TH_Q.png)

![Employment](charts/TH_N.png)

![Bank Credit](charts/TH_credit_supply.png)

![Currency Strength](charts/TH_RER.png)

[Q1–Q20 JSON for Thailand](numbers/TH.json)

## BR — Brazil

The main impact of a -25% United Kingdom housing shock on Brazil would be only a small drop in GDP of 0.02% by Q10. Equities peak at +0.05% in Q20.

Demand and trade. Consumption peaks at -0.01 % vs baseline in Q10, from +0.00 in Q1 to +0.00 in Q20. Investment peaks at +0.05 % vs baseline in Q20, from -0.00 in Q1 to +0.05 in Q20. Net Exports peaks at -0.03 % vs baseline in Q20, from +0.00 in Q1 to -0.03 in Q20. Gov Spending peaks at -0.01 % vs baseline in Q20, from +0.00 in Q1 to -0.01 in Q20. Gov Debt peaks at -0.00 % vs baseline in Q17, from +0.00 in Q1 to -0.00 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Currency Strength peaks at +0.07 % vs baseline in Q11, from +0.00 in Q1 to +0.04 in Q20.

Labour. Employment peaks at -0.02 % vs baseline in Q14, from +0.00 in Q1 to -0.01 in Q20. Unemployment peaks at +0.00 pp in Q12, from +0.00 in Q1 to +0.00 in Q20. Real Wages peaks at -0.04 % vs baseline in Q20, from +0.00 in Q1 to -0.04 in Q20.

Prices. The three-year CPI impulse is -0.03 percentage points. CPI Inflation peaks at -0.00 pp in Q11, from +0.00 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q11, from +0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.01 % vs baseline in Q10, from +0.00 in Q1 to +0.00 in Q20.

Financial conditions. Policy Rate peaks at -0.03 pp (annualized) in Q13, from +0.00 in Q1 to -0.02 in Q20. Govt 2Y Yield peaks at -0.03 pp (annualized) in Q10, from -0.01 in Q1 to -0.01 in Q20. Govt 5Y Yield peaks at -0.02 pp (annualized) in Q6, from -0.02 in Q1 to -0.01 in Q20. Govt 10Y Yield peaks at -0.01 pp (annualized) in Q1, from -0.01 in Q1 to -0.00 in Q20. Bond Price peaks at +0.12 % vs baseline in Q13, from -0.00 in Q1 to +0.08 in Q20. Equity Index peaks at +0.05 % vs baseline in Q20, from +0.00 in Q1 to +0.05 in Q20. Tobin's Q peaks at +0.03 % vs baseline in Q20, from -0.00 in Q1 to +0.03 in Q20. House Prices peaks at -0.02 % vs baseline in Q14, from +0.00 in Q1 to -0.01 in Q20. Bank Credit peaks at -0.06 % vs baseline in Q20, from +0.00 in Q1 to -0.06 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.02 % vs baseline in Q10, from -0.00 in Q1 to -0.01 in Q20. Services GDP peaks at -0.01 % vs baseline in Q10, from +0.00 in Q1 to +0.00 in Q20. Capital Stock peaks at -0.00 % vs baseline in Q13, from +0.00 in Q1 to -0.00 in Q20.

Timing. The GDP response has mostly faded by Q17 (Q20 is +0.01%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/BR_Y.png)

![CPI Inflation](charts/BR_pi_cpi.png)

![Equity Index](charts/BR_equity.png)

![Bond Price](charts/BR_Q_B.png)

![Currency Strength](charts/BR_RER.png)

![Bank Credit](charts/BR_credit_supply.png)

![Investment](charts/BR_I.png)

![Real Wages](charts/BR_w.png)

![Tobin's Q](charts/BR_Q.png)

![Policy Rate](charts/BR_i.png)

![Net Exports](charts/BR_NX.png)

![Govt 2Y Yield](charts/BR_y2.png)

[Q1–Q20 JSON for Brazil](numbers/BR.json)

## MX — Mexico

The main impact of a -25% United Kingdom housing shock on Mexico would be no material drop in GDP of 0.02% by Q10. Equities peak at +0.03% in Q20. This has almost no impact on Mexico.

![GDP](charts/MX_Y.png)

![CPI Inflation](charts/MX_pi_cpi.png)

![Equity Index](charts/MX_equity.png)

![Bond Price](charts/MX_Q_B.png)

![Real Wages](charts/MX_w.png)

![Investment](charts/MX_I.png)

![Currency Strength](charts/MX_RER.png)

![Bank Credit](charts/MX_credit_supply.png)

![Policy Rate](charts/MX_i.png)

![Govt 2Y Yield](charts/MX_y2.png)

![Gov Debt](charts/MX_B.png)

![Tobin's Q](charts/MX_Q.png)

[Q1–Q20 JSON for Mexico](numbers/MX.json)

## KR — South Korea

The main impact of a -25% United Kingdom housing shock on South Korea would be no material drop in GDP of 0.02% by Q10. Equities peak at -0.03% in Q8. This has almost no impact on South Korea.

![GDP](charts/KR_Y.png)

![CPI Inflation](charts/KR_pi_cpi.png)

![Equity Index](charts/KR_equity.png)

![Bond Price](charts/KR_Q_B.png)

![Currency Strength](charts/KR_RER.png)

![Real Wages](charts/KR_w.png)

![Manuf. GDP](charts/KR_gdp_manufacturing.png)

![Bank Credit](charts/KR_credit_supply.png)

![Investment](charts/KR_I.png)

![Policy Rate](charts/KR_i.png)

![Govt 2Y Yield](charts/KR_y2.png)

![Tobin's Q](charts/KR_Q.png)

[Q1–Q20 JSON for South Korea](numbers/KR.json)

## NG — Nigeria

The main impact of a -25% United Kingdom housing shock on Nigeria would be only a small drop in GDP of 0.02% by Q9. Equities peak at +0.06% in Q20.

Demand and trade. Consumption peaks at -0.01 % vs baseline in Q10, from -0.00 in Q1 to +0.01 in Q20. Investment peaks at +0.06 % vs baseline in Q20, from -0.00 in Q1 to +0.06 in Q20. Net Exports peaks at -0.03 % vs baseline in Q20, from +0.00 in Q1 to -0.03 in Q20. Gov Spending peaks at -0.01 % vs baseline in Q20, from +0.00 in Q1 to -0.01 in Q20. Gov Debt peaks at -0.04 % vs baseline in Q16, from +0.00 in Q1 to -0.03 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Currency Strength peaks at +0.03 % vs baseline in Q8, from +0.00 in Q1 to +0.00 in Q20.

Labour. Employment peaks at -0.01 % vs baseline in Q13, from +0.00 in Q1 to -0.00 in Q20. Unemployment peaks at +0.00 pp in Q10, from +0.00 in Q1 to -0.00 in Q20. Real Wages peaks at -0.05 % vs baseline in Q20, from +0.00 in Q1 to -0.05 in Q20.

Prices. The three-year CPI impulse is -0.05 percentage points. CPI Inflation peaks at -0.01 pp in Q10, from +0.00 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q10, from +0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.01 % vs baseline in Q9, from +0.00 in Q1 to +0.01 in Q20.

Financial conditions. Policy Rate peaks at -0.03 pp (annualized) in Q12, from +0.00 in Q1 to -0.02 in Q20. Govt 2Y Yield peaks at -0.03 pp (annualized) in Q9, from -0.01 in Q1 to -0.01 in Q20. Govt 5Y Yield peaks at -0.02 pp (annualized) in Q5, from -0.02 in Q1 to -0.00 in Q20. Govt 10Y Yield peaks at -0.01 pp (annualized) in Q3, from -0.01 in Q1 to -0.00 in Q20. Bond Price peaks at +0.07 % vs baseline in Q12, from -0.00 in Q1 to +0.04 in Q20. Equity Index peaks at +0.06 % vs baseline in Q20, from +0.00 in Q1 to +0.06 in Q20. Tobin's Q peaks at +0.04 % vs baseline in Q20, from -0.00 in Q1 to +0.04 in Q20. House Prices peaks at -0.01 % vs baseline in Q13, from +0.00 in Q1 to -0.00 in Q20. Bank Credit peaks at -0.07 % vs baseline in Q20, from +0.00 in Q1 to -0.07 in Q20. Credit Spread peaks at +0.01 pp in Q20, from +0.00 in Q1 to +0.01 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.01 % vs baseline in Q8, from -0.00 in Q1 to +0.00 in Q20. Services GDP peaks at -0.01 % vs baseline in Q9, from +0.00 in Q1 to +0.01 in Q20. Capital Stock peaks at +0.00 % vs baseline in Q20, from +0.00 in Q1 to +0.00 in Q20.

Timing. The GDP response has mostly faded by Q15 (Q20 is +0.01%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/NG_Y.png)

![CPI Inflation](charts/NG_pi_cpi.png)

![Equity Index](charts/NG_equity.png)

![Bond Price](charts/NG_Q_B.png)

![Bank Credit](charts/NG_credit_supply.png)

![Investment](charts/NG_I.png)

![Real Wages](charts/NG_w.png)

![Tobin's Q](charts/NG_Q.png)

![Gov Debt](charts/NG_B.png)

![Net Exports](charts/NG_NX.png)

![Currency Strength](charts/NG_RER.png)

![Policy Rate](charts/NG_i.png)

[Q1–Q20 JSON for Nigeria](numbers/NG.json)

## RU — Russia

The main impact of a -25% United Kingdom housing shock on Russia would be no material drop in GDP of 0.02% by Q10. Equities peak at +0.05% in Q20. This has almost no impact on Russia.

![GDP](charts/RU_Y.png)

![CPI Inflation](charts/RU_pi_cpi.png)

![Equity Index](charts/RU_equity.png)

![Net Exports](charts/RU_NX.png)

![Bond Price](charts/RU_Q_B.png)

![Real Wages](charts/RU_w.png)

![Currency Strength](charts/RU_RER.png)

![Investment](charts/RU_I.png)

![Bank Credit](charts/RU_credit_supply.png)

![Gov Spending](charts/RU_G.png)

![Tobin's Q](charts/RU_Q.png)

![Policy Rate](charts/RU_i.png)

[Q1–Q20 JSON for Russia](numbers/RU.json)

## CL — Chile

The main impact of a -25% United Kingdom housing shock on Chile would be no material drop in GDP of 0.01% by Q10. Equities peak at +0.03% in Q20. This has almost no impact on Chile.

![GDP](charts/CL_Y.png)

![CPI Inflation](charts/CL_pi_cpi.png)

![Equity Index](charts/CL_equity.png)

![Bond Price](charts/CL_Q_B.png)

![Real Wages](charts/CL_w.png)

![Investment](charts/CL_I.png)

![Policy Rate](charts/CL_i.png)

![Bank Credit](charts/CL_credit_supply.png)

![Govt 2Y Yield](charts/CL_y2.png)

![Govt 5Y Yield](charts/CL_y5.png)

![Tobin's Q](charts/CL_Q.png)

![Net Exports](charts/CL_NX.png)

[Q1–Q20 JSON for Chile](numbers/CL.json)

## CO — Colombia

The main impact of a -25% United Kingdom housing shock on Colombia would be no material drop in GDP of 0.01% by Q9. Equities peak at +0.04% in Q20. This has almost no impact on Colombia.

![GDP](charts/CO_Y.png)

![CPI Inflation](charts/CO_pi_cpi.png)

![Equity Index](charts/CO_equity.png)

![Bond Price](charts/CO_Q_B.png)

![Currency Strength](charts/CO_RER.png)

![Real Wages](charts/CO_w.png)

![Investment](charts/CO_I.png)

![Tobin's Q](charts/CO_Q.png)

![Policy Rate](charts/CO_i.png)

![Bank Credit](charts/CO_credit_supply.png)

![Govt 2Y Yield](charts/CO_y2.png)

![Net Exports](charts/CO_NX.png)

[Q1–Q20 JSON for Colombia](numbers/CO.json)

## ID — Indonesia

The main impact of a -25% United Kingdom housing shock on Indonesia would be no material drop in GDP of 0.01% by Q9. Equities peak at +0.04% in Q20. This has almost no impact on Indonesia.

![GDP](charts/ID_Y.png)

![CPI Inflation](charts/ID_pi_cpi.png)

![Equity Index](charts/ID_equity.png)

![Bond Price](charts/ID_Q_B.png)

![Investment](charts/ID_I.png)

![Real Wages](charts/ID_w.png)

![Tobin's Q](charts/ID_Q.png)

![Bank Credit](charts/ID_credit_supply.png)

![Policy Rate](charts/ID_i.png)

![Govt 2Y Yield](charts/ID_y2.png)

![Govt 5Y Yield](charts/ID_y5.png)

![Manuf. GDP](charts/ID_gdp_manufacturing.png)

[Q1–Q20 JSON for Indonesia](numbers/ID.json)


---

These figures are model IRFs versus baseline, not forecasts, and not financial advice.
