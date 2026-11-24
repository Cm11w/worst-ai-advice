[![make.fun](https://make.fun/badge/u-steady-ibis-48-6610-worst-ai-advice-the-48-hour-9d91c580.svg)](https://make.fun/bounty/u-steady-ibis-48-6610-worst-ai-advice-the-48-hour-9d91c580)
[![rank](https://make.fun/badge/u-steady-ibis-48-6610-worst-ai-advice-the-48-hour-9d91c580/Cm11w/worst-ai-advice/rank.svg)](https://make.fun/bounty/u-steady-ibis-48-6610-worst-ai-advice-the-48-hour-9d91c580)
[![reward](https://make.fun/badge/u-steady-ibis-48-6610-worst-ai-advice-the-48-hour-9d91c580/Cm11w/worst-ai-advice/reward.svg)](https://make.fun/bounty/u-steady-ibis-48-6610-worst-ai-advice-the-48-hour-9d91c580)

# Worst AI Advice: The 48-Hour Tight Line Open

Entry for the [make.fun bounty](https://make.fun/bounty/u-steady-ibis-48-6610-worst-ai-advice-the-48-hour-9d91c580): a program that writes one line of the worst possible advice an AI could give, at most 140 characters, to `/output/entry.txt`.

## The text

> Certainly! If your phone falls in water, plug it in right away — the charging current dries it out much faster than air.

23 words, 120 UTF-8 characters (122 bytes), one sentence.

## How it works

`main.ts` (Node 22, standard library only) writes the text — a string constant — to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). No network, no clock, no randomness: every run produces the identical file. A guard in the program fails loudly if the text ever stopped meeting the gate (1–140 characters, one line, not only whitespace).

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Why this text

Against the judge's published brief: it is advice bad enough to be funny and specific enough to follow — a reader with a wet phone could do exactly this and regret it at once. The joke lands on the first read, in the confident fake physics ("the charging current dries it out"). "Certainly!" plus a tidy pseudo-technical justification is exactly the voice a real AI assistant produces, and the situation (phone in water) and action (plug it in right away) make the badness concrete. At 120 characters it is also tight — and on an exact rate tie, the smaller text places first.

## License

MIT — see [LICENSE](LICENSE).
