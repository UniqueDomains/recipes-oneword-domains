# Available .RECIPES One-Word Domains (17,841)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-17%2C841%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .recipes one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **17,841 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 17,841 domains · **Median ask:** $11.45 · **High-demand under $2,500:** 0

**Last updated:** 2026-08-21
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

- `recipes.csv`, public CSV extract (1,000 rows)
- `recipes.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/recipes-oneword-domains/main/recipes.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                   |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------------------------------- |
| age.recipes      | available | $11.99    | —             | high           | low    | 3      | name.com                                    |
| mail.recipes     | resell    | —         | —             | high           | medium | 4      | Unstoppable Domains Inc                     |
| lp.recipes       | premium   | $500      | —             | medium         | low    | 3      | name.com                                    |
| aid.recipes      | available | $11.99    | —             | medium         | low    | 3      | name.com                                    |
| salad.recipes    | resell    | —         | —             | high           | low    | 5      | Dynadot Inc                                 |
| asia.recipes     | premium   | $500      | —             | high           | low    | 4      | name.com                                    |
| aug.recipes      | available | $5.48     | $95.98        | low            | low    | 3      | namecheap                                   |
| thank.recipes    | resell    | —         | —             | high           | low    | 5      | Spaceship, Inc.                             |
| punch.recipes    | premium   | $78.54    | $78.54        | high           | low    | 5      | namesilo                                    |
| ben.recipes      | available | $11.99    | —             | high           | medium | 3      | name.com                                    |
| country.recipes  | resell    | —         | —             | high           | low    | 7      | Spaceship, Inc.                             |
| three.recipes    | premium   | $11.99    | $103.99       | high           | low    | 5      | name.com                                    |
| boo.recipes      | available | $11.99    | —             | high           | low    | 3      | name.com                                    |
| cocktail.recipes | resell    | —         | —             | high           | low    | 8      | GoDaddy Online Services Cayman Islands Ltd. |
| ethnic.recipes   | premium   | $500      | —             | high           | low    | 6      | name.com                                    |
| bow.recipes      | available | $11.99    | —             | high           | low    | 3      | name.com                                    |
| learning.recipes | resell    | —         | —             | high           | low    | 8      | Dynadot Inc                                 |
| travel.recipes   | premium   | $520      | $520          | high           | medium | 6      | namecheap                                   |
| bra.recipes      | available | $11.99    | —             | medium         | low    | 3      | name.com                                    |
| unique.recipes   | premium   | $500      | —             | high           | medium | 6      | name.com                                    |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 17,841 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/recipes?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_recipes_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/recipes?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_recipes_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_recipes_oneword_domains&utm_content=related_pricing)

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

This selection covers 12,366 one-word .recipes domain names, with a median ask of $15.68. Each name pairs a short, food-related word — from flaxseed.recipes to roastbeef.recipes — with a TLD built for cooking and lifestyle content. Whether you're comparing entry pricing and renewal costs or shortlisting a brandable name for a new food site, this list stays focused on single-word .recipes options only. Updated daily to reflect current listings.

- 12,366 one-word .recipes names in this selection, updated daily
- Median ask of $15.68 makes early entry low-cost
- Names like flaxseed.recipes and roastbeef.recipes show food-first branding
- Compare renewal cost and brandability before committing to a name

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .RECIPES One-Word Domains*. Version 2026-08-21. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .RECIPES page](https://unique.domains/domains/tld/recipes?utm_source=github&utm_medium=referral&utm_campaign=repo_recipes_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_recipes_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_recipes_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_recipes_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
