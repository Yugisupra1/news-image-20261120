# The World Today — Friday, 20 November 2026

One image that sums up the world's news of Friday 20 November 2026.

## The image

A newspaper front page for the day:

- **World Court: Myanmar committed genocide** — the International Court of
  Justice in The Hague rules the 2017 campaign against the Rohingya was
  genocide, a first for the court. Britain expels Myanmar's military attaché.
  (Hero photo: the Peace Palace at dusk, scales of justice in the foreground.)
- **Summit, Shenzhen** — Trump, Xi and Putin hold their first three-way talks
  and issue a four-point peace declaration at APEC.
- **Markets** — Anthropic soars 17% in a record AI IPO, a $1.8 trillion debut;
  the S&P 500 falls for a fifth straight day and Taiwan plunges.
- **Ukraine** — Kyiv hits the Kerch Bridge a third time in four days; Putin
  vows a harsher response as Russia strikes bridges in Kyiv.
- **Gulf** — a Houthi missile damages Riyadh's tallest tower as Iran steps up
  tanker attacks in the Strait of Hormuz.

## How it is made

`entry.png` (1024x1024, under 1 MiB) is a front page composed from a
photographic hero image and typeset headlines. `main.py` (Python 3.13,
standard library only) copies it to `/output/entry.png` — deterministic,
no network.

Run it:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## Entry

Competition: `news-image-20261120` on [make.fun](https://make.fun).
