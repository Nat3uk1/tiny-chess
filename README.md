# Tiny Chess — a 4 KB Python chess engine

[![competition](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Nat3uk1/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Nat3uk1/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01)

An entry for make.fun's [Build the strongest chess engine in 4 KB of Python](https://make.fun/bounty/tiny-chess-01).

`main.py` is the whole engine, packed by `makefun compress` from a readable
source: a 0x88 negamax search with alpha-beta pruning, quiescence over
captures, promotions and check evasions, a transposition table, null-move
pruning, late move reductions, killer and MVV-LVA move ordering, and a
material + piece-square evaluation with the bishop pair. It searches to a
fixed node budget, never a clock, so every replay plays the same moves.
