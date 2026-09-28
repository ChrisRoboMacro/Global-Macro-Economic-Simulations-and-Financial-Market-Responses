# Global Macro Economic Simulations and Financial Market Responses

**This listing is ten sample simulations only.** Two licensed training packs are for sale: **1,000 simulations** and **10,000 simulations**. Same Layer A schema, more shocks. They are not in this sample.

**Contact Chris to discuss the full training set purchase options. [chris@robomacro.com](mailto:chris@robomacro.com)**

Ten named global macro simulations. Each one ships the full human-readable report — cover briefing, thirty country chapters with charts, and the unedited Q1–Q20 JSON for all 45 series — plus the same numbers as machine tables.

**Training records (Layer A) and human-readable reports, side by side:** [https://robomacro.com/GlobalMacroTrainingDataset/](https://robomacro.com/GlobalMacroTrainingDataset/)

The training product is `train.jsonl` / `eval.jsonl`: one JSON object per country (`record_id`, `shock`, `series`, `summary`, `qa_checks`). The typeset report is a reading companion. It is not what a model trains on.

GitHub cannot render HTML. There are no `.html` files in this repo on purpose — clicking one would show CSS, not the report. Each folder under `reports/` has a `README.md` GitHub will display. The document to send someone is the robomacro.com link.

**The model is not included.** There is no solver, no weights, and no coupler in this repository. Paths are impulse responses versus a model baseline, not forecasts and not market data.

The point is to improve how an AI reads economics: what happens after an event, and after events in combination. Example: an oil-price spike in Nigeria versus Spain. Or a stronger dollar together with an EM FX collapse, and what that does to Japanese house prices.

**Contact Chris to discuss the full training set purchase options. [chris@robomacro.com](mailto:chris@robomacro.com)**

Gated Hub copy (same sample): [CHRISrobomacro/global-macro-economic-simulations](https://huggingface.co/datasets/CHRISrobomacro/global-macro-economic-simulations)

| Split | Simulation | Training records | Human-readable report | Largest GDP move |
|---|---|---|---|---|
| train | US policy rate +200bp | <a href="https://robomacro.com/GlobalMacroTrainingDataset/us_hike_200/training.html" target="_blank" rel="noopener noreferrer">Layer A</a> | <a href="https://robomacro.com/GlobalMacroTrainingDataset/us_hike_200/" target="_blank" rel="noopener noreferrer">Report</a> | US -0.52% |
| train | US policy rate -200bp | <a href="https://robomacro.com/GlobalMacroTrainingDataset/us_cut_200/training.html" target="_blank" rel="noopener noreferrer">Layer A</a> | <a href="https://robomacro.com/GlobalMacroTrainingDataset/us_cut_200/" target="_blank" rel="noopener noreferrer">Report</a> | US +0.47% |
| train | Oil $200/bbl | <a href="https://robomacro.com/GlobalMacroTrainingDataset/oil_200/training.html" target="_blank" rel="noopener noreferrer">Layer A</a> | <a href="https://robomacro.com/GlobalMacroTrainingDataset/oil_200/" target="_blank" rel="noopener noreferrer">Report</a> | TR -5.82% |
| train | Oil $50/bbl | <a href="https://robomacro.com/GlobalMacroTrainingDataset/oil_50/training.html" target="_blank" rel="noopener noreferrer">Layer A</a> | <a href="https://robomacro.com/GlobalMacroTrainingDataset/oil_50/" target="_blank" rel="noopener noreferrer">Report</a> | SA -4.05% |
| train | Metals supply -20% | <a href="https://robomacro.com/GlobalMacroTrainingDataset/metals_cut_20/training.html" target="_blank" rel="noopener noreferrer">Layer A</a> | <a href="https://robomacro.com/GlobalMacroTrainingDataset/metals_cut_20/" target="_blank" rel="noopener noreferrer">Report</a> | CL +0.58% |
| train | UK housing -25% | <a href="https://robomacro.com/GlobalMacroTrainingDataset/uk_housing_25/training.html" target="_blank" rel="noopener noreferrer">Layer A</a> | <a href="https://robomacro.com/GlobalMacroTrainingDataset/uk_housing_25/" target="_blank" rel="noopener noreferrer">Report</a> | UK -3.27% |
| train | VIX 80 | <a href="https://robomacro.com/GlobalMacroTrainingDataset/vix_80/training.html" target="_blank" rel="noopener noreferrer">Layer A</a> | <a href="https://robomacro.com/GlobalMacroTrainingDataset/vix_80/" target="_blank" rel="noopener noreferrer">Report</a> | NL -2.26% |
| train | Risk premium +250bp | <a href="https://robomacro.com/GlobalMacroTrainingDataset/risk_250/training.html" target="_blank" rel="noopener noreferrer">Layer A</a> | <a href="https://robomacro.com/GlobalMacroTrainingDataset/risk_250/" target="_blank" rel="noopener noreferrer">Report</a> | AR -2.32% |
| eval | US-China tariffs 25% each way | <a href="https://robomacro.com/GlobalMacroTrainingDataset/tariff_us_cn_25/training.html" target="_blank" rel="noopener noreferrer">Layer A</a> | <a href="https://robomacro.com/GlobalMacroTrainingDataset/tariff_us_cn_25/" target="_blank" rel="noopener noreferrer">Report</a> | CN -0.51% |
| eval | Oil $180 and US +150bp | <a href="https://robomacro.com/GlobalMacroTrainingDataset/oil180_us150/training.html" target="_blank" rel="noopener noreferrer">Layer A</a> | <a href="https://robomacro.com/GlobalMacroTrainingDataset/oil180_us150/" target="_blank" rel="noopener noreferrer">Report</a> | TR -4.96% |

Each machine row is one `(shock, country)`: the active treatment, units, Q1–Q20 paths for 45 series (GDP, CPI, policy rates, the yield curve, bond prices, equities, VIX, housing, NEER/USD, labour, credit, energy/metals/food/gas/copper/wheat/gold), locked summary, QA flags.

| Split | Simulations | Country rows | File |
|---|---|---|---|
| train | 8 | 240 | `train.jsonl` |
| eval | 2 | 60 | `eval.jsonl` |

## Also here

- `UNITS.md` — series names and units (`RER`, `CPI_3yr_pp`)
- `catalog.json` — the ten active treatments
- `train_qa.jsonl` / `eval_qa.jsonl` — short questions grounded in the numbers
- `tool_use_examples.jsonl` — three treatment → summary traces

## License

Evaluation only. See `LICENSE.md`. No training, no redistribution. A paid invoice is required to train on the 1,000- or 10,000-scenario packs. Paths are model IRFs versus baseline and are not investment advice.
