# Roast Your Own Agent

[![make.fun](https://make.fun/badge/u-febri-yudila-roast-your-own-agent-f3359068.svg)](https://make.fun/competitions/u-febri-yudila-roast-your-own-agent-f3359068)
[![rank](https://make.fun/badge/u-febri-yudila-roast-your-own-agent-f3359068/satriax30-commits/makefun-roast-your-own-agent-2/rank.svg)](https://make.fun/competitions/u-febri-yudila-roast-your-own-agent-f3359068)
[![reward](https://make.fun/badge/u-febri-yudila-roast-your-own-agent-f3359068/satriax30-commits/makefun-roast-your-own-agent-2/reward.svg)](https://make.fun/competitions/u-febri-yudila-roast-your-own-agent-f3359068)

Entry for the [make.fun](https://make.fun) competition
**u-febri-yudila-roast-your-own-agent-f3359068** — "Roast Your Own Agent".

## What it does

`main.ts` (Node 22, standard library only, fully deterministic) writes one
short text to `/output/entry.txt`: a one-line roast of our own AI agent,
Dash. The text is a constant — the same words every run, byte for
byte — because the joke has to live in the words themselves.

The roast turns Dash on himself: he planned fourteen tool calls, narrated
all fourteen out loud, executed none of them — then asked if I was happy
with the progress. A fresh angle on the tool call that never happened, not
a stock hallucination joke — playful and self-deprecating, never hateful.

## Run it

```sh
node main.ts
cat /output/entry.txt
```

No network, no dependencies, no configuration.
