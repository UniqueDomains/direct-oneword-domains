# Available .DIRECT One-Word Domains (16,465)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-16%2C465%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .direct one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **16,465 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 16,465 domains · **Median ask:** $20.88 · **High-demand under $2,500:** 0

**Last updated:** 2026-08-20
**Canonical page:** `https://unique.domains/domains/tld/direct`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/direct?utm_source=github&utm_medium=referral&utm_campaign=repo_direct_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./direct.csv">CSV</a> / <a href="./direct.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_direct_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_direct_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .DIRECT search](https://unique.domains/domains/tld/direct?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_direct_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .DIRECT search](https://unique.domains/domains/tld/direct?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_direct_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_direct_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .DIRECT one-word domain catalog.

### Files

- `direct.csv`, public CSV extract (1,000 rows)
- `direct.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/direct-oneword-domains/main/direct.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price | renewal_price | attractiveness | demand | length | registrar         |
| -------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------- |
| half.direct    | available | $19.99    | —             | high           | low    | 4      | name.com          |
| correct.direct | available | $19.99    | $50.99        | high           | low    | 7      | name.com          |
| axe.direct     | available | $19.99    | —             | medium         | low    | 3      | name.com          |
| fin.direct     | resell    | —         | —             | low            | low    | 3      | Dynadot Inc       |
| gal.direct     | premium   | $118.80   | $118.80       | medium         | low    | 3      | namesilo          |
| boy.direct     | available | $19.99    | —             | medium         | low    | 3      | name.com          |
| tea.direct     | resell    | —         | —             | medium         | medium | 3      | Edomains LLC      |
| mom.direct     | premium   | $118.80   | $118.80       | high           | low    | 3      | namesilo          |
| clv.direct     | available | $14.98    | $53.98        | medium         | low    | 3      | namecheap         |
| base.direct    | resell    | —         | —             | medium         | medium | 4      | Porkbun LLC       |
| NYC.direct     | premium   | $242      | $242          | high           | medium | 3      | namesilo          |
| clx.direct     | available | $14.98    | $53.98        | low            | low    | 3      | namecheap         |
| code.direct    | resell    | —         | —             | high           | medium | 4      | Sav.com, LLC - 45 |
| asia.direct    | premium   | $854      | $854          | high           | low    | 4      | namesilo          |
| cxl.direct     | available | $14.98    | $53.98        | low            | low    | 3      | namecheap         |
| data.direct    | resell    | —         | —             | medium         | medium | 4      | Sav.com, LLC      |
| asian.direct   | premium   | $123.75   | —             | high           | low    | 5      | name.com          |
| due.direct     | available | $19.99    | —             | high           | low    | 3      | name.com          |
| easy.direct    | resell    | —         | —             | high           | medium | 4      | Spaceship, Inc.   |
| cheap.direct   | premium   | $118.80   | $118.80       | high           | low    | 5      | namesilo          |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 16,465 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/direct?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_direct_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/direct?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_direct_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_direct_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection covers 11,593 one-word domain names on the .direct extension, drawn from common, easy-to-spell words such as feel, correct, sorry, great, quiet, and one. With a median ask near $25, most of these names are priced within reach of a single purchase rather than requiring negotiation. Because every entry is a single dictionary or everyday word, the list favors clarity and memorability over invented terms — useful whether you're shortlisting a name for a new brand or comparing entries for resale potential. Word length, common usage, and spelling simplicity are the main signals to weigh when comparing names within this set.

- 11,593 one-word .direct domains in this selection
- Median ask near $25 across the full list
- Everyday words like half.direct and out.direct
- Updated daily for current pricing and availability

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .DIRECT One-Word Domains*. Version 2026-08-20. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .DIRECT page](https://unique.domains/domains/tld/direct?utm_source=github&utm_medium=referral&utm_campaign=repo_direct_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_direct_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_direct_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_direct_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
