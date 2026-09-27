# Global Macro Economic Simulations and Financial Market Responses

This is a sample of our **1,000- and 10,000-scenario** economics dataset.

Ten named global macro simulations. Each one ships the full human-readable report — cover briefing, thirty country chapters with charts, and the unedited Q1–Q20 JSON for all 26 series — plus the same numbers as machine tables. Together that is about 60,000 words per simulation.

**Read the reports here (rendered HTML, not raw source):** [https://robomacro.com/GlobalMacroTrainingDataset/](https://robomacro.com/GlobalMacroTrainingDataset/)

This GitHub listing is the machine tables and a copy of the files. Open the robomacro.com pages to read the documents.

**The model is not included.** There is no solver, no weights, and no coupler in this repository. Paths are impulse responses versus a model baseline, not forecasts and not market data.

The point is to improve how an AI reads economics: what happens after an event, and after events in combination. Example: an oil-price spike in Nigeria versus Spain. Or a stronger dollar together with an EM FX collapse, and what that does to Japanese house prices.

**Contact for the full training dataset and pricing:** [licensing@robomacro.com](mailto:licensing@robomacro.com)

Gated Hub copy (same sample): [CHRISrobomacro/global-macro-economic-simulations](https://huggingface.co/datasets/CHRISrobomacro/global-macro-economic-simulations)

| Split | Simulation | Report | Largest GDP move |
|---|---|---|---|
| train | US policy rate +200bp | [https://robomacro.com/GlobalMacroTrainingDataset/us_hike_200/](https://robomacro.com/GlobalMacroTrainingDataset/us_hike_200/) | US -0.52% |
| train | US policy rate −200bp | [https://robomacro.com/GlobalMacroTrainingDataset/us_cut_200/](https://robomacro.com/GlobalMacroTrainingDataset/us_cut_200/) | US +0.47% |
| train | Oil $200/bbl | [https://robomacro.com/GlobalMacroTrainingDataset/oil_200/](https://robomacro.com/GlobalMacroTrainingDataset/oil_200/) | TR -5.14% |
| train | Oil $50/bbl | [https://robomacro.com/GlobalMacroTrainingDataset/oil_50/](https://robomacro.com/GlobalMacroTrainingDataset/oil_50/) | SA -1.06% |
| train | Metals supply −20% | [https://robomacro.com/GlobalMacroTrainingDataset/metals_cut_20/](https://robomacro.com/GlobalMacroTrainingDataset/metals_cut_20/) | CL +0.58% |
| train | UK housing −25% | [https://robomacro.com/GlobalMacroTrainingDataset/uk_housing_25/](https://robomacro.com/GlobalMacroTrainingDataset/uk_housing_25/) | UK -3.27% |
| train | VIX 80 | [https://robomacro.com/GlobalMacroTrainingDataset/vix_80/](https://robomacro.com/GlobalMacroTrainingDataset/vix_80/) | NL -2.25% |
| train | Risk premium +250bp | [https://robomacro.com/GlobalMacroTrainingDataset/risk_250/](https://robomacro.com/GlobalMacroTrainingDataset/risk_250/) | AR -2.32% |
| eval | US–China tariffs 25% each way | [https://robomacro.com/GlobalMacroTrainingDataset/tariff_us_cn_25/](https://robomacro.com/GlobalMacroTrainingDataset/tariff_us_cn_25/) | CN -0.51% |
| eval | Oil $180 and US +150bp | [https://robomacro.com/GlobalMacroTrainingDataset/oil180_us150/](https://robomacro.com/GlobalMacroTrainingDataset/oil180_us150/) | TR -4.20% |

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
