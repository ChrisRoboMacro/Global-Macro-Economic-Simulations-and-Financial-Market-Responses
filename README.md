# Global Macro Economic Simulations and Financial Market Responses

**This listing is ten sample simulations only.** Two licensed training packs, **1,000 simulations** and **10,000 simulations**, are for exclusive sale to one AI lab. Same training-record schema, more shocks. They are not in this sample.

**Contact Chris: [chris@robomacro.com](mailto:chris@robomacro.com)**

Ten named global macro simulations. Each one ships the full human-readable report — cover briefing, thirty country chapters with charts, and the unedited Q1–Q20 JSON for all 45 series — plus the same numbers as machine tables. Each human-readable report averages about 11,000 words.

**Training records and human-readable reports, side by side:** [https://robomacro.com/GlobalMacroTrainingDataset/](https://robomacro.com/GlobalMacroTrainingDataset/)

The training product is `train.jsonl` / `eval.jsonl`: one JSON object per country (`record_id`, `shock`, `series`, `summary`, `qa_checks`). The typeset report is a reading companion. It is not what a model trains on.

GitHub cannot render HTML. There are no `.html` files in this repo on purpose — clicking one would show CSS, not the report. Each folder under `reports/` has a `README.md` GitHub will display. The document to send someone is the robomacro.com link.

**The model is not included.** There is no solver, no weights, and no coupler in this repository. Paths are impulse responses versus a model baseline, not forecasts and not market data.

The point is to improve how an AI reads economics: what happens after an event, and after events in combination. Example: an oil-price spike in Nigeria versus Spain. Or a stronger dollar together with an EM FX collapse, and what that does to Japanese house prices.

**Contact Chris: [chris@robomacro.com](mailto:chris@robomacro.com)**

Gated Hub copy (same sample): [robomacro/global-macro-economic-simulations](https://huggingface.co/datasets/robomacro/global-macro-economic-simulations)

Blog: [The Macro Training Data Only One AI Lab Will Own](https://robomacro.com/blog/macro-training-data-one-ai-lab) · [Same Bet, Different Engine](https://robomacro.com/blog/why-ai-needs-synthetic-macro-data)

| Split | Simulation | Training records | Human-readable report | Largest GDP move |
|---|---|---|---|---|
| train | US policy rate +200bp | <a href="https://robomacro.com/GlobalMacroTrainingDataset/us_hike_200/training.html" target="_blank" rel="noopener noreferrer">Records</a> | <a href="https://robomacro.com/GlobalMacroTrainingDataset/us_hike_200/" target="_blank" rel="noopener noreferrer">Report</a> | US -0.52% |
| train | US policy rate -200bp | <a href="https://robomacro.com/GlobalMacroTrainingDataset/us_cut_200/training.html" target="_blank" rel="noopener noreferrer">Records</a> | <a href="https://robomacro.com/GlobalMacroTrainingDataset/us_cut_200/" target="_blank" rel="noopener noreferrer">Report</a> | US +0.47% |
| train | Oil $200/bbl | <a href="https://robomacro.com/GlobalMacroTrainingDataset/oil_200/training.html" target="_blank" rel="noopener noreferrer">Records</a> | <a href="https://robomacro.com/GlobalMacroTrainingDataset/oil_200/" target="_blank" rel="noopener noreferrer">Report</a> | TR -5.81% |
| train | Oil $50/bbl | <a href="https://robomacro.com/GlobalMacroTrainingDataset/oil_50/training.html" target="_blank" rel="noopener noreferrer">Records</a> | <a href="https://robomacro.com/GlobalMacroTrainingDataset/oil_50/" target="_blank" rel="noopener noreferrer">Report</a> | SA -4.05% |
| train | Metals supply -20% | <a href="https://robomacro.com/GlobalMacroTrainingDataset/metals_cut_20/training.html" target="_blank" rel="noopener noreferrer">Records</a> | <a href="https://robomacro.com/GlobalMacroTrainingDataset/metals_cut_20/" target="_blank" rel="noopener noreferrer">Report</a> | CL +0.58% |
| train | UK housing -25% | <a href="https://robomacro.com/GlobalMacroTrainingDataset/uk_housing_25/training.html" target="_blank" rel="noopener noreferrer">Records</a> | <a href="https://robomacro.com/GlobalMacroTrainingDataset/uk_housing_25/" target="_blank" rel="noopener noreferrer">Report</a> | UK -3.27% |
| train | VIX 80 | <a href="https://robomacro.com/GlobalMacroTrainingDataset/vix_80/training.html" target="_blank" rel="noopener noreferrer">Records</a> | <a href="https://robomacro.com/GlobalMacroTrainingDataset/vix_80/" target="_blank" rel="noopener noreferrer">Report</a> | NL -2.26% |
| train | Risk premium +250bp | <a href="https://robomacro.com/GlobalMacroTrainingDataset/risk_250/training.html" target="_blank" rel="noopener noreferrer">Records</a> | <a href="https://robomacro.com/GlobalMacroTrainingDataset/risk_250/" target="_blank" rel="noopener noreferrer">Report</a> | AR -2.32% |
| eval | US-China tariffs 25% each way | <a href="https://robomacro.com/GlobalMacroTrainingDataset/tariff_us_cn_25/training.html" target="_blank" rel="noopener noreferrer">Records</a> | <a href="https://robomacro.com/GlobalMacroTrainingDataset/tariff_us_cn_25/" target="_blank" rel="noopener noreferrer">Report</a> | CN -0.51% |
| eval | Oil $180 and US +150bp | <a href="https://robomacro.com/GlobalMacroTrainingDataset/oil180_us150/training.html" target="_blank" rel="noopener noreferrer">Records</a> | <a href="https://robomacro.com/GlobalMacroTrainingDataset/oil180_us150/" target="_blank" rel="noopener noreferrer">Report</a> | TR -4.96% |

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

## For AI labs

The **1,000-simulation** and **10,000-simulation** packs are for exclusive sale to one AI lab, under a licence separate from this sample.

What a pack contains, per simulation:

- **30 country records**, each with Q1–Q20 impulse-response paths for **45 series**: 37 country-specific and 8 global. 25 of them are market series: FX, government yields, bond prices, equities, bank equity, house prices, VIX and commodities.
- **Records written as JSON answers**: given a shock and a country, the structured answer a model should return (GDP peak and quarter, three-year CPI effect, equity peak, paths at Q4/Q8/Q12).
- **QA rows** grounded in the numbers, and **tool-use rows** that teach a model to call for a simulation instead of guessing it.
- A **human-readable report** of about 11,000 words.

Shocks come from the Global Macro Model v6.4: **12 shock types** (policy rates, oil, metals, housing, fiscal, productivity, tariffs, risk premia and more), and they stack, so packs cover combined scenarios, not just single shocks. Evaluation runs under a frozen, SHA-256-hashed eval spec, with a private 20-simulation held-out set (600 country rows) in which shocks located in six reserved countries never appear in anything a model trains on.

**Contact Chris: [chris@robomacro.com](mailto:chris@robomacro.com)**

## Related work

Chib, Tan and Zhang, *Learning the Macroeconomic Language* ([arXiv:2512.21031](https://arxiv.org/abs/2512.21031)), trained a transformer on DSGE-simulated US data and showed that theory-generated data helps a learner where real data is scarce. Our comparison of the two approaches: [Same Bet, Different Engine](https://robomacro.com/blog/why-ai-needs-synthetic-macro-data).

## License

This 10-simulation sample is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): you may use it for anything, including training and fine-tuning models, with credit to RoboMacro (robomacro.com). See `LICENSE.md`. The 1,000- and 10,000-simulation packs are not covered and are licensed separately. Paths are model impulse responses versus a baseline and are not investment advice.
