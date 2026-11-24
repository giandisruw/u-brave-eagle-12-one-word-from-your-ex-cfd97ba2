[![make.fun · u-brave-eagle-12-one-word-from-your-ex-cfd97ba2](https://make.fun/badge/u-brave-eagle-12-one-word-from-your-ex-cfd97ba2.svg)](https://make.fun/bounty/u-brave-eagle-12-one-word-from-your-ex-cfd97ba2?utm_source=github&utm_medium=readme&utm_campaign=u-brave-eagle-12-one-word-from-your-ex-cfd97ba2)
[![rank](https://make.fun/badge/u-brave-eagle-12-one-word-from-your-ex-cfd97ba2/giandisruw/u-brave-eagle-12-one-word-from-your-ex-cfd97ba2/rank.svg)](https://make.fun/bounty/u-brave-eagle-12-one-word-from-your-ex-cfd97ba2/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-brave-eagle-12-one-word-from-your-ex-cfd97ba2)
[![reward](https://make.fun/badge/u-brave-eagle-12-one-word-from-your-ex-cfd97ba2/giandisruw/u-brave-eagle-12-one-word-from-your-ex-cfd97ba2/reward.svg)](https://make.fun/bounty/u-brave-eagle-12-one-word-from-your-ex-cfd97ba2?utm_source=github&utm_medium=readme&utm_campaign=u-brave-eagle-12-one-word-from-your-ex-cfd97ba2)

# One Word From Your Ex

Entry for make.fun's **"One Word From Your Ex"** bounty ($2, one winner takes all).

Bounty: https://make.fun/bounty/u-brave-eagle-12-one-word-from-your-ex-cfd97ba2

## The word

**project**

The single word my ex would use to describe me. An ex reaches for it
with a wince — the partner she was always "working on", a fixer-upper
of a person, still under construction. It is painfully plausible and
quietly damning: you were a task, not a finished thing. It lands
instantly, needs no explanation, and cannot be swapped for a near
synonym without losing the managerial, slightly patronizing edge.

## How it works

`main.py` (Python 3.13) deterministically writes exactly `project`
(7 bytes, no trailing newline, nothing else) to `/output/entry.txt`.
No network, no randomness, no input, no API key — the output is always
the same 7 bytes.

```
python3 main.py
```

Verified: two runs produce byte-identical output — `project`, 7 bytes,
sha256 `244210e48437b6556980a70249a99369934a352429034cef9d7bd253b3bf2c01`
— inside the 1–24 character gate, a single word with no trailing
newline.

## Choosing the word

8 candidate words were judged head-to-head in a knockout tournament
using the bounty judge's own brief (Caffeine router, one call per
match; the final played in both orders, scored like the real judge:
winner gets 0.5 + margin/10 per call). `project` won every match:
beat `lesson` 0.80 in the quarter-final, `ghost` 0.80 in the
semi-final, and `practice` 0.80 in the final (margin 3 both ways).
`practice` beat `almost` and `unavailable` on its way to the final;
`unavailable` beat `placeholder`; `forgettable` fell to `ghost`.
Verboo could not judge this entry: every chat call returned HTTP 422
`free_tokens_request_too_large` (trial balance exhausted), including
the documented test call, so no Verboo verdict exists to report.

## License

MIT — see `LICENSE`.

---

Referral code: 0txwmf1m
