# Available .KIWI One-Word Domains (32,577)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-32%2C577%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .kiwi one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **32,577 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 32,577 domains · **Median ask:** $34.66 · **High-demand under $2,500:** 76

**Last updated:** 2026-10-02
**Canonical page:** `https://unique.domains/domains/tld/kiwi`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/kiwi?utm_source=github&utm_medium=referral&utm_campaign=repo_kiwi_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./kiwi.csv">CSV</a> / <a href="./kiwi.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_kiwi_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_kiwi_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .KIWI search](https://unique.domains/domains/tld/kiwi?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_kiwi_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .KIWI search](https://unique.domains/domains/tld/kiwi?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_kiwi_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_kiwi_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .KIWI one-word domain catalog.

### Files

- `kiwi.csv`, public CSV extract (1,000 rows)
- `kiwi.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/kiwi-oneword-domains/main/kiwi.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain    | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| --------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| amo.kiwi  | available | $21.41    | $21.41        | high           | low    | 3      | dynadot   |
| aba.kiwi  | premium   | $202.80   | $202.80       | high           | low    | 3      | namecheap |
| ayr.kiwi  | available | $31.98    | $35.68        | high           | low    | 3      | namecheap |
| act.kiwi  | premium   | $81.90    | $81.90        | high           | medium | 3      | namecheap |
| bae.kiwi  | available | $31.98    | $35.68        | high           | low    | 3      | namecheap |
| ali.kiwi  | premium   | $81.90    | $81.90        | high           | high   | 3      | namecheap |
| blm.kiwi  | available | $31.98    | $35.68        | high           | low    | 3      | namecheap |
| ecc.kiwi  | premium   | $61.97    | $61.97        | high           | low    | 3      | dynadot   |
| cic.kiwi  | available | $21.43    | $21.43        | high           | low    | 3      | dynadot   |
| jac.kiwi  | premium   | $30.98    | $30.98        | high           | low    | 3      | dynadot   |
| cup.kiwi  | available | $31.98    | $35.68        | high           | low    | 3      | namecheap |
| mat.kiwi  | premium   | $54.89    | $54.89        | high           | low    | 3      | name.com  |
| eec.kiwi  | available | $21.47    | $21.47        | high           | low    | 3      | dynadot   |
| sor.kiwi  | premium   | $81.90    | $81.90        | medium         | low    | 3      | namecheap |
| hbo.kiwi  | available | $35.68    | —             | high           | medium | 3      | namecheap |
| eric.kiwi | premium   | $81.90    | $81.90        | high           | medium | 4      | namecheap |
| hex.kiwi  | available | $31.98    | $35.68        | high           | medium | 3      | namecheap |
| find.kiwi | premium   | $81.90    | $81.90        | high           | medium | 4      | namecheap |
| iaa.kiwi  | available | $31.98    | $35.68        | medium         | low    | 3      | namecheap |
| kale.kiwi | premium   | $41.60    | $41.60        | high           | low    | 4      | namecheap |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 32,577 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 76 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/kiwi?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_kiwi_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/kiwi?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_kiwi_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_kiwi_oneword_domains&utm_content=related_pricing)

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
- `status_verified_at`, When status was last established against the registry. Null means never checked.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection covers 9,919 one-word domain names registered under the .kiwi extension, spanning everyday words, action phrases, and short brand-style names. Median asking price sits near $42, making many of these accessible for early-stage projects and portfolio testing alike. Some names closely echo well-known brands, so trademark exposure should be checked before purchase. When comparing these domains, weigh word clarity, pronounceability, and renewal cost alongside the asking price to find names that hold long-term value.

- 9,919 one-word .kiwi domain names in this selection
- Median asking price near $42 across the set
- Mix of dictionary words, phrases, and brand-style names
- Some names carry trademark risk — verify before buying

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The snapshot date above is when this file was written, not when each row was checked. Read `status_verified_at` for that: a name whose status was last established months ago is exported with its real date rather than the snapshot's.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .KIWI One-Word Domains*. Version 2026-10-02. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .KIWI page](https://unique.domains/domains/tld/kiwi?utm_source=github&utm_medium=referral&utm_campaign=repo_kiwi_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_kiwi_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_kiwi_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_kiwi_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `kai@unique.domains`
