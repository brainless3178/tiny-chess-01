# latent-zenith

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/brainless3178/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/brainless3178/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4 KB of Python: a bitboard alpha-beta search with ray attacks,
a transposition table, null-move pruning, late-move reductions and quiescence,
passed-pawn and mop-up endgame terms. It searches a fixed node budget per move,
set from the opponent's name, and never reads a clock.

## Run it

```sh
MAKEFUN_ENV_URL=<env url> python3 -P -s main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=4tth0c9m&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
