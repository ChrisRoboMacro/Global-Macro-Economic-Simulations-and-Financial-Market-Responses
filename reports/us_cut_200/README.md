# Global Macro Economic Simulations and Financial Market Responses

v6 · IRF · evaluation

**Open the typeset report (this is the document):** https://robomacro.com/GlobalMacroTrainingDataset/us_cut_200/

GitHub and Hugging Face show `.html` as source code. That is not the report. Read it on robomacro.com, or keep scrolling this page.

## What's the impact of US policy rate -200bp

a 200 basis-point (2.00 percentage-point) cut in United States interest rates. Every path is a model impulse response versus baseline, not a forecast and not financial advice.

### Summary

This note traces the model response to a 200 basis-point (2.00 percentage-point) cut in United States interest rates. Every path is an impulse response versus an unchanged baseline — not a forecast of what will happen in the world and not a reading of market data. The chapters that follow are already sorted by the size of the GDP response.

The United States is where the shock lands. GDP expands by 0.47% by Q11, a first-order GDP response for a 200 basis-point (2.00 percentage-point) cut in United States interest rates. Equities firm 1.61%, and the three-year CPI impulse is +0.23 percentage points. The move shows up first in private investment / the cost of capital, then in household consumption, government debt. That is the main adjustment: a change in financial conditions and real income, then the usual lag into activity and prices. It is the conditional elasticity to the shock that was switched on, not a prediction that this path will be realised.

Spillovers are not a carbon copy of that first path. Saudi Arabia expands by 0.13% versus baseline by Q13 — a moderate GDP response. Equities firm 0.55%, and the three-year CPI impulse is +0.15 percentage points. The move shows up first in private investment / the cost of capital, then in government debt, the trade balance. Mexico expands by 0.13% versus baseline by Q12 — a moderate GDP response. Equities firm 0.42%, and the three-year CPI impulse is -0.25 percentage points. The move shows up first in private investment / the cost of capital, then in the trade balance, government debt. Canada expands by 0.10% versus baseline by Q12 — a moderate GDP response. Equities firm 0.39%, and the three-year CPI impulse is -0.29 percentage points. The move shows up first in private investment / the cost of capital, then in the trade balance, real wages. The contrast is the point: a neighbour with a floating rate does not print the same curve as a euro-area member that shares a policy rate.

Colombia expands by 0.06% versus baseline by Q11 — only a small GDP response. Equities firm 0.33%, and the three-year CPI impulse is -0.09 percentage points. The move shows up first in private investment / the cost of capital, then in bond prices (higher discount rates), 2-year bond prices.

A few prices are common across the panel. On the government curve, bond prices (higher discount rates) rally 6.75% by Q8, and unused tenors stay in the background rather than getting a sentence each; the NEER prints a trade-weighted depreciation (-1.05% in Q10). Treat those as the shared financial backdrop, not as extra shocks, unless they appear in the active treatment.

Read GDP as percent of baseline GDP: −0.52 is minus half a percent, never −52%. A 200 basis-point move is 2.00 percentage points on the policy rate. CPI over three years is the sum of twelve quarterly impulses, not an annualised rate. A rising real exchange rate is a real depreciation — a weaker, more competitive home currency.

The remaining economies are smaller spillovers, written in the same order in the chapters that follow. Each chapter is a desk note, not a catalog of every series. This material is a model-based summary and is not financial advice.


![US GDP](charts/global_US_Y.png)

![SA GDP](charts/global_SA_Y.png)

![MX GDP](charts/global_MX_Y.png)

![CA GDP](charts/global_CA_Y.png)

![US Equity Index](charts/global_US_equity.png)

![US Policy Rate](charts/global_US_i.png)

## US — United States

The main impact of a 200 basis-point (2.00 percentage-point) cut in United States interest rates on the United States is a large rise in GDP of 0.47% by Q11. This is a model impulse response versus baseline, not a forecast. Equities firm 1.61% by Q11. The three-year CPI impulse is +0.23 percentage points.

Demand and trade. Private investment / the cost of capital rises 2.53% by Q8; household consumption rises 0.29% by Q12; government debt rises 0.09% by Q13; government spending falls 0.09% by Q11; the trade balance stay close to baseline.

Labour. Employment rises 0.48% by Q13; real wages rises 0.46% by Q20; unemployment eases by -0.24 percentage points in Q14.

Prices. Firms' marginal cost rises 0.28% by Q11; CPI inflation, domestic inflation stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 6.75% by Q8; 10-year bond prices rally 1.29% by Q2; 2-year bond prices rally 1.21% by Q4; 5-year bond prices rally 1.14% by Q1; the same direction shows up in the local policy rate, 3-month government yields, 30-year bond prices.

Exchange rates. The NEER prints a trade-weighted depreciation (-1.05% in Q10); versus the dollar the home currency is stronger versus the dollar (-1.05% in Q10); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.61% in Q11.

Equities and risk. Tobin's Q (the value of installed capital) rises 1.77% by Q8; equity prices / financial conditions rises 1.61% by Q11; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices rise 0.41% by Q16; house prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Services output rises 0.36% by Q11; manufacturing output falls 0.10% by Q11; the capital stock rises 0.10% by Q18.

The GDP response has mostly faded by Q19 (Q20 is still +0.03%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/US_Y.png)

![CPI Inflation](charts/US_pi_cpi.png)

![Equity Index](charts/US_equity.png)

![Gold Price](charts/US_P_gold.png)

![Food Price](charts/US_P_food.png)

![Metals Price](charts/US_P_metals.png)

![Copper Price](charts/US_P_copper.png)

![Wheat Price](charts/US_P_wheat.png)

![Energy Price](charts/US_P_energy.png)

![VIX](charts/US_vix.png)

![Bond Price (7y)](charts/US_Q_B.png)

![Gas Price](charts/US_P_gas.png)

[Q1–Q20 JSON for United States](numbers/US.json)

## SA — Saudi Arabia

The main impact of a 200 basis-point (2.00 percentage-point) cut in United States interest rates on Saudi Arabia is a moderate rise in GDP of 0.13% by Q13. This is a model impulse response versus baseline, not a forecast. Equities firm 0.55% by Q12. The three-year CPI impulse is +0.15 percentage points.

Demand and trade. Private investment / the cost of capital rises 1.74% by Q8; government debt rises 0.18% by Q20; the trade balance (net exports — this model does not split imports from exports) improves to +0.14% in Q12; household consumption, government spending stay close to baseline.

Labour. Real wages rises 0.15% by Q20; employment rises 0.12% by Q16; unemployment stay close to baseline.

Prices. Firms' marginal cost rises 0.08% by Q13; CPI inflation, domestic inflation stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 5.13% by Q8; 10-year bond prices rally 1.29% by Q2; 2-year bond prices rally 1.21% by Q4; 5-year bond prices rally 1.14% by Q1; the same direction shows up in the local policy rate, 3-month government yields, 30-year bond prices.

Exchange rates. The NEER prints a trade-weighted depreciation (-0.51% in Q9); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.43% in Q11; versus the dollar the home currency is stronger versus the dollar (-0.19% in Q11).

Equities and risk. Tobin's Q (the value of installed capital) rises 1.22% by Q8; equity prices / financial conditions rises 0.55% by Q12; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices rise 0.19% by Q16; house prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 0.11% by Q11; services output, the capital stock stay close to baseline.

By Q20, GDP is still +0.05% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/SA_Y.png)

![CPI Inflation](charts/SA_pi_cpi.png)

![Equity Index](charts/SA_equity.png)

![Gold Price](charts/SA_P_gold.png)

![Food Price](charts/SA_P_food.png)

![Metals Price](charts/SA_P_metals.png)

![Copper Price](charts/SA_P_copper.png)

![Wheat Price](charts/SA_P_wheat.png)

![Energy Price](charts/SA_P_energy.png)

![VIX](charts/SA_vix.png)

![Bond Price (7y)](charts/SA_Q_B.png)

![Gas Price](charts/SA_P_gas.png)

[Q1–Q20 JSON for Saudi Arabia](numbers/SA.json)

## MX — Mexico

The main impact of a 200 basis-point (2.00 percentage-point) cut in United States interest rates on Mexico is a moderate rise in GDP of 0.13% by Q12. This is a model impulse response versus baseline, not a forecast. Equities firm 0.42% by Q8. The three-year CPI impulse is -0.25 percentage points.

Demand and trade. Private investment / the cost of capital rises 0.46% by Q9; the trade balance (net exports — this model does not split imports from exports) softens to -0.15% in Q9; government debt rises 0.13% by Q18; household consumption, government spending stay close to baseline.

Labour. Real wages falls 0.11% by Q11; employment rises 0.09% by Q15; unemployment stay close to baseline.

Prices. CPI inflation falls 0.06 percentage points by Q2; domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 0.50% by Q4; 2-year bond prices rally 0.21% by Q2; 5-year bond prices cheapen 0.19% by Q12; 10-year bond prices cheapen 0.19% by Q12; the same direction shows up in 30-year bond prices, the local policy rate, 3-month government yields; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-1.38% in Q10); the NEER prints a trade-weighted appreciation (+0.95% in Q10); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.83% in Q9.

Equities and risk. Equity prices / financial conditions rises 0.42% by Q8; Tobin's Q (the value of installed capital) rises 0.32% by Q9; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices rise 0.14% by Q16; house prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output rises 0.27% by Q9; services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q19 (Q20 is still +0.01%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/MX_Y.png)

![CPI Inflation](charts/MX_pi_cpi.png)

![Equity Index](charts/MX_equity.png)

![Gold Price](charts/MX_P_gold.png)

![Food Price](charts/MX_P_food.png)

![Metals Price](charts/MX_P_metals.png)

![Copper Price](charts/MX_P_copper.png)

![Wheat Price](charts/MX_P_wheat.png)

![Energy Price](charts/MX_P_energy.png)

![VIX](charts/MX_vix.png)

![Gas Price](charts/MX_P_gas.png)

![vs USD](charts/MX_USD.png)

[Q1–Q20 JSON for Mexico](numbers/MX.json)

## CA — Canada

The main impact of a 200 basis-point (2.00 percentage-point) cut in United States interest rates on Canada is a moderate rise in GDP of 0.10% by Q12. This is a model impulse response versus baseline, not a forecast. Equities firm 0.39% by Q8. The three-year CPI impulse is -0.29 percentage points.

Demand and trade. Private investment / the cost of capital rises 0.40% by Q9; the trade balance (net exports — this model does not split imports from exports) softens to -0.15% in Q8; household consumption, government spending, government debt stay close to baseline.

Labour. Real wages falls 0.14% by Q12; employment rises 0.10% by Q14; unemployment eases by -0.05 percentage points in Q14.

Prices. CPI inflation falls 0.07 percentage points by Q2; domestic inflation falls 0.05 percentage points by Q2; firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 0.70% by Q5; 5-year bond prices cheapen 0.22% by Q12; 2-year bond prices rally 0.20% by Q2; 10-year bond prices cheapen 0.19% by Q12; the same direction shows up in 30-year bond prices, the local policy rate, 3-month government yields; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-1.61% in Q9); the NEER prints a trade-weighted appreciation (+1.23% in Q9); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -1.06% in Q9.

Equities and risk. Equity prices / financial conditions rises 0.39% by Q8; Tobin's Q (the value of installed capital) rises 0.28% by Q9; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices rise 0.09% by Q16; house prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output rises 0.33% by Q9; services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q19 (Q20 is still +0.01%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/CA_Y.png)

![CPI Inflation](charts/CA_pi_cpi.png)

![Equity Index](charts/CA_equity.png)

![Gold Price](charts/CA_P_gold.png)

![Food Price](charts/CA_P_food.png)

![Metals Price](charts/CA_P_metals.png)

![Copper Price](charts/CA_P_copper.png)

![Wheat Price](charts/CA_P_wheat.png)

![Energy Price](charts/CA_P_energy.png)

![VIX](charts/CA_vix.png)

![Gas Price](charts/CA_P_gas.png)

![vs USD](charts/CA_USD.png)

[Q1–Q20 JSON for Canada](numbers/CA.json)

## CO — Colombia

The main impact of a 200 basis-point (2.00 percentage-point) cut in United States interest rates on Colombia is only a small rise in GDP of 0.06% by Q11. This is a model impulse response versus baseline, not a forecast. Equities firm 0.33% by Q8. The three-year CPI impulse is -0.09 percentage points.

Demand and trade. Private investment / the cost of capital rises 0.19% by Q9; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 0.18% by Q16; 2-year bond prices cheapen 0.08% by Q13; the local policy rate rises 0.05 percentage points by Q16; 3-month government yields rise 0.05 percentage points by Q16; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-1.17% in Q10); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.60% in Q9; the NEER prints a trade-weighted appreciation (+0.52% in Q10).

Equities and risk. Equity prices / financial conditions rises 0.33% by Q8; Tobin's Q (the value of installed capital) rises 0.13% by Q9; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output rises 0.19% by Q9; services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q18 (Q20 is still -0.00%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/CO_Y.png)

![CPI Inflation](charts/CO_pi_cpi.png)

![Equity Index](charts/CO_equity.png)

![Gold Price](charts/CO_P_gold.png)

![Food Price](charts/CO_P_food.png)

![Metals Price](charts/CO_P_metals.png)

![Copper Price](charts/CO_P_copper.png)

![Wheat Price](charts/CO_P_wheat.png)

![Energy Price](charts/CO_P_energy.png)

![VIX](charts/CO_vix.png)

![Gas Price](charts/CO_P_gas.png)

![vs USD](charts/CO_USD.png)

[Q1–Q20 JSON for Colombia](numbers/CO.json)

## AR — Argentina

The main impact of a 200 basis-point (2.00 percentage-point) cut in United States interest rates on Argentina is only a small rise in GDP of 0.05% by Q9. This is a model impulse response versus baseline, not a forecast. Equities firm 0.49% by Q8.

Demand and trade. Private investment / the cost of capital rises 0.13% by Q8; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 0.12% by Q8; 5-year bond prices rally 0.08% by Q17; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-0.72% in Q9); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.22% in Q8; the NEER prints a trade-weighted depreciation (-0.09% in Q17).

Equities and risk. Equity prices / financial conditions rises 0.49% by Q8; Tobin's Q (the value of installed capital) rises 0.09% by Q8; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output, services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q15 (Q20 is still -0.05%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/AR_Y.png)

![CPI Inflation](charts/AR_pi_cpi.png)

![Equity Index](charts/AR_equity.png)

![Gold Price](charts/AR_P_gold.png)

![Food Price](charts/AR_P_food.png)

![Metals Price](charts/AR_P_metals.png)

![Copper Price](charts/AR_P_copper.png)

![Wheat Price](charts/AR_P_wheat.png)

![Energy Price](charts/AR_P_energy.png)

![VIX](charts/AR_vix.png)

![Gas Price](charts/AR_P_gas.png)

![vs USD](charts/AR_USD.png)

[Q1–Q20 JSON for Argentina](numbers/AR.json)

## BR — Brazil

The main impact of a 200 basis-point (2.00 percentage-point) cut in United States interest rates on Brazil is only a small rise in GDP of 0.05% by Q11. This is a model impulse response versus baseline, not a forecast. Equities firm 0.38% by Q8.

Demand and trade. Private investment / the cost of capital rises 0.15% by Q9; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 0.21% by Q15; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-1.07% in Q10); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.50% in Q9; the NEER prints a trade-weighted appreciation (+0.43% in Q10).

Equities and risk. Equity prices / financial conditions rises 0.38% by Q8; Tobin's Q (the value of installed capital) rises 0.10% by Q9; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output rises 0.15% by Q9; services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q18 (Q20 is still -0.01%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/BR_Y.png)

![CPI Inflation](charts/BR_pi_cpi.png)

![Equity Index](charts/BR_equity.png)

![Gold Price](charts/BR_P_gold.png)

![Food Price](charts/BR_P_food.png)

![Metals Price](charts/BR_P_metals.png)

![Copper Price](charts/BR_P_copper.png)

![Wheat Price](charts/BR_P_wheat.png)

![Energy Price](charts/BR_P_energy.png)

![VIX](charts/BR_vix.png)

![Gas Price](charts/BR_P_gas.png)

![vs USD](charts/BR_USD.png)

[Q1–Q20 JSON for Brazil](numbers/BR.json)

## CL — Chile

The main impact of a 200 basis-point (2.00 percentage-point) cut in United States interest rates on Chile is only a small rise in GDP of 0.04% by Q11. This is a model impulse response versus baseline, not a forecast. Equities firm 0.34% by Q8. The three-year CPI impulse is -0.09 percentage points.

Demand and trade. Private investment / the cost of capital rises 0.17% by Q9; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 0.20% by Q5; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-0.96% in Q10); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.39% in Q8; the NEER prints a trade-weighted appreciation (+0.30% in Q10).

Equities and risk. Equity prices / financial conditions rises 0.34% by Q8; Tobin's Q (the value of installed capital) rises 0.12% by Q9; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output rises 0.12% by Q8; services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q18 (Q20 is still -0.00%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/CL_Y.png)

![CPI Inflation](charts/CL_pi_cpi.png)

![Equity Index](charts/CL_equity.png)

![Gold Price](charts/CL_P_gold.png)

![Food Price](charts/CL_P_food.png)

![Metals Price](charts/CL_P_metals.png)

![Copper Price](charts/CL_P_copper.png)

![Wheat Price](charts/CL_P_wheat.png)

![Energy Price](charts/CL_P_energy.png)

![VIX](charts/CL_vix.png)

![Gas Price](charts/CL_P_gas.png)

![vs USD](charts/CL_USD.png)

[Q1–Q20 JSON for Chile](numbers/CL.json)

## NO — Norway

The main impact of a 200 basis-point (2.00 percentage-point) cut in United States interest rates on Norway is only a small rise in GDP of 0.04% by Q12. This is a model impulse response versus baseline, not a forecast. Equities firm 0.27% by Q8.

Demand and trade. Private investment / the cost of capital rises 0.12% by Q10; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 0.45% by Q8; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-0.92% in Q11); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.32% in Q10; the NEER prints a trade-weighted appreciation (+0.14% in Q12).

Equities and risk. Equity prices / financial conditions rises 0.27% by Q8; Tobin's Q (the value of installed capital) rises 0.08% by Q10; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output rises 0.10% by Q10; services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q19 (Q20 is still +0.00%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/NO_Y.png)

![CPI Inflation](charts/NO_pi_cpi.png)

![Equity Index](charts/NO_equity.png)

![Gold Price](charts/NO_P_gold.png)

![Food Price](charts/NO_P_food.png)

![Metals Price](charts/NO_P_metals.png)

![Copper Price](charts/NO_P_copper.png)

![Wheat Price](charts/NO_P_wheat.png)

![Energy Price](charts/NO_P_energy.png)

![VIX](charts/NO_vix.png)

![Gas Price](charts/NO_P_gas.png)

![vs USD](charts/NO_USD.png)

[Q1–Q20 JSON for Norway](numbers/NO.json)

## MY — Malaysia

The main impact of a 200 basis-point (2.00 percentage-point) cut in United States interest rates on Malaysia is only a small rise in GDP of 0.04% by Q11. This is a model impulse response versus baseline, not a forecast. Equities firm 0.29% by Q8. The three-year CPI impulse is -0.05 percentage points.

Demand and trade. Private investment / the cost of capital rises 0.13% by Q8; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation falls 0.06 percentage points by Q1; domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 0.19% by Q8; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-0.77% in Q9); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.29% in Q8; the NEER prints a trade-weighted appreciation (+0.13% in Q8).

Equities and risk. Equity prices / financial conditions rises 0.29% by Q8; Tobin's Q (the value of installed capital) rises 0.09% by Q8; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output rises 0.09% by Q8; services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q18 (Q20 is still -0.00%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/MY_Y.png)

![CPI Inflation](charts/MY_pi_cpi.png)

![Equity Index](charts/MY_equity.png)

![Gold Price](charts/MY_P_gold.png)

![Food Price](charts/MY_P_food.png)

![Metals Price](charts/MY_P_metals.png)

![Copper Price](charts/MY_P_copper.png)

![Wheat Price](charts/MY_P_wheat.png)

![Energy Price](charts/MY_P_energy.png)

![VIX](charts/MY_vix.png)

![Gas Price](charts/MY_P_gas.png)

![vs USD](charts/MY_USD.png)

[Q1–Q20 JSON for Malaysia](numbers/MY.json)

## TR — Turkey

The main impact of a 200 basis-point (2.00 percentage-point) cut in United States interest rates on Turkey is only a small rise in GDP of 0.04% by Q9. This is a model impulse response versus baseline, not a forecast. Equities firm 0.42% by Q8.

Demand and trade. Private investment / the cost of capital rises 0.10% by Q8; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 0.12% by Q8; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-0.70% in Q10); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.18% in Q8; the NEER prints a trade-weighted depreciation (-0.10% in Q20).

Equities and risk. Equity prices / financial conditions rises 0.42% by Q8; the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output, services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q15 (Q20 is still -0.02%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/TR_Y.png)

![CPI Inflation](charts/TR_pi_cpi.png)

![Equity Index](charts/TR_equity.png)

![Gold Price](charts/TR_P_gold.png)

![Food Price](charts/TR_P_food.png)

![Metals Price](charts/TR_P_metals.png)

![Copper Price](charts/TR_P_copper.png)

![Wheat Price](charts/TR_P_wheat.png)

![Energy Price](charts/TR_P_energy.png)

![VIX](charts/TR_vix.png)

![Gas Price](charts/TR_P_gas.png)

![vs USD](charts/TR_USD.png)

[Q1–Q20 JSON for Turkey](numbers/TR.json)

## NG — Nigeria

The main impact of a 200 basis-point (2.00 percentage-point) cut in United States interest rates on Nigeria is only a small rise in GDP of 0.03% by Q10. This is a model impulse response versus baseline, not a forecast. Equities firm 0.36% by Q8.

Demand and trade. Private investment / the cost of capital rises 0.08% by Q8; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 0.11% by Q13; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-0.74% in Q9); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.25% in Q8; the nominal effective exchange rate (increase = trade-weighted appreciation) stay close to baseline.

Equities and risk. Equity prices / financial conditions rises 0.36% by Q8; the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output, services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q16 (Q20 is still -0.03%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/NG_Y.png)

![CPI Inflation](charts/NG_pi_cpi.png)

![Equity Index](charts/NG_equity.png)

![Gold Price](charts/NG_P_gold.png)

![Food Price](charts/NG_P_food.png)

![Metals Price](charts/NG_P_metals.png)

![Copper Price](charts/NG_P_copper.png)

![Wheat Price](charts/NG_P_wheat.png)

![Energy Price](charts/NG_P_energy.png)

![VIX](charts/NG_vix.png)

![Gas Price](charts/NG_P_gas.png)

![vs USD](charts/NG_USD.png)

[Q1–Q20 JSON for Nigeria](numbers/NG.json)

## RU — Russia

The main impact of a 200 basis-point (2.00 percentage-point) cut in United States interest rates on Russia is only a small rise in GDP of 0.03% by Q11. This is a model impulse response versus baseline, not a forecast. Equities firm 0.41% by Q8.

Demand and trade. Household consumption, private investment / the cost of capital, the trade balance, government spending stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 0.12% by Q8; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-0.69% in Q11); the NEER prints a trade-weighted depreciation (-0.16% in Q8); the real exchange rate stay close to baseline.

Equities and risk. Equity prices / financial conditions rises 0.41% by Q8; the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output, services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q17 (Q20 is still -0.01%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/RU_Y.png)

![CPI Inflation](charts/RU_pi_cpi.png)

![Equity Index](charts/RU_equity.png)

![Gold Price](charts/RU_P_gold.png)

![Food Price](charts/RU_P_food.png)

![Metals Price](charts/RU_P_metals.png)

![Copper Price](charts/RU_P_copper.png)

![Wheat Price](charts/RU_P_wheat.png)

![Energy Price](charts/RU_P_energy.png)

![VIX](charts/RU_vix.png)

![Gas Price](charts/RU_P_gas.png)

![vs USD](charts/RU_USD.png)

[Q1–Q20 JSON for Russia](numbers/RU.json)

## NL — Netherlands

The main impact of a 200 basis-point (2.00 percentage-point) cut in United States interest rates on Netherlands is only a small rise in GDP of 0.03% by Q11. This is a model impulse response versus baseline, not a forecast. Equities firm 0.25% by Q8. The three-year CPI impulse is -0.21 percentage points.

Demand and trade. Private investment / the cost of capital rises 0.13% by Q10; the trade balance (net exports — this model does not split imports from exports) softens to -0.10% in Q10; household consumption, government spending, government debt stay close to baseline.

Labour. Real wages falls 0.09% by Q15; employment, unemployment stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 0.51% by Q8; 10-year bond prices rally 0.09% by Q1; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-1.00% in Q11); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.39% in Q11; the NEER prints a trade-weighted appreciation (+0.29% in Q13).

Equities and risk. Equity prices / financial conditions rises 0.25% by Q8; Tobin's Q (the value of installed capital) rises 0.09% by Q10; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output rises 0.12% by Q11; services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q20 (Q20 is still +0.00%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/NL_Y.png)

![CPI Inflation](charts/NL_pi_cpi.png)

![Equity Index](charts/NL_equity.png)

![Gold Price](charts/NL_P_gold.png)

![Food Price](charts/NL_P_food.png)

![Metals Price](charts/NL_P_metals.png)

![Copper Price](charts/NL_P_copper.png)

![Wheat Price](charts/NL_P_wheat.png)

![Energy Price](charts/NL_P_energy.png)

![VIX](charts/NL_vix.png)

![Gas Price](charts/NL_P_gas.png)

![vs USD](charts/NL_USD.png)

[Q1–Q20 JSON for Netherlands](numbers/NL.json)

## KR — South Korea

The main impact of a 200 basis-point (2.00 percentage-point) cut in United States interest rates on South Korea is only a small rise in GDP of 0.03% by Q11. This is a model impulse response versus baseline, not a forecast. Equities firm 0.31% by Q8. The three-year CPI impulse is -0.12 percentage points.

Demand and trade. Private investment / the cost of capital rises 0.13% by Q8; the trade balance (net exports — this model does not split imports from exports) softens to -0.10% in Q9; household consumption, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 0.24% by Q5; 2-year bond prices rally 0.08% by Q2; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-0.93% in Q10); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.38% in Q8; the NEER prints a trade-weighted appreciation (+0.28% in Q9).

Equities and risk. Equity prices / financial conditions rises 0.31% by Q8; Tobin's Q (the value of installed capital) rises 0.09% by Q8; the VIX (global equity-implied volatility) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output rises 0.11% by Q8; services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q19 (Q20 is still +0.00%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/KR_Y.png)

![CPI Inflation](charts/KR_pi_cpi.png)

![Equity Index](charts/KR_equity.png)

![Gold Price](charts/KR_P_gold.png)

![Food Price](charts/KR_P_food.png)

![Metals Price](charts/KR_P_metals.png)

![Copper Price](charts/KR_P_copper.png)

![Wheat Price](charts/KR_P_wheat.png)

![Energy Price](charts/KR_P_energy.png)

![VIX](charts/KR_vix.png)

![Gas Price](charts/KR_P_gas.png)

![vs USD](charts/KR_USD.png)

[Q1–Q20 JSON for South Korea](numbers/KR.json)

## ZA — South Africa

The main impact of a 200 basis-point (2.00 percentage-point) cut in United States interest rates on South Africa is only a small rise in GDP of 0.03% by Q10. This is a model impulse response versus baseline, not a forecast. Equities firm 0.35% by Q8. The three-year CPI impulse is -0.05 percentage points.

Demand and trade. Private investment / the cost of capital rises 0.10% by Q8; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 0.20% by Q8; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-0.84% in Q10); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.27% in Q8; the NEER prints a trade-weighted appreciation (+0.13% in Q11).

Equities and risk. Equity prices / financial conditions rises 0.35% by Q8; the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output rises 0.08% by Q8; services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q18 (Q20 is still -0.00%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/ZA_Y.png)

![CPI Inflation](charts/ZA_pi_cpi.png)

![Equity Index](charts/ZA_equity.png)

![Gold Price](charts/ZA_P_gold.png)

![Food Price](charts/ZA_P_food.png)

![Metals Price](charts/ZA_P_metals.png)

![Copper Price](charts/ZA_P_copper.png)

![Wheat Price](charts/ZA_P_wheat.png)

![Energy Price](charts/ZA_P_energy.png)

![VIX](charts/ZA_vix.png)

![Gas Price](charts/ZA_P_gas.png)

![vs USD](charts/ZA_USD.png)

[Q1–Q20 JSON for South Africa](numbers/ZA.json)

## TH — Thailand

The main impact of a 200 basis-point (2.00 percentage-point) cut in United States interest rates on Thailand is only a small rise in GDP of 0.02% by Q10. This is a model impulse response versus baseline, not a forecast. Equities firm 0.26% by Q8.

Demand and trade. Private investment / the cost of capital rises 0.09% by Q8; household consumption, the trade balance, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 0.19% by Q8; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-0.70% in Q10); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.21% in Q8; the nominal effective exchange rate (increase = trade-weighted appreciation) stay close to baseline.

Equities and risk. Equity prices / financial conditions rises 0.26% by Q8; the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output, services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q17 (Q20 is still -0.00%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/TH_Y.png)

![CPI Inflation](charts/TH_pi_cpi.png)

![Equity Index](charts/TH_equity.png)

![Gold Price](charts/TH_P_gold.png)

![Food Price](charts/TH_P_food.png)

![Metals Price](charts/TH_P_metals.png)

![Copper Price](charts/TH_P_copper.png)

![Wheat Price](charts/TH_P_wheat.png)

![Energy Price](charts/TH_P_energy.png)

![VIX](charts/TH_vix.png)

![Gas Price](charts/TH_P_gas.png)

![vs USD](charts/TH_USD.png)

[Q1–Q20 JSON for Thailand](numbers/TH.json)

## ID — Indonesia

The main impact of a 200 basis-point (2.00 percentage-point) cut in United States interest rates on Indonesia is only a small rise in GDP of 0.02% by Q10. This is a model impulse response versus baseline, not a forecast. Equities firm 0.25% by Q8.

Demand and trade. Household consumption, private investment / the cost of capital, the trade balance, government spending stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 0.17% by Q8; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-0.70% in Q10); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.20% in Q8; the nominal effective exchange rate (increase = trade-weighted appreciation) stay close to baseline.

Equities and risk. Equity prices / financial conditions rises 0.25% by Q8; the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output, services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q16 (Q20 is still -0.01%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/ID_Y.png)

![CPI Inflation](charts/ID_pi_cpi.png)

![Equity Index](charts/ID_equity.png)

![Gold Price](charts/ID_P_gold.png)

![Food Price](charts/ID_P_food.png)

![Metals Price](charts/ID_P_metals.png)

![Copper Price](charts/ID_P_copper.png)

![Wheat Price](charts/ID_P_wheat.png)

![Energy Price](charts/ID_P_energy.png)

![VIX](charts/ID_vix.png)

![Gas Price](charts/ID_P_gas.png)

![vs USD](charts/ID_USD.png)

[Q1–Q20 JSON for Indonesia](numbers/ID.json)

## IN — India

The main impact of a 200 basis-point (2.00 percentage-point) cut in United States interest rates on India is only a small rise in GDP of 0.02% by Q9. This is a model impulse response versus baseline, not a forecast. Equities firm 0.31% by Q8.

Demand and trade. Household consumption, private investment / the cost of capital, the trade balance, government spending stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 0.24% by Q8; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-0.73% in Q9); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.25% in Q8; the NEER prints a trade-weighted appreciation (+0.09% in Q8).

Equities and risk. Equity prices / financial conditions rises 0.31% by Q8; the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output, services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q15 (Q20 is still -0.02%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/IN_Y.png)

![CPI Inflation](charts/IN_pi_cpi.png)

![Equity Index](charts/IN_equity.png)

![Gold Price](charts/IN_P_gold.png)

![Food Price](charts/IN_P_food.png)

![Metals Price](charts/IN_P_metals.png)

![Copper Price](charts/IN_P_copper.png)

![Wheat Price](charts/IN_P_wheat.png)

![Energy Price](charts/IN_P_energy.png)

![VIX](charts/IN_vix.png)

![Gas Price](charts/IN_P_gas.png)

![vs USD](charts/IN_USD.png)

[Q1–Q20 JSON for India](numbers/IN.json)

## CH — Switzerland

The main impact of a 200 basis-point (2.00 percentage-point) cut in United States interest rates on Switzerland is only a small rise in GDP of 0.02% by Q11. This is a model impulse response versus baseline, not a forecast. Equities firm 0.21% by Q8. The three-year CPI impulse is -0.09 percentage points.

Demand and trade. Household consumption, private investment / the cost of capital, the trade balance, government spending stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 0.49% by Q8; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-0.83% in Q10); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.27% in Q8; the NEER prints a trade-weighted depreciation (-0.09% in Q20).

Equities and risk. Equity prices / financial conditions rises 0.21% by Q8; the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output rises 0.08% by Q8; services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q19 (Q20 is still +0.00%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/CH_Y.png)

![CPI Inflation](charts/CH_pi_cpi.png)

![Equity Index](charts/CH_equity.png)

![Gold Price](charts/CH_P_gold.png)

![Food Price](charts/CH_P_food.png)

![Metals Price](charts/CH_P_metals.png)

![Copper Price](charts/CH_P_copper.png)

![Wheat Price](charts/CH_P_wheat.png)

![Energy Price](charts/CH_P_energy.png)

![VIX](charts/CH_vix.png)

![Gas Price](charts/CH_P_gas.png)

![vs USD](charts/CH_USD.png)

[Q1–Q20 JSON for Switzerland](numbers/CH.json)

## AU — Australia

The main impact of a 200 basis-point (2.00 percentage-point) cut in United States interest rates on Australia is only a small rise in GDP of 0.02% by Q11. This is a model impulse response versus baseline, not a forecast. Equities firm 0.24% by Q8.

Demand and trade. Household consumption, private investment / the cost of capital, the trade balance, government spending stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 0.27% by Q8; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-0.89% in Q10); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.32% in Q9; the NEER prints a trade-weighted appreciation (+0.18% in Q11).

Equities and risk. Equity prices / financial conditions rises 0.24% by Q8; the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output rises 0.09% by Q8; services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q18 (Q20 is still -0.00%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/AU_Y.png)

![CPI Inflation](charts/AU_pi_cpi.png)

![Equity Index](charts/AU_equity.png)

![Gold Price](charts/AU_P_gold.png)

![Food Price](charts/AU_P_food.png)

![Metals Price](charts/AU_P_metals.png)

![Copper Price](charts/AU_P_copper.png)

![Wheat Price](charts/AU_P_wheat.png)

![Energy Price](charts/AU_P_energy.png)

![VIX](charts/AU_vix.png)

![Gas Price](charts/AU_P_gas.png)

![vs USD](charts/AU_USD.png)

[Q1–Q20 JSON for Australia](numbers/AU.json)

## PL — Poland

The main impact of a 200 basis-point (2.00 percentage-point) cut in United States interest rates on Poland is only a small rise in GDP of 0.02% by Q10. This is a model impulse response versus baseline, not a forecast. Equities firm 0.28% by Q8.

Demand and trade. Household consumption, private investment / the cost of capital, the trade balance, government spending stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 0.31% by Q8; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-0.73% in Q10); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.15% in Q8; the NEER prints a trade-weighted depreciation (-0.10% in Q8).

Equities and risk. Equity prices / financial conditions rises 0.28% by Q8; the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output, services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q18 (Q20 is still -0.00%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/PL_Y.png)

![CPI Inflation](charts/PL_pi_cpi.png)

![Equity Index](charts/PL_equity.png)

![Gold Price](charts/PL_P_gold.png)

![Food Price](charts/PL_P_food.png)

![Metals Price](charts/PL_P_metals.png)

![Copper Price](charts/PL_P_copper.png)

![Wheat Price](charts/PL_P_wheat.png)

![Energy Price](charts/PL_P_energy.png)

![VIX](charts/PL_vix.png)

![Gas Price](charts/PL_P_gas.png)

![vs USD](charts/PL_USD.png)

[Q1–Q20 JSON for Poland](numbers/PL.json)

## UK — United Kingdom

The main impact of a 200 basis-point (2.00 percentage-point) cut in United States interest rates on United Kingdom is only a small rise in GDP of 0.01% by Q10. This is a model impulse response versus baseline, not a forecast. Equities firm 0.23% by Q8.

Demand and trade. Household consumption, private investment / the cost of capital, the trade balance, government spending stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 0.60% by Q8; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-0.91% in Q10); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.37% in Q8; the NEER prints a trade-weighted appreciation (+0.20% in Q8).

Equities and risk. Equity prices / financial conditions rises 0.23% by Q8; the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output rises 0.11% by Q8; services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q18 (Q20 is still +0.00%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/UK_Y.png)

![CPI Inflation](charts/UK_pi_cpi.png)

![Equity Index](charts/UK_equity.png)

![Gold Price](charts/UK_P_gold.png)

![Food Price](charts/UK_P_food.png)

![Metals Price](charts/UK_P_metals.png)

![Copper Price](charts/UK_P_copper.png)

![Wheat Price](charts/UK_P_wheat.png)

![Energy Price](charts/UK_P_energy.png)

![VIX](charts/UK_vix.png)

![Gas Price](charts/UK_P_gas.png)

![vs USD](charts/UK_USD.png)

[Q1–Q20 JSON for United Kingdom](numbers/UK.json)

## FR — France

The main impact of a 200 basis-point (2.00 percentage-point) cut in United States interest rates on France is only a small rise in GDP of 0.01% by Q10. This is a model impulse response versus baseline, not a forecast. Equities firm 0.21% by Q8. The three-year CPI impulse is -0.12 percentage points.

Demand and trade. Household consumption, private investment / the cost of capital, the trade balance, government spending stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 0.63% by Q8; 10-year bond prices rally 0.09% by Q1; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-0.97% in Q11); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.36% in Q10; the NEER prints a trade-weighted appreciation (+0.17% in Q14).

Equities and risk. Equity prices / financial conditions rises 0.21% by Q8; the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output rises 0.10% by Q10; services output, the capital stock stay close to baseline.

By Q20, GDP is still +0.00% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/FR_Y.png)

![CPI Inflation](charts/FR_pi_cpi.png)

![Equity Index](charts/FR_equity.png)

![Gold Price](charts/FR_P_gold.png)

![Food Price](charts/FR_P_food.png)

![Metals Price](charts/FR_P_metals.png)

![Copper Price](charts/FR_P_copper.png)

![Wheat Price](charts/FR_P_wheat.png)

![Energy Price](charts/FR_P_energy.png)

![VIX](charts/FR_vix.png)

![Gas Price](charts/FR_P_gas.png)

![vs USD](charts/FR_USD.png)

[Q1–Q20 JSON for France](numbers/FR.json)

## SE — Sweden

The main impact of a 200 basis-point (2.00 percentage-point) cut in United States interest rates on Sweden is only a small rise in GDP of 0.01% by Q10. This is a model impulse response versus baseline, not a forecast. Equities firm 0.23% by Q8.

Demand and trade. Household consumption, private investment / the cost of capital, the trade balance, government spending stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 0.43% by Q8; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-0.74% in Q11); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.16% in Q8; the NEER prints a trade-weighted depreciation (-0.10% in Q20).

Equities and risk. Equity prices / financial conditions rises 0.23% by Q8; the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output, services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q18 (Q20 is still -0.00%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/SE_Y.png)

![CPI Inflation](charts/SE_pi_cpi.png)

![Equity Index](charts/SE_equity.png)

![Gold Price](charts/SE_P_gold.png)

![Food Price](charts/SE_P_food.png)

![Metals Price](charts/SE_P_metals.png)

![Copper Price](charts/SE_P_copper.png)

![Wheat Price](charts/SE_P_wheat.png)

![Energy Price](charts/SE_P_energy.png)

![VIX](charts/SE_vix.png)

![Gas Price](charts/SE_P_gas.png)

![vs USD](charts/SE_USD.png)

[Q1–Q20 JSON for Sweden](numbers/SE.json)

## ES — Spain

The main impact of a 200 basis-point (2.00 percentage-point) cut in United States interest rates on Spain is only a small rise in GDP of 0.01% by Q10. This is a model impulse response versus baseline, not a forecast. Equities firm 0.22% by Q8. The three-year CPI impulse is -0.12 percentage points.

Demand and trade. Household consumption, private investment / the cost of capital, the trade balance, government spending stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 0.61% by Q8; 10-year bond prices rally 0.09% by Q1; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-0.97% in Q11); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.36% in Q10; the NEER prints a trade-weighted appreciation (+0.20% in Q14).

Equities and risk. Equity prices / financial conditions rises 0.22% by Q8; the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output rises 0.10% by Q10; services output, the capital stock stay close to baseline.

By Q20, GDP is still +0.00% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/ES_Y.png)

![CPI Inflation](charts/ES_pi_cpi.png)

![Equity Index](charts/ES_equity.png)

![Gold Price](charts/ES_P_gold.png)

![Food Price](charts/ES_P_food.png)

![Metals Price](charts/ES_P_metals.png)

![Copper Price](charts/ES_P_copper.png)

![Wheat Price](charts/ES_P_wheat.png)

![Energy Price](charts/ES_P_energy.png)

![VIX](charts/ES_vix.png)

![Gas Price](charts/ES_P_gas.png)

![vs USD](charts/ES_USD.png)

[Q1–Q20 JSON for Spain](numbers/ES.json)

## DE — Germany

The main impact of a 200 basis-point (2.00 percentage-point) cut in United States interest rates on Germany is only a small rise in GDP of 0.01% by Q10. This is a model impulse response versus baseline, not a forecast. Equities firm 0.17% by Q8. The three-year CPI impulse is -0.15 percentage points.

Demand and trade. The trade balance (net exports — this model does not split imports from exports) softens to -0.09% in Q11; household consumption, private investment / the cost of capital, government spending, government debt stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 0.54% by Q8; 10-year bond prices rally 0.09% by Q1; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-0.96% in Q11); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.36% in Q10; the NEER prints a trade-weighted appreciation (+0.21% in Q15).

Equities and risk. Equity prices / financial conditions rises 0.17% by Q8; the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output rises 0.10% by Q10; services output, the capital stock stay close to baseline.

By Q20, GDP is still +0.00% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/DE_Y.png)

![CPI Inflation](charts/DE_pi_cpi.png)

![Equity Index](charts/DE_equity.png)

![Gold Price](charts/DE_P_gold.png)

![Food Price](charts/DE_P_food.png)

![Metals Price](charts/DE_P_metals.png)

![Copper Price](charts/DE_P_copper.png)

![Wheat Price](charts/DE_P_wheat.png)

![Energy Price](charts/DE_P_energy.png)

![VIX](charts/DE_vix.png)

![Gas Price](charts/DE_P_gas.png)

![vs USD](charts/DE_USD.png)

[Q1–Q20 JSON for Germany](numbers/DE.json)

## CN — China

The main impact of a 200 basis-point (2.00 percentage-point) cut in United States interest rates on China is only a small rise in GDP of 0.01% by Q9. This is a model impulse response versus baseline, not a forecast. Equities firm 0.17% by Q8.

Demand and trade. Household consumption, private investment / the cost of capital, the trade balance, government spending stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 0.24% by Q8; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-0.67% in Q9); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.23% in Q2; the NEER prints a trade-weighted depreciation (-0.13% in Q11).

Equities and risk. Equity prices / financial conditions rises 0.17% by Q8; the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output, services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q15 (Q20 is still -0.00%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/CN_Y.png)

![CPI Inflation](charts/CN_pi_cpi.png)

![Equity Index](charts/CN_equity.png)

![Gold Price](charts/CN_P_gold.png)

![Food Price](charts/CN_P_food.png)

![Metals Price](charts/CN_P_metals.png)

![Copper Price](charts/CN_P_copper.png)

![Wheat Price](charts/CN_P_wheat.png)

![Energy Price](charts/CN_P_energy.png)

![VIX](charts/CN_vix.png)

![Gas Price](charts/CN_P_gas.png)

![vs USD](charts/CN_USD.png)

[Q1–Q20 JSON for China](numbers/CN.json)

## IT — Italy

The main impact of a 200 basis-point (2.00 percentage-point) cut in United States interest rates on Italy is only a small rise in GDP of 0.01% by Q9. This is a model impulse response versus baseline, not a forecast. Equities firm 0.22% by Q8. The three-year CPI impulse is -0.10 percentage points.

Demand and trade. Household consumption, private investment / the cost of capital, the trade balance, government spending stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 0.67% by Q8; 10-year bond prices rally 0.09% by Q1; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-0.96% in Q11); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.35% in Q10; the NEER prints a trade-weighted appreciation (+0.17% in Q14).

Equities and risk. Equity prices / financial conditions rises 0.22% by Q8; the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output rises 0.10% by Q10; services output, the capital stock stay close to baseline.

By Q20, GDP is still +0.00% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/IT_Y.png)

![CPI Inflation](charts/IT_pi_cpi.png)

![Equity Index](charts/IT_equity.png)

![Gold Price](charts/IT_P_gold.png)

![Food Price](charts/IT_P_food.png)

![Metals Price](charts/IT_P_metals.png)

![Copper Price](charts/IT_P_copper.png)

![Wheat Price](charts/IT_P_wheat.png)

![Energy Price](charts/IT_P_energy.png)

![VIX](charts/IT_vix.png)

![Gas Price](charts/IT_P_gas.png)

![vs USD](charts/IT_USD.png)

[Q1–Q20 JSON for Italy](numbers/IT.json)

## JP — Japan

The main impact of a 200 basis-point (2.00 percentage-point) cut in United States interest rates on Japan is only a small rise in GDP of 0.01% by Q8. This is a model impulse response versus baseline, not a forecast. Equities firm 0.14% by Q8. The three-year CPI impulse is -0.05 percentage points.

Demand and trade. Household consumption, private investment / the cost of capital, the trade balance, government spending stay close to baseline.

Labour. Employment, unemployment, real wages stay close to baseline.

Prices. CPI inflation, domestic inflation, firms' marginal cost stay close to baseline.

Policy rates and the government curve. Bond prices (higher discount rates) rally 0.78% by Q8; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is stronger versus the dollar (-0.95% in Q9); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.43% in Q8; the NEER prints a trade-weighted appreciation (+0.31% in Q9).

Equities and risk. Equity prices / financial conditions rises 0.14% by Q8; the VIX (global equity-implied volatility), Tobin's Q (the value of installed capital) stay close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. Other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output rises 0.13% by Q8; services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q13 (Q20 is still -0.00%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/JP_Y.png)

![CPI Inflation](charts/JP_pi_cpi.png)

![Equity Index](charts/JP_equity.png)

![Gold Price](charts/JP_P_gold.png)

![Food Price](charts/JP_P_food.png)

![Metals Price](charts/JP_P_metals.png)

![Copper Price](charts/JP_P_copper.png)

![Wheat Price](charts/JP_P_wheat.png)

![Energy Price](charts/JP_P_energy.png)

![VIX](charts/JP_vix.png)

![Gas Price](charts/JP_P_gas.png)

![vs USD](charts/JP_USD.png)

[Q1–Q20 JSON for Japan](numbers/JP.json)


---

These figures are model IRFs versus baseline, not forecasts, and not financial advice.
