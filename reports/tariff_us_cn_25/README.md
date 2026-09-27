# Global Macro Economic Simulations and Financial Market Responses

v6 · IRF · evaluation

**Open the typeset report (this is the document):** https://robomacro.com/GlobalMacroTrainingDataset/tariff_us_cn_25/

GitHub and Hugging Face show `.html` as source code. That is not the report. Read it on robomacro.com, or keep scrolling this page.

## What's the impact of US-China tariffs 25% each way

### Active treatment

```json
{
  "bilateral_tariffs": [
    {
      "origin": "US",
      "target": "CN",
      "rate": 0.25
    },
    {
      "origin": "CN",
      "target": "US",
      "rate": 0.25
    }
  ]
}
```

### Assumptions

- Every path is a model impulse response versus baseline, not a forecast.
- The solver and weights are not included.
- English never enters the solver.

### Summary

This report traces the model response to bilateral tariffs at 25%. Every path is an impulse response versus an unchanged baseline — not a forecast and not market data. The question was: What's the impact of US-China tariffs 25% each way

China sees a -0.51% GDP peak at Q1, with CPI +0.67pp over three years and equities -1.07%. United States sees a -0.33% GDP peak at Q17, with CPI +1.20pp over three years and equities -1.11%. Canada sees a +0.19% GDP peak at Q1, with CPI -0.01pp over three years and equities +0.49%. Mexico sees a +0.19% GDP peak at Q1, with CPI +0.04pp over three years and equities +0.34%.

The remaining countries are smaller spillovers and are covered in the chapters that follow. This material is a model-based summary and is not financial advice.

### Countries by GDP impact

- [CN — China](#cn--china) · GDP -0.51% Q1
- [US — United States](#us--united-states) · GDP -0.33% Q17
- [CA — Canada](#ca--canada) · GDP +0.19% Q1
- [MX — Mexico](#mx--mexico) · GDP +0.19% Q1
- [MY — Malaysia](#my--malaysia) · GDP +0.14% Q1
- [TH — Thailand](#th--thailand) · GDP +0.12% Q1
- [KR — South Korea](#kr--south-korea) · GDP +0.11% Q1
- [CL — Chile](#cl--chile) · GDP +0.10% Q1
- [CH — Switzerland](#ch--switzerland) · GDP +0.09% Q1
- [ZA — South Africa](#za--south-africa) · GDP +0.07% Q1
- [JP — Japan](#jp--japan) · GDP +0.06% Q1
- [SA — Saudi Arabia](#sa--saudi-arabia) · GDP -0.06% Q16
- [CO — Colombia](#co--colombia) · GDP +0.04% Q1
- [IT — Italy](#it--italy) · GDP +0.04% Q2
- [AU — Australia](#au--australia) · GDP +0.04% Q1
- [DE — Germany](#de--germany) · GDP +0.04% Q1
- [SE — Sweden](#se--sweden) · GDP +0.04% Q1
- [BR — Brazil](#br--brazil) · GDP +0.04% Q1
- [UK — United Kingdom](#uk--united-kingdom) · GDP +0.03% Q1
- [IN — India](#in--india) · GDP +0.03% Q17
- [FR — France](#fr--france) · GDP +0.03% Q1
- [ID — Indonesia](#id--indonesia) · GDP +0.03% Q1
- [AR — Argentina](#ar--argentina) · GDP +0.03% Q16
- [TR — Turkey](#tr--turkey) · GDP +0.02% Q15
- [NG — Nigeria](#ng--nigeria) · GDP +0.02% Q18
- [NL — Netherlands](#nl--netherlands) · GDP +0.02% Q1
- [ES — Spain](#es--spain) · GDP +0.02% Q2
- [PL — Poland](#pl--poland) · GDP +0.01% Q2
- [NO — Norway](#no--norway) · GDP +0.01% Q1
- [RU — Russia](#ru--russia) · GDP +0.01% Q1

![CN GDP](charts/global_CN_Y.png)

![US GDP](charts/global_US_Y.png)

![CA GDP](charts/global_CA_Y.png)

![MX GDP](charts/global_MX_Y.png)

![US Equity Index](charts/global_US_equity.png)

![US Policy Rate](charts/global_US_i.png)

## CN — China

The main impact of bilateral tariffs at 25% on China would be a large drop in GDP of 0.51% by Q1. Equities peak at -1.07% in Q1.

Demand and trade. Consumption peaks at -0.38 % vs baseline in Q4, from -0.31 in Q1 to -0.28 in Q20. Investment peaks at -1.43 % vs baseline in Q1, from -1.43 in Q1 to -0.68 in Q20. Net Exports peaks at -0.45 % vs baseline in Q1, from -0.45 in Q1 to -0.31 in Q20. Gov Spending peaks at +0.09 % vs baseline in Q1, from +0.09 in Q1 to +0.06 in Q20. Gov Debt peaks at -4.59 % vs baseline in Q20, from -0.30 in Q1 to -4.59 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Currency Strength peaks at +0.17 % vs baseline in Q20, from +0.00 in Q1 to +0.17 in Q20.

Labour. Employment peaks at -0.45 % vs baseline in Q17, from -0.07 in Q1 to -0.44 in Q20. Unemployment peaks at +0.11 pp in Q10, from +0.03 in Q1 to +0.09 in Q20. Real Wages peaks at -0.59 % vs baseline in Q20, from -0.01 in Q1 to -0.59 in Q20.

Prices. The three-year CPI impulse is +0.67 percentage points. CPI Inflation peaks at +0.09 pp in Q1, from +0.09 in Q1 to +0.00 in Q20. Domestic Infl. peaks at +0.07 pp in Q1, from +0.07 in Q1 to +0.00 in Q20. Marginal Cost peaks at -0.31 % vs baseline in Q1, from -0.31 in Q1 to -0.22 in Q20.

Financial conditions. Policy Rate peaks at -0.21 pp (annualized) in Q20, from +0.00 in Q1 to -0.21 in Q20. Govt 2Y Yield peaks at -0.23 pp (annualized) in Q20, from -0.01 in Q1 to -0.23 in Q20. Govt 5Y Yield peaks at -0.23 pp (annualized) in Q20, from -0.09 in Q1 to -0.23 in Q20. Govt 10Y Yield peaks at -0.20 pp (annualized) in Q14, from -0.16 in Q1 to -0.19 in Q20. Bond Price peaks at +1.06 % vs baseline in Q20, from -0.02 in Q1 to +1.06 in Q20. Equity Index peaks at -1.07 % vs baseline in Q1, from -1.07 in Q1 to -0.72 in Q20. Tobin's Q peaks at -1.00 % vs baseline in Q1, from -1.00 in Q1 to -0.48 in Q20. House Prices peaks at -0.69 % vs baseline in Q20, from -0.08 in Q1 to -0.69 in Q20. Bank Credit peaks at -0.17 % vs baseline in Q20, from -0.02 in Q1 to -0.17 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.16 % vs baseline in Q1, from -0.16 in Q1 to -0.16 in Q20. Services GDP peaks at -0.30 % vs baseline in Q1, from -0.30 in Q1 to -0.21 in Q20. Capital Stock peaks at -0.11 % vs baseline in Q20, from -0.01 in Q1 to -0.11 in Q20.

Timing. By Q20 GDP is still -0.36% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/CN_Y.png)

![CPI Inflation](charts/CN_pi_cpi.png)

![Equity Index](charts/CN_equity.png)

![Gov Debt](charts/CN_B.png)

![Investment](charts/CN_I.png)

![Bond Price](charts/CN_Q_B.png)

![Tobin's Q](charts/CN_Q.png)

![House Prices](charts/CN_P_H.png)

![Real Wages](charts/CN_w.png)

![Net Exports](charts/CN_NX.png)

![Employment](charts/CN_N.png)

![Consumption](charts/CN_C.png)

[Q1–Q20 JSON for China](numbers/CN.json)

## US — United States

The main impact of bilateral tariffs at 25% on the United States would be a large drop in GDP of 0.33% by Q17. Equities peak at -1.11% in Q16.

Demand and trade. Consumption peaks at -0.23 % vs baseline in Q18, from -0.07 in Q1 to -0.22 in Q20. Investment peaks at -1.34 % vs baseline in Q11, from -0.46 in Q1 to -0.95 in Q20. Net Exports peaks at +0.26 % vs baseline in Q1, from +0.26 in Q1 to +0.16 in Q20. Gov Spending peaks at +0.06 % vs baseline in Q17, from +0.02 in Q1 to +0.06 in Q20. Gov Debt peaks at -0.80 % vs baseline in Q10, from -0.30 in Q1 to -0.73 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Currency Strength peaks at -0.71 % vs baseline in Q20, from -0.02 in Q1 to -0.71 in Q20.

Labour. Employment peaks at -0.38 % vs baseline in Q20, from -0.03 in Q1 to -0.38 in Q20. Unemployment peaks at +0.24 pp in Q20, from +0.01 in Q1 to +0.24 in Q20. Real Wages peaks at +0.49 % vs baseline in Q17, from -0.00 in Q1 to +0.47 in Q20.

Prices. The three-year CPI impulse is +1.20 percentage points. CPI Inflation peaks at +0.14 pp in Q2, from +0.14 in Q1 to +0.01 in Q20. Domestic Infl. peaks at +0.10 pp in Q2, from +0.10 in Q1 to +0.01 in Q20. Marginal Cost peaks at -0.20 % vs baseline in Q17, from -0.05 in Q1 to -0.19 in Q20.

Financial conditions. Policy Rate peaks at +0.52 pp (annualized) in Q6, from +0.16 in Q1 to +0.04 in Q20. Govt 2Y Yield peaks at +0.47 pp (annualized) in Q3, from +0.42 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at +0.31 pp (annualized) in Q1, from +0.31 in Q1 to -0.06 in Q20. Govt 10Y Yield peaks at +0.12 pp (annualized) in Q1, from +0.12 in Q1 to -0.05 in Q20. Bond Price peaks at -3.39 % vs baseline in Q6, from -1.07 in Q1 to -0.24 in Q20. Equity Index peaks at -1.11 % vs baseline in Q16, from -0.30 in Q1 to -1.04 in Q20. Tobin's Q peaks at -0.94 % vs baseline in Q11, from -0.32 in Q1 to -0.67 in Q20. House Prices peaks at -0.41 % vs baseline in Q20, from -0.01 in Q1 to -0.41 in Q20. Bank Credit peaks at -0.03 % vs baseline in Q20, from -0.00 in Q1 to -0.03 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.16 % vs baseline in Q20, from -0.00 in Q1 to +0.16 in Q20. Services GDP peaks at -0.26 % vs baseline in Q17, from -0.06 in Q1 to -0.25 in Q20. Capital Stock peaks at -0.11 % vs baseline in Q20, from -0.00 in Q1 to -0.11 in Q20.

Timing. By Q20 GDP is still -0.32% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/US_Y.png)

![CPI Inflation](charts/US_pi_cpi.png)

![Equity Index](charts/US_equity.png)

![Bond Price](charts/US_Q_B.png)

![Investment](charts/US_I.png)

![Tobin's Q](charts/US_Q.png)

![Gov Debt](charts/US_B.png)

![Currency Strength](charts/US_RER.png)

![Policy Rate](charts/US_i.png)

![Real Wages](charts/US_w.png)

![Govt 2Y Yield](charts/US_y2.png)

![House Prices](charts/US_P_H.png)

[Q1–Q20 JSON for United States](numbers/US.json)

## CA — Canada

The main impact of bilateral tariffs at 25% on Canada would be a moderate rise in GDP of 0.19% by Q1. Equities peak at +0.49% in Q1.

Demand and trade. Consumption peaks at +0.12 % vs baseline in Q3, from +0.10 in Q1 to +0.05 in Q20. Investment peaks at +0.50 % vs baseline in Q1, from +0.50 in Q1 to +0.14 in Q20. Net Exports peaks at +0.25 % vs baseline in Q1, from +0.25 in Q1 to +0.15 in Q20. Gov Spending peaks at -0.04 % vs baseline in Q2, from -0.04 in Q1 to -0.02 in Q20. Gov Debt peaks at +0.03 % vs baseline in Q18, from +0.00 in Q1 to +0.03 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Currency Strength peaks at +0.09 % vs baseline in Q4, from +0.05 in Q1 to +0.05 in Q20.

Labour. Employment peaks at +0.17 % vs baseline in Q7, from +0.06 in Q1 to +0.10 in Q20. Unemployment peaks at -0.09 pp in Q7, from -0.03 in Q1 to -0.05 in Q20. Real Wages peaks at +0.17 % vs baseline in Q20, from +0.00 in Q1 to +0.17 in Q20.

Prices. The three-year CPI impulse is -0.01 percentage points. CPI Inflation peaks at -0.00 pp in Q11, from +0.00 in Q1 to +0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q11, from +0.00 in Q1 to +0.00 in Q20. Marginal Cost peaks at +0.11 % vs baseline in Q1, from +0.11 in Q1 to +0.04 in Q20.

Financial conditions. Policy Rate peaks at +0.07 pp (annualized) in Q8, from +0.02 in Q1 to +0.05 in Q20. Govt 2Y Yield peaks at +0.06 pp (annualized) in Q5, from +0.05 in Q1 to +0.05 in Q20. Govt 5Y Yield peaks at +0.05 pp (annualized) in Q4, from +0.05 in Q1 to +0.05 in Q20. Govt 10Y Yield peaks at +0.05 pp (annualized) in Q4, from +0.05 in Q1 to +0.05 in Q20. Bond Price peaks at -0.39 % vs baseline in Q8, from -0.11 in Q1 to -0.27 in Q20. Equity Index peaks at +0.49 % vs baseline in Q1, from +0.49 in Q1 to +0.18 in Q20. Tobin's Q peaks at +0.35 % vs baseline in Q1, from +0.35 in Q1 to +0.10 in Q20. House Prices peaks at +0.15 % vs baseline in Q20, from +0.02 in Q1 to +0.15 in Q20. Bank Credit peaks at +0.01 % vs baseline in Q20, from +0.00 in Q1 to +0.01 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.02 % vs baseline in Q1, from +0.02 in Q1 to +0.01 in Q20. Services GDP peaks at +0.13 % vs baseline in Q1, from +0.13 in Q1 to +0.05 in Q20. Capital Stock peaks at +0.03 % vs baseline in Q20, from +0.00 in Q1 to +0.03 in Q20.

Timing. By Q20 GDP is still +0.07% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/CA_Y.png)

![CPI Inflation](charts/CA_pi_cpi.png)

![Equity Index](charts/CA_equity.png)

![Investment](charts/CA_I.png)

![Bond Price](charts/CA_Q_B.png)

![Tobin's Q](charts/CA_Q.png)

![Net Exports](charts/CA_NX.png)

![Real Wages](charts/CA_w.png)

![Employment](charts/CA_N.png)

![House Prices](charts/CA_P_H.png)

![Services GDP](charts/CA_gdp_services.png)

![Consumption](charts/CA_C.png)

[Q1–Q20 JSON for Canada](numbers/CA.json)

## MX — Mexico

The main impact of bilateral tariffs at 25% on Mexico would be a moderate rise in GDP of 0.19% by Q1. Equities peak at +0.34% in Q1.

Demand and trade. Consumption peaks at +0.11 % vs baseline in Q4, from +0.09 in Q1 to +0.06 in Q20. Investment peaks at +0.52 % vs baseline in Q1, from +0.52 in Q1 to +0.21 in Q20. Net Exports peaks at +0.26 % vs baseline in Q1, from +0.26 in Q1 to +0.19 in Q20. Gov Spending peaks at -0.03 % vs baseline in Q2, from -0.03 in Q1 to -0.02 in Q20. Gov Debt peaks at +0.25 % vs baseline in Q20, from +0.03 in Q1 to +0.25 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Currency Strength peaks at +0.09 % vs baseline in Q13, from +0.04 in Q1 to +0.07 in Q20.

Labour. Employment peaks at +0.15 % vs baseline in Q11, from +0.03 in Q1 to +0.13 in Q20. Unemployment peaks at -0.02 pp in Q8, from -0.01 in Q1 to -0.01 in Q20. Real Wages peaks at +0.26 % vs baseline in Q20, from +0.00 in Q1 to +0.26 in Q20.

Prices. The three-year CPI impulse is +0.04 percentage points. CPI Inflation peaks at +0.00 pp in Q7, from +0.00 in Q1 to +0.00 in Q20. Domestic Infl. peaks at +0.00 pp in Q7, from +0.00 in Q1 to +0.00 in Q20. Marginal Cost peaks at +0.11 % vs baseline in Q1, from +0.11 in Q1 to +0.05 in Q20.

Financial conditions. Policy Rate peaks at +0.02 pp (annualized) in Q10, from +0.01 in Q1 to +0.02 in Q20. Govt 2Y Yield peaks at +0.03 pp (annualized) in Q20, from +0.02 in Q1 to +0.03 in Q20. Govt 5Y Yield peaks at +0.03 pp (annualized) in Q20, from +0.02 in Q1 to +0.03 in Q20. Govt 10Y Yield peaks at +0.03 pp (annualized) in Q20, from +0.02 in Q1 to +0.03 in Q20. Bond Price peaks at -0.10 % vs baseline in Q10, from -0.02 in Q1 to -0.10 in Q20. Equity Index peaks at +0.34 % vs baseline in Q1, from +0.34 in Q1 to +0.15 in Q20. Tobin's Q peaks at +0.36 % vs baseline in Q1, from +0.36 in Q1 to +0.14 in Q20. House Prices peaks at +0.21 % vs baseline in Q17, from +0.03 in Q1 to +0.21 in Q20. Bank Credit peaks at +0.00 % vs baseline in Q20, from +0.00 in Q1 to +0.00 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.04 % vs baseline in Q1, from +0.04 in Q1 to +0.01 in Q20. Services GDP peaks at +0.11 % vs baseline in Q1, from +0.11 in Q1 to +0.05 in Q20. Capital Stock peaks at +0.03 % vs baseline in Q20, from +0.00 in Q1 to +0.03 in Q20.

Timing. By Q20 GDP is still +0.09% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/MX_Y.png)

![CPI Inflation](charts/MX_pi_cpi.png)

![Equity Index](charts/MX_equity.png)

![Investment](charts/MX_I.png)

![Tobin's Q](charts/MX_Q.png)

![Net Exports](charts/MX_NX.png)

![Real Wages](charts/MX_w.png)

![Gov Debt](charts/MX_B.png)

![House Prices](charts/MX_P_H.png)

![Employment](charts/MX_N.png)

![Services GDP](charts/MX_gdp_services.png)

![Marginal Cost](charts/MX_mc.png)

[Q1–Q20 JSON for Mexico](numbers/MX.json)

## MY — Malaysia

The main impact of bilateral tariffs at 25% on Malaysia would be a moderate rise in GDP of 0.14% by Q1. Equities peak at +0.38% in Q1.

Demand and trade. Consumption peaks at +0.10 % vs baseline in Q3, from +0.08 in Q1 to +0.06 in Q20. Investment peaks at +0.39 % vs baseline in Q1, from +0.39 in Q1 to +0.20 in Q20. Net Exports peaks at +0.20 % vs baseline in Q1, from +0.20 in Q1 to +0.13 in Q20. Gov Spending peaks at -0.02 % vs baseline in Q2, from -0.02 in Q1 to -0.02 in Q20. Gov Debt peaks at +0.25 % vs baseline in Q20, from +0.03 in Q1 to +0.25 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Currency Strength peaks at +0.03 % vs baseline in Q4, from +0.02 in Q1 to -0.01 in Q20.

Labour. Employment peaks at +0.12 % vs baseline in Q11, from +0.03 in Q1 to +0.11 in Q20. Unemployment peaks at -0.03 pp in Q8, from -0.01 in Q1 to -0.03 in Q20. Real Wages peaks at +0.19 % vs baseline in Q20, from +0.00 in Q1 to +0.19 in Q20.

Prices. The three-year CPI impulse is -0.01 percentage points. CPI Inflation peaks at -0.00 pp in Q4, from +0.00 in Q1 to +0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q4, from +0.00 in Q1 to +0.00 in Q20. Marginal Cost peaks at +0.09 % vs baseline in Q1, from +0.09 in Q1 to +0.05 in Q20.

Financial conditions. Policy Rate peaks at +0.03 pp (annualized) in Q20, from +0.01 in Q1 to +0.03 in Q20. Govt 2Y Yield peaks at +0.03 pp (annualized) in Q20, from +0.02 in Q1 to +0.03 in Q20. Govt 5Y Yield peaks at +0.03 pp (annualized) in Q20, from +0.03 in Q1 to +0.03 in Q20. Govt 10Y Yield peaks at +0.03 pp (annualized) in Q11, from +0.03 in Q1 to +0.03 in Q20. Bond Price peaks at -0.13 % vs baseline in Q20, from -0.03 in Q1 to -0.13 in Q20. Equity Index peaks at +0.38 % vs baseline in Q1, from +0.38 in Q1 to +0.23 in Q20. Tobin's Q peaks at +0.27 % vs baseline in Q1, from +0.27 in Q1 to +0.14 in Q20. House Prices peaks at +0.20 % vs baseline in Q20, from +0.03 in Q1 to +0.20 in Q20. Bank Credit peaks at +0.01 % vs baseline in Q20, from +0.00 in Q1 to +0.01 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.04 % vs baseline in Q1, from +0.04 in Q1 to +0.04 in Q20. Services GDP peaks at +0.08 % vs baseline in Q1, from +0.08 in Q1 to +0.05 in Q20. Capital Stock peaks at +0.03 % vs baseline in Q20, from +0.00 in Q1 to +0.03 in Q20.

Timing. By Q20 GDP is still +0.09% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/MY_Y.png)

![CPI Inflation](charts/MY_pi_cpi.png)

![Equity Index](charts/MY_equity.png)

![Investment](charts/MY_I.png)

![Tobin's Q](charts/MY_Q.png)

![Gov Debt](charts/MY_B.png)

![Net Exports](charts/MY_NX.png)

![House Prices](charts/MY_P_H.png)

![Real Wages](charts/MY_w.png)

![Bond Price](charts/MY_Q_B.png)

![Employment](charts/MY_N.png)

![Consumption](charts/MY_C.png)

[Q1–Q20 JSON for Malaysia](numbers/MY.json)

## TH — Thailand

The main impact of bilateral tariffs at 25% on Thailand would be a moderate rise in GDP of 0.12% by Q1. Equities peak at +0.31% in Q1.

Demand and trade. Consumption peaks at +0.08 % vs baseline in Q4, from +0.06 in Q1 to +0.05 in Q20. Investment peaks at +0.34 % vs baseline in Q1, from +0.34 in Q1 to +0.17 in Q20. Net Exports peaks at +0.18 % vs baseline in Q1, from +0.18 in Q1 to +0.12 in Q20. Gov Spending peaks at -0.02 % vs baseline in Q1, from -0.02 in Q1 to -0.01 in Q20. Gov Debt peaks at +0.19 % vs baseline in Q20, from +0.02 in Q1 to +0.19 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Currency Strength peaks at -0.04 % vs baseline in Q20, from +0.00 in Q1 to -0.04 in Q20.

Labour. Employment peaks at +0.11 % vs baseline in Q10, from +0.03 in Q1 to +0.10 in Q20. Unemployment peaks at -0.01 pp in Q8, from -0.00 in Q1 to -0.01 in Q20. Real Wages peaks at +0.17 % vs baseline in Q20, from +0.00 in Q1 to +0.17 in Q20.

Prices. The three-year CPI impulse is -0.01 percentage points. CPI Inflation peaks at -0.00 pp in Q3, from -0.00 in Q1 to +0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q3, from -0.00 in Q1 to +0.00 in Q20. Marginal Cost peaks at +0.07 % vs baseline in Q1, from +0.07 in Q1 to +0.05 in Q20.

Financial conditions. Policy Rate peaks at +0.03 pp (annualized) in Q20, from +0.01 in Q1 to +0.03 in Q20. Govt 2Y Yield peaks at +0.03 pp (annualized) in Q20, from +0.01 in Q1 to +0.03 in Q20. Govt 5Y Yield peaks at +0.03 pp (annualized) in Q20, from +0.02 in Q1 to +0.03 in Q20. Govt 10Y Yield peaks at +0.03 pp (annualized) in Q18, from +0.03 in Q1 to +0.03 in Q20. Bond Price peaks at -0.12 % vs baseline in Q20, from -0.02 in Q1 to -0.12 in Q20. Equity Index peaks at +0.31 % vs baseline in Q1, from +0.31 in Q1 to +0.18 in Q20. Tobin's Q peaks at +0.24 % vs baseline in Q1, from +0.24 in Q1 to +0.12 in Q20. House Prices peaks at +0.17 % vs baseline in Q20, from +0.02 in Q1 to +0.17 in Q20. Bank Credit peaks at +0.00 % vs baseline in Q20, from +0.00 in Q1 to +0.00 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.05 % vs baseline in Q20, from +0.04 in Q1 to +0.05 in Q20. Services GDP peaks at +0.07 % vs baseline in Q1, from +0.07 in Q1 to +0.04 in Q20. Capital Stock peaks at +0.02 % vs baseline in Q20, from +0.00 in Q1 to +0.02 in Q20.

Timing. By Q20 GDP is still +0.08% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/TH_Y.png)

![CPI Inflation](charts/TH_pi_cpi.png)

![Equity Index](charts/TH_equity.png)

![Investment](charts/TH_I.png)

![Tobin's Q](charts/TH_Q.png)

![Gov Debt](charts/TH_B.png)

![Net Exports](charts/TH_NX.png)

![Real Wages](charts/TH_w.png)

![House Prices](charts/TH_P_H.png)

![Bond Price](charts/TH_Q_B.png)

![Employment](charts/TH_N.png)

![Consumption](charts/TH_C.png)

[Q1–Q20 JSON for Thailand](numbers/TH.json)

## KR — South Korea

The main impact of bilateral tariffs at 25% on South Korea would be a moderate rise in GDP of 0.11% by Q1. Equities peak at +0.27% in Q1.

Demand and trade. Consumption peaks at +0.07 % vs baseline in Q3, from +0.05 in Q1 to +0.04 in Q20. Investment peaks at +0.30 % vs baseline in Q1, from +0.30 in Q1 to +0.13 in Q20. Net Exports peaks at +0.18 % vs baseline in Q3, from +0.18 in Q1 to +0.15 in Q20. Gov Spending peaks at -0.02 % vs baseline in Q1, from -0.02 in Q1 to -0.01 in Q20. Gov Debt peaks at +0.07 % vs baseline in Q20, from +0.01 in Q1 to +0.07 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Currency Strength peaks at -0.10 % vs baseline in Q20, from -0.02 in Q1 to -0.10 in Q20.

Labour. Employment peaks at +0.09 % vs baseline in Q10, from +0.02 in Q1 to +0.08 in Q20. Unemployment peaks at -0.04 pp in Q8, from -0.01 in Q1 to -0.03 in Q20. Real Wages peaks at +0.15 % vs baseline in Q20, from +0.00 in Q1 to +0.15 in Q20.

Prices. The three-year CPI impulse is +0.00 percentage points. CPI Inflation peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20. Domestic Infl. peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20. Marginal Cost peaks at +0.07 % vs baseline in Q1, from +0.07 in Q1 to +0.04 in Q20.

Financial conditions. Policy Rate peaks at +0.03 pp (annualized) in Q10, from +0.01 in Q1 to +0.03 in Q20. Govt 2Y Yield peaks at +0.03 pp (annualized) in Q20, from +0.02 in Q1 to +0.03 in Q20. Govt 5Y Yield peaks at +0.03 pp (annualized) in Q20, from +0.02 in Q1 to +0.03 in Q20. Govt 10Y Yield peaks at +0.03 pp (annualized) in Q7, from +0.03 in Q1 to +0.03 in Q20. Bond Price peaks at -0.13 % vs baseline in Q10, from -0.04 in Q1 to -0.13 in Q20. Equity Index peaks at +0.27 % vs baseline in Q1, from +0.27 in Q1 to +0.15 in Q20. Tobin's Q peaks at +0.21 % vs baseline in Q1, from +0.21 in Q1 to +0.09 in Q20. House Prices peaks at +0.11 % vs baseline in Q20, from +0.01 in Q1 to +0.11 in Q20. Bank Credit peaks at +0.00 % vs baseline in Q20, from +0.00 in Q1 to +0.00 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.06 % vs baseline in Q18, from +0.05 in Q1 to +0.06 in Q20. Services GDP peaks at +0.07 % vs baseline in Q1, from +0.07 in Q1 to +0.04 in Q20. Capital Stock peaks at +0.02 % vs baseline in Q20, from +0.00 in Q1 to +0.02 in Q20.

Timing. By Q20 GDP is still +0.06% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/KR_Y.png)

![CPI Inflation](charts/KR_pi_cpi.png)

![Equity Index](charts/KR_equity.png)

![Investment](charts/KR_I.png)

![Tobin's Q](charts/KR_Q.png)

![Net Exports](charts/KR_NX.png)

![Real Wages](charts/KR_w.png)

![Bond Price](charts/KR_Q_B.png)

![House Prices](charts/KR_P_H.png)

![Currency Strength](charts/KR_RER.png)

![Employment](charts/KR_N.png)

![Gov Debt](charts/KR_B.png)

[Q1–Q20 JSON for South Korea](numbers/KR.json)

## CL — Chile

The main impact of bilateral tariffs at 25% on Chile would be only a small rise in GDP of 0.10% by Q1. Equities peak at +0.23% in Q1.

Demand and trade. Consumption peaks at +0.06 % vs baseline in Q3, from +0.05 in Q1 to +0.04 in Q20. Investment peaks at +0.28 % vs baseline in Q1, from +0.28 in Q1 to +0.14 in Q20. Net Exports peaks at +0.13 % vs baseline in Q1, from +0.13 in Q1 to +0.08 in Q20. Gov Spending peaks at -0.04 % vs baseline in Q5, from -0.03 in Q1 to -0.03 in Q20. Gov Debt peaks at +0.09 % vs baseline in Q20, from +0.01 in Q1 to +0.09 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Currency Strength peaks at +0.18 % vs baseline in Q8, from +0.09 in Q1 to +0.14 in Q20.

Labour. Employment peaks at +0.09 % vs baseline in Q10, from +0.02 in Q1 to +0.07 in Q20. Unemployment peaks at -0.03 pp in Q8, from -0.01 in Q1 to -0.03 in Q20. Real Wages peaks at +0.14 % vs baseline in Q20, from +0.00 in Q1 to +0.14 in Q20.

Prices. The three-year CPI impulse is +0.01 percentage points. CPI Inflation peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20. Domestic Infl. peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20. Marginal Cost peaks at +0.06 % vs baseline in Q1, from +0.06 in Q1 to +0.03 in Q20.

Financial conditions. Policy Rate peaks at +0.01 pp (annualized) in Q20, from +0.00 in Q1 to +0.01 in Q20. Govt 2Y Yield peaks at +0.02 pp (annualized) in Q20, from +0.00 in Q1 to +0.02 in Q20. Govt 5Y Yield peaks at +0.02 pp (annualized) in Q20, from +0.01 in Q1 to +0.02 in Q20. Govt 10Y Yield peaks at +0.02 pp (annualized) in Q20, from +0.01 in Q1 to +0.02 in Q20. Bond Price peaks at -0.06 % vs baseline in Q20, from -0.00 in Q1 to -0.06 in Q20. Equity Index peaks at +0.23 % vs baseline in Q1, from +0.23 in Q1 to +0.13 in Q20. Tobin's Q peaks at +0.19 % vs baseline in Q1, from +0.19 in Q1 to +0.10 in Q20. House Prices peaks at +0.12 % vs baseline in Q20, from +0.02 in Q1 to +0.12 in Q20. Bank Credit peaks at +0.00 % vs baseline in Q20, from +0.00 in Q1 to +0.00 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.04 % vs baseline in Q9, from -0.01 in Q1 to -0.02 in Q20. Services GDP peaks at +0.06 % vs baseline in Q1, from +0.06 in Q1 to +0.03 in Q20. Capital Stock peaks at +0.02 % vs baseline in Q20, from +0.00 in Q1 to +0.02 in Q20.

Timing. By Q20 GDP is still +0.06% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/CL_Y.png)

![CPI Inflation](charts/CL_pi_cpi.png)

![Equity Index](charts/CL_equity.png)

![Investment](charts/CL_I.png)

![Tobin's Q](charts/CL_Q.png)

![Currency Strength](charts/CL_RER.png)

![Real Wages](charts/CL_w.png)

![Net Exports](charts/CL_NX.png)

![House Prices](charts/CL_P_H.png)

![Gov Debt](charts/CL_B.png)

![Employment](charts/CL_N.png)

![Services GDP](charts/CL_gdp_services.png)

[Q1–Q20 JSON for Chile](numbers/CL.json)

## CH — Switzerland

The main impact of bilateral tariffs at 25% on Switzerland would be only a small rise in GDP of 0.09% by Q1. Equities peak at +0.36% in Q1.

Demand and trade. Consumption peaks at +0.06 % vs baseline in Q3, from +0.05 in Q1 to +0.04 in Q20. Investment peaks at +0.25 % vs baseline in Q1, from +0.25 in Q1 to +0.13 in Q20. Net Exports peaks at +0.11 % vs baseline in Q1, from +0.11 in Q1 to +0.08 in Q20. Gov Spending peaks at -0.02 % vs baseline in Q1, from -0.02 in Q1 to -0.01 in Q20. Gov Debt peaks at +0.04 % vs baseline in Q20, from +0.01 in Q1 to +0.04 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Currency Strength peaks at -0.06 % vs baseline in Q20, from -0.01 in Q1 to -0.06 in Q20.

Labour. Employment peaks at +0.08 % vs baseline in Q8, from +0.02 in Q1 to +0.06 in Q20. Unemployment peaks at -0.04 pp in Q7, from -0.01 in Q1 to -0.03 in Q20. Real Wages peaks at +0.04 % vs baseline in Q20, from +0.00 in Q1 to +0.04 in Q20.

Prices. The three-year CPI impulse is -0.01 percentage points. CPI Inflation peaks at -0.00 pp in Q1, from -0.00 in Q1 to +0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q1, from -0.00 in Q1 to +0.00 in Q20. Marginal Cost peaks at +0.05 % vs baseline in Q1, from +0.05 in Q1 to +0.03 in Q20.

Financial conditions. Policy Rate peaks at +0.02 pp (annualized) in Q20, from +0.00 in Q1 to +0.02 in Q20. Govt 2Y Yield peaks at +0.02 pp (annualized) in Q20, from +0.01 in Q1 to +0.02 in Q20. Govt 5Y Yield peaks at +0.02 pp (annualized) in Q20, from +0.01 in Q1 to +0.02 in Q20. Govt 10Y Yield peaks at +0.02 pp (annualized) in Q20, from +0.02 in Q1 to +0.02 in Q20. Bond Price peaks at -0.11 % vs baseline in Q20, from -0.02 in Q1 to -0.11 in Q20. Equity Index peaks at +0.36 % vs baseline in Q1, from +0.36 in Q1 to +0.22 in Q20. Tobin's Q peaks at +0.18 % vs baseline in Q1, from +0.18 in Q1 to +0.09 in Q20. House Prices peaks at +0.10 % vs baseline in Q20, from +0.01 in Q1 to +0.10 in Q20. Bank Credit peaks at +0.00 % vs baseline in Q20, from +0.00 in Q1 to +0.00 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.04 % vs baseline in Q20, from +0.03 in Q1 to +0.04 in Q20. Services GDP peaks at +0.07 % vs baseline in Q1, from +0.07 in Q1 to +0.04 in Q20. Capital Stock peaks at +0.02 % vs baseline in Q20, from +0.00 in Q1 to +0.02 in Q20.

Timing. By Q20 GDP is still +0.05% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/CH_Y.png)

![CPI Inflation](charts/CH_pi_cpi.png)

![Equity Index](charts/CH_equity.png)

![Investment](charts/CH_I.png)

![Tobin's Q](charts/CH_Q.png)

![Net Exports](charts/CH_NX.png)

![Bond Price](charts/CH_Q_B.png)

![House Prices](charts/CH_P_H.png)

![Employment](charts/CH_N.png)

![Services GDP](charts/CH_gdp_services.png)

![Consumption](charts/CH_C.png)

![Currency Strength](charts/CH_RER.png)

[Q1–Q20 JSON for Switzerland](numbers/CH.json)

## ZA — South Africa

The main impact of bilateral tariffs at 25% on South Africa would be only a small rise in GDP of 0.07% by Q1. Equities peak at +0.29% in Q1.

Demand and trade. Consumption peaks at +0.04 % vs baseline in Q3, from +0.03 in Q1 to +0.03 in Q20. Investment peaks at +0.21 % vs baseline in Q1, from +0.21 in Q1 to +0.12 in Q20. Net Exports peaks at +0.10 % vs baseline in Q1, from +0.10 in Q1 to +0.06 in Q20. Gov Spending peaks at -0.02 % vs baseline in Q4, from -0.02 in Q1 to -0.01 in Q20. Gov Debt peaks at +0.07 % vs baseline in Q20, from +0.01 in Q1 to +0.07 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Currency Strength peaks at +0.14 % vs baseline in Q9, from +0.07 in Q1 to +0.11 in Q20.

Labour. Employment peaks at +0.07 % vs baseline in Q13, from +0.02 in Q1 to +0.07 in Q20. Unemployment peaks at -0.02 pp in Q10, from -0.01 in Q1 to -0.02 in Q20. Real Wages peaks at +0.11 % vs baseline in Q20, from +0.00 in Q1 to +0.11 in Q20.

Prices. The three-year CPI impulse is -0.00 percentage points. CPI Inflation peaks at +0.00 pp in Q20, from -0.00 in Q1 to +0.00 in Q20. Domestic Infl. peaks at +0.00 pp in Q20, from -0.00 in Q1 to +0.00 in Q20. Marginal Cost peaks at +0.04 % vs baseline in Q1, from +0.04 in Q1 to +0.03 in Q20.

Financial conditions. Policy Rate peaks at +0.01 pp (annualized) in Q20, from -0.00 in Q1 to +0.01 in Q20. Govt 2Y Yield peaks at +0.01 pp (annualized) in Q20, from -0.00 in Q1 to +0.01 in Q20. Govt 5Y Yield peaks at +0.01 pp (annualized) in Q20, from +0.00 in Q1 to +0.01 in Q20. Govt 10Y Yield peaks at +0.01 pp (annualized) in Q20, from +0.01 in Q1 to +0.01 in Q20. Bond Price peaks at -0.04 % vs baseline in Q20, from +0.00 in Q1 to -0.04 in Q20. Equity Index peaks at +0.29 % vs baseline in Q1, from +0.29 in Q1 to +0.20 in Q20. Tobin's Q peaks at +0.14 % vs baseline in Q1, from +0.14 in Q1 to +0.09 in Q20. House Prices peaks at +0.10 % vs baseline in Q20, from +0.01 in Q1 to +0.10 in Q20. Bank Credit peaks at +0.00 % vs baseline in Q20, from +0.00 in Q1 to +0.00 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.03 % vs baseline in Q8, from -0.01 in Q1 to -0.02 in Q20. Services GDP peaks at +0.05 % vs baseline in Q1, from +0.05 in Q1 to +0.03 in Q20. Capital Stock peaks at +0.02 % vs baseline in Q20, from +0.00 in Q1 to +0.02 in Q20.

Timing. By Q20 GDP is still +0.05% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/ZA_Y.png)

![CPI Inflation](charts/ZA_pi_cpi.png)

![Equity Index](charts/ZA_equity.png)

![Investment](charts/ZA_I.png)

![Tobin's Q](charts/ZA_Q.png)

![Currency Strength](charts/ZA_RER.png)

![Real Wages](charts/ZA_w.png)

![House Prices](charts/ZA_P_H.png)

![Net Exports](charts/ZA_NX.png)

![Gov Debt](charts/ZA_B.png)

![Employment](charts/ZA_N.png)

![Services GDP](charts/ZA_gdp_services.png)

[Q1–Q20 JSON for South Africa](numbers/ZA.json)

## JP — Japan

The main impact of bilateral tariffs at 25% on Japan would be only a small rise in GDP of 0.06% by Q1. Equities peak at +0.18% in Q1.

Demand and trade. Consumption peaks at +0.04 % vs baseline in Q3, from +0.03 in Q1 to +0.03 in Q20. Investment peaks at +0.18 % vs baseline in Q1, from +0.18 in Q1 to +0.12 in Q20. Net Exports peaks at +0.11 % vs baseline in Q5, from +0.10 in Q1 to +0.10 in Q20. Gov Spending peaks at -0.01 % vs baseline in Q1, from -0.01 in Q1 to -0.01 in Q20. Gov Debt peaks at +0.02 % vs baseline in Q20, from +0.00 in Q1 to +0.02 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Currency Strength peaks at -0.08 % vs baseline in Q16, from -0.03 in Q1 to -0.07 in Q20.

Labour. Employment peaks at +0.05 % vs baseline in Q7, from +0.02 in Q1 to +0.05 in Q20. Unemployment peaks at -0.03 pp in Q7, from -0.01 in Q1 to -0.02 in Q20. Real Wages peaks at -0.01 % vs baseline in Q17, from +0.00 in Q1 to -0.01 in Q20.

Prices. The three-year CPI impulse is -0.02 percentage points. CPI Inflation peaks at -0.00 pp in Q1, from -0.00 in Q1 to +0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q1, from -0.00 in Q1 to +0.00 in Q20. Marginal Cost peaks at +0.04 % vs baseline in Q1, from +0.04 in Q1 to +0.03 in Q20.

Financial conditions. Policy Rate peaks at -0.00 pp (annualized) in Q14, from -0.00 in Q1 to -0.00 in Q20. Govt 2Y Yield peaks at -0.00 pp (annualized) in Q10, from -0.00 in Q1 to -0.00 in Q20. Govt 5Y Yield peaks at -0.00 pp (annualized) in Q4, from -0.00 in Q1 to +0.00 in Q20. Govt 10Y Yield peaks at +0.00 pp (annualized) in Q20, from -0.00 in Q1 to +0.00 in Q20. Bond Price peaks at +0.02 % vs baseline in Q14, from +0.00 in Q1 to +0.01 in Q20. Equity Index peaks at +0.18 % vs baseline in Q1, from +0.18 in Q1 to +0.12 in Q20. Tobin's Q peaks at +0.13 % vs baseline in Q1, from +0.13 in Q1 to +0.09 in Q20. House Prices peaks at +0.06 % vs baseline in Q20, from +0.01 in Q1 to +0.06 in Q20. Bank Credit peaks at +0.00 % vs baseline in Q20, from +0.00 in Q1 to +0.00 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.04 % vs baseline in Q17, from +0.03 in Q1 to +0.04 in Q20. Services GDP peaks at +0.04 % vs baseline in Q1, from +0.04 in Q1 to +0.03 in Q20. Capital Stock peaks at +0.01 % vs baseline in Q20, from +0.00 in Q1 to +0.01 in Q20.

Timing. By Q20 GDP is still +0.04% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/JP_Y.png)

![CPI Inflation](charts/JP_pi_cpi.png)

![Equity Index](charts/JP_equity.png)

![Investment](charts/JP_I.png)

![Tobin's Q](charts/JP_Q.png)

![Net Exports](charts/JP_NX.png)

![Currency Strength](charts/JP_RER.png)

![House Prices](charts/JP_P_H.png)

![Employment](charts/JP_N.png)

![Services GDP](charts/JP_gdp_services.png)

![Manuf. GDP](charts/JP_gdp_manufacturing.png)

![Consumption](charts/JP_C.png)

[Q1–Q20 JSON for Japan](numbers/JP.json)

## SA — Saudi Arabia

The main impact of bilateral tariffs at 25% on Saudi Arabia would be only a small drop in GDP of 0.06% by Q16. Equities peak at -0.28% in Q14.

Demand and trade. Consumption peaks at -0.03 % vs baseline in Q17, from -0.01 in Q1 to -0.02 in Q20. Investment peaks at -0.80 % vs baseline in Q8, from -0.16 in Q1 to -0.18 in Q20. Net Exports peaks at -0.10 % vs baseline in Q17, from +0.03 in Q1 to -0.09 in Q20. Gov Spending peaks at -0.04 % vs baseline in Q17, from -0.02 in Q1 to -0.04 in Q20. Gov Debt peaks at -0.07 % vs baseline in Q20, from +0.00 in Q1 to -0.07 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Currency Strength peaks at -0.39 % vs baseline in Q15, from -0.01 in Q1 to -0.35 in Q20.

Labour. Employment peaks at -0.06 % vs baseline in Q19, from +0.01 in Q1 to -0.06 in Q20. Unemployment peaks at +0.02 pp in Q19, from -0.00 in Q1 to +0.02 in Q20. Real Wages peaks at -0.09 % vs baseline in Q20, from +0.00 in Q1 to -0.09 in Q20.

Prices. The three-year CPI impulse is -0.12 percentage points. CPI Inflation peaks at -0.01 pp in Q8, from -0.00 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.01 pp in Q8, from -0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.04 % vs baseline in Q16, from +0.02 in Q1 to -0.03 in Q20.

Financial conditions. Policy Rate peaks at +0.52 pp (annualized) in Q6, from +0.16 in Q1 to +0.04 in Q20. Govt 2Y Yield peaks at +0.47 pp (annualized) in Q3, from +0.42 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at +0.31 pp (annualized) in Q1, from +0.31 in Q1 to -0.06 in Q20. Govt 10Y Yield peaks at +0.12 pp (annualized) in Q1, from +0.12 in Q1 to -0.05 in Q20. Bond Price peaks at -2.58 % vs baseline in Q6, from -0.81 in Q1 to -0.18 in Q20. Equity Index peaks at -0.28 % vs baseline in Q14, from +0.09 in Q1 to -0.20 in Q20. Tobin's Q peaks at -0.56 % vs baseline in Q8, from -0.11 in Q1 to -0.13 in Q20. House Prices peaks at -0.12 % vs baseline in Q19, from +0.00 in Q1 to -0.12 in Q20. Bank Credit peaks at +0.00 % vs baseline in Q8, from +0.00 in Q1 to +0.00 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.11 % vs baseline in Q15, from +0.01 in Q1 to +0.10 in Q20. Services GDP peaks at -0.03 % vs baseline in Q16, from +0.01 in Q1 to -0.02 in Q20. Capital Stock peaks at -0.05 % vs baseline in Q20, from -0.00 in Q1 to -0.05 in Q20.

Timing. By Q20 GDP is still -0.05% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/SA_Y.png)

![CPI Inflation](charts/SA_pi_cpi.png)

![Equity Index](charts/SA_equity.png)

![Bond Price](charts/SA_Q_B.png)

![Investment](charts/SA_I.png)

![Tobin's Q](charts/SA_Q.png)

![Policy Rate](charts/SA_i.png)

![Govt 2Y Yield](charts/SA_y2.png)

![Currency Strength](charts/SA_RER.png)

![Govt 5Y Yield](charts/SA_y5.png)

![Govt 10Y Yield](charts/SA_y10.png)

![House Prices](charts/SA_P_H.png)

[Q1–Q20 JSON for Saudi Arabia](numbers/SA.json)

## CO — Colombia

The main impact of bilateral tariffs at 25% on Colombia would be only a small rise in GDP of 0.04% by Q1. Equities peak at +0.08% in Q1.

Demand and trade. Consumption peaks at +0.03 % vs baseline in Q3, from +0.02 in Q1 to +0.02 in Q20. Investment peaks at +0.13 % vs baseline in Q3, from +0.13 in Q1 to +0.06 in Q20. Net Exports peaks at +0.07 % vs baseline in Q1, from +0.07 in Q1 to +0.04 in Q20. Gov Spending peaks at -0.01 % vs baseline in Q4, from -0.01 in Q1 to -0.01 in Q20. Gov Debt peaks at +0.06 % vs baseline in Q20, from +0.01 in Q1 to +0.06 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Currency Strength peaks at +0.13 % vs baseline in Q16, from +0.04 in Q1 to +0.12 in Q20.

Labour. Employment peaks at +0.04 % vs baseline in Q12, from +0.01 in Q1 to +0.04 in Q20. Unemployment peaks at -0.01 pp in Q8, from -0.00 in Q1 to -0.00 in Q20. Real Wages peaks at +0.06 % vs baseline in Q20, from +0.00 in Q1 to +0.06 in Q20.

Prices. The three-year CPI impulse is -0.01 percentage points. CPI Inflation peaks at -0.00 pp in Q3, from -0.00 in Q1 to +0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q3, from -0.00 in Q1 to +0.00 in Q20. Marginal Cost peaks at +0.03 % vs baseline in Q1, from +0.03 in Q1 to +0.02 in Q20.

Financial conditions. Policy Rate peaks at -0.01 pp (annualized) in Q5, from -0.00 in Q1 to +0.01 in Q20. Govt 2Y Yield peaks at +0.01 pp (annualized) in Q20, from -0.01 in Q1 to +0.01 in Q20. Govt 5Y Yield peaks at +0.01 pp (annualized) in Q20, from -0.00 in Q1 to +0.01 in Q20. Govt 10Y Yield peaks at +0.01 pp (annualized) in Q20, from +0.00 in Q1 to +0.01 in Q20. Bond Price peaks at +0.03 % vs baseline in Q5, from +0.01 in Q1 to -0.02 in Q20. Equity Index peaks at +0.08 % vs baseline in Q1, from +0.08 in Q1 to +0.05 in Q20. Tobin's Q peaks at +0.09 % vs baseline in Q3, from +0.09 in Q1 to +0.05 in Q20. House Prices peaks at +0.05 % vs baseline in Q20, from +0.01 in Q1 to +0.05 in Q20. Bank Credit peaks at +0.00 % vs baseline in Q20, from +0.00 in Q1 to +0.00 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.02 % vs baseline in Q16, from -0.00 in Q1 to -0.02 in Q20. Services GDP peaks at +0.03 % vs baseline in Q1, from +0.03 in Q1 to +0.02 in Q20. Capital Stock peaks at +0.01 % vs baseline in Q20, from +0.00 in Q1 to +0.01 in Q20.

Timing. By Q20 GDP is still +0.03% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/CO_Y.png)

![CPI Inflation](charts/CO_pi_cpi.png)

![Equity Index](charts/CO_equity.png)

![Investment](charts/CO_I.png)

![Currency Strength](charts/CO_RER.png)

![Tobin's Q](charts/CO_Q.png)

![Net Exports](charts/CO_NX.png)

![Gov Debt](charts/CO_B.png)

![Real Wages](charts/CO_w.png)

![House Prices](charts/CO_P_H.png)

![Employment](charts/CO_N.png)

![Bond Price](charts/CO_Q_B.png)

[Q1–Q20 JSON for Colombia](numbers/CO.json)

## IT — Italy

The main impact of bilateral tariffs at 25% on Italy would be only a small rise in GDP of 0.04% by Q2. Equities peak at +0.07% in Q2.

Demand and trade. Consumption peaks at +0.02 % vs baseline in Q4, from +0.02 in Q1 to +0.02 in Q20. Investment peaks at +0.11 % vs baseline in Q2, from +0.11 in Q1 to +0.08 in Q20. Net Exports peaks at +0.07 % vs baseline in Q10, from +0.06 in Q1 to +0.06 in Q20. Gov Spending peaks at -0.01 % vs baseline in Q2, from -0.01 in Q1 to -0.01 in Q20. Gov Debt peaks at -0.00 % vs baseline in Q5, from -0.00 in Q1 to -0.00 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Currency Strength peaks at -0.04 % vs baseline in Q17, from -0.01 in Q1 to -0.04 in Q20.

Labour. Employment peaks at +0.04 % vs baseline in Q15, from +0.01 in Q1 to +0.04 in Q20. Unemployment peaks at -0.01 pp in Q9, from -0.00 in Q1 to -0.01 in Q20. Real Wages peaks at +0.02 % vs baseline in Q20, from +0.00 in Q1 to +0.02 in Q20.

Prices. The three-year CPI impulse is -0.01 percentage points. CPI Inflation peaks at -0.00 pp in Q3, from -0.00 in Q1 to +0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q3, from -0.00 in Q1 to +0.00 in Q20. Marginal Cost peaks at +0.02 % vs baseline in Q2, from +0.02 in Q1 to +0.02 in Q20.

Financial conditions. Policy Rate peaks at +0.00 pp (annualized) in Q18, from +0.00 in Q1 to +0.00 in Q20. Govt 2Y Yield peaks at +0.00 pp (annualized) in Q15, from +0.00 in Q1 to +0.00 in Q20. Govt 5Y Yield peaks at +0.00 pp (annualized) in Q12, from +0.00 in Q1 to +0.00 in Q20. Govt 10Y Yield peaks at +0.00 pp (annualized) in Q8, from +0.00 in Q1 to +0.00 in Q20. Bond Price peaks at -0.03 % vs baseline in Q18, from -0.00 in Q1 to -0.03 in Q20. Equity Index peaks at +0.07 % vs baseline in Q2, from +0.07 in Q1 to +0.05 in Q20. Tobin's Q peaks at +0.08 % vs baseline in Q2, from +0.08 in Q1 to +0.05 in Q20. House Prices peaks at +0.05 % vs baseline in Q20, from +0.00 in Q1 to +0.05 in Q20. Bank Credit peaks at +0.00 % vs baseline in Q20, from +0.00 in Q1 to +0.00 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.03 % vs baseline in Q16, from +0.01 in Q1 to +0.03 in Q20. Services GDP peaks at +0.03 % vs baseline in Q2, from +0.03 in Q1 to +0.02 in Q20. Capital Stock peaks at +0.01 % vs baseline in Q20, from +0.00 in Q1 to +0.01 in Q20.

Timing. By Q20 GDP is still +0.03% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/IT_Y.png)

![CPI Inflation](charts/IT_pi_cpi.png)

![Equity Index](charts/IT_equity.png)

![Investment](charts/IT_I.png)

![Tobin's Q](charts/IT_Q.png)

![Net Exports](charts/IT_NX.png)

![House Prices](charts/IT_P_H.png)

![Employment](charts/IT_N.png)

![Currency Strength](charts/IT_RER.png)

![Bond Price](charts/IT_Q_B.png)

![Services GDP](charts/IT_gdp_services.png)

![Manuf. GDP](charts/IT_gdp_manufacturing.png)

[Q1–Q20 JSON for Italy](numbers/IT.json)

## AU — Australia

The main impact of bilateral tariffs at 25% on Australia would be only a small rise in GDP of 0.04% by Q1. Equities peak at +0.10% in Q1.

Demand and trade. Consumption peaks at +0.02 % vs baseline in Q3, from +0.02 in Q1 to +0.01 in Q20. Investment peaks at +0.11 % vs baseline in Q1, from +0.11 in Q1 to +0.04 in Q20. Net Exports peaks at +0.05 % vs baseline in Q1, from +0.05 in Q1 to +0.01 in Q20. Gov Spending peaks at -0.02 % vs baseline in Q4, from -0.01 in Q1 to -0.01 in Q20. Gov Debt peaks at +0.02 % vs baseline in Q20, from +0.00 in Q1 to +0.02 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Currency Strength peaks at +0.43 % vs baseline in Q9, from +0.22 in Q1 to +0.35 in Q20.

Labour. Employment peaks at +0.03 % vs baseline in Q7, from +0.01 in Q1 to +0.02 in Q20. Unemployment peaks at -0.02 pp in Q7, from -0.01 in Q1 to -0.01 in Q20. Real Wages peaks at +0.03 % vs baseline in Q20, from +0.00 in Q1 to +0.03 in Q20.

Prices. The three-year CPI impulse is -0.01 percentage points. CPI Inflation peaks at -0.00 pp in Q3, from -0.00 in Q1 to +0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q3, from -0.00 in Q1 to +0.00 in Q20. Marginal Cost peaks at +0.02 % vs baseline in Q1, from +0.02 in Q1 to +0.01 in Q20.

Financial conditions. Policy Rate peaks at +0.01 pp (annualized) in Q20, from +0.00 in Q1 to +0.01 in Q20. Govt 2Y Yield peaks at +0.01 pp (annualized) in Q20, from +0.01 in Q1 to +0.01 in Q20. Govt 5Y Yield peaks at +0.01 pp (annualized) in Q20, from +0.01 in Q1 to +0.01 in Q20. Govt 10Y Yield peaks at +0.01 pp (annualized) in Q20, from +0.01 in Q1 to +0.01 in Q20. Bond Price peaks at -0.06 % vs baseline in Q20, from -0.01 in Q1 to -0.06 in Q20. Equity Index peaks at +0.10 % vs baseline in Q1, from +0.10 in Q1 to +0.04 in Q20. Tobin's Q peaks at +0.08 % vs baseline in Q1, from +0.08 in Q1 to +0.03 in Q20. House Prices peaks at +0.03 % vs baseline in Q20, from +0.00 in Q1 to +0.03 in Q20. Bank Credit peaks at +0.00 % vs baseline in Q20, from +0.00 in Q1 to +0.00 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.12 % vs baseline in Q9, from -0.06 in Q1 to -0.10 in Q20. Services GDP peaks at +0.03 % vs baseline in Q1, from +0.03 in Q1 to +0.01 in Q20. Capital Stock peaks at +0.01 % vs baseline in Q20, from +0.00 in Q1 to +0.01 in Q20.

Timing. By Q20 GDP is still +0.02% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/AU_Y.png)

![CPI Inflation](charts/AU_pi_cpi.png)

![Equity Index](charts/AU_equity.png)

![Currency Strength](charts/AU_RER.png)

![Manuf. GDP](charts/AU_gdp_manufacturing.png)

![Investment](charts/AU_I.png)

![Tobin's Q](charts/AU_Q.png)

![Bond Price](charts/AU_Q_B.png)

![Net Exports](charts/AU_NX.png)

![Real Wages](charts/AU_w.png)

![Employment](charts/AU_N.png)

![House Prices](charts/AU_P_H.png)

[Q1–Q20 JSON for Australia](numbers/AU.json)

## DE — Germany

The main impact of bilateral tariffs at 25% on Germany would be only a small rise in GDP of 0.04% by Q1. Equities peak at +0.08% in Q1.

Demand and trade. Consumption peaks at +0.02 % vs baseline in Q3, from +0.02 in Q1 to +0.01 in Q20. Investment peaks at +0.11 % vs baseline in Q1, from +0.11 in Q1 to +0.06 in Q20. Net Exports peaks at +0.08 % vs baseline in Q10, from +0.07 in Q1 to +0.07 in Q20. Gov Spending peaks at -0.01 % vs baseline in Q1, from -0.01 in Q1 to -0.01 in Q20. Gov Debt peaks at -0.01 % vs baseline in Q20, from -0.00 in Q1 to -0.01 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Currency Strength peaks at -0.03 % vs baseline in Q16, from -0.01 in Q1 to -0.03 in Q20.

Labour. Employment peaks at +0.03 % vs baseline in Q8, from +0.01 in Q1 to +0.03 in Q20. Unemployment peaks at -0.02 pp in Q6, from -0.01 in Q1 to -0.01 in Q20. Real Wages peaks at +0.03 % vs baseline in Q20, from +0.00 in Q1 to +0.03 in Q20.

Prices. The three-year CPI impulse is -0.01 percentage points. CPI Inflation peaks at -0.00 pp in Q3, from -0.00 in Q1 to +0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q3, from -0.00 in Q1 to +0.00 in Q20. Marginal Cost peaks at +0.02 % vs baseline in Q1, from +0.02 in Q1 to +0.01 in Q20.

Financial conditions. Policy Rate peaks at +0.00 pp (annualized) in Q18, from +0.00 in Q1 to +0.00 in Q20. Govt 2Y Yield peaks at +0.00 pp (annualized) in Q15, from +0.00 in Q1 to +0.00 in Q20. Govt 5Y Yield peaks at +0.00 pp (annualized) in Q12, from +0.00 in Q1 to +0.00 in Q20. Govt 10Y Yield peaks at +0.00 pp (annualized) in Q8, from +0.00 in Q1 to +0.00 in Q20. Bond Price peaks at -0.03 % vs baseline in Q18, from -0.00 in Q1 to -0.03 in Q20. Equity Index peaks at +0.08 % vs baseline in Q1, from +0.08 in Q1 to +0.05 in Q20. Tobin's Q peaks at +0.08 % vs baseline in Q1, from +0.08 in Q1 to +0.04 in Q20. House Prices peaks at +0.04 % vs baseline in Q20, from +0.00 in Q1 to +0.04 in Q20. Bank Credit peaks at +0.00 % vs baseline in Q20, from +0.00 in Q1 to +0.00 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.03 % vs baseline in Q18, from +0.02 in Q1 to +0.03 in Q20. Services GDP peaks at +0.03 % vs baseline in Q1, from +0.03 in Q1 to +0.02 in Q20. Capital Stock peaks at +0.01 % vs baseline in Q20, from +0.00 in Q1 to +0.01 in Q20.

Timing. By Q20 GDP is still +0.02% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/DE_Y.png)

![CPI Inflation](charts/DE_pi_cpi.png)

![Equity Index](charts/DE_equity.png)

![Investment](charts/DE_I.png)

![Tobin's Q](charts/DE_Q.png)

![Net Exports](charts/DE_NX.png)

![House Prices](charts/DE_P_H.png)

![Currency Strength](charts/DE_RER.png)

![Bond Price](charts/DE_Q_B.png)

![Employment](charts/DE_N.png)

![Real Wages](charts/DE_w.png)

![Services GDP](charts/DE_gdp_services.png)

[Q1–Q20 JSON for Germany](numbers/DE.json)

## SE — Sweden

The main impact of bilateral tariffs at 25% on Sweden would be only a small rise in GDP of 0.04% by Q1. Equities peak at +0.11% in Q1.

Demand and trade. Consumption peaks at +0.02 % vs baseline in Q3, from +0.02 in Q1 to +0.02 in Q20. Investment peaks at +0.11 % vs baseline in Q1, from +0.11 in Q1 to +0.07 in Q20. Net Exports peaks at +0.05 % vs baseline in Q1, from +0.05 in Q1 to +0.04 in Q20. Gov Spending peaks at -0.01 % vs baseline in Q2, from -0.01 in Q1 to -0.01 in Q20. Gov Debt peaks at -0.02 % vs baseline in Q20, from -0.00 in Q1 to -0.02 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Currency Strength peaks at +0.07 % vs baseline in Q11, from +0.03 in Q1 to +0.06 in Q20.

Labour. Employment peaks at +0.03 % vs baseline in Q16, from +0.01 in Q1 to +0.03 in Q20. Unemployment peaks at -0.02 pp in Q9, from -0.01 in Q1 to -0.02 in Q20. Real Wages peaks at +0.04 % vs baseline in Q20, from +0.00 in Q1 to +0.04 in Q20.

Prices. The three-year CPI impulse is -0.01 percentage points. CPI Inflation peaks at -0.00 pp in Q2, from -0.00 in Q1 to +0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q2, from -0.00 in Q1 to +0.00 in Q20. Marginal Cost peaks at +0.02 % vs baseline in Q1, from +0.02 in Q1 to +0.02 in Q20.

Financial conditions. Policy Rate peaks at -0.00 pp (annualized) in Q6, from -0.00 in Q1 to +0.00 in Q20. Govt 2Y Yield peaks at -0.00 pp (annualized) in Q3, from -0.00 in Q1 to +0.00 in Q20. Govt 5Y Yield peaks at +0.01 pp (annualized) in Q20, from -0.00 in Q1 to +0.01 in Q20. Govt 10Y Yield peaks at +0.01 pp (annualized) in Q20, from +0.00 in Q1 to +0.01 in Q20. Bond Price peaks at +0.03 % vs baseline in Q6, from +0.01 in Q1 to -0.01 in Q20. Equity Index peaks at +0.11 % vs baseline in Q1, from +0.11 in Q1 to +0.08 in Q20. Tobin's Q peaks at +0.07 % vs baseline in Q1, from +0.07 in Q1 to +0.05 in Q20. House Prices peaks at +0.04 % vs baseline in Q20, from +0.00 in Q1 to +0.04 in Q20. Bank Credit peaks at +0.00 % vs baseline in Q20, from +0.00 in Q1 to +0.00 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.01 % vs baseline in Q8, from +0.00 in Q1 to -0.00 in Q20. Services GDP peaks at +0.03 % vs baseline in Q1, from +0.03 in Q1 to +0.02 in Q20. Capital Stock peaks at +0.01 % vs baseline in Q20, from +0.00 in Q1 to +0.01 in Q20.

Timing. By Q20 GDP is still +0.03% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/SE_Y.png)

![CPI Inflation](charts/SE_pi_cpi.png)

![Equity Index](charts/SE_equity.png)

![Investment](charts/SE_I.png)

![Tobin's Q](charts/SE_Q.png)

![Currency Strength](charts/SE_RER.png)

![Net Exports](charts/SE_NX.png)

![House Prices](charts/SE_P_H.png)

![Real Wages](charts/SE_w.png)

![Employment](charts/SE_N.png)

![Bond Price](charts/SE_Q_B.png)

![Services GDP](charts/SE_gdp_services.png)

[Q1–Q20 JSON for Sweden](numbers/SE.json)

## BR — Brazil

The main impact of bilateral tariffs at 25% on Brazil would be only a small rise in GDP of 0.04% by Q1. Equities peak at +0.07% in Q1.

Demand and trade. Consumption peaks at +0.02 % vs baseline in Q3, from +0.02 in Q1 to +0.01 in Q20. Investment peaks at +0.11 % vs baseline in Q3, from +0.10 in Q1 to +0.05 in Q20. Net Exports peaks at +0.05 % vs baseline in Q1, from +0.05 in Q1 to +0.01 in Q20. Gov Spending peaks at -0.01 % vs baseline in Q13, from -0.01 in Q1 to -0.01 in Q20. Gov Debt peaks at +0.01 % vs baseline in Q20, from +0.00 in Q1 to +0.01 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Currency Strength peaks at +0.10 % vs baseline in Q15, from +0.03 in Q1 to +0.09 in Q20.

Labour. Employment peaks at +0.03 % vs baseline in Q17, from +0.01 in Q1 to +0.03 in Q20. Unemployment peaks at -0.01 pp in Q10, from -0.00 in Q1 to -0.01 in Q20. Real Wages peaks at +0.05 % vs baseline in Q20, from +0.00 in Q1 to +0.05 in Q20.

Prices. The three-year CPI impulse is -0.01 percentage points. CPI Inflation peaks at -0.00 pp in Q3, from -0.00 in Q1 to +0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q3, from -0.00 in Q1 to +0.00 in Q20. Marginal Cost peaks at +0.02 % vs baseline in Q1, from +0.02 in Q1 to +0.01 in Q20.

Financial conditions. Policy Rate peaks at -0.01 pp (annualized) in Q5, from -0.00 in Q1 to +0.01 in Q20. Govt 2Y Yield peaks at +0.01 pp (annualized) in Q20, from -0.01 in Q1 to +0.01 in Q20. Govt 5Y Yield peaks at +0.01 pp (annualized) in Q20, from -0.00 in Q1 to +0.01 in Q20. Govt 10Y Yield peaks at +0.01 pp (annualized) in Q17, from +0.01 in Q1 to +0.01 in Q20. Bond Price peaks at +0.05 % vs baseline in Q5, from +0.01 in Q1 to -0.04 in Q20. Equity Index peaks at +0.07 % vs baseline in Q1, from +0.07 in Q1 to +0.04 in Q20. Tobin's Q peaks at +0.07 % vs baseline in Q3, from +0.07 in Q1 to +0.04 in Q20. House Prices peaks at +0.04 % vs baseline in Q20, from +0.01 in Q1 to +0.04 in Q20. Bank Credit peaks at +0.00 % vs baseline in Q20, from +0.00 in Q1 to +0.00 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.02 % vs baseline in Q14, from -0.00 in Q1 to -0.01 in Q20. Services GDP peaks at +0.02 % vs baseline in Q1, from +0.02 in Q1 to +0.02 in Q20. Capital Stock peaks at +0.01 % vs baseline in Q20, from +0.00 in Q1 to +0.01 in Q20.

Timing. By Q20 GDP is still +0.02% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/BR_Y.png)

![CPI Inflation](charts/BR_pi_cpi.png)

![Equity Index](charts/BR_equity.png)

![Investment](charts/BR_I.png)

![Currency Strength](charts/BR_RER.png)

![Tobin's Q](charts/BR_Q.png)

![Real Wages](charts/BR_w.png)

![Bond Price](charts/BR_Q_B.png)

![Net Exports](charts/BR_NX.png)

![House Prices](charts/BR_P_H.png)

![Employment](charts/BR_N.png)

![Services GDP](charts/BR_gdp_services.png)

[Q1–Q20 JSON for Brazil](numbers/BR.json)

## UK — United Kingdom

The main impact of bilateral tariffs at 25% on United Kingdom would be only a small rise in GDP of 0.03% by Q1. Equities peak at +0.08% in Q1.

Demand and trade. Consumption peaks at +0.02 % vs baseline in Q2, from +0.02 in Q1 to +0.01 in Q20. Investment peaks at +0.09 % vs baseline in Q1, from +0.09 in Q1 to +0.03 in Q20. Net Exports peaks at +0.05 % vs baseline in Q5, from +0.05 in Q1 to +0.05 in Q20. Gov Spending peaks at -0.01 % vs baseline in Q1, from -0.01 in Q1 to -0.00 in Q20. Gov Debt peaks at +0.00 % vs baseline in Q5, from +0.00 in Q1 to +0.00 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Currency Strength peaks at -0.02 % vs baseline in Q14, from -0.01 in Q1 to -0.02 in Q20.

Labour. Employment peaks at +0.02 % vs baseline in Q5, from +0.01 in Q1 to +0.01 in Q20. Unemployment peaks at -0.01 pp in Q5, from -0.00 in Q1 to -0.00 in Q20. Real Wages peaks at +0.00 % vs baseline in Q12, from +0.00 in Q1 to +0.00 in Q20.

Prices. The three-year CPI impulse is -0.01 percentage points. CPI Inflation peaks at -0.00 pp in Q11, from -0.00 in Q1 to +0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q11, from -0.00 in Q1 to +0.00 in Q20. Marginal Cost peaks at +0.02 % vs baseline in Q1, from +0.02 in Q1 to +0.01 in Q20.

Financial conditions. Policy Rate peaks at -0.00 pp (annualized) in Q16, from -0.00 in Q1 to -0.00 in Q20. Govt 2Y Yield peaks at -0.00 pp (annualized) in Q12, from -0.00 in Q1 to -0.00 in Q20. Govt 5Y Yield peaks at -0.00 pp (annualized) in Q4, from -0.00 in Q1 to +0.00 in Q20. Govt 10Y Yield peaks at +0.00 pp (annualized) in Q20, from +0.00 in Q1 to +0.00 in Q20. Bond Price peaks at +0.02 % vs baseline in Q16, from +0.00 in Q1 to +0.01 in Q20. Equity Index peaks at +0.08 % vs baseline in Q1, from +0.08 in Q1 to +0.02 in Q20. Tobin's Q peaks at +0.06 % vs baseline in Q1, from +0.06 in Q1 to +0.02 in Q20. House Prices peaks at +0.02 % vs baseline in Q8, from +0.00 in Q1 to +0.01 in Q20. Bank Credit peaks at -0.00 % vs baseline in Q18, from +0.00 in Q1 to -0.00 in Q20. Credit Spread peaks at +0.00 pp in Q18, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.01 % vs baseline in Q19, from +0.01 in Q1 to +0.01 in Q20. Services GDP peaks at +0.02 % vs baseline in Q1, from +0.02 in Q1 to +0.01 in Q20. Capital Stock peaks at +0.00 % vs baseline in Q20, from +0.00 in Q1 to +0.00 in Q20.

Timing. The GDP response has mostly faded by Q9 (Q20 is +0.01%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/UK_Y.png)

![CPI Inflation](charts/UK_pi_cpi.png)

![Equity Index](charts/UK_equity.png)

![Investment](charts/UK_I.png)

![Tobin's Q](charts/UK_Q.png)

![Net Exports](charts/UK_NX.png)

![Services GDP](charts/UK_gdp_services.png)

![Employment](charts/UK_N.png)

![Marginal Cost](charts/UK_mc.png)

![Currency Strength](charts/UK_RER.png)

![Consumption](charts/UK_C.png)

![House Prices](charts/UK_P_H.png)

[Q1–Q20 JSON for United Kingdom](numbers/UK.json)

## IN — India

The main impact of bilateral tariffs at 25% on India would be only a small rise in GDP of 0.03% by Q17. Equities peak at +0.08% in Q15.

Demand and trade. Consumption peaks at +0.02 % vs baseline in Q17, from +0.01 in Q1 to +0.02 in Q20. Investment peaks at +0.09 % vs baseline in Q9, from +0.07 in Q1 to +0.07 in Q20. Net Exports peaks at +0.05 % vs baseline in Q13, from +0.04 in Q1 to +0.04 in Q20. Gov Spending peaks at -0.01 % vs baseline in Q17, from -0.00 in Q1 to -0.01 in Q20. Gov Debt peaks at +0.07 % vs baseline in Q20, from +0.00 in Q1 to +0.07 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Currency Strength peaks at -0.01 % vs baseline in Q3, from -0.00 in Q1 to +0.00 in Q20.

Labour. Employment peaks at +0.03 % vs baseline in Q20, from +0.00 in Q1 to +0.03 in Q20. Unemployment peaks at -0.00 pp in Q19, from -0.00 in Q1 to -0.00 in Q20. Real Wages peaks at +0.03 % vs baseline in Q20, from +0.00 in Q1 to +0.03 in Q20.

Prices. The three-year CPI impulse is -0.03 percentage points. CPI Inflation peaks at -0.00 pp in Q3, from -0.00 in Q1 to +0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q3, from -0.00 in Q1 to +0.00 in Q20. Marginal Cost peaks at +0.02 % vs baseline in Q17, from +0.01 in Q1 to +0.02 in Q20.

Financial conditions. Policy Rate peaks at -0.02 pp (annualized) in Q5, from -0.01 in Q1 to +0.01 in Q20. Govt 2Y Yield peaks at -0.02 pp (annualized) in Q3, from -0.02 in Q1 to +0.01 in Q20. Govt 5Y Yield peaks at +0.02 pp (annualized) in Q20, from -0.01 in Q1 to +0.02 in Q20. Govt 10Y Yield peaks at +0.01 pp (annualized) in Q18, from +0.00 in Q1 to +0.01 in Q20. Bond Price peaks at +0.10 % vs baseline in Q5, from +0.03 in Q1 to -0.04 in Q20. Equity Index peaks at +0.08 % vs baseline in Q15, from +0.06 in Q1 to +0.07 in Q20. Tobin's Q peaks at +0.06 % vs baseline in Q9, from +0.05 in Q1 to +0.05 in Q20. House Prices peaks at +0.05 % vs baseline in Q20, from +0.00 in Q1 to +0.05 in Q20. Bank Credit peaks at +0.00 % vs baseline in Q20, from +0.00 in Q1 to +0.00 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.02 % vs baseline in Q16, from +0.01 in Q1 to +0.02 in Q20. Services GDP peaks at +0.02 % vs baseline in Q17, from +0.01 in Q1 to +0.02 in Q20. Capital Stock peaks at +0.01 % vs baseline in Q20, from +0.00 in Q1 to +0.01 in Q20.

Timing. By Q20 GDP is still +0.03% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/IN_Y.png)

![CPI Inflation](charts/IN_pi_cpi.png)

![Equity Index](charts/IN_equity.png)

![Bond Price](charts/IN_Q_B.png)

![Investment](charts/IN_I.png)

![Gov Debt](charts/IN_B.png)

![Tobin's Q](charts/IN_Q.png)

![House Prices](charts/IN_P_H.png)

![Net Exports](charts/IN_NX.png)

![Real Wages](charts/IN_w.png)

![Employment](charts/IN_N.png)

![Policy Rate](charts/IN_i.png)

[Q1–Q20 JSON for India](numbers/IN.json)

## FR — France

The main impact of bilateral tariffs at 25% on France would be only a small rise in GDP of 0.03% by Q1. Equities peak at +0.06% in Q1.

Demand and trade. Consumption peaks at +0.01 % vs baseline in Q3, from +0.01 in Q1 to +0.01 in Q20. Investment peaks at +0.07 % vs baseline in Q1, from +0.07 in Q1 to +0.03 in Q20. Net Exports peaks at +0.04 % vs baseline in Q4, from +0.04 in Q1 to +0.04 in Q20. Gov Spending peaks at -0.01 % vs baseline in Q1, from -0.01 in Q1 to -0.00 in Q20. Gov Debt peaks at -0.02 % vs baseline in Q20, from -0.00 in Q1 to -0.02 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Currency Strength peaks at -0.03 % vs baseline in Q18, from -0.01 in Q1 to -0.03 in Q20.

Labour. Employment peaks at +0.02 % vs baseline in Q8, from +0.00 in Q1 to +0.01 in Q20. Unemployment peaks at -0.01 pp in Q6, from -0.00 in Q1 to -0.01 in Q20. Real Wages peaks at +0.00 % vs baseline in Q20, from +0.00 in Q1 to +0.00 in Q20.

Prices. The three-year CPI impulse is -0.02 percentage points. CPI Inflation peaks at -0.00 pp in Q3, from -0.00 in Q1 to +0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q3, from -0.00 in Q1 to +0.00 in Q20. Marginal Cost peaks at +0.02 % vs baseline in Q1, from +0.02 in Q1 to +0.01 in Q20.

Financial conditions. Policy Rate peaks at +0.00 pp (annualized) in Q18, from +0.00 in Q1 to +0.00 in Q20. Govt 2Y Yield peaks at +0.00 pp (annualized) in Q15, from +0.00 in Q1 to +0.00 in Q20. Govt 5Y Yield peaks at +0.00 pp (annualized) in Q12, from +0.00 in Q1 to +0.00 in Q20. Govt 10Y Yield peaks at +0.00 pp (annualized) in Q8, from +0.00 in Q1 to +0.00 in Q20. Bond Price peaks at -0.03 % vs baseline in Q18, from -0.00 in Q1 to -0.03 in Q20. Equity Index peaks at +0.06 % vs baseline in Q1, from +0.06 in Q1 to +0.03 in Q20. Tobin's Q peaks at +0.05 % vs baseline in Q1, from +0.05 in Q1 to +0.02 in Q20. House Prices peaks at +0.02 % vs baseline in Q20, from +0.00 in Q1 to +0.02 in Q20. Bank Credit peaks at +0.00 % vs baseline in Q7, from +0.00 in Q1 to +0.00 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.02 % vs baseline in Q18, from +0.01 in Q1 to +0.02 in Q20. Services GDP peaks at +0.02 % vs baseline in Q1, from +0.02 in Q1 to +0.01 in Q20. Capital Stock peaks at +0.00 % vs baseline in Q20, from +0.00 in Q1 to +0.00 in Q20.

Timing. By Q20 GDP is still +0.01% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/FR_Y.png)

![CPI Inflation](charts/FR_pi_cpi.png)

![Equity Index](charts/FR_equity.png)

![Investment](charts/FR_I.png)

![Tobin's Q](charts/FR_Q.png)

![Net Exports](charts/FR_NX.png)

![Bond Price](charts/FR_Q_B.png)

![Currency Strength](charts/FR_RER.png)

![Services GDP](charts/FR_gdp_services.png)

![House Prices](charts/FR_P_H.png)

![Employment](charts/FR_N.png)

![Manuf. GDP](charts/FR_gdp_manufacturing.png)

[Q1–Q20 JSON for France](numbers/FR.json)

## ID — Indonesia

The main impact of bilateral tariffs at 25% on Indonesia would be only a small rise in GDP of 0.03% by Q1. Equities peak at +0.05% in Q1.

Demand and trade. Consumption peaks at +0.02 % vs baseline in Q3, from +0.01 in Q1 to +0.01 in Q20. Investment peaks at +0.08 % vs baseline in Q4, from +0.07 in Q1 to +0.06 in Q20. Net Exports peaks at +0.05 % vs baseline in Q1, from +0.05 in Q1 to +0.04 in Q20. Gov Spending peaks at -0.01 % vs baseline in Q17, from -0.00 in Q1 to -0.01 in Q20. Gov Debt peaks at +0.05 % vs baseline in Q20, from +0.00 in Q1 to +0.05 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Currency Strength peaks at +0.04 % vs baseline in Q15, from +0.01 in Q1 to +0.04 in Q20.

Labour. Employment peaks at +0.03 % vs baseline in Q20, from +0.00 in Q1 to +0.03 in Q20. Unemployment peaks at -0.00 pp in Q20, from -0.00 in Q1 to -0.00 in Q20. Real Wages peaks at +0.03 % vs baseline in Q20, from +0.00 in Q1 to +0.03 in Q20.

Prices. The three-year CPI impulse is -0.03 percentage points. CPI Inflation peaks at -0.00 pp in Q3, from -0.00 in Q1 to +0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q3, from -0.00 in Q1 to +0.00 in Q20. Marginal Cost peaks at +0.02 % vs baseline in Q1, from +0.02 in Q1 to +0.01 in Q20.

Financial conditions. Policy Rate peaks at -0.01 pp (annualized) in Q6, from -0.00 in Q1 to +0.00 in Q20. Govt 2Y Yield peaks at -0.01 pp (annualized) in Q3, from -0.01 in Q1 to +0.01 in Q20. Govt 5Y Yield peaks at +0.01 pp (annualized) in Q20, from -0.01 in Q1 to +0.01 in Q20. Govt 10Y Yield peaks at +0.01 pp (annualized) in Q20, from +0.00 in Q1 to +0.01 in Q20. Bond Price peaks at +0.05 % vs baseline in Q6, from +0.01 in Q1 to -0.01 in Q20. Equity Index peaks at +0.05 % vs baseline in Q1, from +0.05 in Q1 to +0.05 in Q20. Tobin's Q peaks at +0.06 % vs baseline in Q4, from +0.05 in Q1 to +0.04 in Q20. House Prices peaks at +0.04 % vs baseline in Q20, from +0.00 in Q1 to +0.04 in Q20. Bank Credit peaks at +0.00 % vs baseline in Q20, from +0.00 in Q1 to +0.00 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.00 % vs baseline in Q1, from +0.00 in Q1 to +0.00 in Q20. Services GDP peaks at +0.01 % vs baseline in Q1, from +0.01 in Q1 to +0.01 in Q20. Capital Stock peaks at +0.01 % vs baseline in Q20, from +0.00 in Q1 to +0.01 in Q20.

Timing. By Q20 GDP is still +0.02% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/ID_Y.png)

![CPI Inflation](charts/ID_pi_cpi.png)

![Equity Index](charts/ID_equity.png)

![Investment](charts/ID_I.png)

![Tobin's Q](charts/ID_Q.png)

![Bond Price](charts/ID_Q_B.png)

![Net Exports](charts/ID_NX.png)

![Gov Debt](charts/ID_B.png)

![Currency Strength](charts/ID_RER.png)

![House Prices](charts/ID_P_H.png)

![Real Wages](charts/ID_w.png)

![Employment](charts/ID_N.png)

[Q1–Q20 JSON for Indonesia](numbers/ID.json)

## AR — Argentina

The main impact of bilateral tariffs at 25% on Argentina would be no material rise in GDP of 0.03% by Q16. Equities peak at +0.04% in Q14. This has almost no impact on Argentina.

![GDP](charts/AR_Y.png)

![CPI Inflation](charts/AR_pi_cpi.png)

![Equity Index](charts/AR_equity.png)

![Investment](charts/AR_I.png)

![Tobin's Q](charts/AR_Q.png)

![Real Wages](charts/AR_w.png)

![Currency Strength](charts/AR_RER.png)

![Bond Price](charts/AR_Q_B.png)

![House Prices](charts/AR_P_H.png)

![Employment](charts/AR_N.png)

![Gov Debt](charts/AR_B.png)

![Marginal Cost](charts/AR_mc.png)

[Q1–Q20 JSON for Argentina](numbers/AR.json)

## TR — Turkey

The main impact of bilateral tariffs at 25% on Turkey would be no material rise in GDP of 0.02% by Q15. Equities peak at +0.04% in Q14. This has almost no impact on Turkey.

![GDP](charts/TR_Y.png)

![CPI Inflation](charts/TR_pi_cpi.png)

![Equity Index](charts/TR_equity.png)

![Investment](charts/TR_I.png)

![Tobin's Q](charts/TR_Q.png)

![Net Exports](charts/TR_NX.png)

![Bond Price](charts/TR_Q_B.png)

![House Prices](charts/TR_P_H.png)

![Real Wages](charts/TR_w.png)

![Gov Debt](charts/TR_B.png)

![Employment](charts/TR_N.png)

![Manuf. GDP](charts/TR_gdp_manufacturing.png)

[Q1–Q20 JSON for Turkey](numbers/TR.json)

## NG — Nigeria

The main impact of bilateral tariffs at 25% on Nigeria would be no material rise in GDP of 0.02% by Q18. Equities peak at +0.04% in Q16. This has almost no impact on Nigeria.

![GDP](charts/NG_Y.png)

![CPI Inflation](charts/NG_pi_cpi.png)

![Equity Index](charts/NG_equity.png)

![Investment](charts/NG_I.png)

![Gov Debt](charts/NG_B.png)

![Bond Price](charts/NG_Q_B.png)

![Currency Strength](charts/NG_RER.png)

![Tobin's Q](charts/NG_Q.png)

![House Prices](charts/NG_P_H.png)

![Policy Rate](charts/NG_i.png)

![Govt 2Y Yield](charts/NG_y2.png)

![Employment](charts/NG_N.png)

[Q1–Q20 JSON for Nigeria](numbers/NG.json)

## NL — Netherlands

The main impact of bilateral tariffs at 25% on Netherlands would be no material rise in GDP of 0.02% by Q1. Equities peak at +0.05% in Q1. This has almost no impact on Netherlands.

![GDP](charts/NL_Y.png)

![CPI Inflation](charts/NL_pi_cpi.png)

![Equity Index](charts/NL_equity.png)

![Investment](charts/NL_I.png)

![Tobin's Q](charts/NL_Q.png)

![Net Exports](charts/NL_NX.png)

![Bond Price](charts/NL_Q_B.png)

![Currency Strength](charts/NL_RER.png)

![Services GDP](charts/NL_gdp_services.png)

![Marginal Cost](charts/NL_mc.png)

![House Prices](charts/NL_P_H.png)

![Employment](charts/NL_N.png)

[Q1–Q20 JSON for Netherlands](numbers/NL.json)

## ES — Spain

The main impact of bilateral tariffs at 25% on Spain would be no material rise in GDP of 0.02% by Q2. Equities peak at +0.03% in Q2. This has almost no impact on Spain.

![GDP](charts/ES_Y.png)

![CPI Inflation](charts/ES_pi_cpi.png)

![Equity Index](charts/ES_equity.png)

![Investment](charts/ES_I.png)

![Net Exports](charts/ES_NX.png)

![Bond Price](charts/ES_Q_B.png)

![Tobin's Q](charts/ES_Q.png)

![Currency Strength](charts/ES_RER.png)

![Manuf. GDP](charts/ES_gdp_manufacturing.png)

![House Prices](charts/ES_P_H.png)

![Employment](charts/ES_N.png)

![Services GDP](charts/ES_gdp_services.png)

[Q1–Q20 JSON for Spain](numbers/ES.json)

## PL — Poland

The main impact of bilateral tariffs at 25% on Poland would be no material rise in GDP of 0.01% by Q2. Equities peak at +0.03% in Q3. This has almost no impact on Poland.

![GDP](charts/PL_Y.png)

![CPI Inflation](charts/PL_pi_cpi.png)

![Equity Index](charts/PL_equity.png)

![Investment](charts/PL_I.png)

![Bond Price](charts/PL_Q_B.png)

![Net Exports](charts/PL_NX.png)

![Tobin's Q](charts/PL_Q.png)

![Currency Strength](charts/PL_RER.png)

![House Prices](charts/PL_P_H.png)

![Manuf. GDP](charts/PL_gdp_manufacturing.png)

![Employment](charts/PL_N.png)

![Policy Rate](charts/PL_i.png)

[Q1–Q20 JSON for Poland](numbers/PL.json)

## NO — Norway

The main impact of bilateral tariffs at 25% on Norway would be no material rise in GDP of 0.01% by Q1. Equities peak at +0.02% in Q1. This has almost no impact on Norway.

![GDP](charts/NO_Y.png)

![CPI Inflation](charts/NO_pi_cpi.png)

![Equity Index](charts/NO_equity.png)

![Currency Strength](charts/NO_RER.png)

![Net Exports](charts/NO_NX.png)

![Manuf. GDP](charts/NO_gdp_manufacturing.png)

![Bond Price](charts/NO_Q_B.png)

![Investment](charts/NO_I.png)

![Gov Spending](charts/NO_G.png)

![Tobin's Q](charts/NO_Q.png)

![Real Wages](charts/NO_w.png)

![Policy Rate](charts/NO_i.png)

[Q1–Q20 JSON for Norway](numbers/NO.json)

## RU — Russia

The main impact of bilateral tariffs at 25% on Russia would be no material rise in GDP of 0.01% by Q1. Equities peak at +0.02% in Q1. This has almost no impact on Russia.

![GDP](charts/RU_Y.png)

![CPI Inflation](charts/RU_pi_cpi.png)

![Equity Index](charts/RU_equity.png)

![Currency Strength](charts/RU_RER.png)

![Net Exports](charts/RU_NX.png)

![Bond Price](charts/RU_Q_B.png)

![Gov Spending](charts/RU_G.png)

![Investment](charts/RU_I.png)

![Manuf. GDP](charts/RU_gdp_manufacturing.png)

![Tobin's Q](charts/RU_Q.png)

![Policy Rate](charts/RU_i.png)

![Govt 2Y Yield](charts/RU_y2.png)

[Q1–Q20 JSON for Russia](numbers/RU.json)


---

These figures are model IRFs versus baseline, not forecasts, and not financial advice.
