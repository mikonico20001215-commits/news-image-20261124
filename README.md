# 24 November 2026 — The World in One Day

A one-image summary of Tuesday 24 November 2026's world news, built for the
make.fun bounty `news-image-20261124`. The image is a newspaper front page:
the date across the masthead, six stories in panels with a short label each,
and a ticker of three more stories along the foot.

## What the image shows

1. **HUANG IS BACK AT NVIDIA** — Nvidia's board reinstates Jensen Huang as
   chief executive; Nvidia shares jump about 30% after pressure from Trump
   and investors to bring him back.
2. **TANKERS HIT BY MINES IN HORMUZ** — Three oil tankers are struck and set
   ablaze in the Strait of Hormuz; Iran refuses talks until its seven
   demands are met.
3. **14 NATIONS BACK ICJ GENOCIDE RULING** — Britain, Spain, Canada and
   eleven more endorse the court's finding that Myanmar committed genocide
   against the Rohingya.
4. **STRIKE HITS ZAPORIZHZHIA FLATS** — An overnight Russian attack on an
   apartment block kills 2 and wounds 40, including four children.
5. **HAMAS SECURITY CHIEF KILLED** — Israeli strikes kill Naeem Abu Nahel
   and six others in Gaza; the UN says the war has undone 77 years of
   human development.
6. **CLIMATE SUMMIT ENDS WITH NO DEAL** — The UN climate summit (COP31)
   collapses after a split over fossil fuels and climate finance.

Ticker: the U.S. loses measles-free status after 25 years; two states sue
SpaceX over Grok images; Sanofi buys Insmed for $41bn.

## How it was made

The image (`entry.png`, 1024×1024 PNG) was composed as a page of flat
illustrations and typeset text drawn for this entry — no photographs or
artwork copied from anywhere — and rendered to PNG. `main.ts` (Node 22,
standard library only) checks the PNG against the gate (whole PNG, at most
1 MiB, at most 1024×1024) and copies it to `/output/entry.png`.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Sources (all reporting on 24 November 2026)

- Just Security, "Early Edition: November 24, 2026" —
  https://www.justsecurity.org/165763/early-edition-november-24-2026/
- The Global Eye, "Global news (24 november 2026)" —
  https://theglobaleye.it/2026/11/24/global-news-24-november-2026/
- Principia, "The news on Tuesday, 24 November 2026" —
  https://principia.news/e/2026-11-24
- Horizon, "World news and markets for 24 November 2026" —
  https://www.horizonapp.link/en/2026/11/24
- All Voices News / Medium, "Global and U.S. Strategic News Brief:
  November 24, 2026" —
  https://medium.com/all-voices-news/global-and-u-s-strategic-news-brief-november-24-2026-d22ad6d00284

## License

MIT — see `LICENSE`.
