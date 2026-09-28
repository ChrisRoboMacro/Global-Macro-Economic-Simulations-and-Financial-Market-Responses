# Global Macro Economic Simulations and Financial Market Responses

v6 · IRF · evaluation

**Open the typeset report (this is the document):** https://robomacro.com/GlobalMacroTrainingDataset/us_hike_200/

GitHub and Hugging Face show `.html` as source code. That is not the report. Read it on robomacro.com, or keep scrolling this page.

## What's the impact of US policy rate +200bp

a 200 basis-point (2.00 percentage-point) rise in United States interest rates. Every path is a model impulse response versus baseline, not a forecast and not financial advice.

### Summary

This note traces the model response to a 200 basis-point (2.00 percentage-point) rise in United States interest rates. Every path is an impulse response versus an unchanged baseline — not a forecast of what will happen in the world and not a reading of market data. The chapters that follow are already sorted by the size of the GDP response.

The United States is where the shock lands. GDP contracts by 0.52% by Q12, a first-order GDP response for a 200 basis-point (2.00 percentage-point) rise in United States interest rates. Equities soften 1.82%, and the three-year CPI impulse is -0.25 percentage points. The move shows up first in private investment / the cost of capital, then in household consumption, government debt. That is the main adjustment: a change in financial conditions and real income, then the usual lag into activity and prices. It is the conditional elasticity to the shock that was switched on, not a prediction that this path will be realised.

Spillovers are not a carbon copy of that first path. Saudi Arabia contracts by 0.18% versus baseline by Q14 — a moderate GDP response. Equities soften 0.76%, and the three-year CPI impulse is -0.19 percentage points. The move shows up first in private investment / the cost of capital, then in government debt, the trade balance. Mexico contracts by 0.17% versus baseline by Q13 — a moderate GDP response. Equities soften 0.49%, and the three-year CPI impulse is +0.40 percentage points. The move shows up first in private investment / the cost of capital, then in the trade balance, government debt. Canada contracts by 0.15% versus baseline by Q12 — a moderate GDP response. Equities soften 0.50%, and the three-year CPI impulse is +0.46 percentage points. The move shows up first in private investment / the cost of capital, then in the trade balance, household consumption. The contrast is the point: a neighbour with a floating rate does not print the same curve as a euro-area member that shares a policy rate.

Colombia contracts by 0.08% versus baseline by Q12 — only a small GDP response. Equities soften 0.39%, and the three-year CPI impulse is +0.15 percentage points. The move shows up first in private investment / the cost of capital, then in bond prices (higher discount rates), 5-year bond prices.

A few prices are common across the panel. On the government curve, bond prices (higher discount rates) cheapen 7.68% by Q8, and unused tenors stay in the background rather than getting a sentence each; the NEER prints a trade-weighted appreciation (+1.38% in Q12). Treat those as the shared financial backdrop, not as extra shocks, unless they appear in the active treatment.

Read GDP as percent of baseline GDP: −0.52 is minus half a percent, never −52%. A 200 basis-point move is 2.00 percentage points on the policy rate. CPI over three years is the sum of twelve quarterly impulses, not an annualised rate. A rising real exchange rate is a real depreciation — a weaker, more competitive home currency.

The remaining economies are smaller spillovers, written in the same order in the chapters that follow. Each chapter is a desk note, not a catalog of every series. This material is a model-based summary and is not financial advice.


![US GDP](charts/global_US_Y.png)

![SA GDP](charts/global_SA_Y.png)

![MX GDP](charts/global_MX_Y.png)

![CA GDP](charts/global_CA_Y.png)

![US Equity Index](charts/global_US_equity.png)

![US Policy Rate](charts/global_US_i.png)

## US — United States

The main impact of a 200 basis-point (2.00 percentage-point) rise in United States interest rates on the United States is a large drop in GDP of 0.52% by Q12. This is a model impulse response versus baseline, not a forecast. Equities soften 1.82% by Q11. The three-year CPI impulse is -0.25 percentage points.

Demand and trade. Private investment / the cost of capital falls 2.78% by Q8; household consumption falls 0.33% by Q12; government debt falls 0.10% by Q14; government spending rises 0.10% by Q12; the trade balance stay close to baseline.

Labour. Employment falls 0.54% by Q14; real wages falls 0.54% by Q20; unemployment rises by +0.31 percentage points in Q15.

Prices. Firms' marginal cost falls 0.31% by Q12; CPI inflation, domestic inflation stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 7.68% by Q8; 5-year bond prices cheapen 1.96% by Q2; 10-year bond prices cheapen 1.84% by Q1; 2-year bond prices cheapen 1.48% by Q5; the same direction shows up in 30-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. The NEER prints a trade-weighted appreciation (+1.38% in Q12); versus the dollar the home currency is weaker versus the dollar (+1.38% in Q12); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.78% in Q14.

Equities and risk. Tobin's Q (the value of installed capital) falls 1.95% by Q8; equity prices / financial conditions falls 1.82% by Q11; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices fall 0.53% by Q19; bank equity falls 0.19% by Q18; bank credit supply falls 0.15% by Q18; house prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Services output falls 0.40% by Q12; manufacturing output rises 0.18% by Q20; the capital stock falls 0.15% by Q20.

By Q20, GDP is still -0.21% from baseline.

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

![Bond Price (7y)](charts/US_Q_B.png)

![Gas Price](charts/US_P_gas.png)

[Q1–Q20 JSON for United States](numbers/US.json)

## SA — Saudi Arabia

The main impact of a 200 basis-point (2.00 percentage-point) rise in United States interest rates on Saudi Arabia is a moderate drop in GDP of 0.18% by Q14. This is a model impulse response versus baseline, not a forecast. Equities soften 0.76% by Q13. The three-year CPI impulse is -0.19 percentage points.

Demand and trade. Private investment / the cost of capital falls 2.00% by Q8; government debt falls 0.26% by Q20; the trade balance (net exports — this model does not split imports from exports) softens to -0.17% in Q13; household consumption falls 0.09% by Q8; government spending stay close to baseline.

Labour. Real wages falls 0.21% by Q20; employment falls 0.16% by Q18; unemployment rises by +0.06 percentage points in Q17.

Prices. Firms' marginal cost falls 0.11% by Q14; CPI inflation, domestic inflation stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 5.84% by Q8; 5-year bond prices cheapen 1.96% by Q2; 10-year bond prices cheapen 1.84% by Q1; 2-year bond prices cheapen 1.48% by Q5; the same direction shows up in 30-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. The NEER prints a trade-weighted appreciation (+0.69% in Q11); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.55% in Q14; versus the dollar the home currency is weaker versus the dollar (+0.23% in Q14).

Equities and risk. Tobin's Q (the value of installed capital) falls 1.40% by Q8; equity prices / financial conditions falls 0.76% by Q13; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices fall 0.29% by Q19; house prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output rises 0.14% by Q14; the capital stock falls 0.09% by Q20; services output stay close to baseline.

By Q20, GDP is still -0.12% from baseline.

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

![Bond Price (7y)](charts/SA_Q_B.png)

![Gas Price](charts/SA_P_gas.png)

[Q1–Q20 JSON for Saudi Arabia](numbers/SA.json)

## MX — Mexico

The main impact of a 200 basis-point (2.00 percentage-point) rise in United States interest rates on Mexico is a moderate drop in GDP of 0.17% by Q13. This is a model impulse response versus baseline, not a forecast. Equities soften 0.49% by Q8. The three-year CPI impulse is +0.40 percentage points.

Demand and trade. Private investment / the cost of capital falls 0.62% by Q10; the trade balance (net exports — this model does not split imports from exports) improves to +0.20% in Q10; government debt falls 0.19% by Q20; household consumption falls 0.09% by Q13; government spending stay close to baseline.

Labour. Real wages rises 0.15% by Q12; employment falls 0.13% by Q17; unemployment stay close to baseline.

Prices. Firms' marginal cost falls 0.10% by Q13; CPI inflation rises 0.06 percentage points by Q2; domestic inflation stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 0.69% by Q8; 10-year bond prices rally 0.34% by Q14; 5-year bond prices rally 0.28% by Q15; 2-year bond prices cheapen 0.27% by Q3; the same direction shows up in 30-year bond prices, the local policy rate, 3-month government yields; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+1.82% in Q11); the NEER prints a trade-weighted depreciation (-1.26% in Q11); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +1.11% in Q10.

Equities and risk. Equity prices / financial conditions falls 0.49% by Q8; Tobin's Q (the value of installed capital) falls 0.44% by Q10; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices fall 0.21% by Q18; house prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 0.36% by Q10; services output falls 0.10% by Q13; the capital stock stay close to baseline.

By Q20, GDP is still -0.07% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

![vs USD](charts/MX_USD.png)

[Q1–Q20 JSON for Mexico](numbers/MX.json)

## CA — Canada

The main impact of a 200 basis-point (2.00 percentage-point) rise in United States interest rates on Canada is a moderate drop in GDP of 0.15% by Q12. This is a model impulse response versus baseline, not a forecast. Equities soften 0.50% by Q10. The three-year CPI impulse is +0.46 percentage points.

Demand and trade. Private investment / the cost of capital falls 0.57% by Q10; the trade balance (net exports — this model does not split imports from exports) improves to +0.20% in Q9; household consumption falls 0.09% by Q13; government spending, government debt stay close to baseline.

Labour. Real wages rises 0.19% by Q13; employment falls 0.14% by Q15; unemployment rises by +0.09 percentage points in Q15.

Prices. Firms' marginal cost falls 0.09% by Q12; CPI inflation rises 0.08 percentage points by Q2; domestic inflation rises 0.05 percentage points by Q2.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 0.93% by Q8; 10-year bond prices rally 0.41% by Q14; 5-year bond prices rally 0.35% by Q15; 30-year bond prices rally 0.31% by Q14; the same direction shows up in 2-year bond prices, the local policy rate, 3-month government yields; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+2.14% in Q11); the NEER prints a trade-weighted depreciation (-1.63% in Q11); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +1.43% in Q10.

Equities and risk. Equity prices / financial conditions falls 0.50% by Q10; Tobin's Q (the value of installed capital) falls 0.40% by Q10; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices fall 0.14% by Q18; house prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 0.45% by Q10; services output falls 0.10% by Q12; the capital stock stay close to baseline.

By Q20, GDP is still -0.06% from baseline.

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

![vs USD](charts/CA_USD.png)

[Q1–Q20 JSON for Canada](numbers/CA.json)

## CO — Colombia

The main impact of a 200 basis-point (2.00 percentage-point) rise in United States interest rates on Colombia is only a small drop in GDP of 0.08% by Q12. This is a model impulse response versus baseline, not a forecast. Equities soften 0.39% by Q8. The three-year CPI impulse is +0.15 percentage points.

Demand and trade. Private investment / the cost of capital falls 0.25% by Q9; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 0.21% by Q5; 5-year bond prices rally 0.12% by Q13; 10-year bond prices rally 0.12% by Q12; 2-year bond prices cheapen 0.10% by Q3; the same direction shows up in 30-year bond prices, the local policy rate, 3-month government yields; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+1.54% in Q11); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.83% in Q10; the NEER prints a trade-weighted depreciation (-0.68% in Q11).

Equities and risk. Equity prices / financial conditions falls 0.39% by Q8; Tobin's Q (the value of installed capital) falls 0.18% by Q9; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices fall 0.08% by Q17; house prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 0.26% by Q10; services output, the capital stock stay close to baseline.

By Q20, GDP is still -0.02% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

![vs USD](charts/CO_USD.png)

[Q1–Q20 JSON for Colombia](numbers/CO.json)

## AR — Argentina

The main impact of a 200 basis-point (2.00 percentage-point) rise in United States interest rates on Argentina is only a small drop in GDP of 0.07% by Q10. This is a model impulse response versus baseline, not a forecast. Equities soften 0.58% by Q8.

Demand and trade. Private investment / the cost of capital falls 0.17% by Q8; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 0.14% by Q8; 5-year bond prices cheapen 0.10% by Q19; 2-year bond prices rally 0.08% by Q9; the local policy rate falls 0.06 percentage points by Q12; the same direction shows up in 3-month government yields; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+0.93% in Q11); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.33% in Q8; the NEER prints a trade-weighted appreciation (+0.14% in Q19).

Equities and risk. Equity prices / financial conditions falls 0.58% by Q8; Tobin's Q (the value of installed capital) falls 0.12% by Q8; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 0.11% by Q8; services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q16 (Q20 is still +0.04%).

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

![vs USD](charts/AR_USD.png)

[Q1–Q20 JSON for Argentina](numbers/AR.json)

## BR — Brazil

The main impact of a 200 basis-point (2.00 percentage-point) rise in United States interest rates on Brazil is only a small drop in GDP of 0.07% by Q12. This is a model impulse response versus baseline, not a forecast. Equities soften 0.45% by Q8. The three-year CPI impulse is +0.08 percentage points.

Demand and trade. Private investment / the cost of capital falls 0.22% by Q9; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 0.24% by Q8; 5-year bond prices rally 0.11% by Q11; 10-year bond prices rally 0.09% by Q11; 2-year bond prices rally 0.08% by Q14; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+1.42% in Q12); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.70% in Q10; the NEER prints a trade-weighted depreciation (-0.58% in Q11).

Equities and risk. Equity prices / financial conditions falls 0.45% by Q8; Tobin's Q (the value of installed capital) falls 0.15% by Q9; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 0.22% by Q10; services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q20 (Q20 is still -0.01%).

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

![vs USD](charts/BR_USD.png)

[Q1–Q20 JSON for Brazil](numbers/BR.json)

## UK — United Kingdom

The main impact of a 200 basis-point (2.00 percentage-point) rise in United States interest rates on United Kingdom is only a small drop in GDP of 0.07% by Q11. This is a model impulse response versus baseline, not a forecast. Equities soften 0.35% by Q8. The three-year CPI impulse is +0.08 percentage points.

Demand and trade. Private investment / the cost of capital falls 0.20% by Q10; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 0.69% by Q8; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+1.20% in Q11); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.53% in Q9; the NEER prints a trade-weighted depreciation (-0.28% in Q9).

Equities and risk. Equity prices / financial conditions falls 0.35% by Q8; Tobin's Q (the value of installed capital) falls 0.14% by Q10; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 0.16% by Q9; services output, the capital stock stay close to baseline.

By Q20, GDP is still -0.02% from baseline.

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

![VIX](charts/UK_vix.png)

![Gas Price](charts/UK_P_gas.png)

![vs USD](charts/UK_USD.png)

[Q1–Q20 JSON for United Kingdom](numbers/UK.json)

## NO — Norway

The main impact of a 200 basis-point (2.00 percentage-point) rise in United States interest rates on Norway is only a small drop in GDP of 0.07% by Q12. This is a model impulse response versus baseline, not a forecast. Equities soften 0.33% by Q8. The three-year CPI impulse is +0.08 percentage points.

Demand and trade. Private investment / the cost of capital falls 0.18% by Q11; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 0.51% by Q8; 10-year bond prices rally 0.11% by Q12; 5-year bond prices rally 0.10% by Q13; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+1.21% in Q13); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.46% in Q11; the NEER prints a trade-weighted depreciation (-0.14% in Q13).

Equities and risk. Equity prices / financial conditions falls 0.33% by Q8; Tobin's Q (the value of installed capital) falls 0.13% by Q11; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 0.14% by Q11; services output, the capital stock stay close to baseline.

By Q20, GDP is still -0.03% from baseline.

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

![vs USD](charts/NO_USD.png)

[Q1–Q20 JSON for Norway](numbers/NO.json)

## CL — Chile

The main impact of a 200 basis-point (2.00 percentage-point) rise in United States interest rates on Chile is only a small drop in GDP of 0.06% by Q12. This is a model impulse response versus baseline, not a forecast. Equities soften 0.40% by Q8. The three-year CPI impulse is +0.15 percentage points.

Demand and trade. Private investment / the cost of capital falls 0.23% by Q9; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 0.24% by Q8; 10-year bond prices rally 0.12% by Q13; 5-year bond prices rally 0.10% by Q14; 2-year bond prices cheapen 0.10% by Q3; the same direction shows up in 30-year bond prices, the local policy rate, 3-month government yields; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+1.25% in Q12); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.54% in Q9; the NEER prints a trade-weighted depreciation (-0.37% in Q11).

Equities and risk. Equity prices / financial conditions falls 0.40% by Q8; Tobin's Q (the value of installed capital) falls 0.16% by Q9; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 0.17% by Q9; services output, the capital stock stay close to baseline.

By Q20, GDP is still -0.02% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a 200 basis-point (2.00 percentage-point) rise in United States interest rates on Netherlands is only a small drop in GDP of 0.06% by Q12. This is a model impulse response versus baseline, not a forecast. Equities soften 0.33% by Q8. The three-year CPI impulse is +0.32 percentage points.

Demand and trade. Private investment / the cost of capital falls 0.23% by Q11; the trade balance (net exports — this model does not split imports from exports) improves to +0.16% in Q15; household consumption, government spending, government debt stay close to baseline.

Labour. Real wages rises 0.14% by Q18; employment, unemployment stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 0.58% by Q8; 5-year bond prices cheapen 0.12% by Q3; 10-year bond prices cheapen 0.12% by Q1; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+1.38% in Q14); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.60% in Q15; the NEER prints a trade-weighted depreciation (-0.43% in Q18).

Equities and risk. Equity prices / financial conditions falls 0.33% by Q8; Tobin's Q (the value of installed capital) falls 0.16% by Q11; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 0.18% by Q14; services output, the capital stock stay close to baseline.

By Q20, GDP is still -0.03% from baseline.

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

![vs USD](charts/NL_USD.png)

[Q1–Q20 JSON for Netherlands](numbers/NL.json)

## MY — Malaysia

The main impact of a 200 basis-point (2.00 percentage-point) rise in United States interest rates on Malaysia is only a small drop in GDP of 0.06% by Q12. This is a model impulse response versus baseline, not a forecast. Equities soften 0.35% by Q8. The three-year CPI impulse is +0.13 percentage points.

Demand and trade. Private investment / the cost of capital falls 0.18% by Q9; the trade balance (net exports — this model does not split imports from exports) improves to +0.11% in Q8; household consumption, government spending, government debt stay close to baseline.

Labour. Real wages rises 0.08% by Q10; employment, unemployment stay close to baseline.

Prices. CPI inflation rises 0.06 percentage points by Q1; domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 0.22% by Q8; 5-year bond prices rally 0.10% by Q12; 10-year bond prices rally 0.10% by Q11; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+1.00% in Q12); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.39% in Q8; the NEER prints a trade-weighted depreciation (-0.15% in Q8).

Equities and risk. Equity prices / financial conditions falls 0.35% by Q8; Tobin's Q (the value of installed capital) falls 0.13% by Q9; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 0.12% by Q8; services output, the capital stock stay close to baseline.

By Q20, GDP is still -0.02% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

![vs USD](charts/MY_USD.png)

[Q1–Q20 JSON for Malaysia](numbers/MY.json)

## CH — Switzerland

The main impact of a 200 basis-point (2.00 percentage-point) rise in United States interest rates on Switzerland is only a small drop in GDP of 0.06% by Q11. This is a model impulse response versus baseline, not a forecast. Equities soften 0.34% by Q8. The three-year CPI impulse is +0.14 percentage points.

Demand and trade. Private investment / the cost of capital falls 0.18% by Q10; the trade balance (net exports — this model does not split imports from exports) improves to +0.08% in Q9; household consumption, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 0.56% by Q8; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+1.06% in Q12); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.37% in Q9; the NEER prints a trade-weighted appreciation (+0.11% in Q20).

Equities and risk. Equity prices / financial conditions falls 0.34% by Q8; Tobin's Q (the value of installed capital) falls 0.13% by Q10; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 0.11% by Q9; services output, the capital stock stay close to baseline.

By Q20, GDP is still -0.02% from baseline.

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

![vs USD](charts/CH_USD.png)

[Q1–Q20 JSON for Switzerland](numbers/CH.json)

## TR — Turkey

The main impact of a 200 basis-point (2.00 percentage-point) rise in United States interest rates on Turkey is only a small drop in GDP of 0.05% by Q10. This is a model impulse response versus baseline, not a forecast. Equities soften 0.49% by Q8.

Demand and trade. Private investment / the cost of capital falls 0.14% by Q8; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 0.14% by Q8; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+0.91% in Q12); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.26% in Q8; the NEER prints a trade-weighted appreciation (+0.16% in Q20).

Equities and risk. Equity prices / financial conditions falls 0.49% by Q8; Tobin's Q (the value of installed capital) falls 0.10% by Q8; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 0.08% by Q8; services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q17 (Q20 is still +0.01%).

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

![vs USD](charts/TR_USD.png)

[Q1–Q20 JSON for Turkey](numbers/TR.json)

## KR — South Korea

The main impact of a 200 basis-point (2.00 percentage-point) rise in United States interest rates on South Korea is only a small drop in GDP of 0.05% by Q12. This is a model impulse response versus baseline, not a forecast. Equities soften 0.38% by Q8. The three-year CPI impulse is +0.20 percentage points.

Demand and trade. Private investment / the cost of capital falls 0.21% by Q9; the trade balance (net exports — this model does not split imports from exports) improves to +0.13% in Q10; household consumption, government spending, government debt stay close to baseline.

Labour. Real wages rises 0.09% by Q13; employment, unemployment stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 0.30% by Q8; 10-year bond prices rally 0.12% by Q14; 5-year bond prices rally 0.11% by Q14; 2-year bond prices cheapen 0.10% by Q3; the same direction shows up in 30-year bond prices, the local policy rate, 3-month government yields; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+1.20% in Q11); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.52% in Q9; the NEER prints a trade-weighted depreciation (-0.35% in Q11).

Equities and risk. Equity prices / financial conditions falls 0.38% by Q8; Tobin's Q (the value of installed capital) falls 0.14% by Q9; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 0.16% by Q9; services output, the capital stock stay close to baseline.

By Q20, GDP is still -0.02% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

## RU — Russia

The main impact of a 200 basis-point (2.00 percentage-point) rise in United States interest rates on Russia is only a small drop in GDP of 0.05% by Q11. This is a model impulse response versus baseline, not a forecast. Equities soften 0.48% by Q8.

Demand and trade. Private investment / the cost of capital falls 0.11% by Q10; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 0.14% by Q8; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+0.87% in Q13); the NEER prints a trade-weighted appreciation (+0.24% in Q8); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.11% in Q11.

Equities and risk. Equity prices / financial conditions falls 0.48% by Q8; the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output, services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q19 (Q20 is still -0.00%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

![vs USD](charts/RU_USD.png)

[Q1–Q20 JSON for Russia](numbers/RU.json)

## NG — Nigeria

The main impact of a 200 basis-point (2.00 percentage-point) rise in United States interest rates on Nigeria is only a small drop in GDP of 0.05% by Q11. This is a model impulse response versus baseline, not a forecast. Equities soften 0.42% by Q8.

Demand and trade. Private investment / the cost of capital falls 0.11% by Q8; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 0.13% by Q14; 2-year bond prices rally 0.08% by Q11; the local policy rate falls 0.05 percentage points by Q14; 3-month government yields fall 0.05 percentage points by Q14; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+0.97% in Q11); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.35% in Q8; the NEER prints a trade-weighted depreciation (-0.09% in Q8).

Equities and risk. Equity prices / financial conditions falls 0.42% by Q8; the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 0.11% by Q8; services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q17 (Q20 is still +0.02%).

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

![vs USD](charts/NG_USD.png)

[Q1–Q20 JSON for Nigeria](numbers/NG.json)

## ZA — South Africa

The main impact of a 200 basis-point (2.00 percentage-point) rise in United States interest rates on South Africa is only a small drop in GDP of 0.04% by Q12. This is a model impulse response versus baseline, not a forecast. Equities soften 0.42% by Q8. The three-year CPI impulse is +0.09 percentage points.

Demand and trade. Private investment / the cost of capital falls 0.15% by Q9; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 0.23% by Q8; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+1.10% in Q12); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.38% in Q9; the NEER prints a trade-weighted depreciation (-0.15% in Q12).

Equities and risk. Equity prices / financial conditions falls 0.42% by Q8; Tobin's Q (the value of installed capital) falls 0.10% by Q9; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 0.11% by Q9; services output, the capital stock stay close to baseline.

By Q20, GDP is still -0.01% from baseline.

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

![vs USD](charts/ZA_USD.png)

[Q1–Q20 JSON for South Africa](numbers/ZA.json)

## JP — Japan

The main impact of a 200 basis-point (2.00 percentage-point) rise in United States interest rates on Japan is only a small drop in GDP of 0.04% by Q11. This is a model impulse response versus baseline, not a forecast. Equities soften 0.23% by Q8. The three-year CPI impulse is +0.09 percentage points.

Demand and trade. Private investment / the cost of capital falls 0.13% by Q10; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 0.90% by Q8; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+1.21% in Q10); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.58% in Q8; the NEER prints a trade-weighted depreciation (-0.38% in Q9).

Equities and risk. Equity prices / financial conditions falls 0.23% by Q8; Tobin's Q (the value of installed capital) falls 0.09% by Q10; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 0.18% by Q8; services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q20 (Q20 is still -0.01%).

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

## DE — Germany

The main impact of a 200 basis-point (2.00 percentage-point) rise in United States interest rates on Germany is only a small drop in GDP of 0.04% by Q11. This is a model impulse response versus baseline, not a forecast. Equities soften 0.24% by Q8. The three-year CPI impulse is +0.22 percentage points.

Demand and trade. Private investment / the cost of capital falls 0.18% by Q10; the trade balance (net exports — this model does not split imports from exports) improves to +0.13% in Q13; household consumption, government spending, government debt stay close to baseline.

Labour. Real wages rises 0.10% by Q18; employment, unemployment stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 0.62% by Q8; 5-year bond prices cheapen 0.12% by Q3; 10-year bond prices cheapen 0.12% by Q1; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+1.34% in Q15); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.56% in Q15; the NEER prints a trade-weighted depreciation (-0.35% in Q20).

Equities and risk. Equity prices / financial conditions falls 0.24% by Q8; Tobin's Q (the value of installed capital) falls 0.13% by Q10; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 0.17% by Q15; services output, the capital stock stay close to baseline.

By Q20, GDP is still -0.02% from baseline.

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

![vs USD](charts/DE_USD.png)

[Q1–Q20 JSON for Germany](numbers/DE.json)

## TH — Thailand

The main impact of a 200 basis-point (2.00 percentage-point) rise in United States interest rates on Thailand is only a small drop in GDP of 0.04% by Q11. This is a model impulse response versus baseline, not a forecast. Equities soften 0.31% by Q8. The three-year CPI impulse is +0.08 percentage points.

Demand and trade. Private investment / the cost of capital falls 0.13% by Q8; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 0.22% by Q8; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+0.91% in Q12); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.29% in Q8; the nominal effective exchange rate (increase = trade-weighted appreciation) stay close to baseline.

Equities and risk. Equity prices / financial conditions falls 0.31% by Q8; Tobin's Q (the value of installed capital) falls 0.09% by Q8; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 0.09% by Q8; services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q20 (Q20 is still -0.01%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

![vs USD](charts/TH_USD.png)

[Q1–Q20 JSON for Thailand](numbers/TH.json)

## FR — France

The main impact of a 200 basis-point (2.00 percentage-point) rise in United States interest rates on France is only a small drop in GDP of 0.04% by Q11. This is a model impulse response versus baseline, not a forecast. Equities soften 0.28% by Q8. The three-year CPI impulse is +0.18 percentage points.

Demand and trade. Private investment / the cost of capital falls 0.17% by Q11; the trade balance (net exports — this model does not split imports from exports) improves to +0.10% in Q14; household consumption, government spending, government debt stay close to baseline.

Labour. Real wages rises 0.09% by Q20; employment, unemployment stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 0.72% by Q8; 5-year bond prices cheapen 0.12% by Q3; 10-year bond prices cheapen 0.12% by Q1; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+1.34% in Q14); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.57% in Q15; the NEER prints a trade-weighted depreciation (-0.27% in Q20).

Equities and risk. Equity prices / financial conditions falls 0.28% by Q8; Tobin's Q (the value of installed capital) falls 0.12% by Q11; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 0.17% by Q15; services output, the capital stock stay close to baseline.

By Q20, GDP is still -0.02% from baseline.

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

![vs USD](charts/FR_USD.png)

[Q1–Q20 JSON for France](numbers/FR.json)

## IN — India

The main impact of a 200 basis-point (2.00 percentage-point) rise in United States interest rates on India is only a small drop in GDP of 0.04% by Q10. This is a model impulse response versus baseline, not a forecast. Equities soften 0.38% by Q8.

Demand and trade. Private investment / the cost of capital falls 0.11% by Q8; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 0.28% by Q8; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+0.94% in Q11); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.36% in Q8; the NEER prints a trade-weighted depreciation (-0.12% in Q8).

Equities and risk. Equity prices / financial conditions falls 0.38% by Q8; the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 0.11% by Q8; services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q17 (Q20 is still +0.01%).

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

![vs USD](charts/IN_USD.png)

[Q1–Q20 JSON for India](numbers/IN.json)

## ID — Indonesia

The main impact of a 200 basis-point (2.00 percentage-point) rise in United States interest rates on Indonesia is only a small drop in GDP of 0.03% by Q11. This is a model impulse response versus baseline, not a forecast. Equities soften 0.29% by Q8.

Demand and trade. Private investment / the cost of capital falls 0.09% by Q8; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 0.20% by Q8; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+0.91% in Q12); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.28% in Q8; the nominal effective exchange rate (increase = trade-weighted appreciation) stay close to baseline.

Equities and risk. Equity prices / financial conditions falls 0.29% by Q8; the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 0.09% by Q8; services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q18 (Q20 is still +0.00%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

![vs USD](charts/ID_USD.png)

[Q1–Q20 JSON for Indonesia](numbers/ID.json)

## AU — Australia

The main impact of a 200 basis-point (2.00 percentage-point) rise in United States interest rates on Australia is only a small drop in GDP of 0.03% by Q11. This is a model impulse response versus baseline, not a forecast. Equities soften 0.29% by Q8. The three-year CPI impulse is +0.08 percentage points.

Demand and trade. Private investment / the cost of capital falls 0.11% by Q9; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 0.31% by Q8; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+1.18% in Q12); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.46% in Q10; the NEER prints a trade-weighted depreciation (-0.24% in Q12).

Equities and risk. Equity prices / financial conditions falls 0.29% by Q8; the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 0.14% by Q10; services output, the capital stock stay close to baseline.

By Q20, GDP is still -0.01% from baseline.

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

![vs USD](charts/AU_USD.png)

[Q1–Q20 JSON for Australia](numbers/AU.json)

## ES — Spain

The main impact of a 200 basis-point (2.00 percentage-point) rise in United States interest rates on Spain is only a small drop in GDP of 0.03% by Q11. This is a model impulse response versus baseline, not a forecast. Equities soften 0.28% by Q8. The three-year CPI impulse is +0.18 percentage points.

Demand and trade. Private investment / the cost of capital falls 0.15% by Q11; the trade balance (net exports — this model does not split imports from exports) improves to +0.11% in Q14; household consumption, government spending, government debt stay close to baseline.

Labour. Real wages rises 0.09% by Q20; employment, unemployment stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 0.70% by Q8; 5-year bond prices cheapen 0.12% by Q3; 10-year bond prices cheapen 0.12% by Q1; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+1.34% in Q15); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.57% in Q16; the NEER prints a trade-weighted depreciation (-0.32% in Q20).

Equities and risk. Equity prices / financial conditions falls 0.28% by Q8; Tobin's Q (the value of installed capital) falls 0.10% by Q11; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 0.17% by Q16; services output, the capital stock stay close to baseline.

By Q20, GDP is still -0.02% from baseline.

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

![vs USD](charts/ES_USD.png)

[Q1–Q20 JSON for Spain](numbers/ES.json)

## PL — Poland

The main impact of a 200 basis-point (2.00 percentage-point) rise in United States interest rates on Poland is only a small drop in GDP of 0.03% by Q11. This is a model impulse response versus baseline, not a forecast. Equities soften 0.34% by Q8. The three-year CPI impulse is +0.08 percentage points.

Demand and trade. Private investment / the cost of capital falls 0.11% by Q9; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 0.35% by Q8; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+0.95% in Q13); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.21% in Q9; the NEER prints a trade-weighted appreciation (+0.18% in Q20).

Equities and risk. Equity prices / financial conditions falls 0.34% by Q8; the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output, services output, the capital stock stay close to baseline.

By Q20, GDP is still -0.01% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

![vs USD](charts/PL_USD.png)

[Q1–Q20 JSON for Poland](numbers/PL.json)

## CN — China

The main impact of a 200 basis-point (2.00 percentage-point) rise in United States interest rates on China is only a small drop in GDP of 0.03% by Q11. This is a model impulse response versus baseline, not a forecast. Equities soften 0.23% by Q8.

Demand and trade. Household consumption, private investment / the cost of capital, the trade balance, government spending stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 0.28% by Q8; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+0.89% in Q11); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.29% in Q8; the NEER prints a trade-weighted appreciation (+0.14% in Q13).

Equities and risk. Equity prices / financial conditions falls 0.23% by Q8; the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 0.09% by Q8; services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q19 (Q20 is still -0.00%).

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

![vs USD](charts/CN_USD.png)

[Q1–Q20 JSON for China](numbers/CN.json)

## SE — Sweden

The main impact of a 200 basis-point (2.00 percentage-point) rise in United States interest rates on Sweden is only a small drop in GDP of 0.02% by Q11. This is a model impulse response versus baseline, not a forecast. Equities soften 0.29% by Q8. The three-year CPI impulse is +0.07 percentage points.

Demand and trade. Private investment / the cost of capital falls 0.09% by Q9; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 0.49% by Q8; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+0.96% in Q13); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.22% in Q9; the NEER prints a trade-weighted appreciation (+0.19% in Q20).

Equities and risk. Equity prices / financial conditions falls 0.29% by Q8; the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output, services output, the capital stock stay close to baseline.

By Q20, GDP is still -0.01% from baseline.

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

![vs USD](charts/SE_USD.png)

[Q1–Q20 JSON for Sweden](numbers/SE.json)

## IT — Italy

The main impact of a 200 basis-point (2.00 percentage-point) rise in United States interest rates on Italy is only a small drop in GDP of 0.02% by Q11. This is a model impulse response versus baseline, not a forecast. Equities soften 0.27% by Q8. The three-year CPI impulse is +0.15 percentage points.

Demand and trade. Private investment / the cost of capital falls 0.12% by Q10; the trade balance (net exports — this model does not split imports from exports) improves to +0.10% in Q14; household consumption, government spending, government debt stay close to baseline.

Labour. Real wages rises 0.09% by Q20; employment, unemployment stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 0.76% by Q8; 5-year bond prices cheapen 0.12% by Q3; 10-year bond prices cheapen 0.12% by Q1; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+1.33% in Q15); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.56% in Q16; the NEER prints a trade-weighted depreciation (-0.28% in Q20).

Equities and risk. Equity prices / financial conditions falls 0.27% by Q8; Tobin's Q (the value of installed capital) falls 0.09% by Q10; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 0.16% by Q17; services output, the capital stock stay close to baseline.

By Q20, GDP is still -0.01% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

![vs USD](charts/IT_USD.png)

[Q1–Q20 JSON for Italy](numbers/IT.json)


---

These figures are model IRFs versus baseline, not forecasts, and not financial advice.
