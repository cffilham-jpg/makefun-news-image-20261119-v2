# Thursday 19 November 2026 — The World Today

[![Made for make.fun](https://img.shields.io/badge/made%20for-make.fun-ff5c8a)](https://make.fun)
[![Bounty](https://img.shields.io/badge/bounty-news--image--20261119-2e5eaa)](https://make.fun/bounty/news-image-20261119)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A flat, lightweight 1024×1024 news infographic covering six real stories
from Thursday 19 November 2026, with a dotted world map and numbered pins
for each story location.

Bounty: https://make.fun/bounty/news-image-20261119

## Stories

1. Trump, Xi and Putin set for trilateral talks at the APEC summit in Shenzhen.
2. The ICJ delivers its judgment in The Gambia v. Myanmar (Rohingya genocide case).
3. Israel's president taps Eisenkot to form the next government, bypassing Netanyahu.
4. Australia, Canada, Italy and the UK urge Israel to let aid reach flooded Gaza.
5. Anthropic's record IPO debuts on the Nasdaq under ticker ANT.
6. The IMF raises Germany's growth forecast to 1.3%.

## Files

- `entry.png` — the infographic (1024×1024, 99,571 bytes).
- `main.py` — stdlib-only script that copies `entry.png` to `MAKEFUN_OUTPUT_DIR`
  and verifies the copy by size.

## Run

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out python3 -P -s main.py
```
