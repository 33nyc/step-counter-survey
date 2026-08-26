# In-app purchases, ratings and widgets of iPhone step counters (US App Store, 17 August 2026)

A hand-made survey of **18 iPhone step counter apps**, read off their own App Store pages on **17 August 2026**.

It exists because the one number people most want — *what an app charges once you have installed it* — **is not available from Apple's search interface at all.** It appears only on each app's own page, and only if you scroll to the In-App Purchases block.

There is no ranking and no score in this file. It is what the store showed on that date.

- **Live page with the same data, in a table:** https://angelstep.app/data
- **Canonical JSON, always current:** https://angelstep.app/data/step-counter-survey.json
- **Canonical CSV:** https://angelstep.app/data/step-counter-survey.csv

## What is in it

| file | what it is |
|---|---|
| `step-counter-survey.json` | the canonical record: metadata, method, licence, summary, and the 18 apps |
| `step-counter-survey.csv` | the same 18 rows, flat, for spreadsheets and notebooks |

### Columns

| column | meaning |
|---|---|
| `name` | app name as listed on the US App Store |
| `listed_in` | which of our guides the app appears in (`cute`, `simple`, `free`) |
| `ratings_count` | number of ratings shown on the listing |
| `rating_average` | average rating shown on the listing |
| `widget_per_description` | the listing's own text mentions a widget — **not** that we verified one exists |
| `reads_health_per_description` | the listing's own text says it reads Apple Health |
| `last_updated` | month of the last update shown on the listing |
| `in_app_purchases` | whether the listing shows an In-App Purchases block |
| `prices_listed` | the price range shown in that block |
| `lock_screen_per_description` | the listing's own text mentions a lock screen widget |
| `kind` | what the app is besides a step counter, in its own words (`walking game`, `counter + virtual dog`) — empty where it is a step counter and nothing else |
| `app_store_id` | Apple's numeric identifier for the listing; appended to `https://apps.apple.com/us/app/id` it opens the page this row was read from (`id1037595083` is the first row) |

An empty cell means the store did not show it, which is not the same as `no`.

## What the numbers say

- 13 apps had their purchases checked; **4 of them list no in-app purchases at all** (Pedometer α, Plod, STEPPI, Steps — Simple Pedometer).
- Listed prices run from **$0.99 to $49.99**.
- 12 of 18 listings mention a **widget** in their own description — but only 6 of 18 mention a **lock screen**. On this evidence, "widget" on a store listing usually means the home screen alone.
- Ratings counts run from 0 to **291,037**, median **1,267** — the category is a few large apps and a long tail of small ones.

## Method, stated plainly

Each app's App Store page was opened and read by hand on 2026-08-17. Purchases come from the *In-App Purchases* block on that page; 'per its description' means the listing's own text says so, not that we verified the feature exists. The lock-screen column was read on 2026-08-19 from Apple's public listing data, matched to each app by name, rating count and last-updated month; in the same pass the widget and Health columns were re-read that way and agreed with the hand reading in every one of the 18 rows.

Absence in a description is not proof of absence in the app; it is what the maker chose to mention.

Region: **US App Store**. Date of reading: **17 August 2026** (`2026-08-17`).

## Limits worth knowing before you cite this

- It is a **snapshot**. Prices, ratings and descriptions change; nothing here is re-checked automatically.
- It is **18 apps**, not the whole category — those that appeared for the searches behind three buyer's guides.
- There is **no ranking**, on purpose. A ranking published by a participant in the market is an advertisement. The facts are Apple's; the compilation is ours.

## Who made it

Collected by the people building **Angel Step** — a step counter for iPhone built around one number, with widgets on the home screen and the lock screen. https://angelstep.app

## Where these rows are written out

- [what step counters actually cost](https://angelstep.app/free-step-counters) — the prices, per app, in a table
- [how to choose one](https://angelstep.app/step-counter-apps) — what these numbers do and do not decide
- [cute step counters](https://angelstep.app/cute-step-counters) — the nine that are pleasant to look at
- [simple step counters](https://angelstep.app/simple-step-counters) — the nine that ask least of you
- [steps to calories](https://angelstep.app/steps-to-calories) — the MET model written out, with the tables precomputed
- [how far 10,000 steps is](https://angelstep.app/how-far) — distance by height, in a table you can read

## Licence

**CC BY 4.0** on the compilation, its structure and the described method. Not claimed: the underlying facts, which are Apple's public store listings.

Attribution: Angel Step, <https://angelstep.app/data>

## Citation

> Angel Step (2026). *In-app purchases, ratings and widgets of iPhone step counters* (US App Store, measured 2026-08-17). [10.5281/zenodo.22032007](https://doi.org/10.5281/zenodo.22032007) · https://angelstep.app/data

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22032007.svg)](https://doi.org/10.5281/zenodo.22032007)

## Mirrors

`https://angelstep.app/data` is the canonical copy. The same files are mirrored on [GitHub](https://github.com/33nyc/step-counter-survey), [Hugging Face](https://huggingface.co/datasets/thee3/step-counter-survey), [Kaggle](https://www.kaggle.com/datasets/light33/iphone-step-counter-apps-prices-and-widgets).
