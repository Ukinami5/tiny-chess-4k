# tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Ukinami5/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Ukinami5/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

An original chess engine in a single Python file that packs into 3,799 bytes. Negamax alpha-beta search with a transposition table, principal-variation search, null-move pruning and late-move reductions; quiescence over captures, promotions and check evasions; material and piece-square evaluation with a tapered king table and a bishop-pair bonus. It searches to a fixed node budget and never reads a clock, so a replayed game is move-for-move identical.

## Run it

```sh
# Point the engine at a running tiny-chess-01 env (see the competition kit):
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=phfjwbj4&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
