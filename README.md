# GEO Benchmarks — Open Quarterly Reports

> Open, reproducible benchmarks of AI visibility across ChatGPT, Perplexity, Claude and Gemini. Published quarterly by [AuraCite](https://auracite.de).

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

## What's in this repo?

Every quarter, we publish:

1. **Raw data** (CSV + JSON) — every AI engine response we scraped, anonymized where required
2. **Methodology** — exact prompts, engine versions, locales, time-windows
3. **Analysis reports** — Markdown + PDF with findings
4. **Reproducibility scripts** — Python notebooks to re-run any chart

## Why open-source?

Closed benchmarks are marketing. Open benchmarks are science. The GEO industry needs trustworthy baselines that anyone can verify.

## Latest Reports

| Quarter | Focus | Brands Scanned | Report |
|---------|-------|----------------|--------|
| Q2 2026 | GEO tool comparison (AuraCite vs Peec.ai vs Profound vs Search Atlas) | 4 | [reports/2026-Q2.md](reports/2026-Q2.md) |
| Q1 2026 | Top 100 SaaS brands AI visibility | 100 | [reports/2026-Q1.md](reports/2026-Q1.md) |

## Methodology

All reports follow the same methodology:

1. **Prompt Sets** — 10 standardized queries per brand (see [methodology/prompts.md](methodology/prompts.md))
2. **Engines** — ChatGPT (GPT-4o, GPT-5), Claude (Sonnet 4, Opus 4), Perplexity (Sonar Large), Gemini (2.0 Pro)
3. **Locales** — English (US), German (DE), Arabic (MENA)
4. **Sampling** — 3 runs per prompt, aggregated mean
5. **Metrics** — Mention rate, citation count, sentiment, source attribution, share of voice

Full methodology: [methodology/README.md](methodology/README.md)

## Reproduce any chart

```bash
git clone https://github.com/getauracite/geo-benchmarks
cd geo-benchmarks
pip install -r requirements.txt
jupyter notebook notebooks/2026-Q2.ipynb
```

## Citing

If you use this data in academic or commercial work, please cite:

```
AuraCite (2026). "GEO Benchmark Q2 2026: Comparative Analysis of Generative Engine Optimization Tools."
AuraCite Research. https://github.com/getauracite/geo-benchmarks
```

## Submit a brand

Want your brand included in the next benchmark? Open an issue with:
- Brand name
- Primary category
- 3 representative queries your customers ask

We include up to 100 new brands per quarter (selected by category balance).

## License

All data & reports licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — share and adapt freely with attribution.

## About AuraCite

[AuraCite](https://auracite.de) is the operating system for Generative Engine Optimization. We track how AI engines cite your brand — and help you optimize to win.

- 🌐 [auracite.de](https://auracite.de)
- 🐦 [@AuraCite](https://twitter.com/AuraCite)
- 📧 research@auracite.de

---

**⭐ Star this repo** to get notified of new quarterly benchmarks.
