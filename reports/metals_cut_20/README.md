# Global Macro Economic Simulations and Financial Market Responses

v6 · IRF · evaluation

**Open the typeset report (this is the document):** https://robomacro.com/GlobalMacroTrainingDataset/metals_cut_20/

GitHub and Hugging Face show `.html` as source code. That is not the report. Read it on robomacro.com, or keep scrolling this page.

## What's the impact of Metals supply -20%

### Active treatment

```json
{
  "metals": -0.2
}
```

### Assumptions

- Every path is a model impulse response versus baseline, not a forecast.
- The solver and weights are not included.
- English never enters the solver.

### Summary

This report traces the model response to a 20% metals-supply cut. Every path is an impulse response versus an unchanged baseline — not a forecast and not market data. The question was: What's the impact of Metals supply -20%

Chile sees a +0.58% GDP peak at Q3, with CPI +0.18pp over three years and equities +1.29%. Australia sees a +0.44% GDP peak at Q3, with CPI +0.06pp over three years and equities +1.08%. South Africa sees a +0.31% GDP peak at Q3, with CPI +0.15pp over three years and equities +1.22%. Russia sees a +0.18% GDP peak at Q3, with CPI +0.18pp over three years and equities +0.28%.

The remaining countries are smaller spillovers and are covered in the chapters that follow. This material is a model-based summary and is not financial advice.

### Countries by GDP impact

- [CL — Chile](#cl--chile) · GDP +0.58% Q3
- [AU — Australia](#au--australia) · GDP +0.44% Q3
- [ZA — South Africa](#za--south-africa) · GDP +0.31% Q3
- [RU — Russia](#ru--russia) · GDP +0.18% Q3
- [KR — South Korea](#kr--south-korea) · GDP -0.18% Q3
- [AR — Argentina](#ar--argentina) · GDP -0.15% Q11
- [JP — Japan](#jp--japan) · GDP -0.15% Q3
- [DE — Germany](#de--germany) · GDP -0.12% Q4
- [SE — Sweden](#se--sweden) · GDP +0.12% Q3
- [BR — Brazil](#br--brazil) · GDP +0.12% Q3
- [TR — Turkey](#tr--turkey) · GDP -0.11% Q9
- [IT — Italy](#it--italy) · GDP -0.10% Q4
- [PL — Poland](#pl--poland) · GDP -0.08% Q4
- [FR — France](#fr--france) · GDP -0.07% Q4
- [NG — Nigeria](#ng--nigeria) · GDP -0.07% Q12
- [UK — United Kingdom](#uk--united-kingdom) · GDP -0.06% Q4
- [ES — Spain](#es--spain) · GDP -0.06% Q4
- [TH — Thailand](#th--thailand) · GDP -0.06% Q4
- [CA — Canada](#ca--canada) · GDP +0.06% Q3
- [IN — India](#in--india) · GDP -0.06% Q12
- [MX — Mexico](#mx--mexico) · GDP +0.05% Q3
- [CO — Colombia](#co--colombia) · GDP -0.05% Q12
- [ID — Indonesia](#id--indonesia) · GDP +0.04% Q3
- [SA — Saudi Arabia](#sa--saudi-arabia) · GDP -0.04% Q10
- [US — United States](#us--united-states) · GDP -0.04% Q11
- [NO — Norway](#no--norway) · GDP -0.03% Q12
- [NL — Netherlands](#nl--netherlands) · GDP -0.03% Q10
- [MY — Malaysia](#my--malaysia) · GDP -0.02% Q12
- [CH — Switzerland](#ch--switzerland) · GDP -0.02% Q9
- [CN — China](#cn--china) · GDP -0.02% Q14

![CL GDP](charts/global_CL_Y.png)

![AU GDP](charts/global_AU_Y.png)

![ZA GDP](charts/global_ZA_Y.png)

![RU GDP](charts/global_RU_Y.png)

![US Equity Index](charts/global_US_equity.png)

![US Policy Rate](charts/global_US_i.png)

## CL — Chile

The main impact of a 20% metals-supply cut on Chile would be a large rise in GDP of 0.58% by Q3. Equities peak at +1.29% in Q3.

Demand and trade. Consumption peaks at +0.36 % vs baseline in Q4, from +0.19 in Q1 to +0.05 in Q20. Investment peaks at +1.54 % vs baseline in Q2, from +1.02 in Q1 to +0.15 in Q20. Net Exports peaks at +3.81 % vs baseline in Q3, from +2.53 in Q1 to +0.73 in Q20. Gov Spending peaks at +1.26 % vs baseline in Q3, from +0.83 in Q1 to +0.26 in Q20. Gov Debt peaks at +0.38 % vs baseline in Q11, from +0.05 in Q1 to +0.29 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -12.25 % vs baseline in Q3, from -8.06 in Q1 to -2.69 in Q20.

Labour. Employment peaks at +0.46 % vs baseline in Q7, from +0.09 in Q1 to +0.17 in Q20. Unemployment peaks at -0.18 pp in Q7, from -0.04 in Q1 to -0.05 in Q20. Real Wages peaks at +0.66 % vs baseline in Q20, from +0.01 in Q1 to +0.66 in Q20.

Prices. The three-year CPI impulse is +0.18 percentage points. CPI Inflation peaks at +0.03 pp in Q2, from +0.02 in Q1 to +0.00 in Q20. Domestic Infl. peaks at +0.02 pp in Q2, from +0.02 in Q1 to +0.00 in Q20. Marginal Cost peaks at +0.35 % vs baseline in Q3, from +0.23 in Q1 to +0.04 in Q20.

Financial conditions. Policy Rate peaks at +0.16 pp (annualized) in Q5, from +0.04 in Q1 to +0.03 in Q20. Real Rate peaks at +0.04 pp (annualized) in Q5, from +0.01 in Q1 to +0.01 in Q20. Govt 3M Yield peaks at +0.16 pp (annualized) in Q5, from +0.04 in Q1 to +0.03 in Q20. Govt 2Y Yield peaks at +0.14 pp (annualized) in Q3, from +0.12 in Q1 to +0.02 in Q20. Govt 5Y Yield peaks at +0.09 pp (annualized) in Q1, from +0.09 in Q1 to +0.02 in Q20. Govt 10Y Yield peaks at +0.05 pp (annualized) in Q1, from +0.05 in Q1 to +0.01 in Q20. Govt 30Y Yield peaks at +0.02 pp (annualized) in Q1, from +0.02 in Q1 to +0.00 in Q20. Bond Price (7y) peaks at -0.65 % vs baseline in Q5, from -0.16 in Q1 to -0.11 in Q20. Bond Price 3M peaks at -0.04 % vs baseline in Q5, from -0.01 in Q1 to -0.01 in Q20. Bond Price 2Y peaks at -0.26 % vs baseline in Q3, from -0.23 in Q1 to -0.04 in Q20. Bond Price 5Y peaks at -0.38 % vs baseline in Q1, from -0.38 in Q1 to -0.08 in Q20. Bond Price 10Y peaks at -0.42 % vs baseline in Q1, from -0.42 in Q1 to -0.09 in Q20. Bond Price 30Y peaks at -0.32 % vs baseline in Q1, from -0.32 in Q1 to -0.07 in Q20. Equity Index peaks at +1.29 % vs baseline in Q3, from +0.87 in Q1 to +0.18 in Q20. VIX peaks at +15.09 index_level in Q10, from +15.01 in Q1 to +15.01 in Q20. Tobin's Q peaks at +1.08 % vs baseline in Q2, from +0.72 in Q1 to +0.10 in Q20. House Prices peaks at +0.50 % vs baseline in Q11, from +0.06 in Q1 to +0.38 in Q20. Bank Equity peaks at +0.04 % vs baseline in Q12, from +0.01 in Q1 to +0.04 in Q20. Bank Credit peaks at +0.01 % vs baseline in Q12, from +0.00 in Q1 to +0.01 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +11.80 % vs baseline in Q3, from +7.77 in Q1 to +2.62 in Q20. vs USD peaks at -12.67 % vs baseline in Q3, from -8.34 in Q1 to -2.86 in Q20.

Commodities. Energy Price peaks at +80.03 USD/bbl (level) in Q3, from +80.01 in Q1 to +79.96 in Q20. Metals Price peaks at +143.18 index (level) in Q3, from +128.59 in Q1 to +108.65 in Q20. Food Price peaks at +100.04 index (level) in Q3, from +100.02 in Q1 to +99.95 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q3, from +4.00 in Q1 to +4.00 in Q20. Copper Price peaks at +100.01 index (level) in Q3, from +100.01 in Q1 to +99.97 in Q20. Wheat Price peaks at +100.03 index (level) in Q3, from +100.01 in Q1 to +99.98 in Q20. Gold Price peaks at +2008.23 USD/oz (level) in Q11, from +2003.83 in Q1 to +2003.50 in Q20.

Sectoral and capital. Manuf. GDP peaks at +3.78 % vs baseline in Q3, from +2.49 in Q1 to +0.82 in Q20. Services GDP peaks at +0.35 % vs baseline in Q3, from +0.23 in Q1 to +0.04 in Q20. Capital Stock peaks at +0.07 % vs baseline in Q20, from +0.01 in Q1 to +0.07 in Q20.

Timing. The GDP response has mostly faded by Q15 (Q20 is +0.07%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/CL_Y.png)

![CPI Inflation](charts/CL_pi_cpi.png)

![Equity Index](charts/CL_equity.png)

![Gold Price](charts/CL_P_gold.png)

![Metals Price](charts/CL_P_metals.png)

![Food Price](charts/CL_P_food.png)

![Wheat Price](charts/CL_P_wheat.png)

![Copper Price](charts/CL_P_copper.png)

![Energy Price](charts/CL_P_energy.png)

![VIX](charts/CL_vix.png)

![vs USD](charts/CL_USD.png)

![Real Exchange Rate](charts/CL_RER.png)

[Q1–Q20 JSON for Chile](numbers/CL.json)

## AU — Australia

The main impact of a 20% metals-supply cut on Australia would be a large rise in GDP of 0.44% by Q3. Equities peak at +1.08% in Q3.

Demand and trade. Consumption peaks at +0.29 % vs baseline in Q4, from +0.15 in Q1 to +0.03 in Q20. Investment peaks at +1.14 % vs baseline in Q2, from +0.77 in Q1 to -0.00 in Q20. Net Exports peaks at +2.96 % vs baseline in Q3, from +1.97 in Q1 to +0.55 in Q20. Gov Spending peaks at +0.52 % vs baseline in Q3, from +0.34 in Q1 to +0.11 in Q20. Gov Debt peaks at +0.16 % vs baseline in Q12, from +0.02 in Q1 to +0.13 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -28.35 % vs baseline in Q3, from -18.68 in Q1 to -6.08 in Q20.

Labour. Employment peaks at +0.39 % vs baseline in Q7, from +0.09 in Q1 to +0.10 in Q20. Unemployment peaks at -0.20 pp in Q7, from -0.05 in Q1 to -0.05 in Q20. Real Wages peaks at +0.42 % vs baseline in Q20, from +0.00 in Q1 to +0.42 in Q20.

Prices. The three-year CPI impulse is +0.06 percentage points. CPI Inflation peaks at +0.02 pp in Q2, from +0.02 in Q1 to +0.00 in Q20. Domestic Infl. peaks at +0.01 pp in Q2, from +0.01 in Q1 to +0.00 in Q20. Marginal Cost peaks at +0.27 % vs baseline in Q3, from +0.18 in Q1 to +0.02 in Q20.

Financial conditions. Policy Rate peaks at +0.20 pp (annualized) in Q7, from +0.04 in Q1 to +0.06 in Q20. Real Rate peaks at +0.05 pp (annualized) in Q7, from +0.01 in Q1 to +0.02 in Q20. Govt 3M Yield peaks at +0.20 pp (annualized) in Q7, from +0.04 in Q1 to +0.06 in Q20. Govt 2Y Yield peaks at +0.19 pp (annualized) in Q4, from +0.16 in Q1 to +0.05 in Q20. Govt 5Y Yield peaks at +0.13 pp (annualized) in Q2, from +0.13 in Q1 to +0.03 in Q20. Govt 10Y Yield peaks at +0.08 pp (annualized) in Q1, from +0.08 in Q1 to +0.02 in Q20. Govt 30Y Yield peaks at +0.03 pp (annualized) in Q1, from +0.03 in Q1 to +0.01 in Q20. Bond Price (7y) peaks at -1.26 % vs baseline in Q7, from -0.27 in Q1 to -0.40 in Q20. Bond Price 3M peaks at -0.05 % vs baseline in Q7, from -0.01 in Q1 to -0.02 in Q20. Bond Price 2Y peaks at -0.35 % vs baseline in Q4, from -0.30 in Q1 to -0.09 in Q20. Bond Price 5Y peaks at -0.60 % vs baseline in Q2, from -0.60 in Q1 to -0.14 in Q20. Bond Price 10Y peaks at -0.66 % vs baseline in Q1, from -0.66 in Q1 to -0.14 in Q20. Bond Price 30Y peaks at -0.49 % vs baseline in Q1, from -0.49 in Q1 to -0.09 in Q20. Equity Index peaks at +1.08 % vs baseline in Q3, from +0.73 in Q1 to +0.11 in Q20. VIX peaks at +15.09 index_level in Q10, from +15.01 in Q1 to +15.01 in Q20. Tobin's Q peaks at +0.80 % vs baseline in Q2, from +0.54 in Q1 to -0.00 in Q20. House Prices peaks at +0.29 % vs baseline in Q12, from +0.03 in Q1 to +0.24 in Q20. Bank Equity peaks at +0.05 % vs baseline in Q12, from +0.01 in Q1 to +0.04 in Q20. Bank Credit peaks at +0.02 % vs baseline in Q12, from +0.00 in Q1 to +0.01 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +28.49 % vs baseline in Q3, from +18.77 in Q1 to +6.12 in Q20. vs USD peaks at -28.77 % vs baseline in Q3, from -18.96 in Q1 to -6.25 in Q20.

Commodities. Energy Price peaks at +80.03 USD/bbl (level) in Q3, from +80.01 in Q1 to +79.96 in Q20. Metals Price peaks at +143.18 index (level) in Q3, from +128.59 in Q1 to +108.65 in Q20. Food Price peaks at +100.04 index (level) in Q3, from +100.02 in Q1 to +99.95 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q3, from +4.00 in Q1 to +4.00 in Q20. Copper Price peaks at +100.01 index (level) in Q3, from +100.01 in Q1 to +99.97 in Q20. Wheat Price peaks at +100.03 index (level) in Q3, from +100.01 in Q1 to +99.98 in Q20. Gold Price peaks at +2008.23 USD/oz (level) in Q11, from +2003.83 in Q1 to +2003.50 in Q20.

Sectoral and capital. Manuf. GDP peaks at +8.57 % vs baseline in Q3, from +5.65 in Q1 to +1.83 in Q20. Services GDP peaks at +0.32 % vs baseline in Q3, from +0.21 in Q1 to +0.03 in Q20. Capital Stock peaks at +0.04 % vs baseline in Q19, from +0.00 in Q1 to +0.04 in Q20.

Timing. The GDP response has mostly faded by Q15 (Q20 is +0.04%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/AU_Y.png)

![CPI Inflation](charts/AU_pi_cpi.png)

![Equity Index](charts/AU_equity.png)

![Gold Price](charts/AU_P_gold.png)

![Metals Price](charts/AU_P_metals.png)

![Food Price](charts/AU_P_food.png)

![Wheat Price](charts/AU_P_wheat.png)

![Copper Price](charts/AU_P_copper.png)

![Energy Price](charts/AU_P_energy.png)

![vs USD](charts/AU_USD.png)

![NEER](charts/AU_NEER.png)

![Real Exchange Rate](charts/AU_RER.png)

[Q1–Q20 JSON for Australia](numbers/AU.json)

## ZA — South Africa

The main impact of a 20% metals-supply cut on South Africa would be a large rise in GDP of 0.31% by Q3. Equities peak at +1.22% in Q3.

Demand and trade. Consumption peaks at +0.18 % vs baseline in Q4, from +0.09 in Q1 to +0.02 in Q20. Investment peaks at +0.80 % vs baseline in Q2, from +0.54 in Q1 to +0.10 in Q20. Net Exports peaks at +2.12 % vs baseline in Q3, from +1.41 in Q1 to +0.42 in Q20. Gov Spending peaks at +0.27 % vs baseline in Q3, from +0.18 in Q1 to +0.06 in Q20. Gov Debt peaks at +0.18 % vs baseline in Q13, from +0.02 in Q1 to +0.16 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -9.59 % vs baseline in Q3, from -6.32 in Q1 to -1.99 in Q20.

Labour. Employment peaks at +0.25 % vs baseline in Q7, from +0.05 in Q1 to +0.08 in Q20. Unemployment peaks at -0.07 pp in Q6, from -0.02 in Q1 to -0.01 in Q20. Real Wages peaks at +0.36 % vs baseline in Q19, from +0.00 in Q1 to +0.36 in Q20.

Prices. The three-year CPI impulse is +0.15 percentage points. CPI Inflation peaks at +0.03 pp in Q2, from +0.02 in Q1 to -0.00 in Q20. Domestic Infl. peaks at +0.02 pp in Q2, from +0.02 in Q1 to -0.00 in Q20. Marginal Cost peaks at +0.19 % vs baseline in Q3, from +0.13 in Q1 to +0.02 in Q20.

Financial conditions. Policy Rate peaks at +0.12 pp (annualized) in Q5, from +0.04 in Q1 to -0.01 in Q20. Real Rate peaks at +0.03 pp (annualized) in Q5, from +0.01 in Q1 to -0.00 in Q20. Govt 3M Yield peaks at +0.12 pp (annualized) in Q5, from +0.04 in Q1 to -0.01 in Q20. Govt 2Y Yield peaks at +0.10 pp (annualized) in Q2, from +0.09 in Q1 to -0.01 in Q20. Govt 5Y Yield peaks at +0.05 pp (annualized) in Q1, from +0.05 in Q1 to -0.00 in Q20. Govt 10Y Yield peaks at +0.02 pp (annualized) in Q1, from +0.02 in Q1 to -0.00 in Q20. Govt 30Y Yield peaks at +0.01 pp (annualized) in Q1, from +0.01 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at -0.50 % vs baseline in Q5, from -0.15 in Q1 to +0.04 in Q20. Bond Price 3M peaks at -0.03 % vs baseline in Q5, from -0.01 in Q1 to +0.00 in Q20. Bond Price 2Y peaks at -0.19 % vs baseline in Q2, from -0.18 in Q1 to +0.02 in Q20. Bond Price 5Y peaks at -0.21 % vs baseline in Q1, from -0.21 in Q1 to +0.02 in Q20. Bond Price 10Y peaks at -0.18 % vs baseline in Q1, from -0.18 in Q1 to +0.01 in Q20. Bond Price 30Y peaks at -0.13 % vs baseline in Q1, from -0.13 in Q1 to +0.01 in Q20. Equity Index peaks at +1.22 % vs baseline in Q3, from +0.83 in Q1 to +0.14 in Q20. VIX peaks at +15.09 index_level in Q10, from +15.01 in Q1 to +15.01 in Q20. Tobin's Q peaks at +0.56 % vs baseline in Q2, from +0.38 in Q1 to +0.07 in Q20. House Prices peaks at +0.25 % vs baseline in Q10, from +0.03 in Q1 to +0.18 in Q20. Bank Equity peaks at +0.03 % vs baseline in Q12, from +0.00 in Q1 to +0.02 in Q20. Bank Credit peaks at +0.01 % vs baseline in Q12, from +0.00 in Q1 to +0.01 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +9.29 % vs baseline in Q3, from +6.12 in Q1 to +1.92 in Q20. vs USD peaks at -10.01 % vs baseline in Q3, from -6.60 in Q1 to -2.15 in Q20.

Commodities. Energy Price peaks at +80.03 USD/bbl (level) in Q3, from +80.01 in Q1 to +79.96 in Q20. Metals Price peaks at +143.18 index (level) in Q3, from +128.59 in Q1 to +108.65 in Q20. Food Price peaks at +100.04 index (level) in Q3, from +100.02 in Q1 to +99.95 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q3, from +4.00 in Q1 to +4.00 in Q20. Copper Price peaks at +100.01 index (level) in Q3, from +100.01 in Q1 to +99.97 in Q20. Wheat Price peaks at +100.03 index (level) in Q3, from +100.01 in Q1 to +99.98 in Q20. Gold Price peaks at +2008.23 USD/oz (level) in Q11, from +2003.83 in Q1 to +2003.50 in Q20.

Sectoral and capital. Manuf. GDP peaks at +2.93 % vs baseline in Q3, from +1.93 in Q1 to +0.60 in Q20. Services GDP peaks at +0.20 % vs baseline in Q3, from +0.13 in Q1 to +0.02 in Q20. Capital Stock peaks at +0.03 % vs baseline in Q20, from +0.00 in Q1 to +0.03 in Q20.

Timing. The GDP response has mostly faded by Q13 (Q20 is +0.03%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/ZA_Y.png)

![CPI Inflation](charts/ZA_pi_cpi.png)

![Equity Index](charts/ZA_equity.png)

![Gold Price](charts/ZA_P_gold.png)

![Metals Price](charts/ZA_P_metals.png)

![Food Price](charts/ZA_P_food.png)

![Wheat Price](charts/ZA_P_wheat.png)

![Copper Price](charts/ZA_P_copper.png)

![Energy Price](charts/ZA_P_energy.png)

![VIX](charts/ZA_vix.png)

![vs USD](charts/ZA_USD.png)

![Real Exchange Rate](charts/ZA_RER.png)

[Q1–Q20 JSON for South Africa](numbers/ZA.json)

## RU — Russia

The main impact of a 20% metals-supply cut on Russia would be a moderate rise in GDP of 0.18% by Q3. Equities peak at +0.28% in Q3.

Demand and trade. Consumption peaks at +0.10 % vs baseline in Q4, from +0.05 in Q1 to -0.01 in Q20. Investment peaks at +0.44 % vs baseline in Q2, from +0.31 in Q1 to -0.01 in Q20. Net Exports peaks at +1.28 % vs baseline in Q3, from +0.84 in Q1 to +0.26 in Q20. Gov Spending peaks at +0.38 % vs baseline in Q3, from +0.25 in Q1 to +0.08 in Q20. Gov Debt peaks at +0.05 % vs baseline in Q9, from +0.01 in Q1 to +0.03 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -0.56 % vs baseline in Q3, from -0.38 in Q1 to -0.07 in Q20.

Labour. Employment peaks at +0.13 % vs baseline in Q7, from +0.02 in Q1 to +0.00 in Q20. Unemployment peaks at -0.05 pp in Q6, from -0.01 in Q1 to +0.01 in Q20. Real Wages peaks at +0.25 % vs baseline in Q15, from +0.00 in Q1 to +0.21 in Q20.

Prices. The three-year CPI impulse is +0.18 percentage points. CPI Inflation peaks at +0.03 pp in Q3, from +0.02 in Q1 to -0.01 in Q20. Domestic Infl. peaks at +0.02 pp in Q3, from +0.01 in Q1 to -0.00 in Q20. Marginal Cost peaks at +0.11 % vs baseline in Q3, from +0.08 in Q1 to -0.01 in Q20.

Financial conditions. Policy Rate peaks at +0.13 pp (annualized) in Q5, from +0.03 in Q1 to -0.03 in Q20. Real Rate peaks at +0.03 pp (annualized) in Q5, from +0.01 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at +0.13 pp (annualized) in Q5, from +0.03 in Q1 to -0.03 in Q20. Govt 2Y Yield peaks at +0.11 pp (annualized) in Q2, from +0.10 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at +0.05 pp (annualized) in Q1, from +0.05 in Q1 to -0.02 in Q20. Govt 10Y Yield peaks at +0.02 pp (annualized) in Q1, from +0.02 in Q1 to -0.01 in Q20. Govt 30Y Yield peaks at +0.01 pp (annualized) in Q1, from +0.01 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at -0.41 % vs baseline in Q5, from -0.10 in Q1 to +0.09 in Q20. Bond Price 3M peaks at -0.03 % vs baseline in Q5, from -0.01 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at -0.20 % vs baseline in Q2, from -0.19 in Q1 to +0.05 in Q20. Bond Price 5Y peaks at -0.21 % vs baseline in Q1, from -0.21 in Q1 to +0.07 in Q20. Bond Price 10Y peaks at -0.13 % vs baseline in Q1, from -0.13 in Q1 to +0.07 in Q20. Bond Price 30Y peaks at -0.09 % vs baseline in Q1, from -0.09 in Q1 to +0.05 in Q20. Equity Index peaks at +0.28 % vs baseline in Q3, from +0.21 in Q1 to -0.00 in Q20. VIX peaks at +15.09 index_level in Q10, from +15.01 in Q1 to +15.01 in Q20. Tobin's Q peaks at +0.31 % vs baseline in Q2, from +0.22 in Q1 to -0.00 in Q20. House Prices peaks at +0.13 % vs baseline in Q8, from +0.02 in Q1 to +0.04 in Q20. Bank Equity peaks at +0.01 % vs baseline in Q11, from +0.00 in Q1 to +0.01 in Q20. Bank Credit peaks at +0.00 % vs baseline in Q11, from +0.00 in Q1 to +0.00 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.62 % vs baseline in Q3, from +0.43 in Q1 to +0.08 in Q20. vs USD peaks at -0.98 % vs baseline in Q3, from -0.66 in Q1 to -0.23 in Q20.

Commodities. Energy Price peaks at +80.03 USD/bbl (level) in Q3, from +80.01 in Q1 to +79.96 in Q20. Metals Price peaks at +143.18 index (level) in Q3, from +128.59 in Q1 to +108.65 in Q20. Food Price peaks at +100.04 index (level) in Q3, from +100.02 in Q1 to +99.95 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q3, from +4.00 in Q1 to +4.00 in Q20. Copper Price peaks at +100.01 index (level) in Q3, from +100.01 in Q1 to +99.97 in Q20. Wheat Price peaks at +100.03 index (level) in Q3, from +100.01 in Q1 to +99.98 in Q20. Gold Price peaks at +2008.23 USD/oz (level) in Q11, from +2003.83 in Q1 to +2003.50 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.20 % vs baseline in Q3, from +0.14 in Q1 to +0.02 in Q20. Services GDP peaks at +0.10 % vs baseline in Q3, from +0.07 in Q1 to -0.01 in Q20. Capital Stock peaks at +0.01 % vs baseline in Q9, from +0.00 in Q1 to +0.01 in Q20.

Timing. The GDP response has mostly faded by Q10 (Q20 is -0.02%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/RU_Y.png)

![CPI Inflation](charts/RU_pi_cpi.png)

![Equity Index](charts/RU_equity.png)

![Gold Price](charts/RU_P_gold.png)

![Metals Price](charts/RU_P_metals.png)

![Food Price](charts/RU_P_food.png)

![Wheat Price](charts/RU_P_wheat.png)

![Copper Price](charts/RU_P_copper.png)

![Energy Price](charts/RU_P_energy.png)

![VIX](charts/RU_vix.png)

![Gas Price](charts/RU_P_gas.png)

![Net Exports](charts/RU_NX.png)

[Q1–Q20 JSON for Russia](numbers/RU.json)

## KR — South Korea

The main impact of a 20% metals-supply cut on South Korea would be a moderate drop in GDP of 0.18% by Q3. Equities peak at -0.46% in Q4.

Demand and trade. Consumption peaks at -0.11 % vs baseline in Q4, from -0.06 in Q1 to -0.02 in Q20. Investment peaks at -0.54 % vs baseline in Q3, from -0.32 in Q1 to +0.02 in Q20. Net Exports peaks at -1.05 % vs baseline in Q3, from -0.70 in Q1 to -0.18 in Q20. Gov Spending peaks at +0.03 % vs baseline in Q4, from +0.02 in Q1 to +0.00 in Q20. Gov Debt peaks at -0.09 % vs baseline in Q16, from -0.01 in Q1 to -0.08 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +1.36 % vs baseline in Q3, from +0.88 in Q1 to +0.43 in Q20.

Labour. Employment peaks at -0.13 % vs baseline in Q10, from -0.02 in Q1 to -0.07 in Q20. Unemployment peaks at +0.06 pp in Q8, from +0.01 in Q1 to +0.02 in Q20. Real Wages peaks at -0.15 % vs baseline in Q20, from -0.00 in Q1 to -0.15 in Q20.

Prices. The three-year CPI impulse is +0.13 percentage points. CPI Inflation peaks at +0.03 pp in Q2, from +0.02 in Q1 to -0.01 in Q20. Domestic Infl. peaks at +0.02 pp in Q2, from +0.02 in Q1 to -0.01 in Q20. Marginal Cost peaks at -0.10 % vs baseline in Q4, from -0.06 in Q1 to -0.02 in Q20.

Financial conditions. Policy Rate peaks at -0.06 pp (annualized) in Q18, from +0.02 in Q1 to -0.06 in Q20. Real Rate peaks at -0.01 pp (annualized) in Q18, from +0.00 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -0.06 pp (annualized) in Q18, from +0.02 in Q1 to -0.06 in Q20. Govt 2Y Yield peaks at -0.06 pp (annualized) in Q15, from +0.04 in Q1 to -0.05 in Q20. Govt 5Y Yield peaks at -0.04 pp (annualized) in Q12, from -0.01 in Q1 to -0.03 in Q20. Govt 10Y Yield peaks at -0.03 pp (annualized) in Q10, from -0.02 in Q1 to -0.02 in Q20. Govt 30Y Yield peaks at -0.01 pp (annualized) in Q10, from -0.01 in Q1 to -0.01 in Q20. Bond Price (7y) peaks at +0.29 % vs baseline in Q18, from -0.10 in Q1 to +0.28 in Q20. Bond Price 3M peaks at +0.01 % vs baseline in Q18, from -0.00 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +0.11 % vs baseline in Q15, from -0.07 in Q1 to +0.09 in Q20. Bond Price 5Y peaks at +0.20 % vs baseline in Q12, from +0.05 in Q1 to +0.14 in Q20. Bond Price 10Y peaks at +0.23 % vs baseline in Q10, from +0.16 in Q1 to +0.14 in Q20. Bond Price 30Y peaks at +0.17 % vs baseline in Q10, from +0.13 in Q1 to +0.11 in Q20. Equity Index peaks at -0.46 % vs baseline in Q4, from -0.28 in Q1 to -0.05 in Q20. VIX peaks at +15.09 index_level in Q10, from +15.01 in Q1 to +15.01 in Q20. Tobin's Q peaks at -0.38 % vs baseline in Q3, from -0.23 in Q1 to +0.01 in Q20. House Prices peaks at -0.15 % vs baseline in Q14, from -0.01 in Q1 to -0.13 in Q20. Bank Equity peaks at -0.05 % vs baseline in Q12, from -0.01 in Q1 to -0.04 in Q20. Bank Credit peaks at -0.04 % vs baseline in Q12, from -0.00 in Q1 to -0.03 in Q20. Credit Spread peaks at +0.00 pp in Q12, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -3.10 % vs baseline in Q3, from -2.03 in Q1 to -0.80 in Q20. vs USD peaks at +0.95 % vs baseline in Q4, from +0.60 in Q1 to +0.26 in Q20.

Commodities. Energy Price peaks at +80.03 USD/bbl (level) in Q3, from +80.01 in Q1 to +79.96 in Q20. Metals Price peaks at +143.18 index (level) in Q3, from +128.59 in Q1 to +108.65 in Q20. Food Price peaks at +100.04 index (level) in Q3, from +100.02 in Q1 to +99.95 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q3, from +4.00 in Q1 to +4.00 in Q20. Copper Price peaks at +100.01 index (level) in Q3, from +100.01 in Q1 to +99.97 in Q20. Wheat Price peaks at +100.03 index (level) in Q3, from +100.01 in Q1 to +99.98 in Q20. Gold Price peaks at +2008.23 USD/oz (level) in Q11, from +2003.83 in Q1 to +2003.50 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.47 % vs baseline in Q3, from -0.30 in Q1 to -0.14 in Q20. Services GDP peaks at -0.11 % vs baseline in Q3, from -0.07 in Q1 to -0.02 in Q20. Capital Stock peaks at -0.03 % vs baseline in Q19, from -0.00 in Q1 to -0.03 in Q20.

Timing. The GDP response has mostly faded by Q19 (Q20 is -0.03%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/KR_Y.png)

![CPI Inflation](charts/KR_pi_cpi.png)

![Equity Index](charts/KR_equity.png)

![Gold Price](charts/KR_P_gold.png)

![Metals Price](charts/KR_P_metals.png)

![Food Price](charts/KR_P_food.png)

![Wheat Price](charts/KR_P_wheat.png)

![Copper Price](charts/KR_P_copper.png)

![Energy Price](charts/KR_P_energy.png)

![VIX](charts/KR_vix.png)

![Gas Price](charts/KR_P_gas.png)

![NEER](charts/KR_NEER.png)

[Q1–Q20 JSON for South Korea](numbers/KR.json)

## AR — Argentina

The main impact of a 20% metals-supply cut on Argentina would be a moderate drop in GDP of 0.15% by Q11. Equities peak at -0.26% in Q10.

Demand and trade. Consumption peaks at -0.07 % vs baseline in Q12, from -0.01 in Q1 to -0.00 in Q20. Investment peaks at -0.34 % vs baseline in Q8, from -0.09 in Q1 to +0.13 in Q20. Net Exports peaks at +0.02 % vs baseline in Q9, from +0.00 in Q1 to -0.00 in Q20. Gov Spending peaks at +0.03 % vs baseline in Q11, from +0.00 in Q1 to -0.00 in Q20. Gov Debt peaks at -0.10 % vs baseline in Q20, from +0.00 in Q1 to -0.10 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -0.38 % vs baseline in Q3, from -0.27 in Q1 to -0.09 in Q20.

Labour. Employment peaks at -0.12 % vs baseline in Q15, from +0.00 in Q1 to -0.08 in Q20. Unemployment peaks at +0.03 pp in Q13, from +0.00 in Q1 to +0.01 in Q20. Real Wages peaks at -0.24 % vs baseline in Q20, from +0.00 in Q1 to -0.24 in Q20.

Prices. The three-year CPI impulse is +0.04 percentage points. CPI Inflation peaks at +0.03 pp in Q2, from +0.02 in Q1 to -0.01 in Q20. Domestic Infl. peaks at +0.02 pp in Q2, from +0.02 in Q1 to -0.01 in Q20. Marginal Cost peaks at -0.09 % vs baseline in Q11, from -0.00 in Q1 to +0.01 in Q20.

Financial conditions. Policy Rate peaks at +0.12 pp (annualized) in Q3, from +0.06 in Q1 to -0.06 in Q20. Real Rate peaks at +0.03 pp (annualized) in Q3, from +0.01 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at +0.12 pp (annualized) in Q3, from +0.06 in Q1 to -0.06 in Q20. Govt 2Y Yield peaks at -0.10 pp (annualized) in Q11, from +0.07 in Q1 to -0.02 in Q20. Govt 5Y Yield peaks at -0.06 pp (annualized) in Q8, from -0.02 in Q1 to +0.01 in Q20. Govt 10Y Yield peaks at -0.02 pp (annualized) in Q8, from -0.01 in Q1 to +0.01 in Q20. Govt 30Y Yield peaks at -0.00 pp (annualized) in Q8, from +0.00 in Q1 to +0.00 in Q20. Bond Price (7y) peaks at -0.29 % vs baseline in Q3, from -0.14 in Q1 to +0.14 in Q20. Bond Price 3M peaks at -0.03 % vs baseline in Q3, from -0.01 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +0.19 % vs baseline in Q11, from -0.13 in Q1 to +0.03 in Q20. Bond Price 5Y peaks at +0.25 % vs baseline in Q8, from +0.11 in Q1 to -0.04 in Q20. Bond Price 10Y peaks at +0.13 % vs baseline in Q8, from +0.04 in Q1 to -0.08 in Q20. Bond Price 30Y peaks at +0.08 % vs baseline in Q8, from -0.00 in Q1 to -0.06 in Q20. Equity Index peaks at -0.26 % vs baseline in Q10, from -0.03 in Q1 to +0.05 in Q20. VIX peaks at +15.09 index_level in Q10, from +15.01 in Q1 to +15.01 in Q20. Tobin's Q peaks at -0.24 % vs baseline in Q8, from -0.06 in Q1 to +0.09 in Q20. House Prices peaks at -0.13 % vs baseline in Q15, from -0.00 in Q1 to -0.10 in Q20. Bank Equity peaks at -0.00 % vs baseline in Q19, from +0.00 in Q1 to -0.00 in Q20. Bank Credit peaks at -0.00 % vs baseline in Q19, from +0.00 in Q1 to -0.00 in Q20. Credit Spread peaks at +0.00 pp in Q19, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.51 % vs baseline in Q5, from -0.28 in Q1 to -0.05 in Q20. vs USD peaks at -0.80 % vs baseline in Q3, from -0.54 in Q1 to -0.25 in Q20.

Commodities. Energy Price peaks at +80.03 USD/bbl (level) in Q3, from +80.01 in Q1 to +79.96 in Q20. Metals Price peaks at +143.18 index (level) in Q3, from +128.59 in Q1 to +108.65 in Q20. Food Price peaks at +100.04 index (level) in Q3, from +100.02 in Q1 to +99.95 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q3, from +4.00 in Q1 to +4.00 in Q20. Copper Price peaks at +100.01 index (level) in Q3, from +100.01 in Q1 to +99.97 in Q20. Wheat Price peaks at +100.03 index (level) in Q3, from +100.01 in Q1 to +99.98 in Q20. Gold Price peaks at +2008.23 USD/oz (level) in Q11, from +2003.83 in Q1 to +2003.50 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.11 % vs baseline in Q3, from +0.08 in Q1 to +0.03 in Q20. Services GDP peaks at -0.08 % vs baseline in Q11, from -0.00 in Q1 to +0.01 in Q20. Capital Stock peaks at -0.02 % vs baseline in Q16, from -0.00 in Q1 to -0.02 in Q20.

Timing. The GDP response has mostly faded by Q18 (Q20 is +0.01%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/AR_Y.png)

![CPI Inflation](charts/AR_pi_cpi.png)

![Equity Index](charts/AR_equity.png)

![Gold Price](charts/AR_P_gold.png)

![Metals Price](charts/AR_P_metals.png)

![Food Price](charts/AR_P_food.png)

![Wheat Price](charts/AR_P_wheat.png)

![Copper Price](charts/AR_P_copper.png)

![Energy Price](charts/AR_P_energy.png)

![VIX](charts/AR_vix.png)

![Gas Price](charts/AR_P_gas.png)

![vs USD](charts/AR_USD.png)

[Q1–Q20 JSON for Argentina](numbers/AR.json)

## JP — Japan

The main impact of a 20% metals-supply cut on Japan would be a moderate drop in GDP of 0.15% by Q3. Equities peak at -0.40% in Q4.

Demand and trade. Consumption peaks at -0.09 % vs baseline in Q4, from -0.05 in Q1 to -0.02 in Q20. Investment peaks at -0.40 % vs baseline in Q3, from -0.24 in Q1 to -0.08 in Q20. Net Exports peaks at -0.85 % vs baseline in Q3, from -0.56 in Q1 to -0.17 in Q20. Gov Spending peaks at +0.03 % vs baseline in Q4, from +0.02 in Q1 to +0.01 in Q20. Gov Debt peaks at -0.04 % vs baseline in Q20, from -0.00 in Q1 to -0.04 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.99 % vs baseline in Q4, from +0.61 in Q1 to +0.11 in Q20.

Labour. Employment peaks at -0.11 % vs baseline in Q8, from -0.02 in Q1 to -0.05 in Q20. Unemployment peaks at +0.08 pp in Q8, from +0.01 in Q1 to +0.04 in Q20. Real Wages peaks at +0.06 % vs baseline in Q11, from -0.00 in Q1 to +0.02 in Q20.

Prices. The three-year CPI impulse is +0.09 percentage points. CPI Inflation peaks at +0.03 pp in Q2, from +0.03 in Q1 to -0.01 in Q20. Domestic Infl. peaks at +0.02 pp in Q2, from +0.02 in Q1 to -0.01 in Q20. Marginal Cost peaks at -0.08 % vs baseline in Q4, from -0.05 in Q1 to -0.02 in Q20.

Financial conditions. Policy Rate peaks at +0.01 pp (annualized) in Q6, from +0.00 in Q1 to -0.00 in Q20. Real Rate peaks at +0.00 pp (annualized) in Q6, from +0.00 in Q1 to -0.00 in Q20. Govt 3M Yield peaks at +0.01 pp (annualized) in Q6, from +0.00 in Q1 to -0.00 in Q20. Govt 2Y Yield peaks at +0.01 pp (annualized) in Q3, from +0.01 in Q1 to -0.00 in Q20. Govt 5Y Yield peaks at +0.01 pp (annualized) in Q1, from +0.01 in Q1 to -0.01 in Q20. Govt 10Y Yield peaks at -0.00 pp (annualized) in Q20, from +0.00 in Q1 to -0.00 in Q20. Govt 30Y Yield peaks at -0.00 pp (annualized) in Q18, from -0.00 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at -0.17 % vs baseline in Q5, from -0.05 in Q1 to +0.06 in Q20. Bond Price 3M peaks at -0.00 % vs baseline in Q6, from -0.00 in Q1 to +0.00 in Q20. Bond Price 2Y peaks at -0.02 % vs baseline in Q3, from -0.02 in Q1 to +0.01 in Q20. Bond Price 5Y peaks at -0.03 % vs baseline in Q1, from -0.03 in Q1 to +0.02 in Q20. Bond Price 10Y peaks at +0.04 % vs baseline in Q20, from -0.01 in Q1 to +0.04 in Q20. Bond Price 30Y peaks at +0.05 % vs baseline in Q18, from +0.02 in Q1 to +0.05 in Q20. Equity Index peaks at -0.40 % vs baseline in Q4, from -0.25 in Q1 to -0.08 in Q20. VIX peaks at +15.09 index_level in Q10, from +15.01 in Q1 to +15.01 in Q20. Tobin's Q peaks at -0.28 % vs baseline in Q3, from -0.17 in Q1 to -0.06 in Q20. House Prices peaks at -0.11 % vs baseline in Q15, from -0.01 in Q1 to -0.10 in Q20. Bank Equity peaks at -0.06 % vs baseline in Q12, from -0.01 in Q1 to -0.05 in Q20. Bank Credit peaks at -0.04 % vs baseline in Q12, from -0.00 in Q1 to -0.04 in Q20. Credit Spread peaks at +0.00 pp in Q12, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -3.41 % vs baseline in Q3, from -2.21 in Q1 to -0.62 in Q20. vs USD peaks at +0.57 % vs baseline in Q4, from +0.33 in Q1 to -0.05 in Q20.

Commodities. Energy Price peaks at +80.03 USD/bbl (level) in Q3, from +80.01 in Q1 to +79.96 in Q20. Metals Price peaks at +143.18 index (level) in Q3, from +128.59 in Q1 to +108.65 in Q20. Food Price peaks at +100.04 index (level) in Q3, from +100.02 in Q1 to +99.95 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q3, from +4.00 in Q1 to +4.00 in Q20. Copper Price peaks at +100.01 index (level) in Q3, from +100.01 in Q1 to +99.97 in Q20. Wheat Price peaks at +100.03 index (level) in Q3, from +100.01 in Q1 to +99.98 in Q20. Gold Price peaks at +2008.23 USD/oz (level) in Q11, from +2003.83 in Q1 to +2003.50 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.34 % vs baseline in Q4, from -0.21 in Q1 to -0.04 in Q20. Services GDP peaks at -0.10 % vs baseline in Q3, from -0.07 in Q1 to -0.02 in Q20. Capital Stock peaks at -0.02 % vs baseline in Q20, from -0.00 in Q1 to -0.02 in Q20.

Timing. The GDP response has mostly faded by Q20 (Q20 is -0.03%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/JP_Y.png)

![CPI Inflation](charts/JP_pi_cpi.png)

![Equity Index](charts/JP_equity.png)

![Gold Price](charts/JP_P_gold.png)

![Metals Price](charts/JP_P_metals.png)

![Food Price](charts/JP_P_food.png)

![Wheat Price](charts/JP_P_wheat.png)

![Copper Price](charts/JP_P_copper.png)

![Energy Price](charts/JP_P_energy.png)

![VIX](charts/JP_vix.png)

![Gas Price](charts/JP_P_gas.png)

![NEER](charts/JP_NEER.png)

[Q1–Q20 JSON for Japan](numbers/JP.json)

## DE — Germany

The main impact of a 20% metals-supply cut on Germany would be a moderate drop in GDP of 0.12% by Q4. Equities peak at -0.25% in Q4.

Demand and trade. Consumption peaks at -0.06 % vs baseline in Q4, from -0.03 in Q1 to -0.02 in Q20. Investment peaks at -0.38 % vs baseline in Q4, from -0.21 in Q1 to -0.03 in Q20. Net Exports peaks at -0.64 % vs baseline in Q3, from -0.42 in Q1 to -0.13 in Q20. Gov Spending peaks at +0.02 % vs baseline in Q4, from +0.02 in Q1 to +0.01 in Q20. Gov Debt peaks at +0.02 % vs baseline in Q17, from +0.00 in Q1 to +0.01 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.87 % vs baseline in Q3, from +0.58 in Q1 to +0.16 in Q20.

Labour. Employment peaks at -0.09 % vs baseline in Q10, from -0.01 in Q1 to -0.05 in Q20. Unemployment peaks at +0.07 pp in Q9, from +0.01 in Q1 to +0.04 in Q20. Real Wages peaks at -0.08 % vs baseline in Q20, from -0.00 in Q1 to -0.08 in Q20.

Prices. The three-year CPI impulse is +0.06 percentage points. CPI Inflation peaks at +0.03 pp in Q2, from +0.02 in Q1 to -0.01 in Q20. Domestic Infl. peaks at +0.02 pp in Q2, from +0.01 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.07 % vs baseline in Q4, from -0.04 in Q1 to -0.02 in Q20.

Financial conditions. Policy Rate peaks at +0.05 pp (annualized) in Q5, from +0.02 in Q1 to -0.03 in Q20. Real Rate peaks at +0.01 pp (annualized) in Q5, from +0.00 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at +0.05 pp (annualized) in Q5, from +0.02 in Q1 to -0.03 in Q20. Govt 2Y Yield peaks at +0.04 pp (annualized) in Q2, from +0.04 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at -0.02 pp (annualized) in Q15, from +0.01 in Q1 to -0.02 in Q20. Govt 10Y Yield peaks at -0.01 pp (annualized) in Q13, from -0.00 in Q1 to -0.01 in Q20. Govt 30Y Yield peaks at -0.00 pp (annualized) in Q13, from -0.00 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at -0.37 % vs baseline in Q5, from -0.11 in Q1 to +0.19 in Q20. Bond Price 3M peaks at -0.01 % vs baseline in Q5, from -0.00 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at -0.08 % vs baseline in Q2, from -0.08 in Q1 to +0.05 in Q20. Bond Price 5Y peaks at +0.10 % vs baseline in Q15, from -0.05 in Q1 to +0.08 in Q20. Bond Price 10Y peaks at +0.11 % vs baseline in Q13, from +0.02 in Q1 to +0.09 in Q20. Bond Price 30Y peaks at +0.09 % vs baseline in Q13, from +0.03 in Q1 to +0.07 in Q20. Equity Index peaks at -0.25 % vs baseline in Q4, from -0.15 in Q1 to -0.04 in Q20. VIX peaks at +15.09 index_level in Q10, from +15.01 in Q1 to +15.01 in Q20. Tobin's Q peaks at -0.27 % vs baseline in Q4, from -0.15 in Q1 to -0.02 in Q20. House Prices peaks at -0.11 % vs baseline in Q15, from -0.01 in Q1 to -0.10 in Q20. Bank Equity peaks at -0.05 % vs baseline in Q13, from -0.00 in Q1 to -0.04 in Q20. Bank Credit peaks at -0.04 % vs baseline in Q13, from -0.00 in Q1 to -0.03 in Q20. Credit Spread peaks at +0.00 pp in Q12, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.99 % vs baseline in Q3, from -0.65 in Q1 to -0.19 in Q20. vs USD peaks at +0.46 % vs baseline in Q3, from +0.30 in Q1 to -0.01 in Q20.

Commodities. Energy Price peaks at +80.03 USD/bbl (level) in Q3, from +80.01 in Q1 to +79.96 in Q20. Metals Price peaks at +143.18 index (level) in Q3, from +128.59 in Q1 to +108.65 in Q20. Food Price peaks at +100.04 index (level) in Q3, from +100.02 in Q1 to +99.95 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q3, from +4.00 in Q1 to +4.00 in Q20. Copper Price peaks at +100.01 index (level) in Q3, from +100.01 in Q1 to +99.97 in Q20. Wheat Price peaks at +100.03 index (level) in Q3, from +100.01 in Q1 to +99.98 in Q20. Gold Price peaks at +2008.23 USD/oz (level) in Q11, from +2003.83 in Q1 to +2003.50 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.30 % vs baseline in Q3, from -0.19 in Q1 to -0.05 in Q20. Services GDP peaks at -0.08 % vs baseline in Q4, from -0.05 in Q1 to -0.02 in Q20. Capital Stock peaks at -0.02 % vs baseline in Q20, from -0.00 in Q1 to -0.02 in Q20.

Timing. The GDP response has mostly faded by Q20 (Q20 is -0.03%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/DE_Y.png)

![CPI Inflation](charts/DE_pi_cpi.png)

![Equity Index](charts/DE_equity.png)

![Gold Price](charts/DE_P_gold.png)

![Metals Price](charts/DE_P_metals.png)

![Food Price](charts/DE_P_food.png)

![Wheat Price](charts/DE_P_wheat.png)

![Copper Price](charts/DE_P_copper.png)

![Energy Price](charts/DE_P_energy.png)

![VIX](charts/DE_vix.png)

![Gas Price](charts/DE_P_gas.png)

![NEER](charts/DE_NEER.png)

[Q1–Q20 JSON for Germany](numbers/DE.json)

## SE — Sweden

The main impact of a 20% metals-supply cut on Sweden would be a moderate rise in GDP of 0.12% by Q3. Equities peak at +0.32% in Q3.

Demand and trade. Consumption peaks at +0.07 % vs baseline in Q4, from +0.04 in Q1 to +0.01 in Q20. Investment peaks at +0.28 % vs baseline in Q2, from +0.19 in Q1 to +0.07 in Q20. Net Exports peaks at +0.84 % vs baseline in Q3, from +0.56 in Q1 to +0.16 in Q20. Gov Spending peaks at +0.06 % vs baseline in Q3, from +0.04 in Q1 to +0.01 in Q20. Gov Debt peaks at -0.04 % vs baseline in Q10, from -0.00 in Q1 to -0.03 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -4.35 % vs baseline in Q3, from -2.87 in Q1 to -0.92 in Q20.

Labour. Employment peaks at +0.08 % vs baseline in Q8, from +0.01 in Q1 to +0.04 in Q20. Unemployment peaks at -0.05 pp in Q6, from -0.01 in Q1 to -0.01 in Q20. Real Wages peaks at +0.13 % vs baseline in Q18, from +0.00 in Q1 to +0.13 in Q20.

Prices. The three-year CPI impulse is +0.10 percentage points. CPI Inflation peaks at +0.03 pp in Q2, from +0.02 in Q1 to -0.00 in Q20. Domestic Infl. peaks at +0.02 pp in Q2, from +0.01 in Q1 to -0.00 in Q20. Marginal Cost peaks at +0.07 % vs baseline in Q3, from +0.05 in Q1 to +0.01 in Q20.

Financial conditions. Policy Rate peaks at +0.08 pp (annualized) in Q5, from +0.02 in Q1 to -0.02 in Q20. Real Rate peaks at +0.02 pp (annualized) in Q5, from +0.01 in Q1 to -0.00 in Q20. Govt 3M Yield peaks at +0.08 pp (annualized) in Q5, from +0.02 in Q1 to -0.02 in Q20. Govt 2Y Yield peaks at +0.06 pp (annualized) in Q2, from +0.06 in Q1 to -0.02 in Q20. Govt 5Y Yield peaks at +0.03 pp (annualized) in Q1, from +0.03 in Q1 to -0.01 in Q20. Govt 10Y Yield peaks at +0.01 pp (annualized) in Q1, from +0.01 in Q1 to -0.01 in Q20. Govt 30Y Yield peaks at +0.00 pp (annualized) in Q1, from +0.00 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at -0.47 % vs baseline in Q5, from -0.13 in Q1 to +0.10 in Q20. Bond Price 3M peaks at -0.02 % vs baseline in Q5, from -0.01 in Q1 to +0.00 in Q20. Bond Price 2Y peaks at -0.12 % vs baseline in Q2, from -0.11 in Q1 to +0.03 in Q20. Bond Price 5Y peaks at -0.12 % vs baseline in Q1, from -0.12 in Q1 to +0.05 in Q20. Bond Price 10Y peaks at -0.07 % vs baseline in Q1, from -0.07 in Q1 to +0.05 in Q20. Bond Price 30Y peaks at -0.05 % vs baseline in Q1, from -0.05 in Q1 to +0.04 in Q20. Equity Index peaks at +0.32 % vs baseline in Q3, from +0.23 in Q1 to +0.07 in Q20. VIX peaks at +15.09 index_level in Q10, from +15.01 in Q1 to +15.01 in Q20. Tobin's Q peaks at +0.20 % vs baseline in Q2, from +0.14 in Q1 to +0.05 in Q20. House Prices peaks at +0.08 % vs baseline in Q12, from +0.01 in Q1 to +0.07 in Q20. Bank Equity peaks at +0.01 % vs baseline in Q11, from +0.00 in Q1 to +0.01 in Q20. Bank Credit peaks at +0.00 % vs baseline in Q11, from +0.00 in Q1 to +0.00 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +4.47 % vs baseline in Q3, from +2.95 in Q1 to +0.94 in Q20. vs USD peaks at -4.77 % vs baseline in Q3, from -3.15 in Q1 to -1.08 in Q20.

Commodities. Energy Price peaks at +80.03 USD/bbl (level) in Q3, from +80.01 in Q1 to +79.96 in Q20. Metals Price peaks at +143.18 index (level) in Q3, from +128.59 in Q1 to +108.65 in Q20. Food Price peaks at +100.04 index (level) in Q3, from +100.02 in Q1 to +99.95 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q3, from +4.00 in Q1 to +4.00 in Q20. Copper Price peaks at +100.01 index (level) in Q3, from +100.01 in Q1 to +99.97 in Q20. Wheat Price peaks at +100.03 index (level) in Q3, from +100.01 in Q1 to +99.98 in Q20. Gold Price peaks at +2008.23 USD/oz (level) in Q11, from +2003.83 in Q1 to +2003.50 in Q20.

Sectoral and capital. Manuf. GDP peaks at +1.33 % vs baseline in Q3, from +0.88 in Q1 to +0.28 in Q20. Services GDP peaks at +0.08 % vs baseline in Q3, from +0.06 in Q1 to +0.01 in Q20. Capital Stock peaks at +0.01 % vs baseline in Q20, from +0.00 in Q1 to +0.01 in Q20.

Timing. The GDP response has mostly faded by Q14 (Q20 is +0.02%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/SE_Y.png)

![CPI Inflation](charts/SE_pi_cpi.png)

![Equity Index](charts/SE_equity.png)

![Gold Price](charts/SE_P_gold.png)

![Metals Price](charts/SE_P_metals.png)

![Food Price](charts/SE_P_food.png)

![Wheat Price](charts/SE_P_wheat.png)

![Copper Price](charts/SE_P_copper.png)

![Energy Price](charts/SE_P_energy.png)

![VIX](charts/SE_vix.png)

![vs USD](charts/SE_USD.png)

![NEER](charts/SE_NEER.png)

[Q1–Q20 JSON for Sweden](numbers/SE.json)

## BR — Brazil

The main impact of a 20% metals-supply cut on Brazil would be a moderate rise in GDP of 0.12% by Q3. Equities peak at +0.20% in Q2.

Demand and trade. Consumption peaks at +0.06 % vs baseline in Q4, from +0.03 in Q1 to -0.02 in Q20. Investment peaks at +0.20 % vs baseline in Q2, from +0.15 in Q1 to +0.01 in Q20. Net Exports peaks at +0.85 % vs baseline in Q3, from +0.57 in Q1 to +0.18 in Q20. Gov Spending peaks at +0.13 % vs baseline in Q3, from +0.09 in Q1 to +0.04 in Q20. Gov Debt peaks at +0.02 % vs baseline in Q8, from +0.00 in Q1 to +0.00 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -2.30 % vs baseline in Q3, from -1.48 in Q1 to -0.34 in Q20.

Labour. Employment peaks at +0.07 % vs baseline in Q6, from +0.01 in Q1 to -0.03 in Q20. Unemployment peaks at -0.02 pp in Q5, from -0.01 in Q1 to +0.01 in Q20. Real Wages peaks at +0.14 % vs baseline in Q13, from +0.00 in Q1 to +0.08 in Q20.

Prices. The three-year CPI impulse is +0.13 percentage points. CPI Inflation peaks at +0.03 pp in Q2, from +0.02 in Q1 to -0.01 in Q20. Domestic Infl. peaks at +0.02 pp in Q2, from +0.01 in Q1 to -0.00 in Q20. Marginal Cost peaks at +0.07 % vs baseline in Q3, from +0.05 in Q1 to -0.02 in Q20.

Financial conditions. Policy Rate peaks at +0.16 pp (annualized) in Q4, from +0.06 in Q1 to -0.05 in Q20. Real Rate peaks at +0.04 pp (annualized) in Q4, from +0.01 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at +0.16 pp (annualized) in Q4, from +0.06 in Q1 to -0.05 in Q20. Govt 2Y Yield peaks at +0.12 pp (annualized) in Q2, from +0.12 in Q1 to -0.04 in Q20. Govt 5Y Yield peaks at +0.04 pp (annualized) in Q1, from +0.04 in Q1 to -0.02 in Q20. Govt 10Y Yield peaks at -0.02 pp (annualized) in Q12, from +0.01 in Q1 to -0.01 in Q20. Govt 30Y Yield peaks at -0.01 pp (annualized) in Q12, from +0.00 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at -0.68 % vs baseline in Q4, from -0.23 in Q1 to +0.21 in Q20. Bond Price 3M peaks at -0.04 % vs baseline in Q4, from -0.01 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at -0.24 % vs baseline in Q2, from -0.23 in Q1 to +0.08 in Q20. Bond Price 5Y peaks at -0.17 % vs baseline in Q1, from -0.17 in Q1 to +0.11 in Q20. Bond Price 10Y peaks at +0.16 % vs baseline in Q12, from -0.07 in Q1 to +0.10 in Q20. Bond Price 30Y peaks at +0.11 % vs baseline in Q12, from -0.05 in Q1 to +0.07 in Q20. Equity Index peaks at +0.20 % vs baseline in Q2, from +0.15 in Q1 to -0.03 in Q20. VIX peaks at +15.09 index_level in Q10, from +15.01 in Q1 to +15.01 in Q20. Tobin's Q peaks at +0.14 % vs baseline in Q2, from +0.11 in Q1 to +0.00 in Q20. House Prices peaks at +0.06 % vs baseline in Q6, from +0.01 in Q1 to -0.02 in Q20. Bank Equity peaks at +0.01 % vs baseline in Q11, from +0.00 in Q1 to +0.01 in Q20. Bank Credit peaks at +0.00 % vs baseline in Q11, from +0.00 in Q1 to +0.00 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +1.90 % vs baseline in Q3, from +1.22 in Q1 to +0.27 in Q20. vs USD peaks at -2.72 % vs baseline in Q3, from -1.76 in Q1 to -0.51 in Q20.

Commodities. Energy Price peaks at +80.03 USD/bbl (level) in Q3, from +80.01 in Q1 to +79.96 in Q20. Metals Price peaks at +143.18 index (level) in Q3, from +128.59 in Q1 to +108.65 in Q20. Food Price peaks at +100.04 index (level) in Q3, from +100.02 in Q1 to +99.95 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q3, from +4.00 in Q1 to +4.00 in Q20. Copper Price peaks at +100.01 index (level) in Q3, from +100.01 in Q1 to +99.97 in Q20. Wheat Price peaks at +100.03 index (level) in Q3, from +100.01 in Q1 to +99.98 in Q20. Gold Price peaks at +2008.23 USD/oz (level) in Q11, from +2003.83 in Q1 to +2003.50 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.71 % vs baseline in Q3, from +0.46 in Q1 to +0.10 in Q20. Services GDP peaks at +0.08 % vs baseline in Q3, from +0.05 in Q1 to -0.02 in Q20. Capital Stock peaks at -0.00 % vs baseline in Q19, from +0.00 in Q1 to -0.00 in Q20.

Timing. The GDP response has mostly faded by Q8 (Q20 is -0.03%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/BR_Y.png)

![CPI Inflation](charts/BR_pi_cpi.png)

![Equity Index](charts/BR_equity.png)

![Gold Price](charts/BR_P_gold.png)

![Metals Price](charts/BR_P_metals.png)

![Food Price](charts/BR_P_food.png)

![Wheat Price](charts/BR_P_wheat.png)

![Copper Price](charts/BR_P_copper.png)

![Energy Price](charts/BR_P_energy.png)

![VIX](charts/BR_vix.png)

![Gas Price](charts/BR_P_gas.png)

![vs USD](charts/BR_USD.png)

[Q1–Q20 JSON for Brazil](numbers/BR.json)

## TR — Turkey

The main impact of a 20% metals-supply cut on Turkey would be a moderate drop in GDP of 0.11% by Q9. Equities peak at -0.23% in Q7.

Demand and trade. Consumption peaks at -0.06 % vs baseline in Q10, from -0.03 in Q1 to -0.00 in Q20. Investment peaks at -0.37 % vs baseline in Q5, from -0.19 in Q1 to +0.11 in Q20. Net Exports peaks at -0.42 % vs baseline in Q3, from -0.28 in Q1 to -0.08 in Q20. Gov Spending peaks at +0.02 % vs baseline in Q10, from +0.01 in Q1 to -0.00 in Q20. Gov Debt peaks at -0.11 % vs baseline in Q17, from -0.00 in Q1 to -0.10 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.29 % vs baseline in Q8, from +0.14 in Q1 to +0.07 in Q20.

Labour. Employment peaks at -0.10 % vs baseline in Q14, from -0.01 in Q1 to -0.06 in Q20. Unemployment peaks at +0.03 pp in Q11, from +0.00 in Q1 to +0.01 in Q20. Real Wages peaks at -0.17 % vs baseline in Q20, from -0.00 in Q1 to -0.17 in Q20.

Prices. The three-year CPI impulse is +0.08 percentage points. CPI Inflation peaks at +0.02 pp in Q2, from +0.02 in Q1 to -0.01 in Q20. Domestic Infl. peaks at +0.02 pp in Q2, from +0.01 in Q1 to -0.01 in Q20. Marginal Cost peaks at -0.07 % vs baseline in Q10, from -0.03 in Q1 to +0.00 in Q20.

Financial conditions. Policy Rate peaks at +0.09 pp (annualized) in Q4, from +0.04 in Q1 to -0.05 in Q20. Real Rate peaks at +0.02 pp (annualized) in Q4, from +0.01 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at +0.09 pp (annualized) in Q4, from +0.04 in Q1 to -0.05 in Q20. Govt 2Y Yield peaks at -0.06 pp (annualized) in Q13, from +0.06 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at -0.04 pp (annualized) in Q9, from -0.01 in Q1 to -0.01 in Q20. Govt 10Y Yield peaks at -0.02 pp (annualized) in Q9, from -0.01 in Q1 to -0.00 in Q20. Govt 30Y Yield peaks at -0.01 pp (annualized) in Q9, from -0.00 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at -0.29 % vs baseline in Q4, from -0.13 in Q1 to +0.17 in Q20. Bond Price 3M peaks at -0.02 % vs baseline in Q4, from -0.01 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +0.12 % vs baseline in Q13, from -0.12 in Q1 to +0.06 in Q20. Bond Price 5Y peaks at +0.19 % vs baseline in Q9, from +0.03 in Q1 to +0.04 in Q20. Bond Price 10Y peaks at +0.14 % vs baseline in Q9, from +0.05 in Q1 to +0.02 in Q20. Bond Price 30Y peaks at +0.10 % vs baseline in Q9, from +0.02 in Q1 to +0.01 in Q20. Equity Index peaks at -0.23 % vs baseline in Q7, from -0.10 in Q1 to +0.04 in Q20. VIX peaks at +15.09 index_level in Q10, from +15.01 in Q1 to +15.01 in Q20. Tobin's Q peaks at -0.26 % vs baseline in Q5, from -0.13 in Q1 to +0.07 in Q20. House Prices peaks at -0.13 % vs baseline in Q14, from -0.01 in Q1 to -0.10 in Q20. Bank Equity peaks at -0.02 % vs baseline in Q12, from -0.00 in Q1 to -0.01 in Q20. Bank Credit peaks at -0.01 % vs baseline in Q12, from -0.00 in Q1 to -0.01 in Q20. Credit Spread peaks at +0.00 pp in Q12, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.34 % vs baseline in Q6, from -0.19 in Q1 to -0.08 in Q20. vs USD peaks at -0.18 % vs baseline in Q2, from -0.14 in Q1 to -0.09 in Q20.

Commodities. Energy Price peaks at +80.03 USD/bbl (level) in Q3, from +80.01 in Q1 to +79.96 in Q20. Metals Price peaks at +143.18 index (level) in Q3, from +128.59 in Q1 to +108.65 in Q20. Food Price peaks at +100.04 index (level) in Q3, from +100.02 in Q1 to +99.95 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q3, from +4.00 in Q1 to +4.00 in Q20. Copper Price peaks at +100.01 index (level) in Q3, from +100.01 in Q1 to +99.97 in Q20. Wheat Price peaks at +100.03 index (level) in Q3, from +100.01 in Q1 to +99.98 in Q20. Gold Price peaks at +2008.23 USD/oz (level) in Q11, from +2003.83 in Q1 to +2003.50 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.12 % vs baseline in Q8, from -0.06 in Q1 to -0.02 in Q20. Services GDP peaks at -0.07 % vs baseline in Q9, from -0.03 in Q1 to +0.00 in Q20. Capital Stock peaks at -0.02 % vs baseline in Q16, from -0.00 in Q1 to -0.02 in Q20.

Timing. The GDP response has mostly faded by Q18 (Q20 is +0.00%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/TR_Y.png)

![CPI Inflation](charts/TR_pi_cpi.png)

![Equity Index](charts/TR_equity.png)

![Gold Price](charts/TR_P_gold.png)

![Metals Price](charts/TR_P_metals.png)

![Food Price](charts/TR_P_food.png)

![Wheat Price](charts/TR_P_wheat.png)

![Copper Price](charts/TR_P_copper.png)

![Energy Price](charts/TR_P_energy.png)

![VIX](charts/TR_vix.png)

![Gas Price](charts/TR_P_gas.png)

![Net Exports](charts/TR_NX.png)

[Q1–Q20 JSON for Turkey](numbers/TR.json)

## IT — Italy

The main impact of a 20% metals-supply cut on Italy would be only a small drop in GDP of 0.10% by Q4. Equities peak at -0.20% in Q4.

Demand and trade. Consumption peaks at -0.05 % vs baseline in Q4, from -0.03 in Q1 to -0.01 in Q20. Investment peaks at -0.32 % vs baseline in Q4, from -0.18 in Q1 to -0.01 in Q20. Net Exports peaks at -0.51 % vs baseline in Q3, from -0.34 in Q1 to -0.10 in Q20. Gov Spending peaks at +0.02 % vs baseline in Q4, from +0.01 in Q1 to +0.00 in Q20. Gov Debt peaks at +0.01 % vs baseline in Q5, from +0.00 in Q1 to +0.00 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.44 % vs baseline in Q3, from +0.29 in Q1 to +0.07 in Q20.

Labour. Employment peaks at -0.07 % vs baseline in Q10, from -0.01 in Q1 to -0.05 in Q20. Unemployment peaks at +0.03 pp in Q8, from +0.01 in Q1 to +0.02 in Q20. Real Wages peaks at +0.03 % vs baseline in Q10, from -0.00 in Q1 to -0.02 in Q20.

Prices. The three-year CPI impulse is +0.08 percentage points. CPI Inflation peaks at +0.03 pp in Q2, from +0.02 in Q1 to -0.01 in Q20. Domestic Infl. peaks at +0.02 pp in Q2, from +0.01 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.05 % vs baseline in Q4, from -0.03 in Q1 to -0.01 in Q20.

Financial conditions. Policy Rate peaks at +0.05 pp (annualized) in Q5, from +0.02 in Q1 to -0.03 in Q20. Real Rate peaks at +0.01 pp (annualized) in Q5, from +0.00 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at +0.05 pp (annualized) in Q5, from +0.02 in Q1 to -0.03 in Q20. Govt 2Y Yield peaks at +0.04 pp (annualized) in Q2, from +0.04 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at -0.02 pp (annualized) in Q15, from +0.01 in Q1 to -0.02 in Q20. Govt 10Y Yield peaks at -0.01 pp (annualized) in Q13, from -0.00 in Q1 to -0.01 in Q20. Govt 30Y Yield peaks at -0.00 pp (annualized) in Q13, from -0.00 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at -0.37 % vs baseline in Q5, from -0.11 in Q1 to +0.18 in Q20. Bond Price 3M peaks at -0.01 % vs baseline in Q5, from -0.00 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at -0.08 % vs baseline in Q2, from -0.08 in Q1 to +0.05 in Q20. Bond Price 5Y peaks at +0.10 % vs baseline in Q15, from -0.05 in Q1 to +0.08 in Q20. Bond Price 10Y peaks at +0.11 % vs baseline in Q13, from +0.02 in Q1 to +0.09 in Q20. Bond Price 30Y peaks at +0.09 % vs baseline in Q13, from +0.03 in Q1 to +0.07 in Q20. Equity Index peaks at -0.20 % vs baseline in Q4, from -0.11 in Q1 to -0.02 in Q20. VIX peaks at +15.09 index_level in Q10, from +15.01 in Q1 to +15.01 in Q20. Tobin's Q peaks at -0.22 % vs baseline in Q4, from -0.12 in Q1 to -0.01 in Q20. House Prices peaks at -0.08 % vs baseline in Q15, from -0.01 in Q1 to -0.08 in Q20. Bank Equity peaks at -0.03 % vs baseline in Q12, from -0.00 in Q1 to -0.03 in Q20. Bank Credit peaks at -0.03 % vs baseline in Q12, from -0.00 in Q1 to -0.02 in Q20. Credit Spread peaks at +0.00 pp in Q12, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.38 % vs baseline in Q3, from -0.25 in Q1 to -0.06 in Q20. vs USD peaks at -0.10 % vs baseline in Q18, from +0.01 in Q1 to -0.09 in Q20.

Commodities. Energy Price peaks at +80.03 USD/bbl (level) in Q3, from +80.01 in Q1 to +79.96 in Q20. Metals Price peaks at +143.18 index (level) in Q3, from +128.59 in Q1 to +108.65 in Q20. Food Price peaks at +100.04 index (level) in Q3, from +100.02 in Q1 to +99.95 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q3, from +4.00 in Q1 to +4.00 in Q20. Copper Price peaks at +100.01 index (level) in Q3, from +100.01 in Q1 to +99.97 in Q20. Wheat Price peaks at +100.03 index (level) in Q3, from +100.01 in Q1 to +99.98 in Q20. Gold Price peaks at +2008.23 USD/oz (level) in Q11, from +2003.83 in Q1 to +2003.50 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.15 % vs baseline in Q3, from -0.10 in Q1 to -0.03 in Q20. Services GDP peaks at -0.07 % vs baseline in Q4, from -0.04 in Q1 to -0.02 in Q20. Capital Stock peaks at -0.02 % vs baseline in Q20, from -0.00 in Q1 to -0.02 in Q20.

Timing. The GDP response has mostly faded by Q20 (Q20 is -0.02%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/IT_Y.png)

![CPI Inflation](charts/IT_pi_cpi.png)

![Equity Index](charts/IT_equity.png)

![Gold Price](charts/IT_P_gold.png)

![Metals Price](charts/IT_P_metals.png)

![Food Price](charts/IT_P_food.png)

![Wheat Price](charts/IT_P_wheat.png)

![Copper Price](charts/IT_P_copper.png)

![Energy Price](charts/IT_P_energy.png)

![VIX](charts/IT_vix.png)

![Gas Price](charts/IT_P_gas.png)

![Net Exports](charts/IT_NX.png)

[Q1–Q20 JSON for Italy](numbers/IT.json)

## PL — Poland

The main impact of a 20% metals-supply cut on Poland would be only a small drop in GDP of 0.08% by Q4. Equities peak at -0.20% in Q4.

Demand and trade. Consumption peaks at -0.05 % vs baseline in Q4, from -0.03 in Q1 to -0.01 in Q20. Investment peaks at -0.33 % vs baseline in Q4, from -0.18 in Q1 to +0.00 in Q20. Net Exports peaks at -0.42 % vs baseline in Q3, from -0.28 in Q1 to -0.08 in Q20. Gov Spending peaks at +0.02 % vs baseline in Q4, from +0.01 in Q1 to +0.00 in Q20. Gov Debt peaks at +0.00 % vs baseline in Q1, from +0.00 in Q1 to +0.00 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.86 % vs baseline in Q3, from +0.57 in Q1 to +0.21 in Q20.

Labour. Employment peaks at -0.07 % vs baseline in Q11, from -0.01 in Q1 to -0.04 in Q20. Unemployment peaks at +0.03 pp in Q10, from +0.01 in Q1 to +0.02 in Q20. Real Wages peaks at -0.08 % vs baseline in Q20, from -0.00 in Q1 to -0.08 in Q20.

Prices. The three-year CPI impulse is +0.08 percentage points. CPI Inflation peaks at +0.02 pp in Q2, from +0.02 in Q1 to -0.01 in Q20. Domestic Infl. peaks at +0.02 pp in Q2, from +0.01 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.05 % vs baseline in Q4, from -0.03 in Q1 to -0.01 in Q20.

Financial conditions. Policy Rate peaks at +0.07 pp (annualized) in Q4, from +0.02 in Q1 to -0.03 in Q20. Real Rate peaks at +0.02 pp (annualized) in Q4, from +0.01 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at +0.07 pp (annualized) in Q4, from +0.02 in Q1 to -0.03 in Q20. Govt 2Y Yield peaks at +0.05 pp (annualized) in Q2, from +0.05 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at -0.03 pp (annualized) in Q13, from +0.01 in Q1 to -0.02 in Q20. Govt 10Y Yield peaks at -0.02 pp (annualized) in Q12, from -0.00 in Q1 to -0.01 in Q20. Govt 30Y Yield peaks at -0.01 pp (annualized) in Q12, from -0.00 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at -0.30 % vs baseline in Q4, from -0.10 in Q1 to +0.14 in Q20. Bond Price 3M peaks at -0.02 % vs baseline in Q4, from -0.01 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at -0.10 % vs baseline in Q2, from -0.10 in Q1 to +0.06 in Q20. Bond Price 5Y peaks at +0.12 % vs baseline in Q13, from -0.05 in Q1 to +0.09 in Q20. Bond Price 10Y peaks at +0.13 % vs baseline in Q12, from +0.03 in Q1 to +0.10 in Q20. Bond Price 30Y peaks at +0.10 % vs baseline in Q12, from +0.03 in Q1 to +0.07 in Q20. Equity Index peaks at -0.20 % vs baseline in Q4, from -0.11 in Q1 to -0.01 in Q20. VIX peaks at +15.09 index_level in Q10, from +15.01 in Q1 to +15.01 in Q20. Tobin's Q peaks at -0.23 % vs baseline in Q4, from -0.12 in Q1 to +0.00 in Q20. House Prices peaks at -0.09 % vs baseline in Q15, from -0.01 in Q1 to -0.08 in Q20. Bank Equity peaks at -0.02 % vs baseline in Q13, from -0.00 in Q1 to -0.02 in Q20. Bank Credit peaks at -0.02 % vs baseline in Q13, from -0.00 in Q1 to -0.02 in Q20. Credit Spread peaks at +0.00 pp in Q12, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.70 % vs baseline in Q3, from -0.47 in Q1 to -0.18 in Q20. vs USD peaks at +0.44 % vs baseline in Q3, from +0.29 in Q1 to +0.04 in Q20.

Commodities. Energy Price peaks at +80.03 USD/bbl (level) in Q3, from +80.01 in Q1 to +79.96 in Q20. Metals Price peaks at +143.18 index (level) in Q3, from +128.59 in Q1 to +108.65 in Q20. Food Price peaks at +100.04 index (level) in Q3, from +100.02 in Q1 to +99.95 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q3, from +4.00 in Q1 to +4.00 in Q20. Copper Price peaks at +100.01 index (level) in Q3, from +100.01 in Q1 to +99.97 in Q20. Wheat Price peaks at +100.03 index (level) in Q3, from +100.01 in Q1 to +99.98 in Q20. Gold Price peaks at +2008.23 USD/oz (level) in Q11, from +2003.83 in Q1 to +2003.50 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.28 % vs baseline in Q3, from -0.19 in Q1 to -0.07 in Q20. Services GDP peaks at -0.05 % vs baseline in Q4, from -0.03 in Q1 to -0.01 in Q20. Capital Stock peaks at -0.02 % vs baseline in Q19, from -0.00 in Q1 to -0.02 in Q20.

Timing. The GDP response has mostly faded by Q20 (Q20 is -0.02%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/PL_Y.png)

![CPI Inflation](charts/PL_pi_cpi.png)

![Equity Index](charts/PL_equity.png)

![Gold Price](charts/PL_P_gold.png)

![Metals Price](charts/PL_P_metals.png)

![Food Price](charts/PL_P_food.png)

![Wheat Price](charts/PL_P_wheat.png)

![Copper Price](charts/PL_P_copper.png)

![Energy Price](charts/PL_P_energy.png)

![VIX](charts/PL_vix.png)

![Gas Price](charts/PL_P_gas.png)

![Real Exchange Rate](charts/PL_RER.png)

[Q1–Q20 JSON for Poland](numbers/PL.json)

## FR — France

The main impact of a 20% metals-supply cut on France would be only a small drop in GDP of 0.07% by Q4. Equities peak at -0.19% in Q5.

Demand and trade. Consumption peaks at -0.04 % vs baseline in Q4, from -0.02 in Q1 to -0.01 in Q20. Investment peaks at -0.27 % vs baseline in Q4, from -0.13 in Q1 to -0.00 in Q20. Net Exports peaks at -0.34 % vs baseline in Q3, from -0.22 in Q1 to -0.07 in Q20. Gov Spending peaks at +0.02 % vs baseline in Q4, from +0.01 in Q1 to +0.00 in Q20. Gov Debt peaks at +0.05 % vs baseline in Q18, from +0.00 in Q1 to +0.05 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.44 % vs baseline in Q3, from +0.29 in Q1 to +0.07 in Q20.

Labour. Employment peaks at -0.06 % vs baseline in Q12, from -0.01 in Q1 to -0.04 in Q20. Unemployment peaks at +0.04 pp in Q10, from +0.01 in Q1 to +0.02 in Q20. Real Wages peaks at +0.03 % vs baseline in Q10, from -0.00 in Q1 to -0.02 in Q20.

Prices. The three-year CPI impulse is +0.08 percentage points. CPI Inflation peaks at +0.03 pp in Q2, from +0.02 in Q1 to -0.01 in Q20. Domestic Infl. peaks at +0.02 pp in Q2, from +0.02 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.04 % vs baseline in Q4, from -0.02 in Q1 to -0.01 in Q20.

Financial conditions. Policy Rate peaks at +0.05 pp (annualized) in Q5, from +0.02 in Q1 to -0.03 in Q20. Real Rate peaks at +0.01 pp (annualized) in Q5, from +0.00 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at +0.05 pp (annualized) in Q5, from +0.02 in Q1 to -0.03 in Q20. Govt 2Y Yield peaks at +0.04 pp (annualized) in Q2, from +0.04 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at -0.02 pp (annualized) in Q15, from +0.01 in Q1 to -0.02 in Q20. Govt 10Y Yield peaks at -0.01 pp (annualized) in Q13, from -0.00 in Q1 to -0.01 in Q20. Govt 30Y Yield peaks at -0.00 pp (annualized) in Q13, from -0.00 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at -0.37 % vs baseline in Q5, from -0.11 in Q1 to +0.19 in Q20. Bond Price 3M peaks at -0.01 % vs baseline in Q5, from -0.00 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at -0.08 % vs baseline in Q2, from -0.08 in Q1 to +0.05 in Q20. Bond Price 5Y peaks at +0.10 % vs baseline in Q15, from -0.05 in Q1 to +0.08 in Q20. Bond Price 10Y peaks at +0.11 % vs baseline in Q13, from +0.02 in Q1 to +0.09 in Q20. Bond Price 30Y peaks at +0.09 % vs baseline in Q13, from +0.03 in Q1 to +0.07 in Q20. Equity Index peaks at -0.19 % vs baseline in Q5, from -0.10 in Q1 to -0.02 in Q20. VIX peaks at +15.09 index_level in Q10, from +15.01 in Q1 to +15.01 in Q20. Tobin's Q peaks at -0.19 % vs baseline in Q4, from -0.09 in Q1 to -0.00 in Q20. House Prices peaks at -0.07 % vs baseline in Q15, from -0.00 in Q1 to -0.07 in Q20. Bank Equity peaks at -0.03 % vs baseline in Q13, from -0.00 in Q1 to -0.03 in Q20. Bank Credit peaks at -0.03 % vs baseline in Q13, from -0.00 in Q1 to -0.02 in Q20. Credit Spread peaks at +0.00 pp in Q13, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.25 % vs baseline in Q3, from -0.17 in Q1 to -0.04 in Q20. vs USD peaks at -0.10 % vs baseline in Q18, from +0.01 in Q1 to -0.09 in Q20.

Commodities. Energy Price peaks at +80.03 USD/bbl (level) in Q3, from +80.01 in Q1 to +79.96 in Q20. Metals Price peaks at +143.18 index (level) in Q3, from +128.59 in Q1 to +108.65 in Q20. Food Price peaks at +100.04 index (level) in Q3, from +100.02 in Q1 to +99.95 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q3, from +4.00 in Q1 to +4.00 in Q20. Copper Price peaks at +100.01 index (level) in Q3, from +100.01 in Q1 to +99.97 in Q20. Wheat Price peaks at +100.03 index (level) in Q3, from +100.01 in Q1 to +99.98 in Q20. Gold Price peaks at +2008.23 USD/oz (level) in Q11, from +2003.83 in Q1 to +2003.50 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.15 % vs baseline in Q3, from -0.10 in Q1 to -0.02 in Q20. Services GDP peaks at -0.05 % vs baseline in Q4, from -0.03 in Q1 to -0.01 in Q20. Capital Stock peaks at -0.01 % vs baseline in Q20, from -0.00 in Q1 to -0.01 in Q20.

Timing. By Q20 GDP is still -0.02% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/FR_Y.png)

![CPI Inflation](charts/FR_pi_cpi.png)

![Equity Index](charts/FR_equity.png)

![Gold Price](charts/FR_P_gold.png)

![Metals Price](charts/FR_P_metals.png)

![Food Price](charts/FR_P_food.png)

![Wheat Price](charts/FR_P_wheat.png)

![Copper Price](charts/FR_P_copper.png)

![Energy Price](charts/FR_P_energy.png)

![VIX](charts/FR_vix.png)

![Gas Price](charts/FR_P_gas.png)

![Real Exchange Rate](charts/FR_RER.png)

[Q1–Q20 JSON for France](numbers/FR.json)

## NG — Nigeria

The main impact of a 20% metals-supply cut on Nigeria would be only a small drop in GDP of 0.07% by Q12. Equities peak at -0.12% in Q9.

Demand and trade. Consumption peaks at -0.04 % vs baseline in Q12, from -0.00 in Q1 to -0.01 in Q20. Investment peaks at -0.20 % vs baseline in Q7, from -0.05 in Q1 to +0.07 in Q20. Net Exports peaks at +0.01 % vs baseline in Q8, from +0.00 in Q1 to -0.00 in Q20. Gov Spending peaks at +0.01 % vs baseline in Q11, from +0.00 in Q1 to -0.00 in Q20. Gov Debt peaks at -0.14 % vs baseline in Q20, from +0.00 in Q1 to -0.14 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.08 % vs baseline in Q11, from -0.00 in Q1 to +0.01 in Q20.

Labour. Employment peaks at -0.05 % vs baseline in Q16, from +0.00 in Q1 to -0.04 in Q20. Unemployment peaks at +0.00 pp in Q13, from +0.00 in Q1 to +0.00 in Q20. Real Wages peaks at -0.08 % vs baseline in Q20, from +0.00 in Q1 to -0.08 in Q20.

Prices. The three-year CPI impulse is +0.09 percentage points. CPI Inflation peaks at +0.03 pp in Q2, from +0.02 in Q1 to -0.01 in Q20. Domestic Infl. peaks at +0.02 pp in Q2, from +0.02 in Q1 to -0.01 in Q20. Marginal Cost peaks at -0.04 % vs baseline in Q12, from +0.00 in Q1 to -0.00 in Q20.

Financial conditions. Policy Rate peaks at +0.09 pp (annualized) in Q4, from +0.03 in Q1 to -0.04 in Q20. Real Rate peaks at +0.02 pp (annualized) in Q4, from +0.01 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at +0.09 pp (annualized) in Q4, from +0.03 in Q1 to -0.04 in Q20. Govt 2Y Yield peaks at +0.06 pp (annualized) in Q1, from +0.06 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at -0.03 pp (annualized) in Q10, from +0.00 in Q1 to -0.01 in Q20. Govt 10Y Yield peaks at -0.01 pp (annualized) in Q10, from -0.00 in Q1 to -0.00 in Q20. Govt 30Y Yield peaks at -0.00 pp (annualized) in Q10, from +0.00 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at -0.22 % vs baseline in Q4, from -0.08 in Q1 to +0.11 in Q20. Bond Price 3M peaks at -0.02 % vs baseline in Q4, from -0.01 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at -0.12 % vs baseline in Q1, from -0.12 in Q1 to +0.05 in Q20. Bond Price 5Y peaks at +0.14 % vs baseline in Q10, from -0.01 in Q1 to +0.04 in Q20. Bond Price 10Y peaks at +0.11 % vs baseline in Q10, from +0.01 in Q1 to +0.03 in Q20. Bond Price 30Y peaks at +0.08 % vs baseline in Q10, from +0.00 in Q1 to +0.02 in Q20. Equity Index peaks at -0.12 % vs baseline in Q9, from -0.02 in Q1 to +0.02 in Q20. VIX peaks at +15.09 index_level in Q10, from +15.01 in Q1 to +15.01 in Q20. Tobin's Q peaks at -0.14 % vs baseline in Q7, from -0.03 in Q1 to +0.05 in Q20. House Prices peaks at -0.07 % vs baseline in Q16, from -0.00 in Q1 to -0.06 in Q20. Bank Equity peaks at -0.00 % vs baseline in Q19, from +0.00 in Q1 to -0.00 in Q20. Bank Credit peaks at -0.00 % vs baseline in Q19, from +0.00 in Q1 to -0.00 in Q20. Credit Spread peaks at +0.00 pp in Q19, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.31 % vs baseline in Q4, from -0.19 in Q1 to -0.06 in Q20. vs USD peaks at -0.41 % vs baseline in Q3, from -0.28 in Q1 to -0.15 in Q20.

Commodities. Energy Price peaks at +80.03 USD/bbl (level) in Q3, from +80.01 in Q1 to +79.96 in Q20. Metals Price peaks at +143.18 index (level) in Q3, from +128.59 in Q1 to +108.65 in Q20. Food Price peaks at +100.04 index (level) in Q3, from +100.02 in Q1 to +99.95 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q3, from +4.00 in Q1 to +4.00 in Q20. Copper Price peaks at +100.01 index (level) in Q3, from +100.01 in Q1 to +99.97 in Q20. Wheat Price peaks at +100.03 index (level) in Q3, from +100.01 in Q1 to +99.98 in Q20. Gold Price peaks at +2008.23 USD/oz (level) in Q11, from +2003.83 in Q1 to +2003.50 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.03 % vs baseline in Q11, from +0.00 in Q1 to -0.00 in Q20. Services GDP peaks at -0.03 % vs baseline in Q12, from -0.00 in Q1 to -0.00 in Q20. Capital Stock peaks at -0.01 % vs baseline in Q16, from -0.00 in Q1 to -0.01 in Q20.

Timing. The GDP response has mostly faded by Q19 (Q20 is -0.00%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/NG_Y.png)

![CPI Inflation](charts/NG_pi_cpi.png)

![Equity Index](charts/NG_equity.png)

![Gold Price](charts/NG_P_gold.png)

![Metals Price](charts/NG_P_metals.png)

![Food Price](charts/NG_P_food.png)

![Wheat Price](charts/NG_P_wheat.png)

![Copper Price](charts/NG_P_copper.png)

![Energy Price](charts/NG_P_energy.png)

![VIX](charts/NG_vix.png)

![Gas Price](charts/NG_P_gas.png)

![vs USD](charts/NG_USD.png)

[Q1–Q20 JSON for Nigeria](numbers/NG.json)

## UK — United Kingdom

The main impact of a 20% metals-supply cut on United Kingdom would be only a small drop in GDP of 0.06% by Q4. Equities peak at -0.19% in Q4.

Demand and trade. Consumption peaks at -0.04 % vs baseline in Q4, from -0.02 in Q1 to -0.01 in Q20. Investment peaks at -0.20 % vs baseline in Q4, from -0.11 in Q1 to -0.03 in Q20. Net Exports peaks at -0.34 % vs baseline in Q3, from -0.22 in Q1 to -0.07 in Q20. Gov Spending peaks at +0.01 % vs baseline in Q4, from +0.01 in Q1 to +0.00 in Q20. Gov Debt peaks at -0.00 % vs baseline in Q8, from -0.00 in Q1 to -0.00 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.51 % vs baseline in Q4, from +0.31 in Q1 to +0.01 in Q20.

Labour. Employment peaks at -0.06 % vs baseline in Q9, from -0.01 in Q1 to -0.03 in Q20. Unemployment peaks at +0.04 pp in Q9, from +0.01 in Q1 to +0.02 in Q20. Real Wages peaks at +0.04 % vs baseline in Q10, from -0.00 in Q1 to -0.02 in Q20.

Prices. The three-year CPI impulse is +0.08 percentage points. CPI Inflation peaks at +0.03 pp in Q2, from +0.02 in Q1 to -0.01 in Q20. Domestic Infl. peaks at +0.02 pp in Q2, from +0.02 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.04 % vs baseline in Q4, from -0.02 in Q1 to -0.01 in Q20.

Financial conditions. Policy Rate peaks at +0.02 pp (annualized) in Q6, from +0.00 in Q1 to -0.01 in Q20. Real Rate peaks at +0.01 pp (annualized) in Q6, from +0.00 in Q1 to -0.00 in Q20. Govt 3M Yield peaks at +0.02 pp (annualized) in Q6, from +0.00 in Q1 to -0.01 in Q20. Govt 2Y Yield peaks at +0.02 pp (annualized) in Q3, from +0.02 in Q1 to -0.01 in Q20. Govt 5Y Yield peaks at -0.01 pp (annualized) in Q20, from +0.01 in Q1 to -0.01 in Q20. Govt 10Y Yield peaks at -0.01 pp (annualized) in Q19, from -0.00 in Q1 to -0.01 in Q20. Govt 30Y Yield peaks at -0.00 pp (annualized) in Q16, from -0.00 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at -0.15 % vs baseline in Q6, from -0.04 in Q1 to +0.05 in Q20. Bond Price 3M peaks at -0.01 % vs baseline in Q6, from -0.00 in Q1 to +0.00 in Q20. Bond Price 2Y peaks at -0.04 % vs baseline in Q3, from -0.03 in Q1 to +0.02 in Q20. Bond Price 5Y peaks at +0.04 % vs baseline in Q20, from -0.04 in Q1 to +0.04 in Q20. Bond Price 10Y peaks at +0.07 % vs baseline in Q19, from +0.00 in Q1 to +0.07 in Q20. Bond Price 30Y peaks at +0.07 % vs baseline in Q16, from +0.04 in Q1 to +0.07 in Q20. Equity Index peaks at -0.19 % vs baseline in Q4, from -0.11 in Q1 to -0.02 in Q20. VIX peaks at +15.09 index_level in Q10, from +15.01 in Q1 to +15.01 in Q20. Tobin's Q peaks at -0.14 % vs baseline in Q4, from -0.08 in Q1 to -0.02 in Q20. House Prices peaks at -0.06 % vs baseline in Q16, from -0.00 in Q1 to -0.05 in Q20. Bank Equity peaks at -0.02 % vs baseline in Q13, from -0.00 in Q1 to -0.02 in Q20. Bank Credit peaks at -0.02 % vs baseline in Q13, from -0.00 in Q1 to -0.02 in Q20. Credit Spread peaks at +0.00 pp in Q13, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.62 % vs baseline in Q4, from -0.39 in Q1 to -0.02 in Q20. vs USD peaks at -0.16 % vs baseline in Q19, from +0.03 in Q1 to -0.16 in Q20.

Commodities. Energy Price peaks at +80.03 USD/bbl (level) in Q3, from +80.01 in Q1 to +79.96 in Q20. Metals Price peaks at +143.18 index (level) in Q3, from +128.59 in Q1 to +108.65 in Q20. Food Price peaks at +100.04 index (level) in Q3, from +100.02 in Q1 to +99.95 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q3, from +4.00 in Q1 to +4.00 in Q20. Copper Price peaks at +100.01 index (level) in Q3, from +100.01 in Q1 to +99.97 in Q20. Wheat Price peaks at +100.03 index (level) in Q3, from +100.01 in Q1 to +99.98 in Q20. Gold Price peaks at +2008.23 USD/oz (level) in Q11, from +2003.83 in Q1 to +2003.50 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.16 % vs baseline in Q4, from -0.10 in Q1 to -0.00 in Q20. Services GDP peaks at -0.05 % vs baseline in Q4, from -0.03 in Q1 to -0.01 in Q20. Capital Stock peaks at -0.01 % vs baseline in Q20, from -0.00 in Q1 to -0.01 in Q20.

Timing. The GDP response has mostly faded by Q20 (Q20 is -0.02%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/UK_Y.png)

![CPI Inflation](charts/UK_pi_cpi.png)

![Equity Index](charts/UK_equity.png)

![Gold Price](charts/UK_P_gold.png)

![Metals Price](charts/UK_P_metals.png)

![Food Price](charts/UK_P_food.png)

![Wheat Price](charts/UK_P_wheat.png)

![Copper Price](charts/UK_P_copper.png)

![Energy Price](charts/UK_P_energy.png)

![VIX](charts/UK_vix.png)

![Gas Price](charts/UK_P_gas.png)

![NEER](charts/UK_NEER.png)

[Q1–Q20 JSON for United Kingdom](numbers/UK.json)

## ES — Spain

The main impact of a 20% metals-supply cut on Spain would be only a small drop in GDP of 0.06% by Q4. Equities peak at -0.16% in Q4.

Demand and trade. Consumption peaks at -0.04 % vs baseline in Q4, from -0.02 in Q1 to -0.01 in Q20. Investment peaks at -0.24 % vs baseline in Q4, from -0.13 in Q1 to +0.00 in Q20. Net Exports peaks at -0.34 % vs baseline in Q3, from -0.23 in Q1 to -0.07 in Q20. Gov Spending peaks at +0.01 % vs baseline in Q4, from +0.01 in Q1 to +0.00 in Q20. Gov Debt peaks at +0.00 % vs baseline in Q17, from +0.00 in Q1 to +0.00 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.44 % vs baseline in Q3, from +0.29 in Q1 to +0.07 in Q20.

Labour. Employment peaks at -0.05 % vs baseline in Q11, from -0.01 in Q1 to -0.03 in Q20. Unemployment peaks at +0.03 pp in Q10, from +0.00 in Q1 to +0.01 in Q20. Real Wages peaks at +0.04 % vs baseline in Q10, from -0.00 in Q1 to -0.01 in Q20.

Prices. The three-year CPI impulse is +0.08 percentage points. CPI Inflation peaks at +0.03 pp in Q2, from +0.02 in Q1 to -0.01 in Q20. Domestic Infl. peaks at +0.02 pp in Q2, from +0.01 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.04 % vs baseline in Q4, from -0.02 in Q1 to -0.01 in Q20.

Financial conditions. Policy Rate peaks at +0.05 pp (annualized) in Q5, from +0.02 in Q1 to -0.03 in Q20. Real Rate peaks at +0.01 pp (annualized) in Q5, from +0.00 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at +0.05 pp (annualized) in Q5, from +0.02 in Q1 to -0.03 in Q20. Govt 2Y Yield peaks at +0.04 pp (annualized) in Q2, from +0.04 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at -0.02 pp (annualized) in Q15, from +0.01 in Q1 to -0.02 in Q20. Govt 10Y Yield peaks at -0.01 pp (annualized) in Q13, from -0.00 in Q1 to -0.01 in Q20. Govt 30Y Yield peaks at -0.00 pp (annualized) in Q13, from -0.00 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at -0.37 % vs baseline in Q5, from -0.11 in Q1 to +0.19 in Q20. Bond Price 3M peaks at -0.01 % vs baseline in Q5, from -0.00 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at -0.08 % vs baseline in Q2, from -0.08 in Q1 to +0.05 in Q20. Bond Price 5Y peaks at +0.10 % vs baseline in Q15, from -0.05 in Q1 to +0.08 in Q20. Bond Price 10Y peaks at +0.11 % vs baseline in Q13, from +0.02 in Q1 to +0.09 in Q20. Bond Price 30Y peaks at +0.09 % vs baseline in Q13, from +0.03 in Q1 to +0.07 in Q20. Equity Index peaks at -0.16 % vs baseline in Q4, from -0.09 in Q1 to -0.01 in Q20. VIX peaks at +15.09 index_level in Q10, from +15.01 in Q1 to +15.01 in Q20. Tobin's Q peaks at -0.17 % vs baseline in Q4, from -0.09 in Q1 to +0.00 in Q20. House Prices peaks at -0.06 % vs baseline in Q15, from -0.00 in Q1 to -0.06 in Q20. Bank Equity peaks at -0.02 % vs baseline in Q13, from -0.00 in Q1 to -0.02 in Q20. Bank Credit peaks at -0.02 % vs baseline in Q13, from -0.00 in Q1 to -0.01 in Q20. Credit Spread peaks at +0.00 pp in Q13, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.54 % vs baseline in Q3, from -0.35 in Q1 to -0.10 in Q20. vs USD peaks at -0.10 % vs baseline in Q18, from +0.01 in Q1 to -0.09 in Q20.

Commodities. Energy Price peaks at +80.03 USD/bbl (level) in Q3, from +80.01 in Q1 to +79.96 in Q20. Metals Price peaks at +143.18 index (level) in Q3, from +128.59 in Q1 to +108.65 in Q20. Food Price peaks at +100.04 index (level) in Q3, from +100.02 in Q1 to +99.95 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q3, from +4.00 in Q1 to +4.00 in Q20. Copper Price peaks at +100.01 index (level) in Q3, from +100.01 in Q1 to +99.97 in Q20. Wheat Price peaks at +100.03 index (level) in Q3, from +100.01 in Q1 to +99.98 in Q20. Gold Price peaks at +2008.23 USD/oz (level) in Q11, from +2003.83 in Q1 to +2003.50 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.14 % vs baseline in Q3, from -0.10 in Q1 to -0.02 in Q20. Services GDP peaks at -0.05 % vs baseline in Q4, from -0.03 in Q1 to -0.01 in Q20. Capital Stock peaks at -0.01 % vs baseline in Q19, from -0.00 in Q1 to -0.01 in Q20.

Timing. The GDP response has mostly faded by Q20 (Q20 is -0.02%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/ES_Y.png)

![CPI Inflation](charts/ES_pi_cpi.png)

![Equity Index](charts/ES_equity.png)

![Gold Price](charts/ES_P_gold.png)

![Metals Price](charts/ES_P_metals.png)

![Food Price](charts/ES_P_food.png)

![Wheat Price](charts/ES_P_wheat.png)

![Copper Price](charts/ES_P_copper.png)

![Energy Price](charts/ES_P_energy.png)

![VIX](charts/ES_vix.png)

![Gas Price](charts/ES_P_gas.png)

![NEER](charts/ES_NEER.png)

[Q1–Q20 JSON for Spain](numbers/ES.json)

## TH — Thailand

The main impact of a 20% metals-supply cut on Thailand would be only a small drop in GDP of 0.06% by Q4. Equities peak at -0.19% in Q4.

Demand and trade. Consumption peaks at -0.04 % vs baseline in Q4, from -0.02 in Q1 to -0.01 in Q20. Investment peaks at -0.24 % vs baseline in Q4, from -0.13 in Q1 to +0.02 in Q20. Net Exports peaks at -0.33 % vs baseline in Q3, from -0.22 in Q1 to -0.06 in Q20. Gov Spending peaks at +0.01 % vs baseline in Q4, from +0.01 in Q1 to +0.00 in Q20. Gov Debt peaks at -0.08 % vs baseline in Q16, from -0.01 in Q1 to -0.08 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.25 % vs baseline in Q4, from +0.17 in Q1 to +0.08 in Q20.

Labour. Employment peaks at -0.05 % vs baseline in Q11, from -0.01 in Q1 to -0.03 in Q20. Unemployment peaks at +0.01 pp in Q8, from +0.00 in Q1 to +0.00 in Q20. Real Wages peaks at -0.06 % vs baseline in Q20, from -0.00 in Q1 to -0.06 in Q20.

Prices. The three-year CPI impulse is +0.10 percentage points. CPI Inflation peaks at +0.03 pp in Q2, from +0.03 in Q1 to -0.01 in Q20. Domestic Infl. peaks at +0.02 pp in Q2, from +0.02 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.03 % vs baseline in Q4, from -0.02 in Q1 to -0.01 in Q20.

Financial conditions. Policy Rate peaks at +0.05 pp (annualized) in Q4, from +0.02 in Q1 to -0.03 in Q20. Real Rate peaks at +0.01 pp (annualized) in Q4, from +0.00 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at +0.05 pp (annualized) in Q4, from +0.02 in Q1 to -0.03 in Q20. Govt 2Y Yield peaks at +0.04 pp (annualized) in Q2, from +0.04 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at -0.03 pp (annualized) in Q13, from +0.00 in Q1 to -0.02 in Q20. Govt 10Y Yield peaks at -0.02 pp (annualized) in Q12, from -0.01 in Q1 to -0.01 in Q20. Govt 30Y Yield peaks at -0.01 pp (annualized) in Q11, from -0.00 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at -0.22 % vs baseline in Q4, from -0.07 in Q1 to +0.14 in Q20. Bond Price 3M peaks at -0.01 % vs baseline in Q4, from -0.00 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at -0.07 % vs baseline in Q2, from -0.07 in Q1 to +0.06 in Q20. Bond Price 5Y peaks at +0.12 % vs baseline in Q13, from -0.02 in Q1 to +0.09 in Q20. Bond Price 10Y peaks at +0.13 % vs baseline in Q12, from +0.05 in Q1 to +0.09 in Q20. Bond Price 30Y peaks at +0.10 % vs baseline in Q11, from +0.05 in Q1 to +0.07 in Q20. Equity Index peaks at -0.19 % vs baseline in Q4, from -0.10 in Q1 to -0.02 in Q20. VIX peaks at +15.09 index_level in Q10, from +15.01 in Q1 to +15.01 in Q20. Tobin's Q peaks at -0.17 % vs baseline in Q4, from -0.09 in Q1 to +0.01 in Q20. House Prices peaks at -0.08 % vs baseline in Q14, from -0.01 in Q1 to -0.07 in Q20. Bank Equity peaks at -0.02 % vs baseline in Q13, from -0.00 in Q1 to -0.01 in Q20. Bank Credit peaks at -0.01 % vs baseline in Q13, from -0.00 in Q1 to -0.01 in Q20. Credit Spread peaks at +0.00 pp in Q13, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.97 % vs baseline in Q3, from -0.65 in Q1 to -0.24 in Q20. vs USD peaks at -0.17 % vs baseline in Q3, from -0.11 in Q1 to -0.09 in Q20.

Commodities. Energy Price peaks at +80.03 USD/bbl (level) in Q3, from +80.01 in Q1 to +79.96 in Q20. Metals Price peaks at +143.18 index (level) in Q3, from +128.59 in Q1 to +108.65 in Q20. Food Price peaks at +100.04 index (level) in Q3, from +100.02 in Q1 to +99.95 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q3, from +4.00 in Q1 to +4.00 in Q20. Copper Price peaks at +100.01 index (level) in Q3, from +100.01 in Q1 to +99.97 in Q20. Wheat Price peaks at +100.03 index (level) in Q3, from +100.01 in Q1 to +99.98 in Q20. Gold Price peaks at +2008.23 USD/oz (level) in Q11, from +2003.83 in Q1 to +2003.50 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.10 % vs baseline in Q4, from -0.06 in Q1 to -0.03 in Q20. Services GDP peaks at -0.03 % vs baseline in Q4, from -0.02 in Q1 to -0.01 in Q20. Capital Stock peaks at -0.01 % vs baseline in Q18, from -0.00 in Q1 to -0.01 in Q20.

Timing. The GDP response has mostly faded by Q20 (Q20 is -0.01%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/TH_Y.png)

![CPI Inflation](charts/TH_pi_cpi.png)

![Equity Index](charts/TH_equity.png)

![Gold Price](charts/TH_P_gold.png)

![Metals Price](charts/TH_P_metals.png)

![Food Price](charts/TH_P_food.png)

![Wheat Price](charts/TH_P_wheat.png)

![Copper Price](charts/TH_P_copper.png)

![Energy Price](charts/TH_P_energy.png)

![VIX](charts/TH_vix.png)

![Gas Price](charts/TH_P_gas.png)

![NEER](charts/TH_NEER.png)

[Q1–Q20 JSON for Thailand](numbers/TH.json)

## CA — Canada

The main impact of a 20% metals-supply cut on Canada would be only a small rise in GDP of 0.06% by Q3. Equities peak at +0.13% in Q2.

Demand and trade. Consumption peaks at +0.04 % vs baseline in Q4, from +0.02 in Q1 to -0.00 in Q20. Investment peaks at +0.09 % vs baseline in Q2, from +0.07 in Q1 to +0.04 in Q20. Net Exports peaks at +0.42 % vs baseline in Q3, from +0.28 in Q1 to +0.08 in Q20. Gov Spending peaks at +0.10 % vs baseline in Q3, from +0.06 in Q1 to +0.02 in Q20. Gov Debt peaks at +0.01 % vs baseline in Q8, from +0.00 in Q1 to +0.00 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -0.50 % vs baseline in Q4, from -0.31 in Q1 to -0.11 in Q20.

Labour. Employment peaks at +0.05 % vs baseline in Q6, from +0.01 in Q1 to -0.00 in Q20. Unemployment peaks at -0.02 pp in Q5, from -0.01 in Q1 to +0.00 in Q20. Real Wages peaks at +0.07 % vs baseline in Q14, from +0.00 in Q1 to +0.06 in Q20.

Prices. The three-year CPI impulse is +0.07 percentage points. CPI Inflation peaks at +0.02 pp in Q2, from +0.02 in Q1 to -0.00 in Q20. Domestic Infl. peaks at +0.02 pp in Q2, from +0.01 in Q1 to -0.00 in Q20. Marginal Cost peaks at +0.04 % vs baseline in Q3, from +0.03 in Q1 to -0.00 in Q20.

Financial conditions. Policy Rate peaks at +0.10 pp (annualized) in Q5, from +0.03 in Q1 to -0.03 in Q20. Real Rate peaks at +0.03 pp (annualized) in Q5, from +0.01 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at +0.10 pp (annualized) in Q5, from +0.03 in Q1 to -0.03 in Q20. Govt 2Y Yield peaks at +0.08 pp (annualized) in Q2, from +0.08 in Q1 to -0.02 in Q20. Govt 5Y Yield peaks at +0.03 pp (annualized) in Q1, from +0.03 in Q1 to -0.01 in Q20. Govt 10Y Yield peaks at +0.01 pp (annualized) in Q1, from +0.01 in Q1 to -0.01 in Q20. Govt 30Y Yield peaks at +0.00 pp (annualized) in Q1, from +0.00 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at -0.60 % vs baseline in Q5, from -0.18 in Q1 to +0.16 in Q20. Bond Price 3M peaks at -0.03 % vs baseline in Q5, from -0.01 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at -0.16 % vs baseline in Q2, from -0.15 in Q1 to +0.04 in Q20. Bond Price 5Y peaks at -0.14 % vs baseline in Q1, from -0.14 in Q1 to +0.06 in Q20. Bond Price 10Y peaks at -0.08 % vs baseline in Q1, from -0.08 in Q1 to +0.05 in Q20. Bond Price 30Y peaks at -0.06 % vs baseline in Q1, from -0.06 in Q1 to +0.04 in Q20. Equity Index peaks at +0.13 % vs baseline in Q2, from +0.10 in Q1 to +0.01 in Q20. VIX peaks at +15.09 index_level in Q10, from +15.01 in Q1 to +15.01 in Q20. Tobin's Q peaks at +0.06 % vs baseline in Q2, from +0.05 in Q1 to +0.03 in Q20. House Prices peaks at +0.03 % vs baseline in Q8, from +0.00 in Q1 to +0.01 in Q20. Bank Equity peaks at +0.00 % vs baseline in Q9, from +0.00 in Q1 to +0.00 in Q20. Bank Credit peaks at +0.00 % vs baseline in Q9, from +0.00 in Q1 to +0.00 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.49 % vs baseline in Q4, from +0.31 in Q1 to +0.16 in Q20. vs USD peaks at -0.91 % vs baseline in Q3, from -0.59 in Q1 to -0.28 in Q20.

Commodities. Energy Price peaks at +80.03 USD/bbl (level) in Q3, from +80.01 in Q1 to +79.96 in Q20. Metals Price peaks at +143.18 index (level) in Q3, from +128.59 in Q1 to +108.65 in Q20. Food Price peaks at +100.04 index (level) in Q3, from +100.02 in Q1 to +99.95 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q3, from +4.00 in Q1 to +4.00 in Q20. Copper Price peaks at +100.01 index (level) in Q3, from +100.01 in Q1 to +99.97 in Q20. Wheat Price peaks at +100.03 index (level) in Q3, from +100.01 in Q1 to +99.98 in Q20. Gold Price peaks at +2008.23 USD/oz (level) in Q11, from +2003.83 in Q1 to +2003.50 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.16 % vs baseline in Q4, from +0.10 in Q1 to +0.03 in Q20. Services GDP peaks at +0.04 % vs baseline in Q3, from +0.03 in Q1 to -0.00 in Q20. Capital Stock peaks at +0.00 % vs baseline in Q4, from +0.00 in Q1 to -0.00 in Q20.

Timing. The GDP response has mostly faded by Q9 (Q20 is -0.00%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/CA_Y.png)

![CPI Inflation](charts/CA_pi_cpi.png)

![Equity Index](charts/CA_equity.png)

![Gold Price](charts/CA_P_gold.png)

![Metals Price](charts/CA_P_metals.png)

![Food Price](charts/CA_P_food.png)

![Wheat Price](charts/CA_P_wheat.png)

![Copper Price](charts/CA_P_copper.png)

![Energy Price](charts/CA_P_energy.png)

![VIX](charts/CA_vix.png)

![Gas Price](charts/CA_P_gas.png)

![vs USD](charts/CA_USD.png)

[Q1–Q20 JSON for Canada](numbers/CA.json)

## IN — India

The main impact of a 20% metals-supply cut on India would be only a small drop in GDP of 0.06% by Q12. Equities peak at -0.14% in Q11.

Demand and trade. Consumption peaks at -0.03 % vs baseline in Q13, from +0.00 in Q1 to -0.01 in Q20. Investment peaks at -0.17 % vs baseline in Q7, from -0.02 in Q1 to +0.05 in Q20. Net Exports peaks at +0.08 % vs baseline in Q4, from +0.05 in Q1 to +0.02 in Q20. Gov Spending peaks at +0.01 % vs baseline in Q11, from +0.00 in Q1 to +0.00 in Q20. Gov Debt peaks at -0.05 % vs baseline in Q20, from +0.00 in Q1 to -0.05 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.21 % vs baseline in Q5, from +0.12 in Q1 to +0.08 in Q20.

Labour. Employment peaks at -0.03 % vs baseline in Q17, from +0.00 in Q1 to -0.03 in Q20. Unemployment peaks at +0.00 pp in Q13, from +0.00 in Q1 to +0.00 in Q20. Real Wages peaks at +0.06 % vs baseline in Q10, from +0.00 in Q1 to -0.03 in Q20.

Prices. The three-year CPI impulse is +0.11 percentage points. CPI Inflation peaks at +0.03 pp in Q2, from +0.02 in Q1 to -0.01 in Q20. Domestic Infl. peaks at +0.02 pp in Q2, from +0.01 in Q1 to -0.01 in Q20. Marginal Cost peaks at -0.03 % vs baseline in Q12, from +0.01 in Q1 to -0.01 in Q20.

Financial conditions. Policy Rate peaks at +0.10 pp (annualized) in Q4, from +0.03 in Q1 to -0.05 in Q20. Real Rate peaks at +0.03 pp (annualized) in Q4, from +0.01 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at +0.10 pp (annualized) in Q4, from +0.03 in Q1 to -0.05 in Q20. Govt 2Y Yield peaks at +0.08 pp (annualized) in Q2, from +0.08 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at -0.03 pp (annualized) in Q12, from +0.01 in Q1 to -0.02 in Q20. Govt 10Y Yield peaks at -0.02 pp (annualized) in Q11, from +0.00 in Q1 to -0.01 in Q20. Govt 30Y Yield peaks at -0.01 pp (annualized) in Q11, from +0.00 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at -0.50 % vs baseline in Q4, from -0.16 in Q1 to +0.24 in Q20. Bond Price 3M peaks at -0.03 % vs baseline in Q4, from -0.01 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at -0.14 % vs baseline in Q2, from -0.14 in Q1 to +0.06 in Q20. Bond Price 5Y peaks at +0.14 % vs baseline in Q12, from -0.06 in Q1 to +0.07 in Q20. Bond Price 10Y peaks at +0.13 % vs baseline in Q11, from -0.00 in Q1 to +0.06 in Q20. Bond Price 30Y peaks at +0.09 % vs baseline in Q11, from -0.01 in Q1 to +0.04 in Q20. Equity Index peaks at -0.14 % vs baseline in Q11, from +0.01 in Q1 to -0.00 in Q20. VIX peaks at +15.09 index_level in Q10, from +15.01 in Q1 to +15.01 in Q20. Tobin's Q peaks at -0.12 % vs baseline in Q7, from -0.02 in Q1 to +0.04 in Q20. House Prices peaks at -0.05 % vs baseline in Q16, from +0.00 in Q1 to -0.04 in Q20. Bank Equity peaks at +0.00 % vs baseline in Q9, from +0.00 in Q1 to +0.00 in Q20. Bank Credit peaks at +0.00 % vs baseline in Q9, from +0.00 in Q1 to +0.00 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -1.64 % vs baseline in Q3, from -1.08 in Q1 to -0.37 in Q20. vs USD peaks at -0.22 % vs baseline in Q3, from -0.15 in Q1 to -0.09 in Q20.

Commodities. Energy Price peaks at +80.03 USD/bbl (level) in Q3, from +80.01 in Q1 to +79.96 in Q20. Metals Price peaks at +143.18 index (level) in Q3, from +128.59 in Q1 to +108.65 in Q20. Food Price peaks at +100.04 index (level) in Q3, from +100.02 in Q1 to +99.95 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q3, from +4.00 in Q1 to +4.00 in Q20. Copper Price peaks at +100.01 index (level) in Q3, from +100.01 in Q1 to +99.97 in Q20. Wheat Price peaks at +100.03 index (level) in Q3, from +100.01 in Q1 to +99.98 in Q20. Gold Price peaks at +2008.23 USD/oz (level) in Q11, from +2003.83 in Q1 to +2003.50 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.07 % vs baseline in Q9, from -0.04 in Q1 to -0.03 in Q20. Services GDP peaks at -0.03 % vs baseline in Q12, from +0.00 in Q1 to -0.01 in Q20. Capital Stock peaks at -0.01 % vs baseline in Q16, from -0.00 in Q1 to -0.01 in Q20.

Timing. The GDP response has mostly faded by Q20 (Q20 is -0.01%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/IN_Y.png)

![CPI Inflation](charts/IN_pi_cpi.png)

![Equity Index](charts/IN_equity.png)

![Gold Price](charts/IN_P_gold.png)

![Metals Price](charts/IN_P_metals.png)

![Food Price](charts/IN_P_food.png)

![Wheat Price](charts/IN_P_wheat.png)

![Copper Price](charts/IN_P_copper.png)

![Energy Price](charts/IN_P_energy.png)

![VIX](charts/IN_vix.png)

![Gas Price](charts/IN_P_gas.png)

![NEER](charts/IN_NEER.png)

[Q1–Q20 JSON for India](numbers/IN.json)

## MX — Mexico

The main impact of a 20% metals-supply cut on Mexico would be only a small rise in GDP of 0.05% by Q3. Equities peak at +0.07% in Q2.

Demand and trade. Consumption peaks at +0.03 % vs baseline in Q4, from +0.01 in Q1 to -0.00 in Q20. Investment peaks at -0.08 % vs baseline in Q9, from +0.06 in Q1 to +0.06 in Q20. Net Exports peaks at +0.42 % vs baseline in Q3, from +0.28 in Q1 to +0.08 in Q20. Gov Spending peaks at +0.10 % vs baseline in Q3, from +0.06 in Q1 to +0.02 in Q20. Gov Debt peaks at +0.04 % vs baseline in Q7, from +0.01 in Q1 to +0.01 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -0.92 % vs baseline in Q3, from -0.59 in Q1 to -0.17 in Q20.

Labour. Employment peaks at +0.04 % vs baseline in Q6, from +0.01 in Q1 to -0.01 in Q20. Unemployment peaks at -0.01 pp in Q5, from -0.00 in Q1 to +0.00 in Q20. Real Wages peaks at +0.08 % vs baseline in Q13, from +0.00 in Q1 to +0.05 in Q20.

Prices. The three-year CPI impulse is +0.10 percentage points. CPI Inflation peaks at +0.02 pp in Q2, from +0.02 in Q1 to -0.01 in Q20. Domestic Infl. peaks at +0.02 pp in Q2, from +0.01 in Q1 to -0.00 in Q20. Marginal Cost peaks at +0.03 % vs baseline in Q3, from +0.02 in Q1 to -0.00 in Q20.

Financial conditions. Policy Rate peaks at +0.11 pp (annualized) in Q4, from +0.04 in Q1 to -0.04 in Q20. Real Rate peaks at +0.03 pp (annualized) in Q4, from +0.01 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at +0.11 pp (annualized) in Q4, from +0.04 in Q1 to -0.04 in Q20. Govt 2Y Yield peaks at +0.08 pp (annualized) in Q2, from +0.08 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at +0.02 pp (annualized) in Q1, from +0.02 in Q1 to -0.01 in Q20. Govt 10Y Yield peaks at -0.01 pp (annualized) in Q13, from +0.01 in Q1 to -0.01 in Q20. Govt 30Y Yield peaks at -0.00 pp (annualized) in Q12, from +0.00 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at -0.44 % vs baseline in Q4, from -0.16 in Q1 to +0.15 in Q20. Bond Price 3M peaks at -0.03 % vs baseline in Q4, from -0.01 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at -0.16 % vs baseline in Q2, from -0.15 in Q1 to +0.05 in Q20. Bond Price 5Y peaks at -0.11 % vs baseline in Q1, from -0.11 in Q1 to +0.06 in Q20. Bond Price 10Y peaks at +0.11 % vs baseline in Q13, from -0.05 in Q1 to +0.07 in Q20. Bond Price 30Y peaks at +0.08 % vs baseline in Q12, from -0.03 in Q1 to +0.05 in Q20. Equity Index peaks at +0.07 % vs baseline in Q2, from +0.06 in Q1 to +0.02 in Q20. VIX peaks at +15.09 index_level in Q10, from +15.01 in Q1 to +15.01 in Q20. Tobin's Q peaks at -0.06 % vs baseline in Q9, from +0.04 in Q1 to +0.04 in Q20. House Prices peaks at +0.03 % vs baseline in Q6, from +0.01 in Q1 to -0.00 in Q20. Bank Equity peaks at +0.00 % vs baseline in Q10, from +0.00 in Q1 to +0.00 in Q20. Bank Credit peaks at +0.00 % vs baseline in Q10, from +0.00 in Q1 to +0.00 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +1.07 % vs baseline in Q3, from +0.69 in Q1 to +0.24 in Q20. vs USD peaks at -1.34 % vs baseline in Q3, from -0.87 in Q1 to -0.34 in Q20.

Commodities. Energy Price peaks at +80.03 USD/bbl (level) in Q3, from +80.01 in Q1 to +79.96 in Q20. Metals Price peaks at +143.18 index (level) in Q3, from +128.59 in Q1 to +108.65 in Q20. Food Price peaks at +100.04 index (level) in Q3, from +100.02 in Q1 to +99.95 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q3, from +4.00 in Q1 to +4.00 in Q20. Copper Price peaks at +100.01 index (level) in Q3, from +100.01 in Q1 to +99.97 in Q20. Wheat Price peaks at +100.03 index (level) in Q3, from +100.01 in Q1 to +99.98 in Q20. Gold Price peaks at +2008.23 USD/oz (level) in Q11, from +2003.83 in Q1 to +2003.50 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.29 % vs baseline in Q3, from +0.19 in Q1 to +0.05 in Q20. Services GDP peaks at +0.03 % vs baseline in Q3, from +0.02 in Q1 to -0.00 in Q20. Capital Stock peaks at -0.00 % vs baseline in Q16, from +0.00 in Q1 to -0.00 in Q20.

Timing. The GDP response has mostly faded by Q8 (Q20 is -0.00%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/MX_Y.png)

![CPI Inflation](charts/MX_pi_cpi.png)

![Equity Index](charts/MX_equity.png)

![Gold Price](charts/MX_P_gold.png)

![Metals Price](charts/MX_P_metals.png)

![Food Price](charts/MX_P_food.png)

![Wheat Price](charts/MX_P_wheat.png)

![Copper Price](charts/MX_P_copper.png)

![Energy Price](charts/MX_P_energy.png)

![VIX](charts/MX_vix.png)

![Gas Price](charts/MX_P_gas.png)

![vs USD](charts/MX_USD.png)

[Q1–Q20 JSON for Mexico](numbers/MX.json)

## CO — Colombia

The main impact of a 20% metals-supply cut on Colombia would be only a small drop in GDP of 0.05% by Q12. Equities peak at -0.10% in Q9.

Demand and trade. Consumption peaks at -0.03 % vs baseline in Q13, from -0.00 in Q1 to -0.01 in Q20. Investment peaks at -0.18 % vs baseline in Q6, from -0.05 in Q1 to +0.04 in Q20. Net Exports peaks at +0.00 % vs baseline in Q14, from -0.00 in Q1 to +0.00 in Q20. Gov Spending peaks at +0.01 % vs baseline in Q12, from +0.00 in Q1 to +0.00 in Q20. Gov Debt peaks at -0.05 % vs baseline in Q19, from +0.00 in Q1 to -0.05 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -0.46 % vs baseline in Q3, from -0.30 in Q1 to -0.04 in Q20.

Labour. Employment peaks at -0.04 % vs baseline in Q16, from +0.00 in Q1 to -0.03 in Q20. Unemployment peaks at +0.00 pp in Q13, from +0.00 in Q1 to +0.00 in Q20. Real Wages peaks at +0.05 % vs baseline in Q10, from +0.00 in Q1 to -0.03 in Q20.

Prices. The three-year CPI impulse is +0.10 percentage points. CPI Inflation peaks at +0.03 pp in Q2, from +0.02 in Q1 to -0.01 in Q20. Domestic Infl. peaks at +0.02 pp in Q2, from +0.01 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.03 % vs baseline in Q12, from -0.00 in Q1 to -0.00 in Q20.

Financial conditions. Policy Rate peaks at +0.09 pp (annualized) in Q4, from +0.03 in Q1 to -0.04 in Q20. Real Rate peaks at +0.02 pp (annualized) in Q4, from +0.01 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at +0.09 pp (annualized) in Q4, from +0.03 in Q1 to -0.04 in Q20. Govt 2Y Yield peaks at +0.07 pp (annualized) in Q1, from +0.07 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at -0.03 pp (annualized) in Q12, from +0.02 in Q1 to -0.02 in Q20. Govt 10Y Yield peaks at -0.02 pp (annualized) in Q11, from +0.00 in Q1 to -0.01 in Q20. Govt 30Y Yield peaks at -0.01 pp (annualized) in Q11, from +0.00 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at -0.34 % vs baseline in Q4, from -0.12 in Q1 to +0.14 in Q20. Bond Price 3M peaks at -0.02 % vs baseline in Q4, from -0.01 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at -0.13 % vs baseline in Q1, from -0.13 in Q1 to +0.06 in Q20. Bond Price 5Y peaks at +0.13 % vs baseline in Q12, from -0.07 in Q1 to +0.08 in Q20. Bond Price 10Y peaks at +0.13 % vs baseline in Q11, from -0.00 in Q1 to +0.07 in Q20. Bond Price 30Y peaks at +0.09 % vs baseline in Q11, from +0.00 in Q1 to +0.05 in Q20. Equity Index peaks at -0.10 % vs baseline in Q9, from -0.02 in Q1 to +0.01 in Q20. VIX peaks at +15.09 index_level in Q10, from +15.01 in Q1 to +15.01 in Q20. Tobin's Q peaks at -0.13 % vs baseline in Q6, from -0.04 in Q1 to +0.03 in Q20. House Prices peaks at -0.05 % vs baseline in Q16, from -0.00 in Q1 to -0.05 in Q20. Bank Equity peaks at -0.00 % vs baseline in Q18, from +0.00 in Q1 to -0.00 in Q20. Bank Credit peaks at -0.00 % vs baseline in Q18, from +0.00 in Q1 to -0.00 in Q20. Credit Spread peaks at +0.00 pp in Q18, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.22 % vs baseline in Q3, from +0.14 in Q1 to +0.01 in Q20. vs USD peaks at -0.87 % vs baseline in Q3, from -0.57 in Q1 to -0.20 in Q20.

Commodities. Energy Price peaks at +80.03 USD/bbl (level) in Q3, from +80.01 in Q1 to +79.96 in Q20. Metals Price peaks at +143.18 index (level) in Q3, from +128.59 in Q1 to +108.65 in Q20. Food Price peaks at +100.04 index (level) in Q3, from +100.02 in Q1 to +99.95 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q3, from +4.00 in Q1 to +4.00 in Q20. Copper Price peaks at +100.01 index (level) in Q3, from +100.01 in Q1 to +99.97 in Q20. Wheat Price peaks at +100.03 index (level) in Q3, from +100.01 in Q1 to +99.98 in Q20. Gold Price peaks at +2008.23 USD/oz (level) in Q11, from +2003.83 in Q1 to +2003.50 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.14 % vs baseline in Q3, from +0.09 in Q1 to +0.01 in Q20. Services GDP peaks at -0.03 % vs baseline in Q12, from -0.00 in Q1 to -0.01 in Q20. Capital Stock peaks at -0.01 % vs baseline in Q17, from -0.00 in Q1 to -0.01 in Q20.

Timing. The GDP response has mostly faded by Q20 (Q20 is -0.01%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/CO_Y.png)

![CPI Inflation](charts/CO_pi_cpi.png)

![Equity Index](charts/CO_equity.png)

![Gold Price](charts/CO_P_gold.png)

![Metals Price](charts/CO_P_metals.png)

![Food Price](charts/CO_P_food.png)

![Wheat Price](charts/CO_P_wheat.png)

![Copper Price](charts/CO_P_copper.png)

![Energy Price](charts/CO_P_energy.png)

![VIX](charts/CO_vix.png)

![Gas Price](charts/CO_P_gas.png)

![vs USD](charts/CO_USD.png)

[Q1–Q20 JSON for Colombia](numbers/CO.json)

## ID — Indonesia

The main impact of a 20% metals-supply cut on Indonesia would be only a small rise in GDP of 0.04% by Q3. Equities peak at +0.06% in Q2.

Demand and trade. Consumption peaks at +0.03 % vs baseline in Q4, from +0.01 in Q1 to -0.01 in Q20. Investment peaks at -0.08 % vs baseline in Q9, from +0.06 in Q1 to +0.03 in Q20. Net Exports peaks at +0.34 % vs baseline in Q3, from +0.22 in Q1 to +0.07 in Q20. Gov Spending peaks at +0.04 % vs baseline in Q3, from +0.03 in Q1 to +0.01 in Q20. Gov Debt peaks at +0.04 % vs baseline in Q7, from +0.01 in Q1 to -0.00 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -0.47 % vs baseline in Q3, from -0.31 in Q1 to -0.07 in Q20.

Labour. Employment peaks at +0.03 % vs baseline in Q7, from +0.00 in Q1 to -0.01 in Q20. Unemployment peaks at -0.00 pp in Q5, from -0.00 in Q1 to +0.00 in Q20. Real Wages peaks at +0.09 % vs baseline in Q12, from +0.00 in Q1 to +0.04 in Q20.

Prices. The three-year CPI impulse is +0.12 percentage points. CPI Inflation peaks at +0.03 pp in Q2, from +0.02 in Q1 to -0.01 in Q20. Domestic Infl. peaks at +0.02 pp in Q2, from +0.01 in Q1 to -0.00 in Q20. Marginal Cost peaks at +0.03 % vs baseline in Q3, from +0.02 in Q1 to -0.00 in Q20.

Financial conditions. Policy Rate peaks at +0.09 pp (annualized) in Q5, from +0.02 in Q1 to -0.03 in Q20. Real Rate peaks at +0.02 pp (annualized) in Q5, from +0.01 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at +0.09 pp (annualized) in Q5, from +0.02 in Q1 to -0.03 in Q20. Govt 2Y Yield peaks at +0.07 pp (annualized) in Q2, from +0.07 in Q1 to -0.02 in Q20. Govt 5Y Yield peaks at +0.02 pp (annualized) in Q1, from +0.02 in Q1 to -0.01 in Q20. Govt 10Y Yield peaks at -0.01 pp (annualized) in Q13, from +0.01 in Q1 to -0.01 in Q20. Govt 30Y Yield peaks at -0.00 pp (annualized) in Q13, from +0.00 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at -0.36 % vs baseline in Q5, from -0.10 in Q1 to +0.13 in Q20. Bond Price 3M peaks at -0.02 % vs baseline in Q5, from -0.01 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at -0.13 % vs baseline in Q2, from -0.13 in Q1 to +0.05 in Q20. Bond Price 5Y peaks at -0.11 % vs baseline in Q1, from -0.11 in Q1 to +0.07 in Q20. Bond Price 10Y peaks at +0.09 % vs baseline in Q13, from -0.04 in Q1 to +0.06 in Q20. Bond Price 30Y peaks at +0.07 % vs baseline in Q13, from -0.03 in Q1 to +0.05 in Q20. Equity Index peaks at +0.06 % vs baseline in Q2, from +0.05 in Q1 to +0.00 in Q20. VIX peaks at +15.09 index_level in Q10, from +15.01 in Q1 to +15.01 in Q20. Tobin's Q peaks at -0.06 % vs baseline in Q9, from +0.04 in Q1 to +0.02 in Q20. House Prices peaks at +0.02 % vs baseline in Q6, from +0.00 in Q1 to -0.01 in Q20. Bank Equity peaks at +0.00 % vs baseline in Q11, from +0.00 in Q1 to +0.00 in Q20. Bank Credit peaks at +0.00 % vs baseline in Q11, from +0.00 in Q1 to +0.00 in Q20. Credit Spread peaks at +0.00 pp in Q1, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.62 % vs baseline in Q3, from -0.41 in Q1 to -0.16 in Q20. vs USD peaks at -0.88 % vs baseline in Q3, from -0.59 in Q1 to -0.23 in Q20.

Commodities. Energy Price peaks at +80.03 USD/bbl (level) in Q3, from +80.01 in Q1 to +79.96 in Q20. Metals Price peaks at +143.18 index (level) in Q3, from +128.59 in Q1 to +108.65 in Q20. Food Price peaks at +100.04 index (level) in Q3, from +100.02 in Q1 to +99.95 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q3, from +4.00 in Q1 to +4.00 in Q20. Copper Price peaks at +100.01 index (level) in Q3, from +100.01 in Q1 to +99.97 in Q20. Wheat Price peaks at +100.03 index (level) in Q3, from +100.01 in Q1 to +99.98 in Q20. Gold Price peaks at +2008.23 USD/oz (level) in Q11, from +2003.83 in Q1 to +2003.50 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.15 % vs baseline in Q3, from +0.10 in Q1 to +0.02 in Q20. Services GDP peaks at +0.02 % vs baseline in Q3, from +0.01 in Q1 to -0.00 in Q20. Capital Stock peaks at -0.00 % vs baseline in Q17, from +0.00 in Q1 to -0.00 in Q20.

Timing. The GDP response has mostly faded by Q8 (Q20 is -0.01%).

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/ID_Y.png)

![CPI Inflation](charts/ID_pi_cpi.png)

![Equity Index](charts/ID_equity.png)

![Gold Price](charts/ID_P_gold.png)

![Metals Price](charts/ID_P_metals.png)

![Food Price](charts/ID_P_food.png)

![Wheat Price](charts/ID_P_wheat.png)

![Copper Price](charts/ID_P_copper.png)

![Energy Price](charts/ID_P_energy.png)

![VIX](charts/ID_vix.png)

![Gas Price](charts/ID_P_gas.png)

![vs USD](charts/ID_USD.png)

[Q1–Q20 JSON for Indonesia](numbers/ID.json)

## SA — Saudi Arabia

The main impact of a 20% metals-supply cut on Saudi Arabia would be only a small drop in GDP of 0.04% by Q10. Equities peak at -0.18% in Q8.

Demand and trade. Consumption peaks at -0.02 % vs baseline in Q3, from -0.01 in Q1 to -0.01 in Q20. Investment peaks at -0.22 % vs baseline in Q5, from -0.10 in Q1 to +0.03 in Q20. Net Exports peaks at -0.21 % vs baseline in Q3, from -0.14 in Q1 to -0.05 in Q20. Gov Spending peaks at +0.01 % vs baseline in Q3, from +0.01 in Q1 to -0.00 in Q20. Gov Debt peaks at -0.08 % vs baseline in Q20, from -0.00 in Q1 to -0.08 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -0.04 % vs baseline in Q9, from -0.00 in Q1 to -0.00 in Q20.

Labour. Employment peaks at -0.04 % vs baseline in Q14, from -0.00 in Q1 to -0.03 in Q20. Unemployment peaks at +0.02 pp in Q13, from +0.00 in Q1 to +0.01 in Q20. Real Wages peaks at +0.02 % vs baseline in Q10, from -0.00 in Q1 to -0.02 in Q20.

Prices. The three-year CPI impulse is +0.07 percentage points. CPI Inflation peaks at +0.03 pp in Q2, from +0.02 in Q1 to -0.00 in Q20. Domestic Infl. peaks at +0.02 pp in Q2, from +0.01 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.02 % vs baseline in Q10, from -0.01 in Q1 to -0.01 in Q20.

Financial conditions. Policy Rate peaks at +0.08 pp (annualized) in Q4, from +0.03 in Q1 to -0.04 in Q20. Real Rate peaks at +0.02 pp (annualized) in Q4, from +0.01 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at +0.08 pp (annualized) in Q4, from +0.03 in Q1 to -0.04 in Q20. Govt 2Y Yield peaks at +0.06 pp (annualized) in Q2, from +0.06 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at -0.03 pp (annualized) in Q12, from +0.01 in Q1 to -0.02 in Q20. Govt 10Y Yield peaks at -0.02 pp (annualized) in Q11, from -0.00 in Q1 to -0.01 in Q20. Govt 30Y Yield peaks at -0.00 pp (annualized) in Q12, from -0.00 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at -0.42 % vs baseline in Q4, from -0.13 in Q1 to +0.22 in Q20. Bond Price 3M peaks at -0.02 % vs baseline in Q4, from -0.01 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at -0.12 % vs baseline in Q2, from -0.12 in Q1 to +0.07 in Q20. Bond Price 5Y peaks at +0.14 % vs baseline in Q12, from -0.05 in Q1 to +0.09 in Q20. Bond Price 10Y peaks at +0.13 % vs baseline in Q11, from +0.02 in Q1 to +0.07 in Q20. Bond Price 30Y peaks at +0.09 % vs baseline in Q12, from +0.01 in Q1 to +0.05 in Q20. Equity Index peaks at -0.18 % vs baseline in Q8, from -0.09 in Q1 to -0.04 in Q20. VIX peaks at +15.09 index_level in Q10, from +15.01 in Q1 to +15.01 in Q20. Tobin's Q peaks at -0.16 % vs baseline in Q5, from -0.07 in Q1 to +0.02 in Q20. House Prices peaks at -0.06 % vs baseline in Q15, from -0.00 in Q1 to -0.05 in Q20. Bank Equity peaks at -0.01 % vs baseline in Q16, from -0.00 in Q1 to -0.01 in Q20. Bank Credit peaks at -0.01 % vs baseline in Q16, from -0.00 in Q1 to -0.01 in Q20. Credit Spread peaks at +0.00 pp in Q16, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.13 % vs baseline in Q3, from -0.09 in Q1 to -0.02 in Q20. vs USD peaks at -0.43 % vs baseline in Q4, from -0.28 in Q1 to -0.17 in Q20.

Commodities. Energy Price peaks at +80.03 USD/bbl (level) in Q3, from +80.01 in Q1 to +79.96 in Q20. Metals Price peaks at +143.18 index (level) in Q3, from +128.59 in Q1 to +108.65 in Q20. Food Price peaks at +100.04 index (level) in Q3, from +100.02 in Q1 to +99.95 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q3, from +4.00 in Q1 to +4.00 in Q20. Copper Price peaks at +100.01 index (level) in Q3, from +100.01 in Q1 to +99.97 in Q20. Wheat Price peaks at +100.03 index (level) in Q3, from +100.01 in Q1 to +99.98 in Q20. Gold Price peaks at +2008.23 USD/oz (level) in Q11, from +2003.83 in Q1 to +2003.50 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.01 % vs baseline in Q10, from -0.00 in Q1 to -0.00 in Q20. Services GDP peaks at -0.02 % vs baseline in Q10, from -0.01 in Q1 to -0.01 in Q20. Capital Stock peaks at -0.01 % vs baseline in Q17, from -0.00 in Q1 to -0.01 in Q20.

Timing. By Q20 GDP is still -0.01% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/SA_Y.png)

![CPI Inflation](charts/SA_pi_cpi.png)

![Equity Index](charts/SA_equity.png)

![Gold Price](charts/SA_P_gold.png)

![Metals Price](charts/SA_P_metals.png)

![Food Price](charts/SA_P_food.png)

![Wheat Price](charts/SA_P_wheat.png)

![Copper Price](charts/SA_P_copper.png)

![Energy Price](charts/SA_P_energy.png)

![VIX](charts/SA_vix.png)

![Gas Price](charts/SA_P_gas.png)

![vs USD](charts/SA_USD.png)

[Q1–Q20 JSON for Saudi Arabia](numbers/SA.json)

## US — United States

The main impact of a 20% metals-supply cut on the United States would be only a small drop in GDP of 0.04% by Q11. Equities peak at -0.13% in Q10.

Demand and trade. Consumption peaks at -0.02 % vs baseline in Q13, from -0.00 in Q1 to -0.01 in Q20. Investment peaks at -0.17 % vs baseline in Q6, from -0.04 in Q1 to +0.05 in Q20. Net Exports peaks at +0.00 % vs baseline in Q17, from -0.00 in Q1 to +0.00 in Q20. Gov Spending peaks at +0.01 % vs baseline in Q12, from +0.00 in Q1 to +0.00 in Q20. Gov Debt peaks at -0.01 % vs baseline in Q14, from +0.00 in Q1 to -0.00 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.42 % vs baseline in Q3, from +0.28 in Q1 to +0.17 in Q20.

Labour. Employment peaks at -0.04 % vs baseline in Q14, from +0.00 in Q1 to -0.02 in Q20. Unemployment peaks at +0.03 pp in Q14, from +0.00 in Q1 to +0.02 in Q20. Real Wages peaks at +0.05 % vs baseline in Q11, from +0.00 in Q1 to +0.01 in Q20.

Prices. The three-year CPI impulse is +0.10 percentage points. CPI Inflation peaks at +0.03 pp in Q2, from +0.02 in Q1 to -0.01 in Q20. Domestic Infl. peaks at +0.02 pp in Q2, from +0.01 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.02 % vs baseline in Q12, from -0.00 in Q1 to -0.01 in Q20.

Financial conditions. Policy Rate peaks at +0.08 pp (annualized) in Q4, from +0.03 in Q1 to -0.04 in Q20. Real Rate peaks at +0.02 pp (annualized) in Q4, from +0.01 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at +0.08 pp (annualized) in Q4, from +0.03 in Q1 to -0.04 in Q20. Govt 2Y Yield peaks at +0.06 pp (annualized) in Q2, from +0.06 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at -0.03 pp (annualized) in Q12, from +0.01 in Q1 to -0.02 in Q20. Govt 10Y Yield peaks at -0.02 pp (annualized) in Q11, from -0.00 in Q1 to -0.01 in Q20. Govt 30Y Yield peaks at -0.00 pp (annualized) in Q12, from -0.00 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at -0.55 % vs baseline in Q4, from -0.17 in Q1 to +0.29 in Q20. Bond Price 3M peaks at -0.02 % vs baseline in Q4, from -0.01 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at -0.12 % vs baseline in Q2, from -0.12 in Q1 to +0.07 in Q20. Bond Price 5Y peaks at +0.14 % vs baseline in Q12, from -0.05 in Q1 to +0.09 in Q20. Bond Price 10Y peaks at +0.13 % vs baseline in Q11, from +0.02 in Q1 to +0.07 in Q20. Bond Price 30Y peaks at +0.09 % vs baseline in Q12, from +0.01 in Q1 to +0.05 in Q20. Equity Index peaks at -0.13 % vs baseline in Q10, from -0.02 in Q1 to -0.01 in Q20. VIX peaks at +15.09 index_level in Q10, from +15.01 in Q1 to +15.01 in Q20. Tobin's Q peaks at -0.12 % vs baseline in Q6, from -0.03 in Q1 to +0.03 in Q20. House Prices peaks at -0.03 % vs baseline in Q16, from -0.00 in Q1 to -0.03 in Q20. Bank Equity peaks at -0.00 % vs baseline in Q14, from -0.00 in Q1 to -0.00 in Q20. Bank Credit peaks at -0.00 % vs baseline in Q14, from -0.00 in Q1 to -0.00 in Q20. Credit Spread peaks at +0.00 pp in Q14, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.85 % vs baseline in Q3, from -0.56 in Q1 to -0.26 in Q20. vs USD peaks at -0.85 % vs baseline in Q3, from -0.56 in Q1 to -0.26 in Q20.

Commodities. Energy Price peaks at +80.03 USD/bbl (level) in Q3, from +80.01 in Q1 to +79.96 in Q20. Metals Price peaks at +143.18 index (level) in Q3, from +128.59 in Q1 to +108.65 in Q20. Food Price peaks at +100.04 index (level) in Q3, from +100.02 in Q1 to +99.95 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q3, from +4.00 in Q1 to +4.00 in Q20. Copper Price peaks at +100.01 index (level) in Q3, from +100.01 in Q1 to +99.97 in Q20. Wheat Price peaks at +100.03 index (level) in Q3, from +100.01 in Q1 to +99.98 in Q20. Gold Price peaks at +2008.23 USD/oz (level) in Q11, from +2003.83 in Q1 to +2003.50 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.13 % vs baseline in Q3, from -0.08 in Q1 to -0.05 in Q20. Services GDP peaks at -0.03 % vs baseline in Q11, from -0.00 in Q1 to -0.01 in Q20. Capital Stock peaks at -0.01 % vs baseline in Q16, from -0.00 in Q1 to -0.01 in Q20.

Timing. By Q20 GDP is still -0.01% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/US_Y.png)

![CPI Inflation](charts/US_pi_cpi.png)

![Equity Index](charts/US_equity.png)

![Gold Price](charts/US_P_gold.png)

![Metals Price](charts/US_P_metals.png)

![Food Price](charts/US_P_food.png)

![Wheat Price](charts/US_P_wheat.png)

![Copper Price](charts/US_P_copper.png)

![Energy Price](charts/US_P_energy.png)

![VIX](charts/US_vix.png)

![Gas Price](charts/US_P_gas.png)

![NEER](charts/US_NEER.png)

[Q1–Q20 JSON for United States](numbers/US.json)

## NO — Norway

The main impact of a 20% metals-supply cut on Norway would be only a small drop in GDP of 0.03% by Q12. Equities peak at -0.06% in Q9.

Demand and trade. Consumption peaks at -0.01 % vs baseline in Q14, from -0.00 in Q1 to -0.01 in Q20. Investment peaks at -0.12 % vs baseline in Q6, from -0.03 in Q1 to +0.02 in Q20. Net Exports peaks at -0.01 % vs baseline in Q13, from +0.00 in Q1 to -0.00 in Q20. Gov Spending peaks at +0.00 % vs baseline in Q4, from +0.00 in Q1 to -0.00 in Q20. Gov Debt peaks at +0.01 % vs baseline in Q19, from +0.00 in Q1 to +0.01 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -0.44 % vs baseline in Q3, from -0.29 in Q1 to -0.05 in Q20.

Labour. Employment peaks at -0.02 % vs baseline in Q17, from +0.00 in Q1 to -0.02 in Q20. Unemployment peaks at +0.02 pp in Q15, from +0.00 in Q1 to +0.01 in Q20. Real Wages peaks at +0.05 % vs baseline in Q12, from +0.00 in Q1 to +0.02 in Q20.

Prices. The three-year CPI impulse is +0.10 percentage points. CPI Inflation peaks at +0.03 pp in Q2, from +0.02 in Q1 to -0.00 in Q20. Domestic Infl. peaks at +0.02 pp in Q2, from +0.02 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.02 % vs baseline in Q13, from +0.00 in Q1 to -0.01 in Q20.

Financial conditions. Policy Rate peaks at +0.07 pp (annualized) in Q5, from +0.02 in Q1 to -0.03 in Q20. Real Rate peaks at +0.02 pp (annualized) in Q5, from +0.00 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at +0.07 pp (annualized) in Q5, from +0.02 in Q1 to -0.03 in Q20. Govt 2Y Yield peaks at +0.05 pp (annualized) in Q2, from +0.05 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at -0.02 pp (annualized) in Q14, from +0.02 in Q1 to -0.02 in Q20. Govt 10Y Yield peaks at -0.01 pp (annualized) in Q13, from -0.00 in Q1 to -0.01 in Q20. Govt 30Y Yield peaks at -0.00 pp (annualized) in Q13, from -0.00 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at -0.42 % vs baseline in Q5, from -0.12 in Q1 to +0.19 in Q20. Bond Price 3M peaks at -0.02 % vs baseline in Q5, from -0.00 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at -0.10 % vs baseline in Q2, from -0.10 in Q1 to +0.05 in Q20. Bond Price 5Y peaks at +0.10 % vs baseline in Q14, from -0.07 in Q1 to +0.08 in Q20. Bond Price 10Y peaks at +0.11 % vs baseline in Q13, from +0.00 in Q1 to +0.08 in Q20. Bond Price 30Y peaks at +0.08 % vs baseline in Q13, from +0.01 in Q1 to +0.06 in Q20. Equity Index peaks at -0.06 % vs baseline in Q9, from -0.01 in Q1 to -0.00 in Q20. VIX peaks at +15.09 index_level in Q10, from +15.01 in Q1 to +15.01 in Q20. Tobin's Q peaks at -0.09 % vs baseline in Q6, from -0.02 in Q1 to +0.02 in Q20. House Prices peaks at -0.03 % vs baseline in Q18, from -0.00 in Q1 to -0.02 in Q20. Bank Equity peaks at -0.01 % vs baseline in Q18, from +0.00 in Q1 to -0.01 in Q20. Bank Credit peaks at -0.00 % vs baseline in Q18, from +0.00 in Q1 to -0.00 in Q20. Credit Spread peaks at +0.00 pp in Q18, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.22 % vs baseline in Q3, from -0.14 in Q1 to -0.09 in Q20. vs USD peaks at -0.86 % vs baseline in Q3, from -0.57 in Q1 to -0.22 in Q20.

Commodities. Energy Price peaks at +80.03 USD/bbl (level) in Q3, from +80.01 in Q1 to +79.96 in Q20. Metals Price peaks at +143.18 index (level) in Q3, from +128.59 in Q1 to +108.65 in Q20. Food Price peaks at +100.04 index (level) in Q3, from +100.02 in Q1 to +99.95 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q3, from +4.00 in Q1 to +4.00 in Q20. Copper Price peaks at +100.01 index (level) in Q3, from +100.01 in Q1 to +99.97 in Q20. Wheat Price peaks at +100.03 index (level) in Q3, from +100.01 in Q1 to +99.98 in Q20. Gold Price peaks at +2008.23 USD/oz (level) in Q11, from +2003.83 in Q1 to +2003.50 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.13 % vs baseline in Q3, from +0.09 in Q1 to +0.01 in Q20. Services GDP peaks at -0.02 % vs baseline in Q12, from -0.00 in Q1 to -0.01 in Q20. Capital Stock peaks at -0.01 % vs baseline in Q17, from -0.00 in Q1 to -0.01 in Q20.

Timing. By Q20 GDP is still -0.01% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/NO_Y.png)

![CPI Inflation](charts/NO_pi_cpi.png)

![Equity Index](charts/NO_equity.png)

![Gold Price](charts/NO_P_gold.png)

![Metals Price](charts/NO_P_metals.png)

![Food Price](charts/NO_P_food.png)

![Wheat Price](charts/NO_P_wheat.png)

![Copper Price](charts/NO_P_copper.png)

![Energy Price](charts/NO_P_energy.png)

![VIX](charts/NO_vix.png)

![Gas Price](charts/NO_P_gas.png)

![vs USD](charts/NO_USD.png)

[Q1–Q20 JSON for Norway](numbers/NO.json)

## NL — Netherlands

The main impact of a 20% metals-supply cut on Netherlands would be only a small drop in GDP of 0.03% by Q10. Equities peak at -0.09% in Q7.

Demand and trade. Consumption peaks at -0.01 % vs baseline in Q11, from -0.00 in Q1 to -0.00 in Q20. Investment peaks at -0.13 % vs baseline in Q6, from -0.04 in Q1 to +0.02 in Q20. Net Exports peaks at +0.01 % vs baseline in Q6, from +0.00 in Q1 to -0.00 in Q20. Gov Spending peaks at +0.00 % vs baseline in Q10, from +0.00 in Q1 to +0.00 in Q20. Gov Debt peaks at +0.00 % vs baseline in Q18, from +0.00 in Q1 to +0.00 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.01 % vs baseline in Q8, from +0.00 in Q1 to -0.01 in Q20.

Labour. Employment peaks at -0.02 % vs baseline in Q15, from -0.00 in Q1 to -0.02 in Q20. Unemployment peaks at +0.02 pp in Q13, from +0.00 in Q1 to +0.01 in Q20. Real Wages peaks at +0.05 % vs baseline in Q11, from +0.00 in Q1 to +0.01 in Q20.

Prices. The three-year CPI impulse is +0.09 percentage points. CPI Inflation peaks at +0.03 pp in Q2, from +0.02 in Q1 to -0.01 in Q20. Domestic Infl. peaks at +0.02 pp in Q2, from +0.02 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.01 % vs baseline in Q11, from -0.00 in Q1 to -0.00 in Q20.

Financial conditions. Policy Rate peaks at +0.05 pp (annualized) in Q5, from +0.02 in Q1 to -0.03 in Q20. Real Rate peaks at +0.01 pp (annualized) in Q5, from +0.00 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at +0.05 pp (annualized) in Q5, from +0.02 in Q1 to -0.03 in Q20. Govt 2Y Yield peaks at +0.04 pp (annualized) in Q2, from +0.04 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at -0.02 pp (annualized) in Q15, from +0.01 in Q1 to -0.02 in Q20. Govt 10Y Yield peaks at -0.01 pp (annualized) in Q13, from -0.00 in Q1 to -0.01 in Q20. Govt 30Y Yield peaks at -0.00 pp (annualized) in Q13, from -0.00 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at -0.37 % vs baseline in Q5, from -0.11 in Q1 to +0.19 in Q20. Bond Price 3M peaks at -0.01 % vs baseline in Q5, from -0.00 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at -0.08 % vs baseline in Q2, from -0.08 in Q1 to +0.05 in Q20. Bond Price 5Y peaks at +0.10 % vs baseline in Q15, from -0.05 in Q1 to +0.08 in Q20. Bond Price 10Y peaks at +0.11 % vs baseline in Q13, from +0.02 in Q1 to +0.09 in Q20. Bond Price 30Y peaks at +0.09 % vs baseline in Q13, from +0.03 in Q1 to +0.07 in Q20. Equity Index peaks at -0.09 % vs baseline in Q7, from -0.03 in Q1 to -0.00 in Q20. VIX peaks at +15.09 index_level in Q10, from +15.01 in Q1 to +15.01 in Q20. Tobin's Q peaks at -0.09 % vs baseline in Q6, from -0.03 in Q1 to +0.02 in Q20. House Prices peaks at -0.03 % vs baseline in Q16, from -0.00 in Q1 to -0.03 in Q20. Bank Equity peaks at -0.01 % vs baseline in Q16, from -0.00 in Q1 to -0.01 in Q20. Bank Credit peaks at -0.01 % vs baseline in Q16, from -0.00 in Q1 to -0.01 in Q20. Credit Spread peaks at +0.00 pp in Q15, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.12 % vs baseline in Q3, from -0.08 in Q1 to -0.01 in Q20. vs USD peaks at -0.41 % vs baseline in Q3, from -0.28 in Q1 to -0.18 in Q20.

Commodities. Energy Price peaks at +80.03 USD/bbl (level) in Q3, from +80.01 in Q1 to +79.96 in Q20. Metals Price peaks at +143.18 index (level) in Q3, from +128.59 in Q1 to +108.65 in Q20. Food Price peaks at +100.04 index (level) in Q3, from +100.02 in Q1 to +99.95 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q3, from +4.00 in Q1 to +4.00 in Q20. Copper Price peaks at +100.01 index (level) in Q3, from +100.01 in Q1 to +99.97 in Q20. Wheat Price peaks at +100.03 index (level) in Q3, from +100.01 in Q1 to +99.98 in Q20. Gold Price peaks at +2008.23 USD/oz (level) in Q11, from +2003.83 in Q1 to +2003.50 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.01 % vs baseline in Q8, from -0.00 in Q1 to +0.00 in Q20. Services GDP peaks at -0.02 % vs baseline in Q10, from -0.01 in Q1 to -0.01 in Q20. Capital Stock peaks at -0.01 % vs baseline in Q17, from -0.00 in Q1 to -0.01 in Q20.

Timing. By Q20 GDP is still -0.01% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/NL_Y.png)

![CPI Inflation](charts/NL_pi_cpi.png)

![Equity Index](charts/NL_equity.png)

![Gold Price](charts/NL_P_gold.png)

![Metals Price](charts/NL_P_metals.png)

![Food Price](charts/NL_P_food.png)

![Wheat Price](charts/NL_P_wheat.png)

![Copper Price](charts/NL_P_copper.png)

![Energy Price](charts/NL_P_energy.png)

![VIX](charts/NL_vix.png)

![Gas Price](charts/NL_P_gas.png)

![vs USD](charts/NL_USD.png)

[Q1–Q20 JSON for Netherlands](numbers/NL.json)

## MY — Malaysia

The main impact of a 20% metals-supply cut on Malaysia would be only a small drop in GDP of 0.02% by Q12. Equities peak at -0.07% in Q8.

Demand and trade. Consumption peaks at -0.01 % vs baseline in Q13, from -0.00 in Q1 to -0.01 in Q20. Investment peaks at -0.11 % vs baseline in Q6, from -0.03 in Q1 to +0.02 in Q20. Net Exports peaks at +0.01 % vs baseline in Q5, from +0.01 in Q1 to +0.00 in Q20. Gov Spending peaks at +0.00 % vs baseline in Q11, from +0.00 in Q1 to +0.00 in Q20. Gov Debt peaks at -0.03 % vs baseline in Q20, from +0.00 in Q1 to -0.03 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -0.19 % vs baseline in Q3, from -0.12 in Q1 to -0.03 in Q20.

Labour. Employment peaks at -0.02 % vs baseline in Q16, from +0.00 in Q1 to -0.01 in Q20. Unemployment peaks at +0.01 pp in Q14, from +0.00 in Q1 to +0.00 in Q20. Real Wages peaks at +0.05 % vs baseline in Q10, from +0.00 in Q1 to +0.00 in Q20.

Prices. The three-year CPI impulse is +0.10 percentage points. CPI Inflation peaks at +0.03 pp in Q2, from +0.03 in Q1 to -0.00 in Q20. Domestic Infl. peaks at +0.02 pp in Q2, from +0.02 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.01 % vs baseline in Q12, from -0.00 in Q1 to -0.00 in Q20.

Financial conditions. Policy Rate peaks at +0.06 pp (annualized) in Q5, from +0.02 in Q1 to -0.02 in Q20. Real Rate peaks at +0.01 pp (annualized) in Q5, from +0.00 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at +0.06 pp (annualized) in Q5, from +0.02 in Q1 to -0.02 in Q20. Govt 2Y Yield peaks at +0.04 pp (annualized) in Q2, from +0.04 in Q1 to -0.02 in Q20. Govt 5Y Yield peaks at -0.02 pp (annualized) in Q14, from +0.01 in Q1 to -0.01 in Q20. Govt 10Y Yield peaks at -0.01 pp (annualized) in Q13, from +0.00 in Q1 to -0.01 in Q20. Govt 30Y Yield peaks at -0.00 pp (annualized) in Q13, from -0.00 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at -0.23 % vs baseline in Q5, from -0.08 in Q1 to +0.10 in Q20. Bond Price 3M peaks at -0.01 % vs baseline in Q5, from -0.00 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at -0.09 % vs baseline in Q2, from -0.08 in Q1 to +0.04 in Q20. Bond Price 5Y peaks at +0.08 % vs baseline in Q14, from -0.06 in Q1 to +0.06 in Q20. Bond Price 10Y peaks at +0.08 % vs baseline in Q13, from -0.00 in Q1 to +0.06 in Q20. Bond Price 30Y peaks at +0.06 % vs baseline in Q13, from +0.00 in Q1 to +0.04 in Q20. Equity Index peaks at -0.07 % vs baseline in Q8, from -0.01 in Q1 to +0.00 in Q20. VIX peaks at +15.09 index_level in Q10, from +15.01 in Q1 to +15.01 in Q20. Tobin's Q peaks at -0.07 % vs baseline in Q6, from -0.02 in Q1 to +0.02 in Q20. House Prices peaks at -0.03 % vs baseline in Q16, from -0.00 in Q1 to -0.03 in Q20. Bank Equity peaks at -0.00 % vs baseline in Q19, from +0.00 in Q1 to -0.00 in Q20. Bank Credit peaks at -0.00 % vs baseline in Q19, from +0.00 in Q1 to -0.00 in Q20. Credit Spread peaks at +0.00 pp in Q17, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -1.03 % vs baseline in Q3, from -0.68 in Q1 to -0.22 in Q20. vs USD peaks at -0.61 % vs baseline in Q3, from -0.40 in Q1 to -0.20 in Q20.

Commodities. Energy Price peaks at +80.03 USD/bbl (level) in Q3, from +80.01 in Q1 to +79.96 in Q20. Metals Price peaks at +143.18 index (level) in Q3, from +128.59 in Q1 to +108.65 in Q20. Food Price peaks at +100.04 index (level) in Q3, from +100.02 in Q1 to +99.95 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q3, from +4.00 in Q1 to +4.00 in Q20. Copper Price peaks at +100.01 index (level) in Q3, from +100.01 in Q1 to +99.97 in Q20. Wheat Price peaks at +100.03 index (level) in Q3, from +100.01 in Q1 to +99.98 in Q20. Gold Price peaks at +2008.23 USD/oz (level) in Q11, from +2003.83 in Q1 to +2003.50 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.05 % vs baseline in Q3, from +0.04 in Q1 to +0.01 in Q20. Services GDP peaks at -0.01 % vs baseline in Q12, from -0.00 in Q1 to -0.00 in Q20. Capital Stock peaks at -0.01 % vs baseline in Q17, from -0.00 in Q1 to -0.01 in Q20.

Timing. By Q20 GDP is still -0.01% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/MY_Y.png)

![CPI Inflation](charts/MY_pi_cpi.png)

![Equity Index](charts/MY_equity.png)

![Gold Price](charts/MY_P_gold.png)

![Metals Price](charts/MY_P_metals.png)

![Food Price](charts/MY_P_food.png)

![Wheat Price](charts/MY_P_wheat.png)

![Copper Price](charts/MY_P_copper.png)

![Energy Price](charts/MY_P_energy.png)

![VIX](charts/MY_vix.png)

![Gas Price](charts/MY_P_gas.png)

![NEER](charts/MY_NEER.png)

[Q1–Q20 JSON for Malaysia](numbers/MY.json)

## CH — Switzerland

The main impact of a 20% metals-supply cut on Switzerland would be only a small drop in GDP of 0.02% by Q9. Equities peak at -0.10% in Q7.

Demand and trade. Consumption peaks at -0.01 % vs baseline in Q10, from -0.00 in Q1 to -0.00 in Q20. Investment peaks at -0.11 % vs baseline in Q6, from -0.03 in Q1 to +0.01 in Q20. Net Exports peaks at +0.01 % vs baseline in Q6, from +0.00 in Q1 to -0.00 in Q20. Gov Spending peaks at +0.00 % vs baseline in Q10, from +0.00 in Q1 to +0.00 in Q20. Gov Debt peaks at -0.01 % vs baseline in Q16, from -0.00 in Q1 to -0.01 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.46 % vs baseline in Q4, from +0.29 in Q1 to +0.06 in Q20.

Labour. Employment peaks at -0.02 % vs baseline in Q13, from -0.00 in Q1 to -0.01 in Q20. Unemployment peaks at +0.02 pp in Q12, from +0.00 in Q1 to +0.01 in Q20. Real Wages peaks at +0.06 % vs baseline in Q12, from +0.00 in Q1 to +0.03 in Q20.

Prices. The three-year CPI impulse is +0.09 percentage points. CPI Inflation peaks at +0.03 pp in Q2, from +0.02 in Q1 to -0.01 in Q20. Domestic Infl. peaks at +0.02 pp in Q2, from +0.02 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.01 % vs baseline in Q10, from -0.00 in Q1 to -0.00 in Q20.

Financial conditions. Policy Rate peaks at +0.04 pp (annualized) in Q5, from +0.01 in Q1 to -0.02 in Q20. Real Rate peaks at +0.01 pp (annualized) in Q5, from +0.00 in Q1 to -0.00 in Q20. Govt 3M Yield peaks at +0.04 pp (annualized) in Q5, from +0.01 in Q1 to -0.02 in Q20. Govt 2Y Yield peaks at +0.03 pp (annualized) in Q2, from +0.03 in Q1 to -0.02 in Q20. Govt 5Y Yield peaks at -0.01 pp (annualized) in Q16, from +0.01 in Q1 to -0.01 in Q20. Govt 10Y Yield peaks at -0.01 pp (annualized) in Q14, from -0.00 in Q1 to -0.01 in Q20. Govt 30Y Yield peaks at -0.00 pp (annualized) in Q14, from -0.00 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at -0.29 % vs baseline in Q5, from -0.07 in Q1 to +0.12 in Q20. Bond Price 3M peaks at -0.01 % vs baseline in Q5, from -0.00 in Q1 to +0.00 in Q20. Bond Price 2Y peaks at -0.06 % vs baseline in Q2, from -0.06 in Q1 to +0.03 in Q20. Bond Price 5Y peaks at +0.06 % vs baseline in Q16, from -0.06 in Q1 to +0.06 in Q20. Bond Price 10Y peaks at +0.08 % vs baseline in Q14, from +0.00 in Q1 to +0.07 in Q20. Bond Price 30Y peaks at +0.06 % vs baseline in Q14, from +0.01 in Q1 to +0.05 in Q20. Equity Index peaks at -0.10 % vs baseline in Q7, from -0.03 in Q1 to -0.01 in Q20. VIX peaks at +15.09 index_level in Q10, from +15.01 in Q1 to +15.01 in Q20. Tobin's Q peaks at -0.08 % vs baseline in Q6, from -0.02 in Q1 to +0.01 in Q20. House Prices peaks at -0.02 % vs baseline in Q16, from -0.00 in Q1 to -0.02 in Q20. Bank Equity peaks at -0.01 % vs baseline in Q15, from -0.00 in Q1 to -0.01 in Q20. Bank Credit peaks at -0.01 % vs baseline in Q15, from -0.00 in Q1 to -0.01 in Q20. Credit Spread peaks at +0.00 pp in Q15, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -1.06 % vs baseline in Q3, from -0.69 in Q1 to -0.19 in Q20. vs USD peaks at -0.12 % vs baseline in Q18, from +0.02 in Q1 to -0.11 in Q20.

Commodities. Energy Price peaks at +80.03 USD/bbl (level) in Q3, from +80.01 in Q1 to +79.96 in Q20. Metals Price peaks at +143.18 index (level) in Q3, from +128.59 in Q1 to +108.65 in Q20. Food Price peaks at +100.04 index (level) in Q3, from +100.02 in Q1 to +99.95 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q3, from +4.00 in Q1 to +4.00 in Q20. Copper Price peaks at +100.01 index (level) in Q3, from +100.01 in Q1 to +99.97 in Q20. Wheat Price peaks at +100.03 index (level) in Q3, from +100.01 in Q1 to +99.98 in Q20. Gold Price peaks at +2008.23 USD/oz (level) in Q11, from +2003.83 in Q1 to +2003.50 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.14 % vs baseline in Q4, from -0.09 in Q1 to -0.02 in Q20. Services GDP peaks at -0.02 % vs baseline in Q9, from -0.01 in Q1 to -0.01 in Q20. Capital Stock peaks at -0.01 % vs baseline in Q18, from -0.00 in Q1 to -0.01 in Q20.

Timing. By Q20 GDP is still -0.01% from baseline.

These figures are model IRFs versus baseline, not forecasts.

![GDP](charts/CH_Y.png)

![CPI Inflation](charts/CH_pi_cpi.png)

![Equity Index](charts/CH_equity.png)

![Gold Price](charts/CH_P_gold.png)

![Metals Price](charts/CH_P_metals.png)

![Food Price](charts/CH_P_food.png)

![Wheat Price](charts/CH_P_wheat.png)

![Copper Price](charts/CH_P_copper.png)

![Energy Price](charts/CH_P_energy.png)

![VIX](charts/CH_vix.png)

![Gas Price](charts/CH_P_gas.png)

![NEER](charts/CH_NEER.png)

[Q1–Q20 JSON for Switzerland](numbers/CH.json)

## CN — China

The main impact of a 20% metals-supply cut on China would be no material drop in GDP of 0.02% by Q14. Equities peak at +0.04% in Q2. This has almost no impact on China.

![GDP](charts/CN_Y.png)

![CPI Inflation](charts/CN_pi_cpi.png)

![Equity Index](charts/CN_equity.png)

![Gold Price](charts/CN_P_gold.png)

![Metals Price](charts/CN_P_metals.png)

![Food Price](charts/CN_P_food.png)

![Wheat Price](charts/CN_P_wheat.png)

![Copper Price](charts/CN_P_copper.png)

![Energy Price](charts/CN_P_energy.png)

![VIX](charts/CN_vix.png)

![Gas Price](charts/CN_P_gas.png)

![NEER](charts/CN_NEER.png)

[Q1–Q20 JSON for China](numbers/CN.json)


---

These figures are model IRFs versus baseline, not forecasts, and not financial advice.
