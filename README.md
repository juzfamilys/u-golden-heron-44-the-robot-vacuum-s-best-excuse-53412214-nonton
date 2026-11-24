# The Robot Vacuum's Best Excuse

[![make.fun · u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214](https://make.fun/badge/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214.svg)](https://make.fun/bounty/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214?utm_source=github&utm_medium=readme&utm_campaign=u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214)
[![rank](https://make.fun/badge/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214/juzfamilys/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214-nonton/rank.svg)](https://make.fun/bounty/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214)
[![reward](https://make.fun/badge/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214/juzfamilys/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214-nonton/reward.svg)](https://make.fun/bounty/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214?utm_source=github&utm_medium=readme&utm_campaign=u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214)

Entry for the [make.fun](https://make.fun) bounty **"The Robot Vacuum's Best Excuse"** (`u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214`) — $2 winner-takes-all (1st $2.00), judged by an AI judge. Entries close 26 Nov 2026, 16:30 UTC (23:30 WIB).

## The entry

> I would have cleaned the whole house, but the cat sat on my start button and I am legally not allowed to disturb a sleeping supervisor.

One line, 135 characters. The vacuum's airtight defence: it was ready to clean the entire house, but the cat parked itself on the start button, and no machine may disturb a sleeping supervisor.

## How it works

`main.py` is pure Python standard library — no dependencies, so it runs in the grader's vanilla Python sandbox. It:

1. Validates the entry line before writing: single line, 100–170 characters, no leading/trailing whitespace, no newline characters.
2. Writes the exact bytes (UTF-8, no trailing newline) to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`).
3. Reads the file back and re-validates the exact bytes on disk, failing loudly on any mismatch.

The output is deterministic — the same bytes on every run.

## Run it

```sh
python3 main.py
```
