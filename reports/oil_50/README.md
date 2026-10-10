# Global Macro Economic Simulations and Financial Market Responses

v6 · IRF · evaluation

**Open the typeset report (this is the document):** https://robomacro.com/GlobalMacroTrainingDataset/oil_50/

GitHub and Hugging Face show `.html` as source code. That is not the report. Read it on robomacro.com, or keep scrolling this page.

## What's the impact of Oil $50/bbl?

Oil at $50 a barrel. Every path is a model impulse response versus baseline, not a forecast and not financial advice.

### Summary

This note traces the model response to oil at $50 a barrel. Every path is an impulse response versus an unchanged baseline — not a forecast of what will happen in the world and not a reading of market data. The chapters that follow are already sorted by the size of the GDP response.

Saudi Arabia takes the largest GDP move on this path. GDP contracts by 4.05% versus baseline by Q11 — a first-order GDP response. Equities soften 16.10%, and the three-year CPI impulse is -2.21 percentage points. The move shows up first in private investment, then in government debt and the trade balance. That is the main adjustment: a change in financial conditions and real income, then the usual lag into activity and prices. It is the conditional elasticity to the shock that was switched on, not a prediction that this path will be realised.

Spillovers are not a carbon copy of that first path. Norway contracts by 2.25% versus baseline by Q4 — a first-order GDP response. Equities soften 4.68%. The move shows up first in private investment, then in the trade balance and government spending. Russia contracts by 1.93% versus baseline by Q4 — a first-order GDP response. Equities soften 3.04%, and the three-year CPI impulse is -1.60 percentage points. The move shows up first in private investment, then in the trade balance and government spending. Argentina expands by 0.98% versus baseline by Q13 — a first-order GDP response. Equities firm 1.70%, and the three-year CPI impulse is -0.64 percentage points. The move shows up first in private investment, then in government debt and the trade balance. The contrast is the point: an oil importer does not print the same GDP sign as an oil exporter.

Turkey expands by 0.96% versus baseline by Q11 — a first-order GDP response. Equities firm 1.88%, and the three-year CPI impulse is -0.91 percentage points. The move shows up first in private investment, then in the trade balance and government debt.

For the lead economy, Saudi Arabia, the financial backdrop looks like this. On the government curve, benchmark bond prices rally 2.54% by Q5, and unused tenors stay in the background rather than getting a sentence each; the NEER prints a trade-weighted depreciation (-0.63% in Q9). Treat those as the financial backdrop, not as extra shocks, unless they appear in the active treatment.

Read GDP as percent of baseline GDP: −0.52 is minus half a percent, never −52%. A 200 basis-point move is 2.00 percentage points on the policy rate. CPI over three years is the sum of twelve quarterly impulses, not an annualised rate. A rising real exchange rate is a real depreciation — a weaker, more competitive home currency.

The remaining economies are smaller spillovers, written in the same order in the chapters that follow. Each chapter is a desk note, not a catalog of every series. This material is a model-based summary and is not financial advice.


![SA GDP](charts/global_SA_Y.png)

![NO GDP](charts/global_NO_Y.png)

![RU GDP](charts/global_RU_Y.png)

![AR GDP](charts/global_AR_Y.png)

![US Equity Index](charts/global_US_equity.png)

![US Policy Rate](charts/global_US_i.png)

## SA — Saudi Arabia

The main impact of oil at $50 a barrel on Saudi Arabia is a large drop in GDP of 4.05% by Q11. This is a model impulse response versus baseline, not a forecast. Equities soften 16.10% by Q12. The three-year CPI impulse is -2.21 percentage points.

Demand and trade. Private investment falls 11.19% by Q11; government debt falls 9.46% by Q20; the trade balance (net exports — this model does not split imports from exports) softens to -7.42% in Q4; household consumption falls 2.69% by Q12; related moves also show up in government spending.

Labour. Real wages fall 6.07% by Q20; employment falls 4.38% by Q15; unemployment rises by +1.60 percentage points in Q14.

Prices. Firms' marginal cost falls 2.42% by Q11; CPI inflation falls 0.21 percentage points by Q4; domestic inflation falls 0.15 percentage points by Q4.

Policy rates and the government curve. Benchmark bond prices rally 2.54% by Q5; 10-year bond prices cheapen 0.98% by Q14; 5-year bond prices cheapen 0.86% by Q15; 2-year bond prices rally 0.79% by Q2; related moves also show up in 30-year bond prices, the local policy rate, 3-month government yields; the rest of the government curve moves less.

Exchange rates. The NEER prints a trade-weighted depreciation (-0.63% in Q9); the home currency is weaker versus the dollar (+0.48% in Q16); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.28% in Q11.

Equities and risk. Equity prices fall 16.10% by Q12; Tobin's Q (the value of installed capital) falls 7.83% by Q11; the VIX (global equity-implied volatility) stays close to baseline.

Housing and credit. House prices fall 6.16% by Q20; bank equity falls 1.14% by Q16; bank credit supply falls 0.96% by Q16.

Commodities. The energy price moves to $55 a barrel in Q4; the gas price moves to $3.17 per mmBtu in Q4; the food price index moves to 95.4 in Q9; gold prices move to $2065 in Q4; other published commodity prices stay within 3% of their baselines.

Sectors and capital. Services output falls 1.78% by Q11; the capital stock falls 0.98% by Q20; manufacturing output falls 0.43% by Q12.

By Q20, GDP is still -3.24% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/SA_Y.png)

![CPI Inflation](charts/SA_pi_cpi.png)

![Equity Index](charts/SA_equity.png)

![Gold Price](charts/SA_P_gold.png)

![Metals Price](charts/SA_P_metals.png)

![Copper Price](charts/SA_P_copper.png)

![Wheat Price](charts/SA_P_wheat.png)

![Food Price](charts/SA_P_food.png)

![Energy Price](charts/SA_P_energy.png)

![VIX](charts/SA_vix.png)

![Investment](charts/SA_I.png)

![Gov Debt](charts/SA_B.png)

[Q1–Q20 JSON for Saudi Arabia](numbers/SA.json)

## NO — Norway

The main impact of oil at $50 a barrel on Norway is a large drop in GDP of 2.25% by Q4. This is a model impulse response versus baseline, not a forecast. Equities soften 4.68% by Q4.

Demand and trade. Private investment falls 5.43% by Q2; the trade balance (net exports — this model does not split imports from exports) softens to -4.22% in Q4; government spending falls 1.62% by Q4; household consumption falls 1.31% by Q11; related moves also show up in government debt.

Labour. Real wages fall 2.34% by Q20; employment falls 2.30% by Q18; unemployment rises by +1.60 percentage points in Q17.

Prices. Firms' marginal cost falls 1.34% by Q4; CPI inflation falls 0.08 percentage points by Q2; domestic inflation falls 0.05 percentage points by Q2.

Policy rates and the government curve. 30-year bond prices rally 8.71% by Q1; 10-year bond prices rally 7.56% by Q4; benchmark bond prices rally 6.56% by Q10; 5-year bond prices rally 4.54% by Q6; related moves also show up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. The NEER prints a trade-weighted depreciation (-12.84% in Q6); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +12.63% in Q6; the home currency is weaker versus the dollar (+12.46% in Q6).

Equities and risk. Equity prices fall 4.68% by Q4; Tobin's Q (the value of installed capital) falls 3.80% by Q2; the VIX (global equity-implied volatility) stays close to baseline.

Housing and credit. House prices fall 2.85% by Q20; bank equity falls 0.95% by Q16; bank credit supply falls 0.75% by Q16.

Commodities. The energy price moves to $55 a barrel in Q4; the gas price moves to $3.17 per mmBtu in Q4; the food price index moves to 95.4 in Q9; gold prices move to $2065 in Q4; other published commodity prices stay within 3% of their baselines.

Sectors and capital. Manufacturing output falls 3.75% by Q6; services output falls 1.29% by Q4; the capital stock falls 0.44% by Q20.

By Q20, GDP is still -1.85% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/NO_Y.png)

![CPI Inflation](charts/NO_pi_cpi.png)

![Equity Index](charts/NO_equity.png)

![Gold Price](charts/NO_P_gold.png)

![Metals Price](charts/NO_P_metals.png)

![Copper Price](charts/NO_P_copper.png)

![Wheat Price](charts/NO_P_wheat.png)

![Food Price](charts/NO_P_food.png)

![Energy Price](charts/NO_P_energy.png)

![VIX](charts/NO_vix.png)

![NEER](charts/NO_NEER.png)

![Real Exchange Rate](charts/NO_RER.png)

[Q1–Q20 JSON for Norway](numbers/NO.json)

## RU — Russia

The main impact of oil at $50 a barrel on Russia is a large drop in GDP of 1.93% by Q4. This is a model impulse response versus baseline, not a forecast. Equities soften 3.04% by Q3. The three-year CPI impulse is -1.60 percentage points.

Demand and trade. Private investment falls 4.74% by Q2; the trade balance (net exports — this model does not split imports from exports) softens to -4.38% in Q4; government spending falls 1.14% by Q4; household consumption falls 1.06% by Q5; related moves also show up in government debt.

Labour. Real wages fall 3.86% by Q20; employment falls 1.62% by Q12; unemployment rises by +0.62 percentage points in Q9.

Prices. Firms' marginal cost falls 1.15% by Q4; CPI inflation falls 0.18 percentage points by Q4; domestic inflation falls 0.13 percentage points by Q4.

Policy rates and the government curve. 10-year bond prices rally 3.66% by Q2; 30-year bond prices rally 3.38% by Q1; 5-year bond prices rally 2.91% by Q3; benchmark bond prices rally 2.82% by Q7; related moves also show up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. The NEER prints a trade-weighted depreciation (-6.67% in Q5); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +5.81% in Q5; the home currency is weaker versus the dollar (+5.64% in Q5).

Equities and risk. Tobin's Q (the value of installed capital) falls 3.32% by Q2; equity prices fall 3.04% by Q3; the VIX (global equity-implied volatility) stays close to baseline.

Housing and credit. House prices fall 2.02% by Q16; bank equity falls 0.54% by Q16; bank credit supply falls 0.47% by Q16.

Commodities. The energy price moves to $55 a barrel in Q4; the gas price moves to $3.17 per mmBtu in Q4; the food price index moves to 95.4 in Q9; gold prices move to $2065 in Q4; other published commodity prices stay within 3% of their baselines.

Sectors and capital. Manufacturing output falls 1.63% by Q5; services output falls 1.06% by Q4; the capital stock falls 0.29% by Q20.

By Q20, GDP is still -0.81% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/RU_Y.png)

![CPI Inflation](charts/RU_pi_cpi.png)

![Equity Index](charts/RU_equity.png)

![Gold Price](charts/RU_P_gold.png)

![Metals Price](charts/RU_P_metals.png)

![Copper Price](charts/RU_P_copper.png)

![Wheat Price](charts/RU_P_wheat.png)

![Food Price](charts/RU_P_food.png)

![Energy Price](charts/RU_P_energy.png)

![VIX](charts/RU_vix.png)

![NEER](charts/RU_NEER.png)

![Real Exchange Rate](charts/RU_RER.png)

[Q1–Q20 JSON for Russia](numbers/RU.json)

## AR — Argentina

The main impact of oil at $50 a barrel on Argentina is a large rise in GDP of 0.98% by Q13. This is a model impulse response versus baseline, not a forecast. Equities firm 1.70% by Q11. The three-year CPI impulse is -0.64 percentage points.

Demand and trade. Private investment rises 2.40% by Q10; government debt rises 0.79% by Q20; the trade balance (net exports — this model does not split imports from exports) softens to -0.63% in Q9; household consumption rises 0.50% by Q13; related moves also show up in government spending.

Labour. Real wages rise 1.56% by Q20; employment rises 0.88% by Q17; unemployment eases by -0.25 percentage points in Q15.

Prices. Firms' marginal cost rises 0.59% by Q13; CPI inflation falls 0.16 percentage points by Q3; domestic inflation falls 0.11 percentage points by Q3.

Policy rates and the government curve. 5-year bond prices cheapen 1.77% by Q10; benchmark bond prices rally 1.64% by Q4; 10-year bond prices cheapen 1.32% by Q9; 2-year bond prices cheapen 1.11% by Q14; related moves also show up in 30-year bond prices, the local policy rate, 3-month government yields; the rest of the government curve moves less.

Exchange rates. The NEER prints a trade-weighted appreciation (+1.18% in Q10); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.89% in Q12; the home currency is stronger versus the dollar (-0.84% in Q10).

Equities and risk. Equity prices rise 1.70% by Q11; Tobin's Q (the value of installed capital) rises 1.68% by Q10; the VIX (global equity-implied volatility) stays close to baseline.

Housing and credit. House prices rise 1.02% by Q18; bank credit is close to unchanged.

Commodities. The energy price moves to $55 a barrel in Q4; the gas price moves to $3.17 per mmBtu in Q4; the food price index moves to 95.4 in Q9; gold prices move to $2065 in Q4; other published commodity prices stay within 3% of their baselines.

Sectors and capital. Manufacturing output rises 0.82% by Q11; services output rises 0.56% by Q13; the capital stock rises 0.15% by Q20.

By Q20, GDP is still +0.40% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/AR_Y.png)

![CPI Inflation](charts/AR_pi_cpi.png)

![Equity Index](charts/AR_equity.png)

![Gold Price](charts/AR_P_gold.png)

![Metals Price](charts/AR_P_metals.png)

![Copper Price](charts/AR_P_copper.png)

![Wheat Price](charts/AR_P_wheat.png)

![Food Price](charts/AR_P_food.png)

![Energy Price](charts/AR_P_energy.png)

![VIX](charts/AR_vix.png)

![Gas Price](charts/AR_P_gas.png)

![Investment](charts/AR_I.png)

[Q1–Q20 JSON for Argentina](numbers/AR.json)

## TR — Turkey

The main impact of oil at $50 a barrel on Turkey is a large rise in GDP of 0.96% by Q11. This is a model impulse response versus baseline, not a forecast. Equities firm 1.88% by Q9. The three-year CPI impulse is -0.91 percentage points.

Demand and trade. Private investment rises 3.09% by Q7; the trade balance (net exports — this model does not split imports from exports) improves to +1.20% in Q4; government debt rises 1.12% by Q20; household consumption rises 0.56% by Q12; related moves also show up in government spending.

Labour. Real wages rise 1.43% by Q20; employment rises 0.94% by Q16; unemployment eases by -0.26 percentage points in Q14.

Prices. Firms' marginal cost rises 0.59% by Q11; CPI inflation falls 0.16 percentage points by Q3; domestic inflation falls 0.11 percentage points by Q3.

Policy rates and the government curve. Benchmark bond prices rally 2.09% by Q4; 5-year bond prices cheapen 1.41% by Q12; 10-year bond prices cheapen 1.39% by Q11; 30-year bond prices cheapen 0.99% by Q11; related moves also show up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. The NEER prints a trade-weighted appreciation (+2.10% in Q12); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -1.85% in Q12; the home currency is stronger versus the dollar (-1.78% in Q10).

Equities and risk. Tobin's Q (the value of installed capital) rises 2.16% by Q7; equity prices rise 1.88% by Q9; the VIX (global equity-implied volatility) stays close to baseline.

Housing and credit. House prices rise 1.31% by Q17; bank credit is close to unchanged.

Commodities. The energy price moves to $55 a barrel in Q4; the gas price moves to $3.17 per mmBtu in Q4; the food price index moves to 95.4 in Q9; gold prices move to $2065 in Q4; other published commodity prices stay within 3% of their baselines.

Sectors and capital. Manufacturing output rises 1.34% by Q10; services output rises 0.58% by Q11; the capital stock rises 0.22% by Q20.

By Q20, GDP is still +0.38% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/TR_Y.png)

![CPI Inflation](charts/TR_pi_cpi.png)

![Equity Index](charts/TR_equity.png)

![Gold Price](charts/TR_P_gold.png)

![Metals Price](charts/TR_P_metals.png)

![Copper Price](charts/TR_P_copper.png)

![Wheat Price](charts/TR_P_wheat.png)

![Food Price](charts/TR_P_food.png)

![Energy Price](charts/TR_P_energy.png)

![VIX](charts/TR_vix.png)

![Gas Price](charts/TR_P_gas.png)

![Investment](charts/TR_I.png)

[Q1–Q20 JSON for Turkey](numbers/TR.json)

## NG — Nigeria

The main impact of oil at $50 a barrel on Nigeria is a large drop in GDP of 0.82% by Q3. This is a model impulse response versus baseline, not a forecast. Equities soften 0.99% by Q3. The three-year CPI impulse is -1.52 percentage points.

Demand and trade. The trade balance (net exports — this model does not split imports from exports) softens to -2.37% in Q4; private investment falls 1.81% by Q2; government debt falls 1.33% by Q11; household consumption falls 0.46% by Q4; related moves also show up in government spending.

Labour. Real wages fall 1.32% by Q14; employment falls 0.49% by Q8; unemployment stays close to baseline.

Prices. Firms' marginal cost falls 0.49% by Q3; CPI inflation falls 0.20 percentage points by Q4; domestic inflation falls 0.14 percentage points by Q4.

Policy rates and the government curve. Benchmark bond prices rally 1.93% by Q6; 5-year bond prices rally 1.56% by Q1; 2-year bond prices rally 1.27% by Q3; 10-year bond prices rally 0.97% by Q1; related moves also show up in the local policy rate, 3-month government yields, 2-year government yields; the rest of the government curve moves less.

Exchange rates. The real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +2.58% in Q5; the NEER prints a trade-weighted depreciation (-2.46% in Q5); the home currency is weaker versus the dollar (+2.40% in Q5).

Equities and risk. Tobin's Q (the value of installed capital) falls 1.27% by Q2; equity prices fall 0.99% by Q3; the VIX (global equity-implied volatility) stays close to baseline.

Housing and credit. House prices fall 0.55% by Q8; bank credit supply falls 0.36% by Q16; bank equity falls 0.20% by Q16; lending spreads rise 0.05 percentage points by Q16.

Commodities. The energy price moves to $55 a barrel in Q4; the gas price moves to $3.17 per mmBtu in Q4; the food price index moves to 95.4 in Q9; gold prices move to $2065 in Q4; other published commodity prices stay within 3% of their baselines.

Sectors and capital. Manufacturing output falls 0.60% by Q5; services output falls 0.41% by Q3; the capital stock stays close to baseline.

The GDP response has mostly faded by Q10 (Q20 is still +0.24%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/NG_Y.png)

![CPI Inflation](charts/NG_pi_cpi.png)

![Equity Index](charts/NG_equity.png)

![Gold Price](charts/NG_P_gold.png)

![Metals Price](charts/NG_P_metals.png)

![Copper Price](charts/NG_P_copper.png)

![Wheat Price](charts/NG_P_wheat.png)

![Food Price](charts/NG_P_food.png)

![Energy Price](charts/NG_P_energy.png)

![VIX](charts/NG_vix.png)

![Gas Price](charts/NG_P_gas.png)

![Real Exchange Rate](charts/NG_RER.png)

[Q1–Q20 JSON for Nigeria](numbers/NG.json)

## IN — India

The main impact of oil at $50 a barrel on India is a large rise in GDP of 0.81% by Q12. This is a model impulse response versus baseline, not a forecast. Equities firm 2.34% by Q10. The three-year CPI impulse is -1.03 percentage points.

Demand and trade. Private investment rises 3.02% by Q7; government debt rises 1.65% by Q20; the trade balance (net exports — this model does not split imports from exports) improves to +1.23% in Q4; household consumption rises 0.50% by Q12; related moves also show up in government spending.

Labour. Real wages rise 0.98% by Q20; employment rises 0.74% by Q18; unemployment eases by -0.11 percentage points in Q14.

Prices. Firms' marginal cost rises 0.50% by Q12; CPI inflation falls 0.18 percentage points by Q3; domestic inflation falls 0.13 percentage points by Q3.

Policy rates and the government curve. Benchmark bond prices rally 3.73% by Q5; 10-year bond prices cheapen 1.83% by Q13; 5-year bond prices cheapen 1.60% by Q15; 30-year bond prices cheapen 1.36% by Q13; related moves also show up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. The NEER prints a trade-weighted appreciation (+1.83% in Q15); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -1.33% in Q16; the home currency is stronger versus the dollar (-1.09% in Q13).

Equities and risk. Equity prices rise 2.34% by Q10; Tobin's Q (the value of installed capital) rises 2.11% by Q7; the VIX (global equity-implied volatility) stays close to baseline.

Housing and credit. House prices rise 1.18% by Q18; bank credit is close to unchanged.

Commodities. The energy price moves to $55 a barrel in Q4; the gas price moves to $3.17 per mmBtu in Q4; the food price index moves to 95.4 in Q9; gold prices move to $2065 in Q4; other published commodity prices stay within 3% of their baselines.

Sectors and capital. Manufacturing output rises 1.00% by Q11; services output rises 0.44% by Q12; the capital stock rises 0.21% by Q20.

By Q20, GDP is still +0.45% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/IN_Y.png)

![CPI Inflation](charts/IN_pi_cpi.png)

![Equity Index](charts/IN_equity.png)

![Gold Price](charts/IN_P_gold.png)

![Metals Price](charts/IN_P_metals.png)

![Copper Price](charts/IN_P_copper.png)

![Wheat Price](charts/IN_P_wheat.png)

![Food Price](charts/IN_P_food.png)

![Energy Price](charts/IN_P_energy.png)

![VIX](charts/IN_vix.png)

![Bond Price (7y)](charts/IN_Q_B.png)

![Gas Price](charts/IN_P_gas.png)

[Q1–Q20 JSON for India](numbers/IN.json)

## KR — South Korea

The main impact of oil at $50 a barrel on South Korea is a large rise in GDP of 0.68% by Q5. This is a model impulse response versus baseline, not a forecast. Equities firm 2.10% by Q5. The three-year CPI impulse is -0.94 percentage points.

Demand and trade. Private investment rises 2.66% by Q5; the trade balance (net exports — this model does not split imports from exports) improves to +1.50% in Q4; government debt rises 0.49% by Q20; household consumption rises 0.46% by Q5; related moves also show up in government spending.

Labour. Employment rises 0.66% by Q13; real wages rise 0.64% by Q20; unemployment eases by -0.26 percentage points in Q11.

Prices. Firms' marginal cost rises 0.43% by Q5; CPI inflation falls 0.17 percentage points by Q2; domestic inflation falls 0.12 percentage points by Q2.

Policy rates and the government curve. Benchmark bond prices rally 2.20% by Q5; 10-year bond prices cheapen 1.53% by Q13; 30-year bond prices cheapen 1.30% by Q12; 5-year bond prices cheapen 1.17% by Q15; related moves also show up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. The home currency is stronger versus the dollar (-2.58% in Q5); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -2.41% in Q4; the NEER prints a trade-weighted appreciation (+2.35% in Q4).

Equities and risk. Equity prices rise 2.10% by Q5; Tobin's Q (the value of installed capital) rises 1.86% by Q5; the VIX (global equity-implied volatility) stays close to baseline.

Housing and credit. House prices rise 0.85% by Q18; bank credit is close to unchanged.

Commodities. The energy price moves to $55 a barrel in Q4; the gas price moves to $3.17 per mmBtu in Q4; the food price index moves to 95.4 in Q9; gold prices move to $2065 in Q4; other published commodity prices stay within 3% of their baselines.

Sectors and capital. Manufacturing output rises 1.76% by Q4; services output rises 0.41% by Q5; the capital stock rises 0.17% by Q20.

By Q20, GDP is still +0.32% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/KR_Y.png)

![CPI Inflation](charts/KR_pi_cpi.png)

![Equity Index](charts/KR_equity.png)

![Gold Price](charts/KR_P_gold.png)

![Metals Price](charts/KR_P_metals.png)

![Copper Price](charts/KR_P_copper.png)

![Wheat Price](charts/KR_P_wheat.png)

![Food Price](charts/KR_P_food.png)

![Energy Price](charts/KR_P_energy.png)

![VIX](charts/KR_vix.png)

![Gas Price](charts/KR_P_gas.png)

![Investment](charts/KR_I.png)

[Q1–Q20 JSON for South Korea](numbers/KR.json)

## JP — Japan

The main impact of oil at $50 a barrel on Japan is a large rise in GDP of 0.58% by Q4. This is a model impulse response versus baseline, not a forecast. Equities firm 1.85% by Q4. The three-year CPI impulse is -0.91 percentage points.

Demand and trade. Private investment rises 1.85% by Q4; the trade balance (net exports — this model does not split imports from exports) improves to +1.18% in Q4; household consumption rises 0.41% by Q5; government debt rises 0.20% by Q20; related moves also show up in government spending.

Labour. Employment rises 0.55% by Q9; real wages fall 0.47% by Q14; unemployment eases by -0.30 percentage points in Q9.

Prices. Firms' marginal cost rises 0.37% by Q4; CPI inflation falls 0.19 percentage points by Q3; domestic inflation falls 0.13 percentage points by Q3.

Policy rates and the government curve. Benchmark bond prices rally 0.97% by Q5; 30-year bond prices cheapen 0.37% by Q20; 5-year bond prices rally 0.33% by Q2; 10-year bond prices rally 0.25% by Q1; related moves also show up in 2-year bond prices, the local policy rate, 3-month government yields; the rest of the government curve barely moves.

Exchange rates. The home currency is stronger versus the dollar (-3.27% in Q5); the NEER prints a trade-weighted appreciation (+3.20% in Q5); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -3.09% in Q5.

Equities and risk. Equity prices rise 1.85% by Q4; Tobin's Q (the value of installed capital) rises 1.29% by Q4; the VIX (global equity-implied volatility) stays close to baseline.

Housing and credit. House prices rise 0.62% by Q20; bank equity rises 0.09% by Q16; bank credit is close to unchanged.

Commodities. The energy price moves to $55 a barrel in Q4; the gas price moves to $3.17 per mmBtu in Q4; the food price index moves to 95.4 in Q9; gold prices move to $2065 in Q4; other published commodity prices stay within 3% of their baselines.

Sectors and capital. Manufacturing output rises 1.75% by Q4; services output rises 0.40% by Q4; the capital stock rises 0.14% by Q20.

By Q20, GDP is still +0.27% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/JP_Y.png)

![CPI Inflation](charts/JP_pi_cpi.png)

![Equity Index](charts/JP_equity.png)

![Gold Price](charts/JP_P_gold.png)

![Metals Price](charts/JP_P_metals.png)

![Copper Price](charts/JP_P_copper.png)

![Wheat Price](charts/JP_P_wheat.png)

![Food Price](charts/JP_P_food.png)

![Energy Price](charts/JP_P_energy.png)

![VIX](charts/JP_vix.png)

![Gas Price](charts/JP_P_gas.png)

![vs USD](charts/JP_USD.png)

[Q1–Q20 JSON for Japan](numbers/JP.json)

## CA — Canada

The main impact of oil at $50 a barrel on Canada is a large drop in GDP of 0.55% by Q4. This is a model impulse response versus baseline, not a forecast. Equities soften 1.19% by Q3. The three-year CPI impulse is -0.43 percentage points.

Demand and trade. The trade balance (net exports — this model does not split imports from exports) softens to -1.46% in Q4; private investment falls 1.01% by Q2; household consumption falls 0.34% by Q5; government spending falls 0.29% by Q5; related moves also show up in government debt.

Labour. Real wages fall 0.64% by Q19; employment falls 0.51% by Q7; unemployment rises by +0.30 percentage points in Q8.

Prices. Firms' marginal cost falls 0.33% by Q4; CPI inflation falls 0.10 percentage points by Q2; domestic inflation falls 0.07 percentage points by Q2.

Policy rates and the government curve. Benchmark bond prices rally 3.62% by Q6; 5-year bond prices rally 1.40% by Q1; 10-year bond prices rally 1.35% by Q1; 30-year bond prices rally 1.16% by Q1; related moves also show up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. The real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +11.37% in Q4; the NEER prints a trade-weighted depreciation (-11.24% in Q4); the home currency is weaker versus the dollar (+11.21% in Q4).

Equities and risk. Equity prices fall 1.19% by Q3; Tobin's Q (the value of installed capital) falls 0.71% by Q2; the VIX (global equity-implied volatility) stays close to baseline.

Housing and credit. House prices fall 0.34% by Q13; bank equity falls 0.21% by Q15; bank credit supply falls 0.16% by Q15.

Commodities. The energy price moves to $55 a barrel in Q4; the gas price moves to $3.17 per mmBtu in Q4; the food price index moves to 95.4 in Q9; gold prices move to $2065 in Q4; other published commodity prices stay within 3% of their baselines.

Sectors and capital. Manufacturing output falls 3.06% by Q4; services output falls 0.38% by Q4; the capital stock stays close to baseline.

By Q20, GDP is still -0.14% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/CA_Y.png)

![CPI Inflation](charts/CA_pi_cpi.png)

![Equity Index](charts/CA_equity.png)

![Gold Price](charts/CA_P_gold.png)

![Metals Price](charts/CA_P_metals.png)

![Copper Price](charts/CA_P_copper.png)

![Wheat Price](charts/CA_P_wheat.png)

![Food Price](charts/CA_P_food.png)

![Energy Price](charts/CA_P_energy.png)

![VIX](charts/CA_vix.png)

![Real Exchange Rate](charts/CA_RER.png)

![NEER](charts/CA_NEER.png)

[Q1–Q20 JSON for Canada](numbers/CA.json)

## ZA — South Africa

The main impact of oil at $50 a barrel on South Africa is a large rise in GDP of 0.52% by Q12. This is a model impulse response versus baseline, not a forecast. Equities firm 2.25% by Q10. The three-year CPI impulse is -0.73 percentage points.

Demand and trade. Private investment rises 2.02% by Q6; the trade balance (net exports — this model does not split imports from exports) improves to +0.67% in Q4; government debt rises 0.52% by Q20; household consumption rises 0.30% by Q12; related moves also show up in government spending.

Labour. Employment rises 0.56% by Q15; real wages rise 0.50% by Q20; unemployment eases by -0.14 percentage points in Q14.

Prices. Firms' marginal cost rises 0.32% by Q11; CPI inflation falls 0.13 percentage points by Q2; domestic inflation falls 0.09 percentage points by Q2.

Policy rates and the government curve. Benchmark bond prices rally 2.23% by Q5; 10-year bond prices cheapen 1.00% by Q15; 30-year bond prices cheapen 0.87% by Q14; 2-year bond prices rally 0.84% by Q2; related moves also show up in 5-year bond prices, the local policy rate, 3-month government yields; the rest of the government curve moves less.

Exchange rates. The home currency is stronger versus the dollar (-1.28% in Q4); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -1.11% in Q4; the NEER prints a trade-weighted appreciation (+0.67% in Q3).

Equities and risk. Equity prices rise 2.25% by Q10; Tobin's Q (the value of installed capital) rises 1.42% by Q6; the VIX (global equity-implied volatility) stays close to baseline.

Housing and credit. House prices rise 0.78% by Q18; bank credit is close to unchanged.

Commodities. The energy price moves to $55 a barrel in Q4; the gas price moves to $3.17 per mmBtu in Q4; the food price index moves to 95.4 in Q9; gold prices move to $2065 in Q4; other published commodity prices stay within 3% of their baselines.

Sectors and capital. Manufacturing output rises 0.85% by Q4; services output rises 0.33% by Q12; the capital stock rises 0.14% by Q20.

By Q20, GDP is still +0.28% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/ZA_Y.png)

![CPI Inflation](charts/ZA_pi_cpi.png)

![Equity Index](charts/ZA_equity.png)

![Gold Price](charts/ZA_P_gold.png)

![Metals Price](charts/ZA_P_metals.png)

![Copper Price](charts/ZA_P_copper.png)

![Wheat Price](charts/ZA_P_wheat.png)

![Food Price](charts/ZA_P_food.png)

![Energy Price](charts/ZA_P_energy.png)

![VIX](charts/ZA_vix.png)

![Gas Price](charts/ZA_P_gas.png)

![Bond Price (7y)](charts/ZA_Q_B.png)

[Q1–Q20 JSON for South Africa](numbers/ZA.json)

## IT — Italy

The main impact of oil at $50 a barrel on Italy is a large rise in GDP of 0.49% by Q5. This is a model impulse response versus baseline, not a forecast. Equities firm 1.20% by Q5. The three-year CPI impulse is -0.99 percentage points.

Demand and trade. Private investment rises 2.16% by Q5; the trade balance (net exports — this model does not split imports from exports) improves to +0.89% in Q4; household consumption rises 0.30% by Q4; government spending falls 0.11% by Q5; government debt stays close to baseline.

Labour. Employment rises 0.52% by Q14; real wages fall 0.36% by Q12; unemployment eases by -0.19 percentage points in Q11.

Prices. Firms' marginal cost rises 0.31% by Q5; CPI inflation falls 0.20 percentage points by Q2; domestic inflation falls 0.14 percentage points by Q2.

Policy rates and the government curve. Benchmark bond prices rally 3.28% by Q6; 10-year bond prices cheapen 0.97% by Q19; 5-year bond prices rally 0.94% by Q1; 30-year bond prices cheapen 0.91% by Q17; related moves also show up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. The home currency is stronger versus the dollar (-2.02% in Q4); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -1.85% in Q4; the NEER prints a trade-weighted appreciation (+1.26% in Q4).

Equities and risk. Tobin's Q (the value of installed capital) rises 1.52% by Q5; equity prices rise 1.20% by Q5; the VIX (global equity-implied volatility) stays close to baseline.

Housing and credit. House prices rise 0.66% by Q19; bank credit is close to unchanged.

Commodities. The energy price moves to $55 a barrel in Q4; the gas price moves to $3.17 per mmBtu in Q4; the food price index moves to 95.4 in Q9; gold prices move to $2065 in Q4; other published commodity prices stay within 3% of their baselines.

Sectors and capital. Manufacturing output rises 1.21% by Q4; services output rises 0.36% by Q5; the capital stock rises 0.15% by Q20.

By Q20, GDP is still +0.28% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/IT_Y.png)

![CPI Inflation](charts/IT_pi_cpi.png)

![Equity Index](charts/IT_equity.png)

![Gold Price](charts/IT_P_gold.png)

![Metals Price](charts/IT_P_metals.png)

![Copper Price](charts/IT_P_copper.png)

![Wheat Price](charts/IT_P_wheat.png)

![Food Price](charts/IT_P_food.png)

![Energy Price](charts/IT_P_energy.png)

![VIX](charts/IT_vix.png)

![Gas Price](charts/IT_P_gas.png)

![Bond Price (7y)](charts/IT_Q_B.png)

[Q1–Q20 JSON for Italy](numbers/IT.json)

## BR — Brazil

The main impact of oil at $50 a barrel on Brazil is a large rise in GDP of 0.49% by Q14. This is a model impulse response versus baseline, not a forecast. Equities firm 1.01% by Q12. The three-year CPI impulse is -0.80 percentage points.

Demand and trade. Private investment rises 1.65% by Q10; the trade balance (net exports — this model does not split imports from exports) softens to -0.72% in Q5; household consumption rises 0.27% by Q15; government spending falls 0.21% by Q13; related moves also show up in government debt.

Labour. Employment rises 0.42% by Q19; real wages fall 0.34% by Q11; unemployment eases by -0.13 percentage points in Q17.

Prices. Firms' marginal cost rises 0.30% by Q14; CPI inflation falls 0.13 percentage points by Q3; domestic inflation falls 0.09 percentage points by Q3.

Policy rates and the government curve. Benchmark bond prices rally 3.36% by Q5; 2-year bond prices rally 1.26% by Q2; 10-year bond prices cheapen 1.16% by Q14; 5-year bond prices rally 1.12% by Q1; related moves also show up in 30-year bond prices, the local policy rate, 3-month government yields; the rest of the government curve moves less.

Exchange rates. The real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +2.13% in Q6; the home currency is weaker versus the dollar (+1.96% in Q6); the NEER prints a trade-weighted depreciation (-1.91% in Q6).

Equities and risk. Tobin's Q (the value of installed capital) rises 1.15% by Q10; equity prices rise 1.01% by Q12; the VIX (global equity-implied volatility) stays close to baseline.

Housing and credit. House prices rise 0.55% by Q20; bank credit is close to unchanged.

Commodities. The energy price moves to $55 a barrel in Q4; the gas price moves to $3.17 per mmBtu in Q4; the food price index moves to 95.4 in Q9; gold prices move to $2065 in Q4; other published commodity prices stay within 3% of their baselines.

Sectors and capital. Services output rises 0.32% by Q14; manufacturing output rises 0.18% by Q19; the capital stock rises 0.11% by Q20.

By Q20, GDP is still +0.30% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/BR_Y.png)

![CPI Inflation](charts/BR_pi_cpi.png)

![Equity Index](charts/BR_equity.png)

![Gold Price](charts/BR_P_gold.png)

![Metals Price](charts/BR_P_metals.png)

![Copper Price](charts/BR_P_copper.png)

![Wheat Price](charts/BR_P_wheat.png)

![Food Price](charts/BR_P_food.png)

![Energy Price](charts/BR_P_energy.png)

![VIX](charts/BR_vix.png)

![Gas Price](charts/BR_P_gas.png)

![Bond Price (7y)](charts/BR_Q_B.png)

[Q1–Q20 JSON for Brazil](numbers/BR.json)

## DE — Germany

The main impact of oil at $50 a barrel on Germany is a large rise in GDP of 0.48% by Q5. This is a model impulse response versus baseline, not a forecast. Equities firm 1.21% by Q5. The three-year CPI impulse is -1.03 percentage points.

Demand and trade. Private investment rises 2.12% by Q5; the trade balance (net exports — this model does not split imports from exports) improves to +0.88% in Q4; household consumption rises 0.31% by Q4; government spending falls 0.11% by Q5; related moves also show up in government debt.

Labour. Employment rises 0.48% by Q13; real wages fall 0.29% by Q10; unemployment eases by -0.27 percentage points in Q11.

Prices. Firms' marginal cost rises 0.30% by Q5; CPI inflation falls 0.22 percentage points by Q2; domestic inflation falls 0.16 percentage points by Q2.

Policy rates and the government curve. Benchmark bond prices rally 3.30% by Q6; 10-year bond prices cheapen 0.97% by Q19; 5-year bond prices rally 0.94% by Q1; 30-year bond prices cheapen 0.91% by Q17; related moves also show up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. The home currency is stronger versus the dollar (-1.70% in Q4); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -1.53% in Q4; the NEER prints a trade-weighted appreciation (+1.13% in Q4).

Equities and risk. Tobin's Q (the value of installed capital) rises 1.48% by Q5; equity prices rise 1.21% by Q5; the VIX (global equity-implied volatility) stays close to baseline.

Housing and credit. House prices rise 0.66% by Q19; bank credit is close to unchanged.

Commodities. The energy price moves to $55 a barrel in Q4; the gas price moves to $3.17 per mmBtu in Q4; the food price index moves to 95.4 in Q9; gold prices move to $2065 in Q4; other published commodity prices stay within 3% of their baselines.

Sectors and capital. Manufacturing output rises 1.26% by Q4; services output rises 0.33% by Q5; the capital stock rises 0.15% by Q20.

By Q20, GDP is still +0.28% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/DE_Y.png)

![CPI Inflation](charts/DE_pi_cpi.png)

![Equity Index](charts/DE_equity.png)

![Gold Price](charts/DE_P_gold.png)

![Metals Price](charts/DE_P_metals.png)

![Copper Price](charts/DE_P_copper.png)

![Wheat Price](charts/DE_P_wheat.png)

![Food Price](charts/DE_P_food.png)

![Energy Price](charts/DE_P_energy.png)

![VIX](charts/DE_vix.png)

![Gas Price](charts/DE_P_gas.png)

![Bond Price (7y)](charts/DE_Q_B.png)

[Q1–Q20 JSON for Germany](numbers/DE.json)

## CL — Chile

The main impact of oil at $50 a barrel on Chile is a large rise in GDP of 0.47% by Q11. This is a model impulse response versus baseline, not a forecast. Equities firm 1.30% by Q8. The three-year CPI impulse is -0.60 percentage points.

Demand and trade. Private investment rises 1.97% by Q6; the trade balance (net exports — this model does not split imports from exports) improves to +0.70% in Q5; government debt rises 0.49% by Q19; household consumption rises 0.29% by Q12; government spending stays close to baseline.

Labour. Real wages rise 0.51% by Q20; employment rises 0.50% by Q15; unemployment eases by -0.19 percentage points in Q14.

Prices. Firms' marginal cost rises 0.29% by Q11; CPI inflation falls 0.13 percentage points by Q2; domestic inflation falls 0.09 percentage points by Q2.

Policy rates and the government curve. Benchmark bond prices rally 2.25% by Q5; 10-year bond prices cheapen 1.05% by Q15; 30-year bond prices cheapen 0.97% by Q14; 2-year bond prices rally 0.85% by Q2; related moves also show up in 5-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. The home currency is stronger versus the dollar (-1.03% in Q4); the NEER prints a trade-weighted appreciation (+0.99% in Q4); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.87% in Q3.

Equities and risk. Tobin's Q (the value of installed capital) rises 1.38% by Q6; equity prices rise 1.30% by Q8; the VIX (global equity-implied volatility) stays close to baseline.

Housing and credit. House prices rise 0.73% by Q18; bank credit is close to unchanged.

Commodities. The energy price moves to $55 a barrel in Q4; the gas price moves to $3.17 per mmBtu in Q4; the food price index moves to 95.4 in Q9; gold prices move to $2065 in Q4; other published commodity prices stay within 3% of their baselines.

Sectors and capital. Manufacturing output rises 0.77% by Q4; services output rises 0.29% by Q11; the capital stock rises 0.14% by Q20.

By Q20, GDP is still +0.26% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/CL_Y.png)

![CPI Inflation](charts/CL_pi_cpi.png)

![Equity Index](charts/CL_equity.png)

![Gold Price](charts/CL_P_gold.png)

![Metals Price](charts/CL_P_metals.png)

![Copper Price](charts/CL_P_copper.png)

![Wheat Price](charts/CL_P_wheat.png)

![Food Price](charts/CL_P_food.png)

![Energy Price](charts/CL_P_energy.png)

![VIX](charts/CL_vix.png)

![Gas Price](charts/CL_P_gas.png)

![Bond Price (7y)](charts/CL_Q_B.png)

[Q1–Q20 JSON for Chile](numbers/CL.json)

## ES — Spain

The main impact of oil at $50 a barrel on Spain is a large rise in GDP of 0.47% by Q5. This is a model impulse response versus baseline, not a forecast. Equities firm 1.25% by Q5. The three-year CPI impulse is -0.88 percentage points.

Demand and trade. Private investment rises 2.09% by Q5; the trade balance (net exports — this model does not split imports from exports) improves to +0.88% in Q4; household consumption rises 0.30% by Q4; government spending falls 0.11% by Q5; government debt stays close to baseline.

Labour. Employment rises 0.48% by Q14; real wages fall 0.28% by Q11; unemployment eases by -0.18 percentage points in Q11.

Prices. Firms' marginal cost rises 0.30% by Q5; CPI inflation falls 0.18 percentage points by Q2; domestic inflation falls 0.12 percentage points by Q2.

Policy rates and the government curve. Benchmark bond prices rally 3.30% by Q6; 10-year bond prices cheapen 0.97% by Q19; 5-year bond prices rally 0.94% by Q1; 30-year bond prices cheapen 0.91% by Q17; related moves also show up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. The home currency is stronger versus the dollar (-1.68% in Q4); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -1.51% in Q4; the NEER prints a trade-weighted appreciation (+1.20% in Q4).

Equities and risk. Tobin's Q (the value of installed capital) rises 1.46% by Q5; equity prices rise 1.25% by Q5; the VIX (global equity-implied volatility) stays close to baseline.

Housing and credit. House prices rise 0.64% by Q19; bank credit is close to unchanged.

Commodities. The energy price moves to $55 a barrel in Q4; the gas price moves to $3.17 per mmBtu in Q4; the food price index moves to 95.4 in Q9; gold prices move to $2065 in Q4; other published commodity prices stay within 3% of their baselines.

Sectors and capital. Manufacturing output rises 1.04% by Q4; services output rises 0.35% by Q5; the capital stock rises 0.15% by Q20.

By Q20, GDP is still +0.28% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/ES_Y.png)

![CPI Inflation](charts/ES_pi_cpi.png)

![Equity Index](charts/ES_equity.png)

![Gold Price](charts/ES_P_gold.png)

![Metals Price](charts/ES_P_metals.png)

![Copper Price](charts/ES_P_copper.png)

![Wheat Price](charts/ES_P_wheat.png)

![Food Price](charts/ES_P_food.png)

![Energy Price](charts/ES_P_energy.png)

![VIX](charts/ES_vix.png)

![Gas Price](charts/ES_P_gas.png)

![Bond Price (7y)](charts/ES_Q_B.png)

[Q1–Q20 JSON for Spain](numbers/ES.json)

## TH — Thailand

The main impact of oil at $50 a barrel on Thailand is a large rise in GDP of 0.45% by Q4. This is a model impulse response versus baseline, not a forecast. Equities firm 1.44% by Q5. The three-year CPI impulse is -0.89 percentage points.

Demand and trade. Private investment rises 1.83% by Q5; government debt rises 0.72% by Q19; the trade balance (net exports — this model does not split imports from exports) improves to +0.65% in Q3; household consumption rises 0.33% by Q4; related moves also show up in government spending.

Labour. Employment rises 0.45% by Q12; real wages rise 0.38% by Q20; unemployment eases by -0.06 percentage points in Q10.

Prices. Firms' marginal cost rises 0.29% by Q4; CPI inflation falls 0.16 percentage points by Q3; domestic inflation falls 0.11 percentage points by Q3.

Policy rates and the government curve. Benchmark bond prices rally 1.41% by Q5; 10-year bond prices cheapen 1.00% by Q15; 30-year bond prices cheapen 0.90% by Q14; 5-year bond prices cheapen 0.74% by Q17; related moves also show up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. The home currency is stronger versus the dollar (-0.48% in Q4); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.33% in Q3; the NEER prints a trade-weighted depreciation (-0.31% in Q7).

Equities and risk. Equity prices rise 1.44% by Q5; Tobin's Q (the value of installed capital) rises 1.28% by Q5; the VIX (global equity-implied volatility) stays close to baseline.

Housing and credit. House prices rise 0.72% by Q16; bank credit is close to unchanged.

Commodities. The energy price moves to $55 a barrel in Q4; the gas price moves to $3.17 per mmBtu in Q4; the food price index moves to 95.4 in Q9; gold prices move to $2065 in Q4; other published commodity prices stay within 3% of their baselines.

Sectors and capital. Manufacturing output rises 0.97% by Q4; services output rises 0.25% by Q4; the capital stock rises 0.12% by Q20.

By Q20, GDP is still +0.21% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/TH_Y.png)

![CPI Inflation](charts/TH_pi_cpi.png)

![Equity Index](charts/TH_equity.png)

![Gold Price](charts/TH_P_gold.png)

![Metals Price](charts/TH_P_metals.png)

![Copper Price](charts/TH_P_copper.png)

![Wheat Price](charts/TH_P_wheat.png)

![Food Price](charts/TH_P_food.png)

![Energy Price](charts/TH_P_energy.png)

![VIX](charts/TH_vix.png)

![Gas Price](charts/TH_P_gas.png)

![Investment](charts/TH_I.png)

[Q1–Q20 JSON for Thailand](numbers/TH.json)

## PL — Poland

The main impact of oil at $50 a barrel on Poland is a large rise in GDP of 0.45% by Q10. This is a model impulse response versus baseline, not a forecast. Equities firm 1.11% by Q6. The three-year CPI impulse is -0.88 percentage points.

Demand and trade. Private investment rises 2.09% by Q5; the trade balance (net exports — this model does not split imports from exports) improves to +0.62% in Q4; household consumption rises 0.25% by Q4; government spending falls 0.09% by Q10; government debt stays close to baseline.

Labour. Employment rises 0.49% by Q15; real wages rise 0.29% by Q20; unemployment eases by -0.18 percentage points in Q13.

Prices. Firms' marginal cost rises 0.28% by Q10; CPI inflation falls 0.16 percentage points by Q2; domestic inflation falls 0.11 percentage points by Q2.

Policy rates and the government curve. Benchmark bond prices rally 2.41% by Q5; 10-year bond prices cheapen 1.03% by Q17; 5-year bond prices rally 0.98% by Q1; 30-year bond prices cheapen 0.98% by Q15; related moves also show up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. The home currency is stronger versus the dollar (-1.38% in Q4); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -1.23% in Q3; the NEER prints a trade-weighted appreciation (+0.84% in Q20).

Equities and risk. Tobin's Q (the value of installed capital) rises 1.47% by Q5; equity prices rise 1.11% by Q6; the VIX (global equity-implied volatility) stays close to baseline.

Housing and credit. House prices rise 0.65% by Q19; bank credit is close to unchanged.

Commodities. The energy price moves to $55 a barrel in Q4; the gas price moves to $3.17 per mmBtu in Q4; the food price index moves to 95.4 in Q9; gold prices move to $2065 in Q4; other published commodity prices stay within 3% of their baselines.

Sectors and capital. Manufacturing output rises 1.17% by Q4; services output rises 0.28% by Q10; the capital stock rises 0.15% by Q20.

By Q20, GDP is still +0.26% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/PL_Y.png)

![CPI Inflation](charts/PL_pi_cpi.png)

![Equity Index](charts/PL_equity.png)

![Gold Price](charts/PL_P_gold.png)

![Metals Price](charts/PL_P_metals.png)

![Copper Price](charts/PL_P_copper.png)

![Wheat Price](charts/PL_P_wheat.png)

![Food Price](charts/PL_P_food.png)

![Energy Price](charts/PL_P_energy.png)

![VIX](charts/PL_vix.png)

![Gas Price](charts/PL_P_gas.png)

![Bond Price (7y)](charts/PL_Q_B.png)

[Q1–Q20 JSON for Poland](numbers/PL.json)

## CN — China

The main impact of oil at $50 a barrel on China is a large rise in GDP of 0.45% by Q5. This is a model impulse response versus baseline, not a forecast. Equities firm 1.18% by Q5. The three-year CPI impulse is -0.94 percentage points.

Demand and trade. Private investment rises 1.58% by Q4; the trade balance (net exports — this model does not split imports from exports) improves to +0.89% in Q4; government debt rises 0.74% by Q20; household consumption rises 0.36% by Q5; related moves also show up in government spending.

Labour. Real wages rise 0.50% by Q20; employment rises 0.37% by Q14; unemployment eases by -0.12 percentage points in Q10.

Prices. Firms' marginal cost rises 0.28% by Q5; CPI inflation falls 0.20 percentage points by Q2; domestic inflation falls 0.14 percentage points by Q2.

Policy rates and the government curve. 10-year bond prices cheapen 1.55% by Q12; benchmark bond prices cheapen 1.47% by Q20; 5-year bond prices cheapen 1.20% by Q16; 30-year bond prices cheapen 1.09% by Q11; related moves also show up in 2-year bond prices, 2-year government yields, the local policy rate; the rest of the government curve moves less.

Exchange rates. The home currency is stronger versus the dollar (-0.78% in Q5); the NEER prints a trade-weighted appreciation (+0.70% in Q6); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.60% in Q5.

Equities and risk. Equity prices rise 1.18% by Q5; Tobin's Q (the value of installed capital) rises 1.10% by Q4; the VIX (global equity-implied volatility) stays close to baseline.

Housing and credit. House prices rise 0.58% by Q15; bank credit is close to unchanged.

Commodities. The energy price moves to $55 a barrel in Q4; the gas price moves to $3.17 per mmBtu in Q4; the food price index moves to 95.4 in Q9; gold prices move to $2065 in Q4; other published commodity prices stay within 3% of their baselines.

Sectors and capital. Manufacturing output rises 1.14% by Q4; services output rises 0.26% by Q5; the capital stock rises 0.10% by Q20.

By Q20, GDP is still +0.19% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/CN_Y.png)

![CPI Inflation](charts/CN_pi_cpi.png)

![Equity Index](charts/CN_equity.png)

![Gold Price](charts/CN_P_gold.png)

![Metals Price](charts/CN_P_metals.png)

![Copper Price](charts/CN_P_copper.png)

![Wheat Price](charts/CN_P_wheat.png)

![Food Price](charts/CN_P_food.png)

![Energy Price](charts/CN_P_energy.png)

![VIX](charts/CN_vix.png)

![Gas Price](charts/CN_P_gas.png)

![Investment](charts/CN_I.png)

[Q1–Q20 JSON for China](numbers/CN.json)

## ID — Indonesia

The main impact of oil at $50 a barrel on Indonesia is a large rise in GDP of 0.42% by Q13. This is a model impulse response versus baseline, not a forecast. Equities firm 0.93% by Q10. The three-year CPI impulse is -0.87 percentage points.

Demand and trade. Private investment rises 1.71% by Q8; government debt rises 0.70% by Q20; the trade balance (net exports — this model does not split imports from exports) improves to +0.31% in Q4; household consumption rises 0.25% by Q14; government spending stays close to baseline.

Labour. Employment rises 0.39% by Q18; real wages rise 0.37% by Q20; unemployment eases by -0.06 percentage points in Q15.

Prices. Firms' marginal cost rises 0.26% by Q13; CPI inflation falls 0.15 percentage points by Q3; domestic inflation falls 0.10 percentage points by Q3.

Policy rates and the government curve. Benchmark bond prices rally 2.15% by Q6; 10-year bond prices cheapen 1.06% by Q16; 30-year bond prices cheapen 0.90% by Q15; 5-year bond prices rally 0.85% by Q1; related moves also show up in 2-year bond prices, the local policy rate, 3-month government yields; the rest of the government curve moves less.

Exchange rates. The NEER prints a trade-weighted depreciation (-1.48% in Q5); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +1.25% in Q5; the home currency is weaker versus the dollar (+1.07% in Q4).

Equities and risk. Tobin's Q (the value of installed capital) rises 1.20% by Q8; equity prices rise 0.93% by Q10; the VIX (global equity-implied volatility) stays close to baseline.

Housing and credit. House prices rise 0.62% by Q18; bank credit is close to unchanged.

Commodities. The energy price moves to $55 a barrel in Q4; the gas price moves to $3.17 per mmBtu in Q4; the food price index moves to 95.4 in Q9; gold prices move to $2065 in Q4; other published commodity prices stay within 3% of their baselines.

Sectors and capital. Manufacturing output rises 0.31% by Q4; services output rises 0.21% by Q13; the capital stock rises 0.12% by Q20.

By Q20, GDP is still +0.26% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/ID_Y.png)

![CPI Inflation](charts/ID_pi_cpi.png)

![Equity Index](charts/ID_equity.png)

![Gold Price](charts/ID_P_gold.png)

![Metals Price](charts/ID_P_metals.png)

![Copper Price](charts/ID_P_copper.png)

![Wheat Price](charts/ID_P_wheat.png)

![Food Price](charts/ID_P_food.png)

![Energy Price](charts/ID_P_energy.png)

![VIX](charts/ID_vix.png)

![Gas Price](charts/ID_P_gas.png)

![Bond Price (7y)](charts/ID_Q_B.png)

[Q1–Q20 JSON for Indonesia](numbers/ID.json)

## FR — France

The main impact of oil at $50 a barrel on France is a large rise in GDP of 0.37% by Q5. This is a model impulse response versus baseline, not a forecast. Equities firm 1.12% by Q5. The three-year CPI impulse is -0.92 percentage points.

Demand and trade. Private investment rises 1.79% by Q6; the trade balance (net exports — this model does not split imports from exports) improves to +0.55% in Q4; government debt falls 0.35% by Q20; household consumption rises 0.23% by Q4; related moves also show up in government spending.

Labour. Employment rises 0.37% by Q15; real wages fall 0.34% by Q12; unemployment eases by -0.21 percentage points in Q12.

Prices. Firms' marginal cost rises 0.23% by Q5; CPI inflation falls 0.19 percentage points by Q2; domestic inflation falls 0.13 percentage points by Q2.

Policy rates and the government curve. Benchmark bond prices rally 3.30% by Q6; 10-year bond prices cheapen 0.97% by Q19; 5-year bond prices rally 0.94% by Q1; 30-year bond prices cheapen 0.91% by Q17; related moves also show up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. The home currency is stronger versus the dollar (-1.68% in Q4); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -1.51% in Q4; the NEER prints a trade-weighted appreciation (+0.79% in Q4).

Equities and risk. Tobin's Q (the value of installed capital) rises 1.25% by Q6; equity prices rise 1.12% by Q5; the VIX (global equity-implied volatility) stays close to baseline.

Housing and credit. House prices rise 0.53% by Q19; bank credit is close to unchanged.

Commodities. The energy price moves to $55 a barrel in Q4; the gas price moves to $3.17 per mmBtu in Q4; the food price index moves to 95.4 in Q9; gold prices move to $2065 in Q4; other published commodity prices stay within 3% of their baselines.

Sectors and capital. Manufacturing output rises 0.97% by Q4; services output rises 0.28% by Q5; the capital stock rises 0.13% by Q20.

By Q20, GDP is still +0.22% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/FR_Y.png)

![CPI Inflation](charts/FR_pi_cpi.png)

![Equity Index](charts/FR_equity.png)

![Gold Price](charts/FR_P_gold.png)

![Metals Price](charts/FR_P_metals.png)

![Copper Price](charts/FR_P_copper.png)

![Wheat Price](charts/FR_P_wheat.png)

![Food Price](charts/FR_P_food.png)

![Energy Price](charts/FR_P_energy.png)

![VIX](charts/FR_vix.png)

![Gas Price](charts/FR_P_gas.png)

![Bond Price (7y)](charts/FR_Q_B.png)

[Q1–Q20 JSON for France](numbers/FR.json)

## SE — Sweden

The main impact of oil at $50 a barrel on Sweden is a moderate rise in GDP of 0.28% by Q4. This is a model impulse response versus baseline, not a forecast. Equities firm 1.14% by Q5. The three-year CPI impulse is -0.87 percentage points.

Demand and trade. Private investment rises 1.54% by Q5; the trade balance (net exports — this model does not split imports from exports) improves to +0.60% in Q4; household consumption rises 0.19% by Q4; government debt falls 0.15% by Q19; government spending stays close to baseline.

Labour. Employment rises 0.28% by Q15; real wages fall 0.25% by Q11; unemployment eases by -0.16 percentage points in Q13.

Prices. Firms' marginal cost rises 0.18% by Q4; CPI inflation falls 0.16 percentage points by Q2; domestic inflation falls 0.11 percentage points by Q2.

Policy rates and the government curve. Benchmark bond prices rally 2.97% by Q6; 5-year bond prices rally 0.98% by Q1; 30-year bond prices cheapen 0.83% by Q17; 2-year bond prices rally 0.79% by Q3; related moves also show up in 10-year bond prices, the local policy rate, 3-month government yields; the rest of the government curve moves less.

Exchange rates. The NEER prints a trade-weighted appreciation (+1.56% in Q20); the home currency is stronger versus the dollar (-0.64% in Q6); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.54% in Q20.

Equities and risk. Equity prices rise 1.14% by Q5; Tobin's Q (the value of installed capital) rises 1.08% by Q5; the VIX (global equity-implied volatility) stays close to baseline.

Housing and credit. House prices rise 0.42% by Q19; bank credit is close to unchanged.

Commodities. The energy price moves to $55 a barrel in Q4; the gas price moves to $3.17 per mmBtu in Q4; the food price index moves to 95.4 in Q9; gold prices move to $2065 in Q4; other published commodity prices stay within 3% of their baselines.

Sectors and capital. Manufacturing output rises 0.74% by Q4; services output rises 0.20% by Q4; the capital stock rises 0.11% by Q20.

By Q20, GDP is still +0.18% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/SE_Y.png)

![CPI Inflation](charts/SE_pi_cpi.png)

![Equity Index](charts/SE_equity.png)

![Gold Price](charts/SE_P_gold.png)

![Metals Price](charts/SE_P_metals.png)

![Copper Price](charts/SE_P_copper.png)

![Wheat Price](charts/SE_P_wheat.png)

![Food Price](charts/SE_P_food.png)

![Energy Price](charts/SE_P_energy.png)

![VIX](charts/SE_vix.png)

![Gas Price](charts/SE_P_gas.png)

![Bond Price (7y)](charts/SE_Q_B.png)

[Q1–Q20 JSON for Sweden](numbers/SE.json)

## US — United States

The main impact of oil at $50 a barrel on the United States is a moderate rise in GDP of 0.25% by Q13. This is a model impulse response versus baseline, not a forecast. Equities firm 0.90% by Q11. The three-year CPI impulse is -0.86 percentage points.

Demand and trade. Private investment rises 1.15% by Q6; household consumption rises 0.16% by Q14; the trade balance, government spending, government debt stay close to baseline.

Labour. Real wages fall 0.35% by Q13; employment rises 0.28% by Q15; unemployment eases by -0.14 percentage points in Q16.

Prices. CPI inflation falls 0.16 percentage points by Q2; firms' marginal cost rises 0.16% by Q13; domestic inflation falls 0.11 percentage points by Q2.

Policy rates and the government curve. Benchmark bond prices rally 3.35% by Q5; 10-year bond prices cheapen 0.97% by Q14; 5-year bond prices cheapen 0.86% by Q15; 2-year bond prices rally 0.79% by Q2; related moves also show up in 30-year bond prices, the local policy rate, 3-month government yields; the rest of the government curve moves less.

Exchange rates. The NEER prints a trade-weighted appreciation (+2.22% in Q4); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -0.32% in Q20.

Equities and risk. Equity prices rise 0.90% by Q11; Tobin's Q (the value of installed capital) rises 0.80% by Q6; the VIX (global equity-implied volatility) stays close to baseline.

Housing and credit. House prices rise 0.28% by Q18; bank credit is close to unchanged.

Commodities. The energy price moves to $55 a barrel in Q4; the gas price moves to $3.17 per mmBtu in Q4; the food price index moves to 95.4 in Q9; gold prices move to $2065 in Q4; other published commodity prices stay within 3% of their baselines.

Sectors and capital. Manufacturing output rises 0.41% by Q4; services output rises 0.19% by Q13; the capital stock stays close to baseline.

By Q20, GDP is still +0.14% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/US_Y.png)

![CPI Inflation](charts/US_pi_cpi.png)

![Equity Index](charts/US_equity.png)

![Gold Price](charts/US_P_gold.png)

![Metals Price](charts/US_P_metals.png)

![Copper Price](charts/US_P_copper.png)

![Wheat Price](charts/US_P_wheat.png)

![Food Price](charts/US_P_food.png)

![Energy Price](charts/US_P_energy.png)

![VIX](charts/US_vix.png)

![Gas Price](charts/US_P_gas.png)

![Bond Price (7y)](charts/US_Q_B.png)

[Q1–Q20 JSON for United States](numbers/US.json)

## AU — Australia

The main impact of oil at $50 a barrel on Australia is a moderate rise in GDP of 0.24% by Q10. This is a model impulse response versus baseline, not a forecast. Equities firm 0.86% by Q6. The three-year CPI impulse is -0.67 percentage points.

Demand and trade. Private investment rises 1.17% by Q6; the trade balance (net exports — this model does not split imports from exports) improves to +0.31% in Q4; household consumption rises 0.17% by Q4; government debt rises 0.15% by Q20; government spending stays close to baseline.

Labour. Employment rises 0.28% by Q13; real wages fall 0.18% by Q11; unemployment eases by -0.14 percentage points in Q13.

Prices. Firms' marginal cost rises 0.15% by Q10; CPI inflation falls 0.13 percentage points by Q2; domestic inflation falls 0.09 percentage points by Q2.

Policy rates and the government curve. Benchmark bond prices rally 2.03% by Q5; 10-year bond prices cheapen 0.93% by Q15; 30-year bond prices cheapen 0.77% by Q14; 5-year bond prices cheapen 0.73% by Q17; related moves also show up in 2-year bond prices, the local policy rate, 3-month government yields; the rest of the government curve moves less.

Exchange rates. The home currency is stronger versus the dollar (-1.35% in Q5); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -1.18% in Q5; the NEER prints a trade-weighted appreciation (+0.80% in Q6).

Equities and risk. Equity prices rise 0.86% by Q6; Tobin's Q (the value of installed capital) rises 0.82% by Q6; the VIX (global equity-implied volatility) stays close to baseline.

Housing and credit. House prices rise 0.32% by Q18; bank credit is close to unchanged.

Commodities. The energy price moves to $55 a barrel in Q4; the gas price moves to $3.17 per mmBtu in Q4; the food price index moves to 95.4 in Q9; gold prices move to $2065 in Q4; other published commodity prices stay within 3% of their baselines.

Sectors and capital. Manufacturing output rises 0.75% by Q5; services output rises 0.17% by Q10; the capital stock stays close to baseline.

By Q20, GDP is still +0.13% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/AU_Y.png)

![CPI Inflation](charts/AU_pi_cpi.png)

![Equity Index](charts/AU_equity.png)

![Gold Price](charts/AU_P_gold.png)

![Metals Price](charts/AU_P_metals.png)

![Copper Price](charts/AU_P_copper.png)

![Wheat Price](charts/AU_P_wheat.png)

![Food Price](charts/AU_P_food.png)

![Energy Price](charts/AU_P_energy.png)

![VIX](charts/AU_vix.png)

![Gas Price](charts/AU_P_gas.png)

![Bond Price (7y)](charts/AU_Q_B.png)

[Q1–Q20 JSON for Australia](numbers/AU.json)

## CH — Switzerland

The main impact of oil at $50 a barrel on Switzerland is a moderate rise in GDP of 0.24% by Q5. This is a model impulse response versus baseline, not a forecast. Equities firm 1.20% by Q5. The three-year CPI impulse is -0.76 percentage points.

Demand and trade. Private investment rises 1.00% by Q6; the trade balance (net exports — this model does not split imports from exports) improves to +0.18% in Q3; household consumption rises 0.18% by Q5; government debt rises 0.13% by Q18; government spending stays close to baseline.

Labour. Real wages fall 0.33% by Q13; employment rises 0.24% by Q11; unemployment eases by -0.13 percentage points in Q11.

Prices. CPI inflation falls 0.15 percentage points by Q3; firms' marginal cost rises 0.15% by Q5; domestic inflation falls 0.11 percentage points by Q3.

Policy rates and the government curve. Benchmark bond prices rally 1.38% by Q6; 10-year bond prices cheapen 0.62% by Q17; 30-year bond prices cheapen 0.56% by Q15; 5-year bond prices cheapen 0.46% by Q19; related moves also show up in 2-year bond prices, the local policy rate, 3-month government yields; the rest of the government curve barely moves.

Exchange rates. The home currency is stronger versus the dollar (-1.43% in Q6); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -1.26% in Q6; the NEER prints a trade-weighted appreciation (+0.76% in Q7).

Equities and risk. Equity prices rise 1.20% by Q5; Tobin's Q (the value of installed capital) rises 0.70% by Q6; the VIX (global equity-implied volatility) stays close to baseline.

Housing and credit. House prices rise 0.32% by Q19; bank credit is close to unchanged.

Commodities. The energy price moves to $55 a barrel in Q4; the gas price moves to $3.17 per mmBtu in Q4; the food price index moves to 95.4 in Q9; gold prices move to $2065 in Q4; other published commodity prices stay within 3% of their baselines.

Sectors and capital. Manufacturing output rises 0.96% by Q5; services output rises 0.19% by Q5; the capital stock stays close to baseline.

By Q20, GDP is still +0.13% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/CH_Y.png)

![CPI Inflation](charts/CH_pi_cpi.png)

![Equity Index](charts/CH_equity.png)

![Gold Price](charts/CH_P_gold.png)

![Metals Price](charts/CH_P_metals.png)

![Copper Price](charts/CH_P_copper.png)

![Wheat Price](charts/CH_P_wheat.png)

![Food Price](charts/CH_P_food.png)

![Energy Price](charts/CH_P_energy.png)

![VIX](charts/CH_vix.png)

![Gas Price](charts/CH_P_gas.png)

![vs USD](charts/CH_USD.png)

[Q1–Q20 JSON for Switzerland](numbers/CH.json)

## CO — Colombia

The main impact of oil at $50 a barrel on Colombia is a moderate drop in GDP of 0.24% by Q3. This is a model impulse response versus baseline, not a forecast. Equities firm 0.35% by Q12. The three-year CPI impulse is -0.90 percentage points.

Demand and trade. The trade balance (net exports — this model does not split imports from exports) softens to -0.88% in Q4; private investment rises 0.84% by Q10; government spending falls 0.20% by Q6; government debt falls 0.16% by Q8; related moves also show up in household consumption.

Labour. Real wages fall 0.56% by Q13; employment falls 0.15% by Q6; unemployment stays close to baseline.

Prices. CPI inflation falls 0.14 percentage points by Q3; firms' marginal cost falls 0.13% by Q3; domestic inflation falls 0.10 percentage points by Q3.

Policy rates and the government curve. Benchmark bond prices rally 2.21% by Q5; 5-year bond prices rally 1.12% by Q1; 2-year bond prices rally 1.00% by Q3; 10-year bond prices cheapen 0.63% by Q16; related moves also show up in the local policy rate, 3-month government yields, 30-year bond prices; the rest of the government curve moves less.

Exchange rates. The real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +7.30% in Q4; the home currency is weaker versus the dollar (+7.13% in Q4); the NEER prints a trade-weighted depreciation (-6.89% in Q4).

Equities and risk. Tobin's Q (the value of installed capital) rises 0.59% by Q10; equity prices rise 0.35% by Q12; the VIX (global equity-implied volatility) stays close to baseline.

Housing and credit. House prices rise 0.17% by Q20; bank credit is close to unchanged.

Commodities. The energy price moves to $55 a barrel in Q4; the gas price moves to $3.17 per mmBtu in Q4; the food price index moves to 95.4 in Q9; gold prices move to $2065 in Q4; other published commodity prices stay within 3% of their baselines.

Sectors and capital. Manufacturing output falls 1.74% by Q4; services output falls 0.14% by Q3; the capital stock stays close to baseline.

The GDP response has mostly faded by Q8 (Q20 is still +0.09%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/CO_Y.png)

![CPI Inflation](charts/CO_pi_cpi.png)

![Equity Index](charts/CO_equity.png)

![Gold Price](charts/CO_P_gold.png)

![Metals Price](charts/CO_P_metals.png)

![Copper Price](charts/CO_P_copper.png)

![Wheat Price](charts/CO_P_wheat.png)

![Food Price](charts/CO_P_food.png)

![Energy Price](charts/CO_P_energy.png)

![VIX](charts/CO_vix.png)

![Real Exchange Rate](charts/CO_RER.png)

![vs USD](charts/CO_USD.png)

[Q1–Q20 JSON for Colombia](numbers/CO.json)

## MX — Mexico

The main impact of oil at $50 a barrel on Mexico is a moderate rise in GDP of 0.23% by Q14. This is a model impulse response versus baseline, not a forecast. Equities firm 0.50% by Q11. The three-year CPI impulse is -0.64 percentage points.

Demand and trade. Private investment rises 1.03% by Q9; the trade balance (net exports — this model does not split imports from exports) softens to -0.54% in Q4; government debt rises 0.25% by Q20; government spending falls 0.16% by Q9; related moves also show up in household consumption.

Labour. Real wages fall 0.29% by Q12; employment rises 0.19% by Q18; unemployment stays close to baseline.

Prices. Firms' marginal cost rises 0.15% by Q14; CPI inflation falls 0.10 percentage points by Q3; domestic inflation falls 0.07 percentage points by Q3.

Policy rates and the government curve. Benchmark bond prices rally 2.44% by Q5; 5-year bond prices rally 0.97% by Q1; 2-year bond prices rally 0.93% by Q2; 10-year bond prices cheapen 0.69% by Q16; related moves also show up in 30-year bond prices, the local policy rate, 3-month government yields; the rest of the government curve moves less.

Exchange rates. The NEER prints a trade-weighted depreciation (-6.07% in Q4); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +6.05% in Q4; the home currency is weaker versus the dollar (+5.88% in Q4).

Equities and risk. Tobin's Q (the value of installed capital) rises 0.72% by Q9; equity prices rise 0.50% by Q11; the VIX (global equity-implied volatility) stays close to baseline.

Housing and credit. House prices rise 0.30% by Q19; bank credit is close to unchanged.

Commodities. The energy price moves to $55 a barrel in Q4; the gas price moves to $3.17 per mmBtu in Q4; the food price index moves to 95.4 in Q9; gold prices move to $2065 in Q4; other published commodity prices stay within 3% of their baselines.

Sectors and capital. Manufacturing output falls 1.21% by Q4; services output rises 0.14% by Q14; the capital stock stays close to baseline.

By Q20, GDP is still +0.11% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/MX_Y.png)

![CPI Inflation](charts/MX_pi_cpi.png)

![Equity Index](charts/MX_equity.png)

![Gold Price](charts/MX_P_gold.png)

![Metals Price](charts/MX_P_metals.png)

![Copper Price](charts/MX_P_copper.png)

![Wheat Price](charts/MX_P_wheat.png)

![Food Price](charts/MX_P_food.png)

![Energy Price](charts/MX_P_energy.png)

![VIX](charts/MX_vix.png)

![NEER](charts/MX_NEER.png)

![Real Exchange Rate](charts/MX_RER.png)

[Q1–Q20 JSON for Mexico](numbers/MX.json)

## UK — United Kingdom

The main impact of oil at $50 a barrel on the United Kingdom is a moderate rise in GDP of 0.22% by Q5. This is a model impulse response versus baseline, not a forecast. Equities firm 0.84% by Q5. The three-year CPI impulse is -0.88 percentage points.

Demand and trade. Private investment rises 0.87% by Q6; the trade balance (net exports — this model does not split imports from exports) improves to +0.26% in Q4; household consumption rises 0.15% by Q5; government spending, government debt stay close to baseline.

Labour. Real wages fall 0.39% by Q13; employment rises 0.23% by Q10; unemployment eases by -0.12 percentage points in Q10.

Prices. CPI inflation falls 0.18 percentage points by Q3; firms' marginal cost rises 0.14% by Q5; domestic inflation falls 0.13 percentage points by Q3.

Policy rates and the government curve. Benchmark bond prices rally 1.12% by Q8; 30-year bond prices cheapen 0.51% by Q20; 5-year bond prices rally 0.45% by Q1; 10-year bond prices cheapen 0.32% by Q20; related moves also show up in 2-year bond prices, the local policy rate, 3-month government yields; the rest of the government curve barely moves.

Exchange rates. The NEER prints a trade-weighted appreciation (+1.88% in Q6); the home currency is stronger versus the dollar (-1.85% in Q5); the real exchange rate shows a real appreciation (a stronger home currency), peaking at -1.67% in Q5.

Equities and risk. Equity prices rise 0.84% by Q5; Tobin's Q (the value of installed capital) rises 0.61% by Q6; the VIX (global equity-implied volatility) stays close to baseline.

Housing and credit. House prices rise 0.27% by Q20; bank credit is close to unchanged.

Commodities. The energy price moves to $55 a barrel in Q4; the gas price moves to $3.17 per mmBtu in Q4; the food price index moves to 95.4 in Q9; gold prices move to $2065 in Q4; other published commodity prices stay within 3% of their baselines.

Sectors and capital. Manufacturing output rises 0.95% by Q5; services output rises 0.17% by Q5; the capital stock stays close to baseline.

By Q20, GDP is still +0.11% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/UK_Y.png)

![CPI Inflation](charts/UK_pi_cpi.png)

![Equity Index](charts/UK_equity.png)

![Gold Price](charts/UK_P_gold.png)

![Metals Price](charts/UK_P_metals.png)

![Copper Price](charts/UK_P_copper.png)

![Wheat Price](charts/UK_P_wheat.png)

![Food Price](charts/UK_P_food.png)

![Energy Price](charts/UK_P_energy.png)

![VIX](charts/UK_vix.png)

![Gas Price](charts/UK_P_gas.png)

![NEER](charts/UK_NEER.png)

[Q1–Q20 JSON for United Kingdom](numbers/UK.json)

## NL — Netherlands

The main impact of oil at $50 a barrel on the Netherlands is a moderate rise in GDP of 0.12% by Q13. This is a model impulse response versus baseline, not a forecast. Equities firm 0.48% by Q7. The three-year CPI impulse is -1.02 percentage points.

Demand and trade. Private investment rises 0.96% by Q6; the trade balance (net exports — this model does not split imports from exports) softens to -0.39% in Q5; household consumption, government spending, government debt stay close to baseline.

Labour. Real wages fall 0.48% by Q13; employment rises 0.11% by Q17; unemployment eases by -0.06 percentage points in Q15.

Prices. CPI inflation falls 0.21 percentage points by Q2; domestic inflation falls 0.15 percentage points by Q2; firms' marginal cost stays close to baseline.

Policy rates and the government curve. Benchmark bond prices rally 3.30% by Q6; 10-year bond prices cheapen 0.97% by Q19; 5-year bond prices rally 0.94% by Q1; 30-year bond prices cheapen 0.91% by Q17; related moves also show up in 2-year bond prices, the local policy rate, 3-month government yields.

Exchange rates. The home currency is weaker versus the dollar (+0.85% in Q18); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +0.69% in Q5; the NEER prints a trade-weighted depreciation (-0.55% in Q4).

Equities and risk. Tobin's Q (the value of installed capital) rises 0.67% by Q6; equity prices rise 0.48% by Q7; the VIX (global equity-implied volatility) stays close to baseline.

Housing and credit. House prices rise 0.20% by Q18; bank credit is close to unchanged.

Commodities. The energy price moves to $55 a barrel in Q4; the gas price moves to $3.17 per mmBtu in Q4; the food price index moves to 95.4 in Q9; gold prices move to $2065 in Q4; other published commodity prices stay within 3% of their baselines.

Sectors and capital. Manufacturing output rises 0.25% by Q4; services output rises 0.09% by Q13; the capital stock stays close to baseline.

By Q20, GDP is still +0.06% from baseline.

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/NL_Y.png)

![CPI Inflation](charts/NL_pi_cpi.png)

![Equity Index](charts/NL_equity.png)

![Gold Price](charts/NL_P_gold.png)

![Metals Price](charts/NL_P_metals.png)

![Copper Price](charts/NL_P_copper.png)

![Wheat Price](charts/NL_P_wheat.png)

![Food Price](charts/NL_P_food.png)

![Energy Price](charts/NL_P_energy.png)

![VIX](charts/NL_vix.png)

![Gas Price](charts/NL_P_gas.png)

![Bond Price (7y)](charts/NL_Q_B.png)

[Q1–Q20 JSON for Netherlands](numbers/NL.json)

## MY — Malaysia

The main impact of oil at $50 a barrel on Malaysia is a moderate drop in GDP of 0.10% by Q3. This is a model impulse response versus baseline, not a forecast. Equities soften 0.17% by Q20. The three-year CPI impulse is -0.59 percentage points.

Demand and trade. The trade balance (net exports — this model does not split imports from exports) softens to -0.66% in Q4; private investment rises 0.34% by Q8; government spending falls 0.16% by Q5; government debt falls 0.10% by Q9; household consumption stays close to baseline.

Labour. Real wages fall 0.37% by Q13; employment, unemployment stay close to baseline.

Prices. CPI inflation falls 0.14 percentage points by Q2; domestic inflation falls 0.10 percentage points by Q2; firms' marginal cost stays close to baseline.

Policy rates and the government curve. Benchmark bond prices rally 1.33% by Q6; 5-year bond prices rally 0.60% by Q1; 2-year bond prices rally 0.52% by Q3; 10-year bond prices rally 0.38% by Q1; related moves also show up in the local policy rate, 3-month government yields, 2-year government yields; the rest of the government curve barely moves.

Exchange rates. The NEER prints a trade-weighted depreciation (-3.35% in Q4); the real exchange rate shows a real depreciation (a weaker, more competitive home currency), peaking at +2.81% in Q4; the home currency is weaker versus the dollar (+2.64% in Q4).

Equities and risk. Tobin's Q (the value of installed capital) rises 0.24% by Q8; equity prices fall 0.17% by Q20; the VIX (global equity-implied volatility) stays close to baseline.

Housing and credit. House prices and bank credit are close to unchanged.

Commodities. The energy price moves to $55 a barrel in Q4; the gas price moves to $3.17 per mmBtu in Q4; the food price index moves to 95.4 in Q9; gold prices move to $2065 in Q4; other published commodity prices stay within 3% of their baselines.

Sectors and capital. Manufacturing output falls 0.21% by Q20; services output, the capital stock stay close to baseline.

The GDP response has mostly faded by Q10 (Q20 is still -0.03%).

These figures are model IRFs versus baseline, not forecasts and not financial advice.

![GDP](charts/MY_Y.png)

![CPI Inflation](charts/MY_pi_cpi.png)

![Equity Index](charts/MY_equity.png)

![Gold Price](charts/MY_P_gold.png)

![Metals Price](charts/MY_P_metals.png)

![Copper Price](charts/MY_P_copper.png)

![Wheat Price](charts/MY_P_wheat.png)

![Food Price](charts/MY_P_food.png)

![Energy Price](charts/MY_P_energy.png)

![VIX](charts/MY_vix.png)

![Gas Price](charts/MY_P_gas.png)

![NEER](charts/MY_NEER.png)

[Q1–Q20 JSON for Malaysia](numbers/MY.json)


---

These figures are model IRFs versus baseline, not forecasts and not financial advice.
