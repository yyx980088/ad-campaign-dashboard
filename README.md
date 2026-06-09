# Ad Campaign Performance Dashboard

**Live Dashboard:** https://yyx980088.github.io/ad-campaign-dashboard/

---

## Overview

An interactive single-page dashboard built in HTML and Chart.js that visualises the performance of 10 ad campaigns run between **January 2024 and October 2024**. Designed in Accenture's purple-and-black brand palette.

---

## Features

- **Date range filter** — narrow all charts and KPI cards to any sub-period using the From / To dropdowns
- **Hover guide line** — a dashed line drops from any hovered data point to the x-axis for easy reading
- **Permanent data labels** — CTR, CPC, and ROI values are labelled directly on each data point
- **Demographic annotations** — the ROI chart shows the leading audience segment at every campaign point
- **KPI summary row** — six headline metrics (Impressions, Clicks, CTR, CPC, Spend/Revenue, ROI) update live with the date filter

---

## Charts

| # | Chart | What it shows |
|---|-------|---------------|
| 1 | Impressions & Ad Clicks | Volume of ad views vs. clicks over time (dual y-axes) |
| 2 | CTR (%) | Click-through rate trend across campaigns |
| 3 | CPC ($) | Average cost per click over time |
| 4 | Total Cost & Revenue | Ad spend vs. generated revenue (dual y-axes) |
| 5 | ROI (%) | Return on investment per campaign, annotated by demographic segment |

---

## Metric Definitions

| Metric | Definition |
|--------|------------|
| **Impressions** | Total number of times an ad was displayed |
| **Ad Clicks** | Number of times users clicked an ad |
| **CTR** | Click-Through Rate = Clicks ÷ Impressions × 100 |
| **CPC** | Cost Per Click = Total Cost ÷ Clicks |
| **Total Cost** | Full spend for a campaign period |
| **Generated Revenue** | Revenue attributed to ad clicks |
| **ROI** | Return on Investment = (Revenue − Cost) ÷ Cost × 100 |

---

## Tech Stack

- HTML / CSS / JavaScript (no framework)
- [Chart.js 4.4.4](https://www.chartjs.org/)
