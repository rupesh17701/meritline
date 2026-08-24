# Meritline

**Live site:** https://rupesh17701.github.io/meritline/

An independent analysis of India's power sector — generation mix, demand, and exchange (IEX) pricing — built as a working portfolio piece for power-market analyst and energy-consulting applications.

## What's in it

- **Market snapshot** — KPI strip covering all-time peak demand, installed capacity, non-fossil share, FY 2025–26 energy shortage, and today's live IEX Day-Ahead price.
- **Merit-order stack (original analysis)** — a modeled supply stack showing which source sets the marginal price at record demand, toggled between a "full nameplate" daytime scenario and an "solar off" evening scenario. This is the core analytical piece: it explains *why* exchange prices spike after sunset, not just that they do, using CERC-reported cost bands for coal and gas layered against India's actual capacity mix.
- **Installed capacity mix** — donut chart of the 532.7 GW national fleet by source.
- **Regional capacity vs. peak demand** — installed capacity against each grid region's all-time peak-demand record.
- **National peak demand, 2026** — a real monthly time series (Jan–Jul 2026) tracking the two new all-time demand records set in the same quarter.
- **IEX exchange snapshot** — Day-Ahead vs. Real-Time market price and volume for July 2026, plus a live intraday price-range gauge for the current trading day.
- **Renewable capacity additions, FY 2025–26** — the 54.6 GW added this fiscal year, the largest on record.
- **Analyst notes** — four short, data-grounded reads on what the numbers imply for grid flexibility, regional transmission dependence, and market pricing behavior.

## Data & sources

All figures are drawn from public disclosures: Central Electricity Authority (CEA), Ministry of Power / PIB press releases, Grid-India (POSOCO), IEX market snapshots, Mercom India's market coverage, and CERC tariff orders. Every chart card and the merit-order model carry inline source and methodology footnotes. The merit-order stack is explicitly labeled as an illustrative model built from public cost bands — not real plant-level bid data — and the write-up is careful to distinguish IEX's thin, residual marginal price from the system's average cost.

## Built with

Plain HTML/CSS/JS — no frameworks, no build step. Charts (donut, step/line, merit-order stack) are hand-built inline SVG with hover tooltips; everything else is CSS. Typefaces: Archivo, IBM Plex Sans, IBM Plex Mono.

## Author

Rupesh Mishra
