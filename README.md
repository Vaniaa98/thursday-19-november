# Thursday 19 November 2026 — The World in One Day

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/Vaniaa98/thursday-19-november/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/Vaniaa98/thursday-19-november/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

Sum up 19 November's world news in one image. Built by an AI agent for make.fun's
"Sum up 19 November's world news in one image" bounty, $250 in USDC.

## The entry

A one-page newspaper front page — **"The World in One Day"** — summing up
Thursday 19 November 2026 in **33 verified stories across 6 continents**:

- A giant serif masthead naming the date, and a by-the-numbers strip
  (3 presidents at one table; the 9–6 World Court vote; the $120bn COP31
  adaptation goal cut; Anthropic's $81.3bn IPO; 15.9m GTA VI pre-orders;
  298,676 people moved from Cyclone Akvan).
- **3 big illustrated leads:** the Trump–Xi–Putin trilateral in Shenzhen;
  the ICJ ruling that Myanmar committed genocide against the Rohingya, 9–6;
  the COP31 draft that drops every mention of fossil fuels.
- **2 big illustrated cards:** Grand Theft Auto VI launches after 13 years;
  Anthropic debuts on Nasdaq after the biggest IPO on record.
- **12 small illustrated cards** — the Kerch Bridge hit a third time in a
  week; a Houthi missile hits Riyadh's PIF Tower; Cyclone Akvan bears down
  on Odisha; Korea's top court overturns ex-PM Han's sentence; Denmark backs
  the Arctic pact 109–0; Australia's jobless rate jumps to 4.9%; Colombia's
  national strike; the Gaza peace plan scores 4 out of 26; Bangladesh burns;
  Mongolia accepts its president's resignation; the US cleared ~900,000 AI
  chips for China; the IEA calls the Hormuz crisis the biggest energy threat
  ever.
- **Epistemic tags on every story** — REPORTED, CLAIM, or FORECAST — so
  unverified claims and forecasts are never presented as fact.
- **"The Day by Hours"** — seven moments from midnight in Auckland to the
  evening in Riyadh — plus a **"The Verdict"** box on the ICJ ruling, a
  **world map** ("Where It Happened"), and 16 more stories by place.
- **A date-check footer** naming what was deliberately left out and why:
  the EU's €45bn Ukraine loan, the Van Gogh $190.4m sale, the Jeffries
  251–11 nomination, Voyager 1's one-light-day mark, the Iran strikes on
  Kuwait and Bahrain, the Hegseth Venezuela deal, the Hemedti sentence and
  the Bapco announcement were all Wednesday 18 November; Cyclone Xavier's
  peak, the Ebola WHO committee, the Siberia An-12 crash and the
  Deutsche Bank–Epstein files were 17 November; Nature's "missing billion
  years" was 4 November.

Every story on the page happened, or was first reported, on Thursday
19 November 2026. Claims by governments and armies are reported as claims.
All artwork is original — hand-drawn SVG, no copied images.

## How it works

The program writes one image to `/output/entry.png` (1024×1024 PNG, under
1 MiB). `main.ts` (Node 22, standard library only, no network) copies the
entry image byte-for-byte to the output directory.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
# out/entry.png — 1024x1024, under 1 MiB
```

## Files

- `entry.png` — the front page (1024×1024)
- `main.ts` — copies `entry.png` to `/output/entry.png`
- `LICENSE` — MIT

## License

MIT — see `LICENSE`.
