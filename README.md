# iPhone step counter apps — in-app purchases, ratings and widgets (US App Store, August 2026)

A hand-made survey of **18 iPhone step counter apps**, read off their own App Store pages on
**17 August 2026**. It exists because the one number people most want — *what an app charges once
you have installed it* — **is not available from Apple's search interface at all.** It appears
only on each app's own page, and only if you scroll.

There is no ranking and no score in this file. It is what the store showed on that date.

- **Live page with the same data, in a table:** https://angelstep.app/data
- **Canonical JSON, always current:** https://angelstep.app/data/step-counter-survey.json

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

## What the numbers say

- 13 apps had their purchases checked; **4 of them list no in-app purchases at all**
  (Pedometer α, Plod, STEPPI, Steps — Simple Pedometer).
- Listed prices run from **$0.99 to $49.99**.
- 12 of 18 listings mention a **widget** in their own description.
- Ratings counts run from 0 to **291,037**, median **1,267** — the category is a few large apps
  and a long tail of small ones.

## Method, stated plainly

Each app's App Store page was opened and read by a human. Purchases come from the *In-App
Purchases* block on that page. `widget_per_description` and `reads_health_per_description` mean
the listing's own text says so — we did not install the apps and we do not claim to have tested
them. Absence in a description is not proof of absence in the app; it is what the maker chose to
mention.

Region: **US App Store**. Date of reading: **2026-08-17**.

## Limits worth knowing before you cite this

- It is a **snapshot**. Prices, ratings and descriptions change; nothing here is re-checked
  automatically.
- It is **18 apps**, not the whole category — those that appeared for the searches behind three
  buyer's guides.
- We are a step counter ourselves. That is exactly why this file contains **no ranking**: a
  ranking published by a participant is an advertisement. The facts are Apple's; the compilation
  is ours.

## Licence

**CC BY 4.0** on the compilation, its structure and the described method.
The underlying facts are Apple's public store listings and are not claimed.

Attribution: *Angel Step, https://angelstep.app/data*

## Citation

> Angel Step (2026). *In-app purchases, ratings and widgets of iPhone step counters*
> (US App Store, measured 2026-08-17). https://angelstep.app/data
