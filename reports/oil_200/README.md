# Global Macro Economic Simulations and Financial Market Responses

v6 · IRF · evaluation

**Open the typeset report (this is the document):** https://robomacro.com/GlobalMacroTrainingDataset/oil_200/

GitHub and Hugging Face show `.html` as source code. That is not the report. Read it on robomacro.com, or keep scrolling this page.

## What's the impact of Oil $200/bbl

### Active treatment

```json
{
  "oil": 200.0
}
```

### Assumptions

- Every path is a model impulse response versus baseline, not a forecast.
- The solver and weights are not included.
- English never enters the solver.

### Summary

This report traces the model response to oil at $200 a barrel. Every path is an impulse response versus an unchanged baseline — not a forecast and not market data. The question was: What's the impact of Oil $200/bbl

Turkey sees a -5.82% GDP peak at Q12, with CPI +2.14pp over three years and equities -9.67%. India sees a -5.39% GDP peak at Q12, with CPI +2.10pp over three years and equities -14.22%. South Korea sees a -5.32% GDP peak at Q11, with CPI +3.24pp over three years and equities -13.22%. Germany sees a -4.68% GDP peak at Q13, with CPI +3.22pp over three years and equities -9.06%.

The remaining countries are smaller spillovers and are covered in the chapters that follow. This material is a model-based summary and is not financial advice.

### Countries by GDP impact

- [TR — Turkey](#tr--turkey) · GDP -5.82% Q12
- [IN — India](#in--india) · GDP -5.39% Q12
- [KR — South Korea](#kr--south-korea) · GDP -5.32% Q11
- [DE — Germany](#de--germany) · GDP -4.68% Q13
- [JP — Japan](#jp--japan) · GDP -4.67% Q11
- [IT — Italy](#it--italy) · GDP -4.34% Q13
- [PL — Poland](#pl--poland) · GDP -4.22% Q14
- [ES — Spain](#es--spain) · GDP -4.08% Q13
- [TH — Thailand](#th--thailand) · GDP -4.05% Q13
- [FR — France](#fr--france) · GDP -3.94% Q15
- [RU — Russia](#ru--russia) · GDP +3.83% Q1
- [SA — Saudi Arabia](#sa--saudi-arabia) · GDP +3.82% Q1
- [NO — Norway](#no--norway) · GDP +3.78% Q1
- [AR — Argentina](#ar--argentina) · GDP -3.72% Q13
- [ZA — South Africa](#za--south-africa) · GDP -3.69% Q15
- [CN — China](#cn--china) · GDP -3.37% Q13
- [CL — Chile](#cl--chile) · GDP -3.29% Q15
- [SE — Sweden](#se--sweden) · GDP -2.97% Q17
- [ID — Indonesia](#id--indonesia) · GDP -2.80% Q14
- [NG — Nigeria](#ng--nigeria) · GDP +2.63% Q3
- [CH — Switzerland](#ch--switzerland) · GDP -2.62% Q15
- [UK — United Kingdom](#uk--united-kingdom) · GDP -2.37% Q13
- [NL — Netherlands](#nl--netherlands) · GDP -2.30% Q15
- [BR — Brazil](#br--brazil) · GDP -2.16% Q14
- [AU — Australia](#au--australia) · GDP -1.91% Q13
- [US — United States](#us--united-states) · GDP -1.71% Q12
- [CA — Canada](#ca--canada) · GDP +1.56% Q3
- [MX — Mexico](#mx--mexico) · GDP -1.52% Q12
- [MY — Malaysia](#my--malaysia) · GDP -1.12% Q12
- [CO — Colombia](#co--colombia) · GDP -1.05% Q13

![TR GDP](charts/global_TR_Y.png)

![IN GDP](charts/global_IN_Y.png)

![KR GDP](charts/global_KR_Y.png)

![DE GDP](charts/global_DE_Y.png)

![US Equity Index](charts/global_US_equity.png)

![US Policy Rate](charts/global_US_i.png)

## TR — Turkey

The main impact of oil at $200 a barrel on Turkey would be a large drop in GDP of 5.82% by Q12. Equities peak at -9.67% in Q11.

Demand and trade. Consumption peaks at -3.37 % vs baseline in Q12, from -1.05 in Q1 to -1.87 in Q20. Investment peaks at -15.18 % vs baseline in Q9, from -6.96 in Q1 to -3.64 in Q20. Net Exports peaks at -4.45 % vs baseline in Q3, from -2.87 in Q1 to -1.40 in Q20. Gov Spending peaks at +1.01 % vs baseline in Q12, from +0.36 in Q1 to +0.49 in Q20. Gov Debt peaks at -6.40 % vs baseline in Q20, from -0.20 in Q1 to -6.40 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +7.42 % vs baseline in Q12, from +1.82 in Q1 to +4.92 in Q20.

Labour. Employment peaks at -5.56 % vs baseline in Q16, from -0.33 in Q1 to -5.11 in Q20. Unemployment peaks at +1.33 pp in Q14, from +0.14 in Q1 to +0.95 in Q20. Real Wages peaks at -9.65 % vs baseline in Q20, from -0.04 in Q1 to -9.65 in Q20.

Prices. The three-year CPI impulse is +2.14 percentage points. CPI Inflation peaks at +0.55 pp in Q3, from +0.34 in Q1 to -0.52 in Q20. Domestic Infl. peaks at +0.38 pp in Q3, from +0.24 in Q1 to -0.36 in Q20. Marginal Cost peaks at -3.45 % vs baseline in Q12, from -1.22 in Q1 to -1.68 in Q20.

Financial conditions. Policy Rate peaks at -2.59 pp (annualized) in Q18, from +0.84 in Q1 to -2.53 in Q20. Real Rate peaks at -0.65 pp (annualized) in Q18, from +0.21 in Q1 to -0.63 in Q20. Govt 3M Yield peaks at -2.59 pp (annualized) in Q18, from +0.84 in Q1 to -2.53 in Q20. Govt 2Y Yield peaks at -2.49 pp (annualized) in Q15, from +1.59 in Q1 to -2.18 in Q20. Govt 5Y Yield peaks at -2.06 pp (annualized) in Q12, from -0.45 in Q1 to -1.49 in Q20. Govt 10Y Yield peaks at -1.32 pp (annualized) in Q10, from -0.92 in Q1 to -0.89 in Q20. Govt 30Y Yield peaks at -0.51 pp (annualized) in Q10, from -0.40 in Q1 to -0.35 in Q20. Bond Price (7y) peaks at +8.08 % vs baseline in Q18, from -2.62 in Q1 to +7.92 in Q20. Bond Price 3M peaks at +0.65 % vs baseline in Q18, from -0.21 in Q1 to +0.63 in Q20. Bond Price 2Y peaks at +4.72 % vs baseline in Q15, from -3.02 in Q1 to +4.14 in Q20. Bond Price 5Y peaks at +9.25 % vs baseline in Q12, from +2.00 in Q1 to +6.73 in Q20. Bond Price 10Y peaks at +10.82 % vs baseline in Q10, from +7.54 in Q1 to +7.31 in Q20. Bond Price 30Y peaks at +9.21 % vs baseline in Q10, from +7.23 in Q1 to +6.36 in Q20. Equity Index peaks at -9.67 % vs baseline in Q11, from -3.88 in Q1 to -3.09 in Q20. VIX peaks at +23.07 index_level in Q6, from +19.31 in Q1 to +18.76 in Q20. Tobin's Q peaks at -10.63 % vs baseline in Q9, from -4.87 in Q1 to -2.55 in Q20. House Prices peaks at -7.42 % vs baseline in Q18, from -0.34 in Q1 to -7.25 in Q20. Bank Equity peaks at -0.98 % vs baseline in Q17, from -0.08 in Q1 to -0.96 in Q20. Bank Credit peaks at -0.86 % vs baseline in Q17, from -0.07 in Q1 to -0.84 in Q20. Credit Spread peaks at +0.07 pp in Q17, from +0.01 in Q1 to +0.07 in Q20.

Nominal FX. NEER peaks at -8.15 % vs baseline in Q12, from -2.19 in Q1 to -5.88 in Q20. vs USD peaks at +7.49 % vs baseline in Q10, from +2.14 in Q1 to +4.56 in Q20.

Commodities. Energy Price peaks at +176.36 USD/bbl (level) in Q4, from +138.90 in Q1 to +122.38 in Q20. Metals Price peaks at +98.20 index (level) in Q1, from +98.20 in Q1 to +93.22 in Q20. Food Price peaks at +112.54 index (level) in Q8, from +101.83 in Q1 to +107.12 in Q20. Gas Price peaks at +7.04 USD/mmBtu (level) in Q4, from +5.91 in Q1 to +5.22 in Q20. Copper Price peaks at +98.42 index (level) in Q1, from +98.42 in Q1 to +94.50 in Q20. Wheat Price peaks at +99.21 index (level) in Q1, from +99.21 in Q1 to +96.05 in Q20. Gold Price peaks at +2444.29 USD/oz (level) in Q8, from +2250.80 in Q1 to +2287.25 in Q20.

Sectoral and capital. Manuf. GDP peaks at -5.78 % vs baseline in Q10, from -2.78 in Q1 to -3.46 in Q20. Services GDP peaks at -3.52 % vs baseline in Q12, from -1.27 in Q1 to -1.72 in Q20. Capital Stock peaks at -1.13 % vs baseline in Q20, from -0.03 in Q1 to -1.13 in Q20.

Timing. By Q20 GDP is still -2.85% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/TR_Y.png)

![CPI Inflation](charts/TR_pi_cpi.png)

![Equity Index](charts/TR_equity.png)

![Gold Price](charts/TR_P_gold.png)

![Energy Price](charts/TR_P_energy.png)

![Food Price](charts/TR_P_food.png)

![Wheat Price](charts/TR_P_wheat.png)

![Copper Price](charts/TR_P_copper.png)

![Metals Price](charts/TR_P_metals.png)

![VIX](charts/TR_vix.png)

![Investment](charts/TR_I.png)

![Bond Price 10Y](charts/TR_Q_B_10y.png)

[Q1–Q20 JSON for Turkey](numbers/TR.json)

## IN — India

The main impact of oil at $200 a barrel on India would be a large drop in GDP of 5.39% by Q12. Equities peak at -14.22% in Q11.

Demand and trade. Consumption peaks at -3.26 % vs baseline in Q12, from -1.10 in Q1 to -2.14 in Q20. Investment peaks at -14.95 % vs baseline in Q8, from -6.92 in Q1 to -4.21 in Q20. Net Exports peaks at -4.64 % vs baseline in Q4, from -2.95 in Q1 to -1.46 in Q20. Gov Spending peaks at +0.90 % vs baseline in Q12, from +0.36 in Q1 to +0.54 in Q20. Gov Debt peaks at -10.04 % vs baseline in Q20, from -0.31 in Q1 to -10.04 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +5.76 % vs baseline in Q15, from +0.84 in Q1 to +5.28 in Q20.

Labour. Employment peaks at -4.68 % vs baseline in Q18, from -0.24 in Q1 to -4.64 in Q20. Unemployment peaks at +0.38 pp in Q13, from +0.06 in Q1 to +0.27 in Q20. Real Wages peaks at -7.90 % vs baseline in Q20, from -0.04 in Q1 to -7.90 in Q20.

Prices. The three-year CPI impulse is +2.10 percentage points. CPI Inflation peaks at +0.58 pp in Q3, from +0.38 in Q1 to -0.51 in Q20. Domestic Infl. peaks at +0.41 pp in Q3, from +0.26 in Q1 to -0.36 in Q20. Marginal Cost peaks at -3.19 % vs baseline in Q12, from -1.27 in Q1 to -1.91 in Q20.

Financial conditions. Policy Rate peaks at -2.91 pp (annualized) in Q20, from +0.68 in Q1 to -2.91 in Q20. Real Rate peaks at -0.73 pp (annualized) in Q20, from +0.17 in Q1 to -0.73 in Q20. Govt 3M Yield peaks at -2.91 pp (annualized) in Q20, from +0.68 in Q1 to -2.91 in Q20. Govt 2Y Yield peaks at -2.84 pp (annualized) in Q18, from +1.74 in Q1 to -2.77 in Q20. Govt 5Y Yield peaks at -2.48 pp (annualized) in Q14, from -0.26 in Q1 to -2.20 in Q20. Govt 10Y Yield peaks at -1.79 pp (annualized) in Q12, from -1.19 in Q1 to -1.46 in Q20. Govt 30Y Yield peaks at -0.71 pp (annualized) in Q11, from -0.58 in Q1 to -0.57 in Q20. Bond Price (7y) peaks at +14.56 % vs baseline in Q20, from -3.38 in Q1 to +14.56 in Q20. Bond Price 3M peaks at +0.73 % vs baseline in Q20, from -0.17 in Q1 to +0.73 in Q20. Bond Price 2Y peaks at +5.39 % vs baseline in Q18, from -3.31 in Q1 to +5.27 in Q20. Bond Price 5Y peaks at +11.18 % vs baseline in Q14, from +1.19 in Q1 to +9.92 in Q20. Bond Price 10Y peaks at +14.69 % vs baseline in Q12, from +9.77 in Q1 to +11.96 in Q20. Bond Price 30Y peaks at +12.81 % vs baseline in Q11, from +10.49 in Q1 to +10.25 in Q20. Equity Index peaks at -14.22 % vs baseline in Q11, from -5.99 in Q1 to -7.38 in Q20. VIX peaks at +23.07 index_level in Q6, from +19.31 in Q1 to +18.76 in Q20. Tobin's Q peaks at -10.47 % vs baseline in Q8, from -4.85 in Q1 to -2.95 in Q20. House Prices peaks at -6.97 % vs baseline in Q18, from -0.34 in Q1 to -6.89 in Q20. Bank Equity peaks at -1.13 % vs baseline in Q16, from -0.10 in Q1 to -1.10 in Q20. Bank Credit peaks at -0.99 % vs baseline in Q16, from -0.08 in Q1 to -0.96 in Q20. Credit Spread peaks at +0.03 pp in Q16, from +0.00 in Q1 to +0.03 in Q20.

Nominal FX. NEER peaks at -7.31 % vs baseline in Q14, from -2.16 in Q1 to -6.70 in Q20. vs USD peaks at +5.43 % vs baseline in Q14, from +1.16 in Q1 to +4.92 in Q20.

Commodities. Energy Price peaks at +176.36 USD/bbl (level) in Q4, from +138.90 in Q1 to +122.38 in Q20. Metals Price peaks at +98.20 index (level) in Q1, from +98.20 in Q1 to +93.22 in Q20. Food Price peaks at +112.54 index (level) in Q8, from +101.83 in Q1 to +107.12 in Q20. Gas Price peaks at +7.04 USD/mmBtu (level) in Q4, from +5.91 in Q1 to +5.22 in Q20. Copper Price peaks at +98.42 index (level) in Q1, from +98.42 in Q1 to +94.50 in Q20. Wheat Price peaks at +99.21 index (level) in Q1, from +99.21 in Q1 to +96.05 in Q20. Gold Price peaks at +2444.29 USD/oz (level) in Q8, from +2250.80 in Q1 to +2287.25 in Q20.

Sectoral and capital. Manuf. GDP peaks at -4.61 % vs baseline in Q11, from -2.27 in Q1 to -3.45 in Q20. Services GDP peaks at -2.96 % vs baseline in Q12, from -1.20 in Q1 to -1.77 in Q20. Capital Stock peaks at -1.13 % vs baseline in Q20, from -0.03 in Q1 to -1.13 in Q20.

Timing. By Q20 GDP is still -3.22% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/IN_Y.png)

![CPI Inflation](charts/IN_pi_cpi.png)

![Equity Index](charts/IN_equity.png)

![Gold Price](charts/IN_P_gold.png)

![Energy Price](charts/IN_P_energy.png)

![Food Price](charts/IN_P_food.png)

![Wheat Price](charts/IN_P_wheat.png)

![Copper Price](charts/IN_P_copper.png)

![Metals Price](charts/IN_P_metals.png)

![VIX](charts/IN_vix.png)

![Investment](charts/IN_I.png)

![Bond Price 10Y](charts/IN_Q_B_10y.png)

[Q1–Q20 JSON for India](numbers/IN.json)

## KR — South Korea

The main impact of oil at $200 a barrel on South Korea would be a large drop in GDP of 5.32% by Q11. Equities peak at -13.22% in Q10.

Demand and trade. Consumption peaks at -3.33 % vs baseline in Q11, from -1.30 in Q1 to -2.30 in Q20. Investment peaks at -14.33 % vs baseline in Q9, from -7.57 in Q1 to -5.78 in Q20. Net Exports peaks at -5.47 % vs baseline in Q4, from -3.38 in Q1 to -1.49 in Q20. Gov Spending peaks at +0.95 % vs baseline in Q11, from +0.44 in Q1 to +0.62 in Q20. Gov Debt peaks at -3.75 % vs baseline in Q20, from -0.16 in Q1 to -3.75 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +9.72 % vs baseline in Q5, from +5.82 in Q1 to +7.64 in Q20.

Labour. Employment peaks at -5.08 % vs baseline in Q15, from -0.47 in Q1 to -4.64 in Q20. Unemployment peaks at +2.05 pp in Q13, from +0.25 in Q1 to +1.71 in Q20. Real Wages peaks at -6.21 % vs baseline in Q20, from -0.03 in Q1 to -6.21 in Q20.

Prices. The three-year CPI impulse is +3.24 percentage points. CPI Inflation peaks at +0.65 pp in Q2, from +0.52 in Q1 to -0.23 in Q20. Domestic Infl. peaks at +0.45 pp in Q2, from +0.36 in Q1 to -0.16 in Q20. Marginal Cost peaks at -3.15 % vs baseline in Q11, from -1.47 in Q1 to -2.04 in Q20.

Financial conditions. Policy Rate peaks at -2.34 pp (annualized) in Q20, from +0.48 in Q1 to -2.34 in Q20. Real Rate peaks at -0.58 pp (annualized) in Q20, from +0.12 in Q1 to -0.58 in Q20. Govt 3M Yield peaks at -2.34 pp (annualized) in Q20, from +0.48 in Q1 to -2.34 in Q20. Govt 2Y Yield peaks at -2.29 pp (annualized) in Q18, from +0.96 in Q1 to -2.25 in Q20. Govt 5Y Yield peaks at -2.08 pp (annualized) in Q14, from -0.53 in Q1 to -1.90 in Q20. Govt 10Y Yield peaks at -1.63 pp (annualized) in Q12, from -1.19 in Q1 to -1.40 in Q20. Govt 30Y Yield peaks at -0.72 pp (annualized) in Q10, from -0.65 in Q1 to -0.59 in Q20. Bond Price (7y) peaks at +11.70 % vs baseline in Q20, from -2.42 in Q1 to +11.70 in Q20. Bond Price 3M peaks at +0.58 % vs baseline in Q20, from -0.12 in Q1 to +0.58 in Q20. Bond Price 2Y peaks at +4.36 % vs baseline in Q18, from -1.83 in Q1 to +4.28 in Q20. Bond Price 5Y peaks at +9.35 % vs baseline in Q14, from +2.39 in Q1 to +8.56 in Q20. Bond Price 10Y peaks at +13.39 % vs baseline in Q12, from +9.76 in Q1 to +11.46 in Q20. Bond Price 30Y peaks at +13.01 % vs baseline in Q10, from +11.77 in Q1 to +10.67 in Q20. Equity Index peaks at -13.22 % vs baseline in Q10, from -6.40 in Q1 to -7.28 in Q20. VIX peaks at +23.07 index_level in Q6, from +19.31 in Q1 to +18.76 in Q20. Tobin's Q peaks at -10.03 % vs baseline in Q9, from -5.30 in Q1 to -4.05 in Q20. House Prices peaks at -6.37 % vs baseline in Q20, from -0.30 in Q1 to -6.37 in Q20. Bank Equity peaks at -1.70 % vs baseline in Q16, from -0.14 in Q1 to -1.66 in Q20. Bank Credit peaks at -1.35 % vs baseline in Q16, from -0.11 in Q1 to -1.32 in Q20. Credit Spread peaks at +0.02 pp in Q16, from +0.00 in Q1 to +0.02 in Q20.

Nominal FX. NEER peaks at -9.34 % vs baseline in Q5, from -5.57 in Q1 to -7.79 in Q20. vs USD peaks at +10.55 % vs baseline in Q5, from +6.14 in Q1 to +7.28 in Q20.

Commodities. Energy Price peaks at +176.36 USD/bbl (level) in Q4, from +138.90 in Q1 to +122.38 in Q20. Metals Price peaks at +98.20 index (level) in Q1, from +98.20 in Q1 to +93.22 in Q20. Food Price peaks at +112.54 index (level) in Q8, from +101.83 in Q1 to +107.12 in Q20. Gas Price peaks at +7.04 USD/mmBtu (level) in Q4, from +5.91 in Q1 to +5.22 in Q20. Copper Price peaks at +98.42 index (level) in Q1, from +98.42 in Q1 to +94.50 in Q20. Wheat Price peaks at +99.21 index (level) in Q1, from +99.21 in Q1 to +96.05 in Q20. Gold Price peaks at +2444.29 USD/oz (level) in Q8, from +2250.80 in Q1 to +2287.25 in Q20.

Sectoral and capital. Manuf. GDP peaks at -7.51 % vs baseline in Q4, from -4.52 in Q1 to -4.83 in Q20. Services GDP peaks at -3.22 % vs baseline in Q11, from -1.52 in Q1 to -2.08 in Q20. Capital Stock peaks at -1.13 % vs baseline in Q20, from -0.04 in Q1 to -1.13 in Q20.

Timing. By Q20 GDP is still -3.44% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/KR_Y.png)

![CPI Inflation](charts/KR_pi_cpi.png)

![Equity Index](charts/KR_equity.png)

![Gold Price](charts/KR_P_gold.png)

![Energy Price](charts/KR_P_energy.png)

![Food Price](charts/KR_P_food.png)

![Wheat Price](charts/KR_P_wheat.png)

![Copper Price](charts/KR_P_copper.png)

![Metals Price](charts/KR_P_metals.png)

![VIX](charts/KR_vix.png)

![Investment](charts/KR_I.png)

![Bond Price 10Y](charts/KR_Q_B_10y.png)

[Q1–Q20 JSON for South Korea](numbers/KR.json)

## DE — Germany

The main impact of oil at $200 a barrel on Germany would be a large drop in GDP of 4.68% by Q13. Equities peak at -9.06% in Q12.

Demand and trade. Consumption peaks at -2.64 % vs baseline in Q13, from -0.88 in Q1 to -2.08 in Q20. Investment peaks at -13.76 % vs baseline in Q12, from -5.67 in Q1 to -8.28 in Q20. Net Exports peaks at -3.18 % vs baseline in Q4, from -1.97 in Q1 to -1.27 in Q20. Gov Spending peaks at +1.04 % vs baseline in Q13, from +0.40 in Q1 to +0.78 in Q20. Gov Debt peaks at +0.87 % vs baseline in Q20, from +0.03 in Q1 to +0.87 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +6.03 % vs baseline in Q4, from +3.75 in Q1 to +1.75 in Q20.

Labour. Employment peaks at -4.58 % vs baseline in Q17, from -0.35 in Q1 to -4.42 in Q20. Unemployment peaks at +3.23 pp in Q16, from +0.29 in Q1 to +3.03 in Q20. Real Wages peaks at -3.43 % vs baseline in Q20, from -0.01 in Q1 to -3.43 in Q20.

Prices. The three-year CPI impulse is +3.22 percentage points. CPI Inflation peaks at +0.86 pp in Q2, from +0.69 in Q1 to -0.31 in Q20. Domestic Infl. peaks at +0.60 pp in Q2, from +0.48 in Q1 to -0.22 in Q20. Marginal Cost peaks at -2.77 % vs baseline in Q13, from -1.07 in Q1 to -2.09 in Q20.

Financial conditions. Policy Rate peaks at +1.72 pp (annualized) in Q6, from +0.43 in Q1 to -0.88 in Q20. Real Rate peaks at +0.43 pp (annualized) in Q6, from +0.11 in Q1 to -0.22 in Q20. Govt 3M Yield peaks at +1.72 pp (annualized) in Q6, from +0.43 in Q1 to -0.88 in Q20. Govt 2Y Yield peaks at +1.46 pp (annualized) in Q3, from +1.35 in Q1 to -1.02 in Q20. Govt 5Y Yield peaks at -0.97 pp (annualized) in Q19, from +0.55 in Q1 to -0.97 in Q20. Govt 10Y Yield peaks at -0.77 pp (annualized) in Q16, from -0.21 in Q1 to -0.75 in Q20. Govt 30Y Yield peaks at -0.34 pp (annualized) in Q15, from -0.22 in Q1 to -0.32 in Q20. Bond Price (7y) peaks at -12.07 % vs baseline in Q6, from -3.04 in Q1 to +6.13 in Q20. Bond Price 3M peaks at -0.43 % vs baseline in Q6, from -0.11 in Q1 to +0.22 in Q20. Bond Price 2Y peaks at -2.78 % vs baseline in Q3, from -2.57 in Q1 to +1.93 in Q20. Bond Price 5Y peaks at +4.36 % vs baseline in Q19, from -2.46 in Q1 to +4.36 in Q20. Bond Price 10Y peaks at +6.33 % vs baseline in Q16, from +1.70 in Q1 to +6.14 in Q20. Bond Price 30Y peaks at +6.13 % vs baseline in Q15, from +3.90 in Q1 to +5.75 in Q20. Equity Index peaks at -9.06 % vs baseline in Q12, from -3.76 in Q1 to -6.25 in Q20. VIX peaks at +23.07 index_level in Q6, from +19.31 in Q1 to +18.76 in Q20. Tobin's Q peaks at -9.63 % vs baseline in Q12, from -3.97 in Q1 to -5.80 in Q20. House Prices peaks at -5.96 % vs baseline in Q20, from -0.22 in Q1 to -5.96 in Q20. Bank Equity peaks at -1.94 % vs baseline in Q17, from -0.13 in Q1 to -1.91 in Q20. Bank Credit peaks at -1.57 % vs baseline in Q17, from -0.11 in Q1 to -1.54 in Q20. Credit Spread peaks at +0.02 pp in Q17, from +0.00 in Q1 to +0.02 in Q20.

Nominal FX. NEER peaks at -4.41 % vs baseline in Q4, from -2.73 in Q1 to -1.58 in Q20. vs USD peaks at +6.84 % vs baseline in Q4, from +4.07 in Q1 to +1.39 in Q20.

Commodities. Energy Price peaks at +176.36 USD/bbl (level) in Q4, from +138.90 in Q1 to +122.38 in Q20. Metals Price peaks at +98.20 index (level) in Q1, from +98.20 in Q1 to +93.22 in Q20. Food Price peaks at +112.54 index (level) in Q8, from +101.83 in Q1 to +107.12 in Q20. Gas Price peaks at +7.04 USD/mmBtu (level) in Q4, from +5.91 in Q1 to +5.22 in Q20. Copper Price peaks at +98.42 index (level) in Q1, from +98.42 in Q1 to +94.50 in Q20. Wheat Price peaks at +99.21 index (level) in Q1, from +99.21 in Q1 to +96.05 in Q20. Gold Price peaks at +2444.29 USD/oz (level) in Q8, from +2250.80 in Q1 to +2287.25 in Q20.

Sectoral and capital. Manuf. GDP peaks at -5.31 % vs baseline in Q4, from -3.21 in Q1 to -2.62 in Q20. Services GDP peaks at -3.19 % vs baseline in Q13, from -1.26 in Q1 to -2.40 in Q20. Capital Stock peaks at -1.14 % vs baseline in Q20, from -0.03 in Q1 to -1.14 in Q20.

Timing. By Q20 GDP is still -3.52% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/DE_Y.png)

![CPI Inflation](charts/DE_pi_cpi.png)

![Equity Index](charts/DE_equity.png)

![Gold Price](charts/DE_P_gold.png)

![Energy Price](charts/DE_P_energy.png)

![Food Price](charts/DE_P_food.png)

![Wheat Price](charts/DE_P_wheat.png)

![Copper Price](charts/DE_P_copper.png)

![Metals Price](charts/DE_P_metals.png)

![VIX](charts/DE_vix.png)

![Investment](charts/DE_I.png)

![Bond Price (7y)](charts/DE_Q_B.png)

[Q1–Q20 JSON for Germany](numbers/DE.json)

## JP — Japan

The main impact of oil at $200 a barrel on Japan would be a large drop in GDP of 4.67% by Q11. Equities peak at -12.83% in Q11.

Demand and trade. Consumption peaks at -3.12 % vs baseline in Q11, from -1.17 in Q1 to -2.39 in Q20. Investment peaks at -13.39 % vs baseline in Q11, from -6.13 in Q1 to -9.28 in Q20. Net Exports peaks at -4.53 % vs baseline in Q4, from -2.79 in Q1 to -2.57 in Q20. Gov Spending peaks at +0.92 % vs baseline in Q11, from +0.43 in Q1 to +0.68 in Q20. Gov Debt peaks at -1.78 % vs baseline in Q20, from -0.05 in Q1 to -1.78 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +10.52 % vs baseline in Q4, from +6.17 in Q1 to -3.47 in Q20.

Labour. Employment peaks at -4.74 % vs baseline in Q14, from -0.54 in Q1 to -4.33 in Q20. Unemployment peaks at +3.22 pp in Q14, from +0.34 in Q1 to +2.96 in Q20. Real Wages peaks at +1.18 % vs baseline in Q11, from -0.00 in Q1 to -0.11 in Q20.

Prices. The three-year CPI impulse is +2.11 percentage points. CPI Inflation peaks at +0.64 pp in Q2, from +0.48 in Q1 to -0.27 in Q20. Domestic Infl. peaks at +0.45 pp in Q2, from +0.34 in Q1 to -0.19 in Q20. Marginal Cost peaks at -2.76 % vs baseline in Q11, from -1.29 in Q1 to -2.04 in Q20.

Financial conditions. Policy Rate peaks at +0.36 pp (annualized) in Q7, from +0.06 in Q1 to -0.09 in Q20. Real Rate peaks at +0.09 pp (annualized) in Q7, from +0.02 in Q1 to -0.02 in Q20. Govt 3M Yield peaks at +0.36 pp (annualized) in Q7, from +0.06 in Q1 to -0.09 in Q20. Govt 2Y Yield peaks at +0.32 pp (annualized) in Q4, from +0.26 in Q1 to -0.17 in Q20. Govt 5Y Yield peaks at -0.22 pp (annualized) in Q20, from +0.18 in Q1 to -0.22 in Q20. Govt 10Y Yield peaks at -0.24 pp (annualized) in Q20, from -0.03 in Q1 to -0.24 in Q20. Govt 30Y Yield peaks at -0.16 pp (annualized) in Q19, from -0.12 in Q1 to -0.16 in Q20. Bond Price (7y) peaks at +3.65 % vs baseline in Q20, from -0.89 in Q1 to +3.65 in Q20. Bond Price 3M peaks at -0.09 % vs baseline in Q7, from -0.02 in Q1 to +0.02 in Q20. Bond Price 2Y peaks at -0.61 % vs baseline in Q4, from -0.50 in Q1 to +0.32 in Q20. Bond Price 5Y peaks at +1.00 % vs baseline in Q20, from -0.80 in Q1 to +1.00 in Q20. Bond Price 10Y peaks at +1.95 % vs baseline in Q20, from +0.23 in Q1 to +1.95 in Q20. Bond Price 30Y peaks at +2.85 % vs baseline in Q19, from +2.15 in Q1 to +2.84 in Q20. Equity Index peaks at -12.83 % vs baseline in Q11, from -6.18 in Q1 to -8.96 in Q20. VIX peaks at +23.07 index_level in Q6, from +19.31 in Q1 to +18.76 in Q20. Tobin's Q peaks at -9.37 % vs baseline in Q11, from -4.29 in Q1 to -6.50 in Q20. House Prices peaks at -5.51 % vs baseline in Q20, from -0.24 in Q1 to -5.51 in Q20. Bank Equity peaks at -2.05 % vs baseline in Q16, from -0.16 in Q1 to -1.98 in Q20. Bank Credit peaks at -1.61 % vs baseline in Q16, from -0.13 in Q1 to -1.55 in Q20. Credit Spread peaks at +0.01 pp in Q16, from +0.00 in Q1 to +0.01 in Q20.

Nominal FX. NEER peaks at -10.58 % vs baseline in Q4, from -6.16 in Q1 to +4.25 in Q20. vs USD peaks at +11.33 % vs baseline in Q4, from +6.48 in Q1 to -3.84 in Q20.

Commodities. Energy Price peaks at +176.36 USD/bbl (level) in Q4, from +138.90 in Q1 to +122.38 in Q20. Metals Price peaks at +98.20 index (level) in Q1, from +98.20 in Q1 to +93.22 in Q20. Food Price peaks at +112.54 index (level) in Q8, from +101.83 in Q1 to +107.12 in Q20. Gas Price peaks at +7.04 USD/mmBtu (level) in Q4, from +5.91 in Q1 to +5.22 in Q20. Copper Price peaks at +98.42 index (level) in Q1, from +98.42 in Q1 to +94.50 in Q20. Wheat Price peaks at +99.21 index (level) in Q1, from +99.21 in Q1 to +96.05 in Q20. Gold Price peaks at +2444.29 USD/oz (level) in Q8, from +2250.80 in Q1 to +2287.25 in Q20.

Sectoral and capital. Manuf. GDP peaks at -6.80 % vs baseline in Q4, from -4.04 in Q1 to -1.03 in Q20. Services GDP peaks at -3.24 % vs baseline in Q11, from -1.54 in Q1 to -2.39 in Q20. Capital Stock peaks at -1.12 % vs baseline in Q20, from -0.03 in Q1 to -1.12 in Q20.

Timing. By Q20 GDP is still -3.45% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/JP_Y.png)

![CPI Inflation](charts/JP_pi_cpi.png)

![Equity Index](charts/JP_equity.png)

![Gold Price](charts/JP_P_gold.png)

![Energy Price](charts/JP_P_energy.png)

![Food Price](charts/JP_P_food.png)

![Wheat Price](charts/JP_P_wheat.png)

![Copper Price](charts/JP_P_copper.png)

![Metals Price](charts/JP_P_metals.png)

![VIX](charts/JP_vix.png)

![Investment](charts/JP_I.png)

![vs USD](charts/JP_USD.png)

[Q1–Q20 JSON for Japan](numbers/JP.json)

## IT — Italy

The main impact of oil at $200 a barrel on Italy would be a large drop in GDP of 4.34% by Q13. Equities peak at -7.37% in Q12.

Demand and trade. Consumption peaks at -2.26 % vs baseline in Q13, from -0.87 in Q1 to -1.83 in Q20. Investment peaks at -12.70 % vs baseline in Q10, from -5.87 in Q1 to -7.75 in Q20. Net Exports peaks at -3.32 % vs baseline in Q4, from -2.04 in Q1 to -1.39 in Q20. Gov Spending peaks at +0.93 % vs baseline in Q13, from +0.41 in Q1 to +0.72 in Q20. Gov Debt peaks at +0.42 % vs baseline in Q13, from +0.09 in Q1 to +0.35 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +7.17 % vs baseline in Q4, from +4.43 in Q1 to +2.20 in Q20.

Labour. Employment peaks at -4.49 % vs baseline in Q18, from -0.35 in Q1 to -4.42 in Q20. Unemployment peaks at +1.76 pp in Q15, from +0.20 in Q1 to +1.62 in Q20. Real Wages peaks at -1.30 % vs baseline in Q20, from -0.01 in Q1 to -1.30 in Q20.

Prices. The three-year CPI impulse is +3.14 percentage points. CPI Inflation peaks at +0.73 pp in Q2, from +0.57 in Q1 to -0.26 in Q20. Domestic Infl. peaks at +0.51 pp in Q2, from +0.40 in Q1 to -0.18 in Q20. Marginal Cost peaks at -2.56 % vs baseline in Q13, from -1.12 in Q1 to -1.97 in Q20.

Financial conditions. Policy Rate peaks at +1.72 pp (annualized) in Q6, from +0.43 in Q1 to -0.88 in Q20. Real Rate peaks at +0.43 pp (annualized) in Q6, from +0.11 in Q1 to -0.22 in Q20. Govt 3M Yield peaks at +1.72 pp (annualized) in Q6, from +0.43 in Q1 to -0.88 in Q20. Govt 2Y Yield peaks at +1.46 pp (annualized) in Q3, from +1.35 in Q1 to -1.02 in Q20. Govt 5Y Yield peaks at -0.97 pp (annualized) in Q19, from +0.55 in Q1 to -0.97 in Q20. Govt 10Y Yield peaks at -0.77 pp (annualized) in Q16, from -0.21 in Q1 to -0.75 in Q20. Govt 30Y Yield peaks at -0.34 pp (annualized) in Q15, from -0.22 in Q1 to -0.32 in Q20. Bond Price (7y) peaks at -11.98 % vs baseline in Q6, from -3.01 in Q1 to +6.08 in Q20. Bond Price 3M peaks at -0.43 % vs baseline in Q6, from -0.11 in Q1 to +0.22 in Q20. Bond Price 2Y peaks at -2.78 % vs baseline in Q3, from -2.57 in Q1 to +1.93 in Q20. Bond Price 5Y peaks at +4.36 % vs baseline in Q19, from -2.46 in Q1 to +4.36 in Q20. Bond Price 10Y peaks at +6.33 % vs baseline in Q16, from +1.70 in Q1 to +6.14 in Q20. Bond Price 30Y peaks at +6.13 % vs baseline in Q15, from +3.90 in Q1 to +5.75 in Q20. Equity Index peaks at -7.37 % vs baseline in Q12, from -3.59 in Q1 to -4.96 in Q20. VIX peaks at +23.07 index_level in Q6, from +19.31 in Q1 to +18.76 in Q20. Tobin's Q peaks at -8.89 % vs baseline in Q10, from -4.11 in Q1 to -5.43 in Q20. House Prices peaks at -5.36 % vs baseline in Q20, from -0.22 in Q1 to -5.36 in Q20. Bank Equity peaks at -1.53 % vs baseline in Q17, from -0.12 in Q1 to -1.50 in Q20. Bank Credit peaks at -1.28 % vs baseline in Q17, from -0.10 in Q1 to -1.25 in Q20. Credit Spread peaks at +0.02 pp in Q17, from +0.00 in Q1 to +0.02 in Q20.

Nominal FX. NEER peaks at -4.73 % vs baseline in Q4, from -2.92 in Q1 to -1.50 in Q20. vs USD peaks at +7.97 % vs baseline in Q4, from +4.75 in Q1 to +1.84 in Q20.

Commodities. Energy Price peaks at +176.36 USD/bbl (level) in Q4, from +138.90 in Q1 to +122.38 in Q20. Metals Price peaks at +98.20 index (level) in Q1, from +98.20 in Q1 to +93.22 in Q20. Food Price peaks at +112.54 index (level) in Q8, from +101.83 in Q1 to +107.12 in Q20. Gas Price peaks at +7.04 USD/mmBtu (level) in Q4, from +5.91 in Q1 to +5.22 in Q20. Copper Price peaks at +98.42 index (level) in Q1, from +98.42 in Q1 to +94.50 in Q20. Wheat Price peaks at +99.21 index (level) in Q1, from +99.21 in Q1 to +96.05 in Q20. Gold Price peaks at +2444.29 USD/oz (level) in Q8, from +2250.80 in Q1 to +2287.25 in Q20.

Sectoral and capital. Manuf. GDP peaks at -5.00 % vs baseline in Q4, from -3.05 in Q1 to -2.33 in Q20. Services GDP peaks at -3.15 % vs baseline in Q13, from -1.40 in Q1 to -2.42 in Q20. Capital Stock peaks at -1.08 % vs baseline in Q20, from -0.03 in Q1 to -1.08 in Q20.

Timing. By Q20 GDP is still -3.33% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/IT_Y.png)

![CPI Inflation](charts/IT_pi_cpi.png)

![Equity Index](charts/IT_equity.png)

![Gold Price](charts/IT_P_gold.png)

![Energy Price](charts/IT_P_energy.png)

![Food Price](charts/IT_P_food.png)

![Wheat Price](charts/IT_P_wheat.png)

![Copper Price](charts/IT_P_copper.png)

![Metals Price](charts/IT_P_metals.png)

![VIX](charts/IT_vix.png)

![Investment](charts/IT_I.png)

![Bond Price (7y)](charts/IT_Q_B.png)

[Q1–Q20 JSON for Italy](numbers/IT.json)

## PL — Poland

The main impact of oil at $200 a barrel on Poland would be a large drop in GDP of 4.22% by Q14. Equities peak at -6.91% in Q12.

Demand and trade. Consumption peaks at -2.23 % vs baseline in Q14, from -0.79 in Q1 to -1.83 in Q20. Investment peaks at -11.70 % vs baseline in Q9, from -5.44 in Q1 to -6.95 in Q20. Net Exports peaks at -2.24 % vs baseline in Q4, from -1.32 in Q1 to -0.61 in Q20. Gov Spending peaks at +0.83 % vs baseline in Q14, from +0.32 in Q1 to +0.64 in Q20. Gov Debt peaks at +0.00 % vs baseline in Q1, from +0.00 in Q1 to +0.00 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +4.79 % vs baseline in Q3, from +3.31 in Q1 to +2.31 in Q20.

Labour. Employment peaks at -4.35 % vs baseline in Q17, from -0.34 in Q1 to -4.23 in Q20. Unemployment peaks at +1.70 pp in Q16, from +0.17 in Q1 to +1.59 in Q20. Real Wages peaks at -4.48 % vs baseline in Q20, from -0.02 in Q1 to -4.48 in Q20.

Prices. The three-year CPI impulse is +2.44 percentage points. CPI Inflation peaks at +0.59 pp in Q2, from +0.49 in Q1 to -0.24 in Q20. Domestic Infl. peaks at +0.42 pp in Q2, from +0.34 in Q1 to -0.17 in Q20. Marginal Cost peaks at -2.50 % vs baseline in Q14, from -0.96 in Q1 to -1.92 in Q20.

Financial conditions. Policy Rate peaks at +2.03 pp (annualized) in Q5, from +0.63 in Q1 to -1.24 in Q20. Real Rate peaks at +0.51 pp (annualized) in Q5, from +0.16 in Q1 to -0.31 in Q20. Govt 3M Yield peaks at +2.03 pp (annualized) in Q5, from +0.63 in Q1 to -1.24 in Q20. Govt 2Y Yield peaks at +1.65 pp (annualized) in Q2, from +1.59 in Q1 to -1.28 in Q20. Govt 5Y Yield peaks at -1.15 pp (annualized) in Q17, from +0.42 in Q1 to -1.11 in Q20. Govt 10Y Yield peaks at -0.89 pp (annualized) in Q14, from -0.33 in Q1 to -0.82 in Q20. Govt 30Y Yield peaks at -0.39 pp (annualized) in Q13, from -0.26 in Q1 to -0.34 in Q20. Bond Price (7y) peaks at -8.44 % vs baseline in Q5, from -2.63 in Q1 to +5.16 in Q20. Bond Price 3M peaks at -0.51 % vs baseline in Q5, from -0.16 in Q1 to +0.31 in Q20. Bond Price 2Y peaks at -3.13 % vs baseline in Q2, from -3.02 in Q1 to +2.42 in Q20. Bond Price 5Y peaks at +5.17 % vs baseline in Q17, from -1.90 in Q1 to +5.00 in Q20. Bond Price 10Y peaks at +7.33 % vs baseline in Q14, from +2.73 in Q1 to +6.74 in Q20. Bond Price 30Y peaks at +6.99 % vs baseline in Q13, from +4.68 in Q1 to +6.20 in Q20. Equity Index peaks at -6.91 % vs baseline in Q12, from -3.18 in Q1 to -4.57 in Q20. VIX peaks at +23.07 index_level in Q6, from +19.31 in Q1 to +18.76 in Q20. Tobin's Q peaks at -8.19 % vs baseline in Q9, from -3.80 in Q1 to -4.87 in Q20. House Prices peaks at -5.40 % vs baseline in Q20, from -0.20 in Q1 to -5.40 in Q20. Bank Equity peaks at -1.00 % vs baseline in Q18, from -0.07 in Q1 to -0.98 in Q20. Bank Credit peaks at -0.90 % vs baseline in Q18, from -0.07 in Q1 to -0.89 in Q20. Credit Spread peaks at +0.02 pp in Q18, from +0.00 in Q1 to +0.02 in Q20.

Nominal FX. NEER peaks at -3.04 % vs baseline in Q3, from -2.17 in Q1 to -2.04 in Q20. vs USD peaks at +5.50 % vs baseline in Q3, from +3.63 in Q1 to +1.95 in Q20.

Commodities. Energy Price peaks at +176.36 USD/bbl (level) in Q4, from +138.90 in Q1 to +122.38 in Q20. Metals Price peaks at +98.20 index (level) in Q1, from +98.20 in Q1 to +93.22 in Q20. Food Price peaks at +112.54 index (level) in Q8, from +101.83 in Q1 to +107.12 in Q20. Gas Price peaks at +7.04 USD/mmBtu (level) in Q4, from +5.91 in Q1 to +5.22 in Q20. Copper Price peaks at +98.42 index (level) in Q1, from +98.42 in Q1 to +94.50 in Q20. Wheat Price peaks at +99.21 index (level) in Q1, from +99.21 in Q1 to +96.05 in Q20. Gold Price peaks at +2444.29 USD/oz (level) in Q8, from +2250.80 in Q1 to +2287.25 in Q20.

Sectoral and capital. Manuf. GDP peaks at -4.91 % vs baseline in Q4, from -3.10 in Q1 to -2.79 in Q20. Services GDP peaks at -2.64 % vs baseline in Q14, from -1.04 in Q1 to -2.03 in Q20. Capital Stock peaks at -1.01 % vs baseline in Q20, from -0.03 in Q1 to -1.01 in Q20.

Timing. By Q20 GDP is still -3.24% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/PL_Y.png)

![CPI Inflation](charts/PL_pi_cpi.png)

![Equity Index](charts/PL_equity.png)

![Gold Price](charts/PL_P_gold.png)

![Energy Price](charts/PL_P_energy.png)

![Food Price](charts/PL_P_food.png)

![Wheat Price](charts/PL_P_wheat.png)

![Copper Price](charts/PL_P_copper.png)

![Metals Price](charts/PL_P_metals.png)

![VIX](charts/PL_vix.png)

![Investment](charts/PL_I.png)

![Bond Price (7y)](charts/PL_Q_B.png)

[Q1–Q20 JSON for Poland](numbers/PL.json)

## ES — Spain

The main impact of oil at $200 a barrel on Spain would be a large drop in GDP of 4.08% by Q13. Equities peak at -7.67% in Q13.

Demand and trade. Consumption peaks at -2.32 % vs baseline in Q14, from -0.86 in Q1 to -1.93 in Q20. Investment peaks at -11.93 % vs baseline in Q10, from -5.51 in Q1 to -7.57 in Q20. Net Exports peaks at -3.30 % vs baseline in Q4, from -2.04 in Q1 to -1.38 in Q20. Gov Spending peaks at +0.88 % vs baseline in Q14, from +0.38 in Q1 to +0.70 in Q20. Gov Debt peaks at +0.38 % vs baseline in Q20, from +0.01 in Q1 to +0.38 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +5.85 % vs baseline in Q4, from +3.66 in Q1 to +1.58 in Q20.

Labour. Employment peaks at -4.18 % vs baseline in Q18, from -0.33 in Q1 to -4.12 in Q20. Unemployment peaks at +1.94 pp in Q16, from +0.19 in Q1 to +1.86 in Q20. Real Wages peaks at -1.94 % vs baseline in Q20, from -0.01 in Q1 to -1.94 in Q20.

Prices. The three-year CPI impulse is +2.71 percentage points. CPI Inflation peaks at +0.66 pp in Q2, from +0.51 in Q1 to -0.25 in Q20. Domestic Infl. peaks at +0.46 pp in Q2, from +0.36 in Q1 to -0.18 in Q20. Marginal Cost peaks at -2.42 % vs baseline in Q14, from -1.04 in Q1 to -1.93 in Q20.

Financial conditions. Policy Rate peaks at +1.72 pp (annualized) in Q6, from +0.43 in Q1 to -0.88 in Q20. Real Rate peaks at +0.43 pp (annualized) in Q6, from +0.11 in Q1 to -0.22 in Q20. Govt 3M Yield peaks at +1.72 pp (annualized) in Q6, from +0.43 in Q1 to -0.88 in Q20. Govt 2Y Yield peaks at +1.46 pp (annualized) in Q3, from +1.35 in Q1 to -1.02 in Q20. Govt 5Y Yield peaks at -0.97 pp (annualized) in Q19, from +0.55 in Q1 to -0.97 in Q20. Govt 10Y Yield peaks at -0.77 pp (annualized) in Q16, from -0.21 in Q1 to -0.75 in Q20. Govt 30Y Yield peaks at -0.34 pp (annualized) in Q15, from -0.22 in Q1 to -0.32 in Q20. Bond Price (7y) peaks at -12.07 % vs baseline in Q6, from -3.04 in Q1 to +6.13 in Q20. Bond Price 3M peaks at -0.43 % vs baseline in Q6, from -0.11 in Q1 to +0.22 in Q20. Bond Price 2Y peaks at -2.78 % vs baseline in Q3, from -2.57 in Q1 to +1.93 in Q20. Bond Price 5Y peaks at +4.36 % vs baseline in Q19, from -2.46 in Q1 to +4.36 in Q20. Bond Price 10Y peaks at +6.33 % vs baseline in Q16, from +1.70 in Q1 to +6.14 in Q20. Bond Price 30Y peaks at +6.13 % vs baseline in Q15, from +3.90 in Q1 to +5.75 in Q20. Equity Index peaks at -7.67 % vs baseline in Q13, from -3.70 in Q1 to -5.48 in Q20. VIX peaks at +23.07 index_level in Q6, from +19.31 in Q1 to +18.76 in Q20. Tobin's Q peaks at -8.35 % vs baseline in Q10, from -3.85 in Q1 to -5.30 in Q20. House Prices peaks at -5.17 % vs baseline in Q20, from -0.21 in Q1 to -5.17 in Q20. Bank Equity peaks at -1.30 % vs baseline in Q17, from -0.10 in Q1 to -1.28 in Q20. Bank Credit peaks at -1.05 % vs baseline in Q17, from -0.08 in Q1 to -1.03 in Q20. Credit Spread peaks at +0.02 pp in Q17, from +0.00 in Q1 to +0.01 in Q20.

Nominal FX. NEER peaks at -4.54 % vs baseline in Q4, from -2.80 in Q1 to -1.39 in Q20. vs USD peaks at +6.65 % vs baseline in Q4, from +3.98 in Q1 to +1.22 in Q20.

Commodities. Energy Price peaks at +176.36 USD/bbl (level) in Q4, from +138.90 in Q1 to +122.38 in Q20. Metals Price peaks at +98.20 index (level) in Q1, from +98.20 in Q1 to +93.22 in Q20. Food Price peaks at +112.54 index (level) in Q8, from +101.83 in Q1 to +107.12 in Q20. Gas Price peaks at +7.04 USD/mmBtu (level) in Q4, from +5.91 in Q1 to +5.22 in Q20. Copper Price peaks at +98.42 index (level) in Q1, from +98.42 in Q1 to +94.50 in Q20. Wheat Price peaks at +99.21 index (level) in Q1, from +99.21 in Q1 to +96.05 in Q20. Gold Price peaks at +2444.29 USD/oz (level) in Q8, from +2250.80 in Q1 to +2287.25 in Q20.

Sectoral and capital. Manuf. GDP peaks at -4.29 % vs baseline in Q4, from -2.63 in Q1 to -1.97 in Q20. Services GDP peaks at -3.01 % vs baseline in Q13, from -1.31 in Q1 to -2.40 in Q20. Capital Stock peaks at -1.03 % vs baseline in Q20, from -0.03 in Q1 to -1.03 in Q20.

Timing. By Q20 GDP is still -3.26% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/ES_Y.png)

![CPI Inflation](charts/ES_pi_cpi.png)

![Equity Index](charts/ES_equity.png)

![Gold Price](charts/ES_P_gold.png)

![Energy Price](charts/ES_P_energy.png)

![Food Price](charts/ES_P_food.png)

![Wheat Price](charts/ES_P_wheat.png)

![Copper Price](charts/ES_P_copper.png)

![Metals Price](charts/ES_P_metals.png)

![VIX](charts/ES_vix.png)

![Bond Price (7y)](charts/ES_Q_B.png)

![Investment](charts/ES_I.png)

[Q1–Q20 JSON for Spain](numbers/ES.json)

## TH — Thailand

The main impact of oil at $200 a barrel on Thailand would be a large drop in GDP of 4.05% by Q13. Equities peak at -9.61% in Q13.

Demand and trade. Consumption peaks at -2.66 % vs baseline in Q13, from -0.99 in Q1 to -2.15 in Q20. Investment peaks at -10.56 % vs baseline in Q9, from -5.60 in Q1 to -5.68 in Q20. Net Exports peaks at -2.52 % vs baseline in Q3, from -1.78 in Q1 to -0.41 in Q20. Gov Spending peaks at +0.67 % vs baseline in Q13, from +0.31 in Q1 to +0.51 in Q20. Gov Debt peaks at -6.85 % vs baseline in Q20, from -0.30 in Q1 to -6.85 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +1.54 % vs baseline in Q3, from +1.00 in Q1 to +0.99 in Q20.

Labour. Employment peaks at -4.28 % vs baseline in Q16, from -0.43 in Q1 to -4.07 in Q20. Unemployment peaks at +0.39 pp in Q14, from +0.06 in Q1 to +0.33 in Q20. Real Wages peaks at -5.20 % vs baseline in Q20, from -0.03 in Q1 to -5.20 in Q20.

Prices. The three-year CPI impulse is +2.67 percentage points. CPI Inflation peaks at +0.60 pp in Q2, from +0.46 in Q1 to -0.21 in Q20. Domestic Infl. peaks at +0.42 pp in Q2, from +0.32 in Q1 to -0.15 in Q20. Marginal Cost peaks at -2.40 % vs baseline in Q13, from -1.11 in Q1 to -1.82 in Q20.

Financial conditions. Policy Rate peaks at -1.77 pp (annualized) in Q20, from +0.28 in Q1 to -1.77 in Q20. Real Rate peaks at -0.44 pp (annualized) in Q20, from +0.07 in Q1 to -0.44 in Q20. Govt 3M Yield peaks at -1.77 pp (annualized) in Q20, from +0.28 in Q1 to -1.77 in Q20. Govt 2Y Yield peaks at -1.77 pp (annualized) in Q19, from +0.72 in Q1 to -1.77 in Q20. Govt 5Y Yield peaks at -1.61 pp (annualized) in Q16, from -0.29 in Q1 to -1.52 in Q20. Govt 10Y Yield peaks at -1.28 pp (annualized) in Q13, from -0.89 in Q1 to -1.14 in Q20. Govt 30Y Yield peaks at -0.58 pp (annualized) in Q11, from -0.52 in Q1 to -0.50 in Q20. Bond Price (7y) peaks at +7.37 % vs baseline in Q20, from -1.17 in Q1 to +7.37 in Q20. Bond Price 3M peaks at +0.44 % vs baseline in Q20, from -0.07 in Q1 to +0.44 in Q20. Bond Price 2Y peaks at +3.37 % vs baseline in Q19, from -1.37 in Q1 to +3.36 in Q20. Bond Price 5Y peaks at +7.23 % vs baseline in Q16, from +1.33 in Q1 to +6.86 in Q20. Bond Price 10Y peaks at +10.46 % vs baseline in Q13, from +7.31 in Q1 to +9.37 in Q20. Bond Price 30Y peaks at +10.40 % vs baseline in Q11, from +9.41 in Q1 to +8.92 in Q20. Equity Index peaks at -9.61 % vs baseline in Q13, from -4.86 in Q1 to -6.61 in Q20. VIX peaks at +23.07 index_level in Q6, from +19.31 in Q1 to +18.76 in Q20. Tobin's Q peaks at -7.39 % vs baseline in Q9, from -3.92 in Q1 to -3.98 in Q20. House Prices peaks at -6.39 % vs baseline in Q20, from -0.33 in Q1 to -6.39 in Q20. Bank Equity peaks at -1.04 % vs baseline in Q17, from -0.08 in Q1 to -1.03 in Q20. Bank Credit peaks at -0.85 % vs baseline in Q17, from -0.07 in Q1 to -0.84 in Q20. Credit Spread peaks at +0.02 pp in Q17, from +0.00 in Q1 to +0.02 in Q20.

Nominal FX. NEER peaks at +0.74 % vs baseline in Q6, from +0.34 in Q1 to -0.53 in Q20. vs USD peaks at +2.33 % vs baseline in Q4, from +1.31 in Q1 to +0.62 in Q20.

Commodities. Energy Price peaks at +176.36 USD/bbl (level) in Q4, from +138.90 in Q1 to +122.38 in Q20. Metals Price peaks at +98.20 index (level) in Q1, from +98.20 in Q1 to +93.22 in Q20. Food Price peaks at +112.54 index (level) in Q8, from +101.83 in Q1 to +107.12 in Q20. Gas Price peaks at +7.04 USD/mmBtu (level) in Q4, from +5.91 in Q1 to +5.22 in Q20. Copper Price peaks at +98.42 index (level) in Q1, from +98.42 in Q1 to +94.50 in Q20. Wheat Price peaks at +99.21 index (level) in Q1, from +99.21 in Q1 to +96.05 in Q20. Gold Price peaks at +2444.29 USD/oz (level) in Q8, from +2250.80 in Q1 to +2287.25 in Q20.

Sectoral and capital. Manuf. GDP peaks at -4.30 % vs baseline in Q4, from -2.64 in Q1 to -2.49 in Q20. Services GDP peaks at -2.23 % vs baseline in Q13, from -1.04 in Q1 to -1.69 in Q20. Capital Stock peaks at -0.90 % vs baseline in Q20, from -0.03 in Q1 to -0.90 in Q20.

Timing. By Q20 GDP is still -3.07% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/TH_Y.png)

![CPI Inflation](charts/TH_pi_cpi.png)

![Equity Index](charts/TH_equity.png)

![Gold Price](charts/TH_P_gold.png)

![Energy Price](charts/TH_P_energy.png)

![Food Price](charts/TH_P_food.png)

![Wheat Price](charts/TH_P_wheat.png)

![Copper Price](charts/TH_P_copper.png)

![Metals Price](charts/TH_P_metals.png)

![VIX](charts/TH_vix.png)

![Investment](charts/TH_I.png)

![Bond Price 10Y](charts/TH_Q_B_10y.png)

[Q1–Q20 JSON for Thailand](numbers/TH.json)

## FR — France

The main impact of oil at $200 a barrel on France would be a large drop in GDP of 3.94% by Q15. Equities peak at -8.41% in Q14.

Demand and trade. Consumption peaks at -2.14 % vs baseline in Q15, from -0.69 in Q1 to -1.80 in Q20. Investment peaks at -11.32 % vs baseline in Q10, from -4.61 in Q1 to -7.39 in Q20. Net Exports peaks at -2.02 % vs baseline in Q4, from -1.29 in Q1 to -0.76 in Q20. Gov Spending peaks at +0.93 % vs baseline in Q15, from +0.34 in Q1 to +0.75 in Q20. Gov Debt peaks at +3.53 % vs baseline in Q20, from +0.10 in Q1 to +3.53 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +5.97 % vs baseline in Q4, from +3.74 in Q1 to +1.71 in Q20.

Labour. Employment peaks at -3.91 % vs baseline in Q19, from -0.23 in Q1 to -3.90 in Q20. Unemployment peaks at +2.76 pp in Q17, from +0.23 in Q1 to +2.67 in Q20. Real Wages peaks at -1.54 % vs baseline in Q20, from -0.01 in Q1 to -1.54 in Q20.

Prices. The three-year CPI impulse is +2.85 percentage points. CPI Inflation peaks at +0.70 pp in Q2, from +0.55 in Q1 to -0.25 in Q20. Domestic Infl. peaks at +0.49 pp in Q2, from +0.38 in Q1 to -0.18 in Q20. Marginal Cost peaks at -2.34 % vs baseline in Q15, from -0.85 in Q1 to -1.90 in Q20.

Financial conditions. Policy Rate peaks at +1.72 pp (annualized) in Q6, from +0.43 in Q1 to -0.88 in Q20. Real Rate peaks at +0.43 pp (annualized) in Q6, from +0.11 in Q1 to -0.22 in Q20. Govt 3M Yield peaks at +1.72 pp (annualized) in Q6, from +0.43 in Q1 to -0.88 in Q20. Govt 2Y Yield peaks at +1.46 pp (annualized) in Q3, from +1.35 in Q1 to -1.02 in Q20. Govt 5Y Yield peaks at -0.97 pp (annualized) in Q19, from +0.55 in Q1 to -0.97 in Q20. Govt 10Y Yield peaks at -0.77 pp (annualized) in Q16, from -0.21 in Q1 to -0.75 in Q20. Govt 30Y Yield peaks at -0.34 pp (annualized) in Q15, from -0.22 in Q1 to -0.32 in Q20. Bond Price (7y) peaks at -12.07 % vs baseline in Q6, from -3.04 in Q1 to +6.13 in Q20. Bond Price 3M peaks at -0.43 % vs baseline in Q6, from -0.11 in Q1 to +0.22 in Q20. Bond Price 2Y peaks at -2.78 % vs baseline in Q3, from -2.57 in Q1 to +1.93 in Q20. Bond Price 5Y peaks at +4.36 % vs baseline in Q19, from -2.46 in Q1 to +4.36 in Q20. Bond Price 10Y peaks at +6.33 % vs baseline in Q16, from +1.70 in Q1 to +6.14 in Q20. Bond Price 30Y peaks at +6.13 % vs baseline in Q15, from +3.90 in Q1 to +5.75 in Q20. Equity Index peaks at -8.41 % vs baseline in Q14, from -3.46 in Q1 to -6.40 in Q20. VIX peaks at +23.07 index_level in Q6, from +19.31 in Q1 to +18.76 in Q20. Tobin's Q peaks at -7.93 % vs baseline in Q10, from -3.23 in Q1 to -5.18 in Q20. House Prices peaks at -4.94 % vs baseline in Q20, from -0.17 in Q1 to -4.94 in Q20. Bank Equity peaks at -1.69 % vs baseline in Q17, from -0.11 in Q1 to -1.66 in Q20. Bank Credit peaks at -1.35 % vs baseline in Q17, from -0.09 in Q1 to -1.32 in Q20. Credit Spread peaks at +0.02 pp in Q17, from +0.00 in Q1 to +0.02 in Q20.

Nominal FX. NEER peaks at -3.13 % vs baseline in Q4, from -1.98 in Q1 to -1.04 in Q20. vs USD peaks at +6.78 % vs baseline in Q4, from +4.05 in Q1 to +1.34 in Q20.

Commodities. Energy Price peaks at +176.36 USD/bbl (level) in Q4, from +138.90 in Q1 to +122.38 in Q20. Metals Price peaks at +98.20 index (level) in Q1, from +98.20 in Q1 to +93.22 in Q20. Food Price peaks at +112.54 index (level) in Q8, from +101.83 in Q1 to +107.12 in Q20. Gas Price peaks at +7.04 USD/mmBtu (level) in Q4, from +5.91 in Q1 to +5.22 in Q20. Copper Price peaks at +98.42 index (level) in Q1, from +98.42 in Q1 to +94.50 in Q20. Wheat Price peaks at +99.21 index (level) in Q1, from +99.21 in Q1 to +96.05 in Q20. Gold Price peaks at +2444.29 USD/oz (level) in Q8, from +2250.80 in Q1 to +2287.25 in Q20.

Sectoral and capital. Manuf. GDP peaks at -4.01 % vs baseline in Q4, from -2.44 in Q1 to -1.85 in Q20. Services GDP peaks at -3.03 % vs baseline in Q15, from -1.12 in Q1 to -2.46 in Q20. Capital Stock peaks at -0.97 % vs baseline in Q20, from -0.02 in Q1 to -0.97 in Q20.

Timing. By Q20 GDP is still -3.19% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/FR_Y.png)

![CPI Inflation](charts/FR_pi_cpi.png)

![Equity Index](charts/FR_equity.png)

![Gold Price](charts/FR_P_gold.png)

![Energy Price](charts/FR_P_energy.png)

![Food Price](charts/FR_P_food.png)

![Wheat Price](charts/FR_P_wheat.png)

![Copper Price](charts/FR_P_copper.png)

![Metals Price](charts/FR_P_metals.png)

![VIX](charts/FR_vix.png)

![Bond Price (7y)](charts/FR_Q_B.png)

![Investment](charts/FR_I.png)

[Q1–Q20 JSON for France](numbers/FR.json)

## RU — Russia

The main impact of oil at $200 a barrel on Russia would be a large rise in GDP of 3.83% by Q1. Equities peak at +6.53% in Q1.

Demand and trade. Consumption peaks at +2.02 % vs baseline in Q4, from +1.67 in Q1 to +0.82 in Q20. Investment peaks at +10.03 % vs baseline in Q1, from +10.03 in Q1 to +3.22 in Q20. Net Exports peaks at +17.27 % vs baseline in Q4, from +10.51 in Q1 to +7.04 in Q20. Gov Spending peaks at +5.07 % vs baseline in Q4, from +2.82 in Q1 to +2.23 in Q20. Gov Debt peaks at +1.70 % vs baseline in Q19, from +0.19 in Q1 to +1.70 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -21.01 % vs baseline in Q5, from -12.75 in Q1 to -13.64 in Q20.

Labour. Employment peaks at +3.00 % vs baseline in Q9, from +0.70 in Q1 to +2.19 in Q20. Unemployment peaks at -1.22 pp in Q7, from -0.40 in Q1 to -0.69 in Q20. Real Wages peaks at +7.23 % vs baseline in Q20, from +0.07 in Q1 to +7.23 in Q20.

Prices. The three-year CPI impulse is +3.73 percentage points. CPI Inflation peaks at +0.50 pp in Q3, from +0.19 in Q1 to +0.03 in Q20. Domestic Infl. peaks at +0.35 pp in Q3, from +0.14 in Q1 to +0.02 in Q20. Marginal Cost peaks at +2.31 % vs baseline in Q1, from +2.31 in Q1 to +0.81 in Q20.

Financial conditions. Policy Rate peaks at +2.42 pp (annualized) in Q6, from +0.51 in Q1 to +0.33 in Q20. Real Rate peaks at +0.60 pp (annualized) in Q6, from +0.13 in Q1 to +0.08 in Q20. Govt 3M Yield peaks at +2.42 pp (annualized) in Q6, from +0.51 in Q1 to +0.33 in Q20. Govt 2Y Yield peaks at +2.14 pp (annualized) in Q3, from +1.87 in Q1 to +0.26 in Q20. Govt 5Y Yield peaks at +1.35 pp (annualized) in Q1, from +1.35 in Q1 to +0.24 in Q20. Govt 10Y Yield peaks at +0.79 pp (annualized) in Q1, from +0.79 in Q1 to +0.15 in Q20. Govt 30Y Yield peaks at +0.27 pp (annualized) in Q1, from +0.27 in Q1 to +0.05 in Q20. Bond Price (7y) peaks at -7.55 % vs baseline in Q6, from -1.60 in Q1 to -1.02 in Q20. Bond Price 3M peaks at -0.60 % vs baseline in Q6, from -0.13 in Q1 to -0.08 in Q20. Bond Price 2Y peaks at -4.07 % vs baseline in Q3, from -3.55 in Q1 to -0.49 in Q20. Bond Price 5Y peaks at -6.07 % vs baseline in Q1, from -6.07 in Q1 to -1.08 in Q20. Bond Price 10Y peaks at -6.48 % vs baseline in Q1, from -6.48 in Q1 to -1.23 in Q20. Bond Price 30Y peaks at -4.84 % vs baseline in Q1, from -4.84 in Q1 to -0.85 in Q20. Equity Index peaks at +6.53 % vs baseline in Q1, from +6.53 in Q1 to +4.13 in Q20. VIX peaks at +23.07 index_level in Q6, from +19.31 in Q1 to +18.76 in Q20. Tobin's Q peaks at +7.02 % vs baseline in Q1, from +7.02 in Q1 to +2.26 in Q20. House Prices peaks at +3.60 % vs baseline in Q16, from +0.58 in Q1 to +3.49 in Q20. Bank Equity peaks at +0.41 % vs baseline in Q20, from +0.05 in Q1 to +0.41 in Q20. Bank Credit peaks at +0.12 % vs baseline in Q20, from +0.01 in Q1 to +0.12 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +24.73 % vs baseline in Q5, from +14.93 in Q1 to +17.07 in Q20. vs USD peaks at -20.18 % vs baseline in Q5, from -12.43 in Q1 to -14.01 in Q20.

Commodities. Energy Price peaks at +176.36 USD/bbl (level) in Q4, from +138.90 in Q1 to +122.38 in Q20. Metals Price peaks at +98.20 index (level) in Q1, from +98.20 in Q1 to +93.22 in Q20. Food Price peaks at +112.54 index (level) in Q8, from +101.83 in Q1 to +107.12 in Q20. Gas Price peaks at +7.04 USD/mmBtu (level) in Q4, from +5.91 in Q1 to +5.22 in Q20. Copper Price peaks at +98.42 index (level) in Q1, from +98.42 in Q1 to +94.50 in Q20. Wheat Price peaks at +99.21 index (level) in Q1, from +99.21 in Q1 to +96.05 in Q20. Gold Price peaks at +2444.29 USD/oz (level) in Q8, from +2250.80 in Q1 to +2287.25 in Q20.

Sectoral and capital. Manuf. GDP peaks at +5.09 % vs baseline in Q5, from +3.41 in Q1 to +3.51 in Q20. Services GDP peaks at +2.11 % vs baseline in Q1, from +2.11 in Q1 to +0.74 in Q20. Capital Stock peaks at +0.50 % vs baseline in Q20, from +0.05 in Q1 to +0.50 in Q20.

Timing. By Q20 GDP is still +1.34% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/RU_Y.png)

![CPI Inflation](charts/RU_pi_cpi.png)

![Equity Index](charts/RU_equity.png)

![Gold Price](charts/RU_P_gold.png)

![Energy Price](charts/RU_P_energy.png)

![Food Price](charts/RU_P_food.png)

![Wheat Price](charts/RU_P_wheat.png)

![Copper Price](charts/RU_P_copper.png)

![Metals Price](charts/RU_P_metals.png)

![NEER](charts/RU_NEER.png)

![VIX](charts/RU_vix.png)

![Real Exchange Rate](charts/RU_RER.png)

[Q1–Q20 JSON for Russia](numbers/RU.json)

## SA — Saudi Arabia

The main impact of oil at $200 a barrel on Saudi Arabia would be a large rise in GDP of 3.82% by Q1. Equities peak at +15.90% in Q20.

Demand and trade. Consumption peaks at +2.49 % vs baseline in Q20, from +1.83 in Q1 to +2.49 in Q20. Investment peaks at +13.05 % vs baseline in Q20, from +10.03 in Q1 to +13.05 in Q20. Net Exports peaks at +29.64 % vs baseline in Q4, from +18.09 in Q1 to +12.89 in Q20. Gov Spending peaks at +11.36 % vs baseline in Q4, from +6.64 in Q1 to +4.59 in Q20. Gov Debt peaks at +9.33 % vs baseline in Q20, from +0.58 in Q1 to +9.33 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -0.80 % vs baseline in Q9, from -0.04 in Q1 to +0.32 in Q20.

Labour. Employment peaks at +4.26 % vs baseline in Q20, from +0.89 in Q1 to +4.26 in Q20. Unemployment peaks at -1.52 pp in Q20, from -0.40 in Q1 to -1.52 in Q20. Real Wages peaks at +6.59 % vs baseline in Q20, from +0.03 in Q1 to +6.59 in Q20.

Prices. The three-year CPI impulse is +3.35 percentage points. CPI Inflation peaks at +0.42 pp in Q3, from +0.31 in Q1 to +0.17 in Q20. Domestic Infl. peaks at +0.29 pp in Q3, from +0.22 in Q1 to +0.12 in Q20. Marginal Cost peaks at +2.30 % vs baseline in Q1, from +2.30 in Q1 to +2.28 in Q20.

Financial conditions. Policy Rate peaks at +1.62 pp (annualized) in Q5, from +0.48 in Q1 to -1.58 in Q20. Real Rate peaks at +0.41 pp (annualized) in Q5, from +0.12 in Q1 to -0.39 in Q20. Govt 3M Yield peaks at +1.62 pp (annualized) in Q5, from +0.48 in Q1 to -1.58 in Q20. Govt 2Y Yield peaks at -1.52 pp (annualized) in Q17, from +1.23 in Q1 to -1.44 in Q20. Govt 5Y Yield peaks at -1.26 pp (annualized) in Q14, from +0.01 in Q1 to -1.05 in Q20. Govt 10Y Yield peaks at -0.85 pp (annualized) in Q12, from -0.49 in Q1 to -0.66 in Q20. Govt 30Y Yield peaks at -0.33 pp (annualized) in Q11, from -0.24 in Q1 to -0.25 in Q20. Bond Price (7y) peaks at -8.11 % vs baseline in Q5, from -2.41 in Q1 to +7.89 in Q20. Bond Price 3M peaks at -0.41 % vs baseline in Q5, from -0.12 in Q1 to +0.39 in Q20. Bond Price 2Y peaks at +2.88 % vs baseline in Q17, from -2.35 in Q1 to +2.74 in Q20. Bond Price 5Y peaks at +5.66 % vs baseline in Q14, from -0.04 in Q1 to +4.71 in Q20. Bond Price 10Y peaks at +6.93 % vs baseline in Q12, from +4.02 in Q1 to +5.39 in Q20. Bond Price 30Y peaks at +5.90 % vs baseline in Q11, from +4.25 in Q1 to +4.56 in Q20. Equity Index peaks at +15.90 % vs baseline in Q20, from +15.18 in Q1 to +15.90 in Q20. VIX peaks at +23.07 index_level in Q6, from +19.31 in Q1 to +18.76 in Q20. Tobin's Q peaks at +9.14 % vs baseline in Q20, from +7.02 in Q1 to +9.14 in Q20. House Prices peaks at +6.26 % vs baseline in Q20, from +0.60 in Q1 to +6.26 in Q20. Bank Equity peaks at +0.48 % vs baseline in Q20, from +0.05 in Q1 to +0.48 in Q20. Bank Credit peaks at +0.15 % vs baseline in Q20, from +0.02 in Q1 to +0.15 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +2.34 % vs baseline in Q8, from +0.99 in Q1 to +0.57 in Q20. vs USD peaks at -0.78 % vs baseline in Q14, from +0.27 in Q1 to -0.04 in Q20.

Commodities. Energy Price peaks at +176.36 USD/bbl (level) in Q4, from +138.90 in Q1 to +122.38 in Q20. Metals Price peaks at +98.20 index (level) in Q1, from +98.20 in Q1 to +93.22 in Q20. Food Price peaks at +112.54 index (level) in Q8, from +101.83 in Q1 to +107.12 in Q20. Gas Price peaks at +7.04 USD/mmBtu (level) in Q4, from +5.91 in Q1 to +5.22 in Q20. Copper Price peaks at +98.42 index (level) in Q1, from +98.42 in Q1 to +94.50 in Q20. Wheat Price peaks at +99.21 index (level) in Q1, from +99.21 in Q1 to +96.05 in Q20. Gold Price peaks at +2444.29 USD/oz (level) in Q8, from +2250.80 in Q1 to +2287.25 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.79 % vs baseline in Q3, from -0.30 in Q1 to -0.17 in Q20. Services GDP peaks at +1.68 % vs baseline in Q1, from +1.68 in Q1 to +1.66 in Q20. Capital Stock peaks at +1.00 % vs baseline in Q20, from +0.05 in Q1 to +1.00 in Q20.

Timing. By Q20 GDP is still +3.78% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/SA_Y.png)

![CPI Inflation](charts/SA_pi_cpi.png)

![Equity Index](charts/SA_equity.png)

![Gold Price](charts/SA_P_gold.png)

![Energy Price](charts/SA_P_energy.png)

![Food Price](charts/SA_P_food.png)

![Wheat Price](charts/SA_P_wheat.png)

![Copper Price](charts/SA_P_copper.png)

![Metals Price](charts/SA_P_metals.png)

![Net Exports](charts/SA_NX.png)

![VIX](charts/SA_vix.png)

![Investment](charts/SA_I.png)

[Q1–Q20 JSON for Saudi Arabia](numbers/SA.json)

## NO — Norway

The main impact of oil at $200 a barrel on Norway would be a large rise in GDP of 3.78% by Q1. Equities peak at +8.14% in Q1.

Demand and trade. Consumption peaks at +2.09 % vs baseline in Q5, from +1.72 in Q1 to +1.69 in Q20. Investment peaks at +9.71 % vs baseline in Q1, from +9.71 in Q1 to +5.82 in Q20. Net Exports peaks at +17.28 % vs baseline in Q4, from +10.59 in Q1 to +6.05 in Q20. Gov Spending peaks at +7.37 % vs baseline in Q4, from +4.16 in Q1 to +3.00 in Q20. Gov Debt peaks at -1.31 % vs baseline in Q20, from -0.13 in Q1 to -1.31 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -45.02 % vs baseline in Q4, from -26.48 in Q1 to -29.32 in Q20.

Labour. Employment peaks at +3.33 % vs baseline in Q18, from +0.70 in Q1 to +3.29 in Q20. Unemployment peaks at -1.90 pp in Q9, from -0.59 in Q1 to -1.77 in Q20. Real Wages peaks at +3.94 % vs baseline in Q20, from +0.03 in Q1 to +3.94 in Q20.

Prices. The three-year CPI impulse is +0.94 percentage points. CPI Inflation peaks at +0.39 pp in Q2, from +0.32 in Q1 to -0.10 in Q20. Domestic Infl. peaks at +0.27 pp in Q2, from +0.23 in Q1 to -0.07 in Q20. Marginal Cost peaks at +2.28 % vs baseline in Q1, from +2.28 in Q1 to +1.64 in Q20.

Financial conditions. Policy Rate peaks at +2.37 pp (annualized) in Q6, from +0.63 in Q1 to +1.12 in Q20. Real Rate peaks at +0.59 pp (annualized) in Q6, from +0.16 in Q1 to +0.28 in Q20. Govt 3M Yield peaks at +2.37 pp (annualized) in Q6, from +0.63 in Q1 to +1.12 in Q20. Govt 2Y Yield peaks at +2.19 pp (annualized) in Q4, from +1.88 in Q1 to +1.06 in Q20. Govt 5Y Yield peaks at +1.69 pp (annualized) in Q2, from +1.66 in Q1 to +0.99 in Q20. Govt 10Y Yield peaks at +1.32 pp (annualized) in Q2, from +1.32 in Q1 to +0.80 in Q20. Govt 30Y Yield peaks at +0.59 pp (annualized) in Q1, from +0.59 in Q1 to +0.33 in Q20. Bond Price (7y) peaks at -14.83 % vs baseline in Q6, from -3.94 in Q1 to -6.97 in Q20. Bond Price 3M peaks at -0.59 % vs baseline in Q6, from -0.16 in Q1 to -0.28 in Q20. Bond Price 2Y peaks at -4.17 % vs baseline in Q4, from -3.57 in Q1 to -2.01 in Q20. Bond Price 5Y peaks at -7.59 % vs baseline in Q2, from -7.48 in Q1 to -4.46 in Q20. Bond Price 10Y peaks at -10.86 % vs baseline in Q2, from -10.83 in Q1 to -6.57 in Q20. Bond Price 30Y peaks at -10.68 % vs baseline in Q1, from -10.68 in Q1 to -5.88 in Q20. Equity Index peaks at +8.14 % vs baseline in Q1, from +8.14 in Q1 to +6.96 in Q20. VIX peaks at +23.07 index_level in Q6, from +19.31 in Q1 to +18.76 in Q20. Tobin's Q peaks at +6.80 % vs baseline in Q1, from +6.80 in Q1 to +4.07 in Q20. House Prices peaks at +4.26 % vs baseline in Q20, from +0.43 in Q1 to +4.26 in Q20. Bank Equity peaks at +0.62 % vs baseline in Q20, from +0.07 in Q1 to +0.62 in Q20. Bank Credit peaks at +0.24 % vs baseline in Q20, from +0.03 in Q1 to +0.24 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +45.88 % vs baseline in Q4, from +27.06 in Q1 to +29.13 in Q20. vs USD peaks at -44.21 % vs baseline in Q4, from -26.16 in Q1 to -29.68 in Q20.

Commodities. Energy Price peaks at +176.36 USD/bbl (level) in Q4, from +138.90 in Q1 to +122.38 in Q20. Metals Price peaks at +98.20 index (level) in Q1, from +98.20 in Q1 to +93.22 in Q20. Food Price peaks at +112.54 index (level) in Q8, from +101.83 in Q1 to +107.12 in Q20. Gas Price peaks at +7.04 USD/mmBtu (level) in Q4, from +5.91 in Q1 to +5.22 in Q20. Copper Price peaks at +98.42 index (level) in Q1, from +98.42 in Q1 to +94.50 in Q20. Wheat Price peaks at +99.21 index (level) in Q1, from +99.21 in Q1 to +96.05 in Q20. Gold Price peaks at +2444.29 USD/oz (level) in Q8, from +2250.80 in Q1 to +2287.25 in Q20.

Sectoral and capital. Manuf. GDP peaks at +12.42 % vs baseline in Q5, from +7.56 in Q1 to +8.52 in Q20. Services GDP peaks at +2.16 % vs baseline in Q1, from +2.16 in Q1 to +1.55 in Q20. Capital Stock peaks at +0.64 % vs baseline in Q20, from +0.05 in Q1 to +0.64 in Q20.

Timing. By Q20 GDP is still +2.71% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/NO_Y.png)

![CPI Inflation](charts/NO_pi_cpi.png)

![Equity Index](charts/NO_equity.png)

![Gold Price](charts/NO_P_gold.png)

![Energy Price](charts/NO_P_energy.png)

![Food Price](charts/NO_P_food.png)

![Wheat Price](charts/NO_P_wheat.png)

![Copper Price](charts/NO_P_copper.png)

![Metals Price](charts/NO_P_metals.png)

![NEER](charts/NO_NEER.png)

![Real Exchange Rate](charts/NO_RER.png)

![vs USD](charts/NO_USD.png)

[Q1–Q20 JSON for Norway](numbers/NO.json)

## AR — Argentina

The main impact of oil at $200 a barrel on Argentina would be a large drop in GDP of 3.72% by Q13. Equities peak at -5.56% in Q10.

Demand and trade. Consumption peaks at -1.89 % vs baseline in Q14, from -0.28 in Q1 to -1.28 in Q20. Investment peaks at -8.49 % vs baseline in Q9, from -2.50 in Q1 to -1.29 in Q20. Net Exports peaks at +2.07 % vs baseline in Q7, from +0.85 in Q1 to +1.15 in Q20. Gov Spending peaks at +0.92 % vs baseline in Q12, from +0.21 in Q1 to +0.55 in Q20. Gov Debt peaks at -3.35 % vs baseline in Q20, from -0.02 in Q1 to -3.35 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +3.07 % vs baseline in Q12, from +0.50 in Q1 to +1.51 in Q20.

Labour. Employment peaks at -3.70 % vs baseline in Q18, from -0.06 in Q1 to -3.60 in Q20. Unemployment peaks at +0.73 pp in Q15, from +0.03 in Q1 to +0.58 in Q20. Real Wages peaks at -7.17 % vs baseline in Q20, from -0.01 in Q1 to -7.17 in Q20.

Prices. The three-year CPI impulse is +1.37 percentage points. CPI Inflation peaks at -0.63 pp in Q18, from +0.35 in Q1 to -0.59 in Q20. Domestic Infl. peaks at -0.44 pp in Q18, from +0.25 in Q1 to -0.41 in Q20. Marginal Cost peaks at -2.21 % vs baseline in Q13, from -0.26 in Q1 to -1.27 in Q20.

Financial conditions. Policy Rate peaks at -2.87 pp (annualized) in Q18, from +0.86 in Q1 to -2.80 in Q20. Real Rate peaks at -0.72 pp (annualized) in Q18, from +0.22 in Q1 to -0.70 in Q20. Govt 3M Yield peaks at -2.87 pp (annualized) in Q18, from +0.86 in Q1 to -2.80 in Q20. Govt 2Y Yield peaks at -2.73 pp (annualized) in Q15, from +1.42 in Q1 to -2.24 in Q20. Govt 5Y Yield peaks at -2.14 pp (annualized) in Q11, from -0.69 in Q1 to -1.29 in Q20. Govt 10Y Yield peaks at -1.23 pp (annualized) in Q9, from -0.92 in Q1 to -0.71 in Q20. Govt 30Y Yield peaks at -0.47 pp (annualized) in Q9, from -0.37 in Q1 to -0.29 in Q20. Bond Price (7y) peaks at +7.17 % vs baseline in Q18, from -2.16 in Q1 to +6.99 in Q20. Bond Price 3M peaks at +0.72 % vs baseline in Q18, from -0.22 in Q1 to +0.70 in Q20. Bond Price 2Y peaks at +5.18 % vs baseline in Q15, from -2.69 in Q1 to +4.25 in Q20. Bond Price 5Y peaks at +9.64 % vs baseline in Q11, from +3.08 in Q1 to +5.83 in Q20. Bond Price 10Y peaks at +10.10 % vs baseline in Q9, from +7.58 in Q1 to +5.81 in Q20. Bond Price 30Y peaks at +8.42 % vs baseline in Q9, from +6.67 in Q1 to +5.14 in Q20. Equity Index peaks at -5.56 % vs baseline in Q10, from -1.16 in Q1 to -1.46 in Q20. VIX peaks at +23.07 index_level in Q6, from +19.31 in Q1 to +18.76 in Q20. Tobin's Q peaks at -5.94 % vs baseline in Q9, from -1.75 in Q1 to -0.90 in Q20. House Prices peaks at -4.17 % vs baseline in Q19, from -0.09 in Q1 to -4.13 in Q20. Bank Equity peaks at -0.16 % vs baseline in Q18, from -0.01 in Q1 to -0.16 in Q20. Bank Credit peaks at -0.32 % vs baseline in Q18, from -0.03 in Q1 to -0.32 in Q20. Credit Spread peaks at +0.09 pp in Q18, from +0.01 in Q1 to +0.09 in Q20.

Nominal FX. NEER peaks at -3.80 % vs baseline in Q10, from -0.93 in Q1 to -1.60 in Q20. vs USD peaks at +3.15 % vs baseline in Q10, from +0.82 in Q1 to +1.14 in Q20.

Commodities. Energy Price peaks at +176.36 USD/bbl (level) in Q4, from +138.90 in Q1 to +122.38 in Q20. Metals Price peaks at +98.20 index (level) in Q1, from +98.20 in Q1 to +93.22 in Q20. Food Price peaks at +112.54 index (level) in Q8, from +101.83 in Q1 to +107.12 in Q20. Gas Price peaks at +7.04 USD/mmBtu (level) in Q4, from +5.91 in Q1 to +5.22 in Q20. Copper Price peaks at +98.42 index (level) in Q1, from +98.42 in Q1 to +94.50 in Q20. Wheat Price peaks at +99.21 index (level) in Q1, from +99.21 in Q1 to +96.05 in Q20. Gold Price peaks at +2444.29 USD/oz (level) in Q8, from +2250.80 in Q1 to +2287.25 in Q20.

Sectoral and capital. Manuf. GDP peaks at -3.00 % vs baseline in Q10, from -1.42 in Q1 to -1.73 in Q20. Services GDP peaks at -2.13 % vs baseline in Q13, from -0.27 in Q1 to -1.22 in Q20. Capital Stock peaks at -0.60 % vs baseline in Q20, from -0.01 in Q1 to -0.60 in Q20.

Timing. By Q20 GDP is still -2.14% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/AR_Y.png)

![CPI Inflation](charts/AR_pi_cpi.png)

![Equity Index](charts/AR_equity.png)

![Gold Price](charts/AR_P_gold.png)

![Energy Price](charts/AR_P_energy.png)

![Food Price](charts/AR_P_food.png)

![Wheat Price](charts/AR_P_wheat.png)

![Copper Price](charts/AR_P_copper.png)

![Metals Price](charts/AR_P_metals.png)

![VIX](charts/AR_vix.png)

![Bond Price 10Y](charts/AR_Q_B_10y.png)

![Bond Price 5Y](charts/AR_Q_B_5y.png)

[Q1–Q20 JSON for Argentina](numbers/AR.json)

## ZA — South Africa

The main impact of oil at $200 a barrel on South Africa would be a large drop in GDP of 3.69% by Q15. Equities peak at -13.92% in Q13.

Demand and trade. Consumption peaks at -2.19 % vs baseline in Q16, from -0.71 in Q1 to -1.79 in Q20. Investment peaks at -10.14 % vs baseline in Q8, from -4.72 in Q1 to -5.55 in Q20. Net Exports peaks at -2.64 % vs baseline in Q4, from -1.49 in Q1 to -1.35 in Q20. Gov Spending peaks at +0.58 % vs baseline in Q15, from +0.23 in Q1 to +0.44 in Q20. Gov Debt peaks at -3.75 % vs baseline in Q20, from -0.11 in Q1 to -3.75 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +4.90 % vs baseline in Q4, from +3.03 in Q1 to +2.22 in Q20.

Labour. Employment peaks at -4.05 % vs baseline in Q18, from -0.29 in Q1 to -3.95 in Q20. Unemployment peaks at +0.89 pp in Q16, from +0.10 in Q1 to +0.80 in Q20. Real Wages peaks at -4.92 % vs baseline in Q20, from -0.02 in Q1 to -4.92 in Q20.

Prices. The three-year CPI impulse is +1.77 percentage points. CPI Inflation peaks at +0.46 pp in Q2, from +0.36 in Q1 to -0.26 in Q20. Domestic Infl. peaks at +0.32 pp in Q2, from +0.25 in Q1 to -0.18 in Q20. Marginal Cost peaks at -2.19 % vs baseline in Q15, from -0.82 in Q1 to -1.69 in Q20.

Financial conditions. Policy Rate peaks at +1.78 pp (annualized) in Q5, from +0.58 in Q1 to -1.42 in Q20. Real Rate peaks at +0.44 pp (annualized) in Q5, from +0.14 in Q1 to -0.36 in Q20. Govt 3M Yield peaks at +1.78 pp (annualized) in Q5, from +0.58 in Q1 to -1.42 in Q20. Govt 2Y Yield peaks at +1.41 pp (annualized) in Q2, from +1.38 in Q1 to -1.36 in Q20. Govt 5Y Yield peaks at -1.20 pp (annualized) in Q15, from +0.17 in Q1 to -1.08 in Q20. Govt 10Y Yield peaks at -0.88 pp (annualized) in Q13, from -0.44 in Q1 to -0.74 in Q20. Govt 30Y Yield peaks at -0.36 pp (annualized) in Q12, from -0.26 in Q1 to -0.30 in Q20. Bond Price (7y) peaks at -7.41 % vs baseline in Q5, from -2.41 in Q1 to +5.93 in Q20. Bond Price 3M peaks at -0.44 % vs baseline in Q5, from -0.14 in Q1 to +0.36 in Q20. Bond Price 2Y peaks at -2.68 % vs baseline in Q2, from -2.63 in Q1 to +2.59 in Q20. Bond Price 5Y peaks at +5.42 % vs baseline in Q15, from -0.77 in Q1 to +4.87 in Q20. Bond Price 10Y peaks at +7.18 % vs baseline in Q13, from +3.57 in Q1 to +6.09 in Q20. Bond Price 30Y peaks at +6.52 % vs baseline in Q12, from +4.62 in Q1 to +5.41 in Q20. Equity Index peaks at -13.92 % vs baseline in Q13, from -5.79 in Q1 to -10.07 in Q20. VIX peaks at +23.07 index_level in Q6, from +19.31 in Q1 to +18.76 in Q20. Tobin's Q peaks at -7.09 % vs baseline in Q8, from -3.30 in Q1 to -3.89 in Q20. House Prices peaks at -5.38 % vs baseline in Q20, from -0.23 in Q1 to -5.38 in Q20. Bank Equity peaks at -0.89 % vs baseline in Q17, from -0.07 in Q1 to -0.88 in Q20. Bank Credit peaks at -0.77 % vs baseline in Q17, from -0.06 in Q1 to -0.76 in Q20. Credit Spread peaks at +0.03 pp in Q17, from +0.00 in Q1 to +0.03 in Q20.

Nominal FX. NEER peaks at -2.99 % vs baseline in Q3, from -1.84 in Q1 to -0.98 in Q20. vs USD peaks at +5.70 % vs baseline in Q4, from +3.35 in Q1 to +1.86 in Q20.

Commodities. Energy Price peaks at +176.36 USD/bbl (level) in Q4, from +138.90 in Q1 to +122.38 in Q20. Metals Price peaks at +98.20 index (level) in Q1, from +98.20 in Q1 to +93.22 in Q20. Food Price peaks at +112.54 index (level) in Q8, from +101.83 in Q1 to +107.12 in Q20. Gas Price peaks at +7.04 USD/mmBtu (level) in Q4, from +5.91 in Q1 to +5.22 in Q20. Copper Price peaks at +98.42 index (level) in Q1, from +98.42 in Q1 to +94.50 in Q20. Wheat Price peaks at +99.21 index (level) in Q1, from +99.21 in Q1 to +96.05 in Q20. Gold Price peaks at +2444.29 USD/oz (level) in Q8, from +2250.80 in Q1 to +2287.25 in Q20.

Sectoral and capital. Manuf. GDP peaks at -3.65 % vs baseline in Q4, from -2.23 in Q1 to -1.94 in Q20. Services GDP peaks at -2.36 % vs baseline in Q15, from -0.90 in Q1 to -1.82 in Q20. Capital Stock peaks at -0.86 % vs baseline in Q20, from -0.02 in Q1 to -0.86 in Q20.

Timing. By Q20 GDP is still -2.85% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/ZA_Y.png)

![CPI Inflation](charts/ZA_pi_cpi.png)

![Equity Index](charts/ZA_equity.png)

![Gold Price](charts/ZA_P_gold.png)

![Energy Price](charts/ZA_P_energy.png)

![Food Price](charts/ZA_P_food.png)

![Wheat Price](charts/ZA_P_wheat.png)

![Copper Price](charts/ZA_P_copper.png)

![Metals Price](charts/ZA_P_metals.png)

![VIX](charts/ZA_vix.png)

![Investment](charts/ZA_I.png)

![Bond Price (7y)](charts/ZA_Q_B.png)

[Q1–Q20 JSON for South Africa](numbers/ZA.json)

## CN — China

The main impact of oil at $200 a barrel on China would be a large drop in GDP of 3.37% by Q13. Equities peak at -6.86% in Q10.

Demand and trade. Consumption peaks at -2.55 % vs baseline in Q14, from -1.02 in Q1 to -1.99 in Q20. Investment peaks at -8.49 % vs baseline in Q4, from -4.76 in Q1 to -2.50 in Q20. Net Exports peaks at -3.33 % vs baseline in Q4, from -1.99 in Q1 to -1.20 in Q20. Gov Spending peaks at +0.58 % vs baseline in Q13, from +0.28 in Q1 to +0.43 in Q20. Gov Debt peaks at -5.78 % vs baseline in Q20, from -0.19 in Q1 to -5.78 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +4.07 % vs baseline in Q20, from +1.81 in Q1 to +4.07 in Q20.

Labour. Employment peaks at -3.10 % vs baseline in Q18, from -0.21 in Q1 to -3.08 in Q20. Unemployment peaks at +0.77 pp in Q15, from +0.11 in Q1 to +0.67 in Q20. Real Wages peaks at -5.36 % vs baseline in Q20, from -0.03 in Q1 to -5.36 in Q20.

Prices. The three-year CPI impulse is +2.68 percentage points. CPI Inflation peaks at +0.71 pp in Q2, from +0.59 in Q1 to -0.33 in Q20. Domestic Infl. peaks at +0.50 pp in Q2, from +0.42 in Q1 to -0.23 in Q20. Marginal Cost peaks at -2.00 % vs baseline in Q13, from -0.98 in Q1 to -1.50 in Q20.

Financial conditions. Policy Rate peaks at -2.90 pp (annualized) in Q20, from +0.12 in Q1 to -2.90 in Q20. Real Rate peaks at -0.72 pp (annualized) in Q20, from +0.03 in Q1 to -0.72 in Q20. Govt 3M Yield peaks at -2.90 pp (annualized) in Q20, from +0.12 in Q1 to -2.90 in Q20. Govt 2Y Yield peaks at -2.95 pp (annualized) in Q20, from +0.13 in Q1 to -2.95 in Q20. Govt 5Y Yield peaks at -2.73 pp (annualized) in Q16, from -1.10 in Q1 to -2.62 in Q20. Govt 10Y Yield peaks at -2.21 pp (annualized) in Q12, from -1.84 in Q1 to -1.95 in Q20. Govt 30Y Yield peaks at -0.98 pp (annualized) in Q8, from -0.96 in Q1 to -0.82 in Q20. Bond Price (7y) peaks at +14.48 % vs baseline in Q20, from -0.62 in Q1 to +14.48 in Q20. Bond Price 3M peaks at +0.72 % vs baseline in Q20, from -0.03 in Q1 to +0.72 in Q20. Bond Price 2Y peaks at +5.61 % vs baseline in Q20, from -0.24 in Q1 to +5.61 in Q20. Bond Price 5Y peaks at +12.28 % vs baseline in Q16, from +4.97 in Q1 to +11.79 in Q20. Bond Price 10Y peaks at +18.09 % vs baseline in Q12, from +15.07 in Q1 to +16.02 in Q20. Bond Price 30Y peaks at +17.62 % vs baseline in Q8, from +17.34 in Q1 to +14.67 in Q20. Equity Index peaks at -6.86 % vs baseline in Q10, from -3.60 in Q1 to -4.52 in Q20. VIX peaks at +23.07 index_level in Q6, from +19.31 in Q1 to +18.76 in Q20. Tobin's Q peaks at -5.94 % vs baseline in Q4, from -3.33 in Q1 to -1.75 in Q20. House Prices peaks at -4.49 % vs baseline in Q19, from -0.25 in Q1 to -4.48 in Q20. Bank Equity peaks at -1.04 % vs baseline in Q16, from -0.08 in Q1 to -1.01 in Q20. Bank Credit peaks at -0.80 % vs baseline in Q16, from -0.06 in Q1 to -0.78 in Q20. Credit Spread peaks at +0.01 pp in Q16, from +0.00 in Q1 to +0.01 in Q20.

Nominal FX. NEER peaks at -5.06 % vs baseline in Q20, from -1.90 in Q1 to -5.06 in Q20. vs USD peaks at +3.81 % vs baseline in Q6, from +2.13 in Q1 to +3.71 in Q20.

Commodities. Energy Price peaks at +176.36 USD/bbl (level) in Q4, from +138.90 in Q1 to +122.38 in Q20. Metals Price peaks at +98.20 index (level) in Q1, from +98.20 in Q1 to +93.22 in Q20. Food Price peaks at +112.54 index (level) in Q8, from +101.83 in Q1 to +107.12 in Q20. Gas Price peaks at +7.04 USD/mmBtu (level) in Q4, from +5.91 in Q1 to +5.22 in Q20. Copper Price peaks at +98.42 index (level) in Q1, from +98.42 in Q1 to +94.50 in Q20. Wheat Price peaks at +99.21 index (level) in Q1, from +99.21 in Q1 to +96.05 in Q20. Gold Price peaks at +2444.29 USD/oz (level) in Q8, from +2250.80 in Q1 to +2287.25 in Q20.

Sectoral and capital. Manuf. GDP peaks at -4.97 % vs baseline in Q4, from -3.04 in Q1 to -3.45 in Q20. Services GDP peaks at -1.96 % vs baseline in Q13, from -0.98 in Q1 to -1.47 in Q20. Capital Stock peaks at -0.65 % vs baseline in Q20, from -0.02 in Q1 to -0.65 in Q20.

Timing. By Q20 GDP is still -2.53% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/CN_Y.png)

![CPI Inflation](charts/CN_pi_cpi.png)

![Equity Index](charts/CN_equity.png)

![Gold Price](charts/CN_P_gold.png)

![Energy Price](charts/CN_P_energy.png)

![Food Price](charts/CN_P_food.png)

![Wheat Price](charts/CN_P_wheat.png)

![Copper Price](charts/CN_P_copper.png)

![Metals Price](charts/CN_P_metals.png)

![VIX](charts/CN_vix.png)

![Bond Price 10Y](charts/CN_Q_B_10y.png)

![Bond Price 30Y](charts/CN_Q_B_30y.png)

[Q1–Q20 JSON for China](numbers/CN.json)

## CL — Chile

The main impact of oil at $200 a barrel on Chile would be a large drop in GDP of 3.29% by Q15. Equities peak at -6.98% in Q11.

Demand and trade. Consumption peaks at -2.10 % vs baseline in Q17, from -0.70 in Q1 to -1.89 in Q20. Investment peaks at -9.36 % vs baseline in Q8, from -4.37 in Q1 to -5.30 in Q20. Net Exports peaks at -2.92 % vs baseline in Q5, from -1.56 in Q1 to -1.69 in Q20. Gov Spending peaks at +0.32 % vs baseline in Q17, from +0.17 in Q1 to +0.27 in Q20. Gov Debt peaks at -3.58 % vs baseline in Q20, from -0.14 in Q1 to -3.58 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +3.96 % vs baseline in Q4, from +2.41 in Q1 to +1.62 in Q20.

Labour. Employment peaks at -3.63 % vs baseline in Q18, from -0.29 in Q1 to -3.59 in Q20. Unemployment peaks at +1.18 pp in Q17, from +0.13 in Q1 to +1.13 in Q20. Real Wages peaks at -4.61 % vs baseline in Q20, from -0.02 in Q1 to -4.61 in Q20.

Prices. The three-year CPI impulse is +1.31 percentage points. CPI Inflation peaks at +0.44 pp in Q2, from +0.35 in Q1 to -0.24 in Q20. Domestic Infl. peaks at +0.31 pp in Q2, from +0.24 in Q1 to -0.17 in Q20. Marginal Cost peaks at -1.95 % vs baseline in Q15, from -0.76 in Q1 to -1.67 in Q20.

Financial conditions. Policy Rate peaks at +1.79 pp (annualized) in Q5, from +0.54 in Q1 to -1.54 in Q20. Real Rate peaks at +0.45 pp (annualized) in Q5, from +0.14 in Q1 to -0.39 in Q20. Govt 3M Yield peaks at +1.79 pp (annualized) in Q5, from +0.54 in Q1 to -1.54 in Q20. Govt 2Y Yield peaks at -1.52 pp (annualized) in Q19, from +1.38 in Q1 to -1.50 in Q20. Govt 5Y Yield peaks at -1.32 pp (annualized) in Q15, from +0.16 in Q1 to -1.21 in Q20. Govt 10Y Yield peaks at -0.98 pp (annualized) in Q13, from -0.51 in Q1 to -0.86 in Q20. Govt 30Y Yield peaks at -0.42 pp (annualized) in Q12, from -0.32 in Q1 to -0.36 in Q20. Bond Price (7y) peaks at -7.45 % vs baseline in Q5, from -2.27 in Q1 to +6.42 in Q20. Bond Price 3M peaks at -0.45 % vs baseline in Q5, from -0.14 in Q1 to +0.39 in Q20. Bond Price 2Y peaks at +2.88 % vs baseline in Q19, from -2.63 in Q1 to +2.85 in Q20. Bond Price 5Y peaks at +5.93 % vs baseline in Q15, from -0.71 in Q1 to +5.44 in Q20. Bond Price 10Y peaks at +8.03 % vs baseline in Q13, from +4.14 in Q1 to +7.02 in Q20. Bond Price 30Y peaks at +7.62 % vs baseline in Q12, from +5.69 in Q1 to +6.48 in Q20. Equity Index peaks at -6.98 % vs baseline in Q11, from -3.22 in Q1 to -5.19 in Q20. VIX peaks at +23.07 index_level in Q6, from +19.31 in Q1 to +18.76 in Q20. Tobin's Q peaks at -6.55 % vs baseline in Q8, from -3.06 in Q1 to -3.71 in Q20. House Prices peaks at -5.00 % vs baseline in Q20, from -0.22 in Q1 to -5.00 in Q20. Bank Equity peaks at -0.77 % vs baseline in Q18, from -0.06 in Q1 to -0.77 in Q20. Bank Credit peaks at -0.63 % vs baseline in Q18, from -0.05 in Q1 to -0.63 in Q20. Credit Spread peaks at +0.02 pp in Q18, from +0.00 in Q1 to +0.02 in Q20.

Nominal FX. NEER peaks at -4.23 % vs baseline in Q4, from -2.38 in Q1 to -1.04 in Q20. vs USD peaks at +4.77 % vs baseline in Q4, from +2.72 in Q1 to +1.25 in Q20.

Commodities. Energy Price peaks at +176.36 USD/bbl (level) in Q4, from +138.90 in Q1 to +122.38 in Q20. Metals Price peaks at +98.20 index (level) in Q1, from +98.20 in Q1 to +93.22 in Q20. Food Price peaks at +112.54 index (level) in Q8, from +101.83 in Q1 to +107.12 in Q20. Gas Price peaks at +7.04 USD/mmBtu (level) in Q4, from +5.91 in Q1 to +5.22 in Q20. Copper Price peaks at +98.42 index (level) in Q1, from +98.42 in Q1 to +94.50 in Q20. Wheat Price peaks at +99.21 index (level) in Q1, from +99.21 in Q1 to +96.05 in Q20. Gold Price peaks at +2444.29 USD/oz (level) in Q8, from +2250.80 in Q1 to +2287.25 in Q20.

Sectoral and capital. Manuf. GDP peaks at -3.34 % vs baseline in Q4, from -2.02 in Q1 to -1.75 in Q20. Services GDP peaks at -1.99 % vs baseline in Q15, from -0.79 in Q1 to -1.70 in Q20. Capital Stock peaks at -0.79 % vs baseline in Q20, from -0.02 in Q1 to -0.79 in Q20.

Timing. By Q20 GDP is still -2.80% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/CL_Y.png)

![CPI Inflation](charts/CL_pi_cpi.png)

![Equity Index](charts/CL_equity.png)

![Gold Price](charts/CL_P_gold.png)

![Energy Price](charts/CL_P_energy.png)

![Food Price](charts/CL_P_food.png)

![Wheat Price](charts/CL_P_wheat.png)

![Copper Price](charts/CL_P_copper.png)

![Metals Price](charts/CL_P_metals.png)

![VIX](charts/CL_vix.png)

![Investment](charts/CL_I.png)

![Bond Price 10Y](charts/CL_Q_B_10y.png)

[Q1–Q20 JSON for Chile](numbers/CL.json)

## SE — Sweden

The main impact of oil at $200 a barrel on Sweden would be a large drop in GDP of 2.97% by Q17. Equities peak at -8.19% in Q13.

Demand and trade. Consumption peaks at -1.73 % vs baseline in Q18, from -0.62 in Q1 to -1.65 in Q20. Investment peaks at -8.84 % vs baseline in Q8, from -3.96 in Q1 to -6.29 in Q20. Net Exports peaks at -2.34 % vs baseline in Q4, from -1.39 in Q1 to -0.98 in Q20. Gov Spending peaks at +0.61 % vs baseline in Q17, from +0.25 in Q1 to +0.57 in Q20. Gov Debt peaks at +1.63 % vs baseline in Q20, from +0.07 in Q1 to +1.63 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +1.57 % vs baseline in Q4, from +0.87 in Q1 to +0.80 in Q20.

Labour. Employment peaks at -3.06 % vs baseline in Q20, from -0.20 in Q1 to -3.06 in Q20. Unemployment peaks at +2.18 pp in Q19, from +0.19 in Q1 to +2.17 in Q20. Real Wages peaks at -2.33 % vs baseline in Q20, from -0.01 in Q1 to -2.33 in Q20.

Prices. The three-year CPI impulse is +2.31 percentage points. CPI Inflation peaks at +0.57 pp in Q2, from +0.45 in Q1 to -0.19 in Q20. Domestic Infl. peaks at +0.40 pp in Q2, from +0.32 in Q1 to -0.13 in Q20. Marginal Cost peaks at -1.77 % vs baseline in Q17, from -0.71 in Q1 to -1.64 in Q20.

Financial conditions. Policy Rate peaks at +1.65 pp (annualized) in Q5, from +0.44 in Q1 to -0.83 in Q20. Real Rate peaks at +0.41 pp (annualized) in Q5, from +0.11 in Q1 to -0.21 in Q20. Govt 3M Yield peaks at +1.65 pp (annualized) in Q5, from +0.44 in Q1 to -0.83 in Q20. Govt 2Y Yield peaks at +1.38 pp (annualized) in Q2, from +1.29 in Q1 to -0.92 in Q20. Govt 5Y Yield peaks at -0.84 pp (annualized) in Q18, from +0.49 in Q1 to -0.83 in Q20. Govt 10Y Yield peaks at -0.67 pp (annualized) in Q16, from -0.17 in Q1 to -0.64 in Q20. Govt 30Y Yield peaks at -0.30 pp (annualized) in Q14, from -0.19 in Q1 to -0.28 in Q20. Bond Price (7y) peaks at -10.29 % vs baseline in Q5, from -2.75 in Q1 to +5.19 in Q20. Bond Price 3M peaks at -0.41 % vs baseline in Q5, from -0.11 in Q1 to +0.21 in Q20. Bond Price 2Y peaks at -2.61 % vs baseline in Q2, from -2.46 in Q1 to +1.74 in Q20. Bond Price 5Y peaks at +3.78 % vs baseline in Q18, from -2.20 in Q1 to +3.75 in Q20. Bond Price 10Y peaks at +5.49 % vs baseline in Q16, from +1.37 in Q1 to +5.27 in Q20. Bond Price 30Y peaks at +5.40 % vs baseline in Q14, from +3.35 in Q1 to +5.00 in Q20. Equity Index peaks at -8.19 % vs baseline in Q13, from -3.77 in Q1 to -7.23 in Q20. VIX peaks at +23.07 index_level in Q6, from +19.31 in Q1 to +18.76 in Q20. Tobin's Q peaks at -6.19 % vs baseline in Q8, from -2.77 in Q1 to -4.40 in Q20. House Prices peaks at -3.98 % vs baseline in Q20, from -0.14 in Q1 to -3.98 in Q20. Bank Equity peaks at -1.13 % vs baseline in Q18, from -0.08 in Q1 to -1.11 in Q20. Bank Credit peaks at -0.90 % vs baseline in Q18, from -0.06 in Q1 to -0.89 in Q20. Credit Spread peaks at +0.01 pp in Q17, from +0.00 in Q1 to +0.01 in Q20.

Nominal FX. NEER peaks at -4.31 % vs baseline in Q5, from -2.37 in Q1 to -3.64 in Q20. vs USD peaks at +2.38 % vs baseline in Q5, from +1.19 in Q1 to +0.43 in Q20.

Commodities. Energy Price peaks at +176.36 USD/bbl (level) in Q4, from +138.90 in Q1 to +122.38 in Q20. Metals Price peaks at +98.20 index (level) in Q1, from +98.20 in Q1 to +93.22 in Q20. Food Price peaks at +112.54 index (level) in Q8, from +101.83 in Q1 to +107.12 in Q20. Gas Price peaks at +7.04 USD/mmBtu (level) in Q4, from +5.91 in Q1 to +5.22 in Q20. Copper Price peaks at +98.42 index (level) in Q1, from +98.42 in Q1 to +94.50 in Q20. Wheat Price peaks at +99.21 index (level) in Q1, from +99.21 in Q1 to +96.05 in Q20. Gold Price peaks at +2444.29 USD/oz (level) in Q8, from +2250.80 in Q1 to +2287.25 in Q20.

Sectoral and capital. Manuf. GDP peaks at -3.07 % vs baseline in Q4, from -1.82 in Q1 to -1.78 in Q20. Services GDP peaks at -2.13 % vs baseline in Q17, from -0.87 in Q1 to -1.97 in Q20. Capital Stock peaks at -0.78 % vs baseline in Q20, from -0.02 in Q1 to -0.78 in Q20.

Timing. By Q20 GDP is still -2.76% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/SE_Y.png)

![CPI Inflation](charts/SE_pi_cpi.png)

![Equity Index](charts/SE_equity.png)

![Gold Price](charts/SE_P_gold.png)

![Energy Price](charts/SE_P_energy.png)

![Food Price](charts/SE_P_food.png)

![Wheat Price](charts/SE_P_wheat.png)

![Copper Price](charts/SE_P_copper.png)

![Metals Price](charts/SE_P_metals.png)

![VIX](charts/SE_vix.png)

![Bond Price (7y)](charts/SE_Q_B.png)

![Investment](charts/SE_I.png)

[Q1–Q20 JSON for Sweden](numbers/SE.json)

## ID — Indonesia

The main impact of oil at $200 a barrel on Indonesia would be a large drop in GDP of 2.80% by Q14. Equities peak at -5.21% in Q11.

Demand and trade. Consumption peaks at -1.71 % vs baseline in Q16, from -0.57 in Q1 to -1.53 in Q20. Investment peaks at -8.35 % vs baseline in Q8, from -3.68 in Q1 to -4.10 in Q20. Net Exports peaks at -1.20 % vs baseline in Q4, from -0.78 in Q1 to -0.44 in Q20. Gov Spending peaks at +0.45 % vs baseline in Q14, from +0.18 in Q1 to +0.38 in Q20. Gov Debt peaks at -5.00 % vs baseline in Q20, from -0.21 in Q1 to -5.00 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -4.67 % vs baseline in Q5, from -2.91 in Q1 to -2.11 in Q20.

Labour. Employment peaks at -2.79 % vs baseline in Q20, from -0.14 in Q1 to -2.79 in Q20. Unemployment peaks at +0.24 pp in Q16, from +0.04 in Q1 to +0.23 in Q20. Real Wages peaks at -4.18 % vs baseline in Q20, from -0.02 in Q1 to -4.18 in Q20.

Prices. The three-year CPI impulse is +1.90 percentage points. CPI Inflation peaks at +0.47 pp in Q3, from +0.28 in Q1 to -0.31 in Q20. Domestic Infl. peaks at +0.33 pp in Q3, from +0.20 in Q1 to -0.22 in Q20. Marginal Cost peaks at -1.66 % vs baseline in Q14, from -0.66 in Q1 to -1.39 in Q20.

Financial conditions. Policy Rate peaks at +1.59 pp (annualized) in Q5, from +0.39 in Q1 to -1.49 in Q20. Real Rate peaks at +0.40 pp (annualized) in Q5, from +0.10 in Q1 to -0.37 in Q20. Govt 3M Yield peaks at +1.59 pp (annualized) in Q5, from +0.39 in Q1 to -1.49 in Q20. Govt 2Y Yield peaks at -1.49 pp (annualized) in Q19, from +1.22 in Q1 to -1.49 in Q20. Govt 5Y Yield peaks at -1.30 pp (annualized) in Q16, from +0.17 in Q1 to -1.22 in Q20. Govt 10Y Yield peaks at -0.96 pp (annualized) in Q14, from -0.51 in Q1 to -0.86 in Q20. Govt 30Y Yield peaks at -0.41 pp (annualized) in Q12, from -0.31 in Q1 to -0.35 in Q20. Bond Price (7y) peaks at -6.61 % vs baseline in Q5, from -1.63 in Q1 to +6.19 in Q20. Bond Price 3M peaks at -0.40 % vs baseline in Q5, from -0.10 in Q1 to +0.37 in Q20. Bond Price 2Y peaks at +2.84 % vs baseline in Q19, from -2.32 in Q1 to +2.83 in Q20. Bond Price 5Y peaks at +5.84 % vs baseline in Q16, from -0.75 in Q1 to +5.47 in Q20. Bond Price 10Y peaks at +7.90 % vs baseline in Q14, from +4.15 in Q1 to +7.02 in Q20. Bond Price 30Y peaks at +7.31 % vs baseline in Q12, from +5.52 in Q1 to +6.31 in Q20. Equity Index peaks at -5.21 % vs baseline in Q11, from -2.44 in Q1 to -3.68 in Q20. VIX peaks at +23.07 index_level in Q6, from +19.31 in Q1 to +18.76 in Q20. Tobin's Q peaks at -5.85 % vs baseline in Q8, from -2.57 in Q1 to -2.87 in Q20. House Prices peaks at -4.09 % vs baseline in Q20, from -0.18 in Q1 to -4.09 in Q20. Bank Equity peaks at -0.56 % vs baseline in Q17, from -0.04 in Q1 to -0.55 in Q20. Bank Credit peaks at -0.57 % vs baseline in Q17, from -0.04 in Q1 to -0.56 in Q20. Credit Spread peaks at +0.03 pp in Q17, from +0.00 in Q1 to +0.03 in Q20.

Nominal FX. NEER peaks at +5.76 % vs baseline in Q5, from +3.57 in Q1 to +2.70 in Q20. vs USD peaks at -3.85 % vs baseline in Q5, from -2.59 in Q1 to -2.47 in Q20.

Commodities. Energy Price peaks at +176.36 USD/bbl (level) in Q4, from +138.90 in Q1 to +122.38 in Q20. Metals Price peaks at +98.20 index (level) in Q1, from +98.20 in Q1 to +93.22 in Q20. Food Price peaks at +112.54 index (level) in Q8, from +101.83 in Q1 to +107.12 in Q20. Gas Price peaks at +7.04 USD/mmBtu (level) in Q4, from +5.91 in Q1 to +5.22 in Q20. Copper Price peaks at +98.42 index (level) in Q1, from +98.42 in Q1 to +94.50 in Q20. Wheat Price peaks at +99.21 index (level) in Q1, from +99.21 in Q1 to +96.05 in Q20. Gold Price peaks at +2444.29 USD/oz (level) in Q8, from +2250.80 in Q1 to +2287.25 in Q20.

Sectoral and capital. Manuf. GDP peaks at -1.52 % vs baseline in Q4, from -0.89 in Q1 to -1.02 in Q20. Services GDP peaks at -1.39 % vs baseline in Q14, from -0.57 in Q1 to -1.16 in Q20. Capital Stock peaks at -0.68 % vs baseline in Q20, from -0.02 in Q1 to -0.68 in Q20.

Timing. By Q20 GDP is still -2.35% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/ID_Y.png)

![CPI Inflation](charts/ID_pi_cpi.png)

![Equity Index](charts/ID_equity.png)

![Gold Price](charts/ID_P_gold.png)

![Energy Price](charts/ID_P_energy.png)

![Food Price](charts/ID_P_food.png)

![Wheat Price](charts/ID_P_wheat.png)

![Copper Price](charts/ID_P_copper.png)

![Metals Price](charts/ID_P_metals.png)

![VIX](charts/ID_vix.png)

![Investment](charts/ID_I.png)

![Bond Price 10Y](charts/ID_Q_B_10y.png)

[Q1–Q20 JSON for Indonesia](numbers/ID.json)

## NG — Nigeria

The main impact of oil at $200 a barrel on Nigeria would be a large rise in GDP of 2.63% by Q3. Equities peak at +3.25% in Q3.

Demand and trade. Consumption peaks at +1.50 % vs baseline in Q4, from +0.75 in Q1 to -0.44 in Q20. Investment peaks at +5.97 % vs baseline in Q2, from +4.16 in Q1 to -0.77 in Q20. Net Exports peaks at +9.21 % vs baseline in Q4, from +5.63 in Q1 to +3.98 in Q20. Gov Spending peaks at +1.33 % vs baseline in Q5, from +0.79 in Q1 to +0.87 in Q20. Gov Debt peaks at +4.38 % vs baseline in Q11, from +0.40 in Q1 to +2.68 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -10.06 % vs baseline in Q5, from -6.02 in Q1 to -6.19 in Q20.

Labour. Employment peaks at +1.58 % vs baseline in Q8, from +0.22 in Q1 to -0.08 in Q20. Unemployment peaks at -0.28 pp in Q6, from -0.06 in Q1 to +0.05 in Q20. Real Wages peaks at +4.02 % vs baseline in Q13, from +0.04 in Q1 to +2.48 in Q20.

Prices. The three-year CPI impulse is +4.44 percentage points. CPI Inflation peaks at +0.61 pp in Q4, from +0.18 in Q1 to -0.16 in Q20. Domestic Infl. peaks at +0.43 pp in Q4, from +0.12 in Q1 to -0.11 in Q20. Marginal Cost peaks at +1.60 % vs baseline in Q3, from +1.02 in Q1 to -0.40 in Q20.

Financial conditions. Policy Rate peaks at +2.47 pp (annualized) in Q6, from +0.42 in Q1 to -0.67 in Q20. Real Rate peaks at +0.62 pp (annualized) in Q6, from +0.10 in Q1 to -0.17 in Q20. Govt 3M Yield peaks at +2.47 pp (annualized) in Q6, from +0.42 in Q1 to -0.67 in Q20. Govt 2Y Yield peaks at +2.12 pp (annualized) in Q3, from +1.84 in Q1 to -0.57 in Q20. Govt 5Y Yield peaks at +0.94 pp (annualized) in Q1, from +0.94 in Q1 to -0.33 in Q20. Govt 10Y Yield peaks at +0.32 pp (annualized) in Q1, from +0.32 in Q1 to -0.20 in Q20. Govt 30Y Yield peaks at +0.09 pp (annualized) in Q1, from +0.09 in Q1 to -0.07 in Q20. Bond Price (7y) peaks at -6.17 % vs baseline in Q6, from -1.04 in Q1 to +1.66 in Q20. Bond Price 3M peaks at -0.62 % vs baseline in Q6, from -0.10 in Q1 to +0.17 in Q20. Bond Price 2Y peaks at -4.02 % vs baseline in Q3, from -3.49 in Q1 to +1.08 in Q20. Bond Price 5Y peaks at -4.23 % vs baseline in Q1, from -4.23 in Q1 to +1.49 in Q20. Bond Price 10Y peaks at -2.62 % vs baseline in Q1, from -2.62 in Q1 to +1.67 in Q20. Bond Price 30Y peaks at -1.64 % vs baseline in Q1, from -1.64 in Q1 to +1.28 in Q20. Equity Index peaks at +3.25 % vs baseline in Q3, from +2.38 in Q1 to +0.38 in Q20. VIX peaks at +23.07 index_level in Q6, from +19.31 in Q1 to +18.76 in Q20. Tobin's Q peaks at +4.18 % vs baseline in Q2, from +2.91 in Q1 to -0.54 in Q20. House Prices peaks at +1.76 % vs baseline in Q8, from +0.25 in Q1 to +0.03 in Q20. Bank Equity peaks at +0.18 % vs baseline in Q14, from +0.02 in Q1 to +0.17 in Q20. Bank Credit peaks at +0.05 % vs baseline in Q14, from +0.00 in Q1 to +0.04 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +9.99 % vs baseline in Q5, from +5.98 in Q1 to +6.98 in Q20. vs USD peaks at -9.23 % vs baseline in Q5, from -5.71 in Q1 to -6.55 in Q20.

Commodities. Energy Price peaks at +176.36 USD/bbl (level) in Q4, from +138.90 in Q1 to +122.38 in Q20. Metals Price peaks at +98.20 index (level) in Q1, from +98.20 in Q1 to +93.22 in Q20. Food Price peaks at +112.54 index (level) in Q8, from +101.83 in Q1 to +107.12 in Q20. Gas Price peaks at +7.04 USD/mmBtu (level) in Q4, from +5.91 in Q1 to +5.22 in Q20. Copper Price peaks at +98.42 index (level) in Q1, from +98.42 in Q1 to +94.50 in Q20. Wheat Price peaks at +99.21 index (level) in Q1, from +99.21 in Q1 to +96.05 in Q20. Gold Price peaks at +2444.29 USD/oz (level) in Q8, from +2250.80 in Q1 to +2287.25 in Q20.

Sectoral and capital. Manuf. GDP peaks at +2.31 % vs baseline in Q5, from +1.39 in Q1 to +1.36 in Q20. Services GDP peaks at +1.30 % vs baseline in Q3, from +0.83 in Q1 to -0.34 in Q20. Capital Stock peaks at +0.13 % vs baseline in Q7, from +0.02 in Q1 to +0.01 in Q20.

Timing. The GDP response has mostly faded by Q10 (Q20 is -0.69%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/NG_Y.png)

![CPI Inflation](charts/NG_pi_cpi.png)

![Equity Index](charts/NG_equity.png)

![Gold Price](charts/NG_P_gold.png)

![Energy Price](charts/NG_P_energy.png)

![Food Price](charts/NG_P_food.png)

![Wheat Price](charts/NG_P_wheat.png)

![Copper Price](charts/NG_P_copper.png)

![Metals Price](charts/NG_P_metals.png)

![VIX](charts/NG_vix.png)

![Real Exchange Rate](charts/NG_RER.png)

![NEER](charts/NG_NEER.png)

[Q1–Q20 JSON for Nigeria](numbers/NG.json)

## CH — Switzerland

The main impact of oil at $200 a barrel on Switzerland would be a large drop in GDP of 2.62% by Q15. Equities peak at -9.99% in Q13.

Demand and trade. Consumption peaks at -1.87 % vs baseline in Q18, from -0.55 in Q1 to -1.80 in Q20. Investment peaks at -7.01 % vs baseline in Q10, from -2.87 in Q1 to -5.66 in Q20. Net Exports peaks at -0.71 % vs baseline in Q3, from -0.54 in Q1 to -0.61 in Q20. Gov Spending peaks at +0.52 % vs baseline in Q15, from +0.19 in Q1 to +0.49 in Q20. Gov Debt peaks at -1.59 % vs baseline in Q20, from -0.06 in Q1 to -1.59 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +4.22 % vs baseline in Q6, from +1.85 in Q1 to -0.88 in Q20.

Labour. Employment peaks at -2.78 % vs baseline in Q19, from -0.24 in Q1 to -2.76 in Q20. Unemployment peaks at +1.94 pp in Q19, from +0.15 in Q1 to +1.93 in Q20. Real Wages peaks at -0.85 % vs baseline in Q20, from -0.00 in Q1 to -0.85 in Q20.

Prices. The three-year CPI impulse is +2.19 percentage points. CPI Inflation peaks at +0.52 pp in Q3, from +0.38 in Q1 to -0.23 in Q20. Domestic Infl. peaks at +0.37 pp in Q3, from +0.27 in Q1 to -0.16 in Q20. Marginal Cost peaks at -1.56 % vs baseline in Q15, from -0.57 in Q1 to -1.47 in Q20.

Financial conditions. Policy Rate peaks at -0.75 pp (annualized) in Q17, from +0.14 in Q1 to -0.75 in Q20. Real Rate peaks at -0.20 pp (annualized) in Q18, from +0.03 in Q1 to -0.20 in Q20. Govt 3M Yield peaks at -0.79 pp (annualized) in Q18, from +0.14 in Q1 to -0.79 in Q20. Govt 2Y Yield peaks at -0.78 pp (annualized) in Q17, from +0.43 in Q1 to -0.77 in Q20. Govt 5Y Yield peaks at -0.75 pp (annualized) in Q16, from -0.07 in Q1 to -0.73 in Q20. Govt 10Y Yield peaks at -0.63 pp (annualized) in Q14, from -0.39 in Q1 to -0.58 in Q20. Govt 30Y Yield peaks at -0.31 pp (annualized) in Q12, from -0.27 in Q1 to -0.27 in Q20. Bond Price (7y) peaks at +5.25 % vs baseline in Q17, from -0.96 in Q1 to +5.25 in Q20. Bond Price 3M peaks at +0.20 % vs baseline in Q18, from -0.03 in Q1 to +0.20 in Q20. Bond Price 2Y peaks at +1.49 % vs baseline in Q17, from -0.82 in Q1 to +1.47 in Q20. Bond Price 5Y peaks at +3.39 % vs baseline in Q16, from +0.30 in Q1 to +3.27 in Q20. Bond Price 10Y peaks at +5.20 % vs baseline in Q14, from +3.21 in Q1 to +4.80 in Q20. Bond Price 30Y peaks at +5.52 % vs baseline in Q12, from +4.87 in Q1 to +4.88 in Q20. Equity Index peaks at -9.99 % vs baseline in Q13, from -3.99 in Q1 to -9.08 in Q20. VIX peaks at +23.07 index_level in Q6, from +19.31 in Q1 to +18.76 in Q20. Tobin's Q peaks at -4.91 % vs baseline in Q10, from -2.01 in Q1 to -3.96 in Q20. House Prices peaks at -3.53 % vs baseline in Q20, from -0.12 in Q1 to -3.53 in Q20. Bank Equity peaks at -1.35 % vs baseline in Q18, from -0.08 in Q1 to -1.34 in Q20. Bank Credit peaks at -1.06 % vs baseline in Q18, from -0.06 in Q1 to -1.05 in Q20. Credit Spread peaks at +0.01 pp in Q18, from +0.00 in Q1 to +0.01 in Q20.

Nominal FX. NEER peaks at -2.20 % vs baseline in Q6, from -0.47 in Q1 to +1.24 in Q20. vs USD peaks at +5.04 % vs baseline in Q5, from +2.17 in Q1 to -1.25 in Q20.

Commodities. Energy Price peaks at +176.36 USD/bbl (level) in Q4, from +138.90 in Q1 to +122.38 in Q20. Metals Price peaks at +98.20 index (level) in Q1, from +98.20 in Q1 to +93.22 in Q20. Food Price peaks at +112.54 index (level) in Q8, from +101.83 in Q1 to +107.12 in Q20. Gas Price peaks at +7.04 USD/mmBtu (level) in Q4, from +5.91 in Q1 to +5.22 in Q20. Copper Price peaks at +98.42 index (level) in Q1, from +98.42 in Q1 to +94.50 in Q20. Wheat Price peaks at +99.21 index (level) in Q1, from +99.21 in Q1 to +96.05 in Q20. Gold Price peaks at +2444.29 USD/oz (level) in Q8, from +2250.80 in Q1 to +2287.25 in Q20.

Sectoral and capital. Manuf. GDP peaks at -3.78 % vs baseline in Q5, from -2.07 in Q1 to -1.21 in Q20. Services GDP peaks at -2.08 % vs baseline in Q15, from -0.78 in Q1 to -1.96 in Q20. Capital Stock peaks at -0.62 % vs baseline in Q20, from -0.01 in Q1 to -0.62 in Q20.

Timing. By Q20 GDP is still -2.47% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/CH_Y.png)

![CPI Inflation](charts/CH_pi_cpi.png)

![Equity Index](charts/CH_equity.png)

![Gold Price](charts/CH_P_gold.png)

![Energy Price](charts/CH_P_energy.png)

![Food Price](charts/CH_P_food.png)

![Wheat Price](charts/CH_P_wheat.png)

![Copper Price](charts/CH_P_copper.png)

![Metals Price](charts/CH_P_metals.png)

![VIX](charts/CH_vix.png)

![Gas Price](charts/CH_P_gas.png)

![Investment](charts/CH_I.png)

[Q1–Q20 JSON for Switzerland](numbers/CH.json)

## UK — United Kingdom

The main impact of oil at $200 a barrel on United Kingdom would be a large drop in GDP of 2.37% by Q13. Equities peak at -5.75% in Q9.

Demand and trade. Consumption peaks at -1.49 % vs baseline in Q14, from -0.48 in Q1 to -1.38 in Q20. Investment peaks at -6.99 % vs baseline in Q11, from -2.76 in Q1 to -5.44 in Q20. Net Exports peaks at -0.96 % vs baseline in Q4, from -0.63 in Q1 to -0.79 in Q20. Gov Spending peaks at +0.48 % vs baseline in Q13, from +0.19 in Q1 to +0.43 in Q20. Gov Debt peaks at -0.23 % vs baseline in Q18, from -0.02 in Q1 to -0.22 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +5.50 % vs baseline in Q5, from +2.81 in Q1 to -2.54 in Q20.

Labour. Employment peaks at -2.75 % vs baseline in Q18, from -0.26 in Q1 to -2.71 in Q20. Unemployment peaks at +1.74 pp in Q18, from +0.15 in Q1 to +1.72 in Q20. Real Wages peaks at -1.27 % vs baseline in Q20, from -0.01 in Q1 to -1.27 in Q20.

Prices. The three-year CPI impulse is +2.16 percentage points. CPI Inflation peaks at +0.63 pp in Q2, from +0.47 in Q1 to -0.30 in Q20. Domestic Infl. peaks at +0.44 pp in Q2, from +0.33 in Q1 to -0.21 in Q20. Marginal Cost peaks at -1.40 % vs baseline in Q13, from -0.56 in Q1 to -1.26 in Q20.

Financial conditions. Policy Rate peaks at +0.53 pp (annualized) in Q7, from +0.10 in Q1 to -0.23 in Q20. Real Rate peaks at +0.13 pp (annualized) in Q7, from +0.02 in Q1 to -0.06 in Q20. Govt 3M Yield peaks at +0.53 pp (annualized) in Q7, from +0.10 in Q1 to -0.23 in Q20. Govt 2Y Yield peaks at +0.47 pp (annualized) in Q4, from +0.39 in Q1 to -0.37 in Q20. Govt 5Y Yield peaks at -0.46 pp (annualized) in Q20, from +0.23 in Q1 to -0.46 in Q20. Govt 10Y Yield peaks at -0.46 pp (annualized) in Q20, from -0.12 in Q1 to -0.46 in Q20. Govt 30Y Yield peaks at -0.27 pp (annualized) in Q17, from -0.22 in Q1 to -0.27 in Q20. Bond Price (7y) peaks at -3.72 % vs baseline in Q7, from -0.68 in Q1 to +2.81 in Q20. Bond Price 3M peaks at -0.13 % vs baseline in Q7, from -0.02 in Q1 to +0.06 in Q20. Bond Price 2Y peaks at -0.89 % vs baseline in Q4, from -0.74 in Q1 to +0.70 in Q20. Bond Price 5Y peaks at +2.06 % vs baseline in Q20, from -1.03 in Q1 to +2.06 in Q20. Bond Price 10Y peaks at +3.78 % vs baseline in Q20, from +1.00 in Q1 to +3.78 in Q20. Bond Price 30Y peaks at +4.94 % vs baseline in Q17, from +4.00 in Q1 to +4.91 in Q20. Equity Index peaks at -5.75 % vs baseline in Q9, from -2.57 in Q1 to -4.29 in Q20. VIX peaks at +23.07 index_level in Q6, from +19.31 in Q1 to +18.76 in Q20. Tobin's Q peaks at -4.89 % vs baseline in Q11, from -1.93 in Q1 to -3.81 in Q20. House Prices peaks at -2.99 % vs baseline in Q20, from -0.10 in Q1 to -2.99 in Q20. Bank Equity peaks at -1.07 % vs baseline in Q17, from -0.07 in Q1 to -1.05 in Q20. Bank Credit peaks at -0.85 % vs baseline in Q17, from -0.05 in Q1 to -0.83 in Q20. Credit Spread peaks at +0.01 pp in Q17, from +0.00 in Q1 to +0.01 in Q20.

Nominal FX. NEER peaks at -6.01 % vs baseline in Q5, from -3.00 in Q1 to +1.76 in Q20. vs USD peaks at +6.33 % vs baseline in Q5, from +3.13 in Q1 to -2.91 in Q20.

Commodities. Energy Price peaks at +176.36 USD/bbl (level) in Q4, from +138.90 in Q1 to +122.38 in Q20. Metals Price peaks at +98.20 index (level) in Q1, from +98.20 in Q1 to +93.22 in Q20. Food Price peaks at +112.54 index (level) in Q8, from +101.83 in Q1 to +107.12 in Q20. Gas Price peaks at +7.04 USD/mmBtu (level) in Q4, from +5.91 in Q1 to +5.22 in Q20. Copper Price peaks at +98.42 index (level) in Q1, from +98.42 in Q1 to +94.50 in Q20. Wheat Price peaks at +99.21 index (level) in Q1, from +99.21 in Q1 to +96.05 in Q20. Gold Price peaks at +2444.29 USD/oz (level) in Q8, from +2250.80 in Q1 to +2287.25 in Q20.

Sectoral and capital. Manuf. GDP peaks at -3.59 % vs baseline in Q4, from -2.01 in Q1 to -0.32 in Q20. Services GDP peaks at -1.87 % vs baseline in Q13, from -0.77 in Q1 to -1.69 in Q20. Capital Stock peaks at -0.61 % vs baseline in Q20, from -0.01 in Q1 to -0.61 in Q20.

Timing. By Q20 GDP is still -2.13% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/UK_Y.png)

![CPI Inflation](charts/UK_pi_cpi.png)

![Equity Index](charts/UK_equity.png)

![Gold Price](charts/UK_P_gold.png)

![Energy Price](charts/UK_P_energy.png)

![Food Price](charts/UK_P_food.png)

![Wheat Price](charts/UK_P_wheat.png)

![Copper Price](charts/UK_P_copper.png)

![Metals Price](charts/UK_P_metals.png)

![VIX](charts/UK_vix.png)

![Gas Price](charts/UK_P_gas.png)

![Investment](charts/UK_I.png)

[Q1–Q20 JSON for United Kingdom](numbers/UK.json)

## NL — Netherlands

The main impact of oil at $200 a barrel on Netherlands would be a large drop in GDP of 2.30% by Q15. Equities peak at -5.93% in Q12.

Demand and trade. Consumption peaks at -1.33 % vs baseline in Q17, from -0.42 in Q1 to -1.28 in Q20. Investment peaks at -7.43 % vs baseline in Q8, from -2.76 in Q1 to -4.54 in Q20. Net Exports peaks at +1.64 % vs baseline in Q5, from +0.91 in Q1 to +0.77 in Q20. Gov Spending peaks at +0.57 % vs baseline in Q13, from +0.24 in Q1 to +0.52 in Q20. Gov Debt peaks at +0.61 % vs baseline in Q20, from +0.02 in Q1 to +0.61 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -2.61 % vs baseline in Q5, from -1.47 in Q1 to -2.10 in Q20.

Labour. Employment peaks at -2.33 % vs baseline in Q20, from -0.12 in Q1 to -2.33 in Q20. Unemployment peaks at +1.68 pp in Q19, from +0.12 in Q1 to +1.68 in Q20. Real Wages peaks at +1.14 % vs baseline in Q10, from -0.01 in Q1 to -0.78 in Q20.

Prices. The three-year CPI impulse is +3.34 percentage points. CPI Inflation peaks at +0.81 pp in Q2, from +0.65 in Q1 to -0.20 in Q20. Domestic Infl. peaks at +0.57 pp in Q2, from +0.46 in Q1 to -0.14 in Q20. Marginal Cost peaks at -1.36 % vs baseline in Q15, from -0.45 in Q1 to -1.27 in Q20.

Financial conditions. Policy Rate peaks at +1.72 pp (annualized) in Q6, from +0.43 in Q1 to -0.88 in Q20. Real Rate peaks at +0.43 pp (annualized) in Q6, from +0.11 in Q1 to -0.22 in Q20. Govt 3M Yield peaks at +1.72 pp (annualized) in Q6, from +0.43 in Q1 to -0.88 in Q20. Govt 2Y Yield peaks at +1.46 pp (annualized) in Q3, from +1.35 in Q1 to -1.02 in Q20. Govt 5Y Yield peaks at -0.97 pp (annualized) in Q19, from +0.55 in Q1 to -0.97 in Q20. Govt 10Y Yield peaks at -0.77 pp (annualized) in Q16, from -0.21 in Q1 to -0.75 in Q20. Govt 30Y Yield peaks at -0.34 pp (annualized) in Q15, from -0.22 in Q1 to -0.32 in Q20. Bond Price (7y) peaks at -12.07 % vs baseline in Q6, from -3.04 in Q1 to +6.13 in Q20. Bond Price 3M peaks at -0.43 % vs baseline in Q6, from -0.11 in Q1 to +0.22 in Q20. Bond Price 2Y peaks at -2.78 % vs baseline in Q3, from -2.57 in Q1 to +1.93 in Q20. Bond Price 5Y peaks at +4.36 % vs baseline in Q19, from -2.46 in Q1 to +4.36 in Q20. Bond Price 10Y peaks at +6.33 % vs baseline in Q16, from +1.70 in Q1 to +6.14 in Q20. Bond Price 30Y peaks at +6.13 % vs baseline in Q15, from +3.90 in Q1 to +5.75 in Q20. Equity Index peaks at -5.93 % vs baseline in Q12, from -2.32 in Q1 to -5.05 in Q20. VIX peaks at +23.07 index_level in Q6, from +19.31 in Q1 to +18.76 in Q20. Tobin's Q peaks at -5.20 % vs baseline in Q8, from -1.93 in Q1 to -3.18 in Q20. House Prices peaks at -3.30 % vs baseline in Q20, from -0.10 in Q1 to -3.30 in Q20. Bank Equity peaks at -1.18 % vs baseline in Q19, from -0.06 in Q1 to -1.18 in Q20. Bank Credit peaks at -0.94 % vs baseline in Q19, from -0.05 in Q1 to -0.93 in Q20. Credit Spread peaks at +0.01 pp in Q19, from +0.00 in Q1 to +0.01 in Q20.

Nominal FX. NEER peaks at +2.27 % vs baseline in Q4, from +1.36 in Q1 to +1.02 in Q20. vs USD peaks at -2.63 % vs baseline in Q17, from -1.15 in Q1 to -2.46 in Q20.

Commodities. Energy Price peaks at +176.36 USD/bbl (level) in Q4, from +138.90 in Q1 to +122.38 in Q20. Metals Price peaks at +98.20 index (level) in Q1, from +98.20 in Q1 to +93.22 in Q20. Food Price peaks at +112.54 index (level) in Q8, from +101.83 in Q1 to +107.12 in Q20. Gas Price peaks at +7.04 USD/mmBtu (level) in Q4, from +5.91 in Q1 to +5.22 in Q20. Copper Price peaks at +98.42 index (level) in Q1, from +98.42 in Q1 to +94.50 in Q20. Wheat Price peaks at +99.21 index (level) in Q1, from +99.21 in Q1 to +96.05 in Q20. Gold Price peaks at +2444.29 USD/oz (level) in Q8, from +2250.80 in Q1 to +2287.25 in Q20.

Sectoral and capital. Manuf. GDP peaks at -1.24 % vs baseline in Q4, from -0.76 in Q1 to -0.52 in Q20. Services GDP peaks at -1.72 % vs baseline in Q15, from -0.60 in Q1 to -1.60 in Q20. Capital Stock peaks at -0.61 % vs baseline in Q20, from -0.01 in Q1 to -0.61 in Q20.

Timing. By Q20 GDP is still -2.14% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/NL_Y.png)

![CPI Inflation](charts/NL_pi_cpi.png)

![Equity Index](charts/NL_equity.png)

![Gold Price](charts/NL_P_gold.png)

![Energy Price](charts/NL_P_energy.png)

![Food Price](charts/NL_P_food.png)

![Wheat Price](charts/NL_P_wheat.png)

![Copper Price](charts/NL_P_copper.png)

![Metals Price](charts/NL_P_metals.png)

![VIX](charts/NL_vix.png)

![Bond Price (7y)](charts/NL_Q_B.png)

![Investment](charts/NL_I.png)

[Q1–Q20 JSON for Netherlands](numbers/NL.json)

## BR — Brazil

The main impact of oil at $200 a barrel on Brazil would be a large drop in GDP of 2.16% by Q14. Equities peak at -3.92% in Q11.

Demand and trade. Consumption peaks at -1.17 % vs baseline in Q15, from -0.16 in Q1 to -0.95 in Q20. Investment peaks at -6.74 % vs baseline in Q8, from -1.61 in Q1 to -1.83 in Q20. Net Exports peaks at +2.57 % vs baseline in Q5, from +1.48 in Q1 to +1.29 in Q20. Gov Spending peaks at +0.81 % vs baseline in Q11, from +0.30 in Q1 to +0.56 in Q20. Gov Debt peaks at -0.56 % vs baseline in Q20, from -0.00 in Q1 to -0.56 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -7.46 % vs baseline in Q6, from -3.09 in Q1 to -2.65 in Q20.

Labour. Employment peaks at -2.05 % vs baseline in Q19, from -0.01 in Q1 to -2.05 in Q20. Unemployment peaks at +0.45 pp in Q16, from +0.01 in Q1 to +0.40 in Q20. Real Wages peaks at -1.82 % vs baseline in Q20, from -0.00 in Q1 to -1.82 in Q20.

Prices. The three-year CPI impulse is +2.17 percentage points. CPI Inflation peaks at +0.43 pp in Q2, from +0.32 in Q1 to -0.20 in Q20. Domestic Infl. peaks at +0.30 pp in Q2, from +0.23 in Q1 to -0.14 in Q20. Marginal Cost peaks at -1.28 % vs baseline in Q14, from -0.07 in Q1 to -0.93 in Q20.

Financial conditions. Policy Rate peaks at +2.67 pp (annualized) in Q5, from +0.85 in Q1 to -1.58 in Q20. Real Rate peaks at +0.67 pp (annualized) in Q5, from +0.21 in Q1 to -0.39 in Q20. Govt 3M Yield peaks at +2.67 pp (annualized) in Q5, from +0.85 in Q1 to -1.58 in Q20. Govt 2Y Yield peaks at +2.14 pp (annualized) in Q2, from +2.08 in Q1 to -1.45 in Q20. Govt 5Y Yield peaks at -1.24 pp (annualized) in Q14, from +0.46 in Q1 to -1.04 in Q20. Govt 10Y Yield peaks at -0.83 pp (annualized) in Q13, from -0.26 in Q1 to -0.66 in Q20. Govt 30Y Yield peaks at -0.32 pp (annualized) in Q12, from -0.16 in Q1 to -0.26 in Q20. Bond Price (7y) peaks at -11.13 % vs baseline in Q5, from -3.56 in Q1 to +6.58 in Q20. Bond Price 3M peaks at -0.67 % vs baseline in Q5, from -0.21 in Q1 to +0.39 in Q20. Bond Price 2Y peaks at -4.06 % vs baseline in Q2, from -3.96 in Q1 to +2.75 in Q20. Bond Price 5Y peaks at +5.60 % vs baseline in Q14, from -2.08 in Q1 to +4.69 in Q20. Bond Price 10Y peaks at +6.78 % vs baseline in Q13, from +2.14 in Q1 to +5.38 in Q20. Bond Price 30Y peaks at +5.81 % vs baseline in Q12, from +2.92 in Q1 to +4.60 in Q20. Equity Index peaks at -3.92 % vs baseline in Q11, from -0.59 in Q1 to -1.65 in Q20. VIX peaks at +23.07 index_level in Q6, from +19.31 in Q1 to +18.76 in Q20. Tobin's Q peaks at -4.72 % vs baseline in Q8, from -1.13 in Q1 to -1.28 in Q20. House Prices peaks at -2.59 % vs baseline in Q20, from -0.04 in Q1 to -2.59 in Q20. Bank Equity peaks at -0.12 % vs baseline in Q19, from -0.01 in Q1 to -0.12 in Q20. Bank Credit peaks at -0.10 % vs baseline in Q19, from -0.00 in Q1 to -0.10 in Q20. Credit Spread peaks at +0.00 pp in Q19, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +6.85 % vs baseline in Q6, from +2.71 in Q1 to +2.52 in Q20. vs USD peaks at -6.67 % vs baseline in Q6, from -2.77 in Q1 to -3.01 in Q20.

Commodities. Energy Price peaks at +176.36 USD/bbl (level) in Q4, from +138.90 in Q1 to +122.38 in Q20. Metals Price peaks at +98.20 index (level) in Q1, from +98.20 in Q1 to +93.22 in Q20. Food Price peaks at +112.54 index (level) in Q8, from +101.83 in Q1 to +107.12 in Q20. Gas Price peaks at +7.04 USD/mmBtu (level) in Q4, from +5.91 in Q1 to +5.22 in Q20. Copper Price peaks at +98.42 index (level) in Q1, from +98.42 in Q1 to +94.50 in Q20. Wheat Price peaks at +99.21 index (level) in Q1, from +99.21 in Q1 to +96.05 in Q20. Gold Price peaks at +2444.29 USD/oz (level) in Q8, from +2250.80 in Q1 to +2287.25 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.48 % vs baseline in Q16, from -0.28 in Q1 to -0.37 in Q20. Services GDP peaks at -1.43 % vs baseline in Q14, from -0.10 in Q1 to -1.04 in Q20. Capital Stock peaks at -0.47 % vs baseline in Q20, from -0.01 in Q1 to -0.47 in Q20.

Timing. By Q20 GDP is still -1.57% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/BR_Y.png)

![CPI Inflation](charts/BR_pi_cpi.png)

![Equity Index](charts/BR_equity.png)

![Gold Price](charts/BR_P_gold.png)

![Energy Price](charts/BR_P_energy.png)

![Food Price](charts/BR_P_food.png)

![Wheat Price](charts/BR_P_wheat.png)

![Copper Price](charts/BR_P_copper.png)

![Metals Price](charts/BR_P_metals.png)

![VIX](charts/BR_vix.png)

![Bond Price (7y)](charts/BR_Q_B.png)

![Real Exchange Rate](charts/BR_RER.png)

[Q1–Q20 JSON for Brazil](numbers/BR.json)

## AU — Australia

The main impact of oil at $200 a barrel on Australia would be a large drop in GDP of 1.91% by Q13. Equities peak at -4.77% in Q8.

Demand and trade. Consumption peaks at -1.23 % vs baseline in Q14, from -0.49 in Q1 to -1.07 in Q20. Investment peaks at -5.93 % vs baseline in Q5, from -2.85 in Q1 to -1.93 in Q20. Net Exports peaks at -1.39 % vs baseline in Q4, from -0.78 in Q1 to -0.93 in Q20. Gov Spending peaks at +0.27 % vs baseline in Q11, from +0.15 in Q1 to +0.22 in Q20. Gov Debt peaks at -1.20 % vs baseline in Q20, from -0.05 in Q1 to -1.20 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +6.45 % vs baseline in Q11, from +2.65 in Q1 to +4.36 in Q20.

Labour. Employment peaks at -2.15 % vs baseline in Q16, from -0.24 in Q1 to -2.05 in Q20. Unemployment peaks at +1.39 pp in Q17, from +0.14 in Q1 to +1.33 in Q20. Real Wages peaks at -1.81 % vs baseline in Q20, from -0.01 in Q1 to -1.81 in Q20.

Prices. The three-year CPI impulse is +1.98 percentage points. CPI Inflation peaks at +0.47 pp in Q2, from +0.36 in Q1 to -0.16 in Q20. Domestic Infl. peaks at +0.33 pp in Q2, from +0.25 in Q1 to -0.11 in Q20. Marginal Cost peaks at -1.13 % vs baseline in Q13, from -0.52 in Q1 to -0.92 in Q20.

Financial conditions. Policy Rate peaks at -1.50 pp (annualized) in Q20, from +0.28 in Q1 to -1.50 in Q20. Real Rate peaks at -0.38 pp (annualized) in Q20, from +0.07 in Q1 to -0.38 in Q20. Govt 3M Yield peaks at -1.50 pp (annualized) in Q20, from +0.28 in Q1 to -1.50 in Q20. Govt 2Y Yield peaks at -1.49 pp (annualized) in Q19, from +0.74 in Q1 to -1.48 in Q20. Govt 5Y Yield peaks at -1.31 pp (annualized) in Q15, from -0.17 in Q1 to -1.22 in Q20. Govt 10Y Yield peaks at -0.98 pp (annualized) in Q13, from -0.67 in Q1 to -0.85 in Q20. Govt 30Y Yield peaks at -0.41 pp (annualized) in Q11, from -0.36 in Q1 to -0.34 in Q20. Bond Price (7y) peaks at +9.38 % vs baseline in Q20, from -1.75 in Q1 to +9.38 in Q20. Bond Price 3M peaks at +0.38 % vs baseline in Q20, from -0.07 in Q1 to +0.38 in Q20. Bond Price 2Y peaks at +2.83 % vs baseline in Q19, from -1.40 in Q1 to +2.81 in Q20. Bond Price 5Y peaks at +5.91 % vs baseline in Q15, from +0.76 in Q1 to +5.47 in Q20. Bond Price 10Y peaks at +8.05 % vs baseline in Q13, from +5.52 in Q1 to +6.96 in Q20. Bond Price 30Y peaks at +7.41 % vs baseline in Q11, from +6.41 in Q1 to +6.20 in Q20. Equity Index peaks at -4.77 % vs baseline in Q8, from -2.40 in Q1 to -2.87 in Q20. VIX peaks at +23.07 index_level in Q6, from +19.31 in Q1 to +18.76 in Q20. Tobin's Q peaks at -4.15 % vs baseline in Q5, from -1.99 in Q1 to -1.35 in Q20. House Prices peaks at -2.33 % vs baseline in Q20, from -0.10 in Q1 to -2.33 in Q20. Bank Equity peaks at -0.78 % vs baseline in Q18, from -0.06 in Q1 to -0.78 in Q20. Bank Credit peaks at -0.62 % vs baseline in Q18, from -0.04 in Q1 to -0.62 in Q20. Credit Spread peaks at +0.01 pp in Q18, from +0.00 in Q1 to +0.01 in Q20.

Nominal FX. NEER peaks at -5.19 % vs baseline in Q12, from -1.69 in Q1 to -3.62 in Q20. vs USD peaks at +7.12 % vs baseline in Q6, from +2.97 in Q1 to +4.00 in Q20.

Commodities. Energy Price peaks at +176.36 USD/bbl (level) in Q4, from +138.90 in Q1 to +122.38 in Q20. Metals Price peaks at +98.20 index (level) in Q1, from +98.20 in Q1 to +93.22 in Q20. Food Price peaks at +112.54 index (level) in Q8, from +101.83 in Q1 to +107.12 in Q20. Gas Price peaks at +7.04 USD/mmBtu (level) in Q4, from +5.91 in Q1 to +5.22 in Q20. Copper Price peaks at +98.42 index (level) in Q1, from +98.42 in Q1 to +94.50 in Q20. Wheat Price peaks at +99.21 index (level) in Q1, from +99.21 in Q1 to +96.05 in Q20. Gold Price peaks at +2444.29 USD/oz (level) in Q8, from +2250.80 in Q1 to +2287.25 in Q20.

Sectoral and capital. Manuf. GDP peaks at -3.54 % vs baseline in Q5, from -1.81 in Q1 to -2.18 in Q20. Services GDP peaks at -1.37 % vs baseline in Q13, from -0.64 in Q1 to -1.11 in Q20. Capital Stock peaks at -0.44 % vs baseline in Q20, from -0.01 in Q1 to -0.44 in Q20.

Timing. By Q20 GDP is still -1.55% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/AU_Y.png)

![CPI Inflation](charts/AU_pi_cpi.png)

![Equity Index](charts/AU_equity.png)

![Gold Price](charts/AU_P_gold.png)

![Energy Price](charts/AU_P_energy.png)

![Food Price](charts/AU_P_food.png)

![Wheat Price](charts/AU_P_wheat.png)

![Copper Price](charts/AU_P_copper.png)

![Metals Price](charts/AU_P_metals.png)

![VIX](charts/AU_vix.png)

![Bond Price (7y)](charts/AU_Q_B.png)

![Bond Price 10Y](charts/AU_Q_B_10y.png)

[Q1–Q20 JSON for Australia](numbers/AU.json)

## US — United States

The main impact of oil at $200 a barrel on the United States would be a large drop in GDP of 1.71% by Q12. Equities peak at -5.41% in Q9.

Demand and trade. Consumption peaks at -1.10 % vs baseline in Q13, from -0.35 in Q1 to -0.81 in Q20. Investment peaks at -5.94 % vs baseline in Q6, from -2.17 in Q1 to -0.63 in Q20. Net Exports peaks at +0.18 % vs baseline in Q12, from +0.02 in Q1 to +0.14 in Q20. Gov Spending peaks at +0.33 % vs baseline in Q12, from +0.10 in Q1 to +0.22 in Q20. Gov Debt peaks at -0.35 % vs baseline in Q14, from -0.04 in Q1 to -0.28 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -0.83 % vs baseline in Q5, from -0.32 in Q1 to +0.36 in Q20.

Labour. Employment peaks at -1.89 % vs baseline in Q15, from -0.17 in Q1 to -1.60 in Q20. Unemployment peaks at +1.18 pp in Q15, from +0.08 in Q1 to +1.06 in Q20. Real Wages peaks at +0.86 % vs baseline in Q10, from -0.00 in Q1 to -0.51 in Q20.

Prices. The three-year CPI impulse is +2.69 percentage points. CPI Inflation peaks at +0.58 pp in Q2, from +0.44 in Q1 to -0.18 in Q20. Domestic Infl. peaks at +0.40 pp in Q2, from +0.31 in Q1 to -0.13 in Q20. Marginal Cost peaks at -1.01 % vs baseline in Q12, from -0.31 in Q1 to -0.67 in Q20.

Financial conditions. Policy Rate peaks at +1.62 pp (annualized) in Q5, from +0.48 in Q1 to -1.58 in Q20. Real Rate peaks at +0.41 pp (annualized) in Q5, from +0.12 in Q1 to -0.39 in Q20. Govt 3M Yield peaks at +1.62 pp (annualized) in Q5, from +0.48 in Q1 to -1.58 in Q20. Govt 2Y Yield peaks at -1.52 pp (annualized) in Q17, from +1.23 in Q1 to -1.44 in Q20. Govt 5Y Yield peaks at -1.26 pp (annualized) in Q14, from +0.01 in Q1 to -1.05 in Q20. Govt 10Y Yield peaks at -0.85 pp (annualized) in Q12, from -0.49 in Q1 to -0.66 in Q20. Govt 30Y Yield peaks at -0.33 pp (annualized) in Q11, from -0.24 in Q1 to -0.25 in Q20. Bond Price (7y) peaks at -10.68 % vs baseline in Q5, from -3.17 in Q1 to +10.38 in Q20. Bond Price 3M peaks at -0.41 % vs baseline in Q5, from -0.12 in Q1 to +0.39 in Q20. Bond Price 2Y peaks at +2.88 % vs baseline in Q17, from -2.35 in Q1 to +2.74 in Q20. Bond Price 5Y peaks at +5.66 % vs baseline in Q14, from -0.04 in Q1 to +4.71 in Q20. Bond Price 10Y peaks at +6.93 % vs baseline in Q12, from +4.02 in Q1 to +5.39 in Q20. Bond Price 30Y peaks at +5.90 % vs baseline in Q11, from +4.24 in Q1 to +4.57 in Q20. Equity Index peaks at -5.41 % vs baseline in Q9, from -1.94 in Q1 to -2.34 in Q20. VIX peaks at +23.07 index_level in Q6, from +19.31 in Q1 to +18.76 in Q20. Tobin's Q peaks at -4.16 % vs baseline in Q6, from -1.52 in Q1 to -0.44 in Q20. House Prices peaks at -1.78 % vs baseline in Q19, from -0.06 in Q1 to -1.77 in Q20. Bank Equity peaks at -0.56 % vs baseline in Q17, from -0.03 in Q1 to -0.55 in Q20. Bank Credit peaks at -0.45 % vs baseline in Q17, from -0.03 in Q1 to -0.44 in Q20. Credit Spread peaks at +0.01 pp in Q17, from +0.00 in Q1 to +0.01 in Q20.

Nominal FX. NEER peaks at -8.36 % vs baseline in Q4, from -5.08 in Q1 to -5.63 in Q20. vs USD peaks at -8.36 % vs baseline in Q4, from -5.08 in Q1 to -5.63 in Q20.

Commodities. Energy Price peaks at +176.36 USD/bbl (level) in Q4, from +138.90 in Q1 to +122.38 in Q20. Metals Price peaks at +98.20 index (level) in Q1, from +98.20 in Q1 to +93.22 in Q20. Food Price peaks at +112.54 index (level) in Q8, from +101.83 in Q1 to +107.12 in Q20. Gas Price peaks at +7.04 USD/mmBtu (level) in Q4, from +5.91 in Q1 to +5.22 in Q20. Copper Price peaks at +98.42 index (level) in Q1, from +98.42 in Q1 to +94.50 in Q20. Wheat Price peaks at +99.21 index (level) in Q1, from +99.21 in Q1 to +96.05 in Q20. Gold Price peaks at +2444.29 USD/oz (level) in Q8, from +2250.80 in Q1 to +2287.25 in Q20.

Sectoral and capital. Manuf. GDP peaks at -1.69 % vs baseline in Q4, from -1.06 in Q1 to -1.07 in Q20. Services GDP peaks at -1.32 % vs baseline in Q12, from -0.42 in Q1 to -0.87 in Q20. Capital Stock peaks at -0.38 % vs baseline in Q20, from -0.01 in Q1 to -0.38 in Q20.

Timing. By Q20 GDP is still -1.13% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/US_Y.png)

![CPI Inflation](charts/US_pi_cpi.png)

![Equity Index](charts/US_equity.png)

![Gold Price](charts/US_P_gold.png)

![Energy Price](charts/US_P_energy.png)

![Food Price](charts/US_P_food.png)

![Wheat Price](charts/US_P_wheat.png)

![Copper Price](charts/US_P_copper.png)

![Metals Price](charts/US_P_metals.png)

![VIX](charts/US_vix.png)

![Bond Price (7y)](charts/US_Q_B.png)

![NEER](charts/US_NEER.png)

[Q1–Q20 JSON for United States](numbers/US.json)

## CA — Canada

The main impact of oil at $200 a barrel on Canada would be a large rise in GDP of 1.56% by Q3. Equities peak at +3.46% in Q3.

Demand and trade. Consumption peaks at +0.97 % vs baseline in Q4, from +0.47 in Q1 to +0.13 in Q20. Investment peaks at +2.84 % vs baseline in Q2, from +2.08 in Q1 to +1.38 in Q20. Net Exports peaks at +5.64 % vs baseline in Q4, from +3.51 in Q1 to +1.80 in Q20. Gov Spending peaks at +1.21 % vs baseline in Q5, from +0.72 in Q1 to +0.63 in Q20. Gov Debt peaks at +0.22 % vs baseline in Q10, from +0.03 in Q1 to +0.15 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -44.13 % vs baseline in Q4, from -26.25 in Q1 to -23.88 in Q20.

Labour. Employment peaks at +1.40 % vs baseline in Q6, from +0.31 in Q1 to +0.23 in Q20. Unemployment peaks at -0.70 pp in Q6, from -0.16 in Q1 to -0.12 in Q20. Real Wages peaks at +1.58 % vs baseline in Q14, from +0.01 in Q1 to +1.33 in Q20.

Prices. The three-year CPI impulse is +1.11 percentage points. CPI Inflation peaks at +0.37 pp in Q2, from +0.28 in Q1 to -0.11 in Q20. Domestic Infl. peaks at +0.26 pp in Q2, from +0.20 in Q1 to -0.08 in Q20. Marginal Cost peaks at +0.96 % vs baseline in Q3, from +0.62 in Q1 to +0.13 in Q20.

Financial conditions. Policy Rate peaks at +2.03 pp (annualized) in Q5, from +0.53 in Q1 to -0.49 in Q20. Real Rate peaks at +0.51 pp (annualized) in Q5, from +0.13 in Q1 to -0.12 in Q20. Govt 3M Yield peaks at +2.03 pp (annualized) in Q5, from +0.53 in Q1 to -0.49 in Q20. Govt 2Y Yield peaks at +1.70 pp (annualized) in Q2, from +1.59 in Q1 to -0.43 in Q20. Govt 5Y Yield peaks at +0.76 pp (annualized) in Q1, from +0.76 in Q1 to -0.20 in Q20. Govt 10Y Yield peaks at +0.29 pp (annualized) in Q1, from +0.29 in Q1 to -0.04 in Q20. Govt 30Y Yield peaks at +0.13 pp (annualized) in Q1, from +0.13 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at -12.06 % vs baseline in Q5, from -3.16 in Q1 to +2.91 in Q20. Bond Price 3M peaks at -0.51 % vs baseline in Q5, from -0.13 in Q1 to +0.12 in Q20. Bond Price 2Y peaks at -3.24 % vs baseline in Q2, from -3.03 in Q1 to +0.81 in Q20. Bond Price 5Y peaks at -3.42 % vs baseline in Q1, from -3.42 in Q1 to +0.92 in Q20. Bond Price 10Y peaks at -2.40 % vs baseline in Q1, from -2.40 in Q1 to +0.36 in Q20. Bond Price 30Y peaks at -2.33 % vs baseline in Q1, from -2.33 in Q1 to +0.03 in Q20. Equity Index peaks at +3.46 % vs baseline in Q3, from +2.43 in Q1 to +1.52 in Q20. VIX peaks at +23.07 index_level in Q6, from +19.31 in Q1 to +18.76 in Q20. Tobin's Q peaks at +1.99 % vs baseline in Q2, from +1.46 in Q1 to +0.96 in Q20. House Prices peaks at +0.81 % vs baseline in Q9, from +0.11 in Q1 to +0.65 in Q20. Bank Equity peaks at +0.12 % vs baseline in Q10, from +0.01 in Q1 to +0.09 in Q20. Bank Credit peaks at +0.05 % vs baseline in Q10, from +0.01 in Q1 to +0.04 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +43.60 % vs baseline in Q4, from +26.06 in Q1 to +23.93 in Q20. vs USD peaks at -43.33 % vs baseline in Q4, from -25.93 in Q1 to -24.25 in Q20.

Commodities. Energy Price peaks at +176.36 USD/bbl (level) in Q4, from +138.90 in Q1 to +122.38 in Q20. Metals Price peaks at +98.20 index (level) in Q1, from +98.20 in Q1 to +93.22 in Q20. Food Price peaks at +112.54 index (level) in Q8, from +101.83 in Q1 to +107.12 in Q20. Gas Price peaks at +7.04 USD/mmBtu (level) in Q4, from +5.91 in Q1 to +5.22 in Q20. Copper Price peaks at +98.42 index (level) in Q1, from +98.42 in Q1 to +94.50 in Q20. Wheat Price peaks at +99.21 index (level) in Q1, from +99.21 in Q1 to +96.05 in Q20. Gold Price peaks at +2444.29 USD/oz (level) in Q8, from +2250.80 in Q1 to +2287.25 in Q20.

Sectoral and capital. Manuf. GDP peaks at +11.78 % vs baseline in Q4, from +7.00 in Q1 to +6.44 in Q20. Services GDP peaks at +1.08 % vs baseline in Q3, from +0.70 in Q1 to +0.14 in Q20. Capital Stock peaks at +0.07 % vs baseline in Q20, from +0.01 in Q1 to +0.07 in Q20.

Timing. The GDP response has mostly faded by Q11 (Q20 is +0.20%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/CA_Y.png)

![CPI Inflation](charts/CA_pi_cpi.png)

![Equity Index](charts/CA_equity.png)

![Gold Price](charts/CA_P_gold.png)

![Energy Price](charts/CA_P_energy.png)

![Food Price](charts/CA_P_food.png)

![Wheat Price](charts/CA_P_wheat.png)

![Copper Price](charts/CA_P_copper.png)

![Metals Price](charts/CA_P_metals.png)

![Real Exchange Rate](charts/CA_RER.png)

![NEER](charts/CA_NEER.png)

![vs USD](charts/CA_USD.png)

[Q1–Q20 JSON for Canada](numbers/CA.json)

## MX — Mexico

The main impact of oil at $200 a barrel on Mexico would be a large drop in GDP of 1.52% by Q12. Equities peak at -2.71% in Q9.

Demand and trade. Consumption peaks at -0.84 % vs baseline in Q14, from -0.21 in Q1 to -0.59 in Q20. Investment peaks at -5.32 % vs baseline in Q7, from -1.67 in Q1 to -0.60 in Q20. Net Exports peaks at +2.18 % vs baseline in Q4, from +1.42 in Q1 to +0.59 in Q20. Gov Spending peaks at +0.71 % vs baseline in Q6, from +0.41 in Q1 to +0.40 in Q20. Gov Debt peaks at -2.18 % vs baseline in Q20, from -0.04 in Q1 to -2.18 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -23.26 % vs baseline in Q4, from -13.64 in Q1 to -12.37 in Q20.

Labour. Employment peaks at -1.42 % vs baseline in Q18, from -0.04 in Q1 to -1.37 in Q20. Unemployment peaks at +0.14 pp in Q14, from +0.01 in Q1 to +0.10 in Q20. Real Wages peaks at -1.50 % vs baseline in Q20, from -0.00 in Q1 to -1.50 in Q20.

Prices. The three-year CPI impulse is +1.49 percentage points. CPI Inflation peaks at +0.37 pp in Q2, from +0.29 in Q1 to -0.18 in Q20. Domestic Infl. peaks at +0.26 pp in Q2, from +0.20 in Q1 to -0.12 in Q20. Marginal Cost peaks at -0.89 % vs baseline in Q12, from -0.16 in Q1 to -0.51 in Q20.

Financial conditions. Policy Rate peaks at +1.93 pp (annualized) in Q5, from +0.61 in Q1 to -1.11 in Q20. Real Rate peaks at +0.48 pp (annualized) in Q5, from +0.15 in Q1 to -0.28 in Q20. Govt 3M Yield peaks at +1.93 pp (annualized) in Q5, from +0.61 in Q1 to -1.11 in Q20. Govt 2Y Yield peaks at +1.55 pp (annualized) in Q2, from +1.51 in Q1 to -1.00 in Q20. Govt 5Y Yield peaks at -0.85 pp (annualized) in Q14, from +0.36 in Q1 to -0.69 in Q20. Govt 10Y Yield peaks at -0.53 pp (annualized) in Q13, from -0.14 in Q1 to -0.40 in Q20. Govt 30Y Yield peaks at -0.19 pp (annualized) in Q12, from -0.08 in Q1 to -0.14 in Q20. Bond Price (7y) peaks at -8.02 % vs baseline in Q5, from -2.53 in Q1 to +4.64 in Q20. Bond Price 3M peaks at -0.48 % vs baseline in Q5, from -0.15 in Q1 to +0.28 in Q20. Bond Price 2Y peaks at -2.95 % vs baseline in Q2, from -2.86 in Q1 to +1.90 in Q20. Bond Price 5Y peaks at +3.80 % vs baseline in Q14, from -1.63 in Q1 to +3.09 in Q20. Bond Price 10Y peaks at +4.36 % vs baseline in Q13, from +1.16 in Q1 to +3.27 in Q20. Bond Price 30Y peaks at +3.35 % vs baseline in Q12, from +1.40 in Q1 to +2.49 in Q20. Equity Index peaks at -2.71 % vs baseline in Q9, from -0.78 in Q1 to -0.34 in Q20. VIX peaks at +23.07 index_level in Q6, from +19.31 in Q1 to +18.76 in Q20. Tobin's Q peaks at -3.72 % vs baseline in Q7, from -1.17 in Q1 to -0.42 in Q20. House Prices peaks at -2.05 % vs baseline in Q18, from -0.06 in Q1 to -2.02 in Q20. Bank Equity peaks at -0.28 % vs baseline in Q20, from -0.01 in Q1 to -0.28 in Q20. Bank Credit peaks at -0.27 % vs baseline in Q20, from -0.01 in Q1 to -0.27 in Q20. Credit Spread peaks at +0.02 pp in Q20, from +0.00 in Q1 to +0.02 in Q20.

Nominal FX. NEER peaks at +23.35 % vs baseline in Q4, from +13.82 in Q1 to +12.89 in Q20. vs USD peaks at -22.46 % vs baseline in Q4, from -13.32 in Q1 to -12.73 in Q20.

Commodities. Energy Price peaks at +176.36 USD/bbl (level) in Q4, from +138.90 in Q1 to +122.38 in Q20. Metals Price peaks at +98.20 index (level) in Q1, from +98.20 in Q1 to +93.22 in Q20. Food Price peaks at +112.54 index (level) in Q8, from +101.83 in Q1 to +107.12 in Q20. Gas Price peaks at +7.04 USD/mmBtu (level) in Q4, from +5.91 in Q1 to +5.22 in Q20. Copper Price peaks at +98.42 index (level) in Q1, from +98.42 in Q1 to +94.50 in Q20. Wheat Price peaks at +99.21 index (level) in Q1, from +99.21 in Q1 to +96.05 in Q20. Gold Price peaks at +2444.29 USD/oz (level) in Q8, from +2250.80 in Q1 to +2287.25 in Q20.

Sectoral and capital. Manuf. GDP peaks at +4.41 % vs baseline in Q4, from +2.54 in Q1 to +2.43 in Q20. Services GDP peaks at -0.92 % vs baseline in Q12, from -0.18 in Q1 to -0.53 in Q20. Capital Stock peaks at -0.35 % vs baseline in Q20, from -0.01 in Q1 to -0.35 in Q20.

Timing. By Q20 GDP is still -0.88% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/MX_Y.png)

![CPI Inflation](charts/MX_pi_cpi.png)

![Equity Index](charts/MX_equity.png)

![Gold Price](charts/MX_P_gold.png)

![Energy Price](charts/MX_P_energy.png)

![Food Price](charts/MX_P_food.png)

![Wheat Price](charts/MX_P_wheat.png)

![Copper Price](charts/MX_P_copper.png)

![Metals Price](charts/MX_P_metals.png)

![NEER](charts/MX_NEER.png)

![Real Exchange Rate](charts/MX_RER.png)

![VIX](charts/MX_vix.png)

[Q1–Q20 JSON for Mexico](numbers/MX.json)

## MY — Malaysia

The main impact of oil at $200 a barrel on Malaysia would be a large drop in GDP of 1.12% by Q12. Equities peak at -2.98% in Q9.

Demand and trade. Consumption peaks at -0.74 % vs baseline in Q13, from -0.21 in Q1 to -0.48 in Q20. Investment peaks at -3.58 % vs baseline in Q7, from -1.34 in Q1 to -0.36 in Q20. Net Exports peaks at +2.63 % vs baseline in Q4, from +1.60 in Q1 to +0.35 in Q20. Gov Spending peaks at +0.75 % vs baseline in Q5, from +0.43 in Q1 to +0.39 in Q20. Gov Debt peaks at -1.92 % vs baseline in Q20, from -0.05 in Q1 to -1.92 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -11.01 % vs baseline in Q4, from -6.51 in Q1 to -7.87 in Q20.

Labour. Employment peaks at -1.08 % vs baseline in Q16, from -0.06 in Q1 to -0.98 in Q20. Unemployment peaks at +0.26 pp in Q14, from +0.02 in Q1 to +0.20 in Q20. Real Wages peaks at -1.47 % vs baseline in Q20, from -0.00 in Q1 to -1.47 in Q20.

Prices. The three-year CPI impulse is +1.19 percentage points. CPI Inflation peaks at +0.50 pp in Q2, from +0.42 in Q1 to -0.16 in Q20. Domestic Infl. peaks at +0.35 pp in Q2, from +0.29 in Q1 to -0.11 in Q20. Marginal Cost peaks at -0.65 % vs baseline in Q12, from -0.20 in Q1 to -0.35 in Q20.

Financial conditions. Policy Rate peaks at +0.92 pp (annualized) in Q5, from +0.27 in Q1 to -0.79 in Q20. Real Rate peaks at +0.23 pp (annualized) in Q5, from +0.07 in Q1 to -0.20 in Q20. Govt 3M Yield peaks at +0.92 pp (annualized) in Q5, from +0.27 in Q1 to -0.79 in Q20. Govt 2Y Yield peaks at -0.76 pp (annualized) in Q17, from +0.71 in Q1 to -0.71 in Q20. Govt 5Y Yield peaks at -0.61 pp (annualized) in Q14, from +0.06 in Q1 to -0.48 in Q20. Govt 10Y Yield peaks at -0.38 pp (annualized) in Q12, from -0.19 in Q1 to -0.28 in Q20. Govt 30Y Yield peaks at -0.13 pp (annualized) in Q12, from -0.08 in Q1 to -0.10 in Q20. Bond Price (7y) peaks at -3.85 % vs baseline in Q5, from -1.14 in Q1 to +3.31 in Q20. Bond Price 3M peaks at -0.23 % vs baseline in Q5, from -0.07 in Q1 to +0.20 in Q20. Bond Price 2Y peaks at +1.44 % vs baseline in Q17, from -1.35 in Q1 to +1.35 in Q20. Bond Price 5Y peaks at +2.74 % vs baseline in Q14, from -0.29 in Q1 to +2.17 in Q20. Bond Price 10Y peaks at +3.09 % vs baseline in Q12, from +1.58 in Q1 to +2.26 in Q20. Bond Price 30Y peaks at +2.39 % vs baseline in Q12, from +1.43 in Q1 to +1.74 in Q20. Equity Index peaks at -2.98 % vs baseline in Q9, from -1.13 in Q1 to -0.62 in Q20. VIX peaks at +23.07 index_level in Q6, from +19.31 in Q1 to +18.76 in Q20. Tobin's Q peaks at -2.51 % vs baseline in Q7, from -0.94 in Q1 to -0.26 in Q20. House Prices peaks at -1.66 % vs baseline in Q18, from -0.07 in Q1 to -1.62 in Q20. Bank Equity peaks at -0.38 % vs baseline in Q20, from -0.02 in Q1 to -0.38 in Q20. Bank Credit peaks at -0.30 % vs baseline in Q20, from -0.01 in Q1 to -0.30 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +13.27 % vs baseline in Q5, from +7.85 in Q1 to +9.11 in Q20. vs USD peaks at -10.21 % vs baseline in Q4, from -6.20 in Q1 to -8.23 in Q20.

Commodities. Energy Price peaks at +176.36 USD/bbl (level) in Q4, from +138.90 in Q1 to +122.38 in Q20. Metals Price peaks at +98.20 index (level) in Q1, from +98.20 in Q1 to +93.22 in Q20. Food Price peaks at +112.54 index (level) in Q8, from +101.83 in Q1 to +107.12 in Q20. Gas Price peaks at +7.04 USD/mmBtu (level) in Q4, from +5.91 in Q1 to +5.22 in Q20. Copper Price peaks at +98.42 index (level) in Q1, from +98.42 in Q1 to +94.50 in Q20. Wheat Price peaks at +99.21 index (level) in Q1, from +99.21 in Q1 to +96.05 in Q20. Gold Price peaks at +2444.29 USD/oz (level) in Q8, from +2250.80 in Q1 to +2287.25 in Q20.

Sectoral and capital. Manuf. GDP peaks at +1.00 % vs baseline in Q20, from +0.20 in Q1 to +1.00 in Q20. Services GDP peaks at -0.64 % vs baseline in Q12, from -0.21 in Q1 to -0.35 in Q20. Capital Stock peaks at -0.24 % vs baseline in Q20, from -0.01 in Q1 to -0.24 in Q20.

Timing. By Q20 GDP is still -0.61% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/MY_Y.png)

![CPI Inflation](charts/MY_pi_cpi.png)

![Equity Index](charts/MY_equity.png)

![Gold Price](charts/MY_P_gold.png)

![Energy Price](charts/MY_P_energy.png)

![Food Price](charts/MY_P_food.png)

![Wheat Price](charts/MY_P_wheat.png)

![Copper Price](charts/MY_P_copper.png)

![Metals Price](charts/MY_P_metals.png)

![VIX](charts/MY_vix.png)

![NEER](charts/MY_NEER.png)

![Real Exchange Rate](charts/MY_RER.png)

[Q1–Q20 JSON for Malaysia](numbers/MY.json)

## CO — Colombia

The main impact of oil at $200 a barrel on Colombia would be a large drop in GDP of 1.05% by Q13. Equities peak at -1.59% in Q10.

Demand and trade. Consumption peaks at -0.56 % vs baseline in Q14, from +0.01 in Q1 to -0.29 in Q20. Investment peaks at -3.85 % vs baseline in Q9, from -0.36 in Q1 to +0.40 in Q20. Net Exports peaks at +3.45 % vs baseline in Q4, from +2.16 in Q1 to +1.20 in Q20. Gov Spending peaks at +0.89 % vs baseline in Q5, from +0.53 in Q1 to +0.47 in Q20. Gov Debt peaks at -1.03 % vs baseline in Q20, from +0.03 in Q1 to -1.03 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -28.30 % vs baseline in Q4, from -16.65 in Q1 to -15.71 in Q20.

Labour. Employment peaks at -0.85 % vs baseline in Q18, from +0.04 in Q1 to -0.79 in Q20. Unemployment peaks at +0.09 pp in Q15, from -0.01 in Q1 to +0.06 in Q20. Real Wages peaks at +1.27 % vs baseline in Q11, from +0.00 in Q1 to -0.24 in Q20.

Prices. The three-year CPI impulse is +2.41 percentage points. CPI Inflation peaks at +0.47 pp in Q3, from +0.35 in Q1 to -0.16 in Q20. Domestic Infl. peaks at +0.33 pp in Q3, from +0.24 in Q1 to -0.11 in Q20. Marginal Cost peaks at -0.61 % vs baseline in Q13, from +0.10 in Q1 to -0.22 in Q20.

Financial conditions. Policy Rate peaks at +2.05 pp (annualized) in Q5, from +0.56 in Q1 to -0.87 in Q20. Real Rate peaks at +0.51 pp (annualized) in Q5, from +0.14 in Q1 to -0.22 in Q20. Govt 3M Yield peaks at +2.05 pp (annualized) in Q5, from +0.56 in Q1 to -0.87 in Q20. Govt 2Y Yield peaks at +1.69 pp (annualized) in Q2, from +1.60 in Q1 to -0.76 in Q20. Govt 5Y Yield peaks at -0.62 pp (annualized) in Q14, from +0.56 in Q1 to -0.49 in Q20. Govt 10Y Yield peaks at -0.36 pp (annualized) in Q14, from +0.06 in Q1 to -0.27 in Q20. Govt 30Y Yield peaks at -0.12 pp (annualized) in Q13, from +0.01 in Q1 to -0.09 in Q20. Bond Price (7y) peaks at -7.33 % vs baseline in Q5, from -2.01 in Q1 to +3.11 in Q20. Bond Price 3M peaks at -0.51 % vs baseline in Q5, from -0.14 in Q1 to +0.22 in Q20. Bond Price 2Y peaks at -3.21 % vs baseline in Q2, from -3.05 in Q1 to +1.44 in Q20. Bond Price 5Y peaks at +2.77 % vs baseline in Q14, from -2.52 in Q1 to +2.19 in Q20. Bond Price 10Y peaks at +2.96 % vs baseline in Q14, from -0.45 in Q1 to +2.22 in Q20. Bond Price 30Y peaks at +2.24 % vs baseline in Q13, from -0.15 in Q1 to +1.66 in Q20. Equity Index peaks at -1.59 % vs baseline in Q10, from +0.02 in Q1 to +0.53 in Q20. VIX peaks at +23.07 index_level in Q6, from +19.31 in Q1 to +18.76 in Q20. Tobin's Q peaks at -2.70 % vs baseline in Q9, from -0.25 in Q1 to +0.28 in Q20. House Prices peaks at -1.08 % vs baseline in Q18, from +0.01 in Q1 to -1.03 in Q20. Bank Equity peaks at +0.01 % vs baseline in Q8, from +0.00 in Q1 to -0.00 in Q20. Bank Credit peaks at +0.00 % vs baseline in Q7, from +0.00 in Q1 to -0.00 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +26.85 % vs baseline in Q4, from +15.93 in Q1 to +15.42 in Q20. vs USD peaks at -27.50 % vs baseline in Q4, from -16.34 in Q1 to -16.08 in Q20.

Commodities. Energy Price peaks at +176.36 USD/bbl (level) in Q4, from +138.90 in Q1 to +122.38 in Q20. Metals Price peaks at +98.20 index (level) in Q1, from +98.20 in Q1 to +93.22 in Q20. Food Price peaks at +112.54 index (level) in Q8, from +101.83 in Q1 to +107.12 in Q20. Gas Price peaks at +7.04 USD/mmBtu (level) in Q4, from +5.91 in Q1 to +5.22 in Q20. Copper Price peaks at +98.42 index (level) in Q1, from +98.42 in Q1 to +94.50 in Q20. Wheat Price peaks at +99.21 index (level) in Q1, from +99.21 in Q1 to +96.05 in Q20. Gold Price peaks at +2444.29 USD/oz (level) in Q8, from +2250.80 in Q1 to +2287.25 in Q20.

Sectoral and capital. Manuf. GDP peaks at +6.59 % vs baseline in Q4, from +3.85 in Q1 to +3.79 in Q20. Services GDP peaks at -0.63 % vs baseline in Q13, from +0.08 in Q1 to -0.24 in Q20. Capital Stock peaks at -0.22 % vs baseline in Q19, from -0.00 in Q1 to -0.22 in Q20.

Timing. By Q20 GDP is still -0.40% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/CO_Y.png)

![CPI Inflation](charts/CO_pi_cpi.png)

![Equity Index](charts/CO_equity.png)

![Gold Price](charts/CO_P_gold.png)

![Energy Price](charts/CO_P_energy.png)

![Food Price](charts/CO_P_food.png)

![Wheat Price](charts/CO_P_wheat.png)

![Copper Price](charts/CO_P_copper.png)

![Metals Price](charts/CO_P_metals.png)

![Real Exchange Rate](charts/CO_RER.png)

![vs USD](charts/CO_USD.png)

![NEER](charts/CO_NEER.png)

[Q1–Q20 JSON for Colombia](numbers/CO.json)


---

These figures are model IRFs versus baseline, not forecasts, and not financial advice.
