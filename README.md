# Tiny Chess — a 4 KB Python chess engine

[![competition](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Nat3uk1/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Nat3uk1/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01)

An entry for make.fun's [Build the strongest chess engine in 4 KB of Python](https://make.fun/bounty/tiny-chess-01).

`main.py` (4,088 bytes) is a self-contained engine: 0x88 board, negamax alpha-beta with PVS, quiescence search, transposition table, null-move pruning, late-move reductions, a history heuristic for quiet moves, futility and delta pruning, and an evaluation with material, piece-square tables, bishop pair, passed-pawn bonuses by rank, rook open/semi-open file bonuses and a king pawn-shield term. Deterministic, under a ply-scaled node budget.

## License

MIT — see `LICENSE`.
