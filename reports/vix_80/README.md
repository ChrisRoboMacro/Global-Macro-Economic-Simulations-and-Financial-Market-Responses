# Global Macro Economic Simulations and Financial Market Responses

v6 · IRF · evaluation

**Open the typeset report (this is the document):** https://robomacro.com/GlobalMacroTrainingDataset/vix_80/

GitHub and Hugging Face show `.html` as source code. That is not the report. Read it on robomacro.com, or keep scrolling this page.

## What's the impact of VIX 80

### Active treatment

```json
{
  "vix": 80.0
}
```

### Assumptions

- Every path is a model impulse response versus baseline, not a forecast.
- The solver and weights are not included.
- English never enters the solver.

### Summary

This report traces the model response to VIX at 80. Every path is an impulse response versus an unchanged baseline — not a forecast and not market data. The question was: What's the impact of VIX 80

Netherlands sees a -2.26% GDP peak at Q1, with CPI -0.30pp over three years and equities -6.31%. Saudi Arabia sees a -2.26% GDP peak at Q1, with CPI -0.58pp over three years and equities -8.98%. Malaysia sees a -2.25% GDP peak at Q1, with CPI -0.16pp over three years and equities -6.03%. Norway sees a -2.22% GDP peak at Q1, with CPI -0.26pp over three years and equities -4.83%.

The remaining countries are smaller spillovers and are covered in the chapters that follow. This material is a model-based summary and is not financial advice.

### Countries by GDP impact

- [NL — Netherlands](#nl--netherlands) · GDP -2.26% Q1
- [SA — Saudi Arabia](#sa--saudi-arabia) · GDP -2.26% Q1
- [MY — Malaysia](#my--malaysia) · GDP -2.25% Q1
- [NO — Norway](#no--norway) · GDP -2.22% Q1
- [MX — Mexico](#mx--mexico) · GDP -2.18% Q1
- [CA — Canada](#ca--canada) · GDP -2.17% Q1
- [TH — Thailand](#th--thailand) · GDP -2.14% Q1
- [CH — Switzerland](#ch--switzerland) · GDP -2.09% Q1
- [PL — Poland](#pl--poland) · GDP -2.08% Q1
- [RU — Russia](#ru--russia) · GDP -2.03% Q1
- [CL — Chile](#cl--chile) · GDP -2.02% Q1
- [DE — Germany](#de--germany) · GDP -2.02% Q1
- [SE — Sweden](#se--sweden) · GDP -2.01% Q1
- [KR — South Korea](#kr--south-korea) · GDP -1.98% Q1
- [FR — France](#fr--france) · GDP -1.98% Q1
- [ES — Spain](#es--spain) · GDP -1.94% Q1
- [AU — Australia](#au--australia) · GDP -1.94% Q1
- [CO — Colombia](#co--colombia) · GDP -1.93% Q1
- [ZA — South Africa](#za--south-africa) · GDP -1.92% Q1
- [NG — Nigeria](#ng--nigeria) · GDP -1.91% Q1
- [IT — Italy](#it--italy) · GDP -1.88% Q1
- [TR — Turkey](#tr--turkey) · GDP -1.87% Q1
- [BR — Brazil](#br--brazil) · GDP -1.87% Q1
- [ID — Indonesia](#id--indonesia) · GDP -1.87% Q1
- [UK — United Kingdom](#uk--united-kingdom) · GDP -1.87% Q1
- [AR — Argentina](#ar--argentina) · GDP -1.84% Q1
- [US — United States](#us--united-states) · GDP -1.82% Q1
- [IN — India](#in--india) · GDP -1.81% Q1
- [CN — China](#cn--china) · GDP -1.79% Q1
- [JP — Japan](#jp--japan) · GDP -1.78% Q1

![NL GDP](charts/global_NL_Y.png)

![SA GDP](charts/global_SA_Y.png)

![MY GDP](charts/global_MY_Y.png)

![NO GDP](charts/global_NO_Y.png)

![US Equity Index](charts/global_US_equity.png)

![US Policy Rate](charts/global_US_i.png)

## NL — Netherlands

The main impact of VIX at 80 on Netherlands would be a large drop in GDP of 2.26% by Q1. Equities peak at -6.31% in Q1.

Demand and trade. Consumption peaks at -3.01 % vs baseline in Q1, from -3.01 in Q1 to -0.21 in Q20. Investment peaks at -11.44 % vs baseline in Q1, from -11.44 in Q1 to -0.99 in Q20. Net Exports peaks at +0.31 % vs baseline in Q1, from +0.31 in Q1 to +0.10 in Q20. Gov Spending peaks at +0.47 % vs baseline in Q1, from +0.47 in Q1 to +0.07 in Q20. Gov Debt peaks at +0.23 % vs baseline in Q12, from +0.06 in Q1 to +0.21 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.26 % vs baseline in Q7, from +0.21 in Q1 to +0.19 in Q20.

Labour. Employment peaks at -0.94 % vs baseline in Q7, from -0.38 in Q1 to -0.50 in Q20. Unemployment peaks at +0.75 pp in Q6, from +0.35 in Q1 to +0.34 in Q20. Real Wages peaks at -1.25 % vs baseline in Q20, from -0.02 in Q1 to -1.25 in Q20.

Prices. The three-year CPI impulse is -0.30 percentage points. CPI Inflation peaks at -0.08 pp in Q2, from -0.06 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.06 pp in Q2, from -0.04 in Q1 to -0.00 in Q20. Marginal Cost peaks at -1.35 % vs baseline in Q1, from -1.35 in Q1 to -0.20 in Q20.

Financial conditions. Policy Rate peaks at -0.20 pp (annualized) in Q5, from -0.06 in Q1 to -0.03 in Q20. Real Rate peaks at -0.05 pp (annualized) in Q5, from -0.01 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -0.20 pp (annualized) in Q5, from -0.06 in Q1 to -0.03 in Q20. Govt 2Y Yield peaks at -0.18 pp (annualized) in Q3, from -0.16 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at -0.11 pp (annualized) in Q1, from -0.11 in Q1 to -0.03 in Q20. Govt 10Y Yield peaks at -0.07 pp (annualized) in Q1, from -0.07 in Q1 to -0.03 in Q20. Govt 30Y Yield peaks at -0.03 pp (annualized) in Q1, from -0.03 in Q1 to -0.01 in Q20. Bond Price (7y) peaks at +1.43 % vs baseline in Q5, from +0.40 in Q1 to +0.20 in Q20. Bond Price 3M peaks at +0.05 % vs baseline in Q5, from +0.01 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +0.34 % vs baseline in Q3, from +0.31 in Q1 to +0.05 in Q20. Bond Price 5Y peaks at +0.50 % vs baseline in Q1, from +0.50 in Q1 to +0.14 in Q20. Bond Price 10Y peaks at +0.58 % vs baseline in Q1, from +0.58 in Q1 to +0.21 in Q20. Bond Price 30Y peaks at +0.54 % vs baseline in Q1, from +0.54 in Q1 to +0.22 in Q20. Equity Index peaks at -6.31 % vs baseline in Q1, from -6.31 in Q1 to -0.92 in Q20. VIX peaks at +80.00 index_level in Q1, from +80.00 in Q1 to +15.57 in Q20. Tobin's Q peaks at -4.37 % vs baseline in Q1, from -4.37 in Q1 to -0.61 in Q20. House Prices peaks at -1.18 % vs baseline in Q13, from -0.29 in Q1 to -1.12 in Q20. Bank Equity peaks at -0.57 % vs baseline in Q8, from -0.19 in Q1 to -0.32 in Q20. Bank Credit peaks at -0.45 % vs baseline in Q8, from -0.15 in Q1 to -0.25 in Q20. Credit Spread peaks at +0.00 pp in Q8, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.18 % vs baseline in Q17, from -0.14 in Q1 to +0.17 in Q20. vs USD peaks at -0.51 % vs baseline in Q16, from +0.41 in Q1 to -0.49 in Q20.

Commodities. Energy Price peaks at +79.86 USD/bbl (level) in Q20, from +77.47 in Q1 to +79.86 in Q20. Metals Price peaks at +99.92 index (level) in Q20, from +97.53 in Q1 to +99.92 in Q20. Food Price peaks at +99.79 index (level) in Q20, from +97.33 in Q1 to +99.79 in Q20. Gas Price peaks at +3.99 USD/mmBtu (level) in Q20, from +3.83 in Q1 to +3.99 in Q20. Copper Price peaks at +99.98 index (level) in Q20, from +98.14 in Q1 to +99.98 in Q20. Wheat Price peaks at +100.00 index (level) in Q18, from +98.47 in Q1 to +99.98 in Q20. Gold Price peaks at +5472.24 USD/oz (level) in Q1, from +5472.24 in Q1 to +2031.95 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.43 % vs baseline in Q1, from -0.43 in Q1 to -0.11 in Q20. Services GDP peaks at -1.69 % vs baseline in Q1, from -1.69 in Q1 to -0.25 in Q20. Capital Stock peaks at -0.20 % vs baseline in Q20, from -0.03 in Q1 to -0.20 in Q20.

Timing. The GDP response has mostly faded by Q12 (Q20 is -0.33%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/NL_Y.png)

![CPI Inflation](charts/NL_pi_cpi.png)

![Equity Index](charts/NL_equity.png)

![Gold Price](charts/NL_P_gold.png)

![Wheat Price](charts/NL_P_wheat.png)

![Copper Price](charts/NL_P_copper.png)

![Metals Price](charts/NL_P_metals.png)

![Food Price](charts/NL_P_food.png)

![VIX](charts/NL_vix.png)

![Energy Price](charts/NL_P_energy.png)

![Investment](charts/NL_I.png)

![Tobin's Q](charts/NL_Q.png)

[Q1–Q20 JSON for Netherlands](numbers/NL.json)

## SA — Saudi Arabia

The main impact of VIX at 80 on Saudi Arabia would be a large drop in GDP of 2.26% by Q1. Equities peak at -8.98% in Q1.

Demand and trade. Consumption peaks at -3.02 % vs baseline in Q1, from -3.02 in Q1 to -0.23 in Q20. Investment peaks at -11.06 % vs baseline in Q1, from -11.06 in Q1 to -1.03 in Q20. Net Exports peaks at -0.79 % vs baseline in Q3, from -0.55 in Q1 to +0.03 in Q20. Gov Spending peaks at -0.11 % vs baseline in Q4, from +0.11 in Q1 to +0.04 in Q20. Gov Debt peaks at -2.14 % vs baseline in Q20, from -0.34 in Q1 to -2.14 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.49 % vs baseline in Q13, from +0.03 in Q1 to +0.39 in Q20.

Labour. Employment peaks at -1.20 % vs baseline in Q5, from -0.52 in Q1 to -0.43 in Q20. Unemployment peaks at +0.49 pp in Q4, from +0.23 in Q1 to +0.17 in Q20. Real Wages peaks at -1.68 % vs baseline in Q20, from -0.02 in Q1 to -1.68 in Q20.

Prices. The three-year CPI impulse is -0.58 percentage points. CPI Inflation peaks at -0.11 pp in Q2, from -0.10 in Q1 to -0.02 in Q20. Domestic Infl. peaks at -0.08 pp in Q2, from -0.07 in Q1 to -0.01 in Q20. Marginal Cost peaks at -1.35 % vs baseline in Q1, from -1.35 in Q1 to -0.19 in Q20.

Financial conditions. Policy Rate peaks at -0.76 pp (annualized) in Q5, from -0.31 in Q1 to +0.01 in Q20. Real Rate peaks at -0.19 pp (annualized) in Q5, from -0.08 in Q1 to +0.00 in Q20. Govt 3M Yield peaks at -0.76 pp (annualized) in Q5, from -0.31 in Q1 to +0.01 in Q20. Govt 2Y Yield peaks at -0.67 pp (annualized) in Q2, from -0.64 in Q1 to +0.02 in Q20. Govt 5Y Yield peaks at -0.38 pp (annualized) in Q1, from -0.38 in Q1 to -0.01 in Q20. Govt 10Y Yield peaks at -0.20 pp (annualized) in Q1, from -0.20 in Q1 to -0.03 in Q20. Govt 30Y Yield peaks at -0.08 pp (annualized) in Q1, from -0.08 in Q1 to -0.02 in Q20. Bond Price (7y) peaks at +3.80 % vs baseline in Q5, from +1.56 in Q1 to -0.07 in Q20. Bond Price 3M peaks at +0.19 % vs baseline in Q5, from +0.08 in Q1 to -0.00 in Q20. Bond Price 2Y peaks at +1.27 % vs baseline in Q2, from +1.22 in Q1 to -0.03 in Q20. Bond Price 5Y peaks at +1.69 % vs baseline in Q1, from +1.69 in Q1 to +0.06 in Q20. Bond Price 10Y peaks at +1.61 % vs baseline in Q1, from +1.61 in Q1 to +0.27 in Q20. Bond Price 30Y peaks at +1.52 % vs baseline in Q1, from +1.52 in Q1 to +0.41 in Q20. Equity Index peaks at -8.98 % vs baseline in Q1, from -8.98 in Q1 to -1.30 in Q20. VIX peaks at +80.00 index_level in Q1, from +80.00 in Q1 to +15.57 in Q20. Tobin's Q peaks at -4.10 % vs baseline in Q1, from -4.10 in Q1 to -0.64 in Q20. House Prices peaks at -1.30 % vs baseline in Q10, from -0.35 in Q1 to -1.08 in Q20. Bank Equity peaks at -0.35 % vs baseline in Q8, from -0.10 in Q1 to -0.19 in Q20. Bank Credit peaks at -0.30 % vs baseline in Q8, from -0.09 in Q1 to -0.16 in Q20. Credit Spread peaks at +0.01 pp in Q8, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.08 % vs baseline in Q9, from -0.04 in Q1 to +0.01 in Q20. vs USD peaks at -0.28 % vs baseline in Q20, from +0.22 in Q1 to -0.28 in Q20.

Commodities. Energy Price peaks at +79.86 USD/bbl (level) in Q20, from +77.47 in Q1 to +79.86 in Q20. Metals Price peaks at +99.92 index (level) in Q20, from +97.53 in Q1 to +99.92 in Q20. Food Price peaks at +99.79 index (level) in Q20, from +97.33 in Q1 to +99.79 in Q20. Gas Price peaks at +3.99 USD/mmBtu (level) in Q20, from +3.83 in Q1 to +3.99 in Q20. Copper Price peaks at +99.98 index (level) in Q20, from +98.14 in Q1 to +99.98 in Q20. Wheat Price peaks at +100.00 index (level) in Q18, from +98.47 in Q1 to +99.98 in Q20. Gold Price peaks at +5472.24 USD/oz (level) in Q1, from +5472.24 in Q1 to +2031.95 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.31 % vs baseline in Q1, from -0.31 in Q1 to -0.16 in Q20. Services GDP peaks at -0.99 % vs baseline in Q1, from -0.99 in Q1 to -0.14 in Q20. Capital Stock peaks at -0.17 % vs baseline in Q20, from -0.03 in Q1 to -0.17 in Q20.

Timing. The GDP response has mostly faded by Q12 (Q20 is -0.32%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/SA_Y.png)

![CPI Inflation](charts/SA_pi_cpi.png)

![Equity Index](charts/SA_equity.png)

![Gold Price](charts/SA_P_gold.png)

![Wheat Price](charts/SA_P_wheat.png)

![Copper Price](charts/SA_P_copper.png)

![Metals Price](charts/SA_P_metals.png)

![Food Price](charts/SA_P_food.png)

![VIX](charts/SA_vix.png)

![Energy Price](charts/SA_P_energy.png)

![Investment](charts/SA_I.png)

![Tobin's Q](charts/SA_Q.png)

[Q1–Q20 JSON for Saudi Arabia](numbers/SA.json)

## MY — Malaysia

The main impact of VIX at 80 on Malaysia would be a large drop in GDP of 2.25% by Q1. Equities peak at -6.03% in Q1.

Demand and trade. Consumption peaks at -3.19 % vs baseline in Q1, from -3.19 in Q1 to -0.18 in Q20. Investment peaks at -11.26 % vs baseline in Q1, from -11.26 in Q1 to -0.59 in Q20. Net Exports peaks at +0.32 % vs baseline in Q1, from +0.32 in Q1 to +0.15 in Q20. Gov Spending peaks at +0.34 % vs baseline in Q1, from +0.34 in Q1 to +0.04 in Q20. Gov Debt peaks at -1.54 % vs baseline in Q12, from -0.39 in Q1 to -1.41 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.54 % vs baseline in Q4, from +0.37 in Q1 to +0.39 in Q20.

Labour. Employment peaks at -1.02 % vs baseline in Q5, from -0.49 in Q1 to -0.31 in Q20. Unemployment peaks at +0.28 pp in Q4, from +0.15 in Q1 to +0.07 in Q20. Real Wages peaks at -1.42 % vs baseline in Q20, from -0.03 in Q1 to -1.42 in Q20.

Prices. The three-year CPI impulse is -0.16 percentage points. CPI Inflation peaks at -0.08 pp in Q2, from -0.07 in Q1 to -0.01 in Q20. Domestic Infl. peaks at -0.06 pp in Q2, from -0.05 in Q1 to -0.00 in Q20. Marginal Cost peaks at -1.35 % vs baseline in Q1, from -1.35 in Q1 to -0.14 in Q20.

Financial conditions. Policy Rate peaks at -0.39 pp (annualized) in Q5, from -0.16 in Q1 to -0.11 in Q20. Real Rate peaks at -0.10 pp (annualized) in Q5, from -0.04 in Q1 to -0.03 in Q20. Govt 3M Yield peaks at -0.39 pp (annualized) in Q5, from -0.16 in Q1 to -0.11 in Q20. Govt 2Y Yield peaks at -0.35 pp (annualized) in Q2, from -0.33 in Q1 to -0.10 in Q20. Govt 5Y Yield peaks at -0.24 pp (annualized) in Q1, from -0.24 in Q1 to -0.10 in Q20. Govt 10Y Yield peaks at -0.17 pp (annualized) in Q1, from -0.17 in Q1 to -0.08 in Q20. Govt 30Y Yield peaks at -0.08 pp (annualized) in Q1, from -0.08 in Q1 to -0.04 in Q20. Bond Price (7y) peaks at +1.61 % vs baseline in Q5, from +0.66 in Q1 to +0.45 in Q20. Bond Price 3M peaks at +0.10 % vs baseline in Q5, from +0.04 in Q1 to +0.03 in Q20. Bond Price 2Y peaks at +0.66 % vs baseline in Q2, from +0.63 in Q1 to +0.20 in Q20. Bond Price 5Y peaks at +1.08 % vs baseline in Q1, from +1.08 in Q1 to +0.44 in Q20. Bond Price 10Y peaks at +1.39 % vs baseline in Q1, from +1.39 in Q1 to +0.68 in Q20. Bond Price 30Y peaks at +1.41 % vs baseline in Q1, from +1.41 in Q1 to +0.72 in Q20. Equity Index peaks at -6.03 % vs baseline in Q1, from -6.03 in Q1 to -0.60 in Q20. VIX peaks at +80.00 index_level in Q1, from +80.00 in Q1 to +15.57 in Q20. Tobin's Q peaks at -4.24 % vs baseline in Q1, from -4.24 in Q1 to -0.33 in Q20. House Prices peaks at -1.32 % vs baseline in Q10, from -0.41 in Q1 to -1.01 in Q20. Bank Equity peaks at -0.34 % vs baseline in Q7, from -0.12 in Q1 to -0.18 in Q20. Bank Credit peaks at -0.27 % vs baseline in Q7, from -0.09 in Q1 to -0.14 in Q20. Credit Spread peaks at +0.00 pp in Q7, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.41 % vs baseline in Q2, from -0.34 in Q1 to +0.04 in Q20. vs USD peaks at +0.57 % vs baseline in Q1, from +0.57 in Q1 to -0.29 in Q20.

Commodities. Energy Price peaks at +79.86 USD/bbl (level) in Q20, from +77.47 in Q1 to +79.86 in Q20. Metals Price peaks at +99.92 index (level) in Q20, from +97.53 in Q1 to +99.92 in Q20. Food Price peaks at +99.79 index (level) in Q20, from +97.33 in Q1 to +99.79 in Q20. Gas Price peaks at +3.99 USD/mmBtu (level) in Q20, from +3.83 in Q1 to +3.99 in Q20. Copper Price peaks at +99.98 index (level) in Q20, from +98.14 in Q1 to +99.98 in Q20. Wheat Price peaks at +100.00 index (level) in Q18, from +98.47 in Q1 to +99.98 in Q20. Gold Price peaks at +5472.24 USD/oz (level) in Q1, from +5472.24 in Q1 to +2031.95 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.67 % vs baseline in Q1, from -0.67 in Q1 to -0.18 in Q20. Services GDP peaks at -1.29 % vs baseline in Q1, from -1.29 in Q1 to -0.13 in Q20. Capital Stock peaks at -0.15 % vs baseline in Q20, from -0.03 in Q1 to -0.15 in Q20.

Timing. The GDP response has mostly faded by Q10 (Q20 is -0.23%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/MY_Y.png)

![CPI Inflation](charts/MY_pi_cpi.png)

![Equity Index](charts/MY_equity.png)

![Gold Price](charts/MY_P_gold.png)

![Wheat Price](charts/MY_P_wheat.png)

![Copper Price](charts/MY_P_copper.png)

![Metals Price](charts/MY_P_metals.png)

![Food Price](charts/MY_P_food.png)

![VIX](charts/MY_vix.png)

![Energy Price](charts/MY_P_energy.png)

![Investment](charts/MY_I.png)

![Tobin's Q](charts/MY_Q.png)

[Q1–Q20 JSON for Malaysia](numbers/MY.json)

## NO — Norway

The main impact of VIX at 80 on Norway would be a large drop in GDP of 2.22% by Q1. Equities peak at -4.83% in Q1.

Demand and trade. Consumption peaks at -2.97 % vs baseline in Q1, from -2.97 in Q1 to -0.16 in Q20. Investment peaks at -11.07 % vs baseline in Q1, from -11.07 in Q1 to -0.44 in Q20. Net Exports peaks at -0.44 % vs baseline in Q3, from -0.26 in Q1 to +0.10 in Q20. Gov Spending peaks at +0.26 % vs baseline in Q1, from +0.26 in Q1 to +0.04 in Q20. Gov Debt peaks at +0.30 % vs baseline in Q11, from +0.07 in Q1 to +0.25 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +1.62 % vs baseline in Q3, from +1.16 in Q1 to +0.73 in Q20.

Labour. Employment peaks at -1.01 % vs baseline in Q6, from -0.41 in Q1 to -0.39 in Q20. Unemployment peaks at +0.78 pp in Q6, from +0.34 in Q1 to +0.28 in Q20. Real Wages peaks at -1.22 % vs baseline in Q20, from -0.02 in Q1 to -1.22 in Q20.

Prices. The three-year CPI impulse is -0.26 percentage points. CPI Inflation peaks at -0.08 pp in Q2, from -0.07 in Q1 to -0.01 in Q20. Domestic Infl. peaks at -0.06 pp in Q2, from -0.05 in Q1 to -0.00 in Q20. Marginal Cost peaks at -1.33 % vs baseline in Q1, from -1.33 in Q1 to -0.14 in Q20.

Financial conditions. Policy Rate peaks at -0.62 pp (annualized) in Q6, from -0.23 in Q1 to -0.22 in Q20. Real Rate peaks at -0.16 pp (annualized) in Q6, from -0.06 in Q1 to -0.06 in Q20. Govt 3M Yield peaks at -0.62 pp (annualized) in Q6, from -0.23 in Q1 to -0.22 in Q20. Govt 2Y Yield peaks at -0.58 pp (annualized) in Q3, from -0.53 in Q1 to -0.20 in Q20. Govt 5Y Yield peaks at -0.43 pp (annualized) in Q1, from -0.43 in Q1 to -0.18 in Q20. Govt 10Y Yield peaks at -0.30 pp (annualized) in Q1, from -0.30 in Q1 to -0.15 in Q20. Govt 30Y Yield peaks at -0.14 pp (annualized) in Q1, from -0.14 in Q1 to -0.07 in Q20. Bond Price (7y) peaks at +3.89 % vs baseline in Q6, from +1.46 in Q1 to +1.38 in Q20. Bond Price 3M peaks at +0.16 % vs baseline in Q6, from +0.06 in Q1 to +0.06 in Q20. Bond Price 2Y peaks at +1.11 % vs baseline in Q3, from +1.01 in Q1 to +0.37 in Q20. Bond Price 5Y peaks at +1.93 % vs baseline in Q1, from +1.93 in Q1 to +0.80 in Q20. Bond Price 10Y peaks at +2.47 % vs baseline in Q1, from +2.47 in Q1 to +1.23 in Q20. Bond Price 30Y peaks at +2.54 % vs baseline in Q1, from +2.54 in Q1 to +1.32 in Q20. Equity Index peaks at -4.83 % vs baseline in Q1, from -4.83 in Q1 to -0.47 in Q20. VIX peaks at +80.00 index_level in Q1, from +80.00 in Q1 to +15.57 in Q20. Tobin's Q peaks at -4.11 % vs baseline in Q1, from -4.11 in Q1 to -0.23 in Q20. House Prices peaks at -1.00 % vs baseline in Q11, from -0.25 in Q1 to -0.86 in Q20. Bank Equity peaks at -0.46 % vs baseline in Q8, from -0.14 in Q1 to -0.25 in Q20. Bank Credit peaks at -0.36 % vs baseline in Q8, from -0.11 in Q1 to -0.20 in Q20. Credit Spread peaks at +0.00 pp in Q8, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -1.46 % vs baseline in Q3, from -1.08 in Q1 to -0.43 in Q20. vs USD peaks at +1.62 % vs baseline in Q2, from +1.36 in Q1 to +0.06 in Q20.

Commodities. Energy Price peaks at +79.86 USD/bbl (level) in Q20, from +77.47 in Q1 to +79.86 in Q20. Metals Price peaks at +99.92 index (level) in Q20, from +97.53 in Q1 to +99.92 in Q20. Food Price peaks at +99.79 index (level) in Q20, from +97.33 in Q1 to +99.79 in Q20. Gas Price peaks at +3.99 USD/mmBtu (level) in Q20, from +3.83 in Q1 to +3.99 in Q20. Copper Price peaks at +99.98 index (level) in Q20, from +98.14 in Q1 to +99.98 in Q20. Wheat Price peaks at +100.00 index (level) in Q18, from +98.47 in Q1 to +99.98 in Q20. Gold Price peaks at +5472.24 USD/oz (level) in Q1, from +5472.24 in Q1 to +2031.95 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.75 % vs baseline in Q2, from -0.70 in Q1 to -0.26 in Q20. Services GDP peaks at -1.27 % vs baseline in Q1, from -1.27 in Q1 to -0.14 in Q20. Capital Stock peaks at -0.14 % vs baseline in Q20, from -0.03 in Q1 to -0.14 in Q20.

Timing. The GDP response has mostly faded by Q11 (Q20 is -0.24%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/NO_Y.png)

![CPI Inflation](charts/NO_pi_cpi.png)

![Equity Index](charts/NO_equity.png)

![Gold Price](charts/NO_P_gold.png)

![Wheat Price](charts/NO_P_wheat.png)

![Copper Price](charts/NO_P_copper.png)

![Metals Price](charts/NO_P_metals.png)

![Food Price](charts/NO_P_food.png)

![VIX](charts/NO_vix.png)

![Energy Price](charts/NO_P_energy.png)

![Investment](charts/NO_I.png)

![Tobin's Q](charts/NO_Q.png)

[Q1–Q20 JSON for Norway](numbers/NO.json)

## MX — Mexico

The main impact of VIX at 80 on Mexico would be a large drop in GDP of 2.18% by Q1. Equities peak at -3.86% in Q1.

Demand and trade. Consumption peaks at -2.95 % vs baseline in Q1, from -2.95 in Q1 to -0.10 in Q20. Investment peaks at -11.02 % vs baseline in Q1, from -11.02 in Q1 to -0.54 in Q20. Net Exports peaks at +0.18 % vs baseline in Q1, from +0.18 in Q1 to +0.07 in Q20. Gov Spending peaks at +0.34 % vs baseline in Q1, from +0.34 in Q1 to +0.02 in Q20. Gov Debt peaks at -1.20 % vs baseline in Q9, from -0.34 in Q1 to -0.93 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +1.11 % vs baseline in Q3, from +0.86 in Q1 to +0.32 in Q20.

Labour. Employment peaks at -0.87 % vs baseline in Q6, from -0.39 in Q1 to -0.20 in Q20. Unemployment peaks at +0.11 pp in Q3, from +0.07 in Q1 to +0.02 in Q20. Real Wages peaks at -1.35 % vs baseline in Q18, from -0.03 in Q1 to -1.34 in Q20.

Prices. The three-year CPI impulse is -0.45 percentage points. CPI Inflation peaks at -0.12 pp in Q2, from -0.07 in Q1 to -0.01 in Q20. Domestic Infl. peaks at -0.08 pp in Q2, from -0.05 in Q1 to -0.01 in Q20. Marginal Cost peaks at -1.30 % vs baseline in Q1, from -1.30 in Q1 to -0.09 in Q20.

Financial conditions. Policy Rate peaks at -0.50 pp (annualized) in Q4, from -0.18 in Q1 to -0.01 in Q20. Real Rate peaks at -0.12 pp (annualized) in Q4, from -0.04 in Q1 to -0.00 in Q20. Govt 3M Yield peaks at -0.50 pp (annualized) in Q4, from -0.18 in Q1 to -0.01 in Q20. Govt 2Y Yield peaks at -0.38 pp (annualized) in Q2, from -0.38 in Q1 to -0.04 in Q20. Govt 5Y Yield peaks at -0.18 pp (annualized) in Q1, from -0.18 in Q1 to -0.06 in Q20. Govt 10Y Yield peaks at -0.12 pp (annualized) in Q1, from -0.12 in Q1 to -0.05 in Q20. Govt 30Y Yield peaks at -0.05 pp (annualized) in Q1, from -0.05 in Q1 to -0.02 in Q20. Bond Price (7y) peaks at +2.06 % vs baseline in Q4, from +0.74 in Q1 to +0.03 in Q20. Bond Price 3M peaks at +0.12 % vs baseline in Q4, from +0.04 in Q1 to +0.00 in Q20. Bond Price 2Y peaks at +0.73 % vs baseline in Q2, from +0.72 in Q1 to +0.07 in Q20. Bond Price 5Y peaks at +0.81 % vs baseline in Q1, from +0.81 in Q1 to +0.26 in Q20. Bond Price 10Y peaks at +0.99 % vs baseline in Q1, from +0.99 in Q1 to +0.42 in Q20. Bond Price 30Y peaks at +0.97 % vs baseline in Q1, from +0.97 in Q1 to +0.44 in Q20. Equity Index peaks at -3.86 % vs baseline in Q1, from -3.86 in Q1 to -0.28 in Q20. VIX peaks at +80.00 index_level in Q1, from +80.00 in Q1 to +15.57 in Q20. Tobin's Q peaks at -4.08 % vs baseline in Q1, from -4.08 in Q1 to -0.30 in Q20. House Prices peaks at -1.09 % vs baseline in Q8, from -0.36 in Q1 to -0.72 in Q20. Bank Equity peaks at -0.30 % vs baseline in Q7, from -0.10 in Q1 to -0.15 in Q20. Bank Credit peaks at -0.29 % vs baseline in Q7, from -0.10 in Q1 to -0.15 in Q20. Credit Spread peaks at +0.02 pp in Q7, from +0.01 in Q1 to +0.01 in Q20.

Nominal FX. NEER peaks at -1.06 % vs baseline in Q2, from -0.93 in Q1 to +0.22 in Q20. vs USD peaks at +1.14 % vs baseline in Q2, from +1.06 in Q1 to -0.35 in Q20.

Commodities. Energy Price peaks at +79.86 USD/bbl (level) in Q20, from +77.47 in Q1 to +79.86 in Q20. Metals Price peaks at +99.92 index (level) in Q20, from +97.53 in Q1 to +99.92 in Q20. Food Price peaks at +99.79 index (level) in Q20, from +97.33 in Q1 to +99.79 in Q20. Gas Price peaks at +3.99 USD/mmBtu (level) in Q20, from +3.83 in Q1 to +3.99 in Q20. Copper Price peaks at +99.98 index (level) in Q20, from +98.14 in Q1 to +99.98 in Q20. Wheat Price peaks at +100.00 index (level) in Q18, from +98.47 in Q1 to +99.98 in Q20. Gold Price peaks at +5472.24 USD/oz (level) in Q1, from +5472.24 in Q1 to +2031.95 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.74 % vs baseline in Q1, from -0.74 in Q1 to -0.13 in Q20. Services GDP peaks at -1.32 % vs baseline in Q1, from -1.32 in Q1 to -0.09 in Q20. Capital Stock peaks at -0.13 % vs baseline in Q20, from -0.03 in Q1 to -0.13 in Q20.

Timing. The GDP response has mostly faded by Q9 (Q20 is -0.15%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/MX_Y.png)

![CPI Inflation](charts/MX_pi_cpi.png)

![Equity Index](charts/MX_equity.png)

![Gold Price](charts/MX_P_gold.png)

![Wheat Price](charts/MX_P_wheat.png)

![Copper Price](charts/MX_P_copper.png)

![Metals Price](charts/MX_P_metals.png)

![Food Price](charts/MX_P_food.png)

![VIX](charts/MX_vix.png)

![Energy Price](charts/MX_P_energy.png)

![Investment](charts/MX_I.png)

![Tobin's Q](charts/MX_Q.png)

[Q1–Q20 JSON for Mexico](numbers/MX.json)

## CA — Canada

The main impact of VIX at 80 on Canada would be a large drop in GDP of 2.17% by Q1. Equities peak at -5.58% in Q1.

Demand and trade. Consumption peaks at -3.05 % vs baseline in Q1, from -3.05 in Q1 to -0.12 in Q20. Investment peaks at -10.86 % vs baseline in Q1, from -10.86 in Q1 to -0.37 in Q20. Net Exports peaks at -0.12 % vs baseline in Q3, from -0.00 in Q1 to +0.10 in Q20. Gov Spending peaks at +0.38 % vs baseline in Q1, from +0.38 in Q1 to +0.03 in Q20. Gov Debt peaks at -0.20 % vs baseline in Q10, from -0.05 in Q1 to -0.15 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +1.71 % vs baseline in Q3, from +1.22 in Q1 to +0.68 in Q20.

Labour. Employment peaks at -1.21 % vs baseline in Q4, from -0.64 in Q1 to -0.16 in Q20. Unemployment peaks at +0.72 pp in Q5, from +0.34 in Q1 to +0.20 in Q20. Real Wages peaks at -1.10 % vs baseline in Q20, from -0.02 in Q1 to -1.10 in Q20.

Prices. The three-year CPI impulse is -0.12 percentage points. CPI Inflation peaks at -0.06 pp in Q2, from -0.06 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.04 pp in Q2, from -0.04 in Q1 to -0.00 in Q20. Marginal Cost peaks at -1.30 % vs baseline in Q1, from -1.30 in Q1 to -0.09 in Q20.

Financial conditions. Policy Rate peaks at -0.65 pp (annualized) in Q4, from -0.28 in Q1 to -0.13 in Q20. Real Rate peaks at -0.16 pp (annualized) in Q4, from -0.07 in Q1 to -0.03 in Q20. Govt 3M Yield peaks at -0.65 pp (annualized) in Q4, from -0.28 in Q1 to -0.13 in Q20. Govt 2Y Yield peaks at -0.58 pp (annualized) in Q2, from -0.55 in Q1 to -0.12 in Q20. Govt 5Y Yield peaks at -0.37 pp (annualized) in Q1, from -0.37 in Q1 to -0.13 in Q20. Govt 10Y Yield peaks at -0.25 pp (annualized) in Q1, from -0.25 in Q1 to -0.12 in Q20. Govt 30Y Yield peaks at -0.12 pp (annualized) in Q1, from -0.12 in Q1 to -0.06 in Q20. Bond Price (7y) peaks at +3.86 % vs baseline in Q4, from +1.67 in Q1 to +0.75 in Q20. Bond Price 3M peaks at +0.16 % vs baseline in Q4, from +0.07 in Q1 to +0.03 in Q20. Bond Price 2Y peaks at +1.10 % vs baseline in Q2, from +1.05 in Q1 to +0.24 in Q20. Bond Price 5Y peaks at +1.69 % vs baseline in Q1, from +1.69 in Q1 to +0.59 in Q20. Bond Price 10Y peaks at +2.07 % vs baseline in Q1, from +2.07 in Q1 to +0.95 in Q20. Bond Price 30Y peaks at +2.12 % vs baseline in Q1, from +2.12 in Q1 to +1.03 in Q20. Equity Index peaks at -5.58 % vs baseline in Q1, from -5.58 in Q1 to -0.38 in Q20. VIX peaks at +80.00 index_level in Q1, from +80.00 in Q1 to +15.57 in Q20. Tobin's Q peaks at -3.96 % vs baseline in Q1, from -3.96 in Q1 to -0.18 in Q20. House Prices peaks at -0.88 % vs baseline in Q10, from -0.25 in Q1 to -0.70 in Q20. Bank Equity peaks at -0.39 % vs baseline in Q8, from -0.13 in Q1 to -0.20 in Q20. Bank Credit peaks at -0.31 % vs baseline in Q8, from -0.10 in Q1 to -0.16 in Q20. Credit Spread peaks at +0.00 pp in Q8, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -1.60 % vs baseline in Q2, from -1.28 in Q1 to -0.14 in Q20. vs USD peaks at +1.70 % vs baseline in Q2, from +1.42 in Q1 to +0.00 in Q20.

Commodities. Energy Price peaks at +79.86 USD/bbl (level) in Q20, from +77.47 in Q1 to +79.86 in Q20. Metals Price peaks at +99.92 index (level) in Q20, from +97.53 in Q1 to +99.92 in Q20. Food Price peaks at +99.79 index (level) in Q20, from +97.33 in Q1 to +99.79 in Q20. Gas Price peaks at +3.99 USD/mmBtu (level) in Q20, from +3.83 in Q1 to +3.99 in Q20. Copper Price peaks at +99.98 index (level) in Q20, from +98.14 in Q1 to +99.98 in Q20. Wheat Price peaks at +100.00 index (level) in Q18, from +98.47 in Q1 to +99.98 in Q20. Gold Price peaks at +5472.24 USD/oz (level) in Q1, from +5472.24 in Q1 to +2031.95 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.75 % vs baseline in Q2, from -0.71 in Q1 to -0.23 in Q20. Services GDP peaks at -1.51 % vs baseline in Q1, from -1.51 in Q1 to -0.11 in Q20. Capital Stock peaks at -0.12 % vs baseline in Q20, from -0.03 in Q1 to -0.12 in Q20.

Timing. The GDP response has mostly faded by Q10 (Q20 is -0.16%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/CA_Y.png)

![CPI Inflation](charts/CA_pi_cpi.png)

![Equity Index](charts/CA_equity.png)

![Gold Price](charts/CA_P_gold.png)

![Wheat Price](charts/CA_P_wheat.png)

![Copper Price](charts/CA_P_copper.png)

![Metals Price](charts/CA_P_metals.png)

![Food Price](charts/CA_P_food.png)

![VIX](charts/CA_vix.png)

![Energy Price](charts/CA_P_energy.png)

![Investment](charts/CA_I.png)

![Gas Price](charts/CA_P_gas.png)

[Q1–Q20 JSON for Canada](numbers/CA.json)

## TH — Thailand

The main impact of VIX at 80 on Thailand would be a large drop in GDP of 2.14% by Q1. Equities peak at -5.31% in Q1.

Demand and trade. Consumption peaks at -3.03 % vs baseline in Q1, from -3.03 in Q1 to -0.13 in Q20. Investment peaks at -10.92 % vs baseline in Q1, from -10.92 in Q1 to -0.49 in Q20. Net Exports peaks at +0.24 % vs baseline in Q1, from +0.24 in Q1 to +0.11 in Q20. Gov Spending peaks at +0.36 % vs baseline in Q1, from +0.36 in Q1 to +0.03 in Q20. Gov Debt peaks at -1.24 % vs baseline in Q10, from -0.36 in Q1 to -1.00 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.46 % vs baseline in Q13, from +0.06 in Q1 to +0.40 in Q20.

Labour. Employment peaks at -1.00 % vs baseline in Q4, from -0.50 in Q1 to -0.21 in Q20. Unemployment peaks at +0.11 pp in Q3, from +0.07 in Q1 to +0.02 in Q20. Real Wages peaks at -1.34 % vs baseline in Q18, from -0.03 in Q1 to -1.32 in Q20.

Prices. The three-year CPI impulse is -0.29 percentage points. CPI Inflation peaks at -0.12 pp in Q2, from -0.11 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.08 pp in Q2, from -0.07 in Q1 to -0.00 in Q20. Marginal Cost peaks at -1.28 % vs baseline in Q1, from -1.28 in Q1 to -0.10 in Q20.

Financial conditions. Policy Rate peaks at -0.46 pp (annualized) in Q4, from -0.18 in Q1 to -0.07 in Q20. Real Rate peaks at -0.12 pp (annualized) in Q4, from -0.05 in Q1 to -0.02 in Q20. Govt 3M Yield peaks at -0.46 pp (annualized) in Q4, from -0.18 in Q1 to -0.07 in Q20. Govt 2Y Yield peaks at -0.41 pp (annualized) in Q2, from -0.39 in Q1 to -0.08 in Q20. Govt 5Y Yield peaks at -0.25 pp (annualized) in Q1, from -0.25 in Q1 to -0.08 in Q20. Govt 10Y Yield peaks at -0.17 pp (annualized) in Q1, from -0.17 in Q1 to -0.07 in Q20. Govt 30Y Yield peaks at -0.08 pp (annualized) in Q1, from -0.08 in Q1 to -0.04 in Q20. Bond Price (7y) peaks at +1.93 % vs baseline in Q4, from +0.77 in Q1 to +0.30 in Q20. Bond Price 3M peaks at +0.12 % vs baseline in Q4, from +0.05 in Q1 to +0.02 in Q20. Bond Price 2Y peaks at +0.77 % vs baseline in Q2, from +0.74 in Q1 to +0.14 in Q20. Bond Price 5Y peaks at +1.14 % vs baseline in Q1, from +1.14 in Q1 to +0.37 in Q20. Bond Price 10Y peaks at +1.38 % vs baseline in Q1, from +1.38 in Q1 to +0.60 in Q20. Bond Price 30Y peaks at +1.37 % vs baseline in Q1, from +1.37 in Q1 to +0.64 in Q20. Equity Index peaks at -5.31 % vs baseline in Q1, from -5.31 in Q1 to -0.42 in Q20. VIX peaks at +80.00 index_level in Q1, from +80.00 in Q1 to +15.57 in Q20. Tobin's Q peaks at -4.00 % vs baseline in Q1, from -4.00 in Q1 to -0.26 in Q20. House Prices peaks at -1.15 % vs baseline in Q9, from -0.37 in Q1 to -0.83 in Q20. Bank Equity peaks at -0.28 % vs baseline in Q7, from -0.10 in Q1 to -0.15 in Q20. Bank Credit peaks at -0.23 % vs baseline in Q7, from -0.08 in Q1 to -0.12 in Q20. Credit Spread peaks at +0.00 pp in Q7, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.08 % vs baseline in Q7, from -0.08 in Q1 to -0.01 in Q20. vs USD peaks at -0.28 % vs baseline in Q18, from +0.26 in Q1 to -0.27 in Q20.

Commodities. Energy Price peaks at +79.86 USD/bbl (level) in Q20, from +77.47 in Q1 to +79.86 in Q20. Metals Price peaks at +99.92 index (level) in Q20, from +97.53 in Q1 to +99.92 in Q20. Food Price peaks at +99.79 index (level) in Q20, from +97.33 in Q1 to +99.79 in Q20. Gas Price peaks at +3.99 USD/mmBtu (level) in Q20, from +3.83 in Q1 to +3.99 in Q20. Copper Price peaks at +99.98 index (level) in Q20, from +98.14 in Q1 to +99.98 in Q20. Wheat Price peaks at +100.00 index (level) in Q18, from +98.47 in Q1 to +99.98 in Q20. Gold Price peaks at +5472.24 USD/oz (level) in Q1, from +5472.24 in Q1 to +2031.95 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.59 % vs baseline in Q1, from -0.59 in Q1 to -0.17 in Q20. Services GDP peaks at -1.18 % vs baseline in Q1, from -1.18 in Q1 to -0.10 in Q20. Capital Stock peaks at -0.13 % vs baseline in Q20, from -0.03 in Q1 to -0.13 in Q20.

Timing. The GDP response has mostly faded by Q10 (Q20 is -0.17%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/TH_Y.png)

![CPI Inflation](charts/TH_pi_cpi.png)

![Equity Index](charts/TH_equity.png)

![Gold Price](charts/TH_P_gold.png)

![Wheat Price](charts/TH_P_wheat.png)

![Copper Price](charts/TH_P_copper.png)

![Metals Price](charts/TH_P_metals.png)

![Food Price](charts/TH_P_food.png)

![VIX](charts/TH_vix.png)

![Energy Price](charts/TH_P_energy.png)

![Investment](charts/TH_I.png)

![Tobin's Q](charts/TH_Q.png)

[Q1–Q20 JSON for Thailand](numbers/TH.json)

## CH — Switzerland

The main impact of VIX at 80 on Switzerland would be a large drop in GDP of 2.09% by Q1. Equities peak at -8.34% in Q1.

Demand and trade. Consumption peaks at -3.11 % vs baseline in Q1, from -3.11 in Q1 to -0.22 in Q20. Investment peaks at -10.90 % vs baseline in Q1, from -10.90 in Q1 to -0.68 in Q20. Net Exports peaks at +0.21 % vs baseline in Q1, from +0.21 in Q1 to +0.10 in Q20. Gov Spending peaks at +0.42 % vs baseline in Q1, from +0.42 in Q1 to +0.06 in Q20. Gov Debt peaks at -0.49 % vs baseline in Q10, from -0.14 in Q1 to -0.39 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -0.45 % vs baseline in Q1, from -0.45 in Q1 to +0.29 in Q20.

Labour. Employment peaks at -1.06 % vs baseline in Q4, from -0.54 in Q1 to -0.37 in Q20. Unemployment peaks at +0.71 pp in Q6, from +0.32 in Q1 to +0.31 in Q20. Real Wages peaks at -0.76 % vs baseline in Q20, from -0.01 in Q1 to -0.76 in Q20.

Prices. The three-year CPI impulse is -0.20 percentage points. CPI Inflation peaks at -0.12 pp in Q1, from -0.12 in Q1 to +0.00 in Q20. Domestic Infl. peaks at -0.08 pp in Q1, from -0.08 in Q1 to +0.00 in Q20. Marginal Cost peaks at -1.25 % vs baseline in Q1, from -1.25 in Q1 to -0.17 in Q20.

Financial conditions. Policy Rate peaks at -0.27 pp (annualized) in Q7, from -0.10 in Q1 to -0.14 in Q20. Real Rate peaks at -0.07 pp (annualized) in Q7, from -0.03 in Q1 to -0.04 in Q20. Govt 3M Yield peaks at -0.27 pp (annualized) in Q7, from -0.10 in Q1 to -0.14 in Q20. Govt 2Y Yield peaks at -0.26 pp (annualized) in Q4, from -0.23 in Q1 to -0.13 in Q20. Govt 5Y Yield peaks at -0.21 pp (annualized) in Q2, from -0.21 in Q1 to -0.11 in Q20. Govt 10Y Yield peaks at -0.16 pp (annualized) in Q1, from -0.16 in Q1 to -0.09 in Q20. Govt 30Y Yield peaks at -0.07 pp (annualized) in Q1, from -0.07 in Q1 to -0.04 in Q20. Bond Price (7y) peaks at +1.92 % vs baseline in Q7, from +0.73 in Q1 to +1.01 in Q20. Bond Price 3M peaks at +0.07 % vs baseline in Q7, from +0.03 in Q1 to +0.04 in Q20. Bond Price 2Y peaks at +0.50 % vs baseline in Q4, from +0.44 in Q1 to +0.24 in Q20. Bond Price 5Y peaks at +0.96 % vs baseline in Q2, from +0.95 in Q1 to +0.49 in Q20. Bond Price 10Y peaks at +1.30 % vs baseline in Q1, from +1.30 in Q1 to +0.70 in Q20. Bond Price 30Y peaks at +1.31 % vs baseline in Q1, from +1.31 in Q1 to +0.72 in Q20. Equity Index peaks at -8.34 % vs baseline in Q1, from -8.34 in Q1 to -1.11 in Q20. VIX peaks at +80.00 index_level in Q1, from +80.00 in Q1 to +15.57 in Q20. Tobin's Q peaks at -3.99 % vs baseline in Q1, from -3.99 in Q1 to -0.39 in Q20. House Prices peaks at -1.03 % vs baseline in Q13, from -0.25 in Q1 to -0.95 in Q20. Bank Equity peaks at -0.52 % vs baseline in Q8, from -0.17 in Q1 to -0.30 in Q20. Bank Credit peaks at -0.41 % vs baseline in Q8, from -0.13 in Q1 to -0.23 in Q20. Credit Spread peaks at +0.00 pp in Q8, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.51 % vs baseline in Q1, from +0.51 in Q1 to +0.02 in Q20. vs USD peaks at -0.51 % vs baseline in Q10, from -0.25 in Q1 to -0.38 in Q20.

Commodities. Energy Price peaks at +79.86 USD/bbl (level) in Q20, from +77.47 in Q1 to +79.86 in Q20. Metals Price peaks at +99.92 index (level) in Q20, from +97.53 in Q1 to +99.92 in Q20. Food Price peaks at +99.79 index (level) in Q20, from +97.33 in Q1 to +99.79 in Q20. Gas Price peaks at +3.99 USD/mmBtu (level) in Q20, from +3.83 in Q1 to +3.99 in Q20. Copper Price peaks at +99.98 index (level) in Q20, from +98.14 in Q1 to +99.98 in Q20. Wheat Price peaks at +100.00 index (level) in Q18, from +98.47 in Q1 to +99.98 in Q20. Gold Price peaks at +5472.24 USD/oz (level) in Q1, from +5472.24 in Q1 to +2031.95 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.27 % vs baseline in Q1, from -0.27 in Q1 to -0.15 in Q20. Services GDP peaks at -1.66 % vs baseline in Q1, from -1.66 in Q1 to -0.23 in Q20. Capital Stock peaks at -0.17 % vs baseline in Q20, from -0.03 in Q1 to -0.17 in Q20.

Timing. The GDP response has mostly faded by Q12 (Q20 is -0.28%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/CH_Y.png)

![CPI Inflation](charts/CH_pi_cpi.png)

![Equity Index](charts/CH_equity.png)

![Gold Price](charts/CH_P_gold.png)

![Wheat Price](charts/CH_P_wheat.png)

![Copper Price](charts/CH_P_copper.png)

![Metals Price](charts/CH_P_metals.png)

![Food Price](charts/CH_P_food.png)

![VIX](charts/CH_vix.png)

![Energy Price](charts/CH_P_energy.png)

![Investment](charts/CH_I.png)

![Gas Price](charts/CH_P_gas.png)

[Q1–Q20 JSON for Switzerland](numbers/CH.json)

## PL — Poland

The main impact of VIX at 80 on Poland would be a large drop in GDP of 2.08% by Q1. Equities peak at -3.70% in Q1.

Demand and trade. Consumption peaks at -2.82 % vs baseline in Q1, from -2.82 in Q1 to -0.12 in Q20. Investment peaks at -10.85 % vs baseline in Q1, from -10.85 in Q1 to -0.66 in Q20. Net Exports peaks at +0.37 % vs baseline in Q1, from +0.37 in Q1 to +0.07 in Q20. Gov Spending peaks at +0.42 % vs baseline in Q1, from +0.42 in Q1 to +0.04 in Q20. Gov Debt peaks at +0.00 % vs baseline in Q1, from +0.00 in Q1 to +0.00 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.23 % vs baseline in Q14, from -0.11 in Q1 to +0.19 in Q20.

Labour. Employment peaks at -0.91 % vs baseline in Q4, from -0.45 in Q1 to -0.26 in Q20. Unemployment peaks at +0.40 pp in Q4, from +0.21 in Q1 to +0.12 in Q20. Real Wages peaks at -1.30 % vs baseline in Q20, from -0.02 in Q1 to -1.30 in Q20.

Prices. The three-year CPI impulse is -0.39 percentage points. CPI Inflation peaks at -0.10 pp in Q2, from -0.08 in Q1 to -0.01 in Q20. Domestic Infl. peaks at -0.07 pp in Q2, from -0.06 in Q1 to -0.00 in Q20. Marginal Cost peaks at -1.25 % vs baseline in Q1, from -1.25 in Q1 to -0.12 in Q20.

Financial conditions. Policy Rate peaks at -0.31 pp (annualized) in Q4, from -0.11 in Q1 to -0.01 in Q20. Real Rate peaks at -0.08 pp (annualized) in Q4, from -0.03 in Q1 to -0.00 in Q20. Govt 3M Yield peaks at -0.31 pp (annualized) in Q4, from -0.11 in Q1 to -0.01 in Q20. Govt 2Y Yield peaks at -0.25 pp (annualized) in Q2, from -0.24 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at -0.13 pp (annualized) in Q1, from -0.13 in Q1 to -0.04 in Q20. Govt 10Y Yield peaks at -0.08 pp (annualized) in Q1, from -0.08 in Q1 to -0.03 in Q20. Govt 30Y Yield peaks at -0.04 pp (annualized) in Q1, from -0.04 in Q1 to -0.02 in Q20. Bond Price (7y) peaks at +1.28 % vs baseline in Q4, from +0.46 in Q1 to +0.06 in Q20. Bond Price 3M peaks at +0.08 % vs baseline in Q4, from +0.03 in Q1 to +0.00 in Q20. Bond Price 2Y peaks at +0.47 % vs baseline in Q2, from +0.46 in Q1 to +0.06 in Q20. Bond Price 5Y peaks at +0.57 % vs baseline in Q1, from +0.57 in Q1 to +0.17 in Q20. Bond Price 10Y peaks at +0.68 % vs baseline in Q1, from +0.68 in Q1 to +0.27 in Q20. Bond Price 30Y peaks at +0.65 % vs baseline in Q1, from +0.65 in Q1 to +0.28 in Q20. Equity Index peaks at -3.70 % vs baseline in Q1, from -3.70 in Q1 to -0.36 in Q20. VIX peaks at +80.00 index_level in Q1, from +80.00 in Q1 to +15.57 in Q20. Tobin's Q peaks at -3.95 % vs baseline in Q1, from -3.95 in Q1 to -0.38 in Q20. House Prices peaks at -0.88 % vs baseline in Q11, from -0.25 in Q1 to -0.77 in Q20. Bank Equity peaks at -0.28 % vs baseline in Q7, from -0.10 in Q1 to -0.16 in Q20. Bank Credit peaks at -0.25 % vs baseline in Q7, from -0.09 in Q1 to -0.14 in Q20. Credit Spread peaks at +0.01 pp in Q7, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.19 % vs baseline in Q2, from +0.16 in Q1 to +0.12 in Q20. vs USD peaks at -0.50 % vs baseline in Q17, from +0.09 in Q1 to -0.49 in Q20.

Commodities. Energy Price peaks at +79.86 USD/bbl (level) in Q20, from +77.47 in Q1 to +79.86 in Q20. Metals Price peaks at +99.92 index (level) in Q20, from +97.53 in Q1 to +99.92 in Q20. Food Price peaks at +99.79 index (level) in Q20, from +97.33 in Q1 to +99.79 in Q20. Gas Price peaks at +3.99 USD/mmBtu (level) in Q20, from +3.83 in Q1 to +3.99 in Q20. Copper Price peaks at +99.98 index (level) in Q20, from +98.14 in Q1 to +99.98 in Q20. Wheat Price peaks at +100.00 index (level) in Q18, from +98.47 in Q1 to +99.98 in Q20. Gold Price peaks at +5472.24 USD/oz (level) in Q1, from +5472.24 in Q1 to +2031.95 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.48 % vs baseline in Q1, from -0.48 in Q1 to -0.11 in Q20. Services GDP peaks at -1.30 % vs baseline in Q1, from -1.30 in Q1 to -0.13 in Q20. Capital Stock peaks at -0.15 % vs baseline in Q20, from -0.03 in Q1 to -0.15 in Q20.

Timing. The GDP response has mostly faded by Q10 (Q20 is -0.20%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/PL_Y.png)

![CPI Inflation](charts/PL_pi_cpi.png)

![Equity Index](charts/PL_equity.png)

![Gold Price](charts/PL_P_gold.png)

![Wheat Price](charts/PL_P_wheat.png)

![Copper Price](charts/PL_P_copper.png)

![Metals Price](charts/PL_P_metals.png)

![Food Price](charts/PL_P_food.png)

![VIX](charts/PL_vix.png)

![Energy Price](charts/PL_P_energy.png)

![Investment](charts/PL_I.png)

![Gas Price](charts/PL_P_gas.png)

[Q1–Q20 JSON for Poland](numbers/PL.json)

## RU — Russia

The main impact of VIX at 80 on Russia would be a large drop in GDP of 2.03% by Q1. Equities peak at -3.56% in Q1.

Demand and trade. Consumption peaks at -2.83 % vs baseline in Q1, from -2.83 in Q1 to -0.03 in Q20. Investment peaks at -10.57 % vs baseline in Q1, from -10.57 in Q1 to -0.26 in Q20. Net Exports peaks at -0.61 % vs baseline in Q3, from -0.42 in Q1 to -0.00 in Q20. Gov Spending peaks at +0.19 % vs baseline in Q1, from +0.19 in Q1 to -0.00 in Q20. Gov Debt peaks at -0.39 % vs baseline in Q9, from -0.10 in Q1 to -0.28 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.75 % vs baseline in Q3, from +0.56 in Q1 to +0.28 in Q20.

Labour. Employment peaks at -0.86 % vs baseline in Q5, from -0.36 in Q1 to -0.06 in Q20. Unemployment peaks at +0.40 pp in Q4, from +0.20 in Q1 to +0.03 in Q20. Real Wages peaks at -1.62 % vs baseline in Q16, from -0.04 in Q1 to -1.51 in Q20.

Prices. The three-year CPI impulse is -0.79 percentage points. CPI Inflation peaks at -0.16 pp in Q2, from -0.13 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.11 pp in Q2, from -0.09 in Q1 to -0.00 in Q20. Marginal Cost peaks at -1.21 % vs baseline in Q1, from -1.21 in Q1 to -0.02 in Q20.

Financial conditions. Policy Rate peaks at -0.55 pp (annualized) in Q4, from -0.20 in Q1 to +0.01 in Q20. Real Rate peaks at -0.14 pp (annualized) in Q4, from -0.05 in Q1 to +0.00 in Q20. Govt 3M Yield peaks at -0.55 pp (annualized) in Q4, from -0.20 in Q1 to +0.01 in Q20. Govt 2Y Yield peaks at -0.46 pp (annualized) in Q2, from -0.44 in Q1 to -0.01 in Q20. Govt 5Y Yield peaks at -0.23 pp (annualized) in Q1, from -0.23 in Q1 to -0.04 in Q20. Govt 10Y Yield peaks at -0.14 pp (annualized) in Q1, from -0.14 in Q1 to -0.05 in Q20. Govt 30Y Yield peaks at -0.06 pp (annualized) in Q1, from -0.06 in Q1 to -0.02 in Q20. Bond Price (7y) peaks at +1.73 % vs baseline in Q4, from +0.62 in Q1 to -0.03 in Q20. Bond Price 3M peaks at +0.14 % vs baseline in Q4, from +0.05 in Q1 to -0.00 in Q20. Bond Price 2Y peaks at +0.87 % vs baseline in Q2, from +0.84 in Q1 to +0.03 in Q20. Bond Price 5Y peaks at +1.05 % vs baseline in Q1, from +1.05 in Q1 to +0.19 in Q20. Bond Price 10Y peaks at +1.14 % vs baseline in Q1, from +1.14 in Q1 to +0.37 in Q20. Bond Price 30Y peaks at +1.13 % vs baseline in Q1, from +1.13 in Q1 to +0.44 in Q20. Equity Index peaks at -3.56 % vs baseline in Q1, from -3.56 in Q1 to -0.08 in Q20. VIX peaks at +80.00 index_level in Q1, from +80.00 in Q1 to +15.57 in Q20. Tobin's Q peaks at -3.76 % vs baseline in Q1, from -3.76 in Q1 to -0.10 in Q20. House Prices peaks at -0.98 % vs baseline in Q8, from -0.31 in Q1 to -0.50 in Q20. Bank Equity peaks at -0.26 % vs baseline in Q8, from -0.08 in Q1 to -0.14 in Q20. Bank Credit peaks at -0.23 % vs baseline in Q8, from -0.07 in Q1 to -0.12 in Q20. Credit Spread peaks at +0.01 pp in Q8, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.71 % vs baseline in Q2, from -0.55 in Q1 to +0.17 in Q20. vs USD peaks at +0.78 % vs baseline in Q2, from +0.75 in Q1 to -0.39 in Q20.

Commodities. Energy Price peaks at +79.86 USD/bbl (level) in Q20, from +77.47 in Q1 to +79.86 in Q20. Metals Price peaks at +99.92 index (level) in Q20, from +97.53 in Q1 to +99.92 in Q20. Food Price peaks at +99.79 index (level) in Q20, from +97.33 in Q1 to +99.79 in Q20. Gas Price peaks at +3.99 USD/mmBtu (level) in Q20, from +3.83 in Q1 to +3.99 in Q20. Copper Price peaks at +99.98 index (level) in Q20, from +98.14 in Q1 to +99.98 in Q20. Wheat Price peaks at +100.00 index (level) in Q18, from +98.47 in Q1 to +99.98 in Q20. Gold Price peaks at +5472.24 USD/oz (level) in Q1, from +5472.24 in Q1 to +2031.95 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.52 % vs baseline in Q1, from -0.52 in Q1 to -0.09 in Q20. Services GDP peaks at -1.11 % vs baseline in Q1, from -1.11 in Q1 to -0.02 in Q20. Capital Stock peaks at -0.10 % vs baseline in Q20, from -0.03 in Q1 to -0.10 in Q20.

Timing. The GDP response has mostly faded by Q9 (Q20 is -0.04%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/RU_Y.png)

![CPI Inflation](charts/RU_pi_cpi.png)

![Equity Index](charts/RU_equity.png)

![Gold Price](charts/RU_P_gold.png)

![Wheat Price](charts/RU_P_wheat.png)

![Copper Price](charts/RU_P_copper.png)

![Metals Price](charts/RU_P_metals.png)

![Food Price](charts/RU_P_food.png)

![VIX](charts/RU_vix.png)

![Energy Price](charts/RU_P_energy.png)

![Investment](charts/RU_I.png)

![Gas Price](charts/RU_P_gas.png)

[Q1–Q20 JSON for Russia](numbers/RU.json)

## CL — Chile

The main impact of VIX at 80 on Chile would be a large drop in GDP of 2.02% by Q1. Equities peak at -4.59% in Q1.

Demand and trade. Consumption peaks at -2.93 % vs baseline in Q1, from -2.93 in Q1 to -0.09 in Q20. Investment peaks at -10.63 % vs baseline in Q1, from -10.63 in Q1 to -0.45 in Q20. Net Exports peaks at -0.07 % vs baseline in Q3, from +0.03 in Q1 to +0.05 in Q20. Gov Spending peaks at +0.28 % vs baseline in Q1, from +0.28 in Q1 to +0.02 in Q20. Gov Debt peaks at -0.73 % vs baseline in Q8, from -0.24 in Q1 to -0.47 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.94 % vs baseline in Q3, from +0.70 in Q1 to +0.29 in Q20.

Labour. Employment peaks at -0.93 % vs baseline in Q4, from -0.47 in Q1 to -0.13 in Q20. Unemployment peaks at +0.36 pp in Q4, from +0.20 in Q1 to +0.06 in Q20. Real Wages peaks at -1.26 % vs baseline in Q17, from -0.03 in Q1 to -1.24 in Q20.

Prices. The three-year CPI impulse is -0.46 percentage points. CPI Inflation peaks at -0.12 pp in Q2, from -0.09 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.08 pp in Q2, from -0.07 in Q1 to -0.00 in Q20. Marginal Cost peaks at -1.21 % vs baseline in Q1, from -1.21 in Q1 to -0.07 in Q20.

Financial conditions. Policy Rate peaks at -0.42 pp (annualized) in Q4, from -0.15 in Q1 to -0.01 in Q20. Real Rate peaks at -0.10 pp (annualized) in Q4, from -0.04 in Q1 to -0.00 in Q20. Govt 3M Yield peaks at -0.42 pp (annualized) in Q4, from -0.15 in Q1 to -0.01 in Q20. Govt 2Y Yield peaks at -0.34 pp (annualized) in Q2, from -0.33 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at -0.17 pp (annualized) in Q1, from -0.17 in Q1 to -0.04 in Q20. Govt 10Y Yield peaks at -0.11 pp (annualized) in Q1, from -0.11 in Q1 to -0.04 in Q20. Govt 30Y Yield peaks at -0.05 pp (annualized) in Q1, from -0.05 in Q1 to -0.02 in Q20. Bond Price (7y) peaks at +1.74 % vs baseline in Q4, from +0.61 in Q1 to +0.03 in Q20. Bond Price 3M peaks at +0.10 % vs baseline in Q4, from +0.04 in Q1 to +0.00 in Q20. Bond Price 2Y peaks at +0.65 % vs baseline in Q2, from +0.63 in Q1 to +0.05 in Q20. Bond Price 5Y peaks at +0.78 % vs baseline in Q1, from +0.78 in Q1 to +0.19 in Q20. Bond Price 10Y peaks at +0.90 % vs baseline in Q1, from +0.90 in Q1 to +0.33 in Q20. Bond Price 30Y peaks at +0.87 % vs baseline in Q1, from +0.87 in Q1 to +0.35 in Q20. Equity Index peaks at -4.59 % vs baseline in Q1, from -4.59 in Q1 to -0.28 in Q20. VIX peaks at +80.00 index_level in Q1, from +80.00 in Q1 to +15.57 in Q20. Tobin's Q peaks at -3.80 % vs baseline in Q1, from -3.80 in Q1 to -0.24 in Q20. House Prices peaks at -0.97 % vs baseline in Q8, from -0.32 in Q1 to -0.63 in Q20. Bank Equity peaks at -0.27 % vs baseline in Q7, from -0.09 in Q1 to -0.13 in Q20. Bank Credit peaks at -0.22 % vs baseline in Q7, from -0.08 in Q1 to -0.11 in Q20. Credit Spread peaks at +0.01 pp in Q7, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.73 % vs baseline in Q2, from -0.60 in Q1 to +0.18 in Q20. vs USD peaks at +0.97 % vs baseline in Q2, from +0.90 in Q1 to -0.39 in Q20.

Commodities. Energy Price peaks at +79.86 USD/bbl (level) in Q20, from +77.47 in Q1 to +79.86 in Q20. Metals Price peaks at +99.92 index (level) in Q20, from +97.53 in Q1 to +99.92 in Q20. Food Price peaks at +99.79 index (level) in Q20, from +97.33 in Q1 to +99.79 in Q20. Gas Price peaks at +3.99 USD/mmBtu (level) in Q20, from +3.83 in Q1 to +3.99 in Q20. Copper Price peaks at +99.98 index (level) in Q20, from +98.14 in Q1 to +99.98 in Q20. Wheat Price peaks at +100.00 index (level) in Q18, from +98.47 in Q1 to +99.98 in Q20. Gold Price peaks at +5472.24 USD/oz (level) in Q1, from +5472.24 in Q1 to +2031.95 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.53 % vs baseline in Q1, from -0.53 in Q1 to -0.11 in Q20. Services GDP peaks at -1.22 % vs baseline in Q1, from -1.22 in Q1 to -0.07 in Q20. Capital Stock peaks at -0.12 % vs baseline in Q20, from -0.03 in Q1 to -0.12 in Q20.

Timing. The GDP response has mostly faded by Q9 (Q20 is -0.12%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/CL_Y.png)

![CPI Inflation](charts/CL_pi_cpi.png)

![Equity Index](charts/CL_equity.png)

![Gold Price](charts/CL_P_gold.png)

![Wheat Price](charts/CL_P_wheat.png)

![Copper Price](charts/CL_P_copper.png)

![Metals Price](charts/CL_P_metals.png)

![Food Price](charts/CL_P_food.png)

![VIX](charts/CL_vix.png)

![Energy Price](charts/CL_P_energy.png)

![Investment](charts/CL_I.png)

![Gas Price](charts/CL_P_gas.png)

[Q1–Q20 JSON for Chile](numbers/CL.json)

## DE — Germany

The main impact of VIX at 80 on Germany would be a large drop in GDP of 2.02% by Q1. Equities peak at -4.01% in Q1.

Demand and trade. Consumption peaks at -2.85 % vs baseline in Q1, from -2.85 in Q1 to -0.16 in Q20. Investment peaks at -10.75 % vs baseline in Q1, from -10.75 in Q1 to -0.74 in Q20. Net Exports peaks at +0.41 % vs baseline in Q1, from +0.41 in Q1 to +0.07 in Q20. Gov Spending peaks at +0.45 % vs baseline in Q1, from +0.45 in Q1 to +0.05 in Q20. Gov Debt peaks at +0.14 % vs baseline in Q13, from +0.03 in Q1 to +0.14 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.19 % vs baseline in Q16, from +0.00 in Q1 to +0.18 in Q20.

Labour. Employment peaks at -0.90 % vs baseline in Q6, from -0.40 in Q1 to -0.36 in Q20. Unemployment peaks at +0.67 pp in Q6, from +0.31 in Q1 to +0.27 in Q20. Real Wages peaks at -1.22 % vs baseline in Q20, from -0.01 in Q1 to -1.22 in Q20.

Prices. The three-year CPI impulse is -0.45 percentage points. CPI Inflation peaks at -0.10 pp in Q2, from -0.06 in Q1 to -0.01 in Q20. Domestic Infl. peaks at -0.07 pp in Q2, from -0.04 in Q1 to -0.00 in Q20. Marginal Cost peaks at -1.21 % vs baseline in Q1, from -1.21 in Q1 to -0.15 in Q20.

Financial conditions. Policy Rate peaks at -0.20 pp (annualized) in Q5, from -0.06 in Q1 to -0.03 in Q20. Real Rate peaks at -0.05 pp (annualized) in Q5, from -0.01 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -0.20 pp (annualized) in Q5, from -0.06 in Q1 to -0.03 in Q20. Govt 2Y Yield peaks at -0.18 pp (annualized) in Q3, from -0.16 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at -0.11 pp (annualized) in Q1, from -0.11 in Q1 to -0.03 in Q20. Govt 10Y Yield peaks at -0.07 pp (annualized) in Q1, from -0.07 in Q1 to -0.03 in Q20. Govt 30Y Yield peaks at -0.03 pp (annualized) in Q1, from -0.03 in Q1 to -0.01 in Q20. Bond Price (7y) peaks at +1.43 % vs baseline in Q5, from +0.40 in Q1 to +0.20 in Q20. Bond Price 3M peaks at +0.05 % vs baseline in Q5, from +0.01 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +0.34 % vs baseline in Q3, from +0.31 in Q1 to +0.05 in Q20. Bond Price 5Y peaks at +0.50 % vs baseline in Q1, from +0.50 in Q1 to +0.14 in Q20. Bond Price 10Y peaks at +0.58 % vs baseline in Q1, from +0.58 in Q1 to +0.21 in Q20. Bond Price 30Y peaks at +0.54 % vs baseline in Q1, from +0.54 in Q1 to +0.22 in Q20. Equity Index peaks at -4.01 % vs baseline in Q1, from -4.01 in Q1 to -0.48 in Q20. VIX peaks at +80.00 index_level in Q1, from +80.00 in Q1 to +15.57 in Q20. Tobin's Q peaks at -3.88 % vs baseline in Q1, from -3.88 in Q1 to -0.44 in Q20. House Prices peaks at -0.96 % vs baseline in Q12, from -0.24 in Q1 to -0.87 in Q20. Bank Equity peaks at -0.49 % vs baseline in Q8, from -0.16 in Q1 to -0.28 in Q20. Bank Credit peaks at -0.39 % vs baseline in Q8, from -0.13 in Q1 to -0.23 in Q20. Credit Spread peaks at +0.00 pp in Q8, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.19 % vs baseline in Q5, from +0.01 in Q1 to +0.14 in Q20. vs USD peaks at -0.54 % vs baseline in Q14, from +0.20 in Q1 to -0.50 in Q20.

Commodities. Energy Price peaks at +79.86 USD/bbl (level) in Q20, from +77.47 in Q1 to +79.86 in Q20. Metals Price peaks at +99.92 index (level) in Q20, from +97.53 in Q1 to +99.92 in Q20. Food Price peaks at +99.79 index (level) in Q20, from +97.33 in Q1 to +99.79 in Q20. Gas Price peaks at +3.99 USD/mmBtu (level) in Q20, from +3.83 in Q1 to +3.99 in Q20. Copper Price peaks at +99.98 index (level) in Q20, from +98.14 in Q1 to +99.98 in Q20. Wheat Price peaks at +100.00 index (level) in Q18, from +98.47 in Q1 to +99.98 in Q20. Gold Price peaks at +5472.24 USD/oz (level) in Q1, from +5472.24 in Q1 to +2031.95 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.48 % vs baseline in Q1, from -0.48 in Q1 to -0.12 in Q20. Services GDP peaks at -1.38 % vs baseline in Q1, from -1.38 in Q1 to -0.17 in Q20. Capital Stock peaks at -0.17 % vs baseline in Q20, from -0.03 in Q1 to -0.17 in Q20.

Timing. The GDP response has mostly faded by Q12 (Q20 is -0.24%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/DE_Y.png)

![CPI Inflation](charts/DE_pi_cpi.png)

![Equity Index](charts/DE_equity.png)

![Gold Price](charts/DE_P_gold.png)

![Wheat Price](charts/DE_P_wheat.png)

![Copper Price](charts/DE_P_copper.png)

![Metals Price](charts/DE_P_metals.png)

![Food Price](charts/DE_P_food.png)

![VIX](charts/DE_vix.png)

![Energy Price](charts/DE_P_energy.png)

![Investment](charts/DE_I.png)

![Gas Price](charts/DE_P_gas.png)

[Q1–Q20 JSON for Germany](numbers/DE.json)

## SE — Sweden

The main impact of VIX at 80 on Sweden would be a large drop in GDP of 2.01% by Q1. Equities peak at -6.01% in Q1.

Demand and trade. Consumption peaks at -2.89 % vs baseline in Q1, from -2.89 in Q1 to -0.15 in Q20. Investment peaks at -10.71 % vs baseline in Q1, from -10.71 in Q1 to -0.71 in Q20. Net Exports peaks at +0.23 % vs baseline in Q1, from +0.23 in Q1 to +0.06 in Q20. Gov Spending peaks at +0.42 % vs baseline in Q1, from +0.42 in Q1 to +0.05 in Q20. Gov Debt peaks at +0.39 % vs baseline in Q10, from +0.12 in Q1 to +0.31 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.33 % vs baseline in Q3, from +0.23 in Q1 to +0.19 in Q20.

Labour. Employment peaks at -0.81 % vs baseline in Q7, from -0.34 in Q1 to -0.36 in Q20. Unemployment peaks at +0.65 pp in Q5, from +0.31 in Q1 to +0.25 in Q20. Real Wages peaks at -1.20 % vs baseline in Q20, from -0.02 in Q1 to -1.20 in Q20.

Prices. The three-year CPI impulse is -0.36 percentage points. CPI Inflation peaks at -0.09 pp in Q2, from -0.08 in Q1 to -0.01 in Q20. Domestic Infl. peaks at -0.06 pp in Q2, from -0.06 in Q1 to -0.00 in Q20. Marginal Cost peaks at -1.21 % vs baseline in Q1, from -1.21 in Q1 to -0.14 in Q20.

Financial conditions. Policy Rate peaks at -0.23 pp (annualized) in Q5, from -0.08 in Q1 to -0.03 in Q20. Real Rate peaks at -0.06 pp (annualized) in Q5, from -0.02 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -0.23 pp (annualized) in Q5, from -0.08 in Q1 to -0.03 in Q20. Govt 2Y Yield peaks at -0.20 pp (annualized) in Q2, from -0.19 in Q1 to -0.04 in Q20. Govt 5Y Yield peaks at -0.12 pp (annualized) in Q1, from -0.12 in Q1 to -0.04 in Q20. Govt 10Y Yield peaks at -0.08 pp (annualized) in Q1, from -0.08 in Q1 to -0.03 in Q20. Govt 30Y Yield peaks at -0.03 pp (annualized) in Q1, from -0.03 in Q1 to -0.02 in Q20. Bond Price (7y) peaks at +1.43 % vs baseline in Q5, from +0.48 in Q1 to +0.20 in Q20. Bond Price 3M peaks at +0.06 % vs baseline in Q5, from +0.02 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +0.38 % vs baseline in Q2, from +0.36 in Q1 to +0.07 in Q20. Bond Price 5Y peaks at +0.54 % vs baseline in Q1, from +0.54 in Q1 to +0.17 in Q20. Bond Price 10Y peaks at +0.65 % vs baseline in Q1, from +0.65 in Q1 to +0.27 in Q20. Bond Price 30Y peaks at +0.62 % vs baseline in Q1, from +0.62 in Q1 to +0.28 in Q20. Equity Index peaks at -6.01 % vs baseline in Q1, from -6.01 in Q1 to -0.69 in Q20. VIX peaks at +80.00 index_level in Q1, from +80.00 in Q1 to +15.57 in Q20. Tobin's Q peaks at -3.86 % vs baseline in Q1, from -3.86 in Q1 to -0.41 in Q20. House Prices peaks at -0.89 % vs baseline in Q12, from -0.23 in Q1 to -0.81 in Q20. Bank Equity peaks at -0.42 % vs baseline in Q8, from -0.14 in Q1 to -0.23 in Q20. Bank Credit peaks at -0.33 % vs baseline in Q8, from -0.11 in Q1 to -0.19 in Q20. Credit Spread peaks at +0.00 pp in Q8, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.14 % vs baseline in Q20, from -0.07 in Q1 to +0.14 in Q20. vs USD peaks at -0.50 % vs baseline in Q17, from +0.42 in Q1 to -0.49 in Q20.

Commodities. Energy Price peaks at +79.86 USD/bbl (level) in Q20, from +77.47 in Q1 to +79.86 in Q20. Metals Price peaks at +99.92 index (level) in Q20, from +97.53 in Q1 to +99.92 in Q20. Food Price peaks at +99.79 index (level) in Q20, from +97.33 in Q1 to +99.79 in Q20. Gas Price peaks at +3.99 USD/mmBtu (level) in Q20, from +3.83 in Q1 to +3.99 in Q20. Copper Price peaks at +99.98 index (level) in Q20, from +98.14 in Q1 to +99.98 in Q20. Wheat Price peaks at +100.00 index (level) in Q18, from +98.47 in Q1 to +99.98 in Q20. Gold Price peaks at +5472.24 USD/oz (level) in Q1, from +5472.24 in Q1 to +2031.95 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.45 % vs baseline in Q1, from -0.45 in Q1 to -0.10 in Q20. Services GDP peaks at -1.44 % vs baseline in Q1, from -1.44 in Q1 to -0.17 in Q20. Capital Stock peaks at -0.16 % vs baseline in Q20, from -0.03 in Q1 to -0.16 in Q20.

Timing. The GDP response has mostly faded by Q11 (Q20 is -0.23%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/SE_Y.png)

![CPI Inflation](charts/SE_pi_cpi.png)

![Equity Index](charts/SE_equity.png)

![Gold Price](charts/SE_P_gold.png)

![Wheat Price](charts/SE_P_wheat.png)

![Copper Price](charts/SE_P_copper.png)

![Metals Price](charts/SE_P_metals.png)

![Food Price](charts/SE_P_food.png)

![VIX](charts/SE_vix.png)

![Energy Price](charts/SE_P_energy.png)

![Investment](charts/SE_I.png)

![Gas Price](charts/SE_P_gas.png)

[Q1–Q20 JSON for Sweden](numbers/SE.json)

## KR — South Korea

The main impact of VIX at 80 on South Korea would be a large drop in GDP of 1.98% by Q1. Equities peak at -4.88% in Q1.

Demand and trade. Consumption peaks at -2.91 % vs baseline in Q1, from -2.91 in Q1 to -0.07 in Q20. Investment peaks at -10.40 % vs baseline in Q1, from -10.40 in Q1 to -0.34 in Q20. Net Exports peaks at +0.52 % vs baseline in Q2, from +0.49 in Q1 to +0.10 in Q20. Gov Spending peaks at +0.36 % vs baseline in Q1, from +0.36 in Q1 to +0.02 in Q20. Gov Debt peaks at -0.46 % vs baseline in Q10, from -0.13 in Q1 to -0.36 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.41 % vs baseline in Q15, from -0.28 in Q1 to +0.37 in Q20.

Labour. Employment peaks at -0.80 % vs baseline in Q5, from -0.39 in Q1 to -0.13 in Q20. Unemployment peaks at +0.37 pp in Q4, from +0.20 in Q1 to +0.06 in Q20. Real Wages peaks at -1.13 % vs baseline in Q19, from -0.02 in Q1 to -1.12 in Q20.

Prices. The three-year CPI impulse is -0.25 percentage points. CPI Inflation peaks at -0.09 pp in Q2, from -0.08 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.06 pp in Q2, from -0.06 in Q1 to -0.00 in Q20. Marginal Cost peaks at -1.19 % vs baseline in Q1, from -1.19 in Q1 to -0.06 in Q20.

Financial conditions. Policy Rate peaks at -0.51 pp (annualized) in Q4, from -0.22 in Q1 to -0.03 in Q20. Real Rate peaks at -0.13 pp (annualized) in Q4, from -0.06 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -0.51 pp (annualized) in Q4, from -0.22 in Q1 to -0.03 in Q20. Govt 2Y Yield peaks at -0.42 pp (annualized) in Q2, from -0.41 in Q1 to -0.04 in Q20. Govt 5Y Yield peaks at -0.23 pp (annualized) in Q1, from -0.23 in Q1 to -0.06 in Q20. Govt 10Y Yield peaks at -0.15 pp (annualized) in Q1, from -0.15 in Q1 to -0.05 in Q20. Govt 30Y Yield peaks at -0.06 pp (annualized) in Q1, from -0.06 in Q1 to -0.03 in Q20. Bond Price (7y) peaks at +2.54 % vs baseline in Q4, from +1.12 in Q1 to +0.14 in Q20. Bond Price 3M peaks at +0.13 % vs baseline in Q4, from +0.06 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +0.81 % vs baseline in Q2, from +0.79 in Q1 to +0.08 in Q20. Bond Price 5Y peaks at +1.05 % vs baseline in Q1, from +1.05 in Q1 to +0.26 in Q20. Bond Price 10Y peaks at +1.20 % vs baseline in Q1, from +1.20 in Q1 to +0.44 in Q20. Bond Price 30Y peaks at +1.16 % vs baseline in Q1, from +1.16 in Q1 to +0.48 in Q20. Equity Index peaks at -4.88 % vs baseline in Q1, from -4.88 in Q1 to -0.23 in Q20. VIX peaks at +80.00 index_level in Q1, from +80.00 in Q1 to +15.57 in Q20. Tobin's Q peaks at -3.64 % vs baseline in Q1, from -3.64 in Q1 to -0.15 in Q20. House Prices peaks at -0.74 % vs baseline in Q9, from -0.23 in Q1 to -0.55 in Q20. Bank Equity peaks at -0.32 % vs baseline in Q7, from -0.11 in Q1 to -0.17 in Q20. Bank Credit peaks at -0.26 % vs baseline in Q7, from -0.09 in Q1 to -0.13 in Q20. Credit Spread peaks at +0.00 pp in Q7, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.53 % vs baseline in Q2, from +0.38 in Q1 to +0.06 in Q20. vs USD peaks at -0.37 % vs baseline in Q4, from -0.09 in Q1 to -0.31 in Q20.

Commodities. Energy Price peaks at +79.86 USD/bbl (level) in Q20, from +77.47 in Q1 to +79.86 in Q20. Metals Price peaks at +99.92 index (level) in Q20, from +97.53 in Q1 to +99.92 in Q20. Food Price peaks at +99.79 index (level) in Q20, from +97.33 in Q1 to +99.79 in Q20. Gas Price peaks at +3.99 USD/mmBtu (level) in Q20, from +3.83 in Q1 to +3.99 in Q20. Copper Price peaks at +99.98 index (level) in Q20, from +98.14 in Q1 to +99.98 in Q20. Wheat Price peaks at +100.00 index (level) in Q18, from +98.47 in Q1 to +99.98 in Q20. Gold Price peaks at +5472.24 USD/oz (level) in Q1, from +5472.24 in Q1 to +2031.95 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.49 % vs baseline in Q1, from -0.49 in Q1 to -0.14 in Q20. Services GDP peaks at -1.20 % vs baseline in Q1, from -1.20 in Q1 to -0.06 in Q20. Capital Stock peaks at -0.10 % vs baseline in Q20, from -0.03 in Q1 to -0.10 in Q20.

Timing. The GDP response has mostly faded by Q9 (Q20 is -0.09%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/KR_Y.png)

![CPI Inflation](charts/KR_pi_cpi.png)

![Equity Index](charts/KR_equity.png)

![Gold Price](charts/KR_P_gold.png)

![Wheat Price](charts/KR_P_wheat.png)

![Copper Price](charts/KR_P_copper.png)

![Metals Price](charts/KR_P_metals.png)

![Food Price](charts/KR_P_food.png)

![VIX](charts/KR_vix.png)

![Energy Price](charts/KR_P_energy.png)

![Investment](charts/KR_I.png)

![Gas Price](charts/KR_P_gas.png)

[Q1–Q20 JSON for South Korea](numbers/KR.json)

## FR — France

The main impact of VIX at 80 on France would be a large drop in GDP of 1.98% by Q1. Equities peak at -4.54% in Q1.

Demand and trade. Consumption peaks at -2.82 % vs baseline in Q1, from -2.82 in Q1 to -0.14 in Q20. Investment peaks at -10.66 % vs baseline in Q1, from -10.66 in Q1 to -0.71 in Q20. Net Exports peaks at +0.27 % vs baseline in Q1, from +0.27 in Q1 to +0.05 in Q20. Gov Spending peaks at +0.47 % vs baseline in Q1, from +0.47 in Q1 to +0.06 in Q20. Gov Debt peaks at +0.67 % vs baseline in Q15, from +0.15 in Q1 to +0.65 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.19 % vs baseline in Q15, from +0.01 in Q1 to +0.18 in Q20.

Labour. Employment peaks at -0.82 % vs baseline in Q7, from -0.33 in Q1 to -0.37 in Q20. Unemployment peaks at +0.66 pp in Q6, from +0.31 in Q1 to +0.26 in Q20. Real Wages peaks at -0.94 % vs baseline in Q20, from -0.01 in Q1 to -0.94 in Q20.

Prices. The three-year CPI impulse is -0.42 percentage points. CPI Inflation peaks at -0.09 pp in Q2, from -0.07 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.07 pp in Q2, from -0.05 in Q1 to -0.00 in Q20. Marginal Cost peaks at -1.19 % vs baseline in Q1, from -1.19 in Q1 to -0.14 in Q20.

Financial conditions. Policy Rate peaks at -0.20 pp (annualized) in Q5, from -0.06 in Q1 to -0.03 in Q20. Real Rate peaks at -0.05 pp (annualized) in Q5, from -0.01 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -0.20 pp (annualized) in Q5, from -0.06 in Q1 to -0.03 in Q20. Govt 2Y Yield peaks at -0.18 pp (annualized) in Q3, from -0.16 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at -0.11 pp (annualized) in Q1, from -0.11 in Q1 to -0.03 in Q20. Govt 10Y Yield peaks at -0.07 pp (annualized) in Q1, from -0.07 in Q1 to -0.03 in Q20. Govt 30Y Yield peaks at -0.03 pp (annualized) in Q1, from -0.03 in Q1 to -0.01 in Q20. Bond Price (7y) peaks at +1.43 % vs baseline in Q5, from +0.40 in Q1 to +0.20 in Q20. Bond Price 3M peaks at +0.05 % vs baseline in Q5, from +0.01 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +0.34 % vs baseline in Q3, from +0.31 in Q1 to +0.05 in Q20. Bond Price 5Y peaks at +0.50 % vs baseline in Q1, from +0.50 in Q1 to +0.14 in Q20. Bond Price 10Y peaks at +0.58 % vs baseline in Q1, from +0.58 in Q1 to +0.21 in Q20. Bond Price 30Y peaks at +0.54 % vs baseline in Q1, from +0.54 in Q1 to +0.22 in Q20. Equity Index peaks at -4.54 % vs baseline in Q1, from -4.54 in Q1 to -0.53 in Q20. VIX peaks at +80.00 index_level in Q1, from +80.00 in Q1 to +15.57 in Q20. Tobin's Q peaks at -3.82 % vs baseline in Q1, from -3.82 in Q1 to -0.42 in Q20. House Prices peaks at -0.90 % vs baseline in Q12, from -0.23 in Q1 to -0.82 in Q20. Bank Equity peaks at -0.49 % vs baseline in Q8, from -0.16 in Q1 to -0.28 in Q20. Bank Credit peaks at -0.39 % vs baseline in Q8, from -0.13 in Q1 to -0.22 in Q20. Credit Spread peaks at +0.00 pp in Q8, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.12 % vs baseline in Q11, from -0.02 in Q1 to +0.11 in Q20. vs USD peaks at -0.54 % vs baseline in Q14, from +0.21 in Q1 to -0.50 in Q20.

Commodities. Energy Price peaks at +79.86 USD/bbl (level) in Q20, from +77.47 in Q1 to +79.86 in Q20. Metals Price peaks at +99.92 index (level) in Q20, from +97.53 in Q1 to +99.92 in Q20. Food Price peaks at +99.79 index (level) in Q20, from +97.33 in Q1 to +99.79 in Q20. Gas Price peaks at +3.99 USD/mmBtu (level) in Q20, from +3.83 in Q1 to +3.99 in Q20. Copper Price peaks at +99.98 index (level) in Q20, from +98.14 in Q1 to +99.98 in Q20. Wheat Price peaks at +100.00 index (level) in Q18, from +98.47 in Q1 to +99.98 in Q20. Gold Price peaks at +5472.24 USD/oz (level) in Q1, from +5472.24 in Q1 to +2031.95 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.31 % vs baseline in Q1, from -0.31 in Q1 to -0.09 in Q20. Services GDP peaks at -1.53 % vs baseline in Q1, from -1.53 in Q1 to -0.18 in Q20. Capital Stock peaks at -0.17 % vs baseline in Q20, from -0.03 in Q1 to -0.17 in Q20.

Timing. The GDP response has mostly faded by Q11 (Q20 is -0.23%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/FR_Y.png)

![CPI Inflation](charts/FR_pi_cpi.png)

![Equity Index](charts/FR_equity.png)

![Gold Price](charts/FR_P_gold.png)

![Wheat Price](charts/FR_P_wheat.png)

![Copper Price](charts/FR_P_copper.png)

![Metals Price](charts/FR_P_metals.png)

![Food Price](charts/FR_P_food.png)

![VIX](charts/FR_vix.png)

![Energy Price](charts/FR_P_energy.png)

![Investment](charts/FR_I.png)

![Gas Price](charts/FR_P_gas.png)

[Q1–Q20 JSON for France](numbers/FR.json)

## ES — Spain

The main impact of VIX at 80 on Spain would be a large drop in GDP of 1.94% by Q1. Equities peak at -3.86% in Q1.

Demand and trade. Consumption peaks at -2.82 % vs baseline in Q1, from -2.82 in Q1 to -0.12 in Q20. Investment peaks at -10.54 % vs baseline in Q1, from -10.54 in Q1 to -0.58 in Q20. Net Exports peaks at +0.30 % vs baseline in Q1, from +0.30 in Q1 to +0.05 in Q20. Gov Spending peaks at +0.42 % vs baseline in Q1, from +0.42 in Q1 to +0.04 in Q20. Gov Debt peaks at +0.06 % vs baseline in Q12, from +0.02 in Q1 to +0.06 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.18 % vs baseline in Q16, from -0.06 in Q1 to +0.17 in Q20.

Labour. Employment peaks at -0.81 % vs baseline in Q6, from -0.37 in Q1 to -0.27 in Q20. Unemployment peaks at +0.41 pp in Q5, from +0.20 in Q1 to +0.14 in Q20. Real Wages peaks at -0.86 % vs baseline in Q20, from -0.01 in Q1 to -0.86 in Q20.

Prices. The three-year CPI impulse is -0.39 percentage points. CPI Inflation peaks at -0.09 pp in Q2, from -0.07 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.06 pp in Q2, from -0.05 in Q1 to -0.00 in Q20. Marginal Cost peaks at -1.16 % vs baseline in Q1, from -1.16 in Q1 to -0.11 in Q20.

Financial conditions. Policy Rate peaks at -0.20 pp (annualized) in Q5, from -0.06 in Q1 to -0.03 in Q20. Real Rate peaks at -0.05 pp (annualized) in Q5, from -0.01 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -0.20 pp (annualized) in Q5, from -0.06 in Q1 to -0.03 in Q20. Govt 2Y Yield peaks at -0.18 pp (annualized) in Q3, from -0.16 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at -0.11 pp (annualized) in Q1, from -0.11 in Q1 to -0.03 in Q20. Govt 10Y Yield peaks at -0.07 pp (annualized) in Q1, from -0.07 in Q1 to -0.03 in Q20. Govt 30Y Yield peaks at -0.03 pp (annualized) in Q1, from -0.03 in Q1 to -0.01 in Q20. Bond Price (7y) peaks at +1.43 % vs baseline in Q5, from +0.40 in Q1 to +0.20 in Q20. Bond Price 3M peaks at +0.05 % vs baseline in Q5, from +0.01 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +0.34 % vs baseline in Q3, from +0.31 in Q1 to +0.05 in Q20. Bond Price 5Y peaks at +0.50 % vs baseline in Q1, from +0.50 in Q1 to +0.14 in Q20. Bond Price 10Y peaks at +0.58 % vs baseline in Q1, from +0.58 in Q1 to +0.21 in Q20. Bond Price 30Y peaks at +0.54 % vs baseline in Q1, from +0.54 in Q1 to +0.22 in Q20. Equity Index peaks at -3.86 % vs baseline in Q1, from -3.86 in Q1 to -0.36 in Q20. VIX peaks at +80.00 index_level in Q1, from +80.00 in Q1 to +15.57 in Q20. Tobin's Q peaks at -3.73 % vs baseline in Q1, from -3.73 in Q1 to -0.33 in Q20. House Prices peaks at -0.80 % vs baseline in Q11, from -0.22 in Q1 to -0.70 in Q20. Bank Equity peaks at -0.34 % vs baseline in Q7, from -0.12 in Q1 to -0.18 in Q20. Bank Credit peaks at -0.27 % vs baseline in Q7, from -0.09 in Q1 to -0.15 in Q20. Credit Spread peaks at +0.00 pp in Q7, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.22 % vs baseline in Q4, from +0.13 in Q1 to +0.14 in Q20. vs USD peaks at -0.55 % vs baseline in Q14, from +0.13 in Q1 to -0.50 in Q20.

Commodities. Energy Price peaks at +79.86 USD/bbl (level) in Q20, from +77.47 in Q1 to +79.86 in Q20. Metals Price peaks at +99.92 index (level) in Q20, from +97.53 in Q1 to +99.92 in Q20. Food Price peaks at +99.79 index (level) in Q20, from +97.33 in Q1 to +99.79 in Q20. Gas Price peaks at +3.99 USD/mmBtu (level) in Q20, from +3.83 in Q1 to +3.99 in Q20. Copper Price peaks at +99.98 index (level) in Q20, from +98.14 in Q1 to +99.98 in Q20. Wheat Price peaks at +100.00 index (level) in Q18, from +98.47 in Q1 to +99.98 in Q20. Gold Price peaks at +5472.24 USD/oz (level) in Q1, from +5472.24 in Q1 to +2031.95 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.32 % vs baseline in Q1, from -0.32 in Q1 to -0.08 in Q20. Services GDP peaks at -1.43 % vs baseline in Q1, from -1.43 in Q1 to -0.14 in Q20. Capital Stock peaks at -0.14 % vs baseline in Q20, from -0.03 in Q1 to -0.14 in Q20.

Timing. The GDP response has mostly faded by Q10 (Q20 is -0.19%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/ES_Y.png)

![CPI Inflation](charts/ES_pi_cpi.png)

![Equity Index](charts/ES_equity.png)

![Gold Price](charts/ES_P_gold.png)

![Wheat Price](charts/ES_P_wheat.png)

![Copper Price](charts/ES_P_copper.png)

![Metals Price](charts/ES_P_metals.png)

![Food Price](charts/ES_P_food.png)

![VIX](charts/ES_vix.png)

![Energy Price](charts/ES_P_energy.png)

![Investment](charts/ES_I.png)

![Gas Price](charts/ES_P_gas.png)

[Q1–Q20 JSON for Spain](numbers/ES.json)

## AU — Australia

The main impact of VIX at 80 on Australia would be a large drop in GDP of 1.94% by Q1. Equities peak at -4.79% in Q1.

Demand and trade. Consumption peaks at -2.93 % vs baseline in Q1, from -2.93 in Q1 to -0.08 in Q20. Investment peaks at -10.29 % vs baseline in Q1, from -10.29 in Q1 to -0.19 in Q20. Net Exports peaks at -0.13 % vs baseline in Q3, from -0.04 in Q1 to +0.06 in Q20. Gov Spending peaks at +0.33 % vs baseline in Q1, from +0.33 in Q1 to +0.02 in Q20. Gov Debt peaks at -0.39 % vs baseline in Q10, from -0.11 in Q1 to -0.29 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +2.15 % vs baseline in Q3, from +1.60 in Q1 to +0.62 in Q20.

Labour. Employment peaks at -1.04 % vs baseline in Q4, from -0.55 in Q1 to -0.09 in Q20. Unemployment peaks at +0.62 pp in Q5, from +0.30 in Q1 to +0.14 in Q20. Real Wages peaks at -1.12 % vs baseline in Q20, from -0.02 in Q1 to -1.12 in Q20.

Prices. The three-year CPI impulse is -0.32 percentage points. CPI Inflation peaks at -0.09 pp in Q2, from -0.08 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.06 pp in Q2, from -0.05 in Q1 to -0.00 in Q20. Marginal Cost peaks at -1.16 % vs baseline in Q1, from -1.16 in Q1 to -0.06 in Q20.

Financial conditions. Policy Rate peaks at -0.57 pp (annualized) in Q5, from -0.22 in Q1 to -0.12 in Q20. Real Rate peaks at -0.14 pp (annualized) in Q5, from -0.05 in Q1 to -0.03 in Q20. Govt 3M Yield peaks at -0.57 pp (annualized) in Q5, from -0.22 in Q1 to -0.12 in Q20. Govt 2Y Yield peaks at -0.52 pp (annualized) in Q3, from -0.48 in Q1 to -0.10 in Q20. Govt 5Y Yield peaks at -0.35 pp (annualized) in Q1, from -0.35 in Q1 to -0.09 in Q20. Govt 10Y Yield peaks at -0.22 pp (annualized) in Q1, from -0.22 in Q1 to -0.08 in Q20. Govt 30Y Yield peaks at -0.10 pp (annualized) in Q1, from -0.10 in Q1 to -0.04 in Q20. Bond Price (7y) peaks at +3.53 % vs baseline in Q5, from +1.37 in Q1 to +0.75 in Q20. Bond Price 3M peaks at +0.14 % vs baseline in Q5, from +0.05 in Q1 to +0.03 in Q20. Bond Price 2Y peaks at +0.98 % vs baseline in Q3, from +0.91 in Q1 to +0.19 in Q20. Bond Price 5Y peaks at +1.58 % vs baseline in Q1, from +1.58 in Q1 to +0.41 in Q20. Bond Price 10Y peaks at +1.80 % vs baseline in Q1, from +1.80 in Q1 to +0.66 in Q20. Bond Price 30Y peaks at +1.74 % vs baseline in Q1, from +1.74 in Q1 to +0.73 in Q20. Equity Index peaks at -4.79 % vs baseline in Q1, from -4.79 in Q1 to -0.20 in Q20. VIX peaks at +80.00 index_level in Q1, from +80.00 in Q1 to +15.57 in Q20. Tobin's Q peaks at -3.57 % vs baseline in Q1, from -3.57 in Q1 to -0.05 in Q20. House Prices peaks at -0.72 % vs baseline in Q9, from -0.21 in Q1 to -0.54 in Q20. Bank Equity peaks at -0.36 % vs baseline in Q7, from -0.12 in Q1 to -0.19 in Q20. Bank Credit peaks at -0.29 % vs baseline in Q7, from -0.10 in Q1 to -0.15 in Q20. Credit Spread peaks at +0.00 pp in Q7, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -2.09 % vs baseline in Q2, from -1.61 in Q1 to -0.21 in Q20. vs USD peaks at +2.17 % vs baseline in Q2, from +1.79 in Q1 to -0.05 in Q20.

Commodities. Energy Price peaks at +79.86 USD/bbl (level) in Q20, from +77.47 in Q1 to +79.86 in Q20. Metals Price peaks at +99.92 index (level) in Q20, from +97.53 in Q1 to +99.92 in Q20. Food Price peaks at +99.79 index (level) in Q20, from +97.33 in Q1 to +99.79 in Q20. Gas Price peaks at +3.99 USD/mmBtu (level) in Q20, from +3.83 in Q1 to +3.99 in Q20. Copper Price peaks at +99.98 index (level) in Q20, from +98.14 in Q1 to +99.98 in Q20. Wheat Price peaks at +100.00 index (level) in Q18, from +98.47 in Q1 to +99.98 in Q20. Gold Price peaks at +5472.24 USD/oz (level) in Q1, from +5472.24 in Q1 to +2031.95 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.82 % vs baseline in Q2, from -0.73 in Q1 to -0.20 in Q20. Services GDP peaks at -1.39 % vs baseline in Q1, from -1.39 in Q1 to -0.07 in Q20. Capital Stock peaks at -0.09 % vs baseline in Q20, from -0.03 in Q1 to -0.09 in Q20.

Timing. The GDP response has mostly faded by Q9 (Q20 is -0.09%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/AU_Y.png)

![CPI Inflation](charts/AU_pi_cpi.png)

![Equity Index](charts/AU_equity.png)

![Gold Price](charts/AU_P_gold.png)

![Wheat Price](charts/AU_P_wheat.png)

![Copper Price](charts/AU_P_copper.png)

![Metals Price](charts/AU_P_metals.png)

![Food Price](charts/AU_P_food.png)

![VIX](charts/AU_vix.png)

![Energy Price](charts/AU_P_energy.png)

![Investment](charts/AU_I.png)

![Gas Price](charts/AU_P_gas.png)

[Q1–Q20 JSON for Australia](numbers/AU.json)

## CO — Colombia

The main impact of VIX at 80 on Colombia would be a large drop in GDP of 1.93% by Q1. Equities peak at -3.42% in Q1.

Demand and trade. Consumption peaks at -2.84 % vs baseline in Q1, from -2.84 in Q1 to -0.05 in Q20. Investment peaks at -10.31 % vs baseline in Q1, from -10.31 in Q1 to -0.40 in Q20. Net Exports peaks at -0.04 % vs baseline in Q3, from +0.03 in Q1 to +0.03 in Q20. Gov Spending peaks at +0.30 % vs baseline in Q1, from +0.30 in Q1 to +0.01 in Q20. Gov Debt peaks at -0.96 % vs baseline in Q9, from -0.27 in Q1 to -0.71 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +1.14 % vs baseline in Q3, from +0.84 in Q1 to +0.30 in Q20.

Labour. Employment peaks at -0.80 % vs baseline in Q5, from -0.37 in Q1 to -0.05 in Q20. Unemployment peaks at +0.10 pp in Q3, from +0.06 in Q1 to +0.01 in Q20. Real Wages peaks at -1.24 % vs baseline in Q15, from -0.03 in Q1 to -1.12 in Q20.

Prices. The three-year CPI impulse is -0.63 percentage points. CPI Inflation peaks at -0.15 pp in Q2, from -0.13 in Q1 to +0.00 in Q20. Domestic Infl. peaks at -0.11 pp in Q2, from -0.09 in Q1 to +0.00 in Q20. Marginal Cost peaks at -1.16 % vs baseline in Q1, from -1.16 in Q1 to -0.05 in Q20.

Financial conditions. Policy Rate peaks at -0.52 pp (annualized) in Q4, from -0.20 in Q1 to +0.04 in Q20. Real Rate peaks at -0.13 pp (annualized) in Q4, from -0.05 in Q1 to +0.01 in Q20. Govt 3M Yield peaks at -0.52 pp (annualized) in Q4, from -0.20 in Q1 to +0.04 in Q20. Govt 2Y Yield peaks at -0.41 pp (annualized) in Q2, from -0.40 in Q1 to -0.00 in Q20. Govt 5Y Yield peaks at -0.18 pp (annualized) in Q1, from -0.18 in Q1 to -0.03 in Q20. Govt 10Y Yield peaks at -0.11 pp (annualized) in Q1, from -0.11 in Q1 to -0.03 in Q20. Govt 30Y Yield peaks at -0.05 pp (annualized) in Q1, from -0.05 in Q1 to -0.02 in Q20. Bond Price (7y) peaks at +1.87 % vs baseline in Q4, from +0.70 in Q1 to -0.13 in Q20. Bond Price 3M peaks at +0.13 % vs baseline in Q4, from +0.05 in Q1 to -0.01 in Q20. Bond Price 2Y peaks at +0.78 % vs baseline in Q2, from +0.77 in Q1 to +0.00 in Q20. Bond Price 5Y peaks at +0.81 % vs baseline in Q1, from +0.81 in Q1 to +0.13 in Q20. Bond Price 10Y peaks at +0.87 % vs baseline in Q1, from +0.87 in Q1 to +0.25 in Q20. Bond Price 30Y peaks at +0.82 % vs baseline in Q1, from +0.82 in Q1 to +0.28 in Q20. Equity Index peaks at -3.42 % vs baseline in Q1, from -3.42 in Q1 to -0.15 in Q20. VIX peaks at +80.00 index_level in Q1, from +80.00 in Q1 to +15.57 in Q20. Tobin's Q peaks at -3.58 % vs baseline in Q1, from -3.58 in Q1 to -0.20 in Q20. House Prices peaks at -0.86 % vs baseline in Q8, from -0.30 in Q1 to -0.47 in Q20. Bank Equity peaks at -0.23 % vs baseline in Q7, from -0.08 in Q1 to -0.12 in Q20. Bank Credit peaks at -0.20 % vs baseline in Q7, from -0.07 in Q1 to -0.10 in Q20. Credit Spread peaks at +0.01 pp in Q7, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.93 % vs baseline in Q2, from -0.76 in Q1 to +0.16 in Q20. vs USD peaks at +1.16 % vs baseline in Q2, from +1.04 in Q1 to -0.37 in Q20.

Commodities. Energy Price peaks at +79.86 USD/bbl (level) in Q20, from +77.47 in Q1 to +79.86 in Q20. Metals Price peaks at +99.92 index (level) in Q20, from +97.53 in Q1 to +99.92 in Q20. Food Price peaks at +99.79 index (level) in Q20, from +97.33 in Q1 to +99.79 in Q20. Gas Price peaks at +3.99 USD/mmBtu (level) in Q20, from +3.83 in Q1 to +3.99 in Q20. Copper Price peaks at +99.98 index (level) in Q20, from +98.14 in Q1 to +99.98 in Q20. Wheat Price peaks at +100.00 index (level) in Q18, from +98.47 in Q1 to +99.98 in Q20. Gold Price peaks at +5472.24 USD/oz (level) in Q1, from +5472.24 in Q1 to +2031.95 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.59 % vs baseline in Q1, from -0.59 in Q1 to -0.10 in Q20. Services GDP peaks at -1.17 % vs baseline in Q1, from -1.17 in Q1 to -0.05 in Q20. Capital Stock peaks at -0.09 % vs baseline in Q20, from -0.03 in Q1 to -0.09 in Q20.

Timing. The GDP response has mostly faded by Q8 (Q20 is -0.08%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/CO_Y.png)

![CPI Inflation](charts/CO_pi_cpi.png)

![Equity Index](charts/CO_equity.png)

![Gold Price](charts/CO_P_gold.png)

![Wheat Price](charts/CO_P_wheat.png)

![Copper Price](charts/CO_P_copper.png)

![Metals Price](charts/CO_P_metals.png)

![Food Price](charts/CO_P_food.png)

![VIX](charts/CO_vix.png)

![Energy Price](charts/CO_P_energy.png)

![Investment](charts/CO_I.png)

![Gas Price](charts/CO_P_gas.png)

[Q1–Q20 JSON for Colombia](numbers/CO.json)

## ZA — South Africa

The main impact of VIX at 80 on South Africa would be a large drop in GDP of 1.92% by Q1. Equities peak at -7.61% in Q1.

Demand and trade. Consumption peaks at -2.82 % vs baseline in Q1, from -2.82 in Q1 to -0.07 in Q20. Investment peaks at -10.34 % vs baseline in Q1, from -10.34 in Q1 to -0.47 in Q20. Net Exports peaks at +0.12 % vs baseline in Q1, from +0.12 in Q1 to +0.04 in Q20. Gov Spending peaks at +0.32 % vs baseline in Q1, from +0.32 in Q1 to +0.02 in Q20. Gov Debt peaks at -0.59 % vs baseline in Q10, from -0.16 in Q1 to -0.52 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.74 % vs baseline in Q3, from +0.57 in Q1 to +0.21 in Q20.

Labour. Employment peaks at -0.85 % vs baseline in Q4, from -0.42 in Q1 to -0.09 in Q20. Unemployment peaks at +0.23 pp in Q4, from +0.13 in Q1 to +0.03 in Q20. Real Wages peaks at -1.17 % vs baseline in Q16, from -0.03 in Q1 to -1.13 in Q20.

Prices. The three-year CPI impulse is -0.44 percentage points. CPI Inflation peaks at -0.11 pp in Q2, from -0.09 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.08 pp in Q2, from -0.06 in Q1 to -0.00 in Q20. Marginal Cost peaks at -1.15 % vs baseline in Q1, from -1.15 in Q1 to -0.07 in Q20.

Financial conditions. Policy Rate peaks at -0.39 pp (annualized) in Q4, from -0.15 in Q1 to +0.02 in Q20. Real Rate peaks at -0.10 pp (annualized) in Q4, from -0.04 in Q1 to +0.00 in Q20. Govt 3M Yield peaks at -0.39 pp (annualized) in Q4, from -0.15 in Q1 to +0.02 in Q20. Govt 2Y Yield peaks at -0.30 pp (annualized) in Q2, from -0.30 in Q1 to -0.01 in Q20. Govt 5Y Yield peaks at -0.13 pp (annualized) in Q1, from -0.13 in Q1 to -0.03 in Q20. Govt 10Y Yield peaks at -0.08 pp (annualized) in Q1, from -0.08 in Q1 to -0.02 in Q20. Govt 30Y Yield peaks at -0.03 pp (annualized) in Q1, from -0.03 in Q1 to -0.01 in Q20. Bond Price (7y) peaks at +1.63 % vs baseline in Q4, from +0.61 in Q1 to -0.07 in Q20. Bond Price 3M peaks at +0.10 % vs baseline in Q4, from +0.04 in Q1 to -0.00 in Q20. Bond Price 2Y peaks at +0.57 % vs baseline in Q2, from +0.56 in Q1 to +0.02 in Q20. Bond Price 5Y peaks at +0.59 % vs baseline in Q1, from +0.59 in Q1 to +0.12 in Q20. Bond Price 10Y peaks at +0.65 % vs baseline in Q1, from +0.65 in Q1 to +0.20 in Q20. Bond Price 30Y peaks at +0.60 % vs baseline in Q1, from +0.60 in Q1 to +0.21 in Q20. Equity Index peaks at -7.61 % vs baseline in Q1, from -7.61 in Q1 to -0.46 in Q20. VIX peaks at +80.00 index_level in Q1, from +80.00 in Q1 to +15.57 in Q20. Tobin's Q peaks at -3.60 % vs baseline in Q1, from -3.60 in Q1 to -0.24 in Q20. House Prices peaks at -0.89 % vs baseline in Q8, from -0.30 in Q1 to -0.56 in Q20. Bank Equity peaks at -0.29 % vs baseline in Q7, from -0.10 in Q1 to -0.15 in Q20. Bank Credit peaks at -0.25 % vs baseline in Q7, from -0.09 in Q1 to -0.13 in Q20. Credit Spread peaks at +0.01 pp in Q7, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.65 % vs baseline in Q2, from -0.54 in Q1 to +0.17 in Q20. vs USD peaks at +0.78 % vs baseline in Q2, from +0.77 in Q1 to -0.46 in Q20.

Commodities. Energy Price peaks at +79.86 USD/bbl (level) in Q20, from +77.47 in Q1 to +79.86 in Q20. Metals Price peaks at +99.92 index (level) in Q20, from +97.53 in Q1 to +99.92 in Q20. Food Price peaks at +99.79 index (level) in Q20, from +97.33 in Q1 to +99.79 in Q20. Gas Price peaks at +3.99 USD/mmBtu (level) in Q20, from +3.83 in Q1 to +3.99 in Q20. Copper Price peaks at +99.98 index (level) in Q20, from +98.14 in Q1 to +99.98 in Q20. Wheat Price peaks at +100.00 index (level) in Q18, from +98.47 in Q1 to +99.98 in Q20. Gold Price peaks at +5472.24 USD/oz (level) in Q1, from +5472.24 in Q1 to +2031.95 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.47 % vs baseline in Q1, from -0.47 in Q1 to -0.08 in Q20. Services GDP peaks at -1.22 % vs baseline in Q1, from -1.22 in Q1 to -0.07 in Q20. Capital Stock peaks at -0.11 % vs baseline in Q20, from -0.03 in Q1 to -0.11 in Q20.

Timing. The GDP response has mostly faded by Q8 (Q20 is -0.11%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/ZA_Y.png)

![CPI Inflation](charts/ZA_pi_cpi.png)

![Equity Index](charts/ZA_equity.png)

![Gold Price](charts/ZA_P_gold.png)

![Wheat Price](charts/ZA_P_wheat.png)

![Copper Price](charts/ZA_P_copper.png)

![Metals Price](charts/ZA_P_metals.png)

![Food Price](charts/ZA_P_food.png)

![VIX](charts/ZA_vix.png)

![Energy Price](charts/ZA_P_energy.png)

![Investment](charts/ZA_I.png)

![Gas Price](charts/ZA_P_gas.png)

[Q1–Q20 JSON for South Africa](numbers/ZA.json)

## NG — Nigeria

The main impact of VIX at 80 on Nigeria would be a large drop in GDP of 1.91% by Q1. Equities peak at -2.94% in Q1.

Demand and trade. Consumption peaks at -2.80 % vs baseline in Q1, from -2.80 in Q1 to +0.03 in Q20. Investment peaks at -10.09 % vs baseline in Q1, from -10.09 in Q1 to -0.28 in Q20. Net Exports peaks at -0.24 % vs baseline in Q3, from -0.13 in Q1 to +0.01 in Q20. Gov Spending peaks at +0.25 % vs baseline in Q1, from +0.25 in Q1 to -0.01 in Q20. Gov Debt peaks at -1.71 % vs baseline in Q9, from -0.45 in Q1 to -1.26 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.50 % vs baseline in Q7, from +0.27 in Q1 to +0.24 in Q20.

Labour. Employment peaks at -0.59 % vs baseline in Q5, from -0.25 in Q1 to +0.14 in Q20. Unemployment peaks at +0.08 pp in Q3, from +0.05 in Q1 to -0.01 in Q20. Real Wages peaks at -1.30 % vs baseline in Q11, from -0.05 in Q1 to -0.66 in Q20.

Prices. The three-year CPI impulse is -0.94 percentage points. CPI Inflation peaks at -0.25 pp in Q2, from -0.21 in Q1 to +0.02 in Q20. Domestic Infl. peaks at -0.17 pp in Q2, from -0.14 in Q1 to +0.01 in Q20. Marginal Cost peaks at -1.15 % vs baseline in Q1, from -1.15 in Q1 to +0.02 in Q20.

Financial conditions. Policy Rate peaks at -0.75 pp (annualized) in Q4, from -0.30 in Q1 to +0.13 in Q20. Real Rate peaks at -0.19 pp (annualized) in Q4, from -0.08 in Q1 to +0.03 in Q20. Govt 3M Yield peaks at -0.75 pp (annualized) in Q4, from -0.30 in Q1 to +0.13 in Q20. Govt 2Y Yield peaks at -0.56 pp (annualized) in Q1, from -0.56 in Q1 to +0.05 in Q20. Govt 5Y Yield peaks at -0.18 pp (annualized) in Q1, from -0.18 in Q1 to -0.01 in Q20. Govt 10Y Yield peaks at -0.10 pp (annualized) in Q1, from -0.10 in Q1 to -0.02 in Q20. Govt 30Y Yield peaks at -0.04 pp (annualized) in Q1, from -0.04 in Q1 to -0.01 in Q20. Bond Price (7y) peaks at +1.86 % vs baseline in Q4, from +0.76 in Q1 to -0.34 in Q20. Bond Price 3M peaks at +0.19 % vs baseline in Q4, from +0.08 in Q1 to -0.03 in Q20. Bond Price 2Y peaks at +1.05 % vs baseline in Q1, from +1.05 in Q1 to -0.10 in Q20. Bond Price 5Y peaks at +0.79 % vs baseline in Q1, from +0.79 in Q1 to +0.05 in Q20. Bond Price 10Y peaks at +0.80 % vs baseline in Q1, from +0.80 in Q1 to +0.18 in Q20. Bond Price 30Y peaks at +0.78 % vs baseline in Q1, from +0.78 in Q1 to +0.25 in Q20. Equity Index peaks at -2.94 % vs baseline in Q1, from -2.94 in Q1 to -0.01 in Q20. VIX peaks at +80.00 index_level in Q1, from +80.00 in Q1 to +15.57 in Q20. Tobin's Q peaks at -3.42 % vs baseline in Q1, from -3.42 in Q1 to -0.12 in Q20. House Prices peaks at -0.78 % vs baseline in Q6, from -0.29 in Q1 to -0.17 in Q20. Bank Equity peaks at -0.20 % vs baseline in Q7, from -0.07 in Q1 to -0.10 in Q20. Bank Credit peaks at -0.36 % vs baseline in Q7, from -0.12 in Q1 to -0.19 in Q20. Credit Spread peaks at +0.05 pp in Q7, from +0.02 in Q1 to +0.03 in Q20.

Nominal FX. NEER peaks at -0.24 % vs baseline in Q3, from -0.19 in Q1 to +0.17 in Q20. vs USD peaks at +0.47 % vs baseline in Q1, from +0.47 in Q1 to -0.44 in Q20.

Commodities. Energy Price peaks at +79.86 USD/bbl (level) in Q20, from +77.47 in Q1 to +79.86 in Q20. Metals Price peaks at +99.92 index (level) in Q20, from +97.53 in Q1 to +99.92 in Q20. Food Price peaks at +99.79 index (level) in Q20, from +97.33 in Q1 to +99.79 in Q20. Gas Price peaks at +3.99 USD/mmBtu (level) in Q20, from +3.83 in Q1 to +3.99 in Q20. Copper Price peaks at +99.98 index (level) in Q20, from +98.14 in Q1 to +99.98 in Q20. Wheat Price peaks at +100.00 index (level) in Q18, from +98.47 in Q1 to +99.98 in Q20. Gold Price peaks at +5472.24 USD/oz (level) in Q1, from +5472.24 in Q1 to +2031.95 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.25 % vs baseline in Q1, from -0.25 in Q1 to -0.07 in Q20. Services GDP peaks at -0.95 % vs baseline in Q1, from -0.95 in Q1 to +0.01 in Q20. Capital Stock peaks at -0.06 % vs baseline in Q7, from -0.02 in Q1 to -0.05 in Q20.

Timing. The GDP response has mostly faded by Q7 (Q20 is +0.03%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/NG_Y.png)

![CPI Inflation](charts/NG_pi_cpi.png)

![Equity Index](charts/NG_equity.png)

![Gold Price](charts/NG_P_gold.png)

![Wheat Price](charts/NG_P_wheat.png)

![Copper Price](charts/NG_P_copper.png)

![Metals Price](charts/NG_P_metals.png)

![Food Price](charts/NG_P_food.png)

![VIX](charts/NG_vix.png)

![Energy Price](charts/NG_P_energy.png)

![Investment](charts/NG_I.png)

![Gas Price](charts/NG_P_gas.png)

[Q1–Q20 JSON for Nigeria](numbers/NG.json)

## IT — Italy

The main impact of VIX at 80 on Italy would be a large drop in GDP of 1.88% by Q1. Equities peak at -3.37% in Q1.

Demand and trade. Consumption peaks at -2.74 % vs baseline in Q1, from -2.74 in Q1 to -0.10 in Q20. Investment peaks at -10.38 % vs baseline in Q1, from -10.38 in Q1 to -0.54 in Q20. Net Exports peaks at +0.31 % vs baseline in Q2, from +0.30 in Q1 to +0.04 in Q20. Gov Spending peaks at +0.41 % vs baseline in Q1, from +0.41 in Q1 to +0.04 in Q20. Gov Debt peaks at +0.12 % vs baseline in Q2, from +0.09 in Q1 to +0.02 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -0.20 % vs baseline in Q2, from -0.13 in Q1 to +0.17 in Q20.

Labour. Employment peaks at -0.78 % vs baseline in Q6, from -0.35 in Q1 to -0.25 in Q20. Unemployment peaks at +0.37 pp in Q4, from +0.19 in Q1 to +0.10 in Q20. Real Wages peaks at -0.73 % vs baseline in Q20, from -0.01 in Q1 to -0.73 in Q20.

Prices. The three-year CPI impulse is -0.39 percentage points. CPI Inflation peaks at -0.10 pp in Q2, from -0.08 in Q1 to +0.00 in Q20. Domestic Infl. peaks at -0.07 pp in Q2, from -0.06 in Q1 to +0.00 in Q20. Marginal Cost peaks at -1.13 % vs baseline in Q1, from -1.13 in Q1 to -0.10 in Q20.

Financial conditions. Policy Rate peaks at -0.20 pp (annualized) in Q5, from -0.06 in Q1 to -0.03 in Q20. Real Rate peaks at -0.05 pp (annualized) in Q5, from -0.01 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -0.20 pp (annualized) in Q5, from -0.06 in Q1 to -0.03 in Q20. Govt 2Y Yield peaks at -0.18 pp (annualized) in Q3, from -0.16 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at -0.11 pp (annualized) in Q1, from -0.11 in Q1 to -0.03 in Q20. Govt 10Y Yield peaks at -0.07 pp (annualized) in Q1, from -0.07 in Q1 to -0.03 in Q20. Govt 30Y Yield peaks at -0.03 pp (annualized) in Q1, from -0.03 in Q1 to -0.01 in Q20. Bond Price (7y) peaks at +1.42 % vs baseline in Q5, from +0.40 in Q1 to +0.19 in Q20. Bond Price 3M peaks at +0.05 % vs baseline in Q5, from +0.01 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +0.34 % vs baseline in Q3, from +0.31 in Q1 to +0.05 in Q20. Bond Price 5Y peaks at +0.50 % vs baseline in Q1, from +0.50 in Q1 to +0.14 in Q20. Bond Price 10Y peaks at +0.58 % vs baseline in Q1, from +0.58 in Q1 to +0.21 in Q20. Bond Price 30Y peaks at +0.54 % vs baseline in Q1, from +0.54 in Q1 to +0.22 in Q20. Equity Index peaks at -3.37 % vs baseline in Q1, from -3.37 in Q1 to -0.30 in Q20. VIX peaks at +80.00 index_level in Q1, from +80.00 in Q1 to +15.57 in Q20. Tobin's Q peaks at -3.62 % vs baseline in Q1, from -3.62 in Q1 to -0.30 in Q20. House Prices peaks at -0.75 % vs baseline in Q11, from -0.21 in Q1 to -0.65 in Q20. Bank Equity peaks at -0.36 % vs baseline in Q7, from -0.12 in Q1 to -0.20 in Q20. Bank Credit peaks at -0.30 % vs baseline in Q7, from -0.10 in Q1 to -0.16 in Q20. Credit Spread peaks at +0.00 pp in Q7, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.24 % vs baseline in Q3, from +0.16 in Q1 to +0.13 in Q20. vs USD peaks at -0.56 % vs baseline in Q13, from +0.06 in Q1 to -0.51 in Q20.

Commodities. Energy Price peaks at +79.86 USD/bbl (level) in Q20, from +77.47 in Q1 to +79.86 in Q20. Metals Price peaks at +99.92 index (level) in Q20, from +97.53 in Q1 to +99.92 in Q20. Food Price peaks at +99.79 index (level) in Q20, from +97.33 in Q1 to +99.79 in Q20. Gas Price peaks at +3.99 USD/mmBtu (level) in Q20, from +3.83 in Q1 to +3.99 in Q20. Copper Price peaks at +99.98 index (level) in Q20, from +98.14 in Q1 to +99.98 in Q20. Wheat Price peaks at +100.00 index (level) in Q18, from +98.47 in Q1 to +99.98 in Q20. Gold Price peaks at +5472.24 USD/oz (level) in Q1, from +5472.24 in Q1 to +2031.95 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.32 % vs baseline in Q1, from -0.32 in Q1 to -0.08 in Q20. Services GDP peaks at -1.37 % vs baseline in Q1, from -1.37 in Q1 to -0.12 in Q20. Capital Stock peaks at -0.14 % vs baseline in Q20, from -0.03 in Q1 to -0.14 in Q20.

Timing. The GDP response has mostly faded by Q10 (Q20 is -0.17%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/IT_Y.png)

![CPI Inflation](charts/IT_pi_cpi.png)

![Equity Index](charts/IT_equity.png)

![Gold Price](charts/IT_P_gold.png)

![Wheat Price](charts/IT_P_wheat.png)

![Copper Price](charts/IT_P_copper.png)

![Metals Price](charts/IT_P_metals.png)

![Food Price](charts/IT_P_food.png)

![VIX](charts/IT_vix.png)

![Energy Price](charts/IT_P_energy.png)

![Investment](charts/IT_I.png)

![Gas Price](charts/IT_P_gas.png)

[Q1–Q20 JSON for Italy](numbers/IT.json)

## TR — Turkey

The main impact of VIX at 80 on Turkey would be a large drop in GDP of 1.87% by Q1. Equities peak at -3.05% in Q1.

Demand and trade. Consumption peaks at -2.79 % vs baseline in Q1, from -2.79 in Q1 to -0.00 in Q20. Investment peaks at -10.00 % vs baseline in Q1, from -10.00 in Q1 to -0.26 in Q20. Net Exports peaks at +0.36 % vs baseline in Q2, from +0.34 in Q1 to +0.05 in Q20. Gov Spending peaks at +0.33 % vs baseline in Q1, from +0.33 in Q1 to +0.00 in Q20. Gov Debt peaks at -0.60 % vs baseline in Q8, from -0.19 in Q1 to -0.35 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.41 % vs baseline in Q10, from +0.07 in Q1 to +0.26 in Q20.

Labour. Employment peaks at -0.66 % vs baseline in Q4, from -0.31 in Q1 to +0.11 in Q20. Unemployment peaks at +0.22 pp in Q3, from +0.13 in Q1 to -0.01 in Q20. Real Wages peaks at -1.14 % vs baseline in Q13, from -0.04 in Q1 to -0.81 in Q20.

Prices. The three-year CPI impulse is -0.56 percentage points. CPI Inflation peaks at -0.16 pp in Q2, from -0.12 in Q1 to +0.00 in Q20. Domestic Infl. peaks at -0.11 pp in Q2, from -0.09 in Q1 to +0.00 in Q20. Marginal Cost peaks at -1.12 % vs baseline in Q1, from -1.12 in Q1 to -0.01 in Q20.

Financial conditions. Policy Rate peaks at -0.61 pp (annualized) in Q3, from -0.29 in Q1 to +0.06 in Q20. Real Rate peaks at -0.15 pp (annualized) in Q3, from -0.07 in Q1 to +0.01 in Q20. Govt 3M Yield peaks at -0.61 pp (annualized) in Q3, from -0.29 in Q1 to +0.06 in Q20. Govt 2Y Yield peaks at -0.42 pp (annualized) in Q1, from -0.42 in Q1 to +0.00 in Q20. Govt 5Y Yield peaks at -0.13 pp (annualized) in Q1, from -0.13 in Q1 to -0.03 in Q20. Govt 10Y Yield peaks at -0.08 pp (annualized) in Q1, from -0.08 in Q1 to -0.03 in Q20. Govt 30Y Yield peaks at -0.03 pp (annualized) in Q1, from -0.03 in Q1 to -0.01 in Q20. Bond Price (7y) peaks at +1.92 % vs baseline in Q3, from +0.91 in Q1 to -0.19 in Q20. Bond Price 3M peaks at +0.15 % vs baseline in Q3, from +0.07 in Q1 to -0.01 in Q20. Bond Price 2Y peaks at +0.80 % vs baseline in Q1, from +0.80 in Q1 to -0.01 in Q20. Bond Price 5Y peaks at +0.56 % vs baseline in Q1, from +0.56 in Q1 to +0.12 in Q20. Bond Price 10Y peaks at +0.64 % vs baseline in Q1, from +0.64 in Q1 to +0.21 in Q20. Bond Price 30Y peaks at +0.62 % vs baseline in Q1, from +0.62 in Q1 to +0.24 in Q20. Equity Index peaks at -3.05 % vs baseline in Q1, from -3.05 in Q1 to -0.04 in Q20. VIX peaks at +80.00 index_level in Q1, from +80.00 in Q1 to +15.57 in Q20. Tobin's Q peaks at -3.36 % vs baseline in Q1, from -3.36 in Q1 to -0.10 in Q20. House Prices peaks at -0.76 % vs baseline in Q6, from -0.29 in Q1 to -0.22 in Q20. Bank Equity peaks at -0.22 % vs baseline in Q7, from -0.08 in Q1 to -0.11 in Q20. Bank Credit peaks at -0.19 % vs baseline in Q7, from -0.07 in Q1 to -0.10 in Q20. Credit Spread peaks at +0.02 pp in Q7, from +0.01 in Q1 to +0.01 in Q20.

Nominal FX. NEER peaks at -0.08 % vs baseline in Q7, from -0.01 in Q1 to +0.08 in Q20. vs USD peaks at -0.41 % vs baseline in Q20, from +0.26 in Q1 to -0.41 in Q20.

Commodities. Energy Price peaks at +79.86 USD/bbl (level) in Q20, from +77.47 in Q1 to +79.86 in Q20. Metals Price peaks at +99.92 index (level) in Q20, from +97.53 in Q1 to +99.92 in Q20. Food Price peaks at +99.79 index (level) in Q20, from +97.33 in Q1 to +99.79 in Q20. Gas Price peaks at +3.99 USD/mmBtu (level) in Q20, from +3.83 in Q1 to +3.99 in Q20. Copper Price peaks at +99.98 index (level) in Q20, from +98.14 in Q1 to +99.98 in Q20. Wheat Price peaks at +100.00 index (level) in Q18, from +98.47 in Q1 to +99.98 in Q20. Gold Price peaks at +5472.24 USD/oz (level) in Q1, from +5472.24 in Q1 to +2031.95 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.47 % vs baseline in Q1, from -0.47 in Q1 to -0.08 in Q20. Services GDP peaks at -1.13 % vs baseline in Q1, from -1.13 in Q1 to -0.01 in Q20. Capital Stock peaks at -0.06 % vs baseline in Q8, from -0.02 in Q1 to -0.06 in Q20.

Timing. The GDP response has mostly faded by Q7 (Q20 is -0.01%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/TR_Y.png)

![CPI Inflation](charts/TR_pi_cpi.png)

![Equity Index](charts/TR_equity.png)

![Gold Price](charts/TR_P_gold.png)

![Wheat Price](charts/TR_P_wheat.png)

![Copper Price](charts/TR_P_copper.png)

![Metals Price](charts/TR_P_metals.png)

![Food Price](charts/TR_P_food.png)

![VIX](charts/TR_vix.png)

![Energy Price](charts/TR_P_energy.png)

![Investment](charts/TR_I.png)

![Gas Price](charts/TR_P_gas.png)

[Q1–Q20 JSON for Turkey](numbers/TR.json)

## BR — Brazil

The main impact of VIX at 80 on Brazil would be a large drop in GDP of 1.87% by Q1. Equities peak at -3.63% in Q1.

Demand and trade. Consumption peaks at -2.76 % vs baseline in Q1, from -2.76 in Q1 to +0.03 in Q20. Investment peaks at -9.99 % vs baseline in Q1, from -9.99 in Q1 to -0.20 in Q20. Net Exports peaks at -0.26 % vs baseline in Q3, from -0.16 in Q1 to +0.01 in Q20. Gov Spending peaks at +0.35 % vs baseline in Q1, from +0.35 in Q1 to -0.01 in Q20. Gov Debt peaks at -0.16 % vs baseline in Q8, from -0.05 in Q1 to -0.09 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.85 % vs baseline in Q4, from +0.61 in Q1 to +0.37 in Q20.

Labour. Employment peaks at -0.71 % vs baseline in Q5, from -0.32 in Q1 to +0.13 in Q20. Unemployment peaks at +0.21 pp in Q3, from +0.12 in Q1 to -0.03 in Q20. Real Wages peaks at -1.11 % vs baseline in Q14, from -0.03 in Q1 to -0.90 in Q20.

Prices. The three-year CPI impulse is -0.59 percentage points. CPI Inflation peaks at -0.15 pp in Q2, from -0.12 in Q1 to +0.01 in Q20. Domestic Infl. peaks at -0.10 pp in Q2, from -0.08 in Q1 to +0.01 in Q20. Marginal Cost peaks at -1.12 % vs baseline in Q1, from -1.12 in Q1 to +0.03 in Q20.

Financial conditions. Policy Rate peaks at -0.76 pp (annualized) in Q4, from -0.30 in Q1 to +0.13 in Q20. Real Rate peaks at -0.19 pp (annualized) in Q4, from -0.08 in Q1 to +0.03 in Q20. Govt 3M Yield peaks at -0.76 pp (annualized) in Q4, from -0.30 in Q1 to +0.13 in Q20. Govt 2Y Yield peaks at -0.57 pp (annualized) in Q1, from -0.57 in Q1 to +0.05 in Q20. Govt 5Y Yield peaks at -0.20 pp (annualized) in Q1, from -0.20 in Q1 to -0.01 in Q20. Govt 10Y Yield peaks at -0.11 pp (annualized) in Q1, from -0.11 in Q1 to -0.02 in Q20. Govt 30Y Yield peaks at -0.05 pp (annualized) in Q1, from -0.05 in Q1 to -0.02 in Q20. Bond Price (7y) peaks at +3.16 % vs baseline in Q4, from +1.26 in Q1 to -0.53 in Q20. Bond Price 3M peaks at +0.19 % vs baseline in Q4, from +0.08 in Q1 to -0.03 in Q20. Bond Price 2Y peaks at +1.08 % vs baseline in Q1, from +1.08 in Q1 to -0.10 in Q20. Bond Price 5Y peaks at +0.88 % vs baseline in Q1, from +0.88 in Q1 to +0.04 in Q20. Bond Price 10Y peaks at +0.88 % vs baseline in Q1, from +0.88 in Q1 to +0.20 in Q20. Bond Price 30Y peaks at +0.88 % vs baseline in Q1, from +0.88 in Q1 to +0.28 in Q20. Equity Index peaks at -3.63 % vs baseline in Q1, from -3.63 in Q1 to +0.05 in Q20. VIX peaks at +80.00 index_level in Q1, from +80.00 in Q1 to +15.57 in Q20. Tobin's Q peaks at -3.35 % vs baseline in Q1, from -3.35 in Q1 to -0.06 in Q20. House Prices peaks at -0.73 % vs baseline in Q6, from -0.27 in Q1 to -0.18 in Q20. Bank Equity peaks at -0.26 % vs baseline in Q7, from -0.09 in Q1 to -0.13 in Q20. Bank Credit peaks at -0.22 % vs baseline in Q7, from -0.07 in Q1 to -0.11 in Q20. Credit Spread peaks at +0.01 pp in Q7, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.64 % vs baseline in Q3, from -0.54 in Q1 to +0.07 in Q20. vs USD peaks at +0.84 % vs baseline in Q2, from +0.80 in Q1 to -0.30 in Q20.

Commodities. Energy Price peaks at +79.86 USD/bbl (level) in Q20, from +77.47 in Q1 to +79.86 in Q20. Metals Price peaks at +99.92 index (level) in Q20, from +97.53 in Q1 to +99.92 in Q20. Food Price peaks at +99.79 index (level) in Q20, from +97.33 in Q1 to +99.79 in Q20. Gas Price peaks at +3.99 USD/mmBtu (level) in Q20, from +3.83 in Q1 to +3.99 in Q20. Copper Price peaks at +99.98 index (level) in Q20, from +98.14 in Q1 to +99.98 in Q20. Wheat Price peaks at +100.00 index (level) in Q18, from +98.47 in Q1 to +99.98 in Q20. Gold Price peaks at +5472.24 USD/oz (level) in Q1, from +5472.24 in Q1 to +2031.95 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.51 % vs baseline in Q1, from -0.51 in Q1 to -0.10 in Q20. Services GDP peaks at -1.24 % vs baseline in Q1, from -1.24 in Q1 to +0.03 in Q20. Capital Stock peaks at -0.06 % vs baseline in Q8, from -0.02 in Q1 to -0.05 in Q20.

Timing. The GDP response has mostly faded by Q7 (Q20 is +0.05%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/BR_Y.png)

![CPI Inflation](charts/BR_pi_cpi.png)

![Equity Index](charts/BR_equity.png)

![Gold Price](charts/BR_P_gold.png)

![Wheat Price](charts/BR_P_wheat.png)

![Copper Price](charts/BR_P_copper.png)

![Metals Price](charts/BR_P_metals.png)

![Food Price](charts/BR_P_food.png)

![VIX](charts/BR_vix.png)

![Energy Price](charts/BR_P_energy.png)

![Investment](charts/BR_I.png)

![Gas Price](charts/BR_P_gas.png)

[Q1–Q20 JSON for Brazil](numbers/BR.json)

## ID — Indonesia

The main impact of VIX at 80 on Indonesia would be a large drop in GDP of 1.87% by Q1. Equities peak at -3.69% in Q1.

Demand and trade. Consumption peaks at -2.82 % vs baseline in Q1, from -2.82 in Q1 to -0.03 in Q20. Investment peaks at -10.16 % vs baseline in Q1, from -10.16 in Q1 to -0.30 in Q20. Net Exports peaks at +0.12 % vs baseline in Q1, from +0.12 in Q1 to +0.03 in Q20. Gov Spending peaks at +0.30 % vs baseline in Q1, from +0.30 in Q1 to +0.01 in Q20. Gov Debt peaks at -1.06 % vs baseline in Q8, from -0.36 in Q1 to -0.53 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.46 % vs baseline in Q9, from +0.25 in Q1 to +0.29 in Q20.

Labour. Employment peaks at -0.60 % vs baseline in Q6, from -0.25 in Q1 to -0.08 in Q20. Unemployment peaks at +0.09 pp in Q3, from +0.06 in Q1 to +0.00 in Q20. Real Wages peaks at -1.27 % vs baseline in Q14, from -0.03 in Q1 to -1.09 in Q20.

Prices. The three-year CPI impulse is -0.79 percentage points. CPI Inflation peaks at -0.19 pp in Q2, from -0.16 in Q1 to +0.00 in Q20. Domestic Infl. peaks at -0.13 pp in Q2, from -0.11 in Q1 to +0.00 in Q20. Marginal Cost peaks at -1.12 % vs baseline in Q1, from -1.12 in Q1 to -0.02 in Q20.

Financial conditions. Policy Rate peaks at -0.53 pp (annualized) in Q4, from -0.18 in Q1 to +0.04 in Q20. Real Rate peaks at -0.13 pp (annualized) in Q4, from -0.05 in Q1 to +0.01 in Q20. Govt 3M Yield peaks at -0.53 pp (annualized) in Q4, from -0.18 in Q1 to +0.04 in Q20. Govt 2Y Yield peaks at -0.43 pp (annualized) in Q2, from -0.42 in Q1 to +0.01 in Q20. Govt 5Y Yield peaks at -0.20 pp (annualized) in Q1, from -0.20 in Q1 to -0.02 in Q20. Govt 10Y Yield peaks at -0.11 pp (annualized) in Q1, from -0.11 in Q1 to -0.03 in Q20. Govt 30Y Yield peaks at -0.05 pp (annualized) in Q1, from -0.05 in Q1 to -0.01 in Q20. Bond Price (7y) peaks at +2.20 % vs baseline in Q4, from +0.76 in Q1 to -0.18 in Q20. Bond Price 3M peaks at +0.13 % vs baseline in Q4, from +0.05 in Q1 to -0.01 in Q20. Bond Price 2Y peaks at +0.83 % vs baseline in Q2, from +0.80 in Q1 to -0.03 in Q20. Bond Price 5Y peaks at +0.92 % vs baseline in Q1, from +0.92 in Q1 to +0.08 in Q20. Bond Price 10Y peaks at +0.93 % vs baseline in Q1, from +0.93 in Q1 to +0.21 in Q20. Bond Price 30Y peaks at +0.86 % vs baseline in Q1, from +0.86 in Q1 to +0.26 in Q20. Equity Index peaks at -3.69 % vs baseline in Q1, from -3.69 in Q1 to -0.08 in Q20. VIX peaks at +80.00 index_level in Q1, from +80.00 in Q1 to +15.57 in Q20. Tobin's Q peaks at -3.47 % vs baseline in Q1, from -3.47 in Q1 to -0.13 in Q20. House Prices peaks at -0.81 % vs baseline in Q7, from -0.29 in Q1 to -0.41 in Q20. Bank Equity peaks at -0.22 % vs baseline in Q7, from -0.08 in Q1 to -0.11 in Q20. Bank Credit peaks at -0.22 % vs baseline in Q7, from -0.08 in Q1 to -0.11 in Q20. Credit Spread peaks at +0.01 pp in Q7, from +0.00 in Q1 to +0.01 in Q20.

Nominal FX. NEER peaks at -0.18 % vs baseline in Q2, from -0.18 in Q1 to +0.13 in Q20. vs USD peaks at +0.44 % vs baseline in Q1, from +0.44 in Q1 to -0.38 in Q20.

Commodities. Energy Price peaks at +79.86 USD/bbl (level) in Q20, from +77.47 in Q1 to +79.86 in Q20. Metals Price peaks at +99.92 index (level) in Q20, from +97.53 in Q1 to +99.92 in Q20. Food Price peaks at +99.79 index (level) in Q20, from +97.33 in Q1 to +99.79 in Q20. Gas Price peaks at +3.99 USD/mmBtu (level) in Q20, from +3.83 in Q1 to +3.99 in Q20. Copper Price peaks at +99.98 index (level) in Q20, from +98.14 in Q1 to +99.98 in Q20. Wheat Price peaks at +100.00 index (level) in Q18, from +98.47 in Q1 to +99.98 in Q20. Gold Price peaks at +5472.24 USD/oz (level) in Q1, from +5472.24 in Q1 to +2031.95 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.48 % vs baseline in Q1, from -0.48 in Q1 to -0.09 in Q20. Services GDP peaks at -0.93 % vs baseline in Q1, from -0.93 in Q1 to -0.02 in Q20. Capital Stock peaks at -0.08 % vs baseline in Q20, from -0.02 in Q1 to -0.08 in Q20.

Timing. The GDP response has mostly faded by Q8 (Q20 is -0.04%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/ID_Y.png)

![CPI Inflation](charts/ID_pi_cpi.png)

![Equity Index](charts/ID_equity.png)

![Gold Price](charts/ID_P_gold.png)

![Wheat Price](charts/ID_P_wheat.png)

![Copper Price](charts/ID_P_copper.png)

![Metals Price](charts/ID_P_metals.png)

![Food Price](charts/ID_P_food.png)

![VIX](charts/ID_vix.png)

![Energy Price](charts/ID_P_energy.png)

![Investment](charts/ID_I.png)

![Gas Price](charts/ID_P_gas.png)

[Q1–Q20 JSON for Indonesia](numbers/ID.json)

## UK — United Kingdom

The main impact of VIX at 80 on United Kingdom would be a large drop in GDP of 1.87% by Q1. Equities peak at -4.67% in Q1.

Demand and trade. Consumption peaks at -2.88 % vs baseline in Q1, from -2.88 in Q1 to -0.15 in Q20. Investment peaks at -10.40 % vs baseline in Q1, from -10.40 in Q1 to -0.55 in Q20. Net Exports peaks at +0.18 % vs baseline in Q2, from +0.17 in Q1 to +0.03 in Q20. Gov Spending peaks at +0.39 % vs baseline in Q1, from +0.39 in Q1 to +0.04 in Q20. Gov Debt peaks at -0.09 % vs baseline in Q4, from -0.05 in Q1 to -0.03 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.15 % vs baseline in Q20, from -0.12 in Q1 to +0.15 in Q20.

Labour. Employment peaks at -1.04 % vs baseline in Q4, from -0.54 in Q1 to -0.24 in Q20. Unemployment peaks at +0.63 pp in Q6, from +0.29 in Q1 to +0.24 in Q20. Real Wages peaks at -1.05 % vs baseline in Q20, from -0.01 in Q1 to -1.05 in Q20.

Prices. The three-year CPI impulse is -0.70 percentage points. CPI Inflation peaks at -0.12 pp in Q2, from -0.10 in Q1 to -0.01 in Q20. Domestic Infl. peaks at -0.09 pp in Q2, from -0.07 in Q1 to -0.01 in Q20. Marginal Cost peaks at -1.12 % vs baseline in Q1, from -1.12 in Q1 to -0.13 in Q20.

Financial conditions. Policy Rate peaks at -0.12 pp (annualized) in Q9, from -0.02 in Q1 to -0.09 in Q20. Real Rate peaks at -0.03 pp (annualized) in Q9, from -0.01 in Q1 to -0.02 in Q20. Govt 3M Yield peaks at -0.12 pp (annualized) in Q9, from -0.02 in Q1 to -0.09 in Q20. Govt 2Y Yield peaks at -0.11 pp (annualized) in Q7, from -0.08 in Q1 to -0.09 in Q20. Govt 5Y Yield peaks at -0.10 pp (annualized) in Q4, from -0.10 in Q1 to -0.08 in Q20. Govt 10Y Yield peaks at -0.09 pp (annualized) in Q3, from -0.09 in Q1 to -0.06 in Q20. Govt 30Y Yield peaks at -0.05 pp (annualized) in Q1, from -0.05 in Q1 to -0.03 in Q20. Bond Price (7y) peaks at +0.81 % vs baseline in Q9, from +0.16 in Q1 to +0.64 in Q20. Bond Price 3M peaks at +0.03 % vs baseline in Q9, from +0.01 in Q1 to +0.02 in Q20. Bond Price 2Y peaks at +0.21 % vs baseline in Q7, from +0.16 in Q1 to +0.16 in Q20. Bond Price 5Y peaks at +0.46 % vs baseline in Q4, from +0.43 in Q1 to +0.35 in Q20. Bond Price 10Y peaks at +0.71 % vs baseline in Q3, from +0.70 in Q1 to +0.53 in Q20. Bond Price 30Y peaks at +0.85 % vs baseline in Q1, from +0.85 in Q1 to +0.60 in Q20. Equity Index peaks at -4.67 % vs baseline in Q1, from -4.67 in Q1 to -0.50 in Q20. VIX peaks at +80.00 index_level in Q1, from +80.00 in Q1 to +15.57 in Q20. Tobin's Q peaks at -3.64 % vs baseline in Q1, from -3.64 in Q1 to -0.31 in Q20. House Prices peaks at -0.82 % vs baseline in Q12, from -0.20 in Q1 to -0.73 in Q20. Bank Equity peaks at -0.41 % vs baseline in Q8, from -0.13 in Q1 to -0.23 in Q20. Bank Credit peaks at -0.33 % vs baseline in Q8, from -0.11 in Q1 to -0.18 in Q20. Credit Spread peaks at +0.00 pp in Q8, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.34 % vs baseline in Q8, from +0.19 in Q1 to +0.21 in Q20. vs USD peaks at -0.62 % vs baseline in Q13, from +0.08 in Q1 to -0.52 in Q20.

Commodities. Energy Price peaks at +79.86 USD/bbl (level) in Q20, from +77.47 in Q1 to +79.86 in Q20. Metals Price peaks at +99.92 index (level) in Q20, from +97.53 in Q1 to +99.92 in Q20. Food Price peaks at +99.79 index (level) in Q20, from +97.33 in Q1 to +99.79 in Q20. Gas Price peaks at +3.99 USD/mmBtu (level) in Q20, from +3.83 in Q1 to +3.99 in Q20. Copper Price peaks at +99.98 index (level) in Q20, from +98.14 in Q1 to +99.98 in Q20. Wheat Price peaks at +100.00 index (level) in Q18, from +98.47 in Q1 to +99.98 in Q20. Gold Price peaks at +5472.24 USD/oz (level) in Q1, from +5472.24 in Q1 to +2031.95 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.24 % vs baseline in Q1, from -0.24 in Q1 to -0.08 in Q20. Services GDP peaks at -1.48 % vs baseline in Q1, from -1.48 in Q1 to -0.17 in Q20. Capital Stock peaks at -0.16 % vs baseline in Q20, from -0.03 in Q1 to -0.16 in Q20.

Timing. The GDP response has mostly faded by Q11 (Q20 is -0.21%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/UK_Y.png)

![CPI Inflation](charts/UK_pi_cpi.png)

![Equity Index](charts/UK_equity.png)

![Gold Price](charts/UK_P_gold.png)

![Wheat Price](charts/UK_P_wheat.png)

![Copper Price](charts/UK_P_copper.png)

![Metals Price](charts/UK_P_metals.png)

![Food Price](charts/UK_P_food.png)

![VIX](charts/UK_vix.png)

![Energy Price](charts/UK_P_energy.png)

![Investment](charts/UK_I.png)

![Gas Price](charts/UK_P_gas.png)

[Q1–Q20 JSON for United Kingdom](numbers/UK.json)

## AR — Argentina

The main impact of VIX at 80 on Argentina would be a large drop in GDP of 1.84% by Q1. Equities peak at -2.70% in Q1.

Demand and trade. Consumption peaks at -2.66 % vs baseline in Q1, from -2.66 in Q1 to +0.22 in Q20. Investment peaks at -9.63 % vs baseline in Q1, from -9.63 in Q1 to +0.27 in Q20. Net Exports peaks at -0.19 % vs baseline in Q3, from -0.10 in Q1 to -0.01 in Q20. Gov Spending peaks at +0.33 % vs baseline in Q1, from +0.33 in Q1 to -0.07 in Q20. Gov Debt peaks at -0.39 % vs baseline in Q6, from -0.12 in Q1 to +0.14 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.55 % vs baseline in Q7, from +0.26 in Q1 to +0.32 in Q20.

Labour. Employment peaks at +0.80 % vs baseline in Q19, from -0.31 in Q1 to +0.79 in Q20. Unemployment peaks at -0.20 pp in Q16, from +0.12 in Q1 to -0.16 in Q20. Real Wages peaks at -1.17 % vs baseline in Q9, from -0.06 in Q1 to +0.69 in Q20.

Prices. The three-year CPI impulse is -0.56 percentage points. CPI Inflation peaks at -0.23 pp in Q2, from -0.19 in Q1 to +0.06 in Q20. Domestic Infl. peaks at -0.16 pp in Q2, from -0.13 in Q1 to +0.04 in Q20. Marginal Cost peaks at -1.10 % vs baseline in Q1, from -1.10 in Q1 to +0.22 in Q20.

Financial conditions. Policy Rate peaks at -0.89 pp (annualized) in Q3, from -0.47 in Q1 to +0.36 in Q20. Real Rate peaks at -0.22 pp (annualized) in Q3, from -0.12 in Q1 to +0.09 in Q20. Govt 3M Yield peaks at -0.89 pp (annualized) in Q3, from -0.47 in Q1 to +0.36 in Q20. Govt 2Y Yield peaks at -0.55 pp (annualized) in Q1, from -0.55 in Q1 to +0.20 in Q20. Govt 5Y Yield peaks at +0.31 pp (annualized) in Q9, from +0.03 in Q1 to +0.09 in Q20. Govt 10Y Yield peaks at +0.15 pp (annualized) in Q9, from +0.05 in Q1 to +0.03 in Q20. Govt 30Y Yield peaks at +0.04 pp (annualized) in Q9, from +0.01 in Q1 to +0.00 in Q20. Bond Price (7y) peaks at +2.21 % vs baseline in Q3, from +1.18 in Q1 to -0.89 in Q20. Bond Price 3M peaks at +0.22 % vs baseline in Q3, from +0.12 in Q1 to -0.09 in Q20. Bond Price 2Y peaks at +1.05 % vs baseline in Q1, from +1.05 in Q1 to -0.39 in Q20. Bond Price 5Y peaks at -1.42 % vs baseline in Q9, from -0.12 in Q1 to -0.39 in Q20. Bond Price 10Y peaks at -1.26 % vs baseline in Q9, from -0.38 in Q1 to -0.27 in Q20. Bond Price 30Y peaks at -0.77 % vs baseline in Q9, from -0.11 in Q1 to -0.07 in Q20. Equity Index peaks at -2.70 % vs baseline in Q1, from -2.70 in Q1 to +0.40 in Q20. VIX peaks at +80.00 index_level in Q1, from +80.00 in Q1 to +15.57 in Q20. Tobin's Q peaks at -3.10 % vs baseline in Q1, from -3.10 in Q1 to +0.27 in Q20. House Prices peaks at -0.61 % vs baseline in Q5, from -0.26 in Q1 to +0.53 in Q20. Bank Equity peaks at -0.18 % vs baseline in Q7, from -0.06 in Q1 to -0.09 in Q20. Bank Credit peaks at -0.38 % vs baseline in Q7, from -0.13 in Q1 to -0.19 in Q20. Credit Spread peaks at +0.11 pp in Q7, from +0.04 in Q1 to +0.06 in Q20.

Nominal FX. NEER peaks at -0.13 % vs baseline in Q4, from -0.08 in Q1 to +0.11 in Q20. vs USD peaks at +0.45 % vs baseline in Q1, from +0.45 in Q1 to -0.35 in Q20.

Commodities. Energy Price peaks at +79.86 USD/bbl (level) in Q20, from +77.47 in Q1 to +79.86 in Q20. Metals Price peaks at +99.92 index (level) in Q20, from +97.53 in Q1 to +99.92 in Q20. Food Price peaks at +99.79 index (level) in Q20, from +97.33 in Q1 to +99.79 in Q20. Gas Price peaks at +3.99 USD/mmBtu (level) in Q20, from +3.83 in Q1 to +3.99 in Q20. Copper Price peaks at +99.98 index (level) in Q20, from +98.14 in Q1 to +99.98 in Q20. Wheat Price peaks at +100.00 index (level) in Q18, from +98.47 in Q1 to +99.98 in Q20. Gold Price peaks at +5472.24 USD/oz (level) in Q1, from +5472.24 in Q1 to +2031.95 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.39 % vs baseline in Q1, from -0.39 in Q1 to -0.02 in Q20. Services GDP peaks at -1.05 % vs baseline in Q1, from -1.05 in Q1 to +0.21 in Q20. Capital Stock peaks at -0.04 % vs baseline in Q4, from -0.02 in Q1 to +0.04 in Q20.

Timing. The GDP response has mostly faded by Q5 (Q20 is +0.36%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/AR_Y.png)

![CPI Inflation](charts/AR_pi_cpi.png)

![Equity Index](charts/AR_equity.png)

![Gold Price](charts/AR_P_gold.png)

![Wheat Price](charts/AR_P_wheat.png)

![Copper Price](charts/AR_P_copper.png)

![Metals Price](charts/AR_P_metals.png)

![Food Price](charts/AR_P_food.png)

![VIX](charts/AR_vix.png)

![Energy Price](charts/AR_P_energy.png)

![Investment](charts/AR_I.png)

![Gas Price](charts/AR_P_gas.png)

[Q1–Q20 JSON for Argentina](numbers/AR.json)

## US — United States

The main impact of VIX at 80 on the United States would be a large drop in GDP of 1.82% by Q1. Equities peak at -5.73% in Q1.

Demand and trade. Consumption peaks at -2.89 % vs baseline in Q1, from -2.89 in Q1 to +0.02 in Q20. Investment peaks at -9.83 % vs baseline in Q1, from -9.83 in Q1 to -0.01 in Q20. Net Exports peaks at +0.03 % vs baseline in Q16, from +0.02 in Q1 to +0.03 in Q20. Gov Spending peaks at +0.35 % vs baseline in Q1, from +0.35 in Q1 to -0.01 in Q20. Gov Debt peaks at -0.22 % vs baseline in Q3, from -0.14 in Q1 to +0.01 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.72 % vs baseline in Q15, from -0.20 in Q1 to +0.67 in Q20.

Labour. Employment peaks at -1.07 % vs baseline in Q4, from -0.62 in Q1 to +0.13 in Q20. Unemployment peaks at +0.59 pp in Q5, from +0.28 in Q1 to +0.02 in Q20. Real Wages peaks at -0.96 % vs baseline in Q17, from -0.01 in Q1 to -0.94 in Q20.

Prices. The three-year CPI impulse is -0.59 percentage points. CPI Inflation peaks at -0.13 pp in Q2, from -0.11 in Q1 to +0.01 in Q20. Domestic Infl. peaks at -0.09 pp in Q2, from -0.08 in Q1 to +0.00 in Q20. Marginal Cost peaks at -1.09 % vs baseline in Q1, from -1.09 in Q1 to +0.03 in Q20.

Financial conditions. Policy Rate peaks at -0.76 pp (annualized) in Q5, from -0.31 in Q1 to +0.01 in Q20. Real Rate peaks at -0.19 pp (annualized) in Q5, from -0.08 in Q1 to +0.00 in Q20. Govt 3M Yield peaks at -0.76 pp (annualized) in Q5, from -0.31 in Q1 to +0.01 in Q20. Govt 2Y Yield peaks at -0.67 pp (annualized) in Q2, from -0.64 in Q1 to +0.02 in Q20. Govt 5Y Yield peaks at -0.38 pp (annualized) in Q1, from -0.38 in Q1 to -0.01 in Q20. Govt 10Y Yield peaks at -0.20 pp (annualized) in Q1, from -0.20 in Q1 to -0.03 in Q20. Govt 30Y Yield peaks at -0.08 pp (annualized) in Q1, from -0.08 in Q1 to -0.02 in Q20. Bond Price (7y) peaks at +5.00 % vs baseline in Q5, from +2.05 in Q1 to -0.09 in Q20. Bond Price 3M peaks at +0.19 % vs baseline in Q5, from +0.08 in Q1 to -0.00 in Q20. Bond Price 2Y peaks at +1.27 % vs baseline in Q2, from +1.22 in Q1 to -0.03 in Q20. Bond Price 5Y peaks at +1.69 % vs baseline in Q1, from +1.69 in Q1 to +0.06 in Q20. Bond Price 10Y peaks at +1.61 % vs baseline in Q1, from +1.61 in Q1 to +0.27 in Q20. Bond Price 30Y peaks at +1.52 % vs baseline in Q1, from +1.52 in Q1 to +0.41 in Q20. Equity Index peaks at -5.73 % vs baseline in Q1, from -5.73 in Q1 to +0.15 in Q20. VIX peaks at +80.00 index_level in Q1, from +80.00 in Q1 to +15.57 in Q20. Tobin's Q peaks at -3.24 % vs baseline in Q1, from -3.24 in Q1 to +0.07 in Q20. House Prices peaks at -0.58 % vs baseline in Q8, from -0.19 in Q1 to -0.31 in Q20. Bank Equity peaks at -0.32 % vs baseline in Q8, from -0.11 in Q1 to -0.18 in Q20. Bank Credit peaks at -0.26 % vs baseline in Q8, from -0.09 in Q1 to -0.14 in Q20. Credit Spread peaks at +0.00 pp in Q8, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.54 % vs baseline in Q1, from +0.54 in Q1 to -0.29 in Q20. vs USD peaks at +0.54 % vs baseline in Q1, from +0.54 in Q1 to -0.29 in Q20.

Commodities. Energy Price peaks at +79.86 USD/bbl (level) in Q20, from +77.47 in Q1 to +79.86 in Q20. Metals Price peaks at +99.92 index (level) in Q20, from +97.53 in Q1 to +99.92 in Q20. Food Price peaks at +99.79 index (level) in Q20, from +97.33 in Q1 to +99.79 in Q20. Gas Price peaks at +3.99 USD/mmBtu (level) in Q20, from +3.83 in Q1 to +3.99 in Q20. Copper Price peaks at +99.98 index (level) in Q20, from +98.14 in Q1 to +99.98 in Q20. Wheat Price peaks at +100.00 index (level) in Q18, from +98.47 in Q1 to +99.98 in Q20. Gold Price peaks at +5472.24 USD/oz (level) in Q1, from +5472.24 in Q1 to +2031.95 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.22 % vs baseline in Q1, from -0.22 in Q1 to -0.19 in Q20. Services GDP peaks at -1.40 % vs baseline in Q1, from -1.40 in Q1 to +0.04 in Q20. Capital Stock peaks at -0.07 % vs baseline in Q9, from -0.02 in Q1 to -0.05 in Q20.

Timing. The GDP response has mostly faded by Q9 (Q20 is +0.05%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/US_Y.png)

![CPI Inflation](charts/US_pi_cpi.png)

![Equity Index](charts/US_equity.png)

![Gold Price](charts/US_P_gold.png)

![Wheat Price](charts/US_P_wheat.png)

![Copper Price](charts/US_P_copper.png)

![Metals Price](charts/US_P_metals.png)

![Food Price](charts/US_P_food.png)

![VIX](charts/US_vix.png)

![Energy Price](charts/US_P_energy.png)

![Investment](charts/US_I.png)

![Bond Price (7y)](charts/US_Q_B.png)

[Q1–Q20 JSON for United States](numbers/US.json)

## IN — India

The main impact of VIX at 80 on India would be a large drop in GDP of 1.81% by Q1. Equities peak at -4.79% in Q1.

Demand and trade. Consumption peaks at -2.79 % vs baseline in Q1, from -2.79 in Q1 to +0.02 in Q20. Investment peaks at -9.83 % vs baseline in Q1, from -9.83 in Q1 to -0.29 in Q20. Net Exports peaks at +0.24 % vs baseline in Q2, from +0.23 in Q1 to +0.03 in Q20. Gov Spending peaks at +0.30 % vs baseline in Q1, from +0.30 in Q1 to -0.00 in Q20. Gov Debt peaks at -0.94 % vs baseline in Q8, from -0.27 in Q1 to -0.62 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.41 % vs baseline in Q12, from -0.04 in Q1 to +0.27 in Q20.

Labour. Employment peaks at -0.51 % vs baseline in Q6, from -0.21 in Q1 to +0.04 in Q20. Unemployment peaks at +0.07 pp in Q3, from +0.05 in Q1 to -0.01 in Q20. Real Wages peaks at -1.13 % vs baseline in Q13, from -0.03 in Q1 to -0.81 in Q20.

Prices. The three-year CPI impulse is -0.80 percentage points. CPI Inflation peaks at -0.22 pp in Q2, from -0.19 in Q1 to +0.01 in Q20. Domestic Infl. peaks at -0.15 pp in Q2, from -0.13 in Q1 to +0.01 in Q20. Marginal Cost peaks at -1.08 % vs baseline in Q1, from -1.08 in Q1 to +0.01 in Q20.

Financial conditions. Policy Rate peaks at -0.75 pp (annualized) in Q4, from -0.29 in Q1 to +0.14 in Q20. Real Rate peaks at -0.19 pp (annualized) in Q4, from -0.07 in Q1 to +0.03 in Q20. Govt 3M Yield peaks at -0.75 pp (annualized) in Q4, from -0.29 in Q1 to +0.14 in Q20. Govt 2Y Yield peaks at -0.57 pp (annualized) in Q1, from -0.57 in Q1 to +0.06 in Q20. Govt 5Y Yield peaks at -0.20 pp (annualized) in Q1, from -0.20 in Q1 to -0.00 in Q20. Govt 10Y Yield peaks at -0.11 pp (annualized) in Q1, from -0.11 in Q1 to -0.02 in Q20. Govt 30Y Yield peaks at -0.05 pp (annualized) in Q1, from -0.05 in Q1 to -0.01 in Q20. Bond Price (7y) peaks at +3.74 % vs baseline in Q4, from +1.45 in Q1 to -0.68 in Q20. Bond Price 3M peaks at +0.19 % vs baseline in Q4, from +0.07 in Q1 to -0.03 in Q20. Bond Price 2Y peaks at +1.08 % vs baseline in Q1, from +1.08 in Q1 to -0.12 in Q20. Bond Price 5Y peaks at +0.89 % vs baseline in Q1, from +0.89 in Q1 to +0.01 in Q20. Bond Price 10Y peaks at +0.86 % vs baseline in Q1, from +0.86 in Q1 to +0.15 in Q20. Bond Price 30Y peaks at +0.82 % vs baseline in Q1, from +0.82 in Q1 to +0.21 in Q20. Equity Index peaks at -4.79 % vs baseline in Q1, from -4.79 in Q1 to +0.01 in Q20. VIX peaks at +80.00 index_level in Q1, from +80.00 in Q1 to +15.57 in Q20. Tobin's Q peaks at -3.24 % vs baseline in Q1, from -3.24 in Q1 to -0.12 in Q20. House Prices peaks at -0.70 % vs baseline in Q6, from -0.27 in Q1 to -0.21 in Q20. Bank Equity peaks at -0.24 % vs baseline in Q7, from -0.08 in Q1 to -0.12 in Q20. Bank Credit peaks at -0.21 % vs baseline in Q7, from -0.07 in Q1 to -0.11 in Q20. Credit Spread peaks at +0.01 pp in Q7, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.28 % vs baseline in Q2, from +0.21 in Q1 to +0.13 in Q20. vs USD peaks at -0.40 % vs baseline in Q20, from +0.16 in Q1 to -0.40 in Q20.

Commodities. Energy Price peaks at +79.86 USD/bbl (level) in Q20, from +77.47 in Q1 to +79.86 in Q20. Metals Price peaks at +99.92 index (level) in Q20, from +97.53 in Q1 to +99.92 in Q20. Food Price peaks at +99.79 index (level) in Q20, from +97.33 in Q1 to +99.79 in Q20. Gas Price peaks at +3.99 USD/mmBtu (level) in Q20, from +3.83 in Q1 to +3.99 in Q20. Copper Price peaks at +99.98 index (level) in Q20, from +98.14 in Q1 to +99.98 in Q20. Wheat Price peaks at +100.00 index (level) in Q18, from +98.47 in Q1 to +99.98 in Q20. Gold Price peaks at +5472.24 USD/oz (level) in Q1, from +5472.24 in Q1 to +2031.95 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.38 % vs baseline in Q1, from -0.38 in Q1 to -0.07 in Q20. Services GDP peaks at -1.00 % vs baseline in Q1, from -1.00 in Q1 to +0.01 in Q20. Capital Stock peaks at -0.06 % vs baseline in Q7, from -0.02 in Q1 to -0.05 in Q20.

Timing. The GDP response has mostly faded by Q7 (Q20 is +0.02%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/IN_Y.png)

![CPI Inflation](charts/IN_pi_cpi.png)

![Equity Index](charts/IN_equity.png)

![Gold Price](charts/IN_P_gold.png)

![Wheat Price](charts/IN_P_wheat.png)

![Copper Price](charts/IN_P_copper.png)

![Metals Price](charts/IN_P_metals.png)

![Food Price](charts/IN_P_food.png)

![VIX](charts/IN_vix.png)

![Energy Price](charts/IN_P_energy.png)

![Investment](charts/IN_I.png)

![Gas Price](charts/IN_P_gas.png)

[Q1–Q20 JSON for India](numbers/IN.json)

## CN — China

The main impact of VIX at 80 on China would be a large drop in GDP of 1.79% by Q1. Equities peak at -3.70% in Q1.

Demand and trade. Consumption peaks at -3.03 % vs baseline in Q1, from -3.03 in Q1 to +0.01 in Q20. Investment peaks at -9.87 % vs baseline in Q1, from -9.87 in Q1 to +0.22 in Q20. Net Exports peaks at +0.23 % vs baseline in Q2, from +0.21 in Q1 to +0.06 in Q20. Gov Spending peaks at +0.31 % vs baseline in Q1, from +0.31 in Q1 to -0.01 in Q20. Gov Debt peaks at -0.89 % vs baseline in Q12, from -0.21 in Q1 to -0.81 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.61 % vs baseline in Q19, from +0.04 in Q1 to +0.61 in Q20.

Labour. Employment peaks at -0.58 % vs baseline in Q6, from -0.23 in Q1 to -0.10 in Q20. Unemployment peaks at +0.21 pp in Q4, from +0.12 in Q1 to +0.00 in Q20. Real Wages peaks at -1.28 % vs baseline in Q15, from -0.03 in Q1 to -1.15 in Q20.

Prices. The three-year CPI impulse is -0.73 percentage points. CPI Inflation peaks at -0.17 pp in Q2, from -0.14 in Q1 to +0.01 in Q20. Domestic Infl. peaks at -0.12 pp in Q2, from -0.10 in Q1 to +0.01 in Q20. Marginal Cost peaks at -1.07 % vs baseline in Q1, from -1.07 in Q1 to +0.02 in Q20.

Financial conditions. Policy Rate peaks at -0.64 pp (annualized) in Q7, from -0.21 in Q1 to -0.16 in Q20. Real Rate peaks at -0.16 pp (annualized) in Q7, from -0.05 in Q1 to -0.04 in Q20. Govt 3M Yield peaks at -0.64 pp (annualized) in Q7, from -0.21 in Q1 to -0.16 in Q20. Govt 2Y Yield peaks at -0.59 pp (annualized) in Q4, from -0.52 in Q1 to -0.10 in Q20. Govt 5Y Yield peaks at -0.43 pp (annualized) in Q1, from -0.43 in Q1 to -0.06 in Q20. Govt 10Y Yield peaks at -0.24 pp (annualized) in Q1, from -0.24 in Q1 to -0.05 in Q20. Govt 30Y Yield peaks at -0.10 pp (annualized) in Q1, from -0.10 in Q1 to -0.03 in Q20. Bond Price (7y) peaks at +3.18 % vs baseline in Q7, from +1.06 in Q1 to +0.80 in Q20. Bond Price 3M peaks at +0.16 % vs baseline in Q7, from +0.05 in Q1 to +0.04 in Q20. Bond Price 2Y peaks at +1.13 % vs baseline in Q4, from +1.00 in Q1 to +0.19 in Q20. Bond Price 5Y peaks at +1.92 % vs baseline in Q1, from +1.92 in Q1 to +0.29 in Q20. Bond Price 10Y peaks at +1.98 % vs baseline in Q1, from +1.98 in Q1 to +0.42 in Q20. Bond Price 30Y peaks at +1.79 % vs baseline in Q1, from +1.79 in Q1 to +0.55 in Q20. Equity Index peaks at -3.70 % vs baseline in Q1, from -3.70 in Q1 to +0.10 in Q20. VIX peaks at +80.00 index_level in Q1, from +80.00 in Q1 to +15.57 in Q20. Tobin's Q peaks at -3.27 % vs baseline in Q1, from -3.27 in Q1 to +0.23 in Q20. House Prices peaks at -0.76 % vs baseline in Q8, from -0.27 in Q1 to -0.32 in Q20. Bank Equity peaks at -0.27 % vs baseline in Q7, from -0.09 in Q1 to -0.14 in Q20. Bank Credit peaks at -0.21 % vs baseline in Q7, from -0.07 in Q1 to -0.11 in Q20. Credit Spread peaks at +0.00 pp in Q7, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.26 % vs baseline in Q20, from +0.15 in Q1 to -0.26 in Q20. vs USD peaks at +0.24 % vs baseline in Q1, from +0.24 in Q1 to -0.06 in Q20.

Commodities. Energy Price peaks at +79.86 USD/bbl (level) in Q20, from +77.47 in Q1 to +79.86 in Q20. Metals Price peaks at +99.92 index (level) in Q20, from +97.53 in Q1 to +99.92 in Q20. Food Price peaks at +99.79 index (level) in Q20, from +97.33 in Q1 to +99.79 in Q20. Gas Price peaks at +3.99 USD/mmBtu (level) in Q20, from +3.83 in Q1 to +3.99 in Q20. Copper Price peaks at +99.98 index (level) in Q20, from +98.14 in Q1 to +99.98 in Q20. Wheat Price peaks at +100.00 index (level) in Q18, from +98.47 in Q1 to +99.98 in Q20. Gold Price peaks at +5472.24 USD/oz (level) in Q1, from +5472.24 in Q1 to +2031.95 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.52 % vs baseline in Q1, from -0.52 in Q1 to -0.17 in Q20. Services GDP peaks at -1.04 % vs baseline in Q1, from -1.04 in Q1 to +0.02 in Q20. Capital Stock peaks at -0.07 % vs baseline in Q8, from -0.02 in Q1 to -0.05 in Q20.

Timing. The GDP response has mostly faded by Q9 (Q20 is +0.03%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/CN_Y.png)

![CPI Inflation](charts/CN_pi_cpi.png)

![Equity Index](charts/CN_equity.png)

![Gold Price](charts/CN_P_gold.png)

![Wheat Price](charts/CN_P_wheat.png)

![Copper Price](charts/CN_P_copper.png)

![Metals Price](charts/CN_P_metals.png)

![Food Price](charts/CN_P_food.png)

![VIX](charts/CN_vix.png)

![Energy Price](charts/CN_P_energy.png)

![Investment](charts/CN_I.png)

![Gas Price](charts/CN_P_gas.png)

[Q1–Q20 JSON for China](numbers/CN.json)

## JP — Japan

The main impact of VIX at 80 on Japan would be a large drop in GDP of 1.78% by Q1. Equities peak at -4.97% in Q1.

Demand and trade. Consumption peaks at -2.91 % vs baseline in Q1, from -2.91 in Q1 to -0.13 in Q20. Investment peaks at -10.15 % vs baseline in Q1, from -10.15 in Q1 to -0.57 in Q20. Net Exports peaks at +0.33 % vs baseline in Q2, from +0.28 in Q1 to +0.02 in Q20. Gov Spending peaks at +0.35 % vs baseline in Q1, from +0.35 in Q1 to +0.04 in Q20. Gov Debt peaks at -0.25 % vs baseline in Q20, from -0.04 in Q1 to -0.25 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -0.66 % vs baseline in Q2, from -0.62 in Q1 to +0.01 in Q20.

Labour. Employment peaks at -0.87 % vs baseline in Q4, from -0.44 in Q1 to -0.23 in Q20. Unemployment peaks at +0.58 pp in Q5, from +0.28 in Q1 to +0.20 in Q20. Real Wages peaks at -0.36 % vs baseline in Q20, from -0.00 in Q1 to -0.36 in Q20.

Prices. The three-year CPI impulse is -0.37 percentage points. CPI Inflation peaks at -0.11 pp in Q1, from -0.11 in Q1 to +0.00 in Q20. Domestic Infl. peaks at -0.08 pp in Q1, from -0.08 in Q1 to +0.00 in Q20. Marginal Cost peaks at -1.06 % vs baseline in Q1, from -1.06 in Q1 to -0.11 in Q20.

Financial conditions. Policy Rate peaks at -0.05 pp (annualized) in Q7, from -0.01 in Q1 to -0.02 in Q20. Real Rate peaks at -0.01 pp (annualized) in Q7, from -0.00 in Q1 to -0.00 in Q20. Govt 3M Yield peaks at -0.05 pp (annualized) in Q7, from -0.01 in Q1 to -0.02 in Q20. Govt 2Y Yield peaks at -0.04 pp (annualized) in Q4, from -0.04 in Q1 to -0.02 in Q20. Govt 5Y Yield peaks at -0.03 pp (annualized) in Q2, from -0.03 in Q1 to -0.02 in Q20. Govt 10Y Yield peaks at -0.02 pp (annualized) in Q2, from -0.02 in Q1 to -0.01 in Q20. Govt 30Y Yield peaks at -0.01 pp (annualized) in Q1, from -0.01 in Q1 to -0.01 in Q20. Bond Price (7y) peaks at +0.33 % vs baseline in Q7, from +0.09 in Q1 to +0.14 in Q20. Bond Price 3M peaks at +0.01 % vs baseline in Q7, from +0.00 in Q1 to +0.00 in Q20. Bond Price 2Y peaks at +0.08 % vs baseline in Q4, from +0.07 in Q1 to +0.03 in Q20. Bond Price 5Y peaks at +0.15 % vs baseline in Q2, from +0.15 in Q1 to +0.07 in Q20. Bond Price 10Y peaks at +0.20 % vs baseline in Q2, from +0.20 in Q1 to +0.11 in Q20. Bond Price 30Y peaks at +0.22 % vs baseline in Q1, from +0.22 in Q1 to +0.13 in Q20. Equity Index peaks at -4.97 % vs baseline in Q1, from -4.97 in Q1 to -0.49 in Q20. VIX peaks at +80.00 index_level in Q1, from +80.00 in Q1 to +15.57 in Q20. Tobin's Q peaks at -3.46 % vs baseline in Q1, from -3.46 in Q1 to -0.32 in Q20. House Prices peaks at -0.73 % vs baseline in Q11, from -0.19 in Q1 to -0.64 in Q20. Bank Equity peaks at -0.42 % vs baseline in Q7, from -0.14 in Q1 to -0.22 in Q20. Bank Credit peaks at -0.33 % vs baseline in Q7, from -0.11 in Q1 to -0.17 in Q20. Credit Spread peaks at +0.00 pp in Q7, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.96 % vs baseline in Q3, from +0.82 in Q1 to +0.48 in Q20. vs USD peaks at -0.81 % vs baseline in Q9, from -0.43 in Q1 to -0.67 in Q20.

Commodities. Energy Price peaks at +79.86 USD/bbl (level) in Q20, from +77.47 in Q1 to +79.86 in Q20. Metals Price peaks at +99.92 index (level) in Q20, from +97.53 in Q1 to +99.92 in Q20. Food Price peaks at +99.79 index (level) in Q20, from +97.33 in Q1 to +99.79 in Q20. Gas Price peaks at +3.99 USD/mmBtu (level) in Q20, from +3.83 in Q1 to +3.99 in Q20. Copper Price peaks at +99.98 index (level) in Q20, from +98.14 in Q1 to +99.98 in Q20. Wheat Price peaks at +100.00 index (level) in Q18, from +98.47 in Q1 to +99.98 in Q20. Gold Price peaks at +5472.24 USD/oz (level) in Q1, from +5472.24 in Q1 to +2031.95 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.23 % vs baseline in Q1, from -0.23 in Q1 to -0.05 in Q20. Services GDP peaks at -1.23 % vs baseline in Q1, from -1.23 in Q1 to -0.12 in Q20. Capital Stock peaks at -0.15 % vs baseline in Q20, from -0.02 in Q1 to -0.15 in Q20.

Timing. The GDP response has mostly faded by Q10 (Q20 is -0.18%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/JP_Y.png)

![CPI Inflation](charts/JP_pi_cpi.png)

![Equity Index](charts/JP_equity.png)

![Gold Price](charts/JP_P_gold.png)

![Wheat Price](charts/JP_P_wheat.png)

![Copper Price](charts/JP_P_copper.png)

![Metals Price](charts/JP_P_metals.png)

![Food Price](charts/JP_P_food.png)

![VIX](charts/JP_vix.png)

![Energy Price](charts/JP_P_energy.png)

![Investment](charts/JP_I.png)

![Gas Price](charts/JP_P_gas.png)

[Q1–Q20 JSON for Japan](numbers/JP.json)


---

These figures are model IRFs versus baseline, not forecasts, and not financial advice.
