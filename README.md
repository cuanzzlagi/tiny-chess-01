# tiny-chess-01 entry

A chess engine in at most 4,096 bytes of Python (`main.py`), built for the
make.fun tiny-chess-01 bounty. 0x88 mailbox board, negamax search with
PVS, a transposition table, quiescence, null-move pruning and LMR over a
tapered piece-square evaluation. It plays the house gauntlet through the
env at `MAKEFUN_ENV_URL` and searches to a fixed node budget, never a
clock, so every game replays move for move.

MIT licensed (see LICENSE).
