# Global Macro Economic Simulations and Financial Market Responses

v6 · IRF · evaluation

**Open the typeset report (this is the document):** https://robomacro.com/GlobalMacroTrainingDataset/uk_housing_25/

GitHub and Hugging Face show `.html` as source code. That is not the report. Read it on robomacro.com, or keep scrolling this page.

## What's the impact of UK housing -25%

a -25% United Kingdom housing shock. Every path is a model impulse response versus baseline, not a forecast and not financial advice.

### Summary

This note traces the model response to a -25% United Kingdom housing shock. Every path is an impulse response versus an unchanged baseline — not a forecast of what will happen in the world and not a reading of market data. The chapters that follow are already sorted by the size of the GDP response.

United Kingdom is where the shock lands. GDP contracts by 3.27% by Q20, a first-order GDP response for a -25% United Kingdom housing shock. Equities soften 8.09%, and the three-year CPI impulse is -0.71 percentage points. The move shows up first in private investment / the cost of capital, then in household consumption, government spending. That is the main adjustment: a change in financial conditions and real income, then the usual lag into activity and prices. It is the conditional elasticity to the shock that was switched on, not a prediction that this path will be realised.

Spillovers are not a carbon copy of that first path. Netherlands contracts by 0.14% versus baseline by Q20 — a moderate GDP response. Equities soften 0.37%. The move shows up first in private investment / the cost of capital, then in household consumption, employment. Switzerland contracts by 0.14% versus baseline by Q14 — a moderate GDP response. Equities soften 0.52%, and the three-year CPI impulse is -0.06 percentage points. The move shows up first in private investment / the cost of capital, then in household consumption, employment. Germany contracts by 0.11% versus baseline by Q14 — a moderate GDP response. Equities soften 0.21%. The move shows up first in private investment / the cost of capital, then in real wages, employment. The contrast is the point: neighbours feel a fraction of the housing-country hit, not a copy of it.

France contracts by 0.10% versus baseline by Q14 — only a small GDP response. Equities soften 0.20%. The move shows up first in private investment / the cost of capital, then in government debt, employment.

A few prices are common across the panel. On the government curve, 30-year bond prices rally 23.23% by Q20, and unused tenors stay in the background rather than getting a sentence each; the NEER prints a trade-weighted depreciation (-0.25% in Q20). Treat those as the shared financial backdrop, not as extra shocks, unless they appear in the active treatment.

Read GDP as percent of baseline GDP: −0.52 is minus half a percent, never −52%. A 200 basis-point move is 2.00 percentage points on the policy rate. CPI over three years is the sum of twelve quarterly impulses, not an annualised rate. A rising real exchange rate is a real depreciation — a weaker, more competitive home currency.

The remaining economies are smaller spillovers, written in the same order in the chapters that follow. Each chapter is a desk note, not a catalog of every series. This material is a model-based summary and is not financial advice.


![UK GDP](charts/global_UK_Y.png)

![NL GDP](charts/global_NL_Y.png)

![CH GDP](charts/global_CH_Y.png)

![DE GDP](charts/global_DE_Y.png)

![US Equity Index](charts/global_US_equity.png)

![US Policy Rate](charts/global_US_i.png)

## UK — United Kingdom

The main impact of a -25% United Kingdom housing shock on United Kingdom is a large drop in GDP of 3.27% by Q20. This is a model impulse response versus baseline, not a forecast. Equities soften 8.09% by Q20. The three-year CPI impulse is -0.71 percentage points.

Demand and trade. Private investment / the cost of capital falls 8.84% by Q20; household consumption falls 2.08% by Q20; government spending rises 0.67% by Q20; government debt falls 0.28% by Q20; the same direction shows up in the trade balance.

Labour. Employment falls 3.38% by Q20; unemployment rises by +2.06 percentage points in Q20; real wages falls 1.97% by Q20.

Prices. Firms' marginal cost falls 1.96% by Q20; CPI inflation falls 0.17 percentage points by Q20; domestic inflation falls 0.12 percentage points by Q20.

Policy rates and the government curve. 30-year bond prices rally 23.23% by Q20; 10-year bond prices rally 6.92% by Q20; 5-year bond prices rally 2.70% by Q20; bond prices (higher discount rates) rally 2.22% by Q20; the same direction shows up in 30-year government yields, 10-year government yields, 2-year bond prices; the rest of the government curve barely moves.

Exchange rates. The NEER prints a trade-weighted depreciation (-0.25% in Q20); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.24% in Q20; versus the dollar the home currency is weaker versus the dollar (+0.22% in Q20).

Equities and risk. Equity prices / financial conditions falls 8.09% by Q20; Tobin's Q (the value of installed capital) falls 6.19% by Q20; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices fall 27.63% by Q20; bank equity falls 12.01% by Q20; bank credit supply falls 9.55% by Q20; lending spreads rises 0.12 percentage points by Q20.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Services output falls 2.59% by Q20; manufacturing output falls 0.62% by Q20; the capital stock falls 0.50% by Q20.

By Q20, GDP is still -3.27% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a -25% United Kingdom housing shock on Netherlands is a moderate drop in GDP of 0.14% by Q20. This is a model impulse response versus baseline, not a forecast. Equities soften 0.37% by Q20.

Demand and trade. Private investment / the cost of capital falls 0.36% by Q20; household consumption falls 0.09% by Q20; the trade balance, government spending, government debt stay close to baseline.

Labour. Employment falls 0.14% by Q20; real wages falls 0.13% by Q20; unemployment rises by +0.10 percentage points in Q20.

Prices. Firms' marginal cost falls 0.08% by Q20; CPI inflation, domestic inflation stay close to baseline.

Policy rates and the government curve. 30-year bond prices rally 0.28% by Q10; bond prices (higher discount rates) rally 0.16% by Q19; 10-year bond prices rally 0.15% by Q11; 5-year bond prices rally 0.10% by Q13; the rest of the government curve barely moves.

Exchange rates. The real exchange rate, the nominal effective exchange rate (increase = trade-weighted appreciation), the bilateral real versus the dollar (increase = home weaker vs USD) stay close to baseline.

Equities and risk. Equity prices / financial conditions falls 0.37% by Q20; Tobin's Q (the value of installed capital) falls 0.25% by Q20; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. Bank equity falls 0.34% by Q20; bank credit supply falls 0.27% by Q20; house prices fall 0.18% by Q20; house prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Services output falls 0.11% by Q20; manufacturing output, the capital stock stay close to baseline.

By Q20, GDP is still -0.14% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a -25% United Kingdom housing shock on Switzerland is a moderate drop in GDP of 0.14% by Q14. This is a model impulse response versus baseline, not a forecast. Equities soften 0.52% by Q14. The three-year CPI impulse is -0.06 percentage points.

Demand and trade. Private investment / the cost of capital falls 0.33% by Q12; household consumption falls 0.10% by Q14; the trade balance, government spending, government debt stay close to baseline.

Labour. Employment falls 0.14% by Q18; real wages falls 0.10% by Q20; unemployment rises by +0.10 percentage points in Q19.

Prices. Firms' marginal cost falls 0.08% by Q14; CPI inflation, domestic inflation stay close to baseline.

Policy rates and the government curve. 30-year bond prices rally 0.74% by Q14; 10-year bond prices rally 0.37% by Q16; bond prices (higher discount rates) rally 0.33% by Q20; 5-year bond prices rally 0.21% by Q18; the same direction shows up in 2-year bond prices; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-0.16% in Q15); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.12% in Q20; the NEER prints a trade-weighted appreciation (+0.10% in Q20).

Equities and risk. Equity prices / financial conditions falls 0.52% by Q14; Tobin's Q (the value of installed capital) falls 0.23% by Q12; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. Bank equity falls 0.45% by Q20; bank credit supply falls 0.35% by Q20; house prices fall 0.16% by Q20; house prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Services output falls 0.11% by Q14; manufacturing output, the capital stock stay close to baseline.

By Q20, GDP is still -0.12% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a -25% United Kingdom housing shock on Germany is a moderate drop in GDP of 0.11% by Q14. This is a model impulse response versus baseline, not a forecast. Equities soften 0.21% by Q13.

Demand and trade. Private investment / the cost of capital falls 0.29% by Q12; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Real wages falls 0.12% by Q20; employment falls 0.12% by Q20; unemployment rises by +0.08 percentage points in Q19.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. 30-year bond prices rally 0.28% by Q10; bond prices (higher discount rates) rally 0.16% by Q19; 10-year bond prices rally 0.15% by Q11; 5-year bond prices rally 0.10% by Q13; the rest of the government curve barely moves.

Exchange rates. The real exchange rate, the nominal effective exchange rate (increase = trade-weighted appreciation), the bilateral real versus the dollar (increase = home weaker vs USD) stay close to baseline.

Equities and risk. Equity prices / financial conditions falls 0.21% by Q13; Tobin's Q (the value of installed capital) falls 0.20% by Q12; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. Bank equity falls 0.39% by Q20; bank credit supply falls 0.32% by Q20; house prices fall 0.13% by Q20; house prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output, services output, the capital stock stay close to baseline.

By Q20, GDP is still -0.10% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a -25% United Kingdom housing shock on France is only a small drop in GDP of 0.10% by Q14. This is a model impulse response versus baseline, not a forecast. Equities soften 0.20% by Q13.

Demand and trade. Private investment / the cost of capital falls 0.24% by Q12; government debt rises 0.08% by Q20; household consumption, the trade balance, government spending stay close to baseline.

Labour. Employment falls 0.10% by Q20; real wages falls 0.08% by Q20; unemployment rises by +0.07 percentage points in Q20.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. 30-year bond prices rally 0.28% by Q10; bond prices (higher discount rates) rally 0.16% by Q19; 10-year bond prices rally 0.15% by Q11; 5-year bond prices rally 0.10% by Q13; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-0.08% in Q15); the real exchange rate, the nominal effective exchange rate (increase = trade-weighted appreciation) stay close to baseline.

Equities and risk. Equity prices / financial conditions falls 0.20% by Q13; Tobin's Q (the value of installed capital) falls 0.17% by Q12; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. Bank equity falls 0.32% by Q20; bank credit supply falls 0.25% by Q20; house prices fall 0.11% by Q20; house prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output, services output, the capital stock stay close to baseline.

By Q20, GDP is still -0.09% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a -25% United Kingdom housing shock on Norway is only a small drop in GDP of 0.09% by Q16. This is a model impulse response versus baseline, not a forecast. Equities soften 0.17% by Q15.

Demand and trade. Private investment / the cost of capital falls 0.19% by Q12; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment falls 0.10% by Q20; real wages falls 0.08% by Q20; unemployment rises by +0.07 percentage points in Q20.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. 30-year bond prices rally 1.14% by Q20; 10-year bond prices rally 0.54% by Q20; bond prices (higher discount rates) rally 0.36% by Q20; 5-year bond prices rally 0.29% by Q20; the same direction shows up in 2-year bond prices, 10-year government yields, 5-year government yields; the rest of the government curve barely moves.

Exchange rates. The NEER prints a trade-weighted depreciation (-0.18% in Q20); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.17% in Q20; versus the dollar the home currency is weaker versus the dollar (+0.15% in Q20).

Equities and risk. Equity prices / financial conditions falls 0.17% by Q15; Tobin's Q (the value of installed capital) falls 0.13% by Q12; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. Bank equity falls 0.17% by Q20; bank credit supply falls 0.14% by Q20; house prices fall 0.10% by Q20; house prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output, services output, the capital stock stay close to baseline.

By Q20, GDP is still -0.09% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a -25% United Kingdom housing shock on the United States is only a small drop in GDP of 0.09% by Q12. This is a model impulse response versus baseline, not a forecast. Equities soften 0.24% by Q11.

Demand and trade. Private investment / the cost of capital falls 0.16% by Q9; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Real wages falls 0.10% by Q20; employment falls 0.10% by Q15; unemployment rises by +0.06 percentage points in Q16.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. 30-year bond prices rally 0.60% by Q8; bond prices (higher discount rates) rally 0.46% by Q16; 10-year bond prices rally 0.37% by Q8; 5-year bond prices rally 0.27% by Q10; the same direction shows up in 2-year bond prices, the local policy rate, 3-month government yields; the rest of the government curve barely moves.

Exchange rates. The real exchange rate, the nominal effective exchange rate (increase = trade-weighted appreciation), the bilateral real versus the dollar (increase = home weaker vs USD) stay close to baseline.

Equities and risk. Equity prices / financial conditions falls 0.24% by Q11; Tobin's Q (the value of installed capital) falls 0.11% by Q9; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. Bank equity falls 0.34% by Q20; bank credit supply falls 0.28% by Q20; house prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output, services output, the capital stock stay close to baseline.

By Q20, GDP is still -0.05% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a -25% United Kingdom housing shock on Saudi Arabia is only a small drop in GDP of 0.07% by Q14. This is a model impulse response versus baseline, not a forecast. Equities soften 0.27% by Q13.

Demand and trade. Government debt falls 0.14% by Q20; private investment / the cost of capital falls 0.11% by Q9; household consumption, the trade balance, government spending stay close to baseline.

Labour. Employment falls 0.08% by Q20; unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. 30-year bond prices rally 0.60% by Q8; 10-year bond prices rally 0.37% by Q8; bond prices (higher discount rates) rally 0.35% by Q16; 5-year bond prices rally 0.27% by Q10; the same direction shows up in 2-year bond prices, the local policy rate, 3-month government yields; the rest of the government curve barely moves.

Exchange rates. The real exchange rate, the nominal effective exchange rate (increase = trade-weighted appreciation), the bilateral real versus the dollar (increase = home weaker vs USD) stay close to baseline.

Equities and risk. Equity prices / financial conditions falls 0.27% by Q13; Tobin's Q (the value of installed capital) falls 0.08% by Q9; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. Bank equity falls 0.09% by Q20; house prices fall 0.09% by Q20; house prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output, services output, the capital stock stay close to baseline.

By Q20, GDP is still -0.07% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a -25% United Kingdom housing shock on Sweden is only a small drop in GDP of 0.07% by Q17. This is a model impulse response versus baseline, not a forecast. Equities soften 0.18% by Q15.

Demand and trade. Private investment / the cost of capital falls 0.16% by Q14; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Real wages falls 0.09% by Q20; unemployment rises by +0.05 percentage points in Q20; employment stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. 30-year bond prices rally 0.41% by Q10; 10-year bond prices rally 0.23% by Q16; bond prices (higher discount rates) rally 0.18% by Q20; 5-year bond prices rally 0.13% by Q18; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-0.12% in Q17); the NEER prints a trade-weighted appreciation (+0.10% in Q20); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.09% in Q20.

Equities and risk. Equity prices / financial conditions falls 0.18% by Q15; Tobin's Q (the value of installed capital) falls 0.11% by Q14; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. Bank equity falls 0.16% by Q20; bank credit supply falls 0.13% by Q20; house prices fall 0.08% by Q20; house prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output, services output, the capital stock stay close to baseline.

By Q20, GDP is still -0.07% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a -25% United Kingdom housing shock on Australia is only a small drop in GDP of 0.06% by Q13. This is a model impulse response versus baseline, not a forecast. Equities soften 0.13% by Q12.

Demand and trade. Private investment / the cost of capital falls 0.12% by Q11; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. 30-year bond prices rally 0.61% by Q11; 10-year bond prices rally 0.32% by Q12; bond prices (higher discount rates) rally 0.28% by Q19; 5-year bond prices rally 0.19% by Q13; the same direction shows up in 2-year bond prices; the rest of the government curve barely moves.

Exchange rates. The NEER prints a trade-weighted depreciation (-0.14% in Q17); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.12% in Q15; versus the dollar the home currency is weaker versus the dollar (+0.09% in Q20).

Equities and risk. Equity prices / financial conditions falls 0.13% by Q12; Tobin's Q (the value of installed capital) falls 0.09% by Q11; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. Bank equity falls 0.21% by Q20; bank credit supply falls 0.17% by Q20; house prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output, services output, the capital stock stay close to baseline.

By Q20, GDP is still -0.05% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a -25% United Kingdom housing shock on Spain is only a small drop in GDP of 0.06% by Q13. This is a model impulse response versus baseline, not a forecast. Equities soften 0.10% by Q12.

Demand and trade. Private investment / the cost of capital falls 0.15% by Q12; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. 30-year bond prices rally 0.28% by Q10; bond prices (higher discount rates) rally 0.16% by Q19; 10-year bond prices rally 0.15% by Q11; 5-year bond prices rally 0.10% by Q13; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-0.09% in Q15); the real exchange rate, the nominal effective exchange rate (increase = trade-weighted appreciation) stay close to baseline.

Equities and risk. Tobin's Q (the value of installed capital) falls 0.10% by Q12; equity prices / financial conditions falls 0.10% by Q12; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. Bank equity falls 0.22% by Q20; bank credit supply falls 0.17% by Q20; house prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output, services output, the capital stock stay close to baseline.

By Q20, GDP is still -0.06% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a -25% United Kingdom housing shock on Canada is only a small drop in GDP of 0.06% by Q12. This is a model impulse response versus baseline, not a forecast. Equities soften 0.14% by Q12.

Demand and trade. Private investment / the cost of capital falls 0.12% by Q10; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. 30-year bond prices rally 0.55% by Q9; bond prices (higher discount rates) rally 0.29% by Q16; 10-year bond prices rally 0.28% by Q9; 5-year bond prices rally 0.19% by Q10; the same direction shows up in 2-year bond prices; the rest of the government curve barely moves.

Exchange rates. The real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.10% in Q20; the NEER prints a trade-weighted depreciation (-0.10% in Q20); versus the dollar the home currency is weaker versus the dollar (+0.08% in Q20).

Equities and risk. Equity prices / financial conditions falls 0.14% by Q12; Tobin's Q (the value of installed capital) falls 0.08% by Q10; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. Bank equity falls 0.16% by Q20; bank credit supply falls 0.13% by Q20; house prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output, services output, the capital stock stay close to baseline.

By Q20, GDP is still -0.05% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a -25% United Kingdom housing shock on Japan is only a small drop in GDP of 0.06% by Q13. This is a model impulse response versus baseline, not a forecast. Equities soften 0.14% by Q12. The three-year CPI impulse is -0.06 percentage points.

Demand and trade. Private investment / the cost of capital falls 0.15% by Q12; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 0.11% by Q19; 30-year bond prices rally 0.10% by Q9; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-0.29% in Q16); the NEER prints a trade-weighted appreciation (+0.26% in Q20); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.25% in Q20.

Equities and risk. Equity prices / financial conditions falls 0.14% by Q12; Tobin's Q (the value of installed capital) falls 0.10% by Q12; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. Bank equity falls 0.22% by Q20; bank credit supply falls 0.18% by Q20; house prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output, services output, the capital stock stay close to baseline.

By Q20, GDP is still -0.05% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a -25% United Kingdom housing shock on Argentina is only a small rise in GDP of 0.05% by Q20. This is a model impulse response versus baseline, not a forecast. Equities firm 0.13% by Q20.

Demand and trade. Private investment / the cost of capital rises 0.12% by Q20; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. 30-year bond prices cheapen 0.14% by Q19; 10-year bond prices cheapen 0.10% by Q19; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-0.10% in Q16); the real exchange rate, the nominal effective exchange rate (increase = trade-weighted appreciation) stay close to baseline.

Equities and risk. Equity prices / financial conditions rises 0.13% by Q20; Tobin's Q (the value of installed capital) rises 0.08% by Q20; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output, services output, the capital stock stay close to baseline.

By Q20, GDP is still +0.05% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a -25% United Kingdom housing shock on Poland is almost no drop in GDP of 0.04% by Q12. This is a model impulse response versus baseline, not a forecast. This has almost no impact on Poland.

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

The main impact of a -25% United Kingdom housing shock on South Africa is only a small drop in GDP of 0.04% by Q11. This is a model impulse response versus baseline, not a forecast. Equities soften 0.13% by Q10.

Demand and trade. Private investment / the cost of capital falls 0.08% by Q9; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. 30-year bond prices rally 0.16% by Q7; 10-year bond prices rally 0.10% by Q7; bond prices (higher discount rates) rally 0.09% by Q14; the rest of the government curve barely moves.

Exchange rates. The real exchange rate, the nominal effective exchange rate (increase = trade-weighted appreciation), the bilateral real versus the dollar (increase = home weaker vs USD) stay close to baseline.

Equities and risk. Equity prices / financial conditions falls 0.13% by Q10; the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. Bank equity falls 0.14% by Q20; bank credit supply falls 0.12% by Q20; house prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output, services output, the capital stock stay close to baseline.

By Q20, GDP is still -0.02% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a -25% United Kingdom housing shock on China is only a small drop in GDP of 0.03% by Q11. This is a model impulse response versus baseline, not a forecast.

Demand and trade. Household consumption, private investment / the cost of capital, the trade balance, government spending stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. 30-year bond prices rally 0.17% by Q6; bond prices (higher discount rates) rally 0.17% by Q17; 10-year bond prices rally 0.16% by Q5; 5-year bond prices rally 0.13% by Q10; the rest of the government curve barely moves.

Exchange rates. The real exchange rate, the nominal effective exchange rate (increase = trade-weighted appreciation), the bilateral real versus the dollar (increase = home weaker vs USD) stay close to baseline.

Equities and risk. Equity prices / financial conditions, the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output, services output, the capital stock stay close to baseline.

By Q20, GDP is still -0.01% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a -25% United Kingdom housing shock on Russia is almost no drop in GDP of 0.03% by Q11. This is a model impulse response versus baseline, not a forecast. This has almost no impact on Russia.

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

The main impact of a -25% United Kingdom housing shock on Italy is almost no drop in GDP of 0.03% by Q12. This is a model impulse response versus baseline, not a forecast. This has almost no impact on Italy.

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

The main impact of a -25% United Kingdom housing shock on Malaysia is almost no drop in GDP of 0.03% by Q12. This is a model impulse response versus baseline, not a forecast. This has almost no impact on Malaysia.

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

The main impact of a -25% United Kingdom housing shock on Turkey is only a small drop in GDP of 0.02% by Q9. This is a model impulse response versus baseline, not a forecast.

Demand and trade. Household consumption, private investment / the cost of capital, the trade balance, government spending stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. 30-year bond prices rally 0.10% by Q5; the rest of the government curve barely moves.

Exchange rates. The real exchange rate, the nominal effective exchange rate (increase = trade-weighted appreciation), the bilateral real versus the dollar (increase = home weaker vs USD) stay close to baseline.

Equities and risk. Equity prices / financial conditions, the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output, services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q16 (Q20 is still +0.01%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a -25% United Kingdom housing shock on Brazil is only a small drop in GDP of 0.02% by Q9. This is a model impulse response versus baseline, not a forecast.

Demand and trade. Household consumption, private investment / the cost of capital, the trade balance, government spending stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 0.13% by Q13; 30-year bond prices rally 0.11% by Q5; 5-year bond prices rally 0.10% by Q6; 10-year bond prices rally 0.10% by Q1; the rest of the government curve barely moves.

Exchange rates. The real exchange rate, the nominal effective exchange rate (increase = trade-weighted appreciation), the bilateral real versus the dollar (increase = home weaker vs USD) stay close to baseline.

Equities and risk. Equity prices / financial conditions, the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output, services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q16 (Q20 is still +0.01%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a -25% United Kingdom housing shock on Mexico is almost no drop in GDP of 0.02% by Q10. This is a model impulse response versus baseline, not a forecast. This has almost no impact on Mexico.

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

The main impact of a -25% United Kingdom housing shock on Nigeria is only a small drop in GDP of 0.02% by Q9. This is a model impulse response versus baseline, not a forecast. The three-year CPI impulse is -0.06 percentage points.

Demand and trade. Household consumption, private investment / the cost of capital, the trade balance, government spending stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. 30-year bond prices rally 0.14% by Q5; 10-year bond prices rally 0.11% by Q4; 5-year bond prices rally 0.10% by Q5; bond prices (higher discount rates) rally 0.08% by Q12; the rest of the government curve barely moves.

Exchange rates. The real exchange rate, the nominal effective exchange rate (increase = trade-weighted appreciation), the bilateral real versus the dollar (increase = home weaker vs USD) stay close to baseline.

Equities and risk. Equity prices / financial conditions, the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output, services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q16 (Q20 is still +0.01%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a -25% United Kingdom housing shock on India is only a small drop in GDP of 0.02% by Q9. This is a model impulse response versus baseline, not a forecast.

Demand and trade. Household consumption, private investment / the cost of capital, the trade balance, government spending stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 0.18% by Q13; 5-year bond prices rally 0.11% by Q6; 10-year bond prices rally 0.10% by Q1; 30-year bond prices rally 0.09% by Q4; the rest of the government curve barely moves.

Exchange rates. The real exchange rate, the nominal effective exchange rate (increase = trade-weighted appreciation), the bilateral real versus the dollar (increase = home weaker vs USD) stay close to baseline.

Equities and risk. Equity prices / financial conditions, the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output, services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q16 (Q20 is still +0.01%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a -25% United Kingdom housing shock on Thailand is almost no drop in GDP of 0.02% by Q11. This is a model impulse response versus baseline, not a forecast. This has almost no impact on Thailand.

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

The main impact of a -25% United Kingdom housing shock on South Korea is almost no drop in GDP of 0.02% by Q10. This is a model impulse response versus baseline, not a forecast. This has almost no impact on South Korea.

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

The main impact of a -25% United Kingdom housing shock on Colombia is almost no drop in GDP of 0.01% by Q9. This is a model impulse response versus baseline, not a forecast. This has almost no impact on Colombia.

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

The main impact of a -25% United Kingdom housing shock on Chile is almost no drop in GDP of 0.01% by Q9. This is a model impulse response versus baseline, not a forecast. This has almost no impact on Chile.

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

The main impact of a -25% United Kingdom housing shock on Indonesia is almost no rise in GDP of 0.01% by Q20. This is a model impulse response versus baseline, not a forecast. This has almost no impact on Indonesia.

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
