# Units

These files are impulse responses versus a model baseline, not forecasts and not market data. The solver is not included.

## Frozen signs

- `RER` increase = real depreciation (home currency weaker). Decrease = real appreciation.
- `CPI_3yr_pp` = sum of quarterly `pi_cpi` over Q1–Q12 (percentage points). Not an annualized rate and not the CPI peak.

## Series (26)

| Key | Name | Unit |
|---|---|---|
| `Y` | GDP | pct_dev_from_baseline |
| `C` | Consumption | pct_dev_from_baseline |
| `pi_cpi` | CPI Inflation | pp_dev |
| `i` | Policy Rate | pp_dev |
| `RER` | Real exchange rate | pct_dev_from_baseline |
| `P_H` | House Prices | pct_dev_from_baseline |
| `Q_B` | Bond Price | pct_dev_from_baseline |
| `equity` | Equity Index | pct_dev_from_baseline |
| `y2` | Govt 2Y Yield | pp_dev |
| `y5` | Govt 5Y Yield | pp_dev |
| `y10` | Govt 10Y Yield | pp_dev |
| `N` | Employment | pct_dev_from_baseline |
| `w` | Real Wages | pct_dev_from_baseline |
| `I` | Investment | pct_dev_from_baseline |
| `K` | Capital Stock | pct_dev_from_baseline |
| `Q` | Tobin's Q | pct_dev_from_baseline |
| `G` | Gov Spending | pct_dev_from_baseline |
| `B` | Gov Debt | pct_dev_from_baseline |
| `NX` | Net Exports | pct_dev_from_baseline |
| `pi` | Domestic Infl. | pp_dev |
| `mc` | Marginal Cost | pct_dev_from_baseline |
| `unemployment` | Unemployment | pp_dev |
| `credit_supply` | Bank Credit | pct_dev_from_baseline |
| `lending_spread` | Credit Spread | pp_dev |
| `gdp_services` | Services GDP | pct_dev_from_baseline |
| `gdp_manufacturing` | Manuf. GDP | pct_dev_from_baseline |

## Shock inputs (active treatment only)

| Field | Unit | Neutral / not a shock |
|---|---|---|
| `monetary` | bp deviation by ISO2 | 0 |
| `oil` | USD/bbl level | 80 |
| `metals` | supply fraction | 0 |
| `housing` | price-level fraction by ISO2 | 0 |
| `fiscal` | GDP fraction by ISO2 | 0 |
| `tfp` | fraction by ISO2 | 0 |
| `risk_premium` | bp | 0 |
| `vix` | index | 15 (active only if > 16) |
| `bank_equity` | fraction by ISO2 | 0 |
| `sovereign_spread` | bp by ISO2 | 0 |
| `bilateral_tariffs` | rate 0–0.60 | none |

There is no DXY, gold, unemployment, or GDP-target input.
