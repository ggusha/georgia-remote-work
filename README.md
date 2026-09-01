# Remote vacancies open to Georgia

Aggregate statistics on remote job adverts that accept applicants from Georgia,
rebuilt daily from live listings.

Updated 2026-09-01. Licence CC-BY-4.0. Source: https://donator.ge/jobs/dataset

## What is in it

| File | Contents |
| --- | --- |
| `data.json` | Eligibility split, published pay by category, skill demand, daily board size, country table. Every figure carries the number of adverts it was computed over. |
| `countries.csv` | One row per country: vacancies open to it, median published monthly pay in USD, and that pay as a multiple of the country's average monthly wage. |

## What is not in it

The vacancies themselves. Those are listings from other boards under their own
terms; only aggregates are published here.

## Method

Pay figures are the median published monthly rate in USD. Hourly and daily rates
are excluded, as is any advert whose pay period we inferred rather than read.
The wage multiple uses ILO average monthly earnings in USD, with the observation
year on each row.

## Citation

> Remote vacancies open to Georgia. Donator, 2026-09-01. https://donator.ge/jobs/dataset. Licensed CC BY 4.0.
