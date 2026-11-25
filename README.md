# Available .CC One-Word Domains

**Looking for a name, not a file?** [Find the strongest domain still available for your business](https://unique.domains/?utm_source=github&utm_medium=referral&utm_campaign=repo_cc_oneword_domains&utm_content=top_home).

1,000 real .cc one-word domain names, refreshed every night, with their status and, when known, the price to register or buy them and what they renew at. One line of pandas, no scraping, no key.

Each word exists once on each ending. Unique.domains tracks [56,976 names on .cc](https://unique.domains/tld/cc); this file is an extract of the ones you can still register or buy, in the list's own neutral order, not a ranking.

42,113 one-word .cc names are free to register today. Cheapest first year $3.11 at Spaceship, renewal $8.26 there. 138 .cc sales in the last 12 months, median $978.

Live page: [unique.domains/tld/cc](https://unique.domains/tld/cc?utm_source=github&utm_medium=referral&utm_campaign=repo_cc_oneword_domains&utm_content=top_tld_page)

<img alt="updated: daily" src="https://img.shields.io/badge/updated-daily-0969da"> <img alt="extract: 1,000 rows" src="https://img.shields.io/badge/extract-1%2C000%20rows-8250df"> <img alt="formats: CSV | JSON" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b"> <img alt="licence: CC BY 4.0" src="https://img.shields.io/badge/licence-CC%20BY%204.0-2ea44f">

## Download

- [cc.csv](https://github.com/UniqueDomains/cc-oneword-domains/raw/main/cc.csv), 1,000 rows
- [cc.json](https://github.com/UniqueDomains/cc-oneword-domains/raw/main/cc.json), 1,000 rows

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/cc-oneword-domains/main/cc.csv")
print(df.head())
```

Also on Kaggle, with every ending: [One-Word Domains by Ending](https://www.kaggle.com/datasets/uniquedomains/one-word-domains-by-ending).

## Sample rows

The first 20 rows of the file, in the file's order.

| domain          | status    | purchase_price | renewal_price | attractiveness | demand | length |
| --------------- | --------- | -------------- | ------------- | -------------- | ------ | ------ |
| otherworldly.cc | available | $11            | —             | high           | low    | 12     |
| blanco.cc       | resell    | —              | —             | high           | low    | 6      |
| irksome.cc      | available | $3.99          | $8.80         | medium         | low    | 7      |
| amalgamate.cc   | available | $4.19          | $9.99         | high           | low    | 10     |
| contralto.cc    | available | $3.11          | $8.26         | high           | low    | 9      |
| mingling.cc     | available | $4.19          | $9.99         | high           | low    | 8      |
| delible.cc      | available | $4.98          | $13.98        | medium         | low    | 7      |
| atm.cc          | resell    | —              | —             | high           | low    | 3      |
| niv.cc          | resell    | —              | —             | high           | low    | 3      |
| spiraling.cc    | available | $11            | $9.99         | high           | low    | 9      |
| courteously.cc  | available | $4.19          | $9.99         | high           | low    | 11     |
| powerstroke.cc  | available | $4.19          | $9.99         | high           | low    | 11     |
| fix.cc          | resell    | —              | —             | high           | medium | 3      |
| currant.cc      | available | $11            | —             | high           | low    | 7      |
| sophisticate.cc | available | $11            | —             | high           | low    | 12     |
| tastes.cc       | available | $4.19          | $9.99         | high           | low    | 6      |
| letterboxing.cc | available | $3.11          | $8.26         | high           | low    | 12     |
| swizzle.cc      | available | $4.98          | $13.98        | high           | low    | 7      |
| fat.cc          | resell    | —              | —             | high           | low    | 3      |
| metta.cc        | resell    | —              | —             | high           | low    | 5      |

## What is in the data

- `domain`: Fully qualified domain name.
- `status`: Current acquisition state for the domain in the public extract.
- `purchase_price`: Visible purchase price when available.
- `renewal_price`: Visible renewal price when available.
- `attractiveness`: Public composite naming band used as a decision-support signal.
- `demand`: Public buyer-pressure band when available.
- `length`: Character count without the TLD.
- `registrar`: Registrar name when known.
- `created_at`: Creation timestamp when known.
- `expires_at`: Expiry timestamp when known.

Types and formats: [DATA_DICTIONARY.md](./DATA_DICTIONARY.md).

## Methodology

- The files hold 1,000 rows of the 19,385 names in the live list today.
- Every row is a one-word domain name.
- Check a name before you act on it: a status or a price can change.

More in [METHODOLOGY.md](./METHODOLOGY.md).

## Update policy

- The files are rebuilt every night from the same export.
- The files hold the public extract, not the whole live list.

## How to cite

> Unique.domains, One-word .cc domains, https://unique.domains/tld/cc, CC BY 4.0

Citation metadata: [CITATION.cff](./CITATION.cff). A DOI follows once Zenodo mints one.

## Related datasets

- [Every one-word domain](https://github.com/UniqueDomains/oneword-domains) (the hub)

One-word domains by ending:

- [.com](https://github.com/UniqueDomains/com-oneword-domains), [page](https://unique.domains/tld/com?utm_source=github&utm_medium=referral&utm_campaign=repo_cc_oneword_domains&utm_content=related_tld_page)
- [.ai](https://github.com/UniqueDomains/ai-oneword-domains), [page](https://unique.domains/tld/ai?utm_source=github&utm_medium=referral&utm_campaign=repo_cc_oneword_domains&utm_content=related_tld_page)
- [.io](https://github.com/UniqueDomains/io-oneword-domains), [page](https://unique.domains/tld/io?utm_source=github&utm_medium=referral&utm_campaign=repo_cc_oneword_domains&utm_content=related_tld_page)
- [.app](https://github.com/UniqueDomains/app-oneword-domains), [page](https://unique.domains/tld/app?utm_source=github&utm_medium=referral&utm_campaign=repo_cc_oneword_domains&utm_content=related_tld_page)
- [.co](https://github.com/UniqueDomains/co-oneword-domains), [page](https://unique.domains/tld/co?utm_source=github&utm_medium=referral&utm_campaign=repo_cc_oneword_domains&utm_content=related_tld_page)
- [.xyz](https://github.com/UniqueDomains/xyz-oneword-domains), [page](https://unique.domains/tld/xyz?utm_source=github&utm_medium=referral&utm_campaign=repo_cc_oneword_domains&utm_content=related_tld_page)

Lists:

- [Expired](https://github.com/UniqueDomains/expired-oneword-domains)
- [Expiring](https://github.com/UniqueDomains/expiring-oneword-domains)
- [Brandable](https://github.com/UniqueDomains/brandable-oneword-domains)
- [Short](https://github.com/UniqueDomains/short-oneword-domains)

Every ending Unique.domains tracks: [unique.domains/tld](https://unique.domains/tld?utm_source=github&utm_medium=referral&utm_campaign=repo_cc_oneword_domains&utm_content=related_hub).

## About Unique.domains

[Unique.domains](https://unique.domains/?utm_source=github&utm_medium=referral&utm_campaign=repo_cc_oneword_domains&utm_content=about) tracks one-word domain names across the endings people build on: which are free to register, what they cost to hold and what names of each ending sell for. The datasets in this organization are its public extracts.

From code: the [Node.js SDK and CLI](https://github.com/UniqueDomains/nodejs) (`npm install domain-name-api`), the [Python client](https://github.com/UniqueDomains/python) (`pip install uniquedomains`) and the [MCP server](https://github.com/UniqueDomains/mcp-server) for AI assistants, hosted at `https://mcp.unique.domains/mcp`.

Questions and corrections: `kai@unique.domains`

[Start a Radar for .cc names](https://unique.domains/tld/cc?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_cc_oneword_domains&utm_content=about)
