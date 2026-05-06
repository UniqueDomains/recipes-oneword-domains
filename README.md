# Available .RECIPES One-Word Domains (12,362)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C362%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .recipes one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,362 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,362 domains · **Median ask:** $19.38 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
**Canonical page:** `https://unique.domains/domains/tld/recipes`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/recipes?utm_source=github&utm_medium=referral&utm_campaign=repo_recipes_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./recipes.csv">CSV</a> / <a href="./recipes.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_recipes_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_recipes_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .RECIPES search](https://unique.domains/domains/tld/recipes?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_recipes_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .RECIPES search](https://unique.domains/domains/tld/recipes?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_recipes_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_recipes_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .RECIPES one-word domain catalog.

### Files

- `recipes.csv` — public CSV extract (1,000 rows)
- `recipes.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/recipes-oneword-domains/main/recipes.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain              | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| ------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| coins.recipes       | available | $11.99    | —             | 56             | 41     | 5      | name.com         |
| CincodeMayo.recipes | resell    | —         | —             | 68             | 7      | 13     | GoDaddy.com, LLC |
| jobs.recipes        | premium   | $500      | —             | 79             | 42     | 4      | name.com         |
| justin.recipes      | available | $11.99    | —             | 58             | 38     | 7      | name.com         |
| tickets.recipes     | available | $11.99    | —             | 64             | 34     | 7      | name.com         |
| payments.recipes    | available | $11.99    | —             | 58             | 33     | 8      | name.com         |
| quotes.recipes      | available | $11.99    | —             | 58             | 29     | 6      | name.com         |
| Jim.recipes         | available | $95.98    | —             | 78             | 28     | 3      | namecheap        |
| gems.recipes        | available | $11.99    | —             | 70             | 28     | 4      | name.com         |
| forms.recipes       | available | $11.99    | —             | 54             | 28     | 5      | name.com         |
| gods.recipes        | available | $11.99    | —             | 72             | 27     | 4      | name.com         |
| trades.recipes      | available | $11.99    | —             | 71             | 26     | 6      | name.com         |
| traders.recipes     | available | $11.99    | —             | 60             | 26     | 7      | name.com         |
| destination.recipes | available | $11.99    | —             | 90             | 25     | 11     | name.com         |
| Trex.recipes        | available | $95.98    | —             | 80             | 24     | 5      | namecheap        |
| pops.recipes        | available | $11.99    | —             | 74             | 24     | 4      | name.com         |
| shops.recipes       | available | $11.99    | —             | 64             | 24     | 5      | name.com         |
| toys.recipes        | available | $11.99    | —             | 60             | 24     | 4      | name.com         |
| loans.recipes       | available | $11.99    | —             | 58             | 24     | 5      | name.com         |
| girls.recipes       | available | $11.99    | —             | 83             | 23     | 5      | name.com         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,362 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/recipes?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_recipes_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/recipes?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_recipes_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_recipes_oneword_domains&utm_content=related_pricing)

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

This selection is entirely one-word .recipes domains, which makes the extension the main context signal. That favors words that feel natural around food, cooking, ingredients, menus, or kitchen utility, and makes off-theme words harder to justify. Examples such as advisor.recipes, impulse.recipes, invent.recipes, cipher.recipes, and reliable.recipes show the range: some are descriptive, some abstract, and some may feel mismatched with the extension. For founders, the best options are memorable and easy to explain aloud. For investors, the key test is whether the word and the .recipes ending create a clear resale story at a low carrying cost. Avoid names with obvious trademark exposure, including terms like reebok.recipes.

- Favor words that make immediate sense with .recipes
- Use the 19.38 median ask as a rough price anchor
- Check trademark exposure before judging brandability
- Prioritize clear spelling and spoken recall

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .RECIPES One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .RECIPES page](https://unique.domains/domains/tld/recipes?utm_source=github&utm_medium=referral&utm_campaign=repo_recipes_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_recipes_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_recipes_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_recipes_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
