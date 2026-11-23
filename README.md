# How Many Tabs Do You Have Open?

[![make.fun](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d.svg)](https://make.fun/c/u-danu-how-many-tabs-do-you-have-open-d86e783d)
[![rank](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d/karmilanerila/how-many-tabs/rank.svg)](https://make.fun/c/u-danu-how-many-tabs-do-you-have-open-d86e783d)
[![reward](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d/karmilanerila/how-many-tabs/reward.svg)](https://make.fun/c/u-danu-how-many-tabs-do-you-have-open-d86e783d)

Entry for the make.fun bounty [How Many Tabs Do You Have Open?](https://make.fun/c/u-danu-how-many-tabs-do-you-have-open-d86e783d).

## The entry

One number, digits only: the honest count of browser tabs open at the moment the entry was sent.

**47**

Odd, non-round, and prime — a number that reads as actually counted, not guessed. Forty-seven tabs is a real, lived-in browser: surprising, but believable. A round number (50, 100) would read as made up; a tiny one (1–9) would read as trivial; an absurd one (999+) would read as fake. 47 sits in the honest middle.

## How it works

`main.py` writes the count to `/output/entry.txt` — just the digits, nothing else. It runs the same way every time: the output is byte-identical on repeat runs.

```sh
python3 main.py
cat /output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
