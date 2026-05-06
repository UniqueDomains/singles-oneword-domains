# Available .SINGLES One-Word Domains (12,555)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C555%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .singles one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,555 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,555 domains · **Median ask:** $15.95 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
**Canonical page:** `https://unique.domains/domains/tld/singles`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/singles?utm_source=github&utm_medium=referral&utm_campaign=repo_singles_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./singles.csv">CSV</a> / <a href="./singles.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_singles_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_singles_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .SINGLES search](https://unique.domains/domains/tld/singles?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_singles_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .SINGLES search](https://unique.domains/domains/tld/singles?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_singles_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_singles_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .SINGLES one-word domain catalog.

### Files

- `singles.csv` — public CSV extract (1,000 rows)
- `singles.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/singles-oneword-domains/main/singles.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain             | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ------------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| jewels.singles     | available | $12.99    | —             | 80             | 15     | 6      | name.com  |
| forces.singles     | available | $12.99    | —             | 82             | 12     | 6      | name.com  |
| geton.singles      | available | $12.99    | —             | 82             | 10     | 6      | name.com  |
| matcha.singles     | available | $12.99    | —             | 86             | 39     | 6      | name.com  |
| useit.singles      | available | $12.99    | —             | 94             | 7      | 6      | name.com  |
| dogsit.singles     | available | $12.99    | —             | 96             | 2      | 6      | name.com  |
| edamame.singles    | available | $12.99    | —             | 80             | 9      | 7      | name.com  |
| playon.singles     | available | $12.99    | —             | 80             | 14     | 7      | name.com  |
| toneup.singles     | available | $12.99    | —             | 80             | 5      | 7      | name.com  |
| hangon.singles     | available | $12.99    | —             | 82             | 6      | 7      | name.com  |
| stirup.singles     | available | $12.99    | —             | 82             | 3      | 7      | name.com  |
| dogsick.singles    | available | $12.99    | —             | 90             | 1      | 7      | name.com  |
| getlife.singles    | available | $12.99    | —             | 80             | 5      | 8      | name.com  |
| SantaClara.singles | premium   | $92.40    | $92.40        | 75             | 9      | 11     | namecheap |
| whynot.singles     | available | $12.99    | —             | 74             | 39     | 7      | name.com  |
| justin.singles     | available | $12.99    | —             | 58             | 38     | 7      | name.com  |
| ideas.singles      | available | $12.99    | —             | 62             | 37     | 5      | name.com  |
| stories.singles    | available | $12.99    | —             | 58             | 36     | 7      | name.com  |
| Cats.singles       | available | $36.98    | —             | 59             | 33     | 4      | namecheap |
| teams.singles      | available | $12.99    | —             | 62             | 32     | 5      | name.com  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,555 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/singles?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_singles_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/singles?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_singles_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_singles_oneword_domains&utm_content=related_pricing)

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

This selection focuses only on one-word .singles domains. The set is broad, with 12,555 names and examples ranging from generic terms like tips.singles and finals.singles to punchier words like popup.singles and jewels.singles. For founders, the main question is whether the word reads clearly with .singles and feels memorable enough to own as a brand. For investors, the key test is whether the keyword has clear end-user relevance at a low enough ask to justify the hold. When comparing these domains, weigh word clarity, commercial intent, and whether the pairing with .singles feels natural rather than forced.

- Check if the word fits naturally with .singles
- Favor clear, memorable words over awkward pairings
- Median ask is about $15.95 across this selection
- Examples include tips.singles and popup.singles

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .SINGLES One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .SINGLES page](https://unique.domains/domains/tld/singles?utm_source=github&utm_medium=referral&utm_campaign=repo_singles_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_singles_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_singles_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_singles_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
