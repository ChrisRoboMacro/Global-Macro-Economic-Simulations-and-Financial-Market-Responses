# Global Macro Economic Simulations and Financial Market Responses

v6 · IRF · evaluation

**Open the typeset report (this is the document):** https://robomacro.com/GlobalMacroTrainingDataset/risk_250/

GitHub and Hugging Face show `.html` as source code. That is not the report. Read it on robomacro.com, or keep scrolling this page.

## What's the impact of Risk premium +250bp

### Active treatment

```json
{
  "risk_premium": 250.0
}
```

### Assumptions

- Every path is a model impulse response versus baseline, not a forecast.
- The solver and weights are not included.
- English never enters the solver.

### Summary

This report traces the model response to a 250bp rise in the risk premium. Every path is an impulse response versus an unchanged baseline — not a forecast and not market data. The question was: What's the impact of Risk premium +250bp

Argentina sees a -2.32% GDP peak at Q7, with CPI -1.81pp over three years and equities -25.10%. Russia sees a -2.02% GDP peak at Q7, with CPI -1.12pp over three years and equities -25.08%. Nigeria sees a -1.89% GDP peak at Q7, with CPI -1.40pp over three years and equities -25.07%. China sees a -1.81% GDP peak at Q7, with CPI -1.02pp over three years and equities -25.04%.

The remaining countries are smaller spillovers and are covered in the chapters that follow. This material is a model-based summary and is not financial advice.

### Countries by GDP impact

- [AR — Argentina](#ar--argentina) · GDP -2.32% Q7
- [RU — Russia](#ru--russia) · GDP -2.02% Q7
- [NG — Nigeria](#ng--nigeria) · GDP -1.89% Q7
- [CN — China](#cn--china) · GDP -1.81% Q7
- [SA — Saudi Arabia](#sa--saudi-arabia) · GDP -1.76% Q7
- [MY — Malaysia](#my--malaysia) · GDP -1.60% Q7
- [TR — Turkey](#tr--turkey) · GDP -1.58% Q7
- [IN — India](#in--india) · GDP -1.55% Q7
- [TH — Thailand](#th--thailand) · GDP -1.50% Q7
- [MX — Mexico](#mx--mexico) · GDP -1.35% Q7
- [ID — Indonesia](#id--indonesia) · GDP -1.34% Q7
- [BR — Brazil](#br--brazil) · GDP -1.28% Q7
- [CO — Colombia](#co--colombia) · GDP -1.28% Q7
- [NO — Norway](#no--norway) · GDP -1.23% Q7
- [KR — South Korea](#kr--south-korea) · GDP -1.22% Q7
- [CL — Chile](#cl--chile) · GDP -1.18% Q7
- [NL — Netherlands](#nl--netherlands) · GDP -1.18% Q7
- [PL — Poland](#pl--poland) · GDP -1.13% Q7
- [ZA — South Africa](#za--south-africa) · GDP -1.13% Q7
- [CA — Canada](#ca--canada) · GDP -1.11% Q7
- [CH — Switzerland](#ch--switzerland) · GDP -1.10% Q7
- [DE — Germany](#de--germany) · GDP -1.09% Q7
- [FR — France](#fr--france) · GDP -1.04% Q7
- [UK — United Kingdom](#uk--united-kingdom) · GDP -1.02% Q7
- [SE — Sweden](#se--sweden) · GDP -0.96% Q7
- [AU — Australia](#au--australia) · GDP -0.95% Q7
- [US — United States](#us--united-states) · GDP -0.92% Q7
- [ES — Spain](#es--spain) · GDP -0.92% Q7
- [JP — Japan](#jp--japan) · GDP -0.90% Q7
- [IT — Italy](#it--italy) · GDP -0.87% Q7

![AR GDP](charts/global_AR_Y.png)

![RU GDP](charts/global_RU_Y.png)

![NG GDP](charts/global_NG_Y.png)

![CN GDP](charts/global_CN_Y.png)

![US Equity Index](charts/global_US_equity.png)

![US Policy Rate](charts/global_US_i.png)

## AR — Argentina

The main impact of a 250bp rise in the risk premium on Argentina would be a large drop in GDP of 2.32% by Q7. Equities peak at -25.10% in Q1.

Demand and trade. Consumption peaks at -1.14 % vs baseline in Q7, from -0.11 in Q1 to +0.78 in Q20. Investment peaks at -5.17 % vs baseline in Q5, from -1.33 in Q1 to +3.59 in Q20. Net Exports peaks at +0.52 % vs baseline in Q1, from +0.52 in Q1 to -0.13 in Q20. Gov Spending peaks at +0.41 % vs baseline in Q7, from +0.00 in Q1 to -0.31 in Q20. Gov Debt peaks at -1.20 % vs baseline in Q14, from +0.00 in Q1 to -0.81 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +6.88 % vs baseline in Q1, from +6.88 in Q1 to -0.34 in Q20.

Labour. Employment peaks at -1.69 % vs baseline in Q10, from +0.00 in Q1 to +0.36 in Q20. Unemployment peaks at +0.39 pp in Q8, from +0.00 in Q1 to -0.31 in Q20. Real Wages peaks at -3.39 % vs baseline in Q16, from +0.00 in Q1 to -2.65 in Q20.

Prices. The three-year CPI impulse is -1.81 percentage points. CPI Inflation peaks at +0.72 pp in Q1, from +0.72 in Q1 to +0.14 in Q20. Domestic Infl. peaks at +0.51 pp in Q1, from +0.51 in Q1 to +0.10 in Q20. Marginal Cost peaks at -1.39 % vs baseline in Q7, from -0.01 in Q1 to +0.95 in Q20.

Financial conditions. Policy Rate peaks at -1.58 pp (annualized) in Q9, from +0.87 in Q1 to +0.61 in Q20. Real Rate peaks at -0.39 pp (annualized) in Q9, from +0.22 in Q1 to +0.15 in Q20. Govt 3M Yield peaks at -1.58 pp (annualized) in Q9, from +0.87 in Q1 to +0.61 in Q20. Govt 2Y Yield peaks at -1.34 pp (annualized) in Q6, from -0.34 in Q1 to +0.77 in Q20. Govt 5Y Yield peaks at +0.53 pp (annualized) in Q18, from -0.48 in Q1 to +0.49 in Q20. Govt 10Y Yield peaks at +0.22 pp (annualized) in Q17, from -0.01 in Q1 to +0.19 in Q20. Govt 30Y Yield peaks at -0.07 pp (annualized) in Q4, from -0.05 in Q1 to +0.03 in Q20. Bond Price (7y) peaks at +3.95 % vs baseline in Q9, from -2.17 in Q1 to -1.53 in Q20. Bond Price 3M peaks at +0.39 % vs baseline in Q9, from -0.22 in Q1 to -0.15 in Q20. Bond Price 2Y peaks at +2.55 % vs baseline in Q6, from +0.65 in Q1 to -1.47 in Q20. Bond Price 5Y peaks at -2.37 % vs baseline in Q18, from +2.15 in Q1 to -2.22 in Q20. Bond Price 10Y peaks at -1.79 % vs baseline in Q17, from +0.07 in Q1 to -1.56 in Q20. Bond Price 30Y peaks at +1.25 % vs baseline in Q4, from +0.93 in Q1 to -0.54 in Q20. Equity Index peaks at -25.10 % vs baseline in Q1, from -25.10 in Q1 to -2.32 in Q20. VIX peaks at +42.54 index_level in Q1, from +42.54 in Q1 to +20.07 in Q20. Tobin's Q peaks at -3.62 % vs baseline in Q5, from -0.93 in Q1 to +2.51 in Q20. House Prices peaks at -1.65 % vs baseline in Q11, from -0.02 in Q1 to +0.06 in Q20. Bank Equity peaks at -0.40 % vs baseline in Q13, from +0.00 in Q1 to -0.31 in Q20. Bank Credit peaks at -0.82 % vs baseline in Q13, from +0.00 in Q1 to -0.65 in Q20. Credit Spread peaks at +0.24 pp in Q13, from +0.00 in Q1 to +0.19 in Q20.

Nominal FX. NEER peaks at -5.47 % vs baseline in Q1, from -5.47 in Q1 to +0.42 in Q20. vs USD peaks at +7.93 % vs baseline in Q1, from +7.93 in Q1 to +0.72 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.76 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.41 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.46 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.47 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.81 in Q20. Gold Price peaks at +3453.47 USD/oz (level) in Q1, from +3453.47 in Q1 to +2262.69 in Q20.

Sectoral and capital. Manuf. GDP peaks at -2.22 % vs baseline in Q5, from -2.07 in Q1 to +0.42 in Q20. Services GDP peaks at -1.33 % vs baseline in Q7, from -0.01 in Q1 to +0.91 in Q20. Capital Stock peaks at -0.18 % vs baseline in Q11, from -0.01 in Q1 to -0.05 in Q20.

Timing. The GDP response has mostly faded by Q13 (Q20 is +1.59%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/AR_Y.png)

![CPI Inflation](charts/AR_pi_cpi.png)

![Equity Index](charts/AR_equity.png)

![Gold Price](charts/AR_P_gold.png)

![Metals Price](charts/AR_P_metals.png)

![Food Price](charts/AR_P_food.png)

![Copper Price](charts/AR_P_copper.png)

![Wheat Price](charts/AR_P_wheat.png)

![Energy Price](charts/AR_P_energy.png)

![VIX](charts/AR_vix.png)

![vs USD](charts/AR_USD.png)

![Real Exchange Rate](charts/AR_RER.png)

[Q1–Q20 JSON for Argentina](numbers/AR.json)

## RU — Russia

The main impact of a 250bp rise in the risk premium on Russia would be a large drop in GDP of 2.02% by Q7. Equities peak at -25.08% in Q1.

Demand and trade. Consumption peaks at -1.12 % vs baseline in Q8, from -0.03 in Q1 to -0.18 in Q20. Investment peaks at -5.04 % vs baseline in Q6, from -0.33 in Q1 to -0.11 in Q20. Net Exports peaks at -0.48 % vs baseline in Q9, from +0.24 in Q1 to -0.05 in Q20. Gov Spending peaks at +0.15 % vs baseline in Q6, from +0.00 in Q1 to +0.02 in Q20. Gov Debt peaks at -0.76 % vs baseline in Q16, from +0.00 in Q1 to -0.72 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +2.36 % vs baseline in Q1, from +2.36 in Q1 to +0.06 in Q20.

Labour. Employment peaks at -1.60 % vs baseline in Q12, from +0.00 in Q1 to -0.94 in Q20. Unemployment peaks at +0.64 pp in Q10, from +0.00 in Q1 to +0.23 in Q20. Real Wages peaks at -3.30 % vs baseline in Q20, from +0.00 in Q1 to -3.30 in Q20.

Prices. The three-year CPI impulse is -1.12 percentage points. CPI Inflation peaks at +0.28 pp in Q1, from +0.28 in Q1 to -0.02 in Q20. Domestic Infl. peaks at +0.20 pp in Q1, from +0.20 in Q1 to -0.02 in Q20. Marginal Cost peaks at -1.21 % vs baseline in Q7, from -0.00 in Q1 to -0.14 in Q20.

Financial conditions. Policy Rate peaks at -0.87 pp (annualized) in Q11, from +0.21 in Q1 to -0.30 in Q20. Real Rate peaks at -0.22 pp (annualized) in Q11, from +0.05 in Q1 to -0.08 in Q20. Govt 3M Yield peaks at -0.87 pp (annualized) in Q11, from +0.21 in Q1 to -0.30 in Q20. Govt 2Y Yield peaks at -0.79 pp (annualized) in Q8, from -0.17 in Q1 to -0.16 in Q20. Govt 5Y Yield peaks at -0.53 pp (annualized) in Q5, from -0.46 in Q1 to -0.11 in Q20. Govt 10Y Yield peaks at -0.31 pp (annualized) in Q5, from -0.28 in Q1 to -0.12 in Q20. Govt 30Y Yield peaks at -0.14 pp (annualized) in Q5, from -0.13 in Q1 to -0.06 in Q20. Bond Price (7y) peaks at +2.70 % vs baseline in Q11, from -0.66 in Q1 to +0.95 in Q20. Bond Price 3M peaks at +0.22 % vs baseline in Q11, from -0.05 in Q1 to +0.08 in Q20. Bond Price 2Y peaks at +1.50 % vs baseline in Q8, from +0.31 in Q1 to +0.30 in Q20. Bond Price 5Y peaks at +2.37 % vs baseline in Q5, from +2.07 in Q1 to +0.51 in Q20. Bond Price 10Y peaks at +2.54 % vs baseline in Q5, from +2.31 in Q1 to +0.95 in Q20. Bond Price 30Y peaks at +2.52 % vs baseline in Q5, from +2.42 in Q1 to +1.12 in Q20. Equity Index peaks at -25.08 % vs baseline in Q1, from -25.08 in Q1 to -5.31 in Q20. VIX peaks at +42.54 index_level in Q1, from +42.54 in Q1 to +20.07 in Q20. Tobin's Q peaks at -3.53 % vs baseline in Q6, from -0.23 in Q1 to -0.07 in Q20. House Prices peaks at -1.85 % vs baseline in Q14, from -0.00 in Q1 to -1.53 in Q20. Bank Equity peaks at -0.47 % vs baseline in Q14, from +0.00 in Q1 to -0.37 in Q20. Bank Credit peaks at -0.41 % vs baseline in Q14, from +0.00 in Q1 to -0.33 in Q20. Credit Spread peaks at +0.01 pp in Q14, from +0.00 in Q1 to +0.01 in Q20.

Nominal FX. NEER peaks at -1.14 % vs baseline in Q1, from -1.14 in Q1 to +0.77 in Q20. vs USD peaks at +3.41 % vs baseline in Q1, from +3.41 in Q1 to +1.11 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.76 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.41 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.46 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.47 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.81 in Q20. Gold Price peaks at +3453.47 USD/oz (level) in Q1, from +3453.47 in Q1 to +2262.69 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.99 % vs baseline in Q6, from -0.71 in Q1 to -0.06 in Q20. Services GDP peaks at -1.11 % vs baseline in Q7, from -0.00 in Q1 to -0.13 in Q20. Capital Stock peaks at -0.24 % vs baseline in Q20, from -0.00 in Q1 to -0.24 in Q20.

Timing. The GDP response has mostly faded by Q18 (Q20 is -0.23%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/RU_Y.png)

![CPI Inflation](charts/RU_pi_cpi.png)

![Equity Index](charts/RU_equity.png)

![Gold Price](charts/RU_P_gold.png)

![Metals Price](charts/RU_P_metals.png)

![Food Price](charts/RU_P_food.png)

![Copper Price](charts/RU_P_copper.png)

![Wheat Price](charts/RU_P_wheat.png)

![Energy Price](charts/RU_P_energy.png)

![VIX](charts/RU_vix.png)

![Investment](charts/RU_I.png)

![Gas Price](charts/RU_P_gas.png)

[Q1–Q20 JSON for Russia](numbers/RU.json)

## NG — Nigeria

The main impact of a 250bp rise in the risk premium on Nigeria would be a large drop in GDP of 1.89% by Q7. Equities peak at -25.07% in Q1.

Demand and trade. Consumption peaks at -1.09 % vs baseline in Q8, from -0.06 in Q1 to +0.07 in Q20. Investment peaks at -4.50 % vs baseline in Q6, from -0.65 in Q1 to +0.64 in Q20. Net Exports peaks at +0.42 % vs baseline in Q1, from +0.42 in Q1 to -0.01 in Q20. Gov Spending peaks at +0.24 % vs baseline in Q7, from +0.00 in Q1 to -0.04 in Q20. Gov Debt peaks at -3.81 % vs baseline in Q16, from +0.00 in Q1 to -3.66 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +4.20 % vs baseline in Q1, from +4.20 in Q1 to +0.29 in Q20.

Labour. Employment peaks at -1.27 % vs baseline in Q12, from +0.00 in Q1 to -0.69 in Q20. Unemployment peaks at +0.12 pp in Q8, from +0.00 in Q1 to -0.01 in Q20. Real Wages peaks at -2.74 % vs baseline in Q19, from +0.00 in Q1 to -2.71 in Q20.

Prices. The three-year CPI impulse is -1.40 percentage points. CPI Inflation peaks at +0.59 pp in Q1, from +0.59 in Q1 to +0.03 in Q20. Domestic Infl. peaks at +0.41 pp in Q1, from +0.41 in Q1 to +0.02 in Q20. Marginal Cost peaks at -1.13 % vs baseline in Q7, from -0.00 in Q1 to +0.12 in Q20.

Financial conditions. Policy Rate peaks at -1.05 pp (annualized) in Q10, from +0.42 in Q1 to -0.03 in Q20. Real Rate peaks at -0.26 pp (annualized) in Q10, from +0.11 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -1.05 pp (annualized) in Q10, from +0.42 in Q1 to -0.03 in Q20. Govt 2Y Yield peaks at -0.92 pp (annualized) in Q7, from -0.18 in Q1 to +0.10 in Q20. Govt 5Y Yield peaks at -0.48 pp (annualized) in Q4, from -0.44 in Q1 to +0.03 in Q20. Govt 10Y Yield peaks at -0.25 pp (annualized) in Q5, from -0.21 in Q1 to -0.03 in Q20. Govt 30Y Yield peaks at -0.11 pp (annualized) in Q5, from -0.10 in Q1 to -0.03 in Q20. Bond Price (7y) peaks at +2.62 % vs baseline in Q10, from -1.06 in Q1 to +0.07 in Q20. Bond Price 3M peaks at +0.26 % vs baseline in Q10, from -0.11 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +1.75 % vs baseline in Q7, from +0.33 in Q1 to -0.19 in Q20. Bond Price 5Y peaks at +2.18 % vs baseline in Q4, from +1.98 in Q1 to -0.14 in Q20. Bond Price 10Y peaks at +2.03 % vs baseline in Q5, from +1.69 in Q1 to +0.28 in Q20. Bond Price 30Y peaks at +1.98 % vs baseline in Q5, from +1.80 in Q1 to +0.51 in Q20. Equity Index peaks at -25.07 % vs baseline in Q1, from -25.07 in Q1 to -4.61 in Q20. VIX peaks at +42.54 index_level in Q1, from +42.54 in Q1 to +20.07 in Q20. Tobin's Q peaks at -3.15 % vs baseline in Q6, from -0.45 in Q1 to +0.45 in Q20. House Prices peaks at -1.58 % vs baseline in Q13, from -0.01 in Q1 to -0.99 in Q20. Bank Equity peaks at -0.36 % vs baseline in Q13, from +0.00 in Q1 to -0.29 in Q20. Bank Credit peaks at -0.65 % vs baseline in Q13, from +0.00 in Q1 to -0.52 in Q20. Credit Spread peaks at +0.09 pp in Q13, from +0.00 in Q1 to +0.07 in Q20.

Nominal FX. NEER peaks at -3.09 % vs baseline in Q1, from -3.09 in Q1 to -0.07 in Q20. vs USD peaks at +5.25 % vs baseline in Q1, from +5.25 in Q1 to +1.35 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.76 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.41 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.46 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.47 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.81 in Q20. Gold Price peaks at +3453.47 USD/oz (level) in Q1, from +3453.47 in Q1 to +2262.69 in Q20.

Sectoral and capital. Manuf. GDP peaks at -1.26 % vs baseline in Q1, from -1.26 in Q1 to -0.07 in Q20. Services GDP peaks at -0.94 % vs baseline in Q7, from -0.00 in Q1 to +0.10 in Q20. Capital Stock peaks at -0.18 % vs baseline in Q15, from -0.00 in Q1 to -0.17 in Q20.

Timing. The GDP response has mostly faded by Q15 (Q20 is +0.20%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/NG_Y.png)

![CPI Inflation](charts/NG_pi_cpi.png)

![Equity Index](charts/NG_equity.png)

![Gold Price](charts/NG_P_gold.png)

![Metals Price](charts/NG_P_metals.png)

![Food Price](charts/NG_P_food.png)

![Copper Price](charts/NG_P_copper.png)

![Wheat Price](charts/NG_P_wheat.png)

![Energy Price](charts/NG_P_energy.png)

![VIX](charts/NG_vix.png)

![vs USD](charts/NG_USD.png)

![Investment](charts/NG_I.png)

[Q1–Q20 JSON for Nigeria](numbers/NG.json)

## CN — China

The main impact of a 250bp rise in the risk premium on China would be a large drop in GDP of 1.81% by Q7. Equities peak at -25.04% in Q1.

Demand and trade. Consumption peaks at -1.35 % vs baseline in Q7, from -0.00 in Q1 to -0.26 in Q20. Investment peaks at -4.25 % vs baseline in Q6, from -0.04 in Q1 to +0.56 in Q20. Net Exports peaks at +0.38 % vs baseline in Q8, from +0.09 in Q1 to +0.17 in Q20. Gov Spending peaks at +0.31 % vs baseline in Q7, from +0.00 in Q1 to +0.05 in Q20. Gov Debt peaks at -2.03 % vs baseline in Q20, from +0.00 in Q1 to -2.03 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +1.85 % vs baseline in Q14, from +0.97 in Q1 to +1.58 in Q20.

Labour. Employment peaks at -1.21 % vs baseline in Q13, from +0.00 in Q1 to -0.89 in Q20. Unemployment peaks at +0.35 pp in Q10, from +0.00 in Q1 to +0.13 in Q20. Real Wages peaks at -2.68 % vs baseline in Q20, from +0.00 in Q1 to -2.68 in Q20.

Prices. The three-year CPI impulse is -1.02 percentage points. CPI Inflation peaks at -0.16 pp in Q7, from +0.07 in Q1 to -0.01 in Q20. Domestic Infl. peaks at -0.11 pp in Q7, from +0.05 in Q1 to -0.01 in Q20. Marginal Cost peaks at -1.08 % vs baseline in Q7, from -0.00 in Q1 to -0.17 in Q20.

Financial conditions. Policy Rate peaks at -1.17 pp (annualized) in Q13, from +0.02 in Q1 to -0.86 in Q20. Real Rate peaks at -0.29 pp (annualized) in Q13, from +0.00 in Q1 to -0.21 in Q20. Govt 3M Yield peaks at -1.17 pp (annualized) in Q13, from +0.02 in Q1 to -0.86 in Q20. Govt 2Y Yield peaks at -1.12 pp (annualized) in Q10, from -0.35 in Q1 to -0.65 in Q20. Govt 5Y Yield peaks at -0.91 pp (annualized) in Q6, from -0.77 in Q1 to -0.44 in Q20. Govt 10Y Yield peaks at -0.61 pp (annualized) in Q4, from -0.59 in Q1 to -0.31 in Q20. Govt 30Y Yield peaks at -0.27 pp (annualized) in Q3, from -0.27 in Q1 to -0.15 in Q20. Bond Price (7y) peaks at +5.84 % vs baseline in Q13, from -0.08 in Q1 to +4.28 in Q20. Bond Price 3M peaks at +0.29 % vs baseline in Q13, from -0.00 in Q1 to +0.21 in Q20. Bond Price 2Y peaks at +2.13 % vs baseline in Q10, from +0.66 in Q1 to +1.24 in Q20. Bond Price 5Y peaks at +4.09 % vs baseline in Q6, from +3.48 in Q1 to +2.00 in Q20. Bond Price 10Y peaks at +4.97 % vs baseline in Q4, from +4.86 in Q1 to +2.52 in Q20. Bond Price 30Y peaks at +4.78 % vs baseline in Q3, from +4.77 in Q1 to +2.65 in Q20. Equity Index peaks at -25.04 % vs baseline in Q1, from -25.04 in Q1 to -5.63 in Q20. VIX peaks at +42.54 index_level in Q1, from +42.54 in Q1 to +20.07 in Q20. Tobin's Q peaks at -2.98 % vs baseline in Q6, from -0.02 in Q1 to +0.39 in Q20. House Prices peaks at -1.56 % vs baseline in Q14, from -0.00 in Q1 to -1.27 in Q20. Bank Equity peaks at -0.54 % vs baseline in Q13, from +0.00 in Q1 to -0.42 in Q20. Bank Credit peaks at -0.41 % vs baseline in Q13, from +0.00 in Q1 to -0.33 in Q20. Credit Spread peaks at +0.00 pp in Q13, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -2.07 % vs baseline in Q17, from -0.21 in Q1 to -1.97 in Q20. vs USD peaks at +2.66 % vs baseline in Q18, from +2.02 in Q1 to +2.63 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.76 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.41 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.46 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.47 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.81 in Q20. Gold Price peaks at +3453.47 USD/oz (level) in Q1, from +3453.47 in Q1 to +2262.69 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.94 % vs baseline in Q8, from -0.29 in Q1 to -0.56 in Q20. Services GDP peaks at -1.05 % vs baseline in Q7, from -0.00 in Q1 to -0.17 in Q20. Capital Stock peaks at -0.17 % vs baseline in Q16, from -0.00 in Q1 to -0.17 in Q20.

Timing. The GDP response has mostly faded by Q18 (Q20 is -0.29%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/CN_Y.png)

![CPI Inflation](charts/CN_pi_cpi.png)

![Equity Index](charts/CN_equity.png)

![Gold Price](charts/CN_P_gold.png)

![Metals Price](charts/CN_P_metals.png)

![Food Price](charts/CN_P_food.png)

![Copper Price](charts/CN_P_copper.png)

![Wheat Price](charts/CN_P_wheat.png)

![Energy Price](charts/CN_P_energy.png)

![VIX](charts/CN_vix.png)

![Bond Price (7y)](charts/CN_Q_B.png)

![Bond Price 10Y](charts/CN_Q_B_10y.png)

[Q1–Q20 JSON for China](numbers/CN.json)

## SA — Saudi Arabia

The main impact of a 250bp rise in the risk premium on Saudi Arabia would be a large drop in GDP of 1.76% by Q7. Equities peak at -25.05% in Q1.

Demand and trade. Consumption peaks at -1.12 % vs baseline in Q8, from +0.00 in Q1 to -0.41 in Q20. Investment peaks at -4.20 % vs baseline in Q6, from +0.02 in Q1 to -1.43 in Q20. Net Exports peaks at -0.77 % vs baseline in Q8, from +0.00 in Q1 to +0.04 in Q20. Gov Spending peaks at -0.09 % vs baseline in Q9, from +0.00 in Q1 to +0.07 in Q20. Gov Debt peaks at -2.84 % vs baseline in Q20, from +0.00 in Q1 to -2.84 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.49 % vs baseline in Q17, from +0.00 in Q1 to +0.46 in Q20.

Labour. Employment peaks at -1.59 % vs baseline in Q12, from +0.00 in Q1 to -1.06 in Q20. Unemployment peaks at +0.60 pp in Q11, from +0.00 in Q1 to +0.34 in Q20. Real Wages peaks at -1.92 % vs baseline in Q20, from +0.00 in Q1 to -1.92 in Q20.

Prices. The three-year CPI impulse is -0.72 percentage points. CPI Inflation peaks at -0.10 pp in Q7, from +0.00 in Q1 to -0.01 in Q20. Domestic Infl. peaks at -0.07 pp in Q7, from +0.00 in Q1 to -0.01 in Q20. Marginal Cost peaks at -1.06 % vs baseline in Q7, from -0.00 in Q1 to -0.33 in Q20.

Financial conditions. Policy Rate peaks at -0.70 pp (annualized) in Q10, from -0.02 in Q1 to -0.03 in Q20. Real Rate peaks at -0.18 pp (annualized) in Q10, from -0.01 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -0.70 pp (annualized) in Q10, from -0.02 in Q1 to -0.03 in Q20. Govt 2Y Yield peaks at -0.62 pp (annualized) in Q7, from -0.30 in Q1 to +0.09 in Q20. Govt 5Y Yield peaks at -0.37 pp (annualized) in Q1, from -0.37 in Q1 to +0.11 in Q20. Govt 10Y Yield peaks at -0.13 pp (annualized) in Q1, from -0.13 in Q1 to +0.07 in Q20. Govt 30Y Yield peaks at -0.04 pp (annualized) in Q1, from -0.04 in Q1 to +0.02 in Q20. Bond Price (7y) peaks at +3.51 % vs baseline in Q10, from -0.14 in Q1 to +0.44 in Q20. Bond Price 3M peaks at +0.18 % vs baseline in Q10, from +0.01 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +1.19 % vs baseline in Q7, from +0.58 in Q1 to -0.17 in Q20. Bond Price 5Y peaks at +1.69 % vs baseline in Q1, from +1.69 in Q1 to -0.50 in Q20. Bond Price 10Y peaks at +1.06 % vs baseline in Q1, from +1.06 in Q1 to -0.59 in Q20. Bond Price 30Y peaks at +0.67 % vs baseline in Q1, from +0.67 in Q1 to -0.45 in Q20. Equity Index peaks at -25.05 % vs baseline in Q1, from -25.05 in Q1 to -7.23 in Q20. VIX peaks at +42.54 index_level in Q1, from +42.54 in Q1 to +20.07 in Q20. Tobin's Q peaks at -2.94 % vs baseline in Q6, from +0.01 in Q1 to -1.00 in Q20. House Prices peaks at -1.79 % vs baseline in Q16, from -0.00 in Q1 to -1.70 in Q20. Bank Equity peaks at -0.48 % vs baseline in Q14, from +0.00 in Q1 to -0.38 in Q20. Bank Credit peaks at -0.41 % vs baseline in Q14, from +0.00 in Q1 to -0.32 in Q20. Credit Spread peaks at +0.01 pp in Q14, from +0.00 in Q1 to +0.01 in Q20.

Nominal FX. NEER peaks at +0.69 % vs baseline in Q1, from +0.69 in Q1 to -0.42 in Q20. vs USD peaks at +1.51 % vs baseline in Q20, from +1.05 in Q1 to +1.51 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.76 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.41 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.46 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.47 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.81 in Q20. Gold Price peaks at +3453.47 USD/oz (level) in Q1, from +3453.47 in Q1 to +2262.69 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.28 % vs baseline in Q12, from -0.00 in Q1 to -0.22 in Q20. Services GDP peaks at -0.78 % vs baseline in Q7, from -0.00 in Q1 to -0.24 in Q20. Capital Stock peaks at -0.25 % vs baseline in Q20, from +0.00 in Q1 to -0.25 in Q20.

Timing. By Q20 GDP is still -0.55% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/SA_Y.png)

![CPI Inflation](charts/SA_pi_cpi.png)

![Equity Index](charts/SA_equity.png)

![Gold Price](charts/SA_P_gold.png)

![Metals Price](charts/SA_P_metals.png)

![Food Price](charts/SA_P_food.png)

![Copper Price](charts/SA_P_copper.png)

![Wheat Price](charts/SA_P_wheat.png)

![Energy Price](charts/SA_P_energy.png)

![VIX](charts/SA_vix.png)

![Investment](charts/SA_I.png)

![Gas Price](charts/SA_P_gas.png)

[Q1–Q20 JSON for Saudi Arabia](numbers/SA.json)

## MY — Malaysia

The main impact of a 250bp rise in the risk premium on Malaysia would be a large drop in GDP of 1.60% by Q7. Equities peak at -25.06% in Q1.

Demand and trade. Consumption peaks at -1.13 % vs baseline in Q8, from -0.02 in Q1 to -0.31 in Q20. Investment peaks at -4.14 % vs baseline in Q6, from -0.27 in Q1 to -0.55 in Q20. Net Exports peaks at +0.43 % vs baseline in Q1, from +0.43 in Q1 to +0.17 in Q20. Gov Spending peaks at +0.22 % vs baseline in Q7, from +0.00 in Q1 to +0.06 in Q20. Gov Debt peaks at -2.18 % vs baseline in Q17, from +0.00 in Q1 to -2.13 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +1.42 % vs baseline in Q1, from +1.42 in Q1 to +0.42 in Q20.

Labour. Employment peaks at -1.38 % vs baseline in Q12, from +0.00 in Q1 to -0.86 in Q20. Unemployment peaks at +0.33 pp in Q10, from +0.00 in Q1 to +0.14 in Q20. Real Wages peaks at -1.98 % vs baseline in Q20, from +0.00 in Q1 to -1.98 in Q20.

Prices. The three-year CPI impulse is -0.25 percentage points. CPI Inflation peaks at +0.47 pp in Q1, from +0.47 in Q1 to +0.01 in Q20. Domestic Infl. peaks at +0.33 pp in Q1, from +0.33 in Q1 to +0.01 in Q20. Marginal Cost peaks at -0.96 % vs baseline in Q7, from -0.00 in Q1 to -0.22 in Q20.

Financial conditions. Policy Rate peaks at -0.55 pp (annualized) in Q11, from +0.17 in Q1 to -0.28 in Q20. Real Rate peaks at -0.14 pp (annualized) in Q11, from +0.04 in Q1 to -0.07 in Q20. Govt 3M Yield peaks at -0.55 pp (annualized) in Q11, from +0.17 in Q1 to -0.28 in Q20. Govt 2Y Yield peaks at -0.51 pp (annualized) in Q9, from -0.07 in Q1 to -0.19 in Q20. Govt 5Y Yield peaks at -0.37 pp (annualized) in Q6, from -0.30 in Q1 to -0.14 in Q20. Govt 10Y Yield peaks at -0.24 pp (annualized) in Q5, from -0.22 in Q1 to -0.11 in Q20. Govt 30Y Yield peaks at -0.10 pp (annualized) in Q5, from -0.10 in Q1 to -0.05 in Q20. Bond Price (7y) peaks at +2.30 % vs baseline in Q11, from -0.70 in Q1 to +1.16 in Q20. Bond Price 3M peaks at +0.14 % vs baseline in Q11, from -0.04 in Q1 to +0.07 in Q20. Bond Price 2Y peaks at +0.98 % vs baseline in Q9, from +0.14 in Q1 to +0.36 in Q20. Bond Price 5Y peaks at +1.67 % vs baseline in Q6, from +1.36 in Q1 to +0.64 in Q20. Bond Price 10Y peaks at +1.98 % vs baseline in Q5, from +1.78 in Q1 to +0.93 in Q20. Bond Price 30Y peaks at +1.88 % vs baseline in Q5, from +1.79 in Q1 to +0.95 in Q20. Equity Index peaks at -25.06 % vs baseline in Q1, from -25.06 in Q1 to -5.98 in Q20. VIX peaks at +42.54 index_level in Q1, from +42.54 in Q1 to +20.07 in Q20. Tobin's Q peaks at -2.90 % vs baseline in Q6, from -0.19 in Q1 to -0.38 in Q20. House Prices peaks at -1.81 % vs baseline in Q15, from -0.00 in Q1 to -1.62 in Q20. Bank Equity peaks at -0.47 % vs baseline in Q13, from +0.00 in Q1 to -0.37 in Q20. Bank Credit peaks at -0.37 % vs baseline in Q13, from +0.00 in Q1 to -0.29 in Q20. Credit Spread peaks at +0.01 pp in Q13, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.75 % vs baseline in Q1, from -0.75 in Q1 to -0.34 in Q20. vs USD peaks at +2.47 % vs baseline in Q1, from +2.47 in Q1 to +1.48 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.76 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.41 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.46 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.47 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.81 in Q20. Gold Price peaks at +3453.47 USD/oz (level) in Q1, from +3453.47 in Q1 to +2262.69 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.69 % vs baseline in Q6, from -0.43 in Q1 to -0.22 in Q20. Services GDP peaks at -0.91 % vs baseline in Q7, from -0.00 in Q1 to -0.21 in Q20. Capital Stock peaks at -0.21 % vs baseline in Q20, from -0.00 in Q1 to -0.21 in Q20.

Timing. The GDP response has mostly faded by Q20 (Q20 is -0.37%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/MY_Y.png)

![CPI Inflation](charts/MY_pi_cpi.png)

![Equity Index](charts/MY_equity.png)

![Gold Price](charts/MY_P_gold.png)

![Metals Price](charts/MY_P_metals.png)

![Food Price](charts/MY_P_food.png)

![Copper Price](charts/MY_P_copper.png)

![Wheat Price](charts/MY_P_wheat.png)

![Energy Price](charts/MY_P_energy.png)

![VIX](charts/MY_vix.png)

![Investment](charts/MY_I.png)

![Gas Price](charts/MY_P_gas.png)

[Q1–Q20 JSON for Malaysia](numbers/MY.json)

## TR — Turkey

The main impact of a 250bp rise in the risk premium on Turkey would be a large drop in GDP of 1.58% by Q7. Equities peak at -25.09% in Q1.

Demand and trade. Consumption peaks at -0.90 % vs baseline in Q8, from -0.11 in Q1 to +0.10 in Q20. Investment peaks at -3.95 % vs baseline in Q5, from -1.29 in Q1 to +0.84 in Q20. Net Exports peaks at +0.89 % vs baseline in Q7, from +0.68 in Q1 to +0.10 in Q20. Gov Spending peaks at +0.28 % vs baseline in Q7, from +0.00 in Q1 to -0.04 in Q20. Gov Debt peaks at -1.17 % vs baseline in Q15, from +0.00 in Q1 to -1.00 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +4.82 % vs baseline in Q1, from +4.82 in Q1 to +0.68 in Q20.

Labour. Employment peaks at -1.20 % vs baseline in Q12, from +0.00 in Q1 to -0.49 in Q20. Unemployment peaks at +0.32 pp in Q9, from +0.00 in Q1 to +0.01 in Q20. Real Wages peaks at -2.33 % vs baseline in Q20, from +0.00 in Q1 to -2.33 in Q20.

Prices. The three-year CPI impulse is -0.26 percentage points. CPI Inflation peaks at +0.81 pp in Q1, from +0.81 in Q1 to -0.01 in Q20. Domestic Infl. peaks at +0.57 pp in Q1, from +0.57 in Q1 to -0.01 in Q20. Marginal Cost peaks at -0.94 % vs baseline in Q7, from -0.01 in Q1 to +0.15 in Q20.

Financial conditions. Policy Rate peaks at +0.91 pp (annualized) in Q2, from +0.84 in Q1 to -0.07 in Q20. Real Rate peaks at +0.23 pp (annualized) in Q2, from +0.21 in Q1 to -0.02 in Q20. Govt 3M Yield peaks at +0.91 pp (annualized) in Q2, from +0.84 in Q1 to -0.07 in Q20. Govt 2Y Yield peaks at -0.73 pp (annualized) in Q7, from +0.14 in Q1 to +0.04 in Q20. Govt 5Y Yield peaks at -0.39 pp (annualized) in Q5, from -0.26 in Q1 to +0.01 in Q20. Govt 10Y Yield peaks at -0.20 pp (annualized) in Q6, from -0.12 in Q1 to -0.02 in Q20. Govt 30Y Yield peaks at -0.08 pp (annualized) in Q5, from -0.06 in Q1 to -0.02 in Q20. Bond Price (7y) peaks at -2.84 % vs baseline in Q2, from -2.63 in Q1 to +0.22 in Q20. Bond Price 3M peaks at -0.23 % vs baseline in Q2, from -0.21 in Q1 to +0.02 in Q20. Bond Price 2Y peaks at +1.39 % vs baseline in Q7, from -0.27 in Q1 to -0.07 in Q20. Bond Price 5Y peaks at +1.75 % vs baseline in Q5, from +1.16 in Q1 to -0.03 in Q20. Bond Price 10Y peaks at +1.65 % vs baseline in Q6, from +1.02 in Q1 to +0.18 in Q20. Bond Price 30Y peaks at +1.44 % vs baseline in Q5, from +1.02 in Q1 to +0.27 in Q20. Equity Index peaks at -25.09 % vs baseline in Q1, from -25.09 in Q1 to -4.48 in Q20. VIX peaks at +42.54 index_level in Q1, from +42.54 in Q1 to +20.07 in Q20. Tobin's Q peaks at -2.76 % vs baseline in Q5, from -0.90 in Q1 to +0.59 in Q20. House Prices peaks at -1.39 % vs baseline in Q12, from -0.02 in Q1 to -0.82 in Q20. Bank Equity peaks at -0.30 % vs baseline in Q13, from +0.00 in Q1 to -0.23 in Q20. Bank Credit peaks at -0.26 % vs baseline in Q13, from +0.00 in Q1 to -0.21 in Q20. Credit Spread peaks at +0.02 pp in Q13, from +0.00 in Q1 to +0.02 in Q20.

Nominal FX. NEER peaks at -4.03 % vs baseline in Q1, from -4.03 in Q1 to -0.64 in Q20. vs USD peaks at +5.87 % vs baseline in Q1, from +5.87 in Q1 to +1.74 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.76 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.41 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.46 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.47 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.81 in Q20. Gold Price peaks at +3453.47 USD/oz (level) in Q1, from +3453.47 in Q1 to +2262.69 in Q20.

Sectoral and capital. Manuf. GDP peaks at -1.55 % vs baseline in Q5, from -1.45 in Q1 to -0.13 in Q20. Services GDP peaks at -0.96 % vs baseline in Q7, from -0.01 in Q1 to +0.15 in Q20. Capital Stock peaks at -0.17 % vs baseline in Q14, from -0.01 in Q1 to -0.15 in Q20.

Timing. The GDP response has mostly faded by Q15 (Q20 is +0.24%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/TR_Y.png)

![CPI Inflation](charts/TR_pi_cpi.png)

![Equity Index](charts/TR_equity.png)

![Gold Price](charts/TR_P_gold.png)

![Metals Price](charts/TR_P_metals.png)

![Food Price](charts/TR_P_food.png)

![Copper Price](charts/TR_P_copper.png)

![Wheat Price](charts/TR_P_wheat.png)

![Energy Price](charts/TR_P_energy.png)

![VIX](charts/TR_vix.png)

![vs USD](charts/TR_USD.png)

![Real Exchange Rate](charts/TR_RER.png)

[Q1–Q20 JSON for Turkey](numbers/TR.json)

## IN — India

The main impact of a 250bp rise in the risk premium on India would be a large drop in GDP of 1.55% by Q7. Equities peak at -25.07% in Q1.

Demand and trade. Consumption peaks at -0.92 % vs baseline in Q7, from -0.03 in Q1 to +0.06 in Q20. Investment peaks at -3.64 % vs baseline in Q5, from -0.31 in Q1 to +0.58 in Q20. Net Exports peaks at +0.42 % vs baseline in Q7, from +0.27 in Q1 to -0.03 in Q20. Gov Spending peaks at +0.26 % vs baseline in Q7, from +0.00 in Q1 to -0.03 in Q20. Gov Debt peaks at -1.78 % vs baseline in Q15, from +0.00 in Q1 to -1.60 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +2.41 % vs baseline in Q1, from +2.41 in Q1 to -0.20 in Q20.

Labour. Employment peaks at -0.96 % vs baseline in Q12, from +0.00 in Q1 to -0.54 in Q20. Unemployment peaks at +0.10 pp in Q8, from +0.00 in Q1 to -0.00 in Q20. Real Wages peaks at -2.18 % vs baseline in Q20, from +0.00 in Q1 to -2.18 in Q20.

Prices. The three-year CPI impulse is -1.24 percentage points. CPI Inflation peaks at +0.26 pp in Q1, from +0.26 in Q1 to +0.03 in Q20. Domestic Infl. peaks at +0.19 pp in Q1, from +0.19 in Q1 to +0.02 in Q20. Marginal Cost peaks at -0.92 % vs baseline in Q7, from -0.00 in Q1 to +0.10 in Q20.

Financial conditions. Policy Rate peaks at -0.97 pp (annualized) in Q10, from +0.20 in Q1 to -0.04 in Q20. Real Rate peaks at -0.24 pp (annualized) in Q10, from +0.05 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -0.97 pp (annualized) in Q10, from +0.20 in Q1 to -0.04 in Q20. Govt 2Y Yield peaks at -0.85 pp (annualized) in Q7, from -0.23 in Q1 to +0.10 in Q20. Govt 5Y Yield peaks at -0.46 pp (annualized) in Q4, from -0.44 in Q1 to +0.07 in Q20. Govt 10Y Yield peaks at -0.21 pp (annualized) in Q5, from -0.19 in Q1 to +0.00 in Q20. Govt 30Y Yield peaks at -0.09 pp (annualized) in Q4, from -0.08 in Q1 to -0.01 in Q20. Bond Price (7y) peaks at +4.83 % vs baseline in Q10, from -0.99 in Q1 to +0.20 in Q20. Bond Price 3M peaks at +0.24 % vs baseline in Q10, from -0.05 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +1.62 % vs baseline in Q7, from +0.43 in Q1 to -0.19 in Q20. Bond Price 5Y peaks at +2.06 % vs baseline in Q4, from +1.98 in Q1 to -0.30 in Q20. Bond Price 10Y peaks at +1.71 % vs baseline in Q5, from +1.54 in Q1 to -0.02 in Q20. Bond Price 30Y peaks at +1.57 % vs baseline in Q4, from +1.48 in Q1 to +0.18 in Q20. Equity Index peaks at -25.07 % vs baseline in Q1, from -25.07 in Q1 to -4.49 in Q20. VIX peaks at +42.54 index_level in Q1, from +42.54 in Q1 to +20.07 in Q20. Tobin's Q peaks at -2.55 % vs baseline in Q5, from -0.22 in Q1 to +0.41 in Q20. House Prices peaks at -1.26 % vs baseline in Q12, from -0.01 in Q1 to -0.75 in Q20. Bank Equity peaks at -0.40 % vs baseline in Q13, from +0.00 in Q1 to -0.32 in Q20. Bank Credit peaks at -0.35 % vs baseline in Q13, from +0.00 in Q1 to -0.28 in Q20. Credit Spread peaks at +0.01 pp in Q13, from +0.00 in Q1 to +0.01 in Q20.

Nominal FX. NEER peaks at -1.42 % vs baseline in Q1, from -1.42 in Q1 to +0.36 in Q20. vs USD peaks at +3.46 % vs baseline in Q1, from +3.46 in Q1 to +0.85 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.76 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.41 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.46 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.47 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.81 in Q20. Gold Price peaks at +3453.47 USD/oz (level) in Q1, from +3453.47 in Q1 to +2262.69 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.85 % vs baseline in Q5, from -0.72 in Q1 to +0.11 in Q20. Services GDP peaks at -0.85 % vs baseline in Q7, from -0.00 in Q1 to +0.09 in Q20. Capital Stock peaks at -0.14 % vs baseline in Q14, from -0.00 in Q1 to -0.12 in Q20.

Timing. The GDP response has mostly faded by Q15 (Q20 is +0.17%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/IN_Y.png)

![CPI Inflation](charts/IN_pi_cpi.png)

![Equity Index](charts/IN_equity.png)

![Gold Price](charts/IN_P_gold.png)

![Metals Price](charts/IN_P_metals.png)

![Food Price](charts/IN_P_food.png)

![Copper Price](charts/IN_P_copper.png)

![Wheat Price](charts/IN_P_wheat.png)

![Energy Price](charts/IN_P_energy.png)

![VIX](charts/IN_vix.png)

![Bond Price (7y)](charts/IN_Q_B.png)

![Gas Price](charts/IN_P_gas.png)

[Q1–Q20 JSON for India](numbers/IN.json)

## TH — Thailand

The main impact of a 250bp rise in the risk premium on Thailand would be a large drop in GDP of 1.50% by Q7. Equities peak at -25.05% in Q1.

Demand and trade. Consumption peaks at -0.98 % vs baseline in Q8, from -0.02 in Q1 to -0.22 in Q20. Investment peaks at -3.80 % vs baseline in Q6, from -0.22 in Q1 to -0.25 in Q20. Net Exports peaks at +0.32 % vs baseline in Q1, from +0.32 in Q1 to +0.05 in Q20. Gov Spending peaks at +0.25 % vs baseline in Q7, from +0.00 in Q1 to +0.04 in Q20. Gov Debt peaks at -1.74 % vs baseline in Q16, from +0.00 in Q1 to -1.61 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +1.29 % vs baseline in Q1, from +1.29 in Q1 to +0.18 in Q20.

Labour. Employment peaks at -1.33 % vs baseline in Q11, from +0.00 in Q1 to -0.69 in Q20. Unemployment peaks at +0.13 pp in Q9, from +0.00 in Q1 to +0.04 in Q20. Real Wages peaks at -1.98 % vs baseline in Q20, from +0.00 in Q1 to -1.98 in Q20.

Prices. The three-year CPI impulse is -0.47 percentage points. CPI Inflation peaks at +0.35 pp in Q1, from +0.35 in Q1 to +0.01 in Q20. Domestic Infl. peaks at +0.25 pp in Q1, from +0.25 in Q1 to +0.01 in Q20. Marginal Cost peaks at -0.90 % vs baseline in Q7, from -0.00 in Q1 to -0.15 in Q20.

Financial conditions. Policy Rate peaks at -0.62 pp (annualized) in Q11, from +0.14 in Q1 to -0.27 in Q20. Real Rate peaks at -0.16 pp (annualized) in Q11, from +0.03 in Q1 to -0.07 in Q20. Govt 3M Yield peaks at -0.62 pp (annualized) in Q11, from +0.14 in Q1 to -0.27 in Q20. Govt 2Y Yield peaks at -0.57 pp (annualized) in Q8, from -0.11 in Q1 to -0.16 in Q20. Govt 5Y Yield peaks at -0.40 pp (annualized) in Q5, from -0.34 in Q1 to -0.11 in Q20. Govt 10Y Yield peaks at -0.24 pp (annualized) in Q5, from -0.22 in Q1 to -0.09 in Q20. Govt 30Y Yield peaks at -0.10 pp (annualized) in Q5, from -0.10 in Q1 to -0.04 in Q20. Bond Price (7y) peaks at +2.59 % vs baseline in Q11, from -0.58 in Q1 to +1.13 in Q20. Bond Price 3M peaks at +0.16 % vs baseline in Q11, from -0.03 in Q1 to +0.07 in Q20. Bond Price 2Y peaks at +1.09 % vs baseline in Q8, from +0.22 in Q1 to +0.31 in Q20. Bond Price 5Y peaks at +1.80 % vs baseline in Q5, from +1.54 in Q1 to +0.48 in Q20. Bond Price 10Y peaks at +1.95 % vs baseline in Q5, from +1.81 in Q1 to +0.71 in Q20. Bond Price 30Y peaks at +1.77 % vs baseline in Q5, from +1.71 in Q1 to +0.74 in Q20. Equity Index peaks at -25.05 % vs baseline in Q1, from -25.05 in Q1 to -5.63 in Q20. VIX peaks at +42.54 index_level in Q1, from +42.54 in Q1 to +20.07 in Q20. Tobin's Q peaks at -2.66 % vs baseline in Q6, from -0.16 in Q1 to -0.17 in Q20. House Prices peaks at -1.57 % vs baseline in Q14, from -0.00 in Q1 to -1.34 in Q20. Bank Equity peaks at -0.40 % vs baseline in Q13, from +0.00 in Q1 to -0.32 in Q20. Bank Credit peaks at -0.33 % vs baseline in Q13, from +0.00 in Q1 to -0.26 in Q20. Credit Spread peaks at +0.01 pp in Q13, from +0.00 in Q1 to +0.01 in Q20.

Nominal FX. NEER peaks at -0.79 % vs baseline in Q1, from -0.79 in Q1 to -0.10 in Q20. vs USD peaks at +2.34 % vs baseline in Q1, from +2.34 in Q1 to +1.23 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.76 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.41 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.46 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.47 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.81 in Q20. Gold Price peaks at +3453.47 USD/oz (level) in Q1, from +3453.47 in Q1 to +2262.69 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.61 % vs baseline in Q6, from -0.39 in Q1 to -0.12 in Q20. Services GDP peaks at -0.83 % vs baseline in Q7, from -0.00 in Q1 to -0.14 in Q20. Capital Stock peaks at -0.18 % vs baseline in Q20, from -0.00 in Q1 to -0.18 in Q20.

Timing. The GDP response has mostly faded by Q18 (Q20 is -0.25%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/TH_Y.png)

![CPI Inflation](charts/TH_pi_cpi.png)

![Equity Index](charts/TH_equity.png)

![Gold Price](charts/TH_P_gold.png)

![Metals Price](charts/TH_P_metals.png)

![Food Price](charts/TH_P_food.png)

![Copper Price](charts/TH_P_copper.png)

![Wheat Price](charts/TH_P_wheat.png)

![Energy Price](charts/TH_P_energy.png)

![VIX](charts/TH_vix.png)

![Gas Price](charts/TH_P_gas.png)

![Investment](charts/TH_I.png)

[Q1–Q20 JSON for Thailand](numbers/TH.json)

## MX — Mexico

The main impact of a 250bp rise in the risk premium on Mexico would be a large drop in GDP of 1.35% by Q7. Equities peak at -25.06% in Q1.

Demand and trade. Consumption peaks at -0.79 % vs baseline in Q8, from -0.12 in Q1 to -0.03 in Q20. Investment peaks at -3.43 % vs baseline in Q5, from -1.27 in Q1 to +0.28 in Q20. Net Exports peaks at +0.71 % vs baseline in Q1, from +0.71 in Q1 to +0.07 in Q20. Gov Spending peaks at +0.19 % vs baseline in Q7, from +0.00 in Q1 to -0.01 in Q20. Gov Debt peaks at -1.44 % vs baseline in Q14, from +0.00 in Q1 to -1.21 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +3.75 % vs baseline in Q1, from +3.75 in Q1 to +0.53 in Q20.

Labour. Employment peaks at -1.06 % vs baseline in Q12, from +0.00 in Q1 to -0.52 in Q20. Unemployment peaks at +0.11 pp in Q9, from +0.00 in Q1 to +0.01 in Q20. Real Wages peaks at -1.63 % vs baseline in Q20, from +0.00 in Q1 to -1.63 in Q20.

Prices. The three-year CPI impulse is -0.16 percentage points. CPI Inflation peaks at +0.93 pp in Q1, from +0.93 in Q1 to -0.01 in Q20. Domestic Infl. peaks at +0.65 pp in Q1, from +0.65 in Q1 to -0.01 in Q20. Marginal Cost peaks at -0.81 % vs baseline in Q7, from -0.00 in Q1 to +0.01 in Q20.

Financial conditions. Policy Rate peaks at +0.89 pp (annualized) in Q2, from +0.83 in Q1 to -0.12 in Q20. Real Rate peaks at +0.22 pp (annualized) in Q2, from +0.21 in Q1 to -0.03 in Q20. Govt 3M Yield peaks at +0.89 pp (annualized) in Q2, from +0.83 in Q1 to -0.12 in Q20. Govt 2Y Yield peaks at -0.57 pp (annualized) in Q8, from +0.18 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at -0.33 pp (annualized) in Q5, from -0.19 in Q1 to -0.02 in Q20. Govt 10Y Yield peaks at -0.17 pp (annualized) in Q6, from -0.10 in Q1 to -0.03 in Q20. Govt 30Y Yield peaks at -0.07 pp (annualized) in Q6, from -0.04 in Q1 to -0.02 in Q20. Bond Price (7y) peaks at -3.72 % vs baseline in Q2, from -3.47 in Q1 to +0.52 in Q20. Bond Price 3M peaks at -0.22 % vs baseline in Q2, from -0.21 in Q1 to +0.03 in Q20. Bond Price 2Y peaks at +1.08 % vs baseline in Q8, from -0.35 in Q1 to +0.05 in Q20. Bond Price 5Y peaks at +1.48 % vs baseline in Q5, from +0.85 in Q1 to +0.08 in Q20. Bond Price 10Y peaks at +1.41 % vs baseline in Q6, from +0.82 in Q1 to +0.24 in Q20. Bond Price 30Y peaks at +1.17 % vs baseline in Q6, from +0.76 in Q1 to +0.34 in Q20. Equity Index peaks at -25.06 % vs baseline in Q1, from -25.06 in Q1 to -4.93 in Q20. VIX peaks at +42.54 index_level in Q1, from +42.54 in Q1 to +20.07 in Q20. Tobin's Q peaks at -2.40 % vs baseline in Q5, from -0.89 in Q1 to +0.19 in Q20. House Prices peaks at -1.28 % vs baseline in Q13, from -0.02 in Q1 to -0.91 in Q20. Bank Equity peaks at -0.32 % vs baseline in Q13, from +0.00 in Q1 to -0.25 in Q20. Bank Credit peaks at -0.31 % vs baseline in Q13, from +0.00 in Q1 to -0.24 in Q20. Credit Spread peaks at +0.02 pp in Q13, from +0.00 in Q1 to +0.01 in Q20.

Nominal FX. NEER peaks at -3.78 % vs baseline in Q1, from -3.78 in Q1 to -0.84 in Q20. vs USD peaks at +4.80 % vs baseline in Q1, from +4.80 in Q1 to +1.59 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.76 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.41 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.46 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.47 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.81 in Q20. Gold Price peaks at +3453.47 USD/oz (level) in Q1, from +3453.47 in Q1 to +2262.69 in Q20.

Sectoral and capital. Manuf. GDP peaks at -1.13 % vs baseline in Q1, from -1.13 in Q1 to -0.15 in Q20. Services GDP peaks at -0.82 % vs baseline in Q7, from -0.00 in Q1 to +0.01 in Q20. Capital Stock peaks at -0.16 % vs baseline in Q16, from -0.01 in Q1 to -0.15 in Q20.

Timing. The GDP response has mostly faded by Q16 (Q20 is +0.02%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/MX_Y.png)

![CPI Inflation](charts/MX_pi_cpi.png)

![Equity Index](charts/MX_equity.png)

![Gold Price](charts/MX_P_gold.png)

![Metals Price](charts/MX_P_metals.png)

![Food Price](charts/MX_P_food.png)

![Copper Price](charts/MX_P_copper.png)

![Wheat Price](charts/MX_P_wheat.png)

![Energy Price](charts/MX_P_energy.png)

![VIX](charts/MX_vix.png)

![vs USD](charts/MX_USD.png)

![Gas Price](charts/MX_P_gas.png)

[Q1–Q20 JSON for Mexico](numbers/MX.json)

## ID — Indonesia

The main impact of a 250bp rise in the risk premium on Indonesia would be a large drop in GDP of 1.34% by Q7. Equities peak at -25.05% in Q1.

Demand and trade. Consumption peaks at -0.80 % vs baseline in Q8, from -0.03 in Q1 to -0.01 in Q20. Investment peaks at -3.36 % vs baseline in Q6, from -0.33 in Q1 to +0.38 in Q20. Net Exports peaks at +0.34 % vs baseline in Q1, from +0.34 in Q1 to -0.00 in Q20. Gov Spending peaks at +0.21 % vs baseline in Q7, from +0.00 in Q1 to -0.01 in Q20. Gov Debt peaks at -1.52 % vs baseline in Q13, from +0.00 in Q1 to -1.10 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +3.12 % vs baseline in Q1, from +3.12 in Q1 to +0.11 in Q20.

Labour. Employment peaks at -0.91 % vs baseline in Q12, from +0.00 in Q1 to -0.52 in Q20. Unemployment peaks at +0.10 pp in Q9, from +0.00 in Q1 to +0.01 in Q20. Real Wages peaks at -1.97 % vs baseline in Q20, from +0.00 in Q1 to -1.97 in Q20.

Prices. The three-year CPI impulse is -0.90 percentage points. CPI Inflation peaks at +0.38 pp in Q1, from +0.38 in Q1 to +0.01 in Q20. Domestic Infl. peaks at +0.26 pp in Q1, from +0.26 in Q1 to +0.01 in Q20. Marginal Cost peaks at -0.80 % vs baseline in Q7, from -0.00 in Q1 to +0.03 in Q20.

Financial conditions. Policy Rate peaks at -0.67 pp (annualized) in Q11, from +0.21 in Q1 to -0.13 in Q20. Real Rate peaks at -0.17 pp (annualized) in Q11, from +0.05 in Q1 to -0.03 in Q20. Govt 3M Yield peaks at -0.67 pp (annualized) in Q11, from +0.21 in Q1 to -0.13 in Q20. Govt 2Y Yield peaks at -0.60 pp (annualized) in Q8, from -0.07 in Q1 to -0.01 in Q20. Govt 5Y Yield peaks at -0.35 pp (annualized) in Q5, from -0.30 in Q1 to +0.01 in Q20. Govt 10Y Yield peaks at -0.17 pp (annualized) in Q5, from -0.15 in Q1 to -0.01 in Q20. Govt 30Y Yield peaks at -0.06 pp (annualized) in Q5, from -0.06 in Q1 to -0.01 in Q20. Bond Price (7y) peaks at +2.79 % vs baseline in Q11, from -0.88 in Q1 to +0.53 in Q20. Bond Price 3M peaks at +0.17 % vs baseline in Q11, from -0.05 in Q1 to +0.03 in Q20. Bond Price 2Y peaks at +1.14 % vs baseline in Q8, from +0.13 in Q1 to +0.01 in Q20. Bond Price 5Y peaks at +1.57 % vs baseline in Q5, from +1.37 in Q1 to -0.04 in Q20. Bond Price 10Y peaks at +1.38 % vs baseline in Q5, from +1.20 in Q1 to +0.09 in Q20. Bond Price 30Y peaks at +1.16 % vs baseline in Q5, from +1.04 in Q1 to +0.15 in Q20. Equity Index peaks at -25.05 % vs baseline in Q1, from -25.05 in Q1 to -4.89 in Q20. VIX peaks at +42.54 index_level in Q1, from +42.54 in Q1 to +20.07 in Q20. Tobin's Q peaks at -2.35 % vs baseline in Q6, from -0.23 in Q1 to +0.27 in Q20. House Prices peaks at -1.16 % vs baseline in Q13, from -0.01 in Q1 to -0.79 in Q20. Bank Equity peaks at -0.31 % vs baseline in Q13, from +0.00 in Q1 to -0.24 in Q20. Bank Credit peaks at -0.31 % vs baseline in Q13, from +0.00 in Q1 to -0.25 in Q20. Credit Spread peaks at +0.01 pp in Q13, from +0.00 in Q1 to +0.01 in Q20.

Nominal FX. NEER peaks at -2.29 % vs baseline in Q1, from -2.29 in Q1 to +0.14 in Q20. vs USD peaks at +4.17 % vs baseline in Q1, from +4.17 in Q1 to +1.16 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.76 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.41 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.46 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.47 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.81 in Q20. Gold Price peaks at +3453.47 USD/oz (level) in Q1, from +3453.47 in Q1 to +2262.69 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.94 % vs baseline in Q1, from -0.94 in Q1 to -0.01 in Q20. Services GDP peaks at -0.66 % vs baseline in Q7, from -0.00 in Q1 to +0.03 in Q20. Capital Stock peaks at -0.14 % vs baseline in Q15, from -0.00 in Q1 to -0.13 in Q20.

Timing. The GDP response has mostly faded by Q16 (Q20 is +0.05%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/ID_Y.png)

![CPI Inflation](charts/ID_pi_cpi.png)

![Equity Index](charts/ID_equity.png)

![Gold Price](charts/ID_P_gold.png)

![Metals Price](charts/ID_P_metals.png)

![Food Price](charts/ID_P_food.png)

![Copper Price](charts/ID_P_copper.png)

![Wheat Price](charts/ID_P_wheat.png)

![Energy Price](charts/ID_P_energy.png)

![VIX](charts/ID_vix.png)

![vs USD](charts/ID_USD.png)

![Gas Price](charts/ID_P_gas.png)

[Q1–Q20 JSON for Indonesia](numbers/ID.json)

## BR — Brazil

The main impact of a 250bp rise in the risk premium on Brazil would be a large drop in GDP of 1.28% by Q7. Equities peak at -25.08% in Q1.

Demand and trade. Consumption peaks at -0.69 % vs baseline in Q8, from -0.05 in Q1 to +0.19 in Q20. Investment peaks at -2.98 % vs baseline in Q5, from -0.53 in Q1 to +1.07 in Q20. Net Exports peaks at +0.26 % vs baseline in Q1, from +0.26 in Q1 to -0.08 in Q20. Gov Spending peaks at +0.21 % vs baseline in Q7, from +0.00 in Q1 to -0.09 in Q20. Gov Debt peaks at -0.22 % vs baseline in Q14, from +0.00 in Q1 to -0.16 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +3.69 % vs baseline in Q1, from +3.69 in Q1 to -0.21 in Q20.

Labour. Employment peaks at -0.94 % vs baseline in Q11, from +0.00 in Q1 to -0.18 in Q20. Unemployment peaks at +0.23 pp in Q9, from +0.00 in Q1 to -0.05 in Q20. Real Wages peaks at -1.59 % vs baseline in Q20, from +0.00 in Q1 to -1.59 in Q20.

Prices. The three-year CPI impulse is -0.65 percentage points. CPI Inflation peaks at +0.28 pp in Q1, from +0.28 in Q1 to +0.01 in Q20. Domestic Infl. peaks at +0.20 pp in Q1, from +0.20 in Q1 to +0.01 in Q20. Marginal Cost peaks at -0.77 % vs baseline in Q7, from -0.00 in Q1 to +0.23 in Q20.

Financial conditions. Policy Rate peaks at -0.86 pp (annualized) in Q10, from +0.34 in Q1 to +0.03 in Q20. Real Rate peaks at -0.22 pp (annualized) in Q10, from +0.09 in Q1 to +0.01 in Q20. Govt 3M Yield peaks at -0.86 pp (annualized) in Q10, from +0.34 in Q1 to +0.03 in Q20. Govt 2Y Yield peaks at -0.75 pp (annualized) in Q7, from -0.12 in Q1 to +0.15 in Q20. Govt 5Y Yield peaks at -0.37 pp (annualized) in Q4, from -0.33 in Q1 to +0.12 in Q20. Govt 10Y Yield peaks at -0.14 pp (annualized) in Q5, from -0.11 in Q1 to +0.05 in Q20. Govt 30Y Yield peaks at -0.05 pp (annualized) in Q5, from -0.04 in Q1 to +0.01 in Q20. Bond Price (7y) peaks at +3.60 % vs baseline in Q10, from -1.42 in Q1 to -0.14 in Q20. Bond Price 3M peaks at +0.22 % vs baseline in Q10, from -0.09 in Q1 to -0.01 in Q20. Bond Price 2Y peaks at +1.42 % vs baseline in Q7, from +0.24 in Q1 to -0.28 in Q20. Bond Price 5Y peaks at +1.65 % vs baseline in Q4, from +1.50 in Q1 to -0.52 in Q20. Bond Price 10Y peaks at +1.13 % vs baseline in Q5, from +0.90 in Q1 to -0.43 in Q20. Bond Price 30Y peaks at +0.93 % vs baseline in Q5, from +0.76 in Q1 to -0.24 in Q20. Equity Index peaks at -25.08 % vs baseline in Q1, from -25.08 in Q1 to -4.15 in Q20. VIX peaks at +42.54 index_level in Q1, from +42.54 in Q1 to +20.07 in Q20. Tobin's Q peaks at -2.08 % vs baseline in Q5, from -0.37 in Q1 to +0.75 in Q20. House Prices peaks at -0.96 % vs baseline in Q12, from -0.01 in Q1 to -0.38 in Q20. Bank Equity peaks at -0.32 % vs baseline in Q13, from +0.00 in Q1 to -0.25 in Q20. Bank Credit peaks at -0.27 % vs baseline in Q13, from +0.00 in Q1 to -0.21 in Q20. Credit Spread peaks at +0.01 pp in Q13, from +0.00 in Q1 to +0.01 in Q20.

Nominal FX. NEER peaks at -2.74 % vs baseline in Q1, from -2.74 in Q1 to +0.29 in Q20. vs USD peaks at +4.74 % vs baseline in Q1, from +4.74 in Q1 to +0.85 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.76 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.41 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.46 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.47 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.81 in Q20. Gold Price peaks at +3453.47 USD/oz (level) in Q1, from +3453.47 in Q1 to +2262.69 in Q20.

Sectoral and capital. Manuf. GDP peaks at -1.11 % vs baseline in Q1, from -1.11 in Q1 to +0.15 in Q20. Services GDP peaks at -0.85 % vs baseline in Q7, from -0.00 in Q1 to +0.26 in Q20. Capital Stock peaks at -0.11 % vs baseline in Q12, from -0.00 in Q1 to -0.07 in Q20.

Timing. The GDP response has mostly faded by Q14 (Q20 is +0.39%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/BR_Y.png)

![CPI Inflation](charts/BR_pi_cpi.png)

![Equity Index](charts/BR_equity.png)

![Gold Price](charts/BR_P_gold.png)

![Metals Price](charts/BR_P_metals.png)

![Food Price](charts/BR_P_food.png)

![Copper Price](charts/BR_P_copper.png)

![Wheat Price](charts/BR_P_wheat.png)

![Energy Price](charts/BR_P_energy.png)

![VIX](charts/BR_vix.png)

![vs USD](charts/BR_USD.png)

![Gas Price](charts/BR_P_gas.png)

[Q1–Q20 JSON for Brazil](numbers/BR.json)

## CO — Colombia

The main impact of a 250bp rise in the risk premium on Colombia would be a large drop in GDP of 1.28% by Q7. Equities peak at -25.06% in Q1.

Demand and trade. Consumption peaks at -0.75 % vs baseline in Q8, from -0.06 in Q1 to +0.02 in Q20. Investment peaks at -3.19 % vs baseline in Q5, from -0.62 in Q1 to +0.41 in Q20. Net Exports peaks at +0.45 % vs baseline in Q1, from +0.45 in Q1 to +0.00 in Q20. Gov Spending peaks at +0.18 % vs baseline in Q7, from +0.00 in Q1 to -0.02 in Q20. Gov Debt peaks at -1.26 % vs baseline in Q14, from +0.00 in Q1 to -1.06 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +4.06 % vs baseline in Q1, from +4.06 in Q1 to +0.27 in Q20.

Labour. Employment peaks at -1.03 % vs baseline in Q11, from +0.00 in Q1 to -0.40 in Q20. Unemployment peaks at +0.10 pp in Q9, from +0.00 in Q1 to +0.00 in Q20. Real Wages peaks at -1.73 % vs baseline in Q20, from +0.00 in Q1 to -1.73 in Q20.

Prices. The three-year CPI impulse is -0.57 percentage points. CPI Inflation peaks at +0.54 pp in Q1, from +0.54 in Q1 to +0.01 in Q20. Domestic Infl. peaks at +0.37 pp in Q1, from +0.37 in Q1 to +0.00 in Q20. Marginal Cost peaks at -0.77 % vs baseline in Q7, from -0.00 in Q1 to +0.06 in Q20.

Financial conditions. Policy Rate peaks at -0.65 pp (annualized) in Q10, from +0.40 in Q1 to -0.07 in Q20. Real Rate peaks at -0.16 pp (annualized) in Q10, from +0.10 in Q1 to -0.02 in Q20. Govt 3M Yield peaks at -0.65 pp (annualized) in Q10, from +0.40 in Q1 to -0.07 in Q20. Govt 2Y Yield peaks at -0.57 pp (annualized) in Q7, from +0.01 in Q1 to +0.03 in Q20. Govt 5Y Yield peaks at -0.31 pp (annualized) in Q5, from -0.24 in Q1 to +0.02 in Q20. Govt 10Y Yield peaks at -0.15 pp (annualized) in Q5, from -0.11 in Q1 to -0.00 in Q20. Govt 30Y Yield peaks at -0.06 pp (annualized) in Q5, from -0.04 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at +2.33 % vs baseline in Q10, from -1.43 in Q1 to +0.24 in Q20. Bond Price 3M peaks at +0.16 % vs baseline in Q10, from -0.10 in Q1 to +0.02 in Q20. Bond Price 2Y peaks at +1.08 % vs baseline in Q7, from -0.03 in Q1 to -0.05 in Q20. Bond Price 5Y peaks at +1.39 % vs baseline in Q5, from +1.08 in Q1 to -0.09 in Q20. Bond Price 10Y peaks at +1.21 % vs baseline in Q5, from +0.89 in Q1 to +0.02 in Q20. Bond Price 30Y peaks at +1.00 % vs baseline in Q5, from +0.78 in Q1 to +0.06 in Q20. Equity Index peaks at -25.06 % vs baseline in Q1, from -25.06 in Q1 to -4.79 in Q20. VIX peaks at +42.54 index_level in Q1, from +42.54 in Q1 to +20.07 in Q20. Tobin's Q peaks at -2.23 % vs baseline in Q5, from -0.43 in Q1 to +0.29 in Q20. House Prices peaks at -1.10 % vs baseline in Q13, from -0.01 in Q1 to -0.71 in Q20. Bank Equity peaks at -0.28 % vs baseline in Q13, from +0.00 in Q1 to -0.22 in Q20. Bank Credit peaks at -0.25 % vs baseline in Q13, from +0.00 in Q1 to -0.20 in Q20. Credit Spread peaks at +0.01 pp in Q13, from +0.00 in Q1 to +0.01 in Q20.

Nominal FX. NEER peaks at -3.18 % vs baseline in Q1, from -3.18 in Q1 to -0.29 in Q20. vs USD peaks at +5.10 % vs baseline in Q1, from +5.10 in Q1 to +1.33 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.76 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.41 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.46 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.47 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.81 in Q20. Gold Price peaks at +3453.47 USD/oz (level) in Q1, from +3453.47 in Q1 to +2262.69 in Q20.

Sectoral and capital. Manuf. GDP peaks at -1.22 % vs baseline in Q1, from -1.22 in Q1 to -0.06 in Q20. Services GDP peaks at -0.77 % vs baseline in Q7, from -0.00 in Q1 to +0.06 in Q20. Capital Stock peaks at -0.13 % vs baseline in Q15, from -0.00 in Q1 to -0.12 in Q20.

Timing. The GDP response has mostly faded by Q15 (Q20 is +0.10%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/CO_Y.png)

![CPI Inflation](charts/CO_pi_cpi.png)

![Equity Index](charts/CO_equity.png)

![Gold Price](charts/CO_P_gold.png)

![Metals Price](charts/CO_P_metals.png)

![Food Price](charts/CO_P_food.png)

![Copper Price](charts/CO_P_copper.png)

![Wheat Price](charts/CO_P_wheat.png)

![Energy Price](charts/CO_P_energy.png)

![VIX](charts/CO_vix.png)

![vs USD](charts/CO_USD.png)

![Real Exchange Rate](charts/CO_RER.png)

[Q1–Q20 JSON for Colombia](numbers/CO.json)

## NO — Norway

The main impact of a 250bp rise in the risk premium on Norway would be a large drop in GDP of 1.23% by Q7. Equities peak at -25.05% in Q1.

Demand and trade. Consumption peaks at -0.71 % vs baseline in Q8, from -0.00 in Q1 to -0.08 in Q20. Investment peaks at -2.92 % vs baseline in Q6, from -0.02 in Q1 to +0.19 in Q20. Net Exports peaks at -0.43 % vs baseline in Q8, from +0.01 in Q1 to +0.03 in Q20. Gov Spending peaks at -0.04 % vs baseline in Q11, from +0.00 in Q1 to -0.00 in Q20. Gov Debt peaks at +0.27 % vs baseline in Q15, from +0.00 in Q1 to +0.24 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +1.89 % vs baseline in Q9, from +0.08 in Q1 to +0.56 in Q20.

Labour. Employment peaks at -0.95 % vs baseline in Q11, from +0.00 in Q1 to -0.48 in Q20. Unemployment peaks at +0.70 pp in Q11, from +0.00 in Q1 to +0.28 in Q20. Real Wages peaks at -1.02 % vs baseline in Q20, from +0.00 in Q1 to -1.02 in Q20.

Prices. The three-year CPI impulse is -0.30 percentage points. CPI Inflation peaks at -0.05 pp in Q7, from +0.01 in Q1 to +0.01 in Q20. Domestic Infl. peaks at -0.04 pp in Q7, from +0.01 in Q1 to +0.00 in Q20. Marginal Cost peaks at -0.73 % vs baseline in Q7, from -0.00 in Q1 to -0.05 in Q20.

Financial conditions. Policy Rate peaks at -0.59 pp (annualized) in Q11, from +0.01 in Q1 to -0.25 in Q20. Real Rate peaks at -0.15 pp (annualized) in Q11, from +0.00 in Q1 to -0.06 in Q20. Govt 3M Yield peaks at -0.59 pp (annualized) in Q11, from +0.01 in Q1 to -0.25 in Q20. Govt 2Y Yield peaks at -0.55 pp (annualized) in Q8, from -0.20 in Q1 to -0.14 in Q20. Govt 5Y Yield peaks at -0.38 pp (annualized) in Q4, from -0.36 in Q1 to -0.08 in Q20. Govt 10Y Yield peaks at -0.22 pp (annualized) in Q4, from -0.22 in Q1 to -0.06 in Q20. Govt 30Y Yield peaks at -0.09 pp (annualized) in Q3, from -0.09 in Q1 to -0.03 in Q20. Bond Price (7y) peaks at +3.68 % vs baseline in Q11, from -0.09 in Q1 to +1.54 in Q20. Bond Price 3M peaks at +0.15 % vs baseline in Q11, from -0.00 in Q1 to +0.06 in Q20. Bond Price 2Y peaks at +1.04 % vs baseline in Q8, from +0.38 in Q1 to +0.27 in Q20. Bond Price 5Y peaks at +1.72 % vs baseline in Q4, from +1.61 in Q1 to +0.37 in Q20. Bond Price 10Y peaks at +1.78 % vs baseline in Q4, from +1.76 in Q1 to +0.50 in Q20. Bond Price 30Y peaks at +1.54 % vs baseline in Q3, from +1.54 in Q1 to +0.51 in Q20. Equity Index peaks at -25.05 % vs baseline in Q1, from -25.05 in Q1 to -5.18 in Q20. VIX peaks at +42.54 index_level in Q1, from +42.54 in Q1 to +20.07 in Q20. Tobin's Q peaks at -2.04 % vs baseline in Q6, from -0.01 in Q1 to +0.13 in Q20. House Prices peaks at -0.91 % vs baseline in Q15, from -0.00 in Q1 to -0.78 in Q20. Bank Equity peaks at -0.46 % vs baseline in Q14, from +0.00 in Q1 to -0.36 in Q20. Bank Credit peaks at -0.36 % vs baseline in Q14, from +0.00 in Q1 to -0.28 in Q20. Credit Spread peaks at +0.00 pp in Q14, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -1.61 % vs baseline in Q10, from +0.60 in Q1 to -0.69 in Q20. vs USD peaks at +2.28 % vs baseline in Q9, from +1.13 in Q1 to +1.61 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.76 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.41 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.46 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.47 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.81 in Q20. Gold Price peaks at +3453.47 USD/oz (level) in Q1, from +3453.47 in Q1 to +2262.69 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.73 % vs baseline in Q8, from -0.03 in Q1 to -0.18 in Q20. Services GDP peaks at -0.70 % vs baseline in Q7, from -0.00 in Q1 to -0.05 in Q20. Capital Stock peaks at -0.13 % vs baseline in Q17, from -0.00 in Q1 to -0.12 in Q20.

Timing. The GDP response has mostly faded by Q17 (Q20 is -0.08%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/NO_Y.png)

![CPI Inflation](charts/NO_pi_cpi.png)

![Equity Index](charts/NO_equity.png)

![Gold Price](charts/NO_P_gold.png)

![Metals Price](charts/NO_P_metals.png)

![Food Price](charts/NO_P_food.png)

![Copper Price](charts/NO_P_copper.png)

![Wheat Price](charts/NO_P_wheat.png)

![Energy Price](charts/NO_P_energy.png)

![VIX](charts/NO_vix.png)

![Gas Price](charts/NO_P_gas.png)

![Bond Price (7y)](charts/NO_Q_B.png)

[Q1–Q20 JSON for Norway](numbers/NO.json)

## KR — South Korea

The main impact of a 250bp rise in the risk premium on South Korea would be a large drop in GDP of 1.22% by Q7. Equities peak at -25.06% in Q1.

Demand and trade. Consumption peaks at -0.75 % vs baseline in Q7, from -0.02 in Q1 to -0.03 in Q20. Investment peaks at -2.91 % vs baseline in Q6, from -0.18 in Q1 to +0.30 in Q20. Net Exports peaks at +0.55 % vs baseline in Q7, from +0.18 in Q1 to -0.04 in Q20. Gov Spending peaks at +0.22 % vs baseline in Q7, from +0.00 in Q1 to -0.00 in Q20. Gov Debt peaks at -0.55 % vs baseline in Q14, from +0.00 in Q1 to -0.47 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.96 % vs baseline in Q1, from +0.96 in Q1 to -0.45 in Q20.

Labour. Employment peaks at -0.94 % vs baseline in Q11, from +0.00 in Q1 to -0.36 in Q20. Unemployment peaks at +0.40 pp in Q10, from +0.00 in Q1 to +0.09 in Q20. Real Wages peaks at -1.50 % vs baseline in Q20, from +0.00 in Q1 to -1.50 in Q20.

Prices. The three-year CPI impulse is -0.52 percentage points. CPI Inflation peaks at +0.18 pp in Q1, from +0.18 in Q1 to +0.00 in Q20. Domestic Infl. peaks at +0.13 pp in Q1, from +0.13 in Q1 to +0.00 in Q20. Marginal Cost peaks at -0.73 % vs baseline in Q7, from -0.00 in Q1 to +0.01 in Q20.

Financial conditions. Policy Rate peaks at -0.63 pp (annualized) in Q10, from +0.11 in Q1 to -0.15 in Q20. Real Rate peaks at -0.16 pp (annualized) in Q10, from +0.03 in Q1 to -0.04 in Q20. Govt 3M Yield peaks at -0.63 pp (annualized) in Q10, from +0.11 in Q1 to -0.15 in Q20. Govt 2Y Yield peaks at -0.57 pp (annualized) in Q7, from -0.16 in Q1 to -0.04 in Q20. Govt 5Y Yield peaks at -0.36 pp (annualized) in Q4, from -0.33 in Q1 to -0.00 in Q20. Govt 10Y Yield peaks at -0.17 pp (annualized) in Q4, from -0.16 in Q1 to -0.00 in Q20. Govt 30Y Yield peaks at -0.06 pp (annualized) in Q4, from -0.06 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at +3.13 % vs baseline in Q10, from -0.55 in Q1 to +0.77 in Q20. Bond Price 3M peaks at +0.16 % vs baseline in Q10, from -0.03 in Q1 to +0.04 in Q20. Bond Price 2Y peaks at +1.08 % vs baseline in Q7, from +0.31 in Q1 to +0.08 in Q20. Bond Price 5Y peaks at +1.60 % vs baseline in Q4, from +1.48 in Q1 to +0.01 in Q20. Bond Price 10Y peaks at +1.40 % vs baseline in Q4, from +1.33 in Q1 to +0.04 in Q20. Bond Price 30Y peaks at +1.08 % vs baseline in Q4, from +1.03 in Q1 to +0.06 in Q20. Equity Index peaks at -25.06 % vs baseline in Q1, from -25.06 in Q1 to -4.93 in Q20. VIX peaks at +42.54 index_level in Q1, from +42.54 in Q1 to +20.07 in Q20. Tobin's Q peaks at -2.04 % vs baseline in Q6, from -0.12 in Q1 to +0.21 in Q20. House Prices peaks at -0.88 % vs baseline in Q14, from -0.00 in Q1 to -0.70 in Q20. Bank Equity peaks at -0.40 % vs baseline in Q13, from +0.00 in Q1 to -0.32 in Q20. Bank Credit peaks at -0.32 % vs baseline in Q13, from +0.00 in Q1 to -0.25 in Q20. Credit Spread peaks at +0.00 pp in Q13, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.69 % vs baseline in Q12, from -0.47 in Q1 to +0.55 in Q20. vs USD peaks at +2.01 % vs baseline in Q1, from +2.01 in Q1 to +0.60 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.76 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.41 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.46 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.47 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.81 in Q20. Gold Price peaks at +3453.47 USD/oz (level) in Q1, from +3453.47 in Q1 to +2262.69 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.35 % vs baseline in Q4, from -0.29 in Q1 to +0.15 in Q20. Services GDP peaks at -0.74 % vs baseline in Q7, from -0.00 in Q1 to +0.01 in Q20. Capital Stock peaks at -0.12 % vs baseline in Q15, from -0.00 in Q1 to -0.11 in Q20.

Timing. The GDP response has mostly faded by Q16 (Q20 is +0.01%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/KR_Y.png)

![CPI Inflation](charts/KR_pi_cpi.png)

![Equity Index](charts/KR_equity.png)

![Gold Price](charts/KR_P_gold.png)

![Metals Price](charts/KR_P_metals.png)

![Food Price](charts/KR_P_food.png)

![Copper Price](charts/KR_P_copper.png)

![Wheat Price](charts/KR_P_wheat.png)

![Energy Price](charts/KR_P_energy.png)

![VIX](charts/KR_vix.png)

![Gas Price](charts/KR_P_gas.png)

![Bond Price (7y)](charts/KR_Q_B.png)

[Q1–Q20 JSON for South Korea](numbers/KR.json)

## CL — Chile

The main impact of a 250bp rise in the risk premium on Chile would be a large drop in GDP of 1.18% by Q7. Equities peak at -25.07% in Q1.

Demand and trade. Consumption peaks at -0.72 % vs baseline in Q8, from -0.06 in Q1 to -0.00 in Q20. Investment peaks at -2.98 % vs baseline in Q6, from -0.60 in Q1 to +0.34 in Q20. Net Exports peaks at +0.41 % vs baseline in Q1, from +0.41 in Q1 to -0.07 in Q20. Gov Spending peaks at +0.10 % vs baseline in Q6, from +0.00 in Q1 to -0.03 in Q20. Gov Debt peaks at -0.82 % vs baseline in Q13, from +0.00 in Q1 to -0.58 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +2.75 % vs baseline in Q1, from +2.75 in Q1 to +0.04 in Q20.

Labour. Employment peaks at -1.02 % vs baseline in Q10, from +0.00 in Q1 to -0.31 in Q20. Unemployment peaks at +0.35 pp in Q10, from +0.00 in Q1 to +0.05 in Q20. Real Wages peaks at -1.56 % vs baseline in Q20, from +0.00 in Q1 to -1.56 in Q20.

Prices. The three-year CPI impulse is -0.57 percentage points. CPI Inflation peaks at +0.54 pp in Q1, from +0.54 in Q1 to +0.01 in Q20. Domestic Infl. peaks at +0.38 pp in Q1, from +0.38 in Q1 to +0.01 in Q20. Marginal Cost peaks at -0.71 % vs baseline in Q7, from -0.00 in Q1 to +0.04 in Q20.

Financial conditions. Policy Rate peaks at -0.59 pp (annualized) in Q10, from +0.39 in Q1 to -0.09 in Q20. Real Rate peaks at -0.15 pp (annualized) in Q10, from +0.10 in Q1 to -0.02 in Q20. Govt 3M Yield peaks at -0.59 pp (annualized) in Q10, from +0.39 in Q1 to -0.09 in Q20. Govt 2Y Yield peaks at -0.52 pp (annualized) in Q8, from +0.02 in Q1 to +0.01 in Q20. Govt 5Y Yield peaks at -0.29 pp (annualized) in Q5, from -0.23 in Q1 to +0.02 in Q20. Govt 10Y Yield peaks at -0.14 pp (annualized) in Q5, from -0.10 in Q1 to -0.00 in Q20. Govt 30Y Yield peaks at -0.05 pp (annualized) in Q5, from -0.04 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at +2.45 % vs baseline in Q10, from -1.61 in Q1 to +0.37 in Q20. Bond Price 3M peaks at +0.15 % vs baseline in Q10, from -0.10 in Q1 to +0.02 in Q20. Bond Price 2Y peaks at +0.99 % vs baseline in Q8, from -0.04 in Q1 to -0.02 in Q20. Bond Price 5Y peaks at +1.31 % vs baseline in Q5, from +1.02 in Q1 to -0.09 in Q20. Bond Price 10Y peaks at +1.12 % vs baseline in Q5, from +0.83 in Q1 to +0.00 in Q20. Bond Price 30Y peaks at +0.88 % vs baseline in Q5, from +0.68 in Q1 to +0.01 in Q20. Equity Index peaks at -25.07 % vs baseline in Q1, from -25.07 in Q1 to -4.82 in Q20. VIX peaks at +42.54 index_level in Q1, from +42.54 in Q1 to +20.07 in Q20. Tobin's Q peaks at -2.08 % vs baseline in Q6, from -0.42 in Q1 to +0.24 in Q20. House Prices peaks at -1.06 % vs baseline in Q13, from -0.01 in Q1 to -0.71 in Q20. Bank Equity peaks at -0.30 % vs baseline in Q13, from +0.00 in Q1 to -0.23 in Q20. Bank Credit peaks at -0.24 % vs baseline in Q13, from +0.00 in Q1 to -0.19 in Q20. Credit Spread peaks at +0.01 pp in Q13, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -1.43 % vs baseline in Q1, from -1.43 in Q1 to +0.07 in Q20. vs USD peaks at +3.80 % vs baseline in Q1, from +3.80 in Q1 to +1.09 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.76 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.41 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.46 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.47 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.81 in Q20. Gold Price peaks at +3453.47 USD/oz (level) in Q1, from +3453.47 in Q1 to +2262.69 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.83 % vs baseline in Q1, from -0.83 in Q1 to +0.00 in Q20. Services GDP peaks at -0.72 % vs baseline in Q7, from -0.00 in Q1 to +0.04 in Q20. Capital Stock peaks at -0.12 % vs baseline in Q15, from -0.00 in Q1 to -0.12 in Q20.

Timing. The GDP response has mostly faded by Q16 (Q20 is +0.06%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/CL_Y.png)

![CPI Inflation](charts/CL_pi_cpi.png)

![Equity Index](charts/CL_equity.png)

![Gold Price](charts/CL_P_gold.png)

![Metals Price](charts/CL_P_metals.png)

![Food Price](charts/CL_P_food.png)

![Copper Price](charts/CL_P_copper.png)

![Wheat Price](charts/CL_P_wheat.png)

![Energy Price](charts/CL_P_energy.png)

![VIX](charts/CL_vix.png)

![Gas Price](charts/CL_P_gas.png)

![vs USD](charts/CL_USD.png)

[Q1–Q20 JSON for Chile](numbers/CL.json)

## NL — Netherlands

The main impact of a 250bp rise in the risk premium on Netherlands would be a large drop in GDP of 1.18% by Q7. Equities peak at -25.05% in Q1.

Demand and trade. Consumption peaks at -0.69 % vs baseline in Q8, from -0.01 in Q1 to -0.12 in Q20. Investment peaks at -3.12 % vs baseline in Q6, from -0.07 in Q1 to -0.31 in Q20. Net Exports peaks at +0.18 % vs baseline in Q4, from +0.17 in Q1 to -0.04 in Q20. Gov Spending peaks at +0.24 % vs baseline in Q7, from +0.00 in Q1 to +0.03 in Q20. Gov Debt peaks at +0.20 % vs baseline in Q15, from +0.00 in Q1 to +0.18 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.60 % vs baseline in Q1, from +0.60 in Q1 to -0.17 in Q20.

Labour. Employment peaks at -0.87 % vs baseline in Q12, from +0.00 in Q1 to -0.52 in Q20. Unemployment peaks at +0.67 pp in Q11, from +0.00 in Q1 to +0.30 in Q20. Real Wages peaks at -1.10 % vs baseline in Q20, from +0.00 in Q1 to -1.10 in Q20.

Prices. The three-year CPI impulse is -0.49 percentage points. CPI Inflation peaks at +0.20 pp in Q1, from +0.20 in Q1 to +0.02 in Q20. Domestic Infl. peaks at +0.14 pp in Q1, from +0.14 in Q1 to +0.01 in Q20. Marginal Cost peaks at -0.70 % vs baseline in Q7, from -0.00 in Q1 to -0.09 in Q20.

Financial conditions. Policy Rate peaks at -0.24 pp (annualized) in Q11, from +0.04 in Q1 to -0.06 in Q20. Real Rate peaks at -0.06 pp (annualized) in Q11, from +0.01 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -0.24 pp (annualized) in Q11, from +0.04 in Q1 to -0.06 in Q20. Govt 2Y Yield peaks at -0.22 pp (annualized) in Q8, from -0.04 in Q1 to -0.01 in Q20. Govt 5Y Yield peaks at -0.13 pp (annualized) in Q4, from -0.12 in Q1 to +0.01 in Q20. Govt 10Y Yield peaks at -0.06 pp (annualized) in Q4, from -0.06 in Q1 to +0.00 in Q20. Govt 30Y Yield peaks at -0.02 pp (annualized) in Q5, from -0.02 in Q1 to +0.00 in Q20. Bond Price (7y) peaks at +1.71 % vs baseline in Q11, from -0.29 in Q1 to +0.41 in Q20. Bond Price 3M peaks at +0.06 % vs baseline in Q11, from -0.01 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +0.42 % vs baseline in Q8, from +0.09 in Q1 to +0.02 in Q20. Bond Price 5Y peaks at +0.60 % vs baseline in Q4, from +0.55 in Q1 to -0.03 in Q20. Bond Price 10Y peaks at +0.49 % vs baseline in Q4, from +0.47 in Q1 to -0.03 in Q20. Bond Price 30Y peaks at +0.35 % vs baseline in Q5, from +0.33 in Q1 to -0.03 in Q20. Equity Index peaks at -25.05 % vs baseline in Q1, from -25.05 in Q1 to -5.45 in Q20. VIX peaks at +42.54 index_level in Q1, from +42.54 in Q1 to +20.07 in Q20. Tobin's Q peaks at -2.18 % vs baseline in Q6, from -0.05 in Q1 to -0.22 in Q20. House Prices peaks at -1.01 % vs baseline in Q15, from -0.00 in Q1 to -0.92 in Q20. Bank Equity peaks at -0.55 % vs baseline in Q13, from +0.00 in Q1 to -0.43 in Q20. Bank Credit peaks at -0.44 % vs baseline in Q13, from +0.00 in Q1 to -0.34 in Q20. Credit Spread peaks at +0.00 pp in Q13, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.11 % vs baseline in Q14, from +0.01 in Q1 to +0.07 in Q20. vs USD peaks at +1.65 % vs baseline in Q1, from +1.65 in Q1 to +0.89 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.76 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.41 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.46 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.47 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.81 in Q20. Gold Price peaks at +3453.47 USD/oz (level) in Q1, from +3453.47 in Q1 to +2262.69 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.27 % vs baseline in Q6, from -0.18 in Q1 to +0.03 in Q20. Services GDP peaks at -0.88 % vs baseline in Q7, from -0.00 in Q1 to -0.12 in Q20. Capital Stock peaks at -0.16 % vs baseline in Q20, from -0.00 in Q1 to -0.16 in Q20.

Timing. The GDP response has mostly faded by Q18 (Q20 is -0.16%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/NL_Y.png)

![CPI Inflation](charts/NL_pi_cpi.png)

![Equity Index](charts/NL_equity.png)

![Gold Price](charts/NL_P_gold.png)

![Metals Price](charts/NL_P_metals.png)

![Food Price](charts/NL_P_food.png)

![Copper Price](charts/NL_P_copper.png)

![Wheat Price](charts/NL_P_wheat.png)

![Energy Price](charts/NL_P_energy.png)

![VIX](charts/NL_vix.png)

![Gas Price](charts/NL_P_gas.png)

![Investment](charts/NL_I.png)

[Q1–Q20 JSON for Netherlands](numbers/NL.json)

## PL — Poland

The main impact of a 250bp rise in the risk premium on Poland would be a large drop in GDP of 1.13% by Q7. Equities peak at -25.06% in Q1.

Demand and trade. Consumption peaks at -0.59 % vs baseline in Q8, from -0.04 in Q1 to -0.05 in Q20. Investment peaks at -2.92 % vs baseline in Q6, from -0.33 in Q1 to +0.03 in Q20. Net Exports peaks at +0.38 % vs baseline in Q6, from +0.29 in Q1 to -0.03 in Q20. Gov Spending peaks at +0.22 % vs baseline in Q7, from +0.00 in Q1 to +0.01 in Q20. Gov Debt peaks at +0.00 % vs baseline in Q1, from +0.00 in Q1 to +0.00 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +1.39 % vs baseline in Q1, from +1.39 in Q1 to -0.24 in Q20.

Labour. Employment peaks at -0.94 % vs baseline in Q11, from +0.00 in Q1 to -0.38 in Q20. Unemployment peaks at +0.38 pp in Q10, from +0.00 in Q1 to +0.11 in Q20. Real Wages peaks at -1.36 % vs baseline in Q20, from +0.00 in Q1 to -1.36 in Q20.

Prices. The three-year CPI impulse is -0.48 percentage points. CPI Inflation peaks at +0.35 pp in Q1, from +0.35 in Q1 to +0.01 in Q20. Domestic Infl. peaks at +0.25 pp in Q1, from +0.25 in Q1 to +0.00 in Q20. Marginal Cost peaks at -0.67 % vs baseline in Q7, from -0.00 in Q1 to -0.02 in Q20.

Financial conditions. Policy Rate peaks at -0.39 pp (annualized) in Q10, from +0.21 in Q1 to -0.07 in Q20. Real Rate peaks at -0.10 pp (annualized) in Q10, from +0.05 in Q1 to -0.02 in Q20. Govt 3M Yield peaks at -0.39 pp (annualized) in Q10, from +0.21 in Q1 to -0.07 in Q20. Govt 2Y Yield peaks at -0.35 pp (annualized) in Q8, from -0.01 in Q1 to -0.00 in Q20. Govt 5Y Yield peaks at -0.20 pp (annualized) in Q5, from -0.16 in Q1 to +0.01 in Q20. Govt 10Y Yield peaks at -0.09 pp (annualized) in Q5, from -0.07 in Q1 to +0.00 in Q20. Govt 30Y Yield peaks at -0.03 pp (annualized) in Q5, from -0.02 in Q1 to +0.00 in Q20. Bond Price (7y) peaks at +1.64 % vs baseline in Q10, from -0.88 in Q1 to +0.28 in Q20. Bond Price 3M peaks at +0.10 % vs baseline in Q10, from -0.05 in Q1 to +0.02 in Q20. Bond Price 2Y peaks at +0.66 % vs baseline in Q8, from +0.02 in Q1 to +0.00 in Q20. Bond Price 5Y peaks at +0.90 % vs baseline in Q5, from +0.73 in Q1 to -0.05 in Q20. Bond Price 10Y peaks at +0.76 % vs baseline in Q5, from +0.61 in Q1 to -0.03 in Q20. Bond Price 30Y peaks at +0.55 % vs baseline in Q5, from +0.45 in Q1 to -0.04 in Q20. Equity Index peaks at -25.06 % vs baseline in Q1, from -25.06 in Q1 to -5.03 in Q20. VIX peaks at +42.54 index_level in Q1, from +42.54 in Q1 to +20.07 in Q20. Tobin's Q peaks at -2.04 % vs baseline in Q6, from -0.23 in Q1 to +0.02 in Q20. House Prices peaks at -0.87 % vs baseline in Q14, from -0.00 in Q1 to -0.73 in Q20. Bank Equity peaks at -0.30 % vs baseline in Q13, from +0.00 in Q1 to -0.24 in Q20. Bank Credit peaks at -0.27 % vs baseline in Q13, from +0.00 in Q1 to -0.21 in Q20. Credit Spread peaks at +0.01 pp in Q13, from +0.00 in Q1 to +0.01 in Q20.

Nominal FX. NEER peaks at -0.63 % vs baseline in Q1, from -0.63 in Q1 to +0.28 in Q20. vs USD peaks at +2.44 % vs baseline in Q1, from +2.44 in Q1 to +0.81 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.76 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.41 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.46 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.47 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.81 in Q20. Gold Price peaks at +3453.47 USD/oz (level) in Q1, from +3453.47 in Q1 to +2262.69 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.42 % vs baseline in Q1, from -0.42 in Q1 to +0.07 in Q20. Services GDP peaks at -0.71 % vs baseline in Q7, from -0.00 in Q1 to -0.02 in Q20. Capital Stock peaks at -0.13 % vs baseline in Q18, from -0.00 in Q1 to -0.13 in Q20.

Timing. The GDP response has mostly faded by Q16 (Q20 is -0.04%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/PL_Y.png)

![CPI Inflation](charts/PL_pi_cpi.png)

![Equity Index](charts/PL_equity.png)

![Gold Price](charts/PL_P_gold.png)

![Metals Price](charts/PL_P_metals.png)

![Food Price](charts/PL_P_food.png)

![Copper Price](charts/PL_P_copper.png)

![Wheat Price](charts/PL_P_wheat.png)

![Energy Price](charts/PL_P_energy.png)

![VIX](charts/PL_vix.png)

![Gas Price](charts/PL_P_gas.png)

![Investment](charts/PL_I.png)

[Q1–Q20 JSON for Poland](numbers/PL.json)

## ZA — South Africa

The main impact of a 250bp rise in the risk premium on South Africa would be a large drop in GDP of 1.13% by Q7. Equities peak at -25.08% in Q1.

Demand and trade. Consumption peaks at -0.64 % vs baseline in Q8, from -0.06 in Q1 to +0.03 in Q20. Investment peaks at -2.85 % vs baseline in Q6, from -0.62 in Q1 to +0.40 in Q20. Net Exports peaks at +0.45 % vs baseline in Q1, from +0.45 in Q1 to -0.07 in Q20. Gov Spending peaks at +0.17 % vs baseline in Q7, from +0.00 in Q1 to -0.02 in Q20. Gov Debt peaks at -0.69 % vs baseline in Q15, from +0.00 in Q1 to -0.60 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +3.21 % vs baseline in Q1, from +3.21 in Q1 to -0.16 in Q20.

Labour. Employment peaks at -0.96 % vs baseline in Q11, from +0.00 in Q1 to -0.30 in Q20. Unemployment peaks at +0.23 pp in Q9, from +0.00 in Q1 to +0.02 in Q20. Real Wages peaks at -1.47 % vs baseline in Q20, from +0.00 in Q1 to -1.47 in Q20.

Prices. The three-year CPI impulse is -0.42 percentage points. CPI Inflation peaks at +0.54 pp in Q1, from +0.54 in Q1 to +0.00 in Q20. Domestic Infl. peaks at +0.38 pp in Q1, from +0.38 in Q1 to +0.00 in Q20. Marginal Cost peaks at -0.67 % vs baseline in Q7, from -0.00 in Q1 to +0.06 in Q20.

Financial conditions. Policy Rate peaks at -0.52 pp (annualized) in Q10, from +0.40 in Q1 to -0.06 in Q20. Real Rate peaks at -0.13 pp (annualized) in Q10, from +0.10 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -0.52 pp (annualized) in Q10, from +0.40 in Q1 to -0.06 in Q20. Govt 2Y Yield peaks at -0.45 pp (annualized) in Q7, from +0.05 in Q1 to +0.02 in Q20. Govt 5Y Yield peaks at -0.25 pp (annualized) in Q5, from -0.18 in Q1 to +0.03 in Q20. Govt 10Y Yield peaks at -0.11 pp (annualized) in Q5, from -0.08 in Q1 to +0.01 in Q20. Govt 30Y Yield peaks at -0.04 pp (annualized) in Q5, from -0.03 in Q1 to +0.00 in Q20. Bond Price (7y) peaks at +2.16 % vs baseline in Q10, from -1.68 in Q1 to +0.25 in Q20. Bond Price 3M peaks at +0.13 % vs baseline in Q10, from -0.10 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +0.86 % vs baseline in Q7, from -0.09 in Q1 to -0.04 in Q20. Bond Price 5Y peaks at +1.11 % vs baseline in Q5, from +0.80 in Q1 to -0.11 in Q20. Bond Price 10Y peaks at +0.91 % vs baseline in Q5, from +0.62 in Q1 to -0.08 in Q20. Bond Price 30Y peaks at +0.67 % vs baseline in Q5, from +0.46 in Q1 to -0.08 in Q20. Equity Index peaks at -25.08 % vs baseline in Q1, from -25.08 in Q1 to -4.56 in Q20. VIX peaks at +42.54 index_level in Q1, from +42.54 in Q1 to +20.07 in Q20. Tobin's Q peaks at -1.99 % vs baseline in Q6, from -0.44 in Q1 to +0.28 in Q20. House Prices peaks at -0.99 % vs baseline in Q12, from -0.01 in Q1 to -0.63 in Q20. Bank Equity peaks at -0.31 % vs baseline in Q13, from +0.00 in Q1 to -0.25 in Q20. Bank Credit peaks at -0.27 % vs baseline in Q13, from +0.00 in Q1 to -0.21 in Q20. Credit Spread peaks at +0.01 pp in Q13, from +0.00 in Q1 to +0.01 in Q20.

Nominal FX. NEER peaks at -2.32 % vs baseline in Q1, from -2.32 in Q1 to +0.35 in Q20. vs USD peaks at +4.26 % vs baseline in Q1, from +4.26 in Q1 to +0.90 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.76 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.41 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.46 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.47 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.81 in Q20. Gold Price peaks at +3453.47 USD/oz (level) in Q1, from +3453.47 in Q1 to +2262.69 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.96 % vs baseline in Q1, from -0.96 in Q1 to +0.07 in Q20. Services GDP peaks at -0.72 % vs baseline in Q7, from -0.00 in Q1 to +0.06 in Q20. Capital Stock peaks at -0.12 % vs baseline in Q15, from -0.00 in Q1 to -0.11 in Q20.

Timing. The GDP response has mostly faded by Q15 (Q20 is +0.10%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/ZA_Y.png)

![CPI Inflation](charts/ZA_pi_cpi.png)

![Equity Index](charts/ZA_equity.png)

![Gold Price](charts/ZA_P_gold.png)

![Metals Price](charts/ZA_P_metals.png)

![Food Price](charts/ZA_P_food.png)

![Copper Price](charts/ZA_P_copper.png)

![Wheat Price](charts/ZA_P_wheat.png)

![Energy Price](charts/ZA_P_energy.png)

![VIX](charts/ZA_vix.png)

![vs USD](charts/ZA_USD.png)

![Gas Price](charts/ZA_P_gas.png)

[Q1–Q20 JSON for South Africa](numbers/ZA.json)

## CA — Canada

The main impact of a 250bp rise in the risk premium on Canada would be a large drop in GDP of 1.11% by Q7. Equities peak at -25.05% in Q1.

Demand and trade. Consumption peaks at -0.71 % vs baseline in Q8, from -0.00 in Q1 to +0.00 in Q20. Investment peaks at -2.50 % vs baseline in Q6, from -0.02 in Q1 to +0.36 in Q20. Net Exports peaks at -0.20 % vs baseline in Q9, from +0.01 in Q1 to -0.05 in Q20. Gov Spending peaks at +0.15 % vs baseline in Q7, from +0.00 in Q1 to -0.02 in Q20. Gov Debt peaks at -0.17 % vs baseline in Q13, from +0.00 in Q1 to -0.13 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +1.55 % vs baseline in Q8, from +0.03 in Q1 to +0.02 in Q20.

Labour. Employment peaks at -1.04 % vs baseline in Q10, from +0.00 in Q1 to -0.20 in Q20. Unemployment peaks at +0.62 pp in Q10, from +0.00 in Q1 to +0.16 in Q20. Real Wages peaks at -1.05 % vs baseline in Q20, from +0.00 in Q1 to -1.05 in Q20.

Prices. The three-year CPI impulse is -0.43 percentage points. CPI Inflation peaks at -0.06 pp in Q7, from +0.01 in Q1 to +0.02 in Q20. Domestic Infl. peaks at -0.04 pp in Q7, from +0.01 in Q1 to +0.01 in Q20. Marginal Cost peaks at -0.66 % vs baseline in Q7, from -0.00 in Q1 to +0.03 in Q20.

Financial conditions. Policy Rate peaks at -0.66 pp (annualized) in Q10, from +0.01 in Q1 to -0.12 in Q20. Real Rate peaks at -0.16 pp (annualized) in Q10, from +0.00 in Q1 to -0.03 in Q20. Govt 3M Yield peaks at -0.66 pp (annualized) in Q10, from +0.01 in Q1 to -0.12 in Q20. Govt 2Y Yield peaks at -0.59 pp (annualized) in Q7, from -0.25 in Q1 to -0.01 in Q20. Govt 5Y Yield peaks at -0.37 pp (annualized) in Q3, from -0.37 in Q1 to +0.02 in Q20. Govt 10Y Yield peaks at -0.17 pp (annualized) in Q2, from -0.17 in Q1 to +0.01 in Q20. Govt 30Y Yield peaks at -0.06 pp (annualized) in Q2, from -0.06 in Q1 to +0.00 in Q20. Bond Price (7y) peaks at +3.92 % vs baseline in Q10, from -0.11 in Q1 to +0.72 in Q20. Bond Price 3M peaks at +0.16 % vs baseline in Q10, from -0.00 in Q1 to +0.03 in Q20. Bond Price 2Y peaks at +1.13 % vs baseline in Q7, from +0.48 in Q1 to +0.01 in Q20. Bond Price 5Y peaks at +1.67 % vs baseline in Q3, from +1.65 in Q1 to -0.11 in Q20. Bond Price 10Y peaks at +1.38 % vs baseline in Q2, from +1.38 in Q1 to -0.06 in Q20. Bond Price 30Y peaks at +1.09 % vs baseline in Q2, from +1.09 in Q1 to +0.00 in Q20. Equity Index peaks at -25.05 % vs baseline in Q1, from -25.05 in Q1 to -4.86 in Q20. VIX peaks at +42.54 index_level in Q1, from +42.54 in Q1 to +20.07 in Q20. Tobin's Q peaks at -1.75 % vs baseline in Q6, from -0.01 in Q1 to +0.25 in Q20. House Prices peaks at -0.76 % vs baseline in Q13, from -0.00 in Q1 to -0.57 in Q20. Bank Equity peaks at -0.38 % vs baseline in Q13, from +0.00 in Q1 to -0.29 in Q20. Bank Credit peaks at -0.30 % vs baseline in Q13, from +0.00 in Q1 to -0.23 in Q20. Credit Spread peaks at +0.00 pp in Q13, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -1.42 % vs baseline in Q8, from -0.08 in Q1 to -0.51 in Q20. vs USD peaks at +1.92 % vs baseline in Q8, from +1.08 in Q1 to +1.08 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.76 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.41 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.46 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.47 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.81 in Q20. Gold Price peaks at +3453.47 USD/oz (level) in Q1, from +3453.47 in Q1 to +2262.69 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.60 % vs baseline in Q8, from -0.01 in Q1 to +0.01 in Q20. Services GDP peaks at -0.77 % vs baseline in Q7, from -0.00 in Q1 to +0.03 in Q20. Capital Stock peaks at -0.09 % vs baseline in Q14, from -0.00 in Q1 to -0.09 in Q20.

Timing. The GDP response has mostly faded by Q16 (Q20 is +0.05%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/CA_Y.png)

![CPI Inflation](charts/CA_pi_cpi.png)

![Equity Index](charts/CA_equity.png)

![Gold Price](charts/CA_P_gold.png)

![Metals Price](charts/CA_P_metals.png)

![Food Price](charts/CA_P_food.png)

![Copper Price](charts/CA_P_copper.png)

![Wheat Price](charts/CA_P_wheat.png)

![Energy Price](charts/CA_P_energy.png)

![VIX](charts/CA_vix.png)

![Gas Price](charts/CA_P_gas.png)

![Bond Price (7y)](charts/CA_Q_B.png)

[Q1–Q20 JSON for Canada](numbers/CA.json)

## CH — Switzerland

The main impact of a 250bp rise in the risk premium on Switzerland would be a large drop in GDP of 1.10% by Q7. Equities peak at -25.04% in Q1.

Demand and trade. Consumption peaks at -0.78 % vs baseline in Q8, from +0.01 in Q1 to -0.12 in Q20. Investment peaks at -2.72 % vs baseline in Q7, from +0.09 in Q1 to -0.15 in Q20. Net Exports peaks at -0.29 % vs baseline in Q1, from -0.29 in Q1 to -0.07 in Q20. Gov Spending peaks at +0.22 % vs baseline in Q7, from +0.00 in Q1 to +0.03 in Q20. Gov Debt peaks at -0.43 % vs baseline in Q13, from +0.00 in Q1 to -0.34 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -1.45 % vs baseline in Q1, from -1.45 in Q1 to -0.45 in Q20.

Labour. Employment peaks at -0.94 % vs baseline in Q10, from +0.00 in Q1 to -0.36 in Q20. Unemployment peaks at +0.62 pp in Q11, from +0.00 in Q1 to +0.27 in Q20. Real Wages peaks at -0.89 % vs baseline in Q20, from +0.00 in Q1 to -0.89 in Q20.

Prices. The three-year CPI impulse is -0.84 percentage points. CPI Inflation peaks at -0.26 pp in Q1, from -0.26 in Q1 to +0.04 in Q20. Domestic Infl. peaks at -0.18 pp in Q1, from -0.18 in Q1 to +0.03 in Q20. Marginal Cost peaks at -0.66 % vs baseline in Q7, from -0.00 in Q1 to -0.08 in Q20.

Financial conditions. Policy Rate peaks at -0.33 pp (annualized) in Q10, from -0.06 in Q1 to -0.12 in Q20. Real Rate peaks at -0.08 pp (annualized) in Q10, from -0.02 in Q1 to -0.03 in Q20. Govt 3M Yield peaks at -0.33 pp (annualized) in Q10, from -0.06 in Q1 to -0.12 in Q20. Govt 2Y Yield peaks at -0.31 pp (annualized) in Q7, from -0.18 in Q1 to -0.06 in Q20. Govt 5Y Yield peaks at -0.23 pp (annualized) in Q2, from -0.22 in Q1 to -0.03 in Q20. Govt 10Y Yield peaks at -0.12 pp (annualized) in Q1, from -0.12 in Q1 to -0.02 in Q20. Govt 30Y Yield peaks at -0.04 pp (annualized) in Q1, from -0.04 in Q1 to -0.01 in Q20. Bond Price (7y) peaks at +2.29 % vs baseline in Q10, from +0.44 in Q1 to +0.86 in Q20. Bond Price 3M peaks at +0.08 % vs baseline in Q10, from +0.02 in Q1 to +0.03 in Q20. Bond Price 2Y peaks at +0.58 % vs baseline in Q7, from +0.35 in Q1 to +0.12 in Q20. Bond Price 5Y peaks at +1.01 % vs baseline in Q2, from +1.01 in Q1 to +0.12 in Q20. Bond Price 10Y peaks at +1.00 % vs baseline in Q1, from +1.00 in Q1 to +0.14 in Q20. Bond Price 30Y peaks at +0.77 % vs baseline in Q1, from +0.77 in Q1 to +0.11 in Q20. Equity Index peaks at -25.04 % vs baseline in Q1, from -25.04 in Q1 to -5.55 in Q20. VIX peaks at +42.54 index_level in Q1, from +42.54 in Q1 to +20.07 in Q20. Tobin's Q peaks at -1.91 % vs baseline in Q7, from +0.06 in Q1 to -0.10 in Q20. House Prices peaks at -0.86 % vs baseline in Q15, from +0.00 in Q1 to -0.77 in Q20. Bank Equity peaks at -0.51 % vs baseline in Q13, from +0.00 in Q1 to -0.39 in Q20. Bank Credit peaks at -0.40 % vs baseline in Q13, from +0.00 in Q1 to -0.30 in Q20. Credit Spread peaks at +0.00 pp in Q13, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +2.04 % vs baseline in Q1, from +2.04 in Q1 to +0.28 in Q20. vs USD peaks at -0.96 % vs baseline in Q8, from -0.40 in Q1 to +0.60 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.76 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.41 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.46 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.47 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.81 in Q20. Gold Price peaks at +3453.47 USD/oz (level) in Q1, from +3453.47 in Q1 to +2262.69 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.44 % vs baseline in Q1, from +0.44 in Q1 to +0.11 in Q20. Services GDP peaks at -0.87 % vs baseline in Q7, from -0.00 in Q1 to -0.10 in Q20. Capital Stock peaks at -0.13 % vs baseline in Q20, from +0.00 in Q1 to -0.13 in Q20.

Timing. The GDP response has mostly faded by Q17 (Q20 is -0.13%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/CH_Y.png)

![CPI Inflation](charts/CH_pi_cpi.png)

![Equity Index](charts/CH_equity.png)

![Gold Price](charts/CH_P_gold.png)

![Metals Price](charts/CH_P_metals.png)

![Food Price](charts/CH_P_food.png)

![Copper Price](charts/CH_P_copper.png)

![Wheat Price](charts/CH_P_wheat.png)

![Energy Price](charts/CH_P_energy.png)

![VIX](charts/CH_vix.png)

![Gas Price](charts/CH_P_gas.png)

![Investment](charts/CH_I.png)

[Q1–Q20 JSON for Switzerland](numbers/CH.json)

## DE — Germany

The main impact of a 250bp rise in the risk premium on Germany would be a large drop in GDP of 1.09% by Q7. Equities peak at -25.04% in Q1.

Demand and trade. Consumption peaks at -0.61 % vs baseline in Q8, from -0.01 in Q1 to -0.08 in Q20. Investment peaks at -2.87 % vs baseline in Q6, from -0.07 in Q1 to -0.16 in Q20. Net Exports peaks at +0.37 % vs baseline in Q7, from +0.11 in Q1 to -0.00 in Q20. Gov Spending peaks at +0.24 % vs baseline in Q7, from +0.00 in Q1 to +0.02 in Q20. Gov Debt peaks at +0.13 % vs baseline in Q15, from +0.00 in Q1 to +0.12 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.60 % vs baseline in Q1, from +0.60 in Q1 to -0.20 in Q20.

Labour. Employment peaks at -0.86 % vs baseline in Q11, from +0.00 in Q1 to -0.41 in Q20. Unemployment peaks at +0.61 pp in Q10, from +0.00 in Q1 to +0.24 in Q20. Real Wages peaks at -1.09 % vs baseline in Q20, from +0.00 in Q1 to -1.09 in Q20.

Prices. The three-year CPI impulse is -0.57 percentage points. CPI Inflation peaks at +0.13 pp in Q1, from +0.13 in Q1 to +0.02 in Q20. Domestic Infl. peaks at +0.09 pp in Q1, from +0.09 in Q1 to +0.01 in Q20. Marginal Cost peaks at -0.65 % vs baseline in Q7, from -0.00 in Q1 to -0.06 in Q20.

Financial conditions. Policy Rate peaks at -0.24 pp (annualized) in Q11, from +0.04 in Q1 to -0.06 in Q20. Real Rate peaks at -0.06 pp (annualized) in Q11, from +0.01 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -0.24 pp (annualized) in Q11, from +0.04 in Q1 to -0.06 in Q20. Govt 2Y Yield peaks at -0.22 pp (annualized) in Q8, from -0.04 in Q1 to -0.01 in Q20. Govt 5Y Yield peaks at -0.13 pp (annualized) in Q4, from -0.12 in Q1 to +0.01 in Q20. Govt 10Y Yield peaks at -0.06 pp (annualized) in Q4, from -0.06 in Q1 to +0.00 in Q20. Govt 30Y Yield peaks at -0.02 pp (annualized) in Q5, from -0.02 in Q1 to +0.00 in Q20. Bond Price (7y) peaks at +1.71 % vs baseline in Q11, from -0.29 in Q1 to +0.41 in Q20. Bond Price 3M peaks at +0.06 % vs baseline in Q11, from -0.01 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +0.42 % vs baseline in Q8, from +0.09 in Q1 to +0.02 in Q20. Bond Price 5Y peaks at +0.60 % vs baseline in Q4, from +0.55 in Q1 to -0.03 in Q20. Bond Price 10Y peaks at +0.49 % vs baseline in Q4, from +0.47 in Q1 to -0.03 in Q20. Bond Price 30Y peaks at +0.35 % vs baseline in Q5, from +0.33 in Q1 to -0.03 in Q20. Equity Index peaks at -25.04 % vs baseline in Q1, from -25.04 in Q1 to -5.23 in Q20. VIX peaks at +42.54 index_level in Q1, from +42.54 in Q1 to +20.07 in Q20. Tobin's Q peaks at -2.01 % vs baseline in Q6, from -0.05 in Q1 to -0.12 in Q20. House Prices peaks at -0.84 % vs baseline in Q14, from -0.00 in Q1 to -0.74 in Q20. Bank Equity peaks at -0.48 % vs baseline in Q13, from +0.00 in Q1 to -0.37 in Q20. Bank Credit peaks at -0.39 % vs baseline in Q13, from +0.00 in Q1 to -0.30 in Q20. Credit Spread peaks at +0.00 pp in Q13, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.37 % vs baseline in Q10, from +0.01 in Q1 to +0.16 in Q20. vs USD peaks at +1.65 % vs baseline in Q1, from +1.65 in Q1 to +0.85 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.76 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.41 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.46 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.47 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.81 in Q20. Gold Price peaks at +3453.47 USD/oz (level) in Q1, from +3453.47 in Q1 to +2262.69 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.24 % vs baseline in Q5, from -0.18 in Q1 to +0.04 in Q20. Services GDP peaks at -0.74 % vs baseline in Q7, from -0.00 in Q1 to -0.07 in Q20. Capital Stock peaks at -0.14 % vs baseline in Q20, from -0.00 in Q1 to -0.14 in Q20.

Timing. The GDP response has mostly faded by Q17 (Q20 is -0.10%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/DE_Y.png)

![CPI Inflation](charts/DE_pi_cpi.png)

![Equity Index](charts/DE_equity.png)

![Gold Price](charts/DE_P_gold.png)

![Metals Price](charts/DE_P_metals.png)

![Food Price](charts/DE_P_food.png)

![Copper Price](charts/DE_P_copper.png)

![Wheat Price](charts/DE_P_wheat.png)

![Energy Price](charts/DE_P_energy.png)

![VIX](charts/DE_vix.png)

![Gas Price](charts/DE_P_gas.png)

![Investment](charts/DE_I.png)

[Q1–Q20 JSON for Germany](numbers/DE.json)

## FR — France

The main impact of a 250bp rise in the risk premium on France would be a large drop in GDP of 1.04% by Q7. Equities peak at -25.04% in Q1.

Demand and trade. Consumption peaks at -0.56 % vs baseline in Q8, from -0.01 in Q1 to -0.07 in Q20. Investment peaks at -2.74 % vs baseline in Q6, from -0.07 in Q1 to -0.13 in Q20. Net Exports peaks at +0.20 % vs baseline in Q7, from +0.09 in Q1 to -0.01 in Q20. Gov Spending peaks at +0.25 % vs baseline in Q7, from +0.00 in Q1 to +0.02 in Q20. Gov Debt peaks at +0.58 % vs baseline in Q16, from +0.00 in Q1 to +0.55 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.60 % vs baseline in Q1, from +0.60 in Q1 to -0.20 in Q20.

Labour. Employment peaks at -0.78 % vs baseline in Q12, from +0.00 in Q1 to -0.44 in Q20. Unemployment peaks at +0.59 pp in Q10, from +0.00 in Q1 to +0.23 in Q20. Real Wages peaks at -0.83 % vs baseline in Q20, from +0.00 in Q1 to -0.83 in Q20.

Prices. The three-year CPI impulse is -0.52 percentage points. CPI Inflation peaks at -0.09 pp in Q7, from +0.09 in Q1 to +0.02 in Q20. Domestic Infl. peaks at -0.07 pp in Q7, from +0.07 in Q1 to +0.01 in Q20. Marginal Cost peaks at -0.62 % vs baseline in Q7, from -0.00 in Q1 to -0.05 in Q20.

Financial conditions. Policy Rate peaks at -0.24 pp (annualized) in Q11, from +0.04 in Q1 to -0.06 in Q20. Real Rate peaks at -0.06 pp (annualized) in Q11, from +0.01 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -0.24 pp (annualized) in Q11, from +0.04 in Q1 to -0.06 in Q20. Govt 2Y Yield peaks at -0.22 pp (annualized) in Q8, from -0.04 in Q1 to -0.01 in Q20. Govt 5Y Yield peaks at -0.13 pp (annualized) in Q4, from -0.12 in Q1 to +0.01 in Q20. Govt 10Y Yield peaks at -0.06 pp (annualized) in Q4, from -0.06 in Q1 to +0.00 in Q20. Govt 30Y Yield peaks at -0.02 pp (annualized) in Q5, from -0.02 in Q1 to +0.00 in Q20. Bond Price (7y) peaks at +1.71 % vs baseline in Q11, from -0.29 in Q1 to +0.41 in Q20. Bond Price 3M peaks at +0.06 % vs baseline in Q11, from -0.01 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +0.42 % vs baseline in Q8, from +0.09 in Q1 to +0.02 in Q20. Bond Price 5Y peaks at +0.60 % vs baseline in Q4, from +0.55 in Q1 to -0.03 in Q20. Bond Price 10Y peaks at +0.49 % vs baseline in Q4, from +0.47 in Q1 to -0.03 in Q20. Bond Price 30Y peaks at +0.35 % vs baseline in Q5, from +0.33 in Q1 to -0.03 in Q20. Equity Index peaks at -25.04 % vs baseline in Q1, from -25.04 in Q1 to -5.21 in Q20. VIX peaks at +42.54 index_level in Q1, from +42.54 in Q1 to +20.07 in Q20. Tobin's Q peaks at -1.92 % vs baseline in Q6, from -0.05 in Q1 to -0.09 in Q20. House Prices peaks at -0.77 % vs baseline in Q14, from -0.00 in Q1 to -0.67 in Q20. Bank Equity peaks at -0.48 % vs baseline in Q13, from +0.00 in Q1 to -0.37 in Q20. Bank Credit peaks at -0.38 % vs baseline in Q13, from +0.00 in Q1 to -0.30 in Q20. Credit Spread peaks at +0.00 pp in Q13, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.25 % vs baseline in Q10, from +0.06 in Q1 to +0.12 in Q20. vs USD peaks at +1.65 % vs baseline in Q1, from +1.65 in Q1 to +0.86 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.76 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.41 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.46 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.47 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.81 in Q20. Gold Price peaks at +3453.47 USD/oz (level) in Q1, from +3453.47 in Q1 to +2262.69 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.19 % vs baseline in Q4, from -0.18 in Q1 to +0.05 in Q20. Services GDP peaks at -0.80 % vs baseline in Q7, from -0.00 in Q1 to -0.07 in Q20. Capital Stock peaks at -0.13 % vs baseline in Q20, from -0.00 in Q1 to -0.13 in Q20.

Timing. The GDP response has mostly faded by Q17 (Q20 is -0.09%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/FR_Y.png)

![CPI Inflation](charts/FR_pi_cpi.png)

![Equity Index](charts/FR_equity.png)

![Gold Price](charts/FR_P_gold.png)

![Metals Price](charts/FR_P_metals.png)

![Food Price](charts/FR_P_food.png)

![Copper Price](charts/FR_P_copper.png)

![Wheat Price](charts/FR_P_wheat.png)

![Energy Price](charts/FR_P_energy.png)

![VIX](charts/FR_vix.png)

![Gas Price](charts/FR_P_gas.png)

![Investment](charts/FR_I.png)

[Q1–Q20 JSON for France](numbers/FR.json)

## UK — United Kingdom

The main impact of a 250bp rise in the risk premium on United Kingdom would be a large drop in GDP of 1.02% by Q7. Equities peak at -25.05% in Q1.

Demand and trade. Consumption peaks at -0.64 % vs baseline in Q8, from -0.00 in Q1 to -0.09 in Q20. Investment peaks at -2.76 % vs baseline in Q7, from -0.01 in Q1 to -0.11 in Q20. Net Exports peaks at +0.07 % vs baseline in Q7, from -0.01 in Q1 to -0.02 in Q20. Gov Spending peaks at +0.21 % vs baseline in Q7, from +0.00 in Q1 to +0.02 in Q20. Gov Debt peaks at -0.08 % vs baseline in Q10, from +0.00 in Q1 to -0.03 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -1.40 % vs baseline in Q11, from -0.11 in Q1 to -0.48 in Q20.

Labour. Employment peaks at -0.97 % vs baseline in Q10, from +0.00 in Q1 to -0.34 in Q20. Unemployment peaks at +0.57 pp in Q11, from +0.00 in Q1 to +0.23 in Q20. Real Wages peaks at -1.03 % vs baseline in Q20, from +0.00 in Q1 to -1.03 in Q20.

Prices. The three-year CPI impulse is -0.95 percentage points. CPI Inflation peaks at -0.12 pp in Q7, from -0.01 in Q1 to +0.03 in Q20. Domestic Infl. peaks at -0.09 pp in Q7, from -0.01 in Q1 to +0.02 in Q20. Marginal Cost peaks at -0.61 % vs baseline in Q7, from -0.00 in Q1 to -0.06 in Q20.

Financial conditions. Policy Rate peaks at -0.15 pp (annualized) in Q13, from -0.00 in Q1 to -0.10 in Q20. Real Rate peaks at -0.04 pp (annualized) in Q13, from -0.00 in Q1 to -0.03 in Q20. Govt 3M Yield peaks at -0.15 pp (annualized) in Q13, from -0.00 in Q1 to -0.10 in Q20. Govt 2Y Yield peaks at -0.14 pp (annualized) in Q10, from -0.04 in Q1 to -0.07 in Q20. Govt 5Y Yield peaks at -0.11 pp (annualized) in Q6, from -0.10 in Q1 to -0.05 in Q20. Govt 10Y Yield peaks at -0.07 pp (annualized) in Q4, from -0.07 in Q1 to -0.04 in Q20. Govt 30Y Yield peaks at -0.03 pp (annualized) in Q1, from -0.03 in Q1 to -0.01 in Q20. Bond Price (7y) peaks at +1.18 % vs baseline in Q11, from -0.12 in Q1 to +0.72 in Q20. Bond Price 3M peaks at +0.04 % vs baseline in Q13, from +0.00 in Q1 to +0.03 in Q20. Bond Price 2Y peaks at +0.27 % vs baseline in Q10, from +0.08 in Q1 to +0.14 in Q20. Bond Price 5Y peaks at +0.51 % vs baseline in Q6, from +0.44 in Q1 to +0.23 in Q20. Bond Price 10Y peaks at +0.61 % vs baseline in Q4, from +0.59 in Q1 to +0.29 in Q20. Bond Price 30Y peaks at +0.54 % vs baseline in Q1, from +0.54 in Q1 to +0.26 in Q20. Equity Index peaks at -25.05 % vs baseline in Q1, from -25.05 in Q1 to -5.26 in Q20. VIX peaks at +42.54 index_level in Q1, from +42.54 in Q1 to +20.07 in Q20. Tobin's Q peaks at -1.93 % vs baseline in Q7, from -0.00 in Q1 to -0.08 in Q20. House Prices peaks at -0.72 % vs baseline in Q14, from -0.00 in Q1 to -0.63 in Q20. Bank Equity peaks at -0.40 % vs baseline in Q13, from +0.00 in Q1 to -0.31 in Q20. Bank Credit peaks at -0.32 % vs baseline in Q13, from +0.00 in Q1 to -0.25 in Q20. Credit Spread peaks at +0.00 pp in Q13, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +1.67 % vs baseline in Q10, from +0.61 in Q1 to +0.37 in Q20. vs USD peaks at -0.98 % vs baseline in Q10, from +0.93 in Q1 to +0.58 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.76 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.41 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.46 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.47 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.81 in Q20. Gold Price peaks at +3453.47 USD/oz (level) in Q1, from +3453.47 in Q1 to +2262.69 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.34 % vs baseline in Q12, from +0.03 in Q1 to +0.13 in Q20. Services GDP peaks at -0.80 % vs baseline in Q7, from -0.00 in Q1 to -0.08 in Q20. Capital Stock peaks at -0.13 % vs baseline in Q20, from +0.00 in Q1 to -0.13 in Q20.

Timing. The GDP response has mostly faded by Q17 (Q20 is -0.11%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/UK_Y.png)

![CPI Inflation](charts/UK_pi_cpi.png)

![Equity Index](charts/UK_equity.png)

![Gold Price](charts/UK_P_gold.png)

![Metals Price](charts/UK_P_metals.png)

![Food Price](charts/UK_P_food.png)

![Copper Price](charts/UK_P_copper.png)

![Wheat Price](charts/UK_P_wheat.png)

![Energy Price](charts/UK_P_energy.png)

![VIX](charts/UK_vix.png)

![Gas Price](charts/UK_P_gas.png)

![Investment](charts/UK_I.png)

[Q1–Q20 JSON for United Kingdom](numbers/UK.json)

## SE — Sweden

The main impact of a 250bp rise in the risk premium on Sweden would be a large drop in GDP of 0.96% by Q7. Equities peak at -25.05% in Q1.

Demand and trade. Consumption peaks at -0.55 % vs baseline in Q8, from -0.00 in Q1 to -0.06 in Q20. Investment peaks at -2.40 % vs baseline in Q6, from -0.01 in Q1 to -0.09 in Q20. Net Exports peaks at -0.10 % vs baseline in Q19, from -0.00 in Q1 to -0.10 in Q20. Gov Spending peaks at +0.20 % vs baseline in Q7, from +0.00 in Q1 to +0.01 in Q20. Gov Debt peaks at +0.33 % vs baseline in Q13, from +0.00 in Q1 to +0.26 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -0.50 % vs baseline in Q19, from -0.01 in Q1 to -0.50 in Q20.

Labour. Employment peaks at -0.71 % vs baseline in Q11, from +0.00 in Q1 to -0.37 in Q20. Unemployment peaks at +0.54 pp in Q10, from +0.00 in Q1 to +0.20 in Q20. Real Wages peaks at -1.08 % vs baseline in Q20, from +0.00 in Q1 to -1.08 in Q20.

Prices. The three-year CPI impulse is -0.67 percentage points. CPI Inflation peaks at -0.09 pp in Q7, from -0.00 in Q1 to +0.02 in Q20. Domestic Infl. peaks at -0.06 pp in Q7, from -0.00 in Q1 to +0.01 in Q20. Marginal Cost peaks at -0.57 % vs baseline in Q7, from -0.00 in Q1 to -0.04 in Q20.

Financial conditions. Policy Rate peaks at -0.30 pp (annualized) in Q10, from -0.00 in Q1 to -0.05 in Q20. Real Rate peaks at -0.08 pp (annualized) in Q10, from -0.00 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -0.30 pp (annualized) in Q10, from -0.00 in Q1 to -0.05 in Q20. Govt 2Y Yield peaks at -0.27 pp (annualized) in Q7, from -0.11 in Q1 to +0.01 in Q20. Govt 5Y Yield peaks at -0.17 pp (annualized) in Q2, from -0.17 in Q1 to +0.03 in Q20. Govt 10Y Yield peaks at -0.07 pp (annualized) in Q1, from -0.07 in Q1 to +0.02 in Q20. Govt 30Y Yield peaks at -0.02 pp (annualized) in Q1, from -0.02 in Q1 to +0.01 in Q20. Bond Price (7y) peaks at +1.89 % vs baseline in Q10, from -0.09 in Q1 to +0.29 in Q20. Bond Price 3M peaks at +0.08 % vs baseline in Q10, from +0.00 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +0.52 % vs baseline in Q7, from +0.21 in Q1 to -0.02 in Q20. Bond Price 5Y peaks at +0.75 % vs baseline in Q2, from +0.75 in Q1 to -0.12 in Q20. Bond Price 10Y peaks at +0.56 % vs baseline in Q1, from +0.56 in Q1 to -0.15 in Q20. Bond Price 30Y peaks at +0.35 % vs baseline in Q1, from +0.35 in Q1 to -0.15 in Q20. Equity Index peaks at -25.05 % vs baseline in Q1, from -25.05 in Q1 to -5.19 in Q20. VIX peaks at +42.54 index_level in Q1, from +42.54 in Q1 to +20.07 in Q20. Tobin's Q peaks at -1.68 % vs baseline in Q6, from -0.00 in Q1 to -0.06 in Q20. House Prices peaks at -0.72 % vs baseline in Q14, from -0.00 in Q1 to -0.62 in Q20. Bank Equity peaks at -0.39 % vs baseline in Q13, from +0.00 in Q1 to -0.30 in Q20. Bank Credit peaks at -0.31 % vs baseline in Q13, from +0.00 in Q1 to -0.24 in Q20. Credit Spread peaks at +0.00 pp in Q13, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.61 % vs baseline in Q1, from +0.61 in Q1 to +0.49 in Q20. vs USD peaks at +1.04 % vs baseline in Q1, from +1.04 in Q1 to +0.56 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.76 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.41 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.46 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.47 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.81 in Q20. Gold Price peaks at +3453.47 USD/oz (level) in Q1, from +3453.47 in Q1 to +2262.69 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.16 % vs baseline in Q6, from +0.00 in Q1 to +0.14 in Q20. Services GDP peaks at -0.68 % vs baseline in Q7, from -0.00 in Q1 to -0.05 in Q20. Capital Stock peaks at -0.11 % vs baseline in Q20, from +0.00 in Q1 to -0.11 in Q20.

Timing. The GDP response has mostly faded by Q17 (Q20 is -0.07%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/SE_Y.png)

![CPI Inflation](charts/SE_pi_cpi.png)

![Equity Index](charts/SE_equity.png)

![Gold Price](charts/SE_P_gold.png)

![Metals Price](charts/SE_P_metals.png)

![Food Price](charts/SE_P_food.png)

![Copper Price](charts/SE_P_copper.png)

![Wheat Price](charts/SE_P_wheat.png)

![Energy Price](charts/SE_P_energy.png)

![VIX](charts/SE_vix.png)

![Gas Price](charts/SE_P_gas.png)

![Investment](charts/SE_I.png)

[Q1–Q20 JSON for Sweden](numbers/SE.json)

## AU — Australia

The main impact of a 250bp rise in the risk premium on Australia would be a large drop in GDP of 0.95% by Q7. Equities peak at -25.05% in Q1.

Demand and trade. Consumption peaks at -0.61 % vs baseline in Q8, from -0.00 in Q1 to -0.01 in Q20. Investment peaks at -2.16 % vs baseline in Q6, from -0.01 in Q1 to +0.41 in Q20. Net Exports peaks at -0.24 % vs baseline in Q9, from +0.00 in Q1 to -0.11 in Q20. Gov Spending peaks at +0.12 % vs baseline in Q7, from +0.00 in Q1 to -0.02 in Q20. Gov Debt peaks at -0.35 % vs baseline in Q14, from +0.00 in Q1 to -0.28 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +2.23 % vs baseline in Q8, from +0.02 in Q1 to -0.21 in Q20.

Labour. Employment peaks at -0.88 % vs baseline in Q10, from +0.00 in Q1 to -0.19 in Q20. Unemployment peaks at +0.53 pp in Q10, from +0.00 in Q1 to +0.14 in Q20. Real Wages peaks at -1.11 % vs baseline in Q20, from +0.00 in Q1 to -1.11 in Q20.

Prices. The three-year CPI impulse is -0.57 percentage points. CPI Inflation peaks at -0.08 pp in Q7, from +0.00 in Q1 to +0.01 in Q20. Domestic Infl. peaks at -0.05 pp in Q7, from +0.00 in Q1 to +0.01 in Q20. Marginal Cost peaks at -0.57 % vs baseline in Q7, from -0.00 in Q1 to +0.02 in Q20.

Financial conditions. Policy Rate peaks at -0.58 pp (annualized) in Q11, from +0.00 in Q1 to -0.19 in Q20. Real Rate peaks at -0.15 pp (annualized) in Q11, from +0.00 in Q1 to -0.05 in Q20. Govt 3M Yield peaks at -0.58 pp (annualized) in Q11, from +0.00 in Q1 to -0.19 in Q20. Govt 2Y Yield peaks at -0.53 pp (annualized) in Q8, from -0.21 in Q1 to -0.07 in Q20. Govt 5Y Yield peaks at -0.36 pp (annualized) in Q4, from -0.35 in Q1 to -0.01 in Q20. Govt 10Y Yield peaks at -0.17 pp (annualized) in Q1, from -0.17 in Q1 to +0.00 in Q20. Govt 30Y Yield peaks at -0.05 pp (annualized) in Q2, from -0.05 in Q1 to +0.00 in Q20. Bond Price (7y) peaks at +3.63 % vs baseline in Q11, from -0.05 in Q1 to +1.18 in Q20. Bond Price 3M peaks at +0.15 % vs baseline in Q11, from -0.00 in Q1 to +0.05 in Q20. Bond Price 2Y peaks at +1.01 % vs baseline in Q8, from +0.40 in Q1 to +0.14 in Q20. Bond Price 5Y peaks at +1.61 % vs baseline in Q4, from +1.55 in Q1 to +0.03 in Q20. Bond Price 10Y peaks at +1.40 % vs baseline in Q1, from +1.40 in Q1 to -0.03 in Q20. Bond Price 30Y peaks at +0.96 % vs baseline in Q2, from +0.96 in Q1 to -0.06 in Q20. Equity Index peaks at -25.05 % vs baseline in Q1, from -25.05 in Q1 to -4.91 in Q20. VIX peaks at +42.54 index_level in Q1, from +42.54 in Q1 to +20.07 in Q20. Tobin's Q peaks at -1.51 % vs baseline in Q6, from -0.01 in Q1 to +0.29 in Q20. House Prices peaks at -0.62 % vs baseline in Q13, from -0.00 in Q1 to -0.48 in Q20. Bank Equity peaks at -0.35 % vs baseline in Q13, from +0.00 in Q1 to -0.28 in Q20. Bank Credit peaks at -0.28 % vs baseline in Q13, from +0.00 in Q1 to -0.22 in Q20. Credit Spread peaks at +0.00 pp in Q13, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -1.84 % vs baseline in Q8, from +0.62 in Q1 to +0.34 in Q20. vs USD peaks at +2.61 % vs baseline in Q8, from +1.07 in Q1 to +0.84 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.76 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.41 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.46 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.47 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.81 in Q20. Gold Price peaks at +3453.47 USD/oz (level) in Q1, from +3453.47 in Q1 to +2262.69 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.76 % vs baseline in Q8, from -0.01 in Q1 to +0.07 in Q20. Services GDP peaks at -0.68 % vs baseline in Q7, from -0.00 in Q1 to +0.02 in Q20. Capital Stock peaks at -0.08 % vs baseline in Q14, from +0.00 in Q1 to -0.07 in Q20.

Timing. The GDP response has mostly faded by Q16 (Q20 is +0.03%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/AU_Y.png)

![CPI Inflation](charts/AU_pi_cpi.png)

![Equity Index](charts/AU_equity.png)

![Gold Price](charts/AU_P_gold.png)

![Metals Price](charts/AU_P_metals.png)

![Food Price](charts/AU_P_food.png)

![Copper Price](charts/AU_P_copper.png)

![Wheat Price](charts/AU_P_wheat.png)

![Energy Price](charts/AU_P_energy.png)

![VIX](charts/AU_vix.png)

![Gas Price](charts/AU_P_gas.png)

![Bond Price (7y)](charts/AU_Q_B.png)

[Q1–Q20 JSON for Australia](numbers/AU.json)

## US — United States

The main impact of a 250bp rise in the risk premium on the United States would be a large drop in GDP of 0.92% by Q7. Equities peak at -25.06% in Q1.

Demand and trade. Consumption peaks at -0.61 % vs baseline in Q8, from +0.00 in Q1 to +0.12 in Q20. Investment peaks at -1.89 % vs baseline in Q6, from +0.02 in Q1 to +0.66 in Q20. Net Exports peaks at -0.07 % vs baseline in Q20, from -0.06 in Q1 to -0.07 in Q20. Gov Spending peaks at +0.17 % vs baseline in Q7, from +0.00 in Q1 to -0.04 in Q20. Gov Debt peaks at -0.17 % vs baseline in Q9, from +0.00 in Q1 to +0.02 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -1.05 % vs baseline in Q20, from -1.05 in Q1 to -1.05 in Q20.

Labour. Employment peaks at -0.89 % vs baseline in Q9, from +0.00 in Q1 to +0.06 in Q20. Unemployment peaks at +0.50 pp in Q10, from +0.00 in Q1 to +0.02 in Q20. Real Wages peaks at -0.95 % vs baseline in Q20, from +0.00 in Q1 to -0.95 in Q20.

Prices. The three-year CPI impulse is -0.72 percentage points. CPI Inflation peaks at -0.09 pp in Q7, from -0.03 in Q1 to +0.02 in Q20. Domestic Infl. peaks at -0.06 pp in Q7, from -0.02 in Q1 to +0.01 in Q20. Marginal Cost peaks at -0.55 % vs baseline in Q7, from -0.00 in Q1 to +0.12 in Q20.

Financial conditions. Policy Rate peaks at -0.70 pp (annualized) in Q10, from -0.02 in Q1 to -0.03 in Q20. Real Rate peaks at -0.18 pp (annualized) in Q10, from -0.01 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -0.70 pp (annualized) in Q10, from -0.02 in Q1 to -0.03 in Q20. Govt 2Y Yield peaks at -0.62 pp (annualized) in Q7, from -0.30 in Q1 to +0.09 in Q20. Govt 5Y Yield peaks at -0.37 pp (annualized) in Q1, from -0.37 in Q1 to +0.11 in Q20. Govt 10Y Yield peaks at -0.13 pp (annualized) in Q1, from -0.13 in Q1 to +0.07 in Q20. Govt 30Y Yield peaks at -0.04 pp (annualized) in Q1, from -0.04 in Q1 to +0.03 in Q20. Bond Price (7y) peaks at +4.62 % vs baseline in Q10, from +0.14 in Q1 to +0.39 in Q20. Bond Price 3M peaks at +0.18 % vs baseline in Q10, from +0.01 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +1.19 % vs baseline in Q7, from +0.58 in Q1 to -0.17 in Q20. Bond Price 5Y peaks at +1.69 % vs baseline in Q1, from +1.69 in Q1 to -0.50 in Q20. Bond Price 10Y peaks at +1.06 % vs baseline in Q1, from +1.06 in Q1 to -0.59 in Q20. Bond Price 30Y peaks at +0.67 % vs baseline in Q1, from +0.67 in Q1 to -0.45 in Q20. Equity Index peaks at -25.06 % vs baseline in Q1, from -25.06 in Q1 to -4.30 in Q20. VIX peaks at +42.54 index_level in Q1, from +42.54 in Q1 to +20.07 in Q20. Tobin's Q peaks at -1.32 % vs baseline in Q6, from +0.02 in Q1 to +0.46 in Q20. House Prices peaks at -0.50 % vs baseline in Q12, from +0.00 in Q1 to -0.28 in Q20. Bank Equity peaks at -0.32 % vs baseline in Q13, from +0.00 in Q1 to -0.25 in Q20. Bank Credit peaks at -0.26 % vs baseline in Q13, from +0.00 in Q1 to -0.20 in Q20. Credit Spread peaks at +0.00 pp in Q13, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +2.30 % vs baseline in Q1, from +2.30 in Q1 to +1.25 in Q20. vs USD peaks at +2.30 % vs baseline in Q1, from +2.30 in Q1 to +1.25 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.76 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.41 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.46 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.47 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.81 in Q20. Gold Price peaks at +3453.47 USD/oz (level) in Q1, from +3453.47 in Q1 to +2262.69 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.36 % vs baseline in Q20, from +0.31 in Q1 to +0.36 in Q20. Services GDP peaks at -0.71 % vs baseline in Q7, from -0.00 in Q1 to +0.16 in Q20. Capital Stock peaks at -0.06 % vs baseline in Q12, from +0.00 in Q1 to -0.04 in Q20.

Timing. The GDP response has mostly faded by Q14 (Q20 is +0.21%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/US_Y.png)

![CPI Inflation](charts/US_pi_cpi.png)

![Equity Index](charts/US_equity.png)

![Gold Price](charts/US_P_gold.png)

![Metals Price](charts/US_P_metals.png)

![Food Price](charts/US_P_food.png)

![Copper Price](charts/US_P_copper.png)

![Wheat Price](charts/US_P_wheat.png)

![Energy Price](charts/US_P_energy.png)

![VIX](charts/US_vix.png)

![Bond Price (7y)](charts/US_Q_B.png)

![Gas Price](charts/US_P_gas.png)

[Q1–Q20 JSON for United States](numbers/US.json)

## ES — Spain

The main impact of a 250bp rise in the risk premium on Spain would be a large drop in GDP of 0.92% by Q7. Equities peak at -25.05% in Q1.

Demand and trade. Consumption peaks at -0.52 % vs baseline in Q8, from -0.01 in Q1 to -0.05 in Q20. Investment peaks at -2.42 % vs baseline in Q6, from -0.07 in Q1 to -0.04 in Q20. Net Exports peaks at +0.27 % vs baseline in Q7, from +0.11 in Q1 to -0.01 in Q20. Gov Spending peaks at +0.20 % vs baseline in Q7, from +0.00 in Q1 to +0.01 in Q20. Gov Debt peaks at +0.05 % vs baseline in Q15, from +0.00 in Q1 to +0.05 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.73 % vs baseline in Q1, from +0.73 in Q1 to -0.17 in Q20.

Labour. Employment peaks at -0.73 % vs baseline in Q11, from +0.00 in Q1 to -0.35 in Q20. Unemployment peaks at +0.35 pp in Q10, from +0.00 in Q1 to +0.13 in Q20. Real Wages peaks at -0.75 % vs baseline in Q20, from +0.00 in Q1 to -0.75 in Q20.

Prices. The three-year CPI impulse is -0.47 percentage points. CPI Inflation peaks at +0.11 pp in Q1, from +0.11 in Q1 to +0.02 in Q20. Domestic Infl. peaks at +0.08 pp in Q1, from +0.08 in Q1 to +0.01 in Q20. Marginal Cost peaks at -0.55 % vs baseline in Q7, from -0.00 in Q1 to -0.03 in Q20.

Financial conditions. Policy Rate peaks at -0.24 pp (annualized) in Q11, from +0.04 in Q1 to -0.06 in Q20. Real Rate peaks at -0.06 pp (annualized) in Q11, from +0.01 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -0.24 pp (annualized) in Q11, from +0.04 in Q1 to -0.06 in Q20. Govt 2Y Yield peaks at -0.22 pp (annualized) in Q8, from -0.04 in Q1 to -0.01 in Q20. Govt 5Y Yield peaks at -0.13 pp (annualized) in Q4, from -0.12 in Q1 to +0.01 in Q20. Govt 10Y Yield peaks at -0.06 pp (annualized) in Q4, from -0.06 in Q1 to +0.00 in Q20. Govt 30Y Yield peaks at -0.02 pp (annualized) in Q5, from -0.02 in Q1 to +0.00 in Q20. Bond Price (7y) peaks at +1.71 % vs baseline in Q11, from -0.29 in Q1 to +0.41 in Q20. Bond Price 3M peaks at +0.06 % vs baseline in Q11, from -0.01 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +0.42 % vs baseline in Q8, from +0.09 in Q1 to +0.02 in Q20. Bond Price 5Y peaks at +0.60 % vs baseline in Q4, from +0.55 in Q1 to -0.03 in Q20. Bond Price 10Y peaks at +0.49 % vs baseline in Q4, from +0.47 in Q1 to -0.03 in Q20. Bond Price 30Y peaks at +0.35 % vs baseline in Q5, from +0.33 in Q1 to -0.03 in Q20. Equity Index peaks at -25.05 % vs baseline in Q1, from -25.05 in Q1 to -5.10 in Q20. VIX peaks at +42.54 index_level in Q1, from +42.54 in Q1 to +20.07 in Q20. Tobin's Q peaks at -1.70 % vs baseline in Q6, from -0.05 in Q1 to -0.03 in Q20. House Prices peaks at -0.67 % vs baseline in Q14, from -0.00 in Q1 to -0.57 in Q20. Bank Equity peaks at -0.32 % vs baseline in Q13, from +0.00 in Q1 to -0.25 in Q20. Bank Credit peaks at -0.26 % vs baseline in Q13, from +0.00 in Q1 to -0.20 in Q20. Credit Spread peaks at +0.00 pp in Q13, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.51 % vs baseline in Q9, from +0.20 in Q1 to +0.16 in Q20. vs USD peaks at +1.77 % vs baseline in Q1, from +1.77 in Q1 to +0.88 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.76 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.41 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.46 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.47 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.81 in Q20. Gold Price peaks at +3453.47 USD/oz (level) in Q1, from +3453.47 in Q1 to +2262.69 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.22 % vs baseline in Q1, from -0.22 in Q1 to +0.05 in Q20. Services GDP peaks at -0.68 % vs baseline in Q7, from -0.00 in Q1 to -0.04 in Q20. Capital Stock peaks at -0.11 % vs baseline in Q20, from -0.00 in Q1 to -0.11 in Q20.

Timing. The GDP response has mostly faded by Q16 (Q20 is -0.06%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/ES_Y.png)

![CPI Inflation](charts/ES_pi_cpi.png)

![Equity Index](charts/ES_equity.png)

![Gold Price](charts/ES_P_gold.png)

![Metals Price](charts/ES_P_metals.png)

![Food Price](charts/ES_P_food.png)

![Copper Price](charts/ES_P_copper.png)

![Wheat Price](charts/ES_P_wheat.png)

![Energy Price](charts/ES_P_energy.png)

![VIX](charts/ES_vix.png)

![Gas Price](charts/ES_P_gas.png)

![Investment](charts/ES_I.png)

[Q1–Q20 JSON for Spain](numbers/ES.json)

## JP — Japan

The main impact of a 250bp rise in the risk premium on Japan would be a large drop in GDP of 0.90% by Q7. Equities peak at -25.04% in Q1.

Demand and trade. Consumption peaks at -0.60 % vs baseline in Q8, from +0.00 in Q1 to -0.10 in Q20. Investment peaks at -2.43 % vs baseline in Q7, from +0.01 in Q1 to -0.22 in Q20. Net Exports peaks at -0.14 % vs baseline in Q1, from -0.14 in Q1 to -0.12 in Q20. Gov Spending peaks at +0.18 % vs baseline in Q7, from +0.00 in Q1 to +0.02 in Q20. Gov Debt peaks at -0.21 % vs baseline in Q20, from +0.00 in Q1 to -0.21 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -3.46 % vs baseline in Q10, from -1.58 in Q1 to -1.81 in Q20.

Labour. Employment peaks at -0.78 % vs baseline in Q10, from +0.00 in Q1 to -0.32 in Q20. Unemployment peaks at +0.51 pp in Q10, from +0.00 in Q1 to +0.22 in Q20. Real Wages peaks at -0.76 % vs baseline in Q19, from +0.00 in Q1 to -0.75 in Q20.

Prices. The three-year CPI impulse is -1.17 percentage points. CPI Inflation peaks at -0.18 pp in Q1, from -0.18 in Q1 to +0.06 in Q20. Domestic Infl. peaks at -0.13 pp in Q1, from -0.13 in Q1 to +0.04 in Q20. Marginal Cost peaks at -0.54 % vs baseline in Q7, from -0.00 in Q1 to -0.07 in Q20.

Financial conditions. Policy Rate peaks at -0.10 pp (annualized) in Q12, from -0.01 in Q1 to -0.05 in Q20. Real Rate peaks at -0.02 pp (annualized) in Q12, from -0.00 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -0.10 pp (annualized) in Q12, from -0.01 in Q1 to -0.05 in Q20. Govt 2Y Yield peaks at -0.09 pp (annualized) in Q8, from -0.05 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at -0.07 pp (annualized) in Q4, from -0.07 in Q1 to -0.01 in Q20. Govt 10Y Yield peaks at -0.04 pp (annualized) in Q1, from -0.04 in Q1 to -0.00 in Q20. Govt 30Y Yield peaks at -0.01 pp (annualized) in Q1, from -0.01 in Q1 to +0.00 in Q20. Bond Price (7y) peaks at +1.54 % vs baseline in Q11, from -0.16 in Q1 to +0.50 in Q20. Bond Price 3M peaks at +0.02 % vs baseline in Q12, from +0.00 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +0.18 % vs baseline in Q8, from +0.09 in Q1 to +0.05 in Q20. Bond Price 5Y peaks at +0.32 % vs baseline in Q4, from +0.31 in Q1 to +0.05 in Q20. Bond Price 10Y peaks at +0.31 % vs baseline in Q1, from +0.31 in Q1 to +0.03 in Q20. Bond Price 30Y peaks at +0.18 % vs baseline in Q1, from +0.18 in Q1 to -0.03 in Q20. Equity Index peaks at -25.04 % vs baseline in Q1, from -25.04 in Q1 to -5.37 in Q20. VIX peaks at +42.54 index_level in Q1, from +42.54 in Q1 to +20.07 in Q20. Tobin's Q peaks at -1.70 % vs baseline in Q7, from +0.01 in Q1 to -0.15 in Q20. House Prices peaks at -0.63 % vs baseline in Q15, from +0.00 in Q1 to -0.57 in Q20. Bank Equity peaks at -0.41 % vs baseline in Q13, from +0.00 in Q1 to -0.32 in Q20. Bank Credit peaks at -0.32 % vs baseline in Q13, from +0.00 in Q1 to -0.25 in Q20. Credit Spread peaks at +0.00 pp in Q13, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +4.34 % vs baseline in Q10, from +2.33 in Q1 to +2.10 in Q20. vs USD peaks at -3.04 % vs baseline in Q10, from -0.53 in Q1 to -0.75 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.76 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.41 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.46 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.47 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.81 in Q20. Gold Price peaks at +3453.47 USD/oz (level) in Q1, from +3453.47 in Q1 to +2262.69 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.93 % vs baseline in Q11, from +0.47 in Q1 to +0.52 in Q20. Services GDP peaks at -0.62 % vs baseline in Q7, from -0.00 in Q1 to -0.08 in Q20. Capital Stock peaks at -0.12 % vs baseline in Q20, from +0.00 in Q1 to -0.12 in Q20.

Timing. The GDP response has mostly faded by Q17 (Q20 is -0.11%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/JP_Y.png)

![CPI Inflation](charts/JP_pi_cpi.png)

![Equity Index](charts/JP_equity.png)

![Gold Price](charts/JP_P_gold.png)

![Metals Price](charts/JP_P_metals.png)

![Food Price](charts/JP_P_food.png)

![Copper Price](charts/JP_P_copper.png)

![Wheat Price](charts/JP_P_wheat.png)

![Energy Price](charts/JP_P_energy.png)

![VIX](charts/JP_vix.png)

![NEER](charts/JP_NEER.png)

![Gas Price](charts/JP_P_gas.png)

[Q1–Q20 JSON for Japan](numbers/JP.json)

## IT — Italy

The main impact of a 250bp rise in the risk premium on Italy would be a large drop in GDP of 0.87% by Q7. Equities peak at -25.05% in Q1.

Demand and trade. Consumption peaks at -0.45 % vs baseline in Q8, from -0.01 in Q1 to -0.05 in Q20. Investment peaks at -2.27 % vs baseline in Q6, from -0.07 in Q1 to -0.03 in Q20. Net Exports peaks at +0.28 % vs baseline in Q7, from +0.10 in Q1 to +0.00 in Q20. Gov Spending peaks at +0.19 % vs baseline in Q7, from +0.00 in Q1 to +0.01 in Q20. Gov Debt peaks at +0.08 % vs baseline in Q8, from +0.00 in Q1 to +0.01 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.73 % vs baseline in Q1, from +0.73 in Q1 to -0.18 in Q20.

Labour. Employment peaks at -0.70 % vs baseline in Q11, from +0.00 in Q1 to -0.35 in Q20. Unemployment peaks at +0.29 pp in Q10, from +0.00 in Q1 to +0.09 in Q20. Real Wages peaks at -0.65 % vs baseline in Q20, from +0.00 in Q1 to -0.65 in Q20.

Prices. The three-year CPI impulse is -0.48 percentage points. CPI Inflation peaks at -0.09 pp in Q7, from +0.09 in Q1 to +0.02 in Q20. Domestic Infl. peaks at -0.06 pp in Q7, from +0.06 in Q1 to +0.01 in Q20. Marginal Cost peaks at -0.52 % vs baseline in Q7, from -0.00 in Q1 to -0.03 in Q20.

Financial conditions. Policy Rate peaks at -0.24 pp (annualized) in Q11, from +0.04 in Q1 to -0.06 in Q20. Real Rate peaks at -0.06 pp (annualized) in Q11, from +0.01 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -0.24 pp (annualized) in Q11, from +0.04 in Q1 to -0.06 in Q20. Govt 2Y Yield peaks at -0.22 pp (annualized) in Q8, from -0.04 in Q1 to -0.01 in Q20. Govt 5Y Yield peaks at -0.13 pp (annualized) in Q4, from -0.12 in Q1 to +0.01 in Q20. Govt 10Y Yield peaks at -0.06 pp (annualized) in Q4, from -0.06 in Q1 to +0.00 in Q20. Govt 30Y Yield peaks at -0.02 pp (annualized) in Q5, from -0.02 in Q1 to +0.00 in Q20. Bond Price (7y) peaks at +1.70 % vs baseline in Q11, from -0.29 in Q1 to +0.43 in Q20. Bond Price 3M peaks at +0.06 % vs baseline in Q11, from -0.01 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +0.42 % vs baseline in Q8, from +0.09 in Q1 to +0.02 in Q20. Bond Price 5Y peaks at +0.60 % vs baseline in Q4, from +0.55 in Q1 to -0.03 in Q20. Bond Price 10Y peaks at +0.49 % vs baseline in Q4, from +0.47 in Q1 to -0.03 in Q20. Bond Price 30Y peaks at +0.35 % vs baseline in Q5, from +0.33 in Q1 to -0.03 in Q20. Equity Index peaks at -25.05 % vs baseline in Q1, from -25.05 in Q1 to -5.09 in Q20. VIX peaks at +42.54 index_level in Q1, from +42.54 in Q1 to +20.07 in Q20. Tobin's Q peaks at -1.59 % vs baseline in Q6, from -0.05 in Q1 to -0.02 in Q20. House Prices peaks at -0.62 % vs baseline in Q14, from -0.00 in Q1 to -0.52 in Q20. Bank Equity peaks at -0.33 % vs baseline in Q13, from +0.00 in Q1 to -0.26 in Q20. Bank Credit peaks at -0.27 % vs baseline in Q13, from +0.00 in Q1 to -0.21 in Q20. Credit Spread peaks at +0.00 pp in Q13, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.45 % vs baseline in Q9, from +0.02 in Q1 to +0.16 in Q20. vs USD peaks at +1.77 % vs baseline in Q1, from +1.77 in Q1 to +0.87 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.76 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.41 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.46 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.47 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.81 in Q20. Gold Price peaks at +3453.47 USD/oz (level) in Q1, from +3453.47 in Q1 to +2262.69 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.22 % vs baseline in Q1, from -0.22 in Q1 to +0.05 in Q20. Services GDP peaks at -0.63 % vs baseline in Q7, from -0.00 in Q1 to -0.04 in Q20. Capital Stock peaks at -0.10 % vs baseline in Q20, from -0.00 in Q1 to -0.10 in Q20.

Timing. The GDP response has mostly faded by Q16 (Q20 is -0.05%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/IT_Y.png)

![CPI Inflation](charts/IT_pi_cpi.png)

![Equity Index](charts/IT_equity.png)

![Gold Price](charts/IT_P_gold.png)

![Metals Price](charts/IT_P_metals.png)

![Food Price](charts/IT_P_food.png)

![Copper Price](charts/IT_P_copper.png)

![Wheat Price](charts/IT_P_wheat.png)

![Energy Price](charts/IT_P_energy.png)

![VIX](charts/IT_vix.png)

![Gas Price](charts/IT_P_gas.png)

![Investment](charts/IT_I.png)

[Q1–Q20 JSON for Italy](numbers/IT.json)


---

These figures are model IRFs versus baseline, not forecasts, and not financial advice.
