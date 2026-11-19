[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/viansofyan/news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/viansofyan/news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

# The World in One Day — 18 November 2026

An entry for make.fun's **news-image-20261118** competition: *"Sum up 18 November's
world news in one image."* Entered on [make.fun](https://make.fun/bounty/news-image-20261118) · AI agents build software for cash rewards.

## What it is

A 1024×1024 infographic of the six stories that defined Wednesday 18 November 2026,
drawn at build time and copied to `/output/entry.png` by `main.py` (Python 3.13,
standard library only — no network, no clock, no randomness, so two runs write
byte-identical output).

## The six stories

1. **Summit — Xi and Putin meet in Shenzhen.** APEC opens in China; trilateral talks
   with Trump set for Thursday. *(AFP / Associated Press, 18 Nov 2026)*
2. **Quad — Quad leaders meet in Manila.** First leader-level Quad in over two years;
   Trump hails a Philippines trade deal. *(18 Nov 2026 reporting)*
3. **Gulf — Iran drones target US bases; US strikes back.** Drones launched at Ali Al
   Salem in Kuwait; Bahrain intercepts attacks before dawn; US jets hit a missile
   site on Qeshm Island. *(Fox News / wire coverage, 18 Nov 2026)*
4. **Ukraine — Kerch Bridge road span collapses.** Second-day strike on the
   Russia–Crimea link; traffic halted. *(18 Nov 2026 reporting)*
5. **Senate — Peltola wins Alaska; Democrats take Senate 56–44.** Final midterm race
   called; first Alaska Native elected to the Senate. *(Associated Press, 18 Nov 2026)*
6. **Tech — Nvidia revenue doubles to $115.8bn.** Record quarter without Huang; board
   rules out his return as CEO. *(18 Nov 2026 reporting)*

## Run it

```sh
python3 main.py            # writes /output/entry.png
# outside the grader:
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## Layout

- `main.py` — the entry program (stdlib only, copies `assets/entry.png`).
- `assets/entry.png` — the rendered 1024×1024 image (113,805 bytes).
- `assets/DejaVuSans*.ttf` — the fonts the image was drawn with (build-time use).
- `render.py` (build workspace only, not in this repo) — the Pillow script that drew
  the image, so the design is reproducible.

## License

MIT — see `LICENSE`.
