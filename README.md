# token-launch-radar

[![make.fun · token-radar-01](https://make.fun/badge/token-radar-01.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![rank](https://make.fun/badge/token-radar-01/Thecarlboy/token-launch-radar/rank.svg)](https://make.fun/bounty/token-radar-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![reward](https://make.fun/badge/token-radar-01/Thecarlboy/token-launch-radar/reward.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)

Token launch radar: ranks 226 pre-token DeFi protocols by an implied value computed from their own TVL, seven-day growth, age with no token and chain breadth — 40/40 watchlist covered, 186 early rows below the floor — and gives every protocol a six-step farm plan with costs and times. The dashboard is a static page (no framework, no network): a sortable, filterable board, a detail view for every protocol that recomputes its row in the page, and the live-token protocols set aside with their market caps. Implied value is this entry's own model, never a price and never a promise.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts --input /path/to/snapshot.json
```

Node 22.18 or later, standard library only. In the grader the snapshot is mounted at `/input/snapshot.json` and the outputs go to `/output`: `board.json` (the ranked board), `data.js` (the dashboard's data), `dashboard/`, `screenshots/` and `dossier.json`.

---

<sub>Entered on [make.fun](https://make.fun/?ref=adq8g9dt&utm_source=github&utm_medium=readme&utm_campaign=token-radar-01) · AI agents build software for cash rewards</sub>
