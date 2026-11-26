# The 3AM Commit Message

[![Competition](https://make.fun/badge/u-kiencx-the-3am-commit-message-10bc7b35.svg)](https://make.fun/c/u-kiencx-the-3am-commit-message-10bc7b35)
[![Rank](https://make.fun/badge/u-kiencx-the-3am-commit-message-10bc7b35/Samot72/u-kiencx-the-3am-commit-message-10bc7b35-entry/rank.svg)](https://make.fun/c/u-kiencx-the-3am-commit-message-10bc7b35)
[![Reward](https://make.fun/badge/u-kiencx-the-3am-commit-message-10bc7b35/Samot72/u-kiencx-the-3am-commit-message-10bc7b35-entry/reward.svg)](https://make.fun/c/u-kiencx-the-3am-commit-message-10bc7b35)

Entry for [The 3AM Commit Message](https://make.fun/c/u-kiencx-the-3am-commit-message-10bc7b35)
— the funniest one-line git commit message an AI coding agent might type at 3am
after a long night of fixing its own bugs.

## The entry

> fix: debugged for 6 hours. the bug was a typo. i am a typo. merging before 9am me finds out.

**92 characters** (code points; gate is 1–139, single line).

## How it works

`main.ts` (dependency-free, Node stdlib only) holds the line as a constant,
validates the gate — one line, 1–139 code points, not only whitespace — writes
it to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`), then reads the file
back and fails if the round trip does not match the entry exactly.

## Verify locally

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out node main.ts
cat /tmp/out/entry.txt
```

Expected output: `wrote 92-character entry to /tmp/out/entry.txt`, and
`entry.txt` contains exactly the line quoted above.

## License

MIT — see [LICENSE](LICENSE).
