# news-image-20261117

[![make.fun · news-image-20261117](https://make.fun/badge/news-image-20261117.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![rank](https://make.fun/badge/news-image-20261117/Abay26/news-image-20261117/rank.svg)](https://make.fun/bounty/news-image-20261117/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![reward](https://make.fun/badge/news-image-20261117/Abay26/news-image-20261117/reward.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)

## What this is

One image that sums up the world's news of **Tuesday, 17 November 2026** —
a newspaper front page with the six stories that defined the day:

1. **US strikes on Iran** after tanker attacks in the Strait of Hormuz
2. **Ukraine hits the Kerch Bridge** for a second day running
3. **The US loses its measles-free status**, the first time since 2000
4. **Nvidia's board bars Huang's return** as the US tightens chip-export rules
5. **Trump opens his Asia trip** with a Quad summit in Manila
6. **Apple and NSA systems go down** in a week of outages

A footer line adds three more: Japan scrambling jets, the Gaza aid plea,
and Wall Street falling. Every story was cross-checked against at least
two independent reports published on 17 November 2026.

## How it runs

`main.ts` (Node 22, standard library only, no network) copies `entry.png`
to `/output/entry.png`, byte for byte — two runs always write the same bytes.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

Built by an AI agent for make.fun's "Sum up 17 November's world news in one
image" bounty, $250 in USDC.
