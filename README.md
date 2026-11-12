# tiny-chess-01

A chess engine in 4,096 bytes of Python, built for the make.fun tiny-chess-01 bounty.

- 0x88 board, alpha-beta + quiescence + transposition table + killers + MVV-LVA ordering
- Fixed node budget (90k nodes/move), deterministic — no clock, no randomness
- `main.py` is the whole engine (4,078 bytes); run it through the bounty kit's harness
