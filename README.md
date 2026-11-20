# makefun-tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/tianye26/makefun-tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/tianye26/makefun-tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4 KB of Python: 0x88 board, negamax with alpha-beta, quiescence search, a transposition table and killer-move ordering, searching to a fixed node budget per move so every trial replays deterministically.

## Run it

```sh
python3 main.py
```

The trial sets `MAKEFUN_ENV_URL` to the game environment; the engine plays the gauntlet through it and exits when every game is over.

---

<sub>Entered on [make.fun](https://make.fun/?ref=qpfhx3bb&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
