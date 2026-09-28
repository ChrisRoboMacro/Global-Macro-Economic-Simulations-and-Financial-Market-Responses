# Global Macro Economic Simulations and Financial Market Responses

v6 · IRF · evaluation

**Open the typeset report (this is the document):** https://robomacro.com/GlobalMacroTrainingDataset/oil180_us150/

GitHub and Hugging Face show `.html` as source code. That is not the report. Read it on robomacro.com, or keep scrolling this page.

## What's the impact of Oil $180 and US +150bp

a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel. Every path is a model impulse response versus baseline, not a forecast and not financial advice.

### Summary

This note traces the model response to a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel. Every path is an impulse response versus an unchanged baseline — not a forecast of what will happen in the world and not a reading of market data. The chapters that follow are already sorted by the size of the GDP response.

Turkey takes the largest GDP move on this path. GDP contracts by 4.96% versus baseline by Q13 — a first-order GDP response. Equities soften 8.18%, and the three-year CPI impulse is +1.96 percentage points. The move shows up first in private investment / the cost of capital, then in government debt, the trade balance. That is the main adjustment: a change in financial conditions and real income, then the usual lag into activity and prices. It is the conditional elasticity to the shock that was switched on, not a prediction that this path will be realised.

Spillovers are not a carbon copy of that first path. India contracts by 4.62% versus baseline by Q13 — a first-order GDP response. Equities soften 12.17%, and the three-year CPI impulse is +1.93 percentage points. The move shows up first in private investment / the cost of capital, then in government debt, the trade balance. South Korea contracts by 4.56% versus baseline by Q12 — a first-order GDP response. Equities soften 11.22%, and the three-year CPI impulse is +3.00 percentage points. The move shows up first in private investment / the cost of capital, then in the trade balance, government debt. Japan contracts by 3.95% versus baseline by Q13 — a first-order GDP response. Equities soften 10.81%, and the three-year CPI impulse is +1.96 percentage points. The move shows up first in private investment / the cost of capital, then in the trade balance, household consumption. The contrast is the point: an oil importer does not print the same GDP sign as an oil exporter.

Germany contracts by 3.93% versus baseline by Q14 — a first-order GDP response. Equities soften 7.60%, and the three-year CPI impulse is +2.92 percentage points. The move shows up first in private investment / the cost of capital, then in the trade balance, household consumption.

A few prices are common across the panel. On the government curve, 10-year bond prices rally 9.52% by Q10, and unused tenors stay in the background rather than getting a sentence each; versus the dollar the home currency is weaker versus the dollar (+8.62% in Q12); gold prices moves to $2377 in Q10. Treat those as the shared financial backdrop, not as extra shocks, unless they appear in the active treatment.

Read GDP as percent of baseline GDP: −0.52 is minus half a percent, never −52%. A 200 basis-point move is 2.00 percentage points on the policy rate. CPI over three years is the sum of twelve quarterly impulses, not an annualised rate. A rising real exchange rate is a real depreciation — a weaker, more competitive home currency.

The remaining economies are smaller spillovers, written in the same order in the chapters that follow. Each chapter is a desk note, not a catalog of every series. This material is a model-based summary and is not financial advice.


![TR GDP](charts/global_TR_Y.png)

![IN GDP](charts/global_IN_Y.png)

![KR GDP](charts/global_KR_Y.png)

![JP GDP](charts/global_JP_Y.png)

![US Equity Index](charts/global_US_equity.png)

![US Policy Rate](charts/global_US_i.png)

## TR — Turkey

The main impact of a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel on Turkey is a large drop in GDP of 4.96% by Q13. This is a model impulse response versus baseline, not a forecast. Equities soften 8.18% by Q12. The three-year CPI impulse is +1.96 percentage points.

Demand and trade. Private investment / the cost of capital falls 12.59% by Q9; government debt falls 5.56% by Q20; the trade balance (net exports — this model does not split imports from exports) softens to -3.70% in Q3; household consumption falls 2.89% by Q13; the same direction shows up in government spending.

Labour. Real wages falls 8.11% by Q20; employment falls 4.78% by Q17; unemployment rises by +1.14 percentage points in Q14.

Prices. Firms' marginal cost falls 2.95% by Q13; CPI inflation falls 0.47 percentage points by Q18; domestic inflation falls 0.33 percentage points by Q18.

Policy rates and the government curve. 10-year bond prices rally 9.52% by Q10; 30-year bond prices rally 8.26% by Q10; 5-year bond prices rally 8.02% by Q12; bond prices (higher discount rates) rally 7.00% by Q19; the same direction shows up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+8.62% in Q12); the NEER prints a trade-weighted depreciation (-7.01% in Q12); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +6.65% in Q12.

Equities and risk. Global VIX moves to 22.0 in Q8 (baseline 15); Tobin's Q (the value of installed capital) falls 8.81% by Q9; equity prices / financial conditions falls 8.18% by Q12.

Housing and credit. House prices fall 6.44% by Q18; bank equity falls 0.82% by Q17; bank credit supply falls 0.72% by Q17; lending spreads rises 0.06 percentage points by Q17.

Commodities. Gold prices moves to $2377 in Q10; the energy price index moves to $160 a barrel in Q4; the food price index moves to 110.7 in Q8; other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 4.92% by Q11; services output falls 3.00% by Q13; the capital stock falls 0.98% by Q20.

By Q20, GDP is still -2.73% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel on India is a large drop in GDP of 4.62% by Q13. This is a model impulse response versus baseline, not a forecast. Equities soften 12.17% by Q13. The three-year CPI impulse is +1.93 percentage points.

Demand and trade. Private investment / the cost of capital falls 12.40% by Q8; government debt falls 8.67% by Q20; the trade balance (net exports — this model does not split imports from exports) softens to -3.86% in Q4; household consumption falls 2.80% by Q13; the same direction shows up in government spending.

Labour. Real wages falls 6.63% by Q20; employment falls 4.05% by Q19; unemployment rises by +0.32 percentage points in Q14.

Prices. Firms' marginal cost falls 2.74% by Q13; CPI inflation rises 0.49 percentage points by Q3; domestic inflation rises 0.34 percentage points by Q3.

Policy rates and the government curve. 10-year bond prices rally 12.84% by Q12; bond prices (higher discount rates) rally 12.67% by Q20; 30-year bond prices rally 11.37% by Q11; 5-year bond prices rally 9.75% by Q15; the same direction shows up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+7.44% in Q15); the NEER prints a trade-weighted depreciation (-6.61% in Q15); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +5.61% in Q16.

Equities and risk. Global VIX moves to 22.0 in Q8 (baseline 15); equity prices / financial conditions falls 12.17% by Q13; Tobin's Q (the value of installed capital) falls 8.68% by Q8.

Housing and credit. House prices fall 6.04% by Q19; bank equity falls 0.94% by Q16; bank credit supply falls 0.83% by Q16; house prices and bank credit are close to unchanged.

Commodities. Gold prices moves to $2377 in Q10; the energy price index moves to $160 a barrel in Q4; the food price index moves to 110.7 in Q8; other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 4.04% by Q13; services output falls 2.54% by Q13; the capital stock falls 0.97% by Q20.

By Q20, GDP is still -2.99% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

![Bond Price 10Y](charts/IN_Q_B_10y.png)

![Bond Price (7y)](charts/IN_Q_B.png)

[Q1–Q20 JSON for India](numbers/IN.json)

## KR — South Korea

The main impact of a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel on South Korea is a large drop in GDP of 4.56% by Q12. This is a model impulse response versus baseline, not a forecast. Equities soften 11.22% by Q12. The three-year CPI impulse is +3.00 percentage points.

Demand and trade. Private investment / the cost of capital falls 11.88% by Q9; the trade balance (net exports — this model does not split imports from exports) softens to -4.54% in Q4; government debt falls 3.27% by Q20; household consumption falls 2.85% by Q12; the same direction shows up in government spending.

Labour. Real wages falls 5.07% by Q20; employment falls 4.39% by Q16; unemployment rises by +1.76 percentage points in Q14.

Prices. Firms' marginal cost falls 2.70% by Q12; CPI inflation rises 0.56 percentage points by Q2; domestic inflation rises 0.39 percentage points by Q2.

Policy rates and the government curve. 10-year bond prices rally 11.71% by Q12; 30-year bond prices rally 11.57% by Q10; bond prices (higher discount rates) rally 9.75% by Q20; 5-year bond prices rally 7.99% by Q15; the same direction shows up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+10.33% in Q10); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +8.36% in Q8; the NEER prints a trade-weighted depreciation (-8.16% in Q14).

Equities and risk. Global VIX moves to 22.0 in Q8 (baseline 15); equity prices / financial conditions falls 11.22% by Q12; Tobin's Q (the value of installed capital) falls 8.32% by Q9.

Housing and credit. House prices fall 5.57% by Q20; bank equity falls 1.41% by Q17; bank credit supply falls 1.12% by Q17; house prices and bank credit are close to unchanged.

Commodities. Gold prices moves to $2377 in Q10; the energy price index moves to $160 a barrel in Q4; the food price index moves to 110.7 in Q8; other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 6.31% by Q4; services output falls 2.76% by Q12; the capital stock falls 0.98% by Q20.

By Q20, GDP is still -3.18% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

## JP — Japan

The main impact of a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel on Japan is a large drop in GDP of 3.95% by Q13. This is a model impulse response versus baseline, not a forecast. Equities soften 10.81% by Q13. The three-year CPI impulse is +1.96 percentage points.

Demand and trade. Private investment / the cost of capital falls 11.21% by Q13; the trade balance (net exports — this model does not split imports from exports) softens to -3.75% in Q4; household consumption falls 2.65% by Q13; government debt falls 1.53% by Q20; the same direction shows up in government spending.

Labour. Employment falls 4.07% by Q15; unemployment rises by +2.77 percentage points in Q16; real wages rises 1.04% by Q11.

Prices. Firms' marginal cost falls 2.33% by Q13; CPI inflation rises 0.55 percentage points by Q2; domestic inflation rises 0.39 percentage points by Q2.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 2.84% by Q5; 30-year bond prices rally 2.45% by Q20; 10-year bond prices rally 1.66% by Q20; 5-year bond prices rally 0.83% by Q20; the same direction shows up in 2-year bond prices, the local policy rate, 3-month government yields; the rest of the government curve barely moves.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+10.12% in Q5); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +9.06% in Q4; the NEER prints a trade-weighted depreciation (-9.05% in Q4).

Equities and risk. Global VIX moves to 22.0 in Q8 (baseline 15); equity prices / financial conditions falls 10.81% by Q13; Tobin's Q (the value of installed capital) falls 7.84% by Q13.

Housing and credit. House prices fall 4.77% by Q20; bank equity falls 1.72% by Q16; bank credit supply falls 1.35% by Q16; house prices and bank credit are close to unchanged.

Commodities. Gold prices moves to $2377 in Q10; the energy price index moves to $160 a barrel in Q4; the food price index moves to 110.7 in Q8; other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 5.76% by Q4; services output falls 2.73% by Q13; the capital stock falls 0.96% by Q20.

By Q20, GDP is still -3.14% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

## DE — Germany

The main impact of a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel on Germany is a large drop in GDP of 3.93% by Q14. This is a model impulse response versus baseline, not a forecast. Equities soften 7.60% by Q14. The three-year CPI impulse is +2.92 percentage points.

Demand and trade. Private investment / the cost of capital falls 11.22% by Q11; the trade balance (net exports — this model does not split imports from exports) softens to -2.63% in Q4; household consumption falls 2.23% by Q15; government spending rises 0.87% by Q14; the same direction shows up in government debt.

Labour. Employment falls 3.95% by Q18; unemployment rises by +2.77 percentage points in Q17; real wages falls 2.67% by Q20.

Prices. Firms' marginal cost falls 2.33% by Q14; CPI inflation rises 0.73 percentage points by Q2; domestic inflation rises 0.51 percentage points by Q2.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 10.15% by Q6; 30-year bond prices rally 5.09% by Q15; 10-year bond prices rally 4.92% by Q17; 5-year bond prices rally 3.31% by Q20; the same direction shows up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+6.36% in Q7); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +5.16% in Q4; the NEER prints a trade-weighted depreciation (-3.71% in Q4).

Equities and risk. Global VIX moves to 22.0 in Q8 (baseline 15); Tobin's Q (the value of installed capital) falls 7.85% by Q11; equity prices / financial conditions falls 7.60% by Q14.

Housing and credit. House prices fall 5.13% by Q20; bank equity falls 1.62% by Q17; bank credit supply falls 1.31% by Q17; house prices and bank credit are close to unchanged.

Commodities. Gold prices moves to $2377 in Q10; the energy price index moves to $160 a barrel in Q4; the food price index moves to 110.7 in Q8; other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 4.47% by Q4; services output falls 2.68% by Q14; the capital stock falls 0.98% by Q20.

By Q20, GDP is still -3.23% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

## SA — Saudi Arabia

The main impact of a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel on Saudi Arabia is a large rise in GDP of 3.85% by Q1. This is a model impulse response versus baseline, not a forecast. Equities firm 15.32% by Q1. The three-year CPI impulse is +3.02 percentage points.

Demand and trade. The trade balance (net exports — this model does not split imports from exports) improves to +24.67% in Q4; private investment / the cost of capital rises 10.20% by Q20; government debt rises 9.60% by Q20; government spending rises 9.35% by Q4; the same direction shows up in household consumption.

Labour. Real wages rises 6.45% by Q20; employment rises 4.22% by Q20; unemployment eases by -1.49 percentage points in Q20.

Prices. Firms' marginal cost rises 2.32% by Q1; CPI inflation rises 0.38 percentage points by Q3; domestic inflation rises 0.26 percentage points by Q3.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 8.71% by Q6; 5-year bond prices cheapen 3.29% by Q1; 10-year bond prices cheapen 3.04% by Q1; 2-year bond prices cheapen 2.76% by Q2; the same direction shows up in 30-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. The NEER prints a trade-weighted appreciation (+2.31% in Q9); versus the dollar the home currency is weaker versus the dollar (+1.05% in Q10); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.95% in Q11.

Equities and risk. Global VIX moves to 22.0 in Q8 (baseline 15); equity prices / financial conditions rises 15.32% by Q1; Tobin's Q (the value of installed capital) rises 7.14% by Q20.

Housing and credit. House prices rise 6.03% by Q20; bank equity rises 0.49% by Q20; bank credit supply rises 0.15% by Q20; house prices and bank credit are close to unchanged.

Commodities. Gold prices moves to $2377 in Q10; the energy price index moves to $160 a barrel in Q4; the food price index moves to 110.7 in Q8; other published commodity prices stay near their baselines.

Sectors and capital. Services output rises 1.69% by Q1; the capital stock rises 0.89% by Q20; manufacturing output falls 0.55% by Q3.

By Q20, GDP is still +3.65% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel on Norway is a large rise in GDP of 3.82% by Q1. This is a model impulse response versus baseline, not a forecast. Equities firm 8.24% by Q1. The three-year CPI impulse is +0.71 percentage points.

Demand and trade. The trade balance (net exports — this model does not split imports from exports) improves to +14.29% in Q4; private investment / the cost of capital rises 9.89% by Q1; government spending rises 6.01% by Q4; household consumption rises 2.14% by Q5; the same direction shows up in government debt.

Labour. Real wages rises 3.99% by Q20; employment rises 3.42% by Q15; unemployment eases by -1.96 percentage points in Q10.

Prices. Firms' marginal cost rises 2.30% by Q1; CPI inflation rises 0.32 percentage points by Q2; domestic inflation rises 0.22 percentage points by Q2.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 13.77% by Q7; 10-year bond prices cheapen 10.17% by Q2; 30-year bond prices cheapen 9.59% by Q1; 5-year bond prices cheapen 7.43% by Q2; the same direction shows up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. The NEER prints a trade-weighted appreciation (+38.86% in Q5); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -38.05% in Q5; versus the dollar the home currency is stronger versus the dollar (-37.03% in Q4).

Equities and risk. Global VIX moves to 22.0 in Q8 (baseline 15); equity prices / financial conditions rises 8.24% by Q1; Tobin's Q (the value of installed capital) rises 6.92% by Q1.

Housing and credit. House prices rise 4.10% by Q20; bank equity rises 0.60% by Q19; bank credit supply rises 0.23% by Q19; house prices and bank credit are close to unchanged.

Commodities. Gold prices moves to $2377 in Q10; the energy price index moves to $160 a barrel in Q4; the food price index moves to 110.7 in Q8; other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output rises 10.63% by Q5; services output rises 2.18% by Q1; the capital stock rises 0.63% by Q20.

By Q20, GDP is still +2.10% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

## RU — Russia

The main impact of a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel on Russia is a large rise in GDP of 3.79% by Q2. This is a model impulse response versus baseline, not a forecast. Equities firm 6.11% by Q2. The three-year CPI impulse is +3.51 percentage points.

Demand and trade. The trade balance (net exports — this model does not split imports from exports) improves to +14.34% in Q4; private investment / the cost of capital rises 9.41% by Q1; government spending rises 4.11% by Q4; household consumption rises 2.05% by Q4; the same direction shows up in government debt.

Labour. Real wages rises 7.15% by Q20; employment rises 3.10% by Q10; unemployment eases by -1.25 percentage points in Q7.

Prices. Firms' marginal cost rises 2.29% by Q2; CPI inflation rises 0.44 percentage points by Q3; domestic inflation rises 0.31 percentage points by Q3.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 6.78% by Q6; 10-year bond prices cheapen 5.79% by Q1; 5-year bond prices cheapen 5.70% by Q1; 30-year bond prices cheapen 4.30% by Q1; the same direction shows up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. The NEER prints a trade-weighted appreciation (+21.21% in Q5); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -17.92% in Q5; versus the dollar the home currency is stronger versus the dollar (-16.84% in Q4).

Equities and risk. Global VIX moves to 22.0 in Q8 (baseline 15); Tobin's Q (the value of installed capital) rises 6.59% by Q1; equity prices / financial conditions rises 6.11% by Q2.

Housing and credit. House prices rise 3.68% by Q13; bank equity rises 0.38% by Q18; bank credit supply rises 0.12% by Q18; house prices and bank credit are close to unchanged.

Commodities. Gold prices moves to $2377 in Q10; the energy price index moves to $160 a barrel in Q4; the food price index moves to 110.7 in Q8; other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output rises 4.50% by Q5; services output rises 2.08% by Q2; the capital stock rises 0.48% by Q20.

The GDP response has mostly faded by Q19 (Q20 is still +0.84%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/RU_Y.png)

![CPI Inflation](charts/RU_pi_cpi.png)

![Equity Index](charts/RU_equity.png)

![Gold Price](charts/RU_P_gold.png)

![Energy Price](charts/RU_P_energy.png)

![Food Price](charts/RU_P_food.png)

![Wheat Price](charts/RU_P_wheat.png)

![Copper Price](charts/RU_P_copper.png)

![Metals Price](charts/RU_P_metals.png)

![VIX](charts/RU_vix.png)

![NEER](charts/RU_NEER.png)

![Real Exchange Rate](charts/RU_RER.png)

[Q1–Q20 JSON for Russia](numbers/RU.json)

## IT — Italy

The main impact of a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel on Italy is a large drop in GDP of 3.63% by Q15. This is a model impulse response versus baseline, not a forecast. Equities soften 6.15% by Q15. The three-year CPI impulse is +2.77 percentage points.

Demand and trade. Private investment / the cost of capital falls 10.39% by Q10; the trade balance (net exports — this model does not split imports from exports) softens to -2.75% in Q4; household consumption falls 1.91% by Q15; government spending rises 0.78% by Q15; the same direction shows up in government debt.

Labour. Employment falls 3.88% by Q19; unemployment rises by +1.50 percentage points in Q17; real wages falls 0.95% by Q20.

Prices. Firms' marginal cost falls 2.15% by Q15; CPI inflation rises 0.62 percentage points by Q2; domestic inflation rises 0.43 percentage points by Q2.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 10.07% by Q6; 30-year bond prices rally 5.09% by Q15; 10-year bond prices rally 4.92% by Q17; 5-year bond prices rally 3.31% by Q20; the same direction shows up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+7.24% in Q6); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +6.10% in Q4; the NEER prints a trade-weighted depreciation (-3.98% in Q4).

Equities and risk. Global VIX moves to 22.0 in Q8 (baseline 15); Tobin's Q (the value of installed capital) falls 7.27% by Q10; equity prices / financial conditions falls 6.15% by Q15.

Housing and credit. House prices fall 4.62% by Q20; bank equity falls 1.28% by Q17; bank credit supply falls 1.07% by Q17; house prices and bank credit are close to unchanged.

Commodities. Gold prices moves to $2377 in Q10; the energy price index moves to $160 a barrel in Q4; the food price index moves to 110.7 in Q8; other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 4.21% by Q4; services output falls 2.63% by Q15; the capital stock falls 0.93% by Q20.

By Q20, GDP is still -3.07% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel on Poland is a large drop in GDP of 3.44% by Q17. This is a model impulse response versus baseline, not a forecast. Equities soften 5.74% by Q13. The three-year CPI impulse is +2.18 percentage points.

Demand and trade. Private investment / the cost of capital falls 9.56% by Q9; household consumption falls 1.86% by Q17; the trade balance (net exports — this model does not split imports from exports) softens to -1.85% in Q4; government spending rises 0.68% by Q17; government debt stay close to baseline.

Labour. Employment falls 3.71% by Q19; real wages falls 3.58% by Q20; unemployment rises by +1.44 percentage points in Q18.

Prices. Firms' marginal cost falls 2.04% by Q17; CPI inflation rises 0.51 percentage points by Q2; domestic inflation rises 0.36 percentage points by Q2.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 7.11% by Q5; 10-year bond prices rally 6.26% by Q15; 30-year bond prices rally 6.01% by Q13; 5-year bond prices rally 4.36% by Q17; the same direction shows up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+5.14% in Q9); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +4.07% in Q3; the NEER prints a trade-weighted depreciation (-2.52% in Q3).

Equities and risk. Global VIX moves to 22.0 in Q8 (baseline 15); Tobin's Q (the value of installed capital) falls 6.69% by Q9; equity prices / financial conditions falls 5.74% by Q13.

Housing and credit. House prices fall 4.59% by Q20; bank equity falls 0.83% by Q18; bank credit supply falls 0.75% by Q18; house prices and bank credit are close to unchanged.

Commodities. Gold prices moves to $2377 in Q10; the energy price index moves to $160 a barrel in Q4; the food price index moves to 110.7 in Q8; other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 4.12% by Q4; services output falls 2.15% by Q17; the capital stock falls 0.85% by Q20.

By Q20, GDP is still -3.02% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel on Spain is a large drop in GDP of 3.39% by Q16. This is a model impulse response versus baseline, not a forecast. Equities soften 6.36% by Q15. The three-year CPI impulse is +2.45 percentage points.

Demand and trade. Private investment / the cost of capital falls 9.77% by Q9; the trade balance (net exports — this model does not split imports from exports) softens to -2.74% in Q4; household consumption falls 1.94% by Q16; government spending rises 0.73% by Q16; the same direction shows up in government debt.

Labour. Employment falls 3.59% by Q19; unemployment rises by +1.66 percentage points in Q18; real wages falls 1.44% by Q20.

Prices. Firms' marginal cost falls 2.01% by Q16; CPI inflation rises 0.56 percentage points by Q2; domestic inflation rises 0.39 percentage points by Q2.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 10.15% by Q6; 30-year bond prices rally 5.09% by Q15; 10-year bond prices rally 4.92% by Q17; 5-year bond prices rally 3.31% by Q20; the same direction shows up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+6.17% in Q7); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +5.00% in Q4; the NEER prints a trade-weighted depreciation (-3.82% in Q4).

Equities and risk. Global VIX moves to 22.0 in Q8 (baseline 15); Tobin's Q (the value of installed capital) falls 6.84% by Q9; equity prices / financial conditions falls 6.36% by Q15.

Housing and credit. House prices fall 4.43% by Q20; bank equity falls 1.09% by Q17; bank credit supply falls 0.88% by Q17; house prices and bank credit are close to unchanged.

Commodities. Gold prices moves to $2377 in Q10; the energy price index moves to $160 a barrel in Q4; the food price index moves to 110.7 in Q8; other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 3.62% by Q4; services output falls 2.50% by Q16; the capital stock falls 0.88% by Q20.

By Q20, GDP is still -3.01% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel on Thailand is a large drop in GDP of 3.32% by Q16. This is a model impulse response versus baseline, not a forecast. Equities soften 7.90% by Q13. The three-year CPI impulse is +2.44 percentage points.

Demand and trade. Private investment / the cost of capital falls 8.65% by Q9; government debt falls 5.87% by Q20; household consumption falls 2.22% by Q16; the trade balance (net exports — this model does not split imports from exports) softens to -2.07% in Q3; the same direction shows up in government spending.

Labour. Real wages falls 4.18% by Q20; employment falls 3.65% by Q18; unemployment rises by +0.32 percentage points in Q17.

Prices. Firms' marginal cost falls 1.97% by Q16; CPI inflation rises 0.52 percentage points by Q2; domestic inflation rises 0.36 percentage points by Q2.

Policy rates and the government curve. 10-year bond prices rally 9.03% by Q13; 30-year bond prices rally 8.98% by Q11; bond prices (higher discount rates) rally 6.26% by Q20; 5-year bond prices rally 6.24% by Q16; the same direction shows up in 2-year bond prices, 2-year government yields, the local policy rate.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+3.34% in Q13); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +1.51% in Q17; the NEER prints a trade-weighted appreciation (+0.64% in Q5).

Equities and risk. Global VIX moves to 22.0 in Q8 (baseline 15); equity prices / financial conditions falls 7.90% by Q13; Tobin's Q (the value of installed capital) falls 6.06% by Q9.

Housing and credit. House prices fall 5.51% by Q20; bank equity falls 0.87% by Q17; bank credit supply falls 0.71% by Q17; house prices and bank credit are close to unchanged.

Commodities. Gold prices moves to $2377 in Q10; the energy price index moves to $160 a barrel in Q4; the food price index moves to 110.7 in Q8; other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 3.61% by Q4; services output falls 1.82% by Q16; the capital stock falls 0.77% by Q20.

By Q20, GDP is still -2.86% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

![Bond Price 10Y](charts/TH_Q_B_10y.png)

![Bond Price 30Y](charts/TH_Q_B_30y.png)

[Q1–Q20 JSON for Thailand](numbers/TH.json)

## FR — France

The main impact of a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel on France is a large drop in GDP of 3.18% by Q17. This is a model impulse response versus baseline, not a forecast. Equities soften 6.92% by Q15. The three-year CPI impulse is +2.58 percentage points.

Demand and trade. Private investment / the cost of capital falls 9.23% by Q10; government debt rises 2.96% by Q20; household consumption falls 1.74% by Q18; the trade balance (net exports — this model does not split imports from exports) softens to -1.66% in Q4; the same direction shows up in government spending.

Labour. Employment falls 3.34% by Q20; unemployment rises by +2.33 percentage points in Q19; real wages falls 1.07% by Q20.

Prices. Firms' marginal cost falls 1.89% by Q17; CPI inflation rises 0.59 percentage points by Q2; domestic inflation rises 0.41 percentage points by Q2.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 10.15% by Q6; 30-year bond prices rally 5.09% by Q15; 10-year bond prices rally 4.92% by Q17; 5-year bond prices rally 3.31% by Q20; the same direction shows up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+6.28% in Q7); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +5.11% in Q4; the NEER prints a trade-weighted depreciation (-2.63% in Q4).

Equities and risk. Global VIX moves to 22.0 in Q8 (baseline 15); equity prices / financial conditions falls 6.92% by Q15; Tobin's Q (the value of installed capital) falls 6.46% by Q10.

Housing and credit. House prices fall 4.17% by Q20; bank equity falls 1.42% by Q17; bank credit supply falls 1.13% by Q17; house prices and bank credit are close to unchanged.

Commodities. Gold prices moves to $2377 in Q10; the energy price index moves to $160 a barrel in Q4; the food price index moves to 110.7 in Q8; other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 3.38% by Q4; services output falls 2.45% by Q17; the capital stock falls 0.82% by Q20.

By Q20, GDP is still -2.96% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

## AR — Argentina

The main impact of a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel on Argentina is a large drop in GDP of 3.09% by Q13. This is a model impulse response versus baseline, not a forecast. Equities soften 4.88% by Q11. The three-year CPI impulse is +1.20 percentage points.

Demand and trade. Private investment / the cost of capital falls 7.21% by Q9; government debt falls 2.80% by Q20; the trade balance (net exports — this model does not split imports from exports) improves to +1.76% in Q8; household consumption falls 1.56% by Q14; the same direction shows up in government spending.

Labour. Real wages falls 5.89% by Q20; employment falls 3.02% by Q18; unemployment rises by +0.61 percentage points in Q15.

Prices. Firms' marginal cost falls 1.84% by Q13; CPI inflation falls 0.50 percentage points by Q18; domestic inflation falls 0.35 percentage points by Q18.

Policy rates and the government curve. 10-year bond prices rally 8.36% by Q9; 5-year bond prices rally 7.92% by Q11; 30-year bond prices rally 7.18% by Q9; bond prices (higher discount rates) rally 5.78% by Q18; the same direction shows up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+4.85% in Q12); the NEER prints a trade-weighted depreciation (-3.31% in Q10); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +2.88% in Q13.

Equities and risk. Global VIX moves to 22.0 in Q8 (baseline 15); Tobin's Q (the value of installed capital) falls 5.04% by Q9; equity prices / financial conditions falls 4.88% by Q11.

Housing and credit. House prices fall 3.48% by Q19; bank credit supply falls 0.27% by Q18; bank equity falls 0.13% by Q18; lending spreads rises 0.08 percentage points by Q18.

Commodities. Gold prices moves to $2377 in Q10; the energy price index moves to $160 a barrel in Q4; the food price index moves to 110.7 in Q8; other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 2.60% by Q10; services output falls 1.77% by Q13; the capital stock falls 0.51% by Q20.

By Q20, GDP is still -1.97% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel on South Africa is a large drop in GDP of 2.96% by Q15. This is a model impulse response versus baseline, not a forecast. Equities soften 11.43% by Q13. The three-year CPI impulse is +1.63 percentage points.

Demand and trade. Private investment / the cost of capital falls 8.39% by Q8; government debt falls 3.10% by Q20; the trade balance (net exports — this model does not split imports from exports) softens to -2.19% in Q4; household consumption falls 1.74% by Q16; the same direction shows up in government spending.

Labour. Real wages falls 3.90% by Q20; employment falls 3.32% by Q19; unemployment rises by +0.72 percentage points in Q17.

Prices. Firms' marginal cost falls 1.75% by Q15; CPI inflation rises 0.39 percentage points by Q2; domestic inflation rises 0.28 percentage points by Q2.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 6.27% by Q5; 10-year bond prices rally 5.91% by Q13; 30-year bond prices rally 5.35% by Q12; 5-year bond prices rally 4.44% by Q15; the same direction shows up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+5.79% in Q9); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +4.18% in Q4; the NEER prints a trade-weighted depreciation (-2.47% in Q3).

Equities and risk. Global VIX moves to 22.0 in Q8 (baseline 15); equity prices / financial conditions falls 11.43% by Q13; Tobin's Q (the value of installed capital) falls 5.87% by Q8.

Housing and credit. House prices fall 4.49% by Q20; bank equity falls 0.75% by Q17; bank credit supply falls 0.64% by Q17; house prices and bank credit are close to unchanged.

Commodities. Gold prices moves to $2377 in Q10; the energy price index moves to $160 a barrel in Q4; the food price index moves to 110.7 in Q8; other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 3.08% by Q4; services output falls 1.89% by Q15; the capital stock falls 0.72% by Q20.

By Q20, GDP is still -2.55% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

![Gas Price](charts/ZA_P_gas.png)

[Q1–Q20 JSON for South Africa](numbers/ZA.json)

## CN — China

The main impact of a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel on China is a large drop in GDP of 2.70% by Q12. This is a model impulse response versus baseline, not a forecast. Equities soften 5.68% by Q8. The three-year CPI impulse is +2.31 percentage points.

Demand and trade. Private investment / the cost of capital falls 7.09% by Q4; government debt falls 4.79% by Q20; the trade balance (net exports — this model does not split imports from exports) softens to -2.77% in Q4; household consumption falls 2.02% by Q13; the same direction shows up in government spending.

Labour. Real wages falls 4.34% by Q20; employment falls 2.56% by Q19; unemployment rises by +0.62 percentage points in Q15.

Prices. Firms' marginal cost falls 1.59% by Q13; CPI inflation rises 0.61 percentage points by Q2; domestic inflation rises 0.43 percentage points by Q2.

Policy rates and the government curve. 10-year bond prices rally 14.76% by Q12; 30-year bond prices rally 14.32% by Q8; bond prices (higher discount rates) rally 11.96% by Q20; 5-year bond prices rally 10.10% by Q16; the same direction shows up in 2-year bond prices, 2-year government yields, the local policy rate.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+5.42% in Q18); the NEER prints a trade-weighted depreciation (-3.91% in Q20); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +3.80% in Q20.

Equities and risk. Global VIX moves to 22.0 in Q8 (baseline 15); equity prices / financial conditions falls 5.68% by Q8; Tobin's Q (the value of installed capital) falls 4.96% by Q4.

Housing and credit. House prices fall 3.72% by Q20; bank equity falls 0.87% by Q16; bank credit supply falls 0.67% by Q16; house prices and bank credit are close to unchanged.

Commodities. Gold prices moves to $2377 in Q10; the energy price index moves to $160 a barrel in Q4; the food price index moves to 110.7 in Q8; other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 4.20% by Q5; services output falls 1.57% by Q12; the capital stock falls 0.54% by Q20.

By Q20, GDP is still -2.14% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel on Chile is a large drop in GDP of 2.64% by Q15. This is a model impulse response versus baseline, not a forecast. Equities soften 5.82% by Q12. The three-year CPI impulse is +1.32 percentage points.

Demand and trade. Private investment / the cost of capital falls 7.82% by Q7; government debt falls 2.91% by Q20; the trade balance (net exports — this model does not split imports from exports) softens to -2.41% in Q5; household consumption falls 1.67% by Q16; the same direction shows up in government spending.

Labour. Real wages falls 3.58% by Q20; employment falls 2.91% by Q19; unemployment rises by +0.95 percentage points in Q18.

Prices. Firms' marginal cost falls 1.57% by Q15; CPI inflation rises 0.38 percentage points by Q2; domestic inflation rises 0.27 percentage points by Q2.

Policy rates and the government curve. 10-year bond prices rally 6.41% by Q14; bond prices (higher discount rates) cheapen 6.35% by Q5; 30-year bond prices rally 6.06% by Q12; 5-year bond prices rally 4.67% by Q16; the same direction shows up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+4.92% in Q9); the NEER prints a trade-weighted depreciation (-3.59% in Q4); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +3.44% in Q4.

Equities and risk. Global VIX moves to 22.0 in Q8 (baseline 15); equity prices / financial conditions falls 5.82% by Q12; Tobin's Q (the value of installed capital) falls 5.48% by Q7.

Housing and credit. House prices fall 4.09% by Q20; bank equity falls 0.65% by Q18; bank credit supply falls 0.53% by Q18; house prices and bank credit are close to unchanged.

Commodities. Gold prices moves to $2377 in Q10; the energy price index moves to $160 a barrel in Q4; the food price index moves to 110.7 in Q8; other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 2.82% by Q4; services output falls 1.60% by Q15; the capital stock falls 0.66% by Q20.

By Q20, GDP is still -2.31% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

![Gas Price](charts/CL_P_gas.png)

[Q1–Q20 JSON for Chile](numbers/CL.json)

## SE — Sweden

The main impact of a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel on Sweden is a large drop in GDP of 2.30% by Q16. This is a model impulse response versus baseline, not a forecast. Equities soften 6.57% by Q13. The three-year CPI impulse is +2.08 percentage points.

Demand and trade. Private investment / the cost of capital falls 7.22% by Q8; the trade balance (net exports — this model does not split imports from exports) softens to -1.93% in Q4; household consumption falls 1.33% by Q17; government debt rises 1.27% by Q20; the same direction shows up in government spending.

Labour. Employment falls 2.37% by Q20; real wages falls 1.73% by Q20; unemployment rises by +1.70 percentage points in Q19.

Prices. Firms' marginal cost falls 1.37% by Q16; CPI inflation rises 0.49 percentage points by Q2; domestic inflation rises 0.34 percentage points by Q2.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 8.69% by Q5; 10-year bond prices rally 4.44% by Q16; 30-year bond prices rally 4.31% by Q14; 5-year bond prices rally 3.04% by Q19; the same direction shows up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. The NEER prints a trade-weighted depreciation (-3.69% in Q5); versus the dollar the home currency is weaker versus the dollar (+3.41% in Q10); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +1.44% in Q5.

Equities and risk. Global VIX moves to 22.0 in Q8 (baseline 15); equity prices / financial conditions falls 6.57% by Q13; Tobin's Q (the value of installed capital) falls 5.06% by Q8.

Housing and credit. House prices fall 3.15% by Q20; bank equity falls 0.94% by Q18; bank credit supply falls 0.75% by Q18; house prices and bank credit are close to unchanged.

Commodities. Gold prices moves to $2377 in Q10; the energy price index moves to $160 a barrel in Q4; the food price index moves to 110.7 in Q8; other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 2.59% by Q4; services output falls 1.65% by Q16; the capital stock falls 0.63% by Q20.

By Q20, GDP is still -2.12% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel on Indonesia is a large drop in GDP of 2.23% by Q14. This is a model impulse response versus baseline, not a forecast. Equities soften 4.32% by Q9. The three-year CPI impulse is +1.71 percentage points.

Demand and trade. Private investment / the cost of capital falls 6.91% by Q8; government debt falls 3.95% by Q20; household consumption falls 1.34% by Q15; the trade balance (net exports — this model does not split imports from exports) softens to -0.99% in Q4; the same direction shows up in government spending.

Labour. Real wages falls 3.30% by Q20; employment falls 2.19% by Q20; unemployment rises by +0.19 percentage points in Q15.

Prices. Firms' marginal cost falls 1.32% by Q14; CPI inflation rises 0.40 percentage points by Q3; domestic inflation rises 0.28 percentage points by Q3.

Policy rates and the government curve. 10-year bond prices rally 6.11% by Q14; bond prices (higher discount rates) cheapen 5.59% by Q5; 30-year bond prices rally 5.52% by Q13; 5-year bond prices rally 4.65% by Q16; the same direction shows up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. The NEER prints a trade-weighted appreciation (+4.80% in Q5); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -3.77% in Q4; versus the dollar the home currency is stronger versus the dollar (-2.88% in Q3).

Equities and risk. Global VIX moves to 22.0 in Q8 (baseline 15); Tobin's Q (the value of installed capital) falls 4.84% by Q8; equity prices / financial conditions falls 4.32% by Q9.

Housing and credit. House prices fall 3.27% by Q20; bank credit supply falls 0.47% by Q17; bank equity falls 0.47% by Q17; house prices and bank credit are close to unchanged.

Commodities. Gold prices moves to $2377 in Q10; the energy price index moves to $160 a barrel in Q4; the food price index moves to 110.7 in Q8; other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 1.30% by Q4; services output falls 1.10% by Q14; the capital stock falls 0.55% by Q20.

By Q20, GDP is still -1.81% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

![Gas Price](charts/ID_P_gas.png)

[Q1–Q20 JSON for Indonesia](numbers/ID.json)

## NG — Nigeria

The main impact of a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel on Nigeria is a large rise in GDP of 2.19% by Q3. This is a model impulse response versus baseline, not a forecast. Equities firm 2.65% by Q3. The three-year CPI impulse is +3.81 percentage points.

Demand and trade. The trade balance (net exports — this model does not split imports from exports) improves to +7.70% in Q4; private investment / the cost of capital rises 4.95% by Q2; government debt rises 3.62% by Q11; household consumption rises 1.25% by Q4; the same direction shows up in government spending.

Labour. Real wages rises 3.39% by Q13; employment rises 1.31% by Q8; unemployment eases by -0.24 percentage points in Q6.

Prices. Firms' marginal cost rises 1.34% by Q3; CPI inflation rises 0.51 percentage points by Q4; domestic inflation rises 0.36 percentage points by Q4.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 5.21% by Q6; 5-year bond prices cheapen 3.53% by Q1; 2-year bond prices cheapen 3.40% by Q3; the local policy rate rises 2.08 percentage points by Q6; the same direction shows up in 3-month government yields, 10-year bond prices, 2-year government yields.

Exchange rates. The NEER prints a trade-weighted appreciation (+8.21% in Q5); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -8.19% in Q5; versus the dollar the home currency is stronger versus the dollar (-7.17% in Q4).

Equities and risk. Global VIX moves to 22.0 in Q8 (baseline 15); Tobin's Q (the value of installed capital) rises 3.47% by Q2; equity prices / financial conditions rises 2.65% by Q3.

Housing and credit. House prices rise 1.46% by Q8; bank equity rises 0.15% by Q14; house prices and bank credit are close to unchanged.

Commodities. Gold prices moves to $2377 in Q10; the energy price index moves to $160 a barrel in Q4; the food price index moves to 110.7 in Q8; other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output rises 1.87% by Q5; services output rises 1.08% by Q3; the capital stock rises 0.10% by Q7.

The GDP response has mostly faded by Q10 (Q20 is still -0.62%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

![NEER](charts/NG_NEER.png)

![Real Exchange Rate](charts/NG_RER.png)

[Q1–Q20 JSON for Nigeria](numbers/NG.json)

## CH — Switzerland

The main impact of a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel on Switzerland is a large drop in GDP of 2.08% by Q15. This is a model impulse response versus baseline, not a forecast. Equities soften 8.06% by Q14. The three-year CPI impulse is +2.04 percentage points.

Demand and trade. Private investment / the cost of capital falls 5.71% by Q9; household consumption falls 1.47% by Q16; government debt falls 1.26% by Q20; the trade balance (net exports — this model does not split imports from exports) softens to -0.58% in Q2; the same direction shows up in government spending.

Labour. Employment falls 2.18% by Q19; unemployment rises by +1.53 percentage points in Q19; real wages rises 0.68% by Q11.

Prices. Firms' marginal cost falls 1.24% by Q15; CPI inflation rises 0.45 percentage points by Q3; domestic inflation rises 0.32 percentage points by Q3.

Policy rates and the government curve. Bond prices (higher discount rates) rally 5.25% by Q20; 30-year bond prices rally 4.89% by Q12; 10-year bond prices rally 4.78% by Q15; 5-year bond prices rally 3.19% by Q18; the same direction shows up in 2-year bond prices, 2-year government yields, 3-month government yields.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+5.37% in Q8); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +3.75% in Q6; the NEER prints a trade-weighted depreciation (-1.97% in Q7).

Equities and risk. Global VIX moves to 22.0 in Q8 (baseline 15); equity prices / financial conditions falls 8.06% by Q14; Tobin's Q (the value of installed capital) falls 4.00% by Q9.

Housing and credit. House prices fall 2.83% by Q20; bank equity falls 1.14% by Q18; bank credit supply falls 0.90% by Q18; house prices and bank credit are close to unchanged.

Commodities. Gold prices moves to $2377 in Q10; the energy price index moves to $160 a barrel in Q4; the food price index moves to 110.7 in Q8; other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 3.21% by Q5; services output falls 1.65% by Q15; the capital stock falls 0.50% by Q20.

By Q20, GDP is still -1.94% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel on United Kingdom is a large drop in GDP of 1.89% by Q12. This is a model impulse response versus baseline, not a forecast. Equities soften 4.90% by Q8. The three-year CPI impulse is +1.97 percentage points.

Demand and trade. Private investment / the cost of capital falls 5.68% by Q10; household consumption falls 1.18% by Q13; the trade balance (net exports — this model does not split imports from exports) softens to -0.78% in Q3; government spending rises 0.38% by Q13; the same direction shows up in government debt.

Labour. Employment falls 2.16% by Q17; unemployment rises by +1.38 percentage points in Q17; real wages falls 0.89% by Q20.

Prices. Firms' marginal cost falls 1.11% by Q13; CPI inflation rises 0.54 percentage points by Q2; domestic inflation rises 0.38 percentage points by Q2.

Policy rates and the government curve. 30-year bond prices rally 3.79% by Q18; bond prices (higher discount rates) cheapen 3.14% by Q7; 10-year bond prices rally 2.91% by Q20; 5-year bond prices rally 1.56% by Q20; the same direction shows up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+6.24% in Q6); the NEER prints a trade-weighted depreciation (-5.30% in Q5); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +4.90% in Q5.

Equities and risk. Global VIX moves to 22.0 in Q8 (baseline 15); equity prices / financial conditions falls 4.90% by Q8; Tobin's Q (the value of installed capital) falls 3.97% by Q10.

Housing and credit. House prices fall 2.40% by Q20; bank equity falls 0.91% by Q17; bank credit supply falls 0.73% by Q17; house prices and bank credit are close to unchanged.

Commodities. Gold prices moves to $2377 in Q10; the energy price index moves to $160 a barrel in Q4; the food price index moves to 110.7 in Q8; other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 3.09% by Q5; services output falls 1.49% by Q12; the capital stock falls 0.49% by Q20.

By Q20, GDP is still -1.64% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

![vs USD](charts/UK_USD.png)

[Q1–Q20 JSON for United Kingdom](numbers/UK.json)

## BR — Brazil

The main impact of a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel on Brazil is a large drop in GDP of 1.84% by Q13. This is a model impulse response versus baseline, not a forecast. Equities soften 3.53% by Q11. The three-year CPI impulse is +1.95 percentage points.

Demand and trade. Private investment / the cost of capital falls 5.78% by Q9; the trade balance (net exports — this model does not split imports from exports) improves to +2.17% in Q5; household consumption falls 0.99% by Q15; government spending rises 0.68% by Q11; the same direction shows up in government debt.

Labour. Employment falls 1.71% by Q19; real wages falls 1.44% by Q20; unemployment rises by +0.38 percentage points in Q16.

Prices. Firms' marginal cost falls 1.09% by Q13; CPI inflation rises 0.37 percentage points by Q2; domestic inflation rises 0.26 percentage points by Q2.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 9.42% by Q5; 10-year bond prices rally 5.45% by Q13; 5-year bond prices rally 4.57% by Q14; 30-year bond prices rally 4.47% by Q12; the same direction shows up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. The real exchange rate shows a real appreciation (a stronger home currency), peaking at -5.91% in Q5; the NEER prints a trade-weighted appreciation (+5.39% in Q6); versus the dollar the home currency is stronger versus the dollar (-4.70% in Q5).

Equities and risk. Global VIX moves to 22.0 in Q8 (baseline 15); Tobin's Q (the value of installed capital) falls 4.05% by Q9; equity prices / financial conditions falls 3.53% by Q11.

Housing and credit. House prices fall 2.20% by Q20; bank equity falls 0.10% by Q20; bank credit supply falls 0.09% by Q20; house prices and bank credit are close to unchanged.

Commodities. Gold prices moves to $2377 in Q10; the energy price index moves to $160 a barrel in Q4; the food price index moves to 110.7 in Q8; other published commodity prices stay near their baselines.

Sectors and capital. Services output falls 1.22% by Q13; manufacturing output falls 0.81% by Q17; the capital stock falls 0.40% by Q20.

By Q20, GDP is still -1.31% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

![Gas Price](charts/BR_P_gas.png)

[Q1–Q20 JSON for Brazil](numbers/BR.json)

## NL — Netherlands

The main impact of a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel on Netherlands is a large drop in GDP of 1.80% by Q15. This is a model impulse response versus baseline, not a forecast. Equities soften 4.77% by Q12. The three-year CPI impulse is +3.15 percentage points.

Demand and trade. Private investment / the cost of capital falls 6.11% by Q8; the trade balance (net exports — this model does not split imports from exports) improves to +1.42% in Q5; household consumption falls 1.03% by Q16; government debt rises 0.48% by Q20; the same direction shows up in government spending.

Labour. Employment falls 1.81% by Q20; unemployment rises by +1.32 percentage points in Q19; real wages rises 1.03% by Q11.

Prices. Firms' marginal cost falls 1.06% by Q15; CPI inflation rises 0.69 percentage points by Q2; domestic inflation rises 0.49 percentage points by Q2.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 10.15% by Q6; 30-year bond prices rally 5.09% by Q15; 10-year bond prices rally 4.92% by Q17; 5-year bond prices rally 3.31% by Q20; the same direction shows up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. The real exchange rate shows a real appreciation (a stronger home currency), peaking at -2.03% in Q4; the NEER prints a trade-weighted appreciation (+1.81% in Q4); versus the dollar the home currency is stronger versus the dollar (-1.27% in Q2).

Equities and risk. Global VIX moves to 22.0 in Q8 (baseline 15); equity prices / financial conditions falls 4.77% by Q12; Tobin's Q (the value of installed capital) falls 4.28% by Q8.

Housing and credit. House prices fall 2.62% by Q20; bank equity falls 1.00% by Q19; bank credit supply falls 0.79% by Q19; house prices and bank credit are close to unchanged.

Commodities. Gold prices moves to $2377 in Q10; the energy price index moves to $160 a barrel in Q4; the food price index moves to 110.7 in Q8; other published commodity prices stay near their baselines.

Sectors and capital. Services output falls 1.35% by Q15; manufacturing output falls 1.07% by Q4; the capital stock falls 0.50% by Q20.

By Q20, GDP is still -1.66% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

![Gas Price](charts/NL_P_gas.png)

[Q1–Q20 JSON for Netherlands](numbers/NL.json)

## US — United States

The main impact of a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel on the United States is a large drop in GDP of 1.75% by Q12. This is a model impulse response versus baseline, not a forecast. Equities soften 5.65% by Q12. The three-year CPI impulse is +1.87 percentage points.

Demand and trade. Private investment / the cost of capital falls 6.49% by Q8; household consumption falls 1.19% by Q13; government debt falls 0.36% by Q14; government spending rises 0.34% by Q12; the trade balance stay close to baseline.

Labour. Employment falls 1.94% by Q15; unemployment rises by +1.21 percentage points in Q16; real wages falls 0.96% by Q20.

Prices. Firms' marginal cost falls 1.04% by Q12; CPI inflation rises 0.48 percentage points by Q2; domestic inflation rises 0.34 percentage points by Q2.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 11.47% by Q6; 5-year bond prices cheapen 3.29% by Q1; 10-year bond prices cheapen 3.04% by Q1; 2-year bond prices cheapen 2.76% by Q2; the same direction shows up in 30-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. The NEER prints a trade-weighted depreciation (-6.52% in Q3); versus the dollar the home currency is stronger versus the dollar (-6.52% in Q3); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -2.00% in Q10.

Equities and risk. Global VIX moves to 22.0 in Q8 (baseline 15); equity prices / financial conditions falls 5.65% by Q12; Tobin's Q (the value of installed capital) falls 4.54% by Q8.

Housing and credit. House prices fall 2.06% by Q20; bank equity falls 0.60% by Q18; bank credit supply falls 0.48% by Q18; house prices and bank credit are close to unchanged.

Commodities. Gold prices moves to $2377 in Q10; the energy price index moves to $160 a barrel in Q4; the food price index moves to 110.7 in Q8; other published commodity prices stay near their baselines.

Sectors and capital. Services output falls 1.35% by Q12; manufacturing output falls 1.35% by Q3; the capital stock falls 0.49% by Q20.

By Q20, GDP is still -1.37% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

![Gas Price](charts/US_P_gas.png)

[Q1–Q20 JSON for United States](numbers/US.json)

## AU — Australia

The main impact of a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel on Australia is a large drop in GDP of 1.50% by Q12. This is a model impulse response versus baseline, not a forecast. Equities soften 4.08% by Q6. The three-year CPI impulse is +1.77 percentage points.

Demand and trade. Private investment / the cost of capital falls 4.98% by Q5; the trade balance (net exports — this model does not split imports from exports) softens to -1.14% in Q4; household consumption falls 0.95% by Q13; government debt falls 0.93% by Q20; the same direction shows up in government spending.

Labour. Employment falls 1.67% by Q15; real wages falls 1.35% by Q20; unemployment rises by +1.08 percentage points in Q16.

Prices. Firms' marginal cost falls 0.89% by Q12; CPI inflation rises 0.40 percentage points by Q2; domestic inflation rises 0.28 percentage points by Q2.

Policy rates and the government curve. Bond prices (higher discount rates) rally 7.26% by Q20; 10-year bond prices rally 6.12% by Q13; 30-year bond prices rally 5.41% by Q11; 5-year bond prices rally 4.56% by Q15; the same direction shows up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. Versus the dollar the home currency is weaker versus the dollar (+7.69% in Q11); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +5.70% in Q11; the NEER prints a trade-weighted depreciation (-4.44% in Q12).

Equities and risk. Global VIX moves to 22.0 in Q8 (baseline 15); equity prices / financial conditions falls 4.08% by Q6; Tobin's Q (the value of installed capital) falls 3.49% by Q5.

Housing and credit. House prices fall 1.83% by Q20; bank equity falls 0.66% by Q18; bank credit supply falls 0.52% by Q18; house prices and bank credit are close to unchanged.

Commodities. Gold prices moves to $2377 in Q10; the energy price index moves to $160 a barrel in Q4; the food price index moves to 110.7 in Q8; other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output falls 3.00% by Q5; services output falls 1.07% by Q12; the capital stock falls 0.36% by Q20.

By Q20, GDP is still -1.14% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

![vs USD](charts/AU_USD.png)

![Bond Price (7y)](charts/AU_Q_B.png)

[Q1–Q20 JSON for Australia](numbers/AU.json)

## MX — Mexico

The main impact of a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel on Mexico is a large drop in GDP of 1.38% by Q12. This is a model impulse response versus baseline, not a forecast. Equities soften 2.53% by Q8. The three-year CPI impulse is +1.71 percentage points.

Demand and trade. Private investment / the cost of capital falls 4.85% by Q8; government debt falls 1.99% by Q20; the trade balance (net exports — this model does not split imports from exports) improves to +1.86% in Q4; household consumption falls 0.77% by Q14; the same direction shows up in government spending.

Labour. Employment falls 1.29% by Q18; real wages falls 0.99% by Q20; unemployment rises by +0.12 percentage points in Q15.

Prices. Firms' marginal cost falls 0.81% by Q13; CPI inflation rises 0.34 percentage points by Q2; domestic inflation rises 0.24 percentage points by Q2.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 7.00% by Q5; 10-year bond prices rally 3.66% by Q14; 30-year bond prices rally 3.08% by Q13; 5-year bond prices rally 2.83% by Q16; the same direction shows up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. The NEER prints a trade-weighted appreciation (+19.20% in Q4); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -19.20% in Q4; versus the dollar the home currency is stronger versus the dollar (-18.23% in Q4).

Equities and risk. Global VIX moves to 22.0 in Q8 (baseline 15); Tobin's Q (the value of installed capital) falls 3.39% by Q8; equity prices / financial conditions falls 2.53% by Q8.

Housing and credit. House prices fall 1.92% by Q19; bank equity falls 0.26% by Q20; bank credit supply falls 0.25% by Q20; house prices and bank credit are close to unchanged.

Commodities. Gold prices moves to $2377 in Q10; the energy price index moves to $160 a barrel in Q4; the food price index moves to 110.7 in Q8; other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output rises 3.61% by Q4; services output falls 0.83% by Q12; the capital stock falls 0.34% by Q20.

By Q20, GDP is still -0.91% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/MX_Y.png)

![CPI Inflation](charts/MX_pi_cpi.png)

![Equity Index](charts/MX_equity.png)

![Gold Price](charts/MX_P_gold.png)

![Energy Price](charts/MX_P_energy.png)

![Food Price](charts/MX_P_food.png)

![Wheat Price](charts/MX_P_wheat.png)

![Copper Price](charts/MX_P_copper.png)

![Metals Price](charts/MX_P_metals.png)

![VIX](charts/MX_vix.png)

![NEER](charts/MX_NEER.png)

![Real Exchange Rate](charts/MX_RER.png)

[Q1–Q20 JSON for Mexico](numbers/MX.json)

## CA — Canada

The main impact of a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel on Canada is a large rise in GDP of 1.30% by Q3. This is a model impulse response versus baseline, not a forecast. Equities firm 2.84% by Q3. The three-year CPI impulse is +1.48 percentage points.

Demand and trade. The trade balance (net exports — this model does not split imports from exports) improves to +4.76% in Q4; private investment / the cost of capital rises 2.30% by Q2; government spending rises 1.02% by Q5; household consumption rises 0.80% by Q4; the same direction shows up in government debt.

Labour. Real wages rises 1.57% by Q16; employment rises 1.16% by Q6; unemployment eases by -0.58 percentage points in Q6.

Prices. Firms' marginal cost rises 0.80% by Q3; CPI inflation rises 0.35 percentage points by Q2; domestic inflation rises 0.25 percentage points by Q2.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 10.51% by Q5; 5-year bond prices cheapen 3.51% by Q1; 2-year bond prices cheapen 2.91% by Q3; 10-year bond prices cheapen 2.39% by Q1; the same direction shows up in the local policy rate, 3-month government yields, 30-year bond prices.

Exchange rates. The real exchange rate shows a real appreciation (a stronger home currency), peaking at -36.49% in Q4; the NEER prints a trade-weighted appreciation (+35.95% in Q4); versus the dollar the home currency is stronger versus the dollar (-35.53% in Q4).

Equities and risk. Global VIX moves to 22.0 in Q8 (baseline 15); equity prices / financial conditions rises 2.84% by Q3; Tobin's Q (the value of installed capital) rises 1.61% by Q2.

Housing and credit. House prices rise 0.64% by Q9; bank equity rises 0.10% by Q9; house prices and bank credit are close to unchanged.

Commodities. Gold prices moves to $2377 in Q10; the energy price index moves to $160 a barrel in Q4; the food price index moves to 110.7 in Q8; other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output rises 9.73% by Q4; services output rises 0.90% by Q3; the capital stock stay close to baseline.

The GDP response has mostly faded by Q11 (Q20 is still +0.01%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

## MY — Malaysia

The main impact of a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel on Malaysia is a large drop in GDP of 0.94% by Q12. This is a model impulse response versus baseline, not a forecast. Equities soften 2.63% by Q8. The three-year CPI impulse is +1.29 percentage points.

Demand and trade. Private investment / the cost of capital falls 3.05% by Q7; the trade balance (net exports — this model does not split imports from exports) improves to +2.23% in Q4; government debt falls 1.64% by Q20; household consumption falls 0.62% by Q13; the same direction shows up in government spending.

Labour. Real wages falls 1.05% by Q20; employment falls 0.91% by Q17; unemployment rises by +0.22 percentage points in Q15.

Prices. Firms' marginal cost falls 0.55% by Q12; CPI inflation rises 0.44 percentage points by Q2; domestic inflation rises 0.31 percentage points by Q2.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 3.34% by Q5; 10-year bond prices rally 2.65% by Q13; 5-year bond prices rally 2.27% by Q14; 30-year bond prices rally 2.09% by Q12; the same direction shows up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. The NEER prints a trade-weighted appreciation (+11.04% in Q4); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -9.08% in Q4; versus the dollar the home currency is stronger versus the dollar (-8.11% in Q4).

Equities and risk. Global VIX moves to 22.0 in Q8 (baseline 15); equity prices / financial conditions falls 2.63% by Q8; Tobin's Q (the value of installed capital) falls 2.14% by Q7.

Housing and credit. House prices fall 1.44% by Q18; bank equity falls 0.32% by Q20; bank credit supply falls 0.26% by Q20; house prices and bank credit are close to unchanged.

Commodities. Gold prices moves to $2377 in Q10; the energy price index moves to $160 a barrel in Q4; the food price index moves to 110.7 in Q8; other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output rises 0.62% by Q20; services output falls 0.54% by Q12; the capital stock falls 0.21% by Q20.

By Q20, GDP is still -0.58% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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

The main impact of a 150 basis-point (1.50 percentage-point) rise in United States interest rates together with oil at $180 a barrel on Colombia is a large drop in GDP of 0.93% by Q13. This is a model impulse response versus baseline, not a forecast. Equities soften 1.54% by Q11. The three-year CPI impulse is +2.25 percentage points.

Demand and trade. Private investment / the cost of capital falls 3.42% by Q9; the trade balance (net exports — this model does not split imports from exports) improves to +2.91% in Q4; government debt falls 0.94% by Q20; government spending rises 0.75% by Q5; the same direction shows up in household consumption.

Labour. Real wages rises 1.12% by Q11; employment falls 0.77% by Q18; unemployment rises by +0.08 percentage points in Q15.

Prices. Firms' marginal cost falls 0.54% by Q14; CPI inflation rises 0.41 percentage points by Q2; domestic inflation rises 0.29 percentage points by Q2.

Policy rates and the government curve. Bond prices (higher discount rates) cheapen 6.24% by Q5; 2-year bond prices cheapen 2.76% by Q2; 10-year bond prices rally 2.64% by Q14; 5-year bond prices cheapen 2.35% by Q1; the same direction shows up in 30-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. The real exchange rate shows a real appreciation (a stronger home currency), peaking at -23.40% in Q4; versus the dollar the home currency is stronger versus the dollar (-22.43% in Q4); the NEER prints a trade-weighted appreciation (+22.21% in Q4).

Equities and risk. Global VIX moves to 22.0 in Q8 (baseline 15); Tobin's Q (the value of installed capital) falls 2.39% by Q9; equity prices / financial conditions falls 1.54% by Q11.

Housing and credit. House prices fall 1.01% by Q18; house prices and bank credit are close to unchanged.

Commodities. Gold prices moves to $2377 in Q10; the energy price index moves to $160 a barrel in Q4; the food price index moves to 110.7 in Q8; other published commodity prices stay near their baselines.

Sectors and capital. Manufacturing output rises 5.43% by Q4; services output falls 0.56% by Q13; the capital stock falls 0.20% by Q20.

By Q20, GDP is still -0.45% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

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
