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

United Kingdom sees a -3.27% GDP peak at Q20, with CPI -0.71pp over three years and equities -8.09%. Netherlands sees a -0.14% GDP peak at Q20, with CPI -0.04pp over three years and equities -0.37%. Switzerland sees a -0.14% GDP peak at Q14, with CPI -0.06pp over three years and equities -0.52%. Germany sees a -0.11% GDP peak at Q14, with CPI -0.04pp over three years and equities -0.21%.

The remaining countries are smaller spillovers and are covered in the chapters that follow. This material is a model-based summary and is not financial advice.

### Countries by GDP impact

- [UK — United Kingdom](#uk--united-kingdom) · GDP -3.27% Q20
- [NL — Netherlands](#nl--netherlands) · GDP -0.14% Q20
- [CH — Switzerland](#ch--switzerland) · GDP -0.14% Q14
- [DE — Germany](#de--germany) · GDP -0.11% Q14
- [FR — France](#fr--france) · GDP -0.10% Q14
- [NO — Norway](#no--norway) · GDP -0.09% Q16
- [US — United States](#us--united-states) · GDP -0.09% Q12
- [SA — Saudi Arabia](#sa--saudi-arabia) · GDP -0.07% Q14
- [SE — Sweden](#se--sweden) · GDP -0.07% Q17
- [AU — Australia](#au--australia) · GDP -0.06% Q13
- [ES — Spain](#es--spain) · GDP -0.06% Q13
- [CA — Canada](#ca--canada) · GDP -0.06% Q12
- [JP — Japan](#jp--japan) · GDP -0.06% Q13
- [AR — Argentina](#ar--argentina) · GDP +0.05% Q20
- [PL — Poland](#pl--poland) · GDP -0.04% Q12
- [ZA — South Africa](#za--south-africa) · GDP -0.04% Q11
- [CN — China](#cn--china) · GDP -0.03% Q11
- [RU — Russia](#ru--russia) · GDP -0.03% Q11
- [IT — Italy](#it--italy) · GDP -0.03% Q12
- [MY — Malaysia](#my--malaysia) · GDP -0.03% Q12
- [TR — Turkey](#tr--turkey) · GDP -0.02% Q9
- [BR — Brazil](#br--brazil) · GDP -0.02% Q9
- [MX — Mexico](#mx--mexico) · GDP -0.02% Q10
- [NG — Nigeria](#ng--nigeria) · GDP -0.02% Q9
- [IN — India](#in--india) · GDP -0.02% Q9
- [TH — Thailand](#th--thailand) · GDP -0.02% Q11
- [KR — South Korea](#kr--south-korea) · GDP -0.02% Q10
- [CO — Colombia](#co--colombia) · GDP -0.01% Q9
- [CL — Chile](#cl--chile) · GDP -0.01% Q9
- [ID — Indonesia](#id--indonesia) · GDP +0.01% Q20

![UK GDP](charts/global_UK_Y.png)

![NL GDP](charts/global_NL_Y.png)

![CH GDP](charts/global_CH_Y.png)

![DE GDP](charts/global_DE_Y.png)

![US Equity Index](charts/global_US_equity.png)

![US Policy Rate](charts/global_US_i.png)

## UK — United Kingdom

The main impact of a -25% United Kingdom housing shock on United Kingdom would be a large drop in GDP of 3.27% by Q20. Equities peak at -8.09% in Q20.

Demand and trade. Consumption peaks at -2.08 % vs baseline in Q20, from +0.00 in Q1 to -2.08 in Q20. Investment peaks at -8.84 % vs baseline in Q20, from +0.00 in Q1 to -8.84 in Q20. Net Exports peaks at +0.21 % vs baseline in Q20, from +0.00 in Q1 to +0.21 in Q20. Gov Spending peaks at +0.67 % vs baseline in Q20, from +0.00 in Q1 to +0.67 in Q20. Gov Debt peaks at -0.28 % vs baseline in Q20, from +0.00 in Q1 to -0.28 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.24 % vs baseline in Q20, from +0.00 in Q1 to +0.24 in Q20.

Labour. Employment peaks at -3.38 % vs baseline in Q20, from +0.00 in Q1 to -3.38 in Q20. Unemployment peaks at +2.06 pp in Q20, from +0.00 in Q1 to +2.06 in Q20. Real Wages peaks at -1.97 % vs baseline in Q20, from +0.00 in Q1 to -1.97 in Q20.

Prices. The three-year CPI impulse is -0.71 percentage points. CPI Inflation peaks at -0.17 pp in Q20, from +0.00 in Q1 to -0.17 in Q20. Domestic Infl. peaks at -0.12 pp in Q20, from +0.00 in Q1 to -0.12 in Q20. Marginal Cost peaks at -1.96 % vs baseline in Q20, from +0.00 in Q1 to -1.96 in Q20.

Financial conditions. Policy Rate peaks at -0.32 pp (annualized) in Q20, from +0.00 in Q1 to -0.32 in Q20. Real Rate peaks at -0.08 pp (annualized) in Q20, from +0.00 in Q1 to -0.08 in Q20. Govt 3M Yield peaks at -0.32 pp (annualized) in Q20, from +0.00 in Q1 to -0.32 in Q20. Govt 2Y Yield peaks at -0.42 pp (annualized) in Q20, from -0.02 in Q1 to -0.42 in Q20. Govt 5Y Yield peaks at -0.60 pp (annualized) in Q20, from -0.12 in Q1 to -0.60 in Q20. Govt 10Y Yield peaks at -0.84 pp (annualized) in Q20, from -0.38 in Q1 to -0.84 in Q20. Govt 30Y Yield peaks at -1.29 pp (annualized) in Q20, from -1.05 in Q1 to -1.29 in Q20. Bond Price (7y) peaks at +2.22 % vs baseline in Q20, from +0.00 in Q1 to +2.22 in Q20. Bond Price 3M peaks at +0.08 % vs baseline in Q20, from +0.00 in Q1 to +0.08 in Q20. Bond Price 2Y peaks at +0.80 % vs baseline in Q20, from +0.05 in Q1 to +0.80 in Q20. Bond Price 5Y peaks at +2.70 % vs baseline in Q20, from +0.56 in Q1 to +2.70 in Q20. Bond Price 10Y peaks at +6.92 % vs baseline in Q20, from +3.08 in Q1 to +6.92 in Q20. Bond Price 30Y peaks at +23.23 % vs baseline in Q20, from +18.96 in Q1 to +23.23 in Q20. Equity Index peaks at -8.09 % vs baseline in Q20, from +0.00 in Q1 to -8.09 in Q20. VIX peaks at +15.18 index_level in Q12, from +15.00 in Q1 to +15.11 in Q20. Tobin's Q peaks at -6.19 % vs baseline in Q20, from +0.00 in Q1 to -6.19 in Q20. House Prices peaks at -27.63 % vs baseline in Q20, from +0.00 in Q1 to -27.63 in Q20. Bank Equity peaks at -12.01 % vs baseline in Q20, from +0.00 in Q1 to -12.01 in Q20. Bank Credit peaks at -9.55 % vs baseline in Q20, from +0.00 in Q1 to -9.55 in Q20. Credit Spread peaks at +0.12 pp in Q20, from +0.00 in Q1 to +0.12 in Q20.

Nominal FX. NEER peaks at -0.25 % vs baseline in Q20, from +0.00 in Q1 to -0.25 in Q20. vs USD peaks at +0.22 % vs baseline in Q20, from -0.01 in Q1 to +0.22 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.71 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.84 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.66 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.95 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.79 in Q20. Gold Price peaks at +2011.96 USD/oz (level) in Q12, from +2000.05 in Q1 to +2008.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.62 % vs baseline in Q20, from +0.00 in Q1 to -0.62 in Q20. Services GDP peaks at -2.59 % vs baseline in Q20, from +0.00 in Q1 to -2.59 in Q20. Capital Stock peaks at -0.50 % vs baseline in Q20, from +0.00 in Q1 to -0.50 in Q20.

Timing. By Q20 GDP is still -3.27% from baseline.

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

![House Prices](charts/UK_P_H.png)

![Bond Price 30Y](charts/UK_Q_B_30y.png)

![VIX](charts/UK_vix.png)

[Q1–Q20 JSON for United Kingdom](numbers/UK.json)

## NL — Netherlands

The main impact of a -25% United Kingdom housing shock on Netherlands would be a moderate drop in GDP of 0.14% by Q20. Equities peak at -0.37% in Q20.

Demand and trade. Consumption peaks at -0.09 % vs baseline in Q20, from +0.00 in Q1 to -0.09 in Q20. Investment peaks at -0.36 % vs baseline in Q20, from +0.00 in Q1 to -0.36 in Q20. Net Exports peaks at +0.01 % vs baseline in Q10, from -0.00 in Q1 to +0.01 in Q20. Gov Spending peaks at +0.03 % vs baseline in Q20, from +0.00 in Q1 to +0.03 in Q20. Gov Debt peaks at +0.03 % vs baseline in Q20, from +0.00 in Q1 to +0.03 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.01 % vs baseline in Q8, from -0.00 in Q1 to -0.00 in Q20.

Labour. Employment peaks at -0.14 % vs baseline in Q20, from +0.00 in Q1 to -0.14 in Q20. Unemployment peaks at +0.10 pp in Q20, from +0.00 in Q1 to +0.10 in Q20. Real Wages peaks at -0.13 % vs baseline in Q20, from +0.00 in Q1 to -0.13 in Q20.

Prices. The three-year CPI impulse is -0.04 percentage points. CPI Inflation peaks at -0.01 pp in Q12, from -0.00 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q12, from -0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.08 % vs baseline in Q20, from +0.00 in Q1 to -0.08 in Q20.

Financial conditions. Policy Rate peaks at -0.02 pp (annualized) in Q19, from -0.00 in Q1 to -0.02 in Q20. Real Rate peaks at -0.01 pp (annualized) in Q19, from +0.00 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -0.02 pp (annualized) in Q19, from -0.00 in Q1 to -0.02 in Q20. Govt 2Y Yield peaks at -0.02 pp (annualized) in Q16, from -0.00 in Q1 to -0.02 in Q20. Govt 5Y Yield peaks at -0.02 pp (annualized) in Q13, from -0.01 in Q1 to -0.02 in Q20. Govt 10Y Yield peaks at -0.02 pp (annualized) in Q11, from -0.02 in Q1 to -0.02 in Q20. Govt 30Y Yield peaks at -0.02 pp (annualized) in Q10, from -0.01 in Q1 to -0.01 in Q20. Bond Price (7y) peaks at +0.16 % vs baseline in Q19, from +0.00 in Q1 to +0.16 in Q20. Bond Price 3M peaks at +0.01 % vs baseline in Q19, from +0.00 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +0.04 % vs baseline in Q16, from +0.01 in Q1 to +0.04 in Q20. Bond Price 5Y peaks at +0.10 % vs baseline in Q13, from +0.06 in Q1 to +0.09 in Q20. Bond Price 10Y peaks at +0.15 % vs baseline in Q11, from +0.13 in Q1 to +0.14 in Q20. Bond Price 30Y peaks at +0.28 % vs baseline in Q10, from +0.26 in Q1 to +0.27 in Q20. Equity Index peaks at -0.37 % vs baseline in Q20, from +0.00 in Q1 to -0.37 in Q20. VIX peaks at +15.18 index_level in Q12, from +15.00 in Q1 to +15.11 in Q20. Tobin's Q peaks at -0.25 % vs baseline in Q20, from +0.00 in Q1 to -0.25 in Q20. House Prices peaks at -0.18 % vs baseline in Q20, from +0.00 in Q1 to -0.18 in Q20. Bank Equity peaks at -0.34 % vs baseline in Q20, from +0.00 in Q1 to -0.34 in Q20. Bank Credit peaks at -0.27 % vs baseline in Q20, from +0.00 in Q1 to -0.27 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.01 % vs baseline in Q20, from +0.00 in Q1 to +0.01 in Q20. vs USD peaks at -0.05 % vs baseline in Q15, from -0.01 in Q1 to -0.02 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.71 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.84 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.66 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.95 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.79 in Q20. Gold Price peaks at +2011.96 USD/oz (level) in Q12, from +2000.05 in Q1 to +2008.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.02 % vs baseline in Q12, from +0.00 in Q1 to -0.02 in Q20. Services GDP peaks at -0.11 % vs baseline in Q20, from +0.00 in Q1 to -0.11 in Q20. Capital Stock peaks at -0.03 % vs baseline in Q20, from +0.00 in Q1 to -0.03 in Q20.

Timing. By Q20 GDP is still -0.14% from baseline.

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

## CH — Switzerland

The main impact of a -25% United Kingdom housing shock on Switzerland would be a moderate drop in GDP of 0.14% by Q14. Equities peak at -0.52% in Q14.

Demand and trade. Consumption peaks at -0.10 % vs baseline in Q14, from +0.00 in Q1 to -0.09 in Q20. Investment peaks at -0.33 % vs baseline in Q12, from -0.00 in Q1 to -0.27 in Q20. Net Exports peaks at -0.00 % vs baseline in Q20, from +0.00 in Q1 to -0.00 in Q20. Gov Spending peaks at +0.03 % vs baseline in Q14, from +0.00 in Q1 to +0.02 in Q20. Gov Debt peaks at -0.08 % vs baseline in Q20, from +0.00 in Q1 to -0.08 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -0.12 % vs baseline in Q20, from +0.00 in Q1 to -0.12 in Q20.

Labour. Employment peaks at -0.14 % vs baseline in Q18, from +0.00 in Q1 to -0.14 in Q20. Unemployment peaks at +0.10 pp in Q19, from +0.00 in Q1 to +0.10 in Q20. Real Wages peaks at -0.10 % vs baseline in Q20, from +0.00 in Q1 to -0.10 in Q20.

Prices. The three-year CPI impulse is -0.06 percentage points. CPI Inflation peaks at -0.01 pp in Q8, from +0.00 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q8, from +0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.08 % vs baseline in Q14, from +0.00 in Q1 to -0.07 in Q20.

Financial conditions. Policy Rate peaks at -0.05 pp (annualized) in Q20, from +0.00 in Q1 to -0.05 in Q20. Real Rate peaks at -0.01 pp (annualized) in Q20, from +0.00 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -0.05 pp (annualized) in Q20, from +0.00 in Q1 to -0.05 in Q20. Govt 2Y Yield peaks at -0.05 pp (annualized) in Q20, from -0.01 in Q1 to -0.05 in Q20. Govt 5Y Yield peaks at -0.05 pp (annualized) in Q18, from -0.03 in Q1 to -0.05 in Q20. Govt 10Y Yield peaks at -0.04 pp (annualized) in Q16, from -0.04 in Q1 to -0.04 in Q20. Govt 30Y Yield peaks at -0.04 pp (annualized) in Q14, from -0.04 in Q1 to -0.04 in Q20. Bond Price (7y) peaks at +0.33 % vs baseline in Q20, from -0.00 in Q1 to +0.33 in Q20. Bond Price 3M peaks at +0.01 % vs baseline in Q20, from +0.00 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +0.09 % vs baseline in Q20, from +0.01 in Q1 to +0.09 in Q20. Bond Price 5Y peaks at +0.21 % vs baseline in Q18, from +0.11 in Q1 to +0.21 in Q20. Bond Price 10Y peaks at +0.37 % vs baseline in Q16, from +0.30 in Q1 to +0.37 in Q20. Bond Price 30Y peaks at +0.74 % vs baseline in Q14, from +0.69 in Q1 to +0.73 in Q20. Equity Index peaks at -0.52 % vs baseline in Q14, from +0.00 in Q1 to -0.47 in Q20. VIX peaks at +15.18 index_level in Q12, from +15.00 in Q1 to +15.11 in Q20. Tobin's Q peaks at -0.23 % vs baseline in Q12, from -0.00 in Q1 to -0.19 in Q20. House Prices peaks at -0.16 % vs baseline in Q20, from +0.00 in Q1 to -0.16 in Q20. Bank Equity peaks at -0.45 % vs baseline in Q20, from +0.00 in Q1 to -0.45 in Q20. Bank Credit peaks at -0.35 % vs baseline in Q20, from +0.00 in Q1 to -0.35 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.10 % vs baseline in Q20, from -0.00 in Q1 to +0.10 in Q20. vs USD peaks at -0.16 % vs baseline in Q15, from -0.01 in Q1 to -0.14 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.71 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.84 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.66 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.95 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.79 in Q20. Gold Price peaks at +2011.96 USD/oz (level) in Q12, from +2000.05 in Q1 to +2008.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.01 % vs baseline in Q20, from -0.00 in Q1 to +0.01 in Q20. Services GDP peaks at -0.11 % vs baseline in Q14, from +0.00 in Q1 to -0.10 in Q20. Capital Stock peaks at -0.02 % vs baseline in Q20, from +0.00 in Q1 to -0.02 in Q20.

Timing. By Q20 GDP is still -0.12% from baseline.

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

![Bond Price 30Y](charts/CH_Q_B_30y.png)

[Q1–Q20 JSON for Switzerland](numbers/CH.json)

## DE — Germany

The main impact of a -25% United Kingdom housing shock on Germany would be a moderate drop in GDP of 0.11% by Q14. Equities peak at -0.21% in Q13.

Demand and trade. Consumption peaks at -0.07 % vs baseline in Q14, from +0.00 in Q1 to -0.06 in Q20. Investment peaks at -0.29 % vs baseline in Q12, from +0.00 in Q1 to -0.25 in Q20. Net Exports peaks at +0.03 % vs baseline in Q14, from -0.00 in Q1 to +0.03 in Q20. Gov Spending peaks at +0.03 % vs baseline in Q14, from +0.00 in Q1 to +0.02 in Q20. Gov Debt peaks at +0.02 % vs baseline in Q20, from +0.00 in Q1 to +0.02 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -0.03 % vs baseline in Q20, from -0.00 in Q1 to -0.03 in Q20.

Labour. Employment peaks at -0.12 % vs baseline in Q20, from +0.00 in Q1 to -0.12 in Q20. Unemployment peaks at +0.08 pp in Q19, from +0.00 in Q1 to +0.08 in Q20. Real Wages peaks at -0.12 % vs baseline in Q20, from +0.00 in Q1 to -0.12 in Q20.

Prices. The three-year CPI impulse is -0.04 percentage points. CPI Inflation peaks at -0.01 pp in Q12, from -0.00 in Q1 to -0.01 in Q20. Domestic Infl. peaks at -0.00 pp in Q12, from -0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.07 % vs baseline in Q14, from +0.00 in Q1 to -0.06 in Q20.

Financial conditions. Policy Rate peaks at -0.02 pp (annualized) in Q19, from -0.00 in Q1 to -0.02 in Q20. Real Rate peaks at -0.01 pp (annualized) in Q19, from +0.00 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -0.02 pp (annualized) in Q19, from -0.00 in Q1 to -0.02 in Q20. Govt 2Y Yield peaks at -0.02 pp (annualized) in Q16, from -0.00 in Q1 to -0.02 in Q20. Govt 5Y Yield peaks at -0.02 pp (annualized) in Q13, from -0.01 in Q1 to -0.02 in Q20. Govt 10Y Yield peaks at -0.02 pp (annualized) in Q11, from -0.02 in Q1 to -0.02 in Q20. Govt 30Y Yield peaks at -0.02 pp (annualized) in Q10, from -0.01 in Q1 to -0.01 in Q20. Bond Price (7y) peaks at +0.16 % vs baseline in Q19, from +0.00 in Q1 to +0.16 in Q20. Bond Price 3M peaks at +0.01 % vs baseline in Q19, from +0.00 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +0.04 % vs baseline in Q16, from +0.01 in Q1 to +0.04 in Q20. Bond Price 5Y peaks at +0.10 % vs baseline in Q13, from +0.06 in Q1 to +0.09 in Q20. Bond Price 10Y peaks at +0.15 % vs baseline in Q11, from +0.13 in Q1 to +0.14 in Q20. Bond Price 30Y peaks at +0.28 % vs baseline in Q10, from +0.26 in Q1 to +0.27 in Q20. Equity Index peaks at -0.21 % vs baseline in Q13, from +0.00 in Q1 to -0.18 in Q20. VIX peaks at +15.18 index_level in Q12, from +15.00 in Q1 to +15.11 in Q20. Tobin's Q peaks at -0.20 % vs baseline in Q12, from +0.00 in Q1 to -0.18 in Q20. House Prices peaks at -0.13 % vs baseline in Q20, from +0.00 in Q1 to -0.13 in Q20. Bank Equity peaks at -0.39 % vs baseline in Q20, from +0.00 in Q1 to -0.39 in Q20. Bank Credit peaks at -0.32 % vs baseline in Q20, from +0.00 in Q1 to -0.32 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.01 % vs baseline in Q18, from +0.00 in Q1 to +0.01 in Q20. vs USD peaks at -0.08 % vs baseline in Q15, from -0.01 in Q1 to -0.05 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.71 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.84 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.66 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.95 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.79 in Q20. Gold Price peaks at +2011.96 USD/oz (level) in Q12, from +2000.05 in Q1 to +2008.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.02 % vs baseline in Q10, from +0.00 in Q1 to -0.01 in Q20. Services GDP peaks at -0.08 % vs baseline in Q14, from +0.00 in Q1 to -0.07 in Q20. Capital Stock peaks at -0.02 % vs baseline in Q20, from +0.00 in Q1 to -0.02 in Q20.

Timing. By Q20 GDP is still -0.10% from baseline.

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

![Bank Equity](charts/DE_bank_equity.png)

[Q1–Q20 JSON for Germany](numbers/DE.json)

## FR — France

The main impact of a -25% United Kingdom housing shock on France would be only a small drop in GDP of 0.10% by Q14. Equities peak at -0.20% in Q13.

Demand and trade. Consumption peaks at -0.05 % vs baseline in Q14, from +0.00 in Q1 to -0.05 in Q20. Investment peaks at -0.24 % vs baseline in Q12, from +0.00 in Q1 to -0.21 in Q20. Net Exports peaks at +0.01 % vs baseline in Q12, from -0.00 in Q1 to +0.01 in Q20. Gov Spending peaks at +0.02 % vs baseline in Q14, from +0.00 in Q1 to +0.02 in Q20. Gov Debt peaks at +0.08 % vs baseline in Q20, from +0.00 in Q1 to +0.08 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -0.03 % vs baseline in Q20, from -0.00 in Q1 to -0.03 in Q20.

Labour. Employment peaks at -0.10 % vs baseline in Q20, from +0.00 in Q1 to -0.10 in Q20. Unemployment peaks at +0.07 pp in Q20, from +0.00 in Q1 to +0.07 in Q20. Real Wages peaks at -0.08 % vs baseline in Q20, from +0.00 in Q1 to -0.08 in Q20.

Prices. The three-year CPI impulse is -0.04 percentage points. CPI Inflation peaks at -0.01 pp in Q12, from -0.00 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q12, from -0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.06 % vs baseline in Q14, from +0.00 in Q1 to -0.05 in Q20.

Financial conditions. Policy Rate peaks at -0.02 pp (annualized) in Q19, from -0.00 in Q1 to -0.02 in Q20. Real Rate peaks at -0.01 pp (annualized) in Q19, from +0.00 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -0.02 pp (annualized) in Q19, from -0.00 in Q1 to -0.02 in Q20. Govt 2Y Yield peaks at -0.02 pp (annualized) in Q16, from -0.00 in Q1 to -0.02 in Q20. Govt 5Y Yield peaks at -0.02 pp (annualized) in Q13, from -0.01 in Q1 to -0.02 in Q20. Govt 10Y Yield peaks at -0.02 pp (annualized) in Q11, from -0.02 in Q1 to -0.02 in Q20. Govt 30Y Yield peaks at -0.02 pp (annualized) in Q10, from -0.01 in Q1 to -0.01 in Q20. Bond Price (7y) peaks at +0.16 % vs baseline in Q19, from +0.00 in Q1 to +0.16 in Q20. Bond Price 3M peaks at +0.01 % vs baseline in Q19, from +0.00 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +0.04 % vs baseline in Q16, from +0.01 in Q1 to +0.04 in Q20. Bond Price 5Y peaks at +0.10 % vs baseline in Q13, from +0.06 in Q1 to +0.09 in Q20. Bond Price 10Y peaks at +0.15 % vs baseline in Q11, from +0.13 in Q1 to +0.14 in Q20. Bond Price 30Y peaks at +0.28 % vs baseline in Q10, from +0.26 in Q1 to +0.27 in Q20. Equity Index peaks at -0.20 % vs baseline in Q13, from +0.00 in Q1 to -0.18 in Q20. VIX peaks at +15.18 index_level in Q12, from +15.00 in Q1 to +15.11 in Q20. Tobin's Q peaks at -0.17 % vs baseline in Q12, from +0.00 in Q1 to -0.15 in Q20. House Prices peaks at -0.11 % vs baseline in Q20, from +0.00 in Q1 to -0.11 in Q20. Bank Equity peaks at -0.32 % vs baseline in Q20, from +0.00 in Q1 to -0.32 in Q20. Bank Credit peaks at -0.25 % vs baseline in Q20, from +0.00 in Q1 to -0.25 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.02 % vs baseline in Q20, from +0.00 in Q1 to +0.02 in Q20. vs USD peaks at -0.08 % vs baseline in Q15, from -0.01 in Q1 to -0.05 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.71 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.84 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.66 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.95 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.79 in Q20. Gold Price peaks at +2011.96 USD/oz (level) in Q12, from +2000.05 in Q1 to +2008.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.01 % vs baseline in Q9, from +0.00 in Q1 to -0.00 in Q20. Services GDP peaks at -0.07 % vs baseline in Q14, from +0.00 in Q1 to -0.07 in Q20. Capital Stock peaks at -0.02 % vs baseline in Q20, from +0.00 in Q1 to -0.02 in Q20.

Timing. By Q20 GDP is still -0.09% from baseline.

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

![Bank Equity](charts/FR_bank_equity.png)

[Q1–Q20 JSON for France](numbers/FR.json)

## NO — Norway

The main impact of a -25% United Kingdom housing shock on Norway would be only a small drop in GDP of 0.09% by Q16. Equities peak at -0.17% in Q15.

Demand and trade. Consumption peaks at -0.06 % vs baseline in Q18, from +0.00 in Q1 to -0.06 in Q20. Investment peaks at -0.19 % vs baseline in Q12, from -0.00 in Q1 to -0.17 in Q20. Net Exports peaks at -0.04 % vs baseline in Q20, from +0.00 in Q1 to -0.04 in Q20. Gov Spending peaks at -0.01 % vs baseline in Q20, from +0.00 in Q1 to -0.01 in Q20. Gov Debt peaks at +0.03 % vs baseline in Q20, from +0.00 in Q1 to +0.03 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.17 % vs baseline in Q20, from +0.00 in Q1 to +0.17 in Q20.

Labour. Employment peaks at -0.10 % vs baseline in Q20, from +0.00 in Q1 to -0.10 in Q20. Unemployment peaks at +0.07 pp in Q20, from +0.00 in Q1 to +0.07 in Q20. Real Wages peaks at -0.08 % vs baseline in Q20, from +0.00 in Q1 to -0.08 in Q20.

Prices. The three-year CPI impulse is -0.02 percentage points. CPI Inflation peaks at -0.00 pp in Q20, from +0.00 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q20, from +0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.05 % vs baseline in Q16, from +0.00 in Q1 to -0.05 in Q20.

Financial conditions. Policy Rate peaks at -0.06 pp (annualized) in Q20, from +0.00 in Q1 to -0.06 in Q20. Real Rate peaks at -0.01 pp (annualized) in Q20, from +0.00 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -0.06 pp (annualized) in Q20, from +0.00 in Q1 to -0.06 in Q20. Govt 2Y Yield peaks at -0.06 pp (annualized) in Q20, from -0.01 in Q1 to -0.06 in Q20. Govt 5Y Yield peaks at -0.06 pp (annualized) in Q20, from -0.03 in Q1 to -0.06 in Q20. Govt 10Y Yield peaks at -0.07 pp (annualized) in Q20, from -0.05 in Q1 to -0.07 in Q20. Govt 30Y Yield peaks at -0.06 pp (annualized) in Q20, from -0.06 in Q1 to -0.06 in Q20. Bond Price (7y) peaks at +0.36 % vs baseline in Q20, from -0.00 in Q1 to +0.36 in Q20. Bond Price 3M peaks at +0.01 % vs baseline in Q20, from +0.00 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +0.12 % vs baseline in Q20, from +0.02 in Q1 to +0.12 in Q20. Bond Price 5Y peaks at +0.29 % vs baseline in Q20, from +0.14 in Q1 to +0.29 in Q20. Bond Price 10Y peaks at +0.54 % vs baseline in Q20, from +0.39 in Q1 to +0.54 in Q20. Bond Price 30Y peaks at +1.14 % vs baseline in Q20, from +1.05 in Q1 to +1.14 in Q20. Equity Index peaks at -0.17 % vs baseline in Q15, from +0.00 in Q1 to -0.17 in Q20. VIX peaks at +15.18 index_level in Q12, from +15.00 in Q1 to +15.11 in Q20. Tobin's Q peaks at -0.13 % vs baseline in Q12, from -0.00 in Q1 to -0.12 in Q20. House Prices peaks at -0.10 % vs baseline in Q20, from +0.00 in Q1 to -0.10 in Q20. Bank Equity peaks at -0.17 % vs baseline in Q20, from +0.00 in Q1 to -0.17 in Q20. Bank Credit peaks at -0.14 % vs baseline in Q20, from +0.00 in Q1 to -0.14 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.18 % vs baseline in Q20, from -0.00 in Q1 to -0.18 in Q20. vs USD peaks at +0.15 % vs baseline in Q20, from -0.01 in Q1 to +0.15 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.71 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.84 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.66 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.95 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.79 in Q20. Gold Price peaks at +2011.96 USD/oz (level) in Q12, from +2000.05 in Q1 to +2008.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.06 % vs baseline in Q20, from -0.00 in Q1 to -0.06 in Q20. Services GDP peaks at -0.05 % vs baseline in Q16, from +0.00 in Q1 to -0.05 in Q20. Capital Stock peaks at -0.01 % vs baseline in Q20, from +0.00 in Q1 to -0.01 in Q20.

Timing. By Q20 GDP is still -0.09% from baseline.

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

![Bond Price 30Y](charts/NO_Q_B_30y.png)

[Q1–Q20 JSON for Norway](numbers/NO.json)

## US — United States

The main impact of a -25% United Kingdom housing shock on the United States would be only a small drop in GDP of 0.09% by Q12. Equities peak at -0.24% in Q11.

Demand and trade. Consumption peaks at -0.06 % vs baseline in Q13, from +0.00 in Q1 to -0.04 in Q20. Investment peaks at -0.16 % vs baseline in Q9, from -0.00 in Q1 to -0.05 in Q20. Net Exports peaks at +0.00 % vs baseline in Q12, from +0.00 in Q1 to -0.00 in Q20. Gov Spending peaks at +0.02 % vs baseline in Q12, from +0.00 in Q1 to +0.01 in Q20. Gov Debt peaks at -0.02 % vs baseline in Q14, from +0.00 in Q1 to -0.01 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.06 % vs baseline in Q14, from +0.01 in Q1 to +0.02 in Q20.

Labour. Employment peaks at -0.10 % vs baseline in Q15, from +0.00 in Q1 to -0.08 in Q20. Unemployment peaks at +0.06 pp in Q16, from +0.00 in Q1 to +0.05 in Q20. Real Wages peaks at -0.10 % vs baseline in Q20, from +0.00 in Q1 to -0.10 in Q20.

Prices. The three-year CPI impulse is -0.04 percentage points. CPI Inflation peaks at -0.01 pp in Q13, from +0.00 in Q1 to -0.01 in Q20. Domestic Infl. peaks at -0.00 pp in Q13, from +0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.05 % vs baseline in Q12, from +0.00 in Q1 to -0.03 in Q20.

Financial conditions. Policy Rate peaks at -0.07 pp (annualized) in Q16, from +0.00 in Q1 to -0.07 in Q20. Real Rate peaks at -0.02 pp (annualized) in Q16, from +0.00 in Q1 to -0.02 in Q20. Govt 3M Yield peaks at -0.07 pp (annualized) in Q16, from +0.00 in Q1 to -0.07 in Q20. Govt 2Y Yield peaks at -0.07 pp (annualized) in Q13, from -0.01 in Q1 to -0.06 in Q20. Govt 5Y Yield peaks at -0.06 pp (annualized) in Q10, from -0.04 in Q1 to -0.04 in Q20. Govt 10Y Yield peaks at -0.05 pp (annualized) in Q8, from -0.04 in Q1 to -0.04 in Q20. Govt 30Y Yield peaks at -0.03 pp (annualized) in Q8, from -0.03 in Q1 to -0.03 in Q20. Bond Price (7y) peaks at +0.46 % vs baseline in Q16, from -0.00 in Q1 to +0.44 in Q20. Bond Price 3M peaks at +0.02 % vs baseline in Q16, from +0.00 in Q1 to +0.02 in Q20. Bond Price 2Y peaks at +0.13 % vs baseline in Q13, from +0.02 in Q1 to +0.11 in Q20. Bond Price 5Y peaks at +0.27 % vs baseline in Q10, from +0.19 in Q1 to +0.20 in Q20. Bond Price 10Y peaks at +0.37 % vs baseline in Q8, from +0.35 in Q1 to +0.29 in Q20. Bond Price 30Y peaks at +0.60 % vs baseline in Q8, from +0.58 in Q1 to +0.54 in Q20. Equity Index peaks at -0.24 % vs baseline in Q11, from +0.00 in Q1 to -0.14 in Q20. VIX peaks at +15.18 index_level in Q12, from +15.00 in Q1 to +15.11 in Q20. Tobin's Q peaks at -0.11 % vs baseline in Q9, from -0.00 in Q1 to -0.03 in Q20. House Prices peaks at -0.07 % vs baseline in Q20, from +0.00 in Q1 to -0.07 in Q20. Bank Equity peaks at -0.34 % vs baseline in Q20, from +0.00 in Q1 to -0.34 in Q20. Bank Credit peaks at -0.28 % vs baseline in Q20, from +0.00 in Q1 to -0.28 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.06 % vs baseline in Q14, from -0.01 in Q1 to -0.02 in Q20. vs USD peaks at -0.06 % vs baseline in Q14, from -0.01 in Q1 to -0.02 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.71 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.84 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.66 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.95 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.79 in Q20. Gold Price peaks at +2011.96 USD/oz (level) in Q12, from +2000.05 in Q1 to +2008.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.03 % vs baseline in Q13, from -0.00 in Q1 to -0.01 in Q20. Services GDP peaks at -0.07 % vs baseline in Q12, from +0.00 in Q1 to -0.04 in Q20. Capital Stock peaks at -0.01 % vs baseline in Q20, from +0.00 in Q1 to -0.01 in Q20.

Timing. By Q20 GDP is still -0.05% from baseline.

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

![Gas Price](charts/US_P_gas.png)

![Bond Price 30Y](charts/US_Q_B_30y.png)

[Q1–Q20 JSON for United States](numbers/US.json)

## SA — Saudi Arabia

The main impact of a -25% United Kingdom housing shock on Saudi Arabia would be only a small drop in GDP of 0.07% by Q14. Equities peak at -0.27% in Q13.

Demand and trade. Consumption peaks at -0.05 % vs baseline in Q15, from +0.00 in Q1 to -0.05 in Q20. Investment peaks at -0.11 % vs baseline in Q9, from -0.00 in Q1 to -0.09 in Q20. Net Exports peaks at -0.07 % vs baseline in Q20, from +0.00 in Q1 to -0.07 in Q20. Gov Spending peaks at -0.02 % vs baseline in Q20, from +0.00 in Q1 to -0.02 in Q20. Gov Debt peaks at -0.14 % vs baseline in Q20, from +0.00 in Q1 to -0.14 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.06 % vs baseline in Q20, from +0.00 in Q1 to +0.06 in Q20.

Labour. Employment peaks at -0.08 % vs baseline in Q20, from +0.00 in Q1 to -0.08 in Q20. Unemployment peaks at +0.03 pp in Q19, from +0.00 in Q1 to +0.03 in Q20. Real Wages peaks at -0.08 % vs baseline in Q20, from +0.00 in Q1 to -0.08 in Q20.

Prices. The three-year CPI impulse is -0.03 percentage points. CPI Inflation peaks at -0.00 pp in Q10, from +0.00 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q10, from +0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.04 % vs baseline in Q14, from +0.00 in Q1 to -0.04 in Q20.

Financial conditions. Policy Rate peaks at -0.07 pp (annualized) in Q16, from +0.00 in Q1 to -0.07 in Q20. Real Rate peaks at -0.02 pp (annualized) in Q16, from +0.00 in Q1 to -0.02 in Q20. Govt 3M Yield peaks at -0.07 pp (annualized) in Q16, from +0.00 in Q1 to -0.07 in Q20. Govt 2Y Yield peaks at -0.07 pp (annualized) in Q13, from -0.01 in Q1 to -0.06 in Q20. Govt 5Y Yield peaks at -0.06 pp (annualized) in Q10, from -0.04 in Q1 to -0.04 in Q20. Govt 10Y Yield peaks at -0.05 pp (annualized) in Q8, from -0.04 in Q1 to -0.04 in Q20. Govt 30Y Yield peaks at -0.03 pp (annualized) in Q8, from -0.03 in Q1 to -0.03 in Q20. Bond Price (7y) peaks at +0.35 % vs baseline in Q16, from -0.00 in Q1 to +0.33 in Q20. Bond Price 3M peaks at +0.02 % vs baseline in Q16, from +0.00 in Q1 to +0.02 in Q20. Bond Price 2Y peaks at +0.13 % vs baseline in Q13, from +0.02 in Q1 to +0.11 in Q20. Bond Price 5Y peaks at +0.27 % vs baseline in Q10, from +0.19 in Q1 to +0.20 in Q20. Bond Price 10Y peaks at +0.37 % vs baseline in Q8, from +0.35 in Q1 to +0.29 in Q20. Bond Price 30Y peaks at +0.60 % vs baseline in Q8, from +0.58 in Q1 to +0.54 in Q20. Equity Index peaks at -0.27 % vs baseline in Q13, from +0.00 in Q1 to -0.24 in Q20. VIX peaks at +15.18 index_level in Q12, from +15.00 in Q1 to +15.11 in Q20. Tobin's Q peaks at -0.08 % vs baseline in Q9, from -0.00 in Q1 to -0.06 in Q20. House Prices peaks at -0.09 % vs baseline in Q20, from +0.00 in Q1 to -0.09 in Q20. Bank Equity peaks at -0.09 % vs baseline in Q20, from +0.00 in Q1 to -0.09 in Q20. Bank Credit peaks at -0.08 % vs baseline in Q20, from +0.00 in Q1 to -0.08 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.08 % vs baseline in Q20, from -0.00 in Q1 to -0.08 in Q20. vs USD peaks at +0.04 % vs baseline in Q20, from -0.01 in Q1 to +0.04 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.71 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.84 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.66 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.95 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.79 in Q20. Gold Price peaks at +2011.96 USD/oz (level) in Q12, from +2000.05 in Q1 to +2008.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.02 % vs baseline in Q20, from +0.00 in Q1 to -0.02 in Q20. Services GDP peaks at -0.03 % vs baseline in Q14, from +0.00 in Q1 to -0.03 in Q20. Capital Stock peaks at -0.01 % vs baseline in Q20, from +0.00 in Q1 to -0.01 in Q20.

Timing. By Q20 GDP is still -0.07% from baseline.

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

![Gas Price](charts/SA_P_gas.png)

![Bond Price 30Y](charts/SA_Q_B_30y.png)

[Q1–Q20 JSON for Saudi Arabia](numbers/SA.json)

## SE — Sweden

The main impact of a -25% United Kingdom housing shock on Sweden would be only a small drop in GDP of 0.07% by Q17. Equities peak at -0.18% in Q15.

Demand and trade. Consumption peaks at -0.04 % vs baseline in Q20, from +0.00 in Q1 to -0.04 in Q20. Investment peaks at -0.16 % vs baseline in Q14, from +0.00 in Q1 to -0.15 in Q20. Net Exports peaks at -0.01 % vs baseline in Q20, from -0.00 in Q1 to -0.01 in Q20. Gov Spending peaks at +0.01 % vs baseline in Q17, from +0.00 in Q1 to +0.01 in Q20. Gov Debt peaks at +0.04 % vs baseline in Q20, from +0.00 in Q1 to +0.04 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -0.09 % vs baseline in Q20, from -0.00 in Q1 to -0.09 in Q20.

Labour. Employment peaks at -0.07 % vs baseline in Q20, from +0.00 in Q1 to -0.07 in Q20. Unemployment peaks at +0.05 pp in Q20, from +0.00 in Q1 to +0.05 in Q20. Real Wages peaks at -0.09 % vs baseline in Q20, from +0.00 in Q1 to -0.09 in Q20.

Prices. The three-year CPI impulse is -0.05 percentage points. CPI Inflation peaks at -0.01 pp in Q12, from -0.00 in Q1 to -0.01 in Q20. Domestic Infl. peaks at -0.00 pp in Q12, from -0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.04 % vs baseline in Q17, from +0.00 in Q1 to -0.04 in Q20.

Financial conditions. Policy Rate peaks at -0.03 pp (annualized) in Q20, from -0.00 in Q1 to -0.03 in Q20. Real Rate peaks at -0.01 pp (annualized) in Q20, from +0.00 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -0.03 pp (annualized) in Q20, from -0.00 in Q1 to -0.03 in Q20. Govt 2Y Yield peaks at -0.03 pp (annualized) in Q20, from -0.01 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at -0.03 pp (annualized) in Q18, from -0.02 in Q1 to -0.03 in Q20. Govt 10Y Yield peaks at -0.03 pp (annualized) in Q15, from -0.02 in Q1 to -0.03 in Q20. Govt 30Y Yield peaks at -0.02 pp (annualized) in Q10, from -0.02 in Q1 to -0.02 in Q20. Bond Price (7y) peaks at +0.18 % vs baseline in Q20, from +0.00 in Q1 to +0.18 in Q20. Bond Price 3M peaks at +0.01 % vs baseline in Q20, from +0.00 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +0.05 % vs baseline in Q20, from +0.01 in Q1 to +0.05 in Q20. Bond Price 5Y peaks at +0.13 % vs baseline in Q18, from +0.07 in Q1 to +0.13 in Q20. Bond Price 10Y peaks at +0.23 % vs baseline in Q16, from +0.18 in Q1 to +0.23 in Q20. Bond Price 30Y peaks at +0.41 % vs baseline in Q10, from +0.40 in Q1 to +0.40 in Q20. Equity Index peaks at -0.18 % vs baseline in Q15, from +0.00 in Q1 to -0.18 in Q20. VIX peaks at +15.18 index_level in Q12, from +15.00 in Q1 to +15.11 in Q20. Tobin's Q peaks at -0.11 % vs baseline in Q14, from +0.00 in Q1 to -0.11 in Q20. House Prices peaks at -0.08 % vs baseline in Q20, from +0.00 in Q1 to -0.08 in Q20. Bank Equity peaks at -0.16 % vs baseline in Q20, from +0.00 in Q1 to -0.16 in Q20. Bank Credit peaks at -0.13 % vs baseline in Q20, from +0.00 in Q1 to -0.13 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.10 % vs baseline in Q20, from +0.00 in Q1 to +0.10 in Q20. vs USD peaks at -0.12 % vs baseline in Q17, from -0.01 in Q1 to -0.11 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.71 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.84 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.66 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.95 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.79 in Q20. Gold Price peaks at +2011.96 USD/oz (level) in Q12, from +2000.05 in Q1 to +2008.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.02 % vs baseline in Q20, from +0.00 in Q1 to +0.02 in Q20. Services GDP peaks at -0.05 % vs baseline in Q17, from +0.00 in Q1 to -0.05 in Q20. Capital Stock peaks at -0.01 % vs baseline in Q20, from +0.00 in Q1 to -0.01 in Q20.

Timing. By Q20 GDP is still -0.07% from baseline.

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

![Bond Price 30Y](charts/SE_Q_B_30y.png)

[Q1–Q20 JSON for Sweden](numbers/SE.json)

## AU — Australia

The main impact of a -25% United Kingdom housing shock on Australia would be only a small drop in GDP of 0.06% by Q13. Equities peak at -0.13% in Q12.

Demand and trade. Consumption peaks at -0.04 % vs baseline in Q14, from +0.00 in Q1 to -0.04 in Q20. Investment peaks at -0.12 % vs baseline in Q11, from +0.00 in Q1 to -0.08 in Q20. Net Exports peaks at -0.01 % vs baseline in Q20, from +0.00 in Q1 to -0.01 in Q20. Gov Spending peaks at +0.01 % vs baseline in Q13, from +0.00 in Q1 to +0.01 in Q20. Gov Debt peaks at -0.04 % vs baseline in Q20, from +0.00 in Q1 to -0.04 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.12 % vs baseline in Q15, from +0.00 in Q1 to +0.11 in Q20.

Labour. Employment peaks at -0.07 % vs baseline in Q17, from +0.00 in Q1 to -0.07 in Q20. Unemployment peaks at +0.04 pp in Q18, from +0.00 in Q1 to +0.04 in Q20. Real Wages peaks at -0.08 % vs baseline in Q20, from +0.00 in Q1 to -0.08 in Q20.

Prices. The three-year CPI impulse is -0.02 percentage points. CPI Inflation peaks at -0.00 pp in Q11, from +0.00 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q11, from +0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.04 % vs baseline in Q13, from +0.00 in Q1 to -0.03 in Q20.

Financial conditions. Policy Rate peaks at -0.05 pp (annualized) in Q19, from +0.00 in Q1 to -0.05 in Q20. Real Rate peaks at -0.01 pp (annualized) in Q19, from +0.00 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -0.05 pp (annualized) in Q19, from +0.00 in Q1 to -0.05 in Q20. Govt 2Y Yield peaks at -0.04 pp (annualized) in Q17, from -0.01 in Q1 to -0.04 in Q20. Govt 5Y Yield peaks at -0.04 pp (annualized) in Q13, from -0.03 in Q1 to -0.04 in Q20. Govt 10Y Yield peaks at -0.04 pp (annualized) in Q12, from -0.03 in Q1 to -0.04 in Q20. Govt 30Y Yield peaks at -0.03 pp (annualized) in Q11, from -0.03 in Q1 to -0.03 in Q20. Bond Price (7y) peaks at +0.28 % vs baseline in Q19, from -0.00 in Q1 to +0.28 in Q20. Bond Price 3M peaks at +0.01 % vs baseline in Q19, from +0.00 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +0.08 % vs baseline in Q17, from +0.01 in Q1 to +0.08 in Q20. Bond Price 5Y peaks at +0.19 % vs baseline in Q13, from +0.12 in Q1 to +0.18 in Q20. Bond Price 10Y peaks at +0.32 % vs baseline in Q12, from +0.27 in Q1 to +0.30 in Q20. Bond Price 30Y peaks at +0.61 % vs baseline in Q11, from +0.58 in Q1 to +0.60 in Q20. Equity Index peaks at -0.13 % vs baseline in Q12, from +0.00 in Q1 to -0.10 in Q20. VIX peaks at +15.18 index_level in Q12, from +15.00 in Q1 to +15.11 in Q20. Tobin's Q peaks at -0.09 % vs baseline in Q11, from +0.00 in Q1 to -0.05 in Q20. House Prices peaks at -0.06 % vs baseline in Q20, from +0.00 in Q1 to -0.06 in Q20. Bank Equity peaks at -0.21 % vs baseline in Q20, from +0.00 in Q1 to -0.21 in Q20. Bank Credit peaks at -0.17 % vs baseline in Q20, from +0.00 in Q1 to -0.17 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.14 % vs baseline in Q17, from -0.00 in Q1 to -0.14 in Q20. vs USD peaks at +0.09 % vs baseline in Q20, from -0.01 in Q1 to +0.09 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.71 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.84 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.66 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.95 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.79 in Q20. Gold Price peaks at +2011.96 USD/oz (level) in Q12, from +2000.05 in Q1 to +2008.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.04 % vs baseline in Q15, from -0.00 in Q1 to -0.04 in Q20. Services GDP peaks at -0.04 % vs baseline in Q13, from +0.00 in Q1 to -0.04 in Q20. Capital Stock peaks at -0.01 % vs baseline in Q20, from +0.00 in Q1 to -0.01 in Q20.

Timing. By Q20 GDP is still -0.05% from baseline.

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

![Bond Price 30Y](charts/AU_Q_B_30y.png)

[Q1–Q20 JSON for Australia](numbers/AU.json)

## ES — Spain

The main impact of a -25% United Kingdom housing shock on Spain would be only a small drop in GDP of 0.06% by Q13. Equities peak at -0.10% in Q12.

Demand and trade. Consumption peaks at -0.04 % vs baseline in Q14, from +0.00 in Q1 to -0.03 in Q20. Investment peaks at -0.15 % vs baseline in Q12, from +0.00 in Q1 to -0.12 in Q20. Net Exports peaks at +0.02 % vs baseline in Q13, from -0.00 in Q1 to +0.01 in Q20. Gov Spending peaks at +0.01 % vs baseline in Q13, from +0.00 in Q1 to +0.01 in Q20. Gov Debt peaks at +0.01 % vs baseline in Q20, from +0.00 in Q1 to +0.01 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -0.04 % vs baseline in Q20, from -0.00 in Q1 to -0.04 in Q20.

Labour. Employment peaks at -0.07 % vs baseline in Q20, from +0.00 in Q1 to -0.07 in Q20. Unemployment peaks at +0.03 pp in Q19, from +0.00 in Q1 to +0.03 in Q20. Real Wages peaks at -0.06 % vs baseline in Q20, from +0.00 in Q1 to -0.06 in Q20.

Prices. The three-year CPI impulse is -0.03 percentage points. CPI Inflation peaks at -0.00 pp in Q12, from -0.00 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q12, from -0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.04 % vs baseline in Q13, from +0.00 in Q1 to -0.03 in Q20.

Financial conditions. Policy Rate peaks at -0.02 pp (annualized) in Q19, from -0.00 in Q1 to -0.02 in Q20. Real Rate peaks at -0.01 pp (annualized) in Q19, from +0.00 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -0.02 pp (annualized) in Q19, from -0.00 in Q1 to -0.02 in Q20. Govt 2Y Yield peaks at -0.02 pp (annualized) in Q16, from -0.00 in Q1 to -0.02 in Q20. Govt 5Y Yield peaks at -0.02 pp (annualized) in Q13, from -0.01 in Q1 to -0.02 in Q20. Govt 10Y Yield peaks at -0.02 pp (annualized) in Q11, from -0.02 in Q1 to -0.02 in Q20. Govt 30Y Yield peaks at -0.02 pp (annualized) in Q10, from -0.01 in Q1 to -0.01 in Q20. Bond Price (7y) peaks at +0.16 % vs baseline in Q19, from +0.00 in Q1 to +0.16 in Q20. Bond Price 3M peaks at +0.01 % vs baseline in Q19, from +0.00 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +0.04 % vs baseline in Q16, from +0.01 in Q1 to +0.04 in Q20. Bond Price 5Y peaks at +0.10 % vs baseline in Q13, from +0.06 in Q1 to +0.09 in Q20. Bond Price 10Y peaks at +0.15 % vs baseline in Q11, from +0.13 in Q1 to +0.14 in Q20. Bond Price 30Y peaks at +0.28 % vs baseline in Q10, from +0.26 in Q1 to +0.27 in Q20. Equity Index peaks at -0.10 % vs baseline in Q12, from +0.00 in Q1 to -0.08 in Q20. VIX peaks at +15.18 index_level in Q12, from +15.00 in Q1 to +15.11 in Q20. Tobin's Q peaks at -0.10 % vs baseline in Q12, from +0.00 in Q1 to -0.08 in Q20. House Prices peaks at -0.07 % vs baseline in Q20, from +0.00 in Q1 to -0.07 in Q20. Bank Equity peaks at -0.22 % vs baseline in Q20, from +0.00 in Q1 to -0.22 in Q20. Bank Credit peaks at -0.17 % vs baseline in Q20, from +0.00 in Q1 to -0.17 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.03 % vs baseline in Q20, from +0.00 in Q1 to +0.03 in Q20. vs USD peaks at -0.09 % vs baseline in Q15, from -0.01 in Q1 to -0.06 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.71 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.84 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.66 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.95 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.79 in Q20. Gold Price peaks at +2011.96 USD/oz (level) in Q12, from +2000.05 in Q1 to +2008.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.01 % vs baseline in Q20, from +0.00 in Q1 to +0.01 in Q20. Services GDP peaks at -0.05 % vs baseline in Q13, from +0.00 in Q1 to -0.04 in Q20. Capital Stock peaks at -0.01 % vs baseline in Q20, from +0.00 in Q1 to -0.01 in Q20.

Timing. By Q20 GDP is still -0.06% from baseline.

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

![Bond Price 30Y](charts/ES_Q_B_30y.png)

[Q1–Q20 JSON for Spain](numbers/ES.json)

## CA — Canada

The main impact of a -25% United Kingdom housing shock on Canada would be only a small drop in GDP of 0.06% by Q12. Equities peak at -0.14% in Q12.

Demand and trade. Consumption peaks at -0.04 % vs baseline in Q13, from +0.00 in Q1 to -0.03 in Q20. Investment peaks at -0.12 % vs baseline in Q10, from +0.00 in Q1 to -0.06 in Q20. Net Exports peaks at -0.03 % vs baseline in Q20, from -0.00 in Q1 to -0.03 in Q20. Gov Spending peaks at +0.01 % vs baseline in Q11, from +0.00 in Q1 to +0.00 in Q20. Gov Debt peaks at -0.01 % vs baseline in Q20, from +0.00 in Q1 to -0.01 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.10 % vs baseline in Q20, from -0.00 in Q1 to +0.10 in Q20.

Labour. Employment peaks at -0.07 % vs baseline in Q16, from +0.00 in Q1 to -0.06 in Q20. Unemployment peaks at +0.04 pp in Q17, from +0.00 in Q1 to +0.04 in Q20. Real Wages peaks at -0.08 % vs baseline in Q20, from +0.00 in Q1 to -0.08 in Q20.

Prices. The three-year CPI impulse is -0.03 percentage points. CPI Inflation peaks at -0.00 pp in Q11, from -0.00 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q11, from -0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.04 % vs baseline in Q12, from +0.00 in Q1 to -0.03 in Q20.

Financial conditions. Policy Rate peaks at -0.05 pp (annualized) in Q16, from -0.00 in Q1 to -0.05 in Q20. Real Rate peaks at -0.01 pp (annualized) in Q16, from +0.00 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -0.05 pp (annualized) in Q16, from -0.00 in Q1 to -0.05 in Q20. Govt 2Y Yield peaks at -0.05 pp (annualized) in Q13, from -0.01 in Q1 to -0.04 in Q20. Govt 5Y Yield peaks at -0.04 pp (annualized) in Q10, from -0.03 in Q1 to -0.03 in Q20. Govt 10Y Yield peaks at -0.03 pp (annualized) in Q9, from -0.03 in Q1 to -0.03 in Q20. Govt 30Y Yield peaks at -0.03 pp (annualized) in Q9, from -0.03 in Q1 to -0.03 in Q20. Bond Price (7y) peaks at +0.29 % vs baseline in Q16, from +0.00 in Q1 to +0.27 in Q20. Bond Price 3M peaks at +0.01 % vs baseline in Q16, from +0.00 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +0.09 % vs baseline in Q13, from +0.02 in Q1 to +0.08 in Q20. Bond Price 5Y peaks at +0.19 % vs baseline in Q10, from +0.13 in Q1 to +0.15 in Q20. Bond Price 10Y peaks at +0.28 % vs baseline in Q9, from +0.25 in Q1 to +0.25 in Q20. Bond Price 30Y peaks at +0.55 % vs baseline in Q9, from +0.52 in Q1 to +0.52 in Q20. Equity Index peaks at -0.14 % vs baseline in Q12, from +0.00 in Q1 to -0.09 in Q20. VIX peaks at +15.18 index_level in Q12, from +15.00 in Q1 to +15.11 in Q20. Tobin's Q peaks at -0.08 % vs baseline in Q10, from +0.00 in Q1 to -0.04 in Q20. House Prices peaks at -0.06 % vs baseline in Q20, from +0.00 in Q1 to -0.06 in Q20. Bank Equity peaks at -0.16 % vs baseline in Q20, from +0.00 in Q1 to -0.16 in Q20. Bank Credit peaks at -0.13 % vs baseline in Q20, from +0.00 in Q1 to -0.13 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.10 % vs baseline in Q20, from +0.00 in Q1 to -0.10 in Q20. vs USD peaks at +0.08 % vs baseline in Q20, from -0.01 in Q1 to +0.08 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.71 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.84 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.66 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.95 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.79 in Q20. Gold Price peaks at +2011.96 USD/oz (level) in Q12, from +2000.05 in Q1 to +2008.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.04 % vs baseline in Q14, from +0.00 in Q1 to -0.03 in Q20. Services GDP peaks at -0.04 % vs baseline in Q12, from +0.00 in Q1 to -0.03 in Q20. Capital Stock peaks at -0.01 % vs baseline in Q20, from +0.00 in Q1 to -0.01 in Q20.

Timing. By Q20 GDP is still -0.05% from baseline.

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

![Bond Price 30Y](charts/CA_Q_B_30y.png)

[Q1–Q20 JSON for Canada](numbers/CA.json)

## JP — Japan

The main impact of a -25% United Kingdom housing shock on Japan would be only a small drop in GDP of 0.06% by Q13. Equities peak at -0.14% in Q12.

Demand and trade. Consumption peaks at -0.04 % vs baseline in Q13, from +0.00 in Q1 to -0.03 in Q20. Investment peaks at -0.15 % vs baseline in Q12, from +0.00 in Q1 to -0.11 in Q20. Net Exports peaks at +0.01 % vs baseline in Q11, from -0.00 in Q1 to +0.00 in Q20. Gov Spending peaks at +0.01 % vs baseline in Q13, from +0.00 in Q1 to +0.01 in Q20. Gov Debt peaks at -0.02 % vs baseline in Q20, from +0.00 in Q1 to -0.02 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -0.25 % vs baseline in Q20, from -0.01 in Q1 to -0.25 in Q20.

Labour. Employment peaks at -0.06 % vs baseline in Q18, from +0.00 in Q1 to -0.06 in Q20. Unemployment peaks at +0.04 pp in Q18, from +0.00 in Q1 to +0.04 in Q20. Real Wages peaks at -0.06 % vs baseline in Q20, from +0.00 in Q1 to -0.06 in Q20.

Prices. The three-year CPI impulse is -0.06 percentage points. CPI Inflation peaks at -0.01 pp in Q9, from -0.00 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.01 pp in Q9, from -0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.03 % vs baseline in Q13, from +0.00 in Q1 to -0.03 in Q20.

Financial conditions. Policy Rate peaks at -0.01 pp (annualized) in Q20, from -0.00 in Q1 to -0.01 in Q20. Real Rate peaks at -0.00 pp (annualized) in Q20, from +0.00 in Q1 to -0.00 in Q20. Govt 3M Yield peaks at -0.01 pp (annualized) in Q20, from -0.00 in Q1 to -0.01 in Q20. Govt 2Y Yield peaks at -0.01 pp (annualized) in Q20, from -0.00 in Q1 to -0.01 in Q20. Govt 5Y Yield peaks at -0.01 pp (annualized) in Q16, from -0.00 in Q1 to -0.01 in Q20. Govt 10Y Yield peaks at -0.01 pp (annualized) in Q13, from -0.01 in Q1 to -0.01 in Q20. Govt 30Y Yield peaks at -0.01 pp (annualized) in Q9, from -0.01 in Q1 to -0.01 in Q20. Bond Price (7y) peaks at +0.11 % vs baseline in Q19, from +0.00 in Q1 to +0.11 in Q20. Bond Price 3M peaks at +0.00 % vs baseline in Q20, from +0.00 in Q1 to +0.00 in Q20. Bond Price 2Y peaks at +0.02 % vs baseline in Q20, from +0.00 in Q1 to +0.02 in Q20. Bond Price 5Y peaks at +0.04 % vs baseline in Q16, from +0.02 in Q1 to +0.03 in Q20. Bond Price 10Y peaks at +0.06 % vs baseline in Q13, from +0.05 in Q1 to +0.06 in Q20. Bond Price 30Y peaks at +0.10 % vs baseline in Q9, from +0.09 in Q1 to +0.09 in Q20. Equity Index peaks at -0.14 % vs baseline in Q12, from +0.00 in Q1 to -0.11 in Q20. VIX peaks at +15.18 index_level in Q12, from +15.00 in Q1 to +15.11 in Q20. Tobin's Q peaks at -0.10 % vs baseline in Q12, from +0.00 in Q1 to -0.08 in Q20. House Prices peaks at -0.06 % vs baseline in Q20, from +0.00 in Q1 to -0.06 in Q20. Bank Equity peaks at -0.22 % vs baseline in Q20, from +0.00 in Q1 to -0.22 in Q20. Bank Credit peaks at -0.18 % vs baseline in Q20, from +0.00 in Q1 to -0.18 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.26 % vs baseline in Q20, from +0.01 in Q1 to +0.26 in Q20. vs USD peaks at -0.29 % vs baseline in Q16, from -0.01 in Q1 to -0.28 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.71 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.84 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.66 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.95 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.79 in Q20. Gold Price peaks at +2011.96 USD/oz (level) in Q12, from +2000.05 in Q1 to +2008.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.07 % vs baseline in Q20, from +0.00 in Q1 to +0.07 in Q20. Services GDP peaks at -0.04 % vs baseline in Q13, from +0.00 in Q1 to -0.03 in Q20. Capital Stock peaks at -0.01 % vs baseline in Q20, from +0.00 in Q1 to -0.01 in Q20.

Timing. By Q20 GDP is still -0.05% from baseline.

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

![Gas Price](charts/JP_P_gas.png)

![vs USD](charts/JP_USD.png)

[Q1–Q20 JSON for Japan](numbers/JP.json)

## AR — Argentina

The main impact of a -25% United Kingdom housing shock on Argentina would be only a small rise in GDP of 0.05% by Q20. Equities peak at +0.13% in Q20.

Demand and trade. Consumption peaks at +0.02 % vs baseline in Q20, from +0.00 in Q1 to +0.02 in Q20. Investment peaks at +0.12 % vs baseline in Q20, from -0.00 in Q1 to +0.12 in Q20. Net Exports peaks at -0.03 % vs baseline in Q20, from +0.00 in Q1 to -0.03 in Q20. Gov Spending peaks at -0.01 % vs baseline in Q20, from +0.00 in Q1 to -0.01 in Q20. Gov Debt peaks at +0.01 % vs baseline in Q20, from +0.00 in Q1 to +0.01 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -0.06 % vs baseline in Q20, from +0.00 in Q1 to -0.06 in Q20.

Labour. Employment peaks at +0.03 % vs baseline in Q20, from +0.00 in Q1 to +0.03 in Q20. Unemployment peaks at -0.01 pp in Q20, from +0.00 in Q1 to -0.01 in Q20. Real Wages peaks at -0.02 % vs baseline in Q14, from +0.00 in Q1 to -0.00 in Q20.

Prices. The three-year CPI impulse is -0.04 percentage points. CPI Inflation peaks at -0.01 pp in Q9, from +0.00 in Q1 to +0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q9, from +0.00 in Q1 to +0.00 in Q20. Marginal Cost peaks at +0.03 % vs baseline in Q20, from +0.00 in Q1 to +0.03 in Q20.

Financial conditions. Policy Rate peaks at -0.02 pp (annualized) in Q10, from +0.00 in Q1 to +0.01 in Q20. Real Rate peaks at -0.01 pp (annualized) in Q10, from +0.00 in Q1 to +0.00 in Q20. Govt 3M Yield peaks at -0.02 pp (annualized) in Q10, from +0.00 in Q1 to +0.01 in Q20. Govt 2Y Yield peaks at -0.02 pp (annualized) in Q6, from -0.01 in Q1 to +0.02 in Q20. Govt 5Y Yield peaks at +0.02 pp (annualized) in Q20, from -0.01 in Q1 to +0.02 in Q20. Govt 10Y Yield peaks at +0.01 pp (annualized) in Q19, from +0.00 in Q1 to +0.01 in Q20. Govt 30Y Yield peaks at +0.01 pp (annualized) in Q19, from +0.01 in Q1 to +0.01 in Q20. Bond Price (7y) peaks at +0.05 % vs baseline in Q10, from -0.00 in Q1 to -0.03 in Q20. Bond Price 3M peaks at +0.01 % vs baseline in Q10, from +0.00 in Q1 to -0.00 in Q20. Bond Price 2Y peaks at +0.03 % vs baseline in Q6, from +0.02 in Q1 to -0.03 in Q20. Bond Price 5Y peaks at -0.08 % vs baseline in Q20, from +0.04 in Q1 to -0.08 in Q20. Bond Price 10Y peaks at -0.10 % vs baseline in Q19, from -0.04 in Q1 to -0.10 in Q20. Bond Price 30Y peaks at -0.14 % vs baseline in Q19, from -0.10 in Q1 to -0.14 in Q20. Equity Index peaks at +0.13 % vs baseline in Q20, from +0.00 in Q1 to +0.13 in Q20. VIX peaks at +15.18 index_level in Q12, from +15.00 in Q1 to +15.11 in Q20. Tobin's Q peaks at +0.08 % vs baseline in Q20, from -0.00 in Q1 to +0.08 in Q20. House Prices peaks at +0.03 % vs baseline in Q20, from +0.00 in Q1 to +0.03 in Q20. Bank Equity peaks at -0.02 % vs baseline in Q20, from +0.00 in Q1 to -0.02 in Q20. Bank Credit peaks at -0.03 % vs baseline in Q20, from +0.00 in Q1 to -0.03 in Q20. Credit Spread peaks at +0.01 pp in Q20, from +0.00 in Q1 to +0.01 in Q20.

Nominal FX. NEER peaks at +0.06 % vs baseline in Q17, from -0.00 in Q1 to +0.06 in Q20. vs USD peaks at -0.10 % vs baseline in Q16, from -0.01 in Q1 to -0.08 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.71 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.84 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.66 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.95 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.79 in Q20. Gold Price peaks at +2011.96 USD/oz (level) in Q12, from +2000.05 in Q1 to +2008.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.03 % vs baseline in Q20, from -0.00 in Q1 to +0.03 in Q20. Services GDP peaks at +0.03 % vs baseline in Q20, from +0.00 in Q1 to +0.03 in Q20. Capital Stock peaks at +0.01 % vs baseline in Q20, from +0.00 in Q1 to +0.01 in Q20.

Timing. By Q20 GDP is still +0.05% from baseline.

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

![Gas Price](charts/AR_P_gas.png)

![Bond Price 30Y](charts/AR_Q_B_30y.png)

[Q1–Q20 JSON for Argentina](numbers/AR.json)

## PL — Poland

The main impact of a -25% United Kingdom housing shock on Poland would be no material drop in GDP of 0.04% by Q12. Equities peak at -0.04% in Q9. This has almost no impact on Poland.

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

![Bond Price 30Y](charts/PL_Q_B_30y.png)

[Q1–Q20 JSON for Poland](numbers/PL.json)

## ZA — South Africa

The main impact of a -25% United Kingdom housing shock on South Africa would be only a small drop in GDP of 0.04% by Q11. Equities peak at -0.13% in Q10.

Demand and trade. Consumption peaks at -0.02 % vs baseline in Q12, from +0.00 in Q1 to -0.01 in Q20. Investment peaks at -0.08 % vs baseline in Q9, from +0.00 in Q1 to -0.03 in Q20. Net Exports peaks at +0.00 % vs baseline in Q8, from -0.00 in Q1 to +0.00 in Q20. Gov Spending peaks at +0.01 % vs baseline in Q11, from +0.00 in Q1 to +0.00 in Q20. Gov Debt peaks at -0.03 % vs baseline in Q20, from +0.00 in Q1 to -0.03 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.05 % vs baseline in Q11, from -0.00 in Q1 to +0.04 in Q20.

Labour. Employment peaks at -0.04 % vs baseline in Q16, from +0.00 in Q1 to -0.04 in Q20. Unemployment peaks at +0.01 pp in Q14, from +0.00 in Q1 to +0.01 in Q20. Real Wages peaks at -0.07 % vs baseline in Q20, from +0.00 in Q1 to -0.07 in Q20.

Prices. The three-year CPI impulse is -0.03 percentage points. CPI Inflation peaks at -0.00 pp in Q11, from -0.00 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q11, from -0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.02 % vs baseline in Q11, from +0.00 in Q1 to -0.01 in Q20.

Financial conditions. Policy Rate peaks at -0.02 pp (annualized) in Q14, from -0.00 in Q1 to -0.02 in Q20. Real Rate peaks at -0.01 pp (annualized) in Q14, from -0.00 in Q1 to -0.00 in Q20. Govt 3M Yield peaks at -0.02 pp (annualized) in Q14, from -0.00 in Q1 to -0.02 in Q20. Govt 2Y Yield peaks at -0.02 pp (annualized) in Q11, from -0.00 in Q1 to -0.01 in Q20. Govt 5Y Yield peaks at -0.02 pp (annualized) in Q8, from -0.01 in Q1 to -0.01 in Q20. Govt 10Y Yield peaks at -0.01 pp (annualized) in Q7, from -0.01 in Q1 to -0.01 in Q20. Govt 30Y Yield peaks at -0.01 pp (annualized) in Q7, from -0.01 in Q1 to -0.01 in Q20. Bond Price (7y) peaks at +0.09 % vs baseline in Q14, from +0.00 in Q1 to +0.07 in Q20. Bond Price 3M peaks at +0.01 % vs baseline in Q14, from +0.00 in Q1 to +0.00 in Q20. Bond Price 2Y peaks at +0.04 % vs baseline in Q11, from +0.01 in Q1 to +0.03 in Q20. Bond Price 5Y peaks at +0.08 % vs baseline in Q8, from +0.06 in Q1 to +0.05 in Q20. Bond Price 10Y peaks at +0.10 % vs baseline in Q7, from +0.10 in Q1 to +0.07 in Q20. Bond Price 30Y peaks at +0.16 % vs baseline in Q7, from +0.16 in Q1 to +0.14 in Q20. Equity Index peaks at -0.13 % vs baseline in Q10, from +0.00 in Q1 to -0.04 in Q20. VIX peaks at +15.18 index_level in Q12, from +15.00 in Q1 to +15.11 in Q20. Tobin's Q peaks at -0.06 % vs baseline in Q9, from +0.00 in Q1 to -0.02 in Q20. House Prices peaks at -0.04 % vs baseline in Q19, from +0.00 in Q1 to -0.04 in Q20. Bank Equity peaks at -0.14 % vs baseline in Q20, from +0.00 in Q1 to -0.14 in Q20. Bank Credit peaks at -0.12 % vs baseline in Q20, from +0.00 in Q1 to -0.12 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.05 % vs baseline in Q20, from +0.00 in Q1 to -0.05 in Q20. vs USD peaks at +0.02 % vs baseline in Q20, from -0.01 in Q1 to +0.02 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.71 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.84 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.66 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.95 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.79 in Q20. Gold Price peaks at +2011.96 USD/oz (level) in Q12, from +2000.05 in Q1 to +2008.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.02 % vs baseline in Q10, from +0.00 in Q1 to -0.01 in Q20. Services GDP peaks at -0.02 % vs baseline in Q11, from +0.00 in Q1 to -0.01 in Q20. Capital Stock peaks at -0.01 % vs baseline in Q20, from +0.00 in Q1 to -0.01 in Q20.

Timing. By Q20 GDP is still -0.02% from baseline.

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

![Gas Price](charts/ZA_P_gas.png)

![Bond Price 30Y](charts/ZA_Q_B_30y.png)

[Q1–Q20 JSON for South Africa](numbers/ZA.json)

## CN — China

The main impact of a -25% United Kingdom housing shock on China would be only a small drop in GDP of 0.03% by Q11. Equities peak at -0.05% in Q10.

Demand and trade. Consumption peaks at -0.03 % vs baseline in Q12, from +0.00 in Q1 to -0.01 in Q20. Investment peaks at -0.06 % vs baseline in Q9, from +0.00 in Q1 to +0.01 in Q20. Net Exports peaks at +0.01 % vs baseline in Q18, from -0.00 in Q1 to +0.01 in Q20. Gov Spending peaks at +0.01 % vs baseline in Q11, from +0.00 in Q1 to +0.00 in Q20. Gov Debt peaks at -0.05 % vs baseline in Q20, from +0.00 in Q1 to -0.05 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.01 % vs baseline in Q17, from -0.00 in Q1 to +0.00 in Q20.

Labour. Employment peaks at -0.03 % vs baseline in Q17, from +0.00 in Q1 to -0.03 in Q20. Unemployment peaks at +0.01 pp in Q14, from +0.00 in Q1 to +0.00 in Q20. Real Wages peaks at -0.07 % vs baseline in Q20, from +0.00 in Q1 to -0.07 in Q20.

Prices. The three-year CPI impulse is -0.04 percentage points. CPI Inflation peaks at -0.01 pp in Q10, from -0.00 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q10, from -0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.02 % vs baseline in Q11, from +0.00 in Q1 to -0.01 in Q20.

Financial conditions. Policy Rate peaks at -0.03 pp (annualized) in Q17, from -0.00 in Q1 to -0.03 in Q20. Real Rate peaks at -0.01 pp (annualized) in Q17, from +0.00 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -0.03 pp (annualized) in Q17, from -0.00 in Q1 to -0.03 in Q20. Govt 2Y Yield peaks at -0.03 pp (annualized) in Q14, from -0.01 in Q1 to -0.03 in Q20. Govt 5Y Yield peaks at -0.03 pp (annualized) in Q10, from -0.02 in Q1 to -0.02 in Q20. Govt 10Y Yield peaks at -0.02 pp (annualized) in Q5, from -0.02 in Q1 to -0.01 in Q20. Govt 30Y Yield peaks at -0.01 pp (annualized) in Q6, from -0.01 in Q1 to -0.01 in Q20. Bond Price (7y) peaks at +0.17 % vs baseline in Q17, from +0.00 in Q1 to +0.16 in Q20. Bond Price 3M peaks at +0.01 % vs baseline in Q17, from +0.00 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +0.06 % vs baseline in Q14, from +0.01 in Q1 to +0.05 in Q20. Bond Price 5Y peaks at +0.13 % vs baseline in Q10, from +0.09 in Q1 to +0.09 in Q20. Bond Price 10Y peaks at +0.16 % vs baseline in Q5, from +0.16 in Q1 to +0.10 in Q20. Bond Price 30Y peaks at +0.17 % vs baseline in Q6, from +0.17 in Q1 to +0.13 in Q20. Equity Index peaks at -0.05 % vs baseline in Q10, from +0.00 in Q1 to -0.01 in Q20. VIX peaks at +15.18 index_level in Q12, from +15.00 in Q1 to +15.11 in Q20. Tobin's Q peaks at -0.04 % vs baseline in Q9, from +0.00 in Q1 to +0.01 in Q20. House Prices peaks at -0.03 % vs baseline in Q17, from +0.00 in Q1 to -0.03 in Q20. Bank Equity peaks at -0.08 % vs baseline in Q20, from +0.00 in Q1 to -0.08 in Q20. Bank Credit peaks at -0.06 % vs baseline in Q20, from +0.00 in Q1 to -0.06 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.03 % vs baseline in Q20, from +0.00 in Q1 to -0.03 in Q20. vs USD peaks at -0.05 % vs baseline in Q13, from -0.01 in Q1 to -0.02 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.71 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.84 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.66 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.95 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.79 in Q20. Gold Price peaks at +2011.96 USD/oz (level) in Q12, from +2000.05 in Q1 to +2008.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.00 % vs baseline in Q20, from +0.00 in Q1 to +0.00 in Q20. Services GDP peaks at -0.02 % vs baseline in Q11, from +0.00 in Q1 to -0.01 in Q20. Capital Stock peaks at -0.00 % vs baseline in Q18, from +0.00 in Q1 to -0.00 in Q20.

Timing. By Q20 GDP is still -0.01% from baseline.

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

![Gas Price](charts/CN_P_gas.png)

![Bond Price 30Y](charts/CN_Q_B_30y.png)

[Q1–Q20 JSON for China](numbers/CN.json)

## RU — Russia

The main impact of a -25% United Kingdom housing shock on Russia would be no material drop in GDP of 0.03% by Q11. Equities peak at +0.03% in Q20. This has almost no impact on Russia.

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

![Gas Price](charts/RU_P_gas.png)

![Bond Price 30Y](charts/RU_Q_B_30y.png)

[Q1–Q20 JSON for Russia](numbers/RU.json)

## IT — Italy

The main impact of a -25% United Kingdom housing shock on Italy would be no material drop in GDP of 0.03% by Q12. Equities peak at -0.03% in Q9. This has almost no impact on Italy.

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

![Bond Price 30Y](charts/IT_Q_B_30y.png)

[Q1–Q20 JSON for Italy](numbers/IT.json)

## MY — Malaysia

The main impact of a -25% United Kingdom housing shock on Malaysia would be no material drop in GDP of 0.03% by Q12. Equities peak at -0.05% in Q10. This has almost no impact on Malaysia.

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

![Gas Price](charts/MY_P_gas.png)

![Bond Price 30Y](charts/MY_Q_B_30y.png)

[Q1–Q20 JSON for Malaysia](numbers/MY.json)

## TR — Turkey

The main impact of a -25% United Kingdom housing shock on Turkey would be only a small drop in GDP of 0.02% by Q9. Equities peak at +0.07% in Q20.

Demand and trade. Consumption peaks at -0.01 % vs baseline in Q10, from +0.00 in Q1 to +0.00 in Q20. Investment peaks at +0.05 % vs baseline in Q20, from -0.00 in Q1 to +0.05 in Q20. Net Exports peaks at +0.02 % vs baseline in Q12, from +0.00 in Q1 to +0.02 in Q20. Gov Spending peaks at +0.00 % vs baseline in Q9, from +0.00 in Q1 to -0.00 in Q20. Gov Debt peaks at -0.02 % vs baseline in Q16, from +0.00 in Q1 to -0.02 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.02 % vs baseline in Q7, from +0.00 in Q1 to -0.01 in Q20.

Labour. Employment peaks at -0.02 % vs baseline in Q13, from +0.00 in Q1 to -0.01 in Q20. Unemployment peaks at +0.00 pp in Q11, from +0.00 in Q1 to -0.00 in Q20. Real Wages peaks at -0.05 % vs baseline in Q20, from +0.00 in Q1 to -0.05 in Q20.

Prices. The three-year CPI impulse is -0.03 percentage points. CPI Inflation peaks at -0.01 pp in Q11, from +0.00 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q11, from +0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.01 % vs baseline in Q9, from +0.00 in Q1 to +0.01 in Q20.

Financial conditions. Policy Rate peaks at -0.03 pp (annualized) in Q12, from +0.00 in Q1 to -0.01 in Q20. Real Rate peaks at -0.01 pp (annualized) in Q12, from +0.00 in Q1 to -0.00 in Q20. Govt 3M Yield peaks at -0.03 pp (annualized) in Q12, from +0.00 in Q1 to -0.01 in Q20. Govt 2Y Yield peaks at -0.02 pp (annualized) in Q9, from -0.01 in Q1 to -0.01 in Q20. Govt 5Y Yield peaks at -0.02 pp (annualized) in Q5, from -0.01 in Q1 to -0.00 in Q20. Govt 10Y Yield peaks at -0.01 pp (annualized) in Q5, from -0.01 in Q1 to -0.00 in Q20. Govt 30Y Yield peaks at -0.01 pp (annualized) in Q5, from -0.01 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at +0.08 % vs baseline in Q12, from -0.00 in Q1 to +0.04 in Q20. Bond Price 3M peaks at +0.01 % vs baseline in Q12, from +0.00 in Q1 to +0.00 in Q20. Bond Price 2Y peaks at +0.04 % vs baseline in Q9, from +0.01 in Q1 to +0.01 in Q20. Bond Price 5Y peaks at +0.07 % vs baseline in Q5, from +0.07 in Q1 to +0.01 in Q20. Bond Price 10Y peaks at +0.07 % vs baseline in Q5, from +0.07 in Q1 to +0.03 in Q20. Bond Price 30Y peaks at +0.10 % vs baseline in Q5, from +0.10 in Q1 to +0.06 in Q20. Equity Index peaks at +0.07 % vs baseline in Q20, from +0.00 in Q1 to +0.07 in Q20. VIX peaks at +15.18 index_level in Q12, from +15.00 in Q1 to +15.11 in Q20. Tobin's Q peaks at +0.03 % vs baseline in Q20, from -0.00 in Q1 to +0.03 in Q20. House Prices peaks at -0.02 % vs baseline in Q14, from +0.00 in Q1 to -0.01 in Q20. Bank Equity peaks at -0.07 % vs baseline in Q20, from +0.00 in Q1 to -0.07 in Q20. Bank Credit peaks at -0.06 % vs baseline in Q20, from +0.00 in Q1 to -0.06 in Q20. Credit Spread peaks at +0.01 pp in Q20, from +0.00 in Q1 to +0.01 in Q20.

Nominal FX. NEER peaks at -0.03 % vs baseline in Q8, from -0.00 in Q1 to -0.01 in Q20. vs USD peaks at -0.06 % vs baseline in Q15, from -0.01 in Q1 to -0.03 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.71 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.84 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.66 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.95 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.79 in Q20. Gold Price peaks at +2011.96 USD/oz (level) in Q12, from +2000.05 in Q1 to +2008.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.01 % vs baseline in Q20, from -0.00 in Q1 to +0.01 in Q20. Services GDP peaks at -0.01 % vs baseline in Q9, from +0.00 in Q1 to +0.01 in Q20. Capital Stock peaks at -0.00 % vs baseline in Q13, from +0.00 in Q1 to -0.00 in Q20.

Timing. The GDP response has mostly faded by Q16 (Q20 is +0.01%).

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

![Gas Price](charts/TR_P_gas.png)

![Bond Price 30Y](charts/TR_Q_B_30y.png)

[Q1–Q20 JSON for Turkey](numbers/TR.json)

## BR — Brazil

The main impact of a -25% United Kingdom housing shock on Brazil would be only a small drop in GDP of 0.02% by Q9. Equities peak at +0.06% in Q20.

Demand and trade. Consumption peaks at -0.01 % vs baseline in Q10, from +0.00 in Q1 to +0.00 in Q20. Investment peaks at +0.06 % vs baseline in Q20, from -0.00 in Q1 to +0.06 in Q20. Net Exports peaks at -0.03 % vs baseline in Q20, from +0.00 in Q1 to -0.03 in Q20. Gov Spending peaks at -0.01 % vs baseline in Q20, from +0.00 in Q1 to -0.01 in Q20. Gov Debt peaks at -0.00 % vs baseline in Q16, from +0.00 in Q1 to -0.00 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.06 % vs baseline in Q11, from +0.00 in Q1 to +0.03 in Q20.

Labour. Employment peaks at -0.02 % vs baseline in Q13, from +0.00 in Q1 to -0.01 in Q20. Unemployment peaks at +0.00 pp in Q11, from +0.00 in Q1 to -0.00 in Q20. Real Wages peaks at -0.05 % vs baseline in Q20, from +0.00 in Q1 to -0.05 in Q20.

Prices. The three-year CPI impulse is -0.03 percentage points. CPI Inflation peaks at -0.00 pp in Q11, from +0.00 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q11, from +0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.01 % vs baseline in Q9, from +0.00 in Q1 to +0.01 in Q20.

Financial conditions. Policy Rate peaks at -0.03 pp (annualized) in Q13, from +0.00 in Q1 to -0.02 in Q20. Real Rate peaks at -0.01 pp (annualized) in Q13, from +0.00 in Q1 to -0.00 in Q20. Govt 3M Yield peaks at -0.03 pp (annualized) in Q13, from +0.00 in Q1 to -0.02 in Q20. Govt 2Y Yield peaks at -0.03 pp (annualized) in Q10, from -0.01 in Q1 to -0.01 in Q20. Govt 5Y Yield peaks at -0.02 pp (annualized) in Q6, from -0.02 in Q1 to -0.01 in Q20. Govt 10Y Yield peaks at -0.01 pp (annualized) in Q1, from -0.01 in Q1 to -0.00 in Q20. Govt 30Y Yield peaks at -0.01 pp (annualized) in Q5, from -0.01 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at +0.13 % vs baseline in Q13, from -0.00 in Q1 to +0.08 in Q20. Bond Price 3M peaks at +0.01 % vs baseline in Q13, from +0.00 in Q1 to +0.00 in Q20. Bond Price 2Y peaks at +0.06 % vs baseline in Q10, from +0.01 in Q1 to +0.02 in Q20. Bond Price 5Y peaks at +0.10 % vs baseline in Q6, from +0.09 in Q1 to +0.02 in Q20. Bond Price 10Y peaks at +0.10 % vs baseline in Q1, from +0.10 in Q1 to +0.03 in Q20. Bond Price 30Y peaks at +0.11 % vs baseline in Q5, from +0.11 in Q1 to +0.07 in Q20. Equity Index peaks at +0.06 % vs baseline in Q20, from +0.00 in Q1 to +0.06 in Q20. VIX peaks at +15.18 index_level in Q12, from +15.00 in Q1 to +15.11 in Q20. Tobin's Q peaks at +0.04 % vs baseline in Q20, from -0.00 in Q1 to +0.04 in Q20. House Prices peaks at -0.02 % vs baseline in Q13, from +0.00 in Q1 to -0.01 in Q20. Bank Equity peaks at -0.08 % vs baseline in Q20, from +0.00 in Q1 to -0.08 in Q20. Bank Credit peaks at -0.06 % vs baseline in Q20, from +0.00 in Q1 to -0.06 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at -0.06 % vs baseline in Q11, from -0.00 in Q1 to -0.04 in Q20. vs USD peaks at +0.03 % vs baseline in Q7, from -0.01 in Q1 to +0.01 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.71 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.84 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.66 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.95 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.79 in Q20. Gold Price peaks at +2011.96 USD/oz (level) in Q12, from +2000.05 in Q1 to +2008.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.02 % vs baseline in Q10, from -0.00 in Q1 to -0.00 in Q20. Services GDP peaks at -0.02 % vs baseline in Q9, from +0.00 in Q1 to +0.01 in Q20. Capital Stock peaks at -0.00 % vs baseline in Q12, from +0.00 in Q1 to +0.00 in Q20.

Timing. The GDP response has mostly faded by Q16 (Q20 is +0.01%).

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

![Gas Price](charts/BR_P_gas.png)

![Bond Price (7y)](charts/BR_Q_B.png)

[Q1–Q20 JSON for Brazil](numbers/BR.json)

## MX — Mexico

The main impact of a -25% United Kingdom housing shock on Mexico would be no material drop in GDP of 0.02% by Q10. Equities peak at +0.04% in Q20. This has almost no impact on Mexico.

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

![Gas Price](charts/MX_P_gas.png)

![Bond Price 30Y](charts/MX_Q_B_30y.png)

[Q1–Q20 JSON for Mexico](numbers/MX.json)

## NG — Nigeria

The main impact of a -25% United Kingdom housing shock on Nigeria would be only a small drop in GDP of 0.02% by Q9. Equities peak at +0.06% in Q20.

Demand and trade. Consumption peaks at -0.01 % vs baseline in Q10, from -0.00 in Q1 to +0.01 in Q20. Investment peaks at +0.06 % vs baseline in Q20, from -0.00 in Q1 to +0.06 in Q20. Net Exports peaks at -0.03 % vs baseline in Q20, from +0.00 in Q1 to -0.03 in Q20. Gov Spending peaks at -0.01 % vs baseline in Q20, from +0.00 in Q1 to -0.01 in Q20. Gov Debt peaks at -0.04 % vs baseline in Q16, from +0.00 in Q1 to -0.04 in Q20.

External / FX. The real exchange rate shows real depreciation (a weaker, more competitive home currency). Real Exchange Rate peaks at +0.03 % vs baseline in Q8, from +0.00 in Q1 to -0.00 in Q20.

Labour. Employment peaks at -0.02 % vs baseline in Q13, from +0.00 in Q1 to -0.01 in Q20. Unemployment peaks at +0.00 pp in Q10, from +0.00 in Q1 to -0.00 in Q20. Real Wages peaks at -0.06 % vs baseline in Q20, from +0.00 in Q1 to -0.06 in Q20.

Prices. The three-year CPI impulse is -0.06 percentage points. CPI Inflation peaks at -0.01 pp in Q10, from +0.00 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.01 pp in Q10, from +0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.01 % vs baseline in Q9, from +0.00 in Q1 to +0.01 in Q20.

Financial conditions. Policy Rate peaks at -0.03 pp (annualized) in Q12, from +0.00 in Q1 to -0.02 in Q20. Real Rate peaks at -0.01 pp (annualized) in Q12, from +0.00 in Q1 to -0.00 in Q20. Govt 3M Yield peaks at -0.03 pp (annualized) in Q12, from +0.00 in Q1 to -0.02 in Q20. Govt 2Y Yield peaks at -0.03 pp (annualized) in Q9, from -0.01 in Q1 to -0.01 in Q20. Govt 5Y Yield peaks at -0.02 pp (annualized) in Q5, from -0.02 in Q1 to -0.01 in Q20. Govt 10Y Yield peaks at -0.01 pp (annualized) in Q4, from -0.01 in Q1 to -0.01 in Q20. Govt 30Y Yield peaks at -0.01 pp (annualized) in Q5, from -0.01 in Q1 to -0.01 in Q20. Bond Price (7y) peaks at +0.08 % vs baseline in Q12, from -0.00 in Q1 to +0.04 in Q20. Bond Price 3M peaks at +0.01 % vs baseline in Q12, from -0.00 in Q1 to +0.00 in Q20. Bond Price 2Y peaks at +0.06 % vs baseline in Q9, from +0.02 in Q1 to +0.02 in Q20. Bond Price 5Y peaks at +0.10 % vs baseline in Q5, from +0.09 in Q1 to +0.03 in Q20. Bond Price 10Y peaks at +0.11 % vs baseline in Q4, from +0.11 in Q1 to +0.04 in Q20. Bond Price 30Y peaks at +0.14 % vs baseline in Q5, from +0.14 in Q1 to +0.09 in Q20. Equity Index peaks at +0.06 % vs baseline in Q20, from +0.00 in Q1 to +0.06 in Q20. VIX peaks at +15.18 index_level in Q12, from +15.00 in Q1 to +15.11 in Q20. Tobin's Q peaks at +0.04 % vs baseline in Q20, from -0.00 in Q1 to +0.04 in Q20. House Prices peaks at -0.02 % vs baseline in Q13, from +0.00 in Q1 to -0.00 in Q20. Bank Equity peaks at -0.04 % vs baseline in Q20, from +0.00 in Q1 to -0.04 in Q20. Bank Credit peaks at -0.07 % vs baseline in Q20, from +0.00 in Q1 to -0.07 in Q20. Credit Spread peaks at +0.01 pp in Q20, from +0.00 in Q1 to +0.01 in Q20.

Nominal FX. NEER peaks at -0.02 % vs baseline in Q7, from -0.00 in Q1 to +0.01 in Q20. vs USD peaks at -0.05 % vs baseline in Q16, from -0.00 in Q1 to -0.03 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.71 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.84 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.66 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.95 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.79 in Q20. Gold Price peaks at +2011.96 USD/oz (level) in Q12, from +2000.05 in Q1 to +2008.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at -0.01 % vs baseline in Q8, from -0.00 in Q1 to +0.01 in Q20. Services GDP peaks at -0.01 % vs baseline in Q9, from +0.00 in Q1 to +0.01 in Q20. Capital Stock peaks at +0.00 % vs baseline in Q20, from +0.00 in Q1 to +0.00 in Q20.

Timing. The GDP response has mostly faded by Q16 (Q20 is +0.01%).

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

![Gas Price](charts/NG_P_gas.png)

![Bond Price 30Y](charts/NG_Q_B_30y.png)

[Q1–Q20 JSON for Nigeria](numbers/NG.json)

## IN — India

The main impact of a -25% United Kingdom housing shock on India would be only a small drop in GDP of 0.02% by Q9. Equities peak at +0.07% in Q20.

Demand and trade. Consumption peaks at -0.01 % vs baseline in Q10, from +0.00 in Q1 to +0.00 in Q20. Investment peaks at +0.07 % vs baseline in Q20, from -0.00 in Q1 to +0.07 in Q20. Net Exports peaks at +0.01 % vs baseline in Q11, from +0.00 in Q1 to +0.01 in Q20. Gov Spending peaks at +0.00 % vs baseline in Q9, from +0.00 in Q1 to -0.00 in Q20. Gov Debt peaks at -0.03 % vs baseline in Q16, from +0.00 in Q1 to -0.02 in Q20.

External / FX. The real exchange rate shows real appreciation (a stronger home currency). Real Exchange Rate peaks at -0.03 % vs baseline in Q20, from +0.00 in Q1 to -0.03 in Q20.

Labour. Employment peaks at -0.01 % vs baseline in Q14, from +0.00 in Q1 to -0.01 in Q20. Unemployment peaks at +0.00 pp in Q11, from +0.00 in Q1 to -0.00 in Q20. Real Wages peaks at -0.05 % vs baseline in Q20, from +0.00 in Q1 to -0.05 in Q20.

Prices. The three-year CPI impulse is -0.05 percentage points. CPI Inflation peaks at -0.01 pp in Q10, from +0.00 in Q1 to -0.00 in Q20. Domestic Infl. peaks at -0.00 pp in Q10, from +0.00 in Q1 to -0.00 in Q20. Marginal Cost peaks at -0.01 % vs baseline in Q9, from +0.00 in Q1 to +0.01 in Q20.

Financial conditions. Policy Rate peaks at -0.04 pp (annualized) in Q13, from +0.00 in Q1 to -0.02 in Q20. Real Rate peaks at -0.01 pp (annualized) in Q13, from +0.00 in Q1 to -0.01 in Q20. Govt 3M Yield peaks at -0.04 pp (annualized) in Q13, from +0.00 in Q1 to -0.02 in Q20. Govt 2Y Yield peaks at -0.03 pp (annualized) in Q10, from -0.01 in Q1 to -0.01 in Q20. Govt 5Y Yield peaks at -0.02 pp (annualized) in Q6, from -0.02 in Q1 to -0.00 in Q20. Govt 10Y Yield peaks at -0.01 pp (annualized) in Q1, from -0.01 in Q1 to -0.00 in Q20. Govt 30Y Yield peaks at -0.00 pp (annualized) in Q4, from -0.00 in Q1 to -0.00 in Q20. Bond Price (7y) peaks at +0.18 % vs baseline in Q13, from -0.00 in Q1 to +0.11 in Q20. Bond Price 3M peaks at +0.01 % vs baseline in Q13, from -0.00 in Q1 to +0.01 in Q20. Bond Price 2Y peaks at +0.06 % vs baseline in Q10, from +0.02 in Q1 to +0.03 in Q20. Bond Price 5Y peaks at +0.11 % vs baseline in Q6, from +0.10 in Q1 to +0.02 in Q20. Bond Price 10Y peaks at +0.10 % vs baseline in Q1, from +0.10 in Q1 to +0.02 in Q20. Bond Price 30Y peaks at +0.09 % vs baseline in Q4, from +0.09 in Q1 to +0.03 in Q20. Equity Index peaks at +0.07 % vs baseline in Q20, from +0.00 in Q1 to +0.07 in Q20. VIX peaks at +15.18 index_level in Q12, from +15.00 in Q1 to +15.11 in Q20. Tobin's Q peaks at +0.05 % vs baseline in Q20, from -0.00 in Q1 to +0.05 in Q20. House Prices peaks at -0.01 % vs baseline in Q13, from +0.00 in Q1 to -0.00 in Q20. Bank Equity peaks at -0.07 % vs baseline in Q20, from +0.00 in Q1 to -0.07 in Q20. Bank Credit peaks at -0.06 % vs baseline in Q20, from +0.00 in Q1 to -0.06 in Q20. Credit Spread peaks at +0.00 pp in Q20, from +0.00 in Q1 to +0.00 in Q20.

Nominal FX. NEER peaks at +0.02 % vs baseline in Q20, from -0.01 in Q1 to +0.02 in Q20. vs USD peaks at -0.07 % vs baseline in Q16, from -0.00 in Q1 to -0.05 in Q20.

Commodities. Energy Price peaks at +80.00 USD/bbl (level) in Q1, from +80.00 in Q1 to +79.71 in Q20. Metals Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.84 in Q20. Food Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.66 in Q20. Gas Price peaks at +4.00 USD/mmBtu (level) in Q1, from +4.00 in Q1 to +3.98 in Q20. Copper Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.95 in Q20. Wheat Price peaks at +100.00 index (level) in Q1, from +100.00 in Q1 to +99.79 in Q20. Gold Price peaks at +2011.96 USD/oz (level) in Q12, from +2000.05 in Q1 to +2008.00 in Q20.

Sectoral and capital. Manuf. GDP peaks at +0.02 % vs baseline in Q20, from -0.00 in Q1 to +0.02 in Q20. Services GDP peaks at -0.01 % vs baseline in Q9, from +0.00 in Q1 to +0.01 in Q20. Capital Stock peaks at +0.00 % vs baseline in Q20, from +0.00 in Q1 to +0.00 in Q20.

Timing. The GDP response has mostly faded by Q16 (Q20 is +0.01%).

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

![Gas Price](charts/IN_P_gas.png)

![Bond Price (7y)](charts/IN_Q_B.png)

[Q1–Q20 JSON for India](numbers/IN.json)

## TH — Thailand

The main impact of a -25% United Kingdom housing shock on Thailand would be no material drop in GDP of 0.02% by Q11. Equities peak at -0.03% in Q9. This has almost no impact on Thailand.

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

![Bond Price 30Y](charts/TH_Q_B_30y.png)

[Q1–Q20 JSON for Thailand](numbers/TH.json)

## KR — South Korea

The main impact of a -25% United Kingdom housing shock on South Korea would be no material drop in GDP of 0.02% by Q10. Equities peak at +0.03% in Q20. This has almost no impact on South Korea.

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

![vs USD](charts/KR_USD.png)

[Q1–Q20 JSON for South Korea](numbers/KR.json)

## CO — Colombia

The main impact of a -25% United Kingdom housing shock on Colombia would be no material drop in GDP of 0.01% by Q9. Equities peak at +0.04% in Q20. This has almost no impact on Colombia.

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

![Gas Price](charts/CO_P_gas.png)

![Bond Price 30Y](charts/CO_Q_B_30y.png)

[Q1–Q20 JSON for Colombia](numbers/CO.json)

## CL — Chile

The main impact of a -25% United Kingdom housing shock on Chile would be no material drop in GDP of 0.01% by Q9. Equities peak at +0.04% in Q20. This has almost no impact on Chile.

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

![Bond Price 30Y](charts/CL_Q_B_30y.png)

[Q1–Q20 JSON for Chile](numbers/CL.json)

## ID — Indonesia

The main impact of a -25% United Kingdom housing shock on Indonesia would be no material rise in GDP of 0.01% by Q20. Equities peak at +0.05% in Q20. This has almost no impact on Indonesia.

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

![Gas Price](charts/ID_P_gas.png)

![Bond Price (7y)](charts/ID_Q_B.png)

[Q1–Q20 JSON for Indonesia](numbers/ID.json)


---

These figures are model IRFs versus baseline, not forecasts, and not financial advice.
