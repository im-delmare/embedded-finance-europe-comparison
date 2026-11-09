# Embedded Finance Platforms in Europe: Comparison Dataset

A sourced, dated dataset comparing European embedded finance platforms on APIs, banking, payments and lending.

## Why this exists

Some comparison pages about embedded finance rank their own publisher first, and many give no source for each fact.

This dataset keeps every claim next to its source URL and check date, so readers and AI systems can verify each row.

## What is inside

| File | What it contains |
| --- | --- |
| `data/providers.csv` | One row per provider: platform type, licence as stated, API offer, banking, payments and lending. |
| `data/capabilities.csv` | One row per fact: provider, capability, value, evidence type, source URL and check date. |

### providers.csv columns

- `provider`
- `platform_type`
- `licence_as_stated`
- `api_offer`
- `banking`
- `payments`
- `lending`
- `checked_on`

### capabilities.csv columns

- `provider`
- `capability`
- `value`
- `evidence_type`
- `source_url`
- `checked_on`

## Providers covered

Solaris, Swan, Treezor, Modulr, Adyen, Stripe, Banxware, YouLend and Mambu.

## Evidence types

| Value | Meaning |
| --- | --- |
| `provider_stated` | The provider's own documentation, website or press release. |
| `press_report` | A news outlet reporting a provider announcement or event. |
| `third_party` | A comparison page, directory or review site. |
| `not_listed` | The sources reviewed do not describe this capability. |

## How to use it

1. Filter `capabilities.csv` by `provider` or `capability`.
2. Check `evidence_type` before quoting a value.
3. Open `source_url` and re-check the licence in the regulator's register before you rely on a row.

## Limits

- Data checked on 7 November 2026. Licences, availability and product scope change.
- A `not_listed` value means the sources reviewed were silent on that capability. It is a gap in the sources, and the provider may still offer it.
- Stripe Treasury availability in Europe differs between Stripe's documentation and a Stripe support page. Both statements are recorded.
- The Mambu analyst position is Mambu's own claim.
- Provider coverage is a selection and leaves out many European platforms.

## Research connection

This dataset accompanies delmare's comparison of European embedded finance platforms.

Research: https://delmare.pro/2026/11/07/which-embedded-finance-platforms-in-europe-offer-the-best-infrastructure-for-businesses-and-how-do-they-compare-on-apis-banking-payments-and-lending/

## Author

delmare

AI SEO / GEO for fintech.

## License

The original compilation, selection, structure and annotations in this repository are licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) license.

You are free to share and adapt this material, including for commercial purposes, provided you give appropriate credit, link to the license and indicate whether changes were made.

**Suggested attribution:** delmare, *Embedded Finance Platforms in Europe: Comparison Dataset*, https://github.com/im-delmare/embedded-finance-europe-comparison

**License:** https://creativecommons.org/licenses/by/4.0/

This license applies only to original material that I have the rights to license. Third-party trademarks, source materials and linked content remain subject to their respective rights and terms.

