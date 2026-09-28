# Global Macro Economic Simulations and Financial Market Responses

This is a sample of our **1,000- and 10,000-scenario** economics dataset.

Ten named global macro simulations. Each one ships the full human-readable report — cover briefing, thirty country chapters with charts, and the unedited Q1–Q20 JSON for all 26 series — plus the same numbers as machine tables. Together that is about 60,000 words per simulation.

**Human-readable reports and raw simulation files, side by side:** [https://robomacro.com/GlobalMacroTrainingDataset/](https://robomacro.com/GlobalMacroTrainingDataset/)

GitHub cannot render HTML. There are no `.html` files in this repo on purpose — clicking one would show CSS, not the report. Each folder under `reports/` has a `README.md` GitHub will display. The document to send someone is the robomacro.com link.

**The model is not included.** There is no solver, no weights, and no coupler in this repository. Paths are impulse responses versus a model baseline, not forecasts and not market data.

The point is to improve how an AI reads economics: what happens after an event, and after events in combination. Example: an oil-price spike in Nigeria versus Spain. Or a stronger dollar together with an EM FX collapse, and what that does to Japanese house prices.

**Contact Chris to discuss the full training set purchase options.** [chris@robomacro.com](mailto:chris@robomacro.com)

Gated Hub copy (same sample): [CHRISrobomacro/global-macro-economic-simulations](https://huggingface.co/datasets/CHRISrobomacro/global-macro-economic-simulations)

| Split | Simulation | Human-readable report | Raw dataset | Largest GDP move |
|---|---|---|---|---|
| train | US policy rate +200bp | [Report](https://robomacro.com/GlobalMacroTrainingDataset/us_hike_200/) | [Raw JSON](https://robomacro.com/GlobalMacroTrainingDataset/us_hike_200/raw.html) | US -0.52% |
| train | US policy rate −200bp | [Report](https://robomacro.com/GlobalMacroTrainingDataset/us_cut_200/) | [Raw JSON](https://robomacro.com/GlobalMacroTrainingDataset/us_cut_200/raw.html) | US +0.47% |
| train | Oil $200/bbl | [Report](https://robomacro.com/GlobalMacroTrainingDataset/oil_200/) | [Raw JSON](https://robomacro.com/GlobalMacroTrainingDataset/oil_200/raw.html) | TR -5.14% |
| train | Oil $50/bbl | [Report](https://robomacro.com/GlobalMacroTrainingDataset/oil_50/) | [Raw JSON](https://robomacro.com/GlobalMacroTrainingDataset/oil_50/raw.html) | SA -1.06% |
| train | Metals supply −20% | [Report](https://robomacro.com/GlobalMacroTrainingDataset/metals_cut_20/) | [Raw JSON](https://robomacro.com/GlobalMacroTrainingDataset/metals_cut_20/raw.html) | CL +0.58% |
| train | UK housing −25% | [Report](https://robomacro.com/GlobalMacroTrainingDataset/uk_housing_25/) | [Raw JSON](https://robomacro.com/GlobalMacroTrainingDataset/uk_housing_25/raw.html) | UK -3.27% |
| train | VIX 80 | [Report](https://robomacro.com/GlobalMacroTrainingDataset/vix_80/) | [Raw JSON](https://robomacro.com/GlobalMacroTrainingDataset/vix_80/raw.html) | NL -2.25% |
| train | Risk premium +250bp | [Report](https://robomacro.com/GlobalMacroTrainingDataset/risk_250/) | [Raw JSON](https://robomacro.com/GlobalMacroTrainingDataset/risk_250/raw.html) | AR -2.32% |
| eval | US–China tariffs 25% each way | [Report](https://robomacro.com/GlobalMacroTrainingDataset/tariff_us_cn_25/) | [Raw JSON](https://robomacro.com/GlobalMacroTrainingDataset/tariff_us_cn_25/raw.html) | CN -0.51% |
| eval | Oil $180 and US +150bp | [Report](https://robomacro.com/GlobalMacroTrainingDataset/oil180_us150/) | [Raw JSON](https://robomacro.com/GlobalMacroTrainingDataset/oil180_us150/raw.html) | TR -4.20% |

Each machine row is one `(shock, country)`: the active treatment, units, Q1–Q20 paths for 26 series (GDP, CPI, policy rates, bonds, equities, housing, FX, labour, credit), locked summary, QA flags.

| Split | Simulations | Country rows | File |
|---|---|---|---|
| train | 8 | 240 | `train.jsonl` |
| eval | 2 | 60 | `eval.jsonl` |

## Also here

- `UNITS.md` — series names and units (`RER`, `CPI_3yr_pp`)
- `catalog.json` — the ten active treatments
- `train_qa.jsonl` / `eval_qa.jsonl` — short questions grounded in the numbers
- `tool_use_examples.jsonl` — three treatment → summary traces

## Limits

- IRF, not a forecast. Not financial advice.
- Euro-area policy-rate paths can sit at zero on a US-only rate shock.
- Equity is an output. There is no equity-price shock.
- Nigeria can print a GDP trough on an oil spike.

## License

Evaluation only. See `LICENSE.md`. No training, no redistribution. A paid invoice is required to train on the 1,000- or 10,000-scenario packs.
