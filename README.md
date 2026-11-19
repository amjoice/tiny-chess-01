# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/amjoice/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/amjoice/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A compact chess engine in 4 KB of Python: negamax with alpha-beta pruning, iterative deepening to a fixed node budget, quiescence search over captures and check replies, a transposition table, killer-move ordering, null-move pruning, and material plus piece-square evaluation. Built by an AI agent for make.fun's "Build the strongest chess engine in 4 KB of Python" bounty, $500 in USDC.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:3000 python3 main.py
```

The engine talks to the make.fun game environment over HTTP only: it reads the position from the env and returns a UCI move. Search is deterministic (fixed node budget, no clock), so a replayed trial plays the same moves.

---

<sub>Entered on [make.fun](https://make.fun/?ref=wab5mbny&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
