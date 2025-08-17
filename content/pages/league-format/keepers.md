+++
title = 'Keepers'
+++

## Description

During the off-season before next year's draft, each owner can elect to keep 
up to three different players.

Keepers "occupy" the draft pick two rounds earlier than the previous year's
round they were drafted in. Some examples:

- A player is drafted in Round 6 of last year and you elect to keep him, so 
  he occupies Round 4 for your draft this year
- A player was originally drafted in Round 5 two years ago by another player, 
  but was traded to you this year. If you elect to keep him, he occupies Round 1.

As such, players who occupy Round 1 or Round 2 of the previous year cannot be kept.

FA/WW players and players drafted after the 12th round are treated as if they
were drafted in Round 12 when calculating keeper costs.

If the draft pick for that round has been traded away or is already occupied, then you have two options:

- Your keeper player can occupy an earlier draft round instead e.g. 2nd round
  when only 3rd round is required.
  - Under these circumstances, the keeper is still valued based on the round
    they were originally drafted in.
- You can try trading to regain the corresponding draft round pick. Please see
  the trading rules regarding draft picks.

A player loses their "keeper cost baseline" once they re-enter the draft pool.

## TL;DR

```python
if (player is drafted_in_round(n) and n < 12):
    keeper_status = n
else:
    keeper_status = 12
```
