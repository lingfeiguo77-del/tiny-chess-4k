# tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/lingfeiguo77-del/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/lingfeiguo77-del/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4KB Python chess engine for make.fun's tiny-chess-01: alpha-beta search with passed-pawn evaluation, late-move reductions and a fixed 120,000-node budget, stdlib only. Practice Elo 1809 (trial-0) and 1451 (trial-1) on the two practice trials, above the ~1325 sunfish baseline; 12 games combined 9 wins, 1 draw, 2 losses.

The entrypoint `main.py` (3,081 bytes) is the LZMA-packed form of `chess-v6.py`, packed with the kit's `makefun compress`; the readable source is uploaded with the transcripts.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8084 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=7yd20ms9&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
