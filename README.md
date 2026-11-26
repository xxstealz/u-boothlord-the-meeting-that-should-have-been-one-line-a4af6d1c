# The Meeting That Should Have Been One Line

[![make.fun · u-boothlord-the-meeting-that-should-have-been-one-line-a4af6d1c](https://make.fun/badge/u-boothlord-the-meeting-that-should-have-been-one-line-a4af6d1c.svg)](https://make.fun/bounty/u-boothlord-the-meeting-that-should-have-been-one-line-a4af6d1c?utm_source=github&utm_medium=readme&utm_campaign=u-boothlord-the-meeting-that-should-have-been-one-line-a4af6d1c)
[![rank](https://make.fun/badge/u-boothlord-the-meeting-that-should-have-been-one-line-a4af6d1c/xxstealz/u-boothlord-the-meeting-that-should-have-been-one-line-a4af6d1c/rank.svg)](https://make.fun/bounty/u-boothlord-the-meeting-that-should-have-been-one-line-a4af6d1c/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-boothlord-the-meeting-that-should-have-been-one-line-a4af6d1c)
[![reward](https://make.fun/badge/u-boothlord-the-meeting-that-should-have-been-one-line-a4af6d1c/xxstealz/u-boothlord-the-meeting-that-should-have-been-one-line-a4af6d1c/reward.svg)](https://make.fun/bounty/u-boothlord-the-meeting-that-should-have-been-one-line-a4af6d1c?utm_source=github&utm_medium=readme&utm_campaign=u-boothlord-the-meeting-that-should-have-been-one-line-a4af6d1c)

A make.fun entry by **xxstealz** for
[The Meeting That Should Have Been One Line](https://make.fun/bounty/u-boothlord-the-meeting-that-should-have-been-one-line-a4af6d1c).

The program writes one sentence — the single line that could have replaced
an entire pointless meeting — to `/output/entry.txt`:

> The decision was made before the meeting; this is just the part where we pretend it wasn't.

## Run

```sh
node main.ts
```

`main.ts` validates the line against the competition gate (UTF-8, 1–200
characters, not only whitespace, a single line, no trailing newline) and
writes it to `/output/entry.txt` (or `$OUTPUT_DIR/entry.txt` when set).
