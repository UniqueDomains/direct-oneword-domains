# Available .DIRECT One-Word Domains (11,591)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C591%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .direct one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,591 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,591 domains · **Median ask:** $28.00 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-11  
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

- `direct.csv` — public CSV extract (1,000 rows)
- `direct.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/direct-oneword-domains/main/direct.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar           |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------- |
| Iam.direct      | available | $53.98    | —             | 90             | 49     | 4      | namecheap           |
| agents.direct   | resell    | —         | —             | 56             | 50     | 6      | Dynadot Inc         |
| payments.direct | premium   | $123.75   | —             | 58             | 33     | 8      | name.com            |
| spaces.direct   | available | $19.99    | —             | 54             | 30     | 6      | name.com            |
| network.direct  | resell    | —         | —             | 72             | 47     | 7      | Porkbun LLC         |
| toys.direct     | premium   | $118.80   | $118.80       | 60             | 24     | 4      | namesilo            |
| popup.direct    | available | $19.99    | —             | 84             | 29     | 6      | name.com            |
| coins.direct    | resell    | —         | —             | 56             | 41     | 5      | Dynadot Inc         |
| coupons.direct  | premium   | $118.80   | $118.80       | 52             | 24     | 7      | namesilo            |
| pages.direct    | available | $19.99    | —             | 52             | 28     | 5      | name.com            |
| Trex.direct     | resell    | —         | —             | 80             | 24     | 5      | GoDaddy.com, LLC    |
| holidays.direct | premium   | $500      | —             | 78             | 23     | 8      | name.com            |
| KFC.direct      | available | $53.98    | —             | 74             | 27     | 3      | namecheap           |
| users.direct    | resell    | —         | —             | 54             | 18     | 5      | GoDaddy.com, LLC    |
| signs.direct    | premium   | $123.75   | —             | 64             | 22     | 5      | name.com            |
| systems.direct  | available | $19.99    | —             | 46             | 27     | 7      | name.com            |
| pins.direct     | resell    | —         | —             | 68             | 15     | 4      | united-domains GmbH |
| herbs.direct    | premium   | $123.75   | —             | 62             | 22     | 5      | name.com            |
| Keith.direct    | available | $53.98    | —             | 66             | 25     | 5      | namecheap           |
| laptops.direct  | premium   | $500      | —             | 56             | 8      | 7      | name.com            |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,591 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/direct?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_direct_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/direct?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_direct_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_direct_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection is entirely made up of one-word .direct domains. The names range from broad dictionary words such as people.direct and relief.direct to more specific or unusual terms such as grandfather.direct and pointy.direct. That creates a wide spread in commercial relevance. For founders, the strongest options are usually the words that are instantly understood, easy to say, and closely matched to a direct-response use case. For investors, the better candidates are typically the words with broad intent and cleaner resale logic. Median ask is 27.995194, so the key question is less entry price and more whether the word has durable meaning, strong recall, and low trademark friction.

- Prefer clear words with obvious commercial meaning
- Check if the word fits the direct tone of .direct
- Avoid trademark-heavy terms such as velcro.direct
- Use memorability to separate broad words from weak ones

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .DIRECT One-Word Domains*. Version 2026-05-11. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .DIRECT page](https://unique.domains/domains/tld/direct?utm_source=github&utm_medium=referral&utm_campaign=repo_direct_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_direct_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_direct_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_direct_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
