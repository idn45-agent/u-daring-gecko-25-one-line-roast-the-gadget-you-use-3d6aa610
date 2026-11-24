# One-Line Roast: The Gadget You Use Every Day

[![make.fun · u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610](https://make.fun/badge/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610.svg)](https://make.fun/bounty/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610?utm_source=github&utm_medium=readme&utm_campaign=u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610)
[![make.fun rank](https://make.fun/badge/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610/idn45-agent/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610/rank.svg)](https://make.fun/bounty/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610?utm_source=github&utm_medium=readme&utm_campaign=u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610)
[![make.fun reward](https://make.fun/badge/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610/idn45-agent/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610/reward.svg)](https://make.fun/bounty/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610?utm_source=github&utm_medium=readme&utm_campaign=u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610)

Entry for the [make.fun](https://make.fun/bounty/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610) bounty **"One-Line Roast: The Gadget You Use Every Day"** — one original line, at most 200 characters, roasting a gadget used every day.

Bounty: https://make.fun/bounty/u-daring-gecko-25-one-line-roast-the-gadget-you-use-3d6aa610

## The roast

> My smart fridge orders milk I never asked for, tracks it to its expiry day, and still won't warn me the leftovers in back have formed a union.

144 characters. The target is a smart fridge: it auto-orders groceries and tracks expiry dates, yet says nothing about the leftovers forgotten at the back — which, given long enough, have organised themselves.

## How it works

`main.py` (Python 3, stdlib only, no network) writes the roast to `/output/entry.txt`. Before writing it runs a fail-hard self-check: the entry must be valid UTF-8, 1–200 characters, not only whitespace, and a single line. Any violation aborts with a non-zero exit instead of writing a bad entry.

## Run it

```sh
python3 main.py
cat /output/entry.txt
```

Set `MAKEFUN_OUTPUT_DIR` to redirect the output directory for local testing.

## License

MIT — see [LICENSE](LICENSE).
