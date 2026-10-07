# LATAM IT Salary Guide 2027 — open data

Monthly salary ranges in US dollars for **81 tech, data, product, design, marketing and sales roles** across **19 Latin American countries**, by seniority (Junior, Mid-level, Senior). Published by [Interfell](https://www.interfell.com/en/), a Simera company.

- **Source and full guide:** [LATAM IT Salary Guide 2027](https://www.interfell.com/en/salary-guide-latinamerica) · [Guía Salarial IT LATAM 2027 (ES)](https://www.interfell.com/guia-salarial-latinoamerica)
- **Methodology:** [How we built the guide](https://www.interfell.com/en/salary-guide-methodology) · [Metodología (ES)](https://www.interfell.com/metodologia-guia-salarial)
- **Data cut-off:** October 2026 · **License:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## The file

[`data/latam-it-salaries-2027.csv`](data/latam-it-salaries-2027.csv): 243 rows (81 roles × 3 seniority levels).

| Column | Meaning |
| --- | --- |
| `role_id`, `role_en`, `role_es` | Role identifier and name in English and Spanish |
| `family_en`, `family_es` | Role family (10 families) |
| `seniority` | Junior, Mid-level or Senior. Seniority is defined by evidence (execution, autonomy, impact), not years |
| `latam_market_usd_month_min` / `_max` | Monthly pay for a remote contractor working for an international company. Min = Tier 3 countries, max = Tier 1 countries |
| `us_market_c1_english_usd_month_min` / `_max` | Same, for profiles with advanced English (C1+) working for US companies. Includes the English premium: +30% in Tier 3, +15% in Tier 1 (rounded to 50) |
| `edition`, `source` | Guide edition and source URL |

**Country tiers.** Tier 1: Brazil, Chile, Costa Rica, Mexico, Puerto Rico, Uruguay. Tier 2: Argentina, Colombia, Dominican Republic, Guatemala, Panama, Peru. Tier 3: Bolivia, Ecuador, El Salvador, Honduras, Nicaragua, Paraguay, Venezuela. Tiers group countries by relative cost, supply density and competition for the profile; they are not a ranking of talent quality.

## Where the numbers come from

Four layers of data: Interfell's own hiring (2,300+ successful hires since 2016 for 250+ companies), the Simera database (80,000+ LATAM profiles, 76,000+ with a self-reported salary expectation), interviews and conversations with thousands of professionals, and public market sources (LinkedIn, Stack Overflow Developer Survey, Deel, Get on Board). Full detail in the [methodology](https://www.interfell.com/en/salary-guide-methodology).

Figures are monthly pay for remote contractors, not local payroll salaries, and exclude bonuses and equity. Country-level detail is available in the [full guide](https://www.interfell.com/en/salary-guide-latinamerica).

## How to cite

> Interfell (2026). *LATAM IT Salary Guide 2027*. https://www.interfell.com/en/salary-guide-latinamerica

You can reuse, adapt and redistribute the data, including commercially, as long as you credit Interfell and link to the guide.
