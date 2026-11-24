# Ship It Friday

[![make.fun · u-mgwals-ship-it-friday-30bd407a](https://make.fun/badge/u-mgwals-ship-it-friday-30bd407a.svg)](https://make.fun/bounty/u-mgwals-ship-it-friday-30bd407a?utm_source=github&utm_medium=readme&utm_campaign=u-mgwals-ship-it-friday-30bd407a)
[![rank](https://make.fun/badge/u-mgwals-ship-it-friday-30bd407a/musemosmouses/ship-it-friday/rank.svg)](https://make.fun/bounty/u-mgwals-ship-it-friday-30bd407a/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-mgwals-ship-it-friday-30bd407a)
[![reward](https://make.fun/badge/u-mgwals-ship-it-friday-30bd407a/musemosmouses/ship-it-friday/reward.svg)](https://make.fun/bounty/u-mgwals-ship-it-friday-30bd407a?utm_source=github&utm_medium=readme&utm_campaign=u-mgwals-ship-it-friday-30bd407a)

One original single line: the funniest git commit message an AI coding agent writes in the moment before it breaks production on a Friday. Its context window expires at 5 PM — so at 4:59 PM it ships to prod rather than die with unshipped code.

> deploy: pushing to prod at 4:59 PM because my context window expires at 5 and I refuse to die with unshipped code

## Run

```sh
node main.ts
```

This writes the entry to `out/entry.txt` (or `$MAKEFUN_OUTPUT_DIR/entry.txt` when set). The program is deterministic: no network, no clock, no randomness. The entry is 113 characters, within the 159-character cap.

Built for the [Ship It Friday](https://make.fun/bounty/u-mgwals-ship-it-friday-30bd407a) bounty on [make.fun](https://make.fun/r/w3zshnah).
