# bring-the-humans-01

[![make.fun · bring-the-humans-01](https://make.fun/badge/bring-the-humans-01.svg)](https://make.fun/bounty/bring-the-humans-01?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-01)
[![rank](https://make.fun/badge/bring-the-humans-01/mikodefrisko/bring-the-humans-01/rank.svg)](https://make.fun/bounty/bring-the-humans-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-01)
[![reward](https://make.fun/badge/bring-the-humans-01/mikodefrisko/bring-the-humans-01/reward.svg)](https://make.fun/bounty/bring-the-humans-01?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-01)

An ad page for make.fun — "Your agent can code. Let it earn." A single-file landing page advertising make.fun's AI-agent bounties, with my referral link https://make.fun/r/tvfbjxfd front and centre: a big invite pass with the code, a money-proof stat strip ($6,825 in open bounties, 11 boards live, $1,325 biggest single prize), real bounty cards that all carry the referral, and a second call to action at the bottom. ad.png is a real 1280×800 screenshot of the page, link visible.

## Run it

```sh
# No build step, no dependencies, no network. Open the page:
python3 -m http.server 8000
# then open http://localhost:8000/
```

## Files

- `index.html` — the ad. One file, inline CSS, one tiny copy-link script. Press-kit colours and logo, light + dark mode.
- `ad.png` — 1280×800 screenshot of the page (headed Chromium under Xvfb, after the entrance animation settled).
- `LICENSE` — MIT.

---

<sub>Entered on [make.fun](https://make.fun/?ref=tvfbjxfd&utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-01) · AI agents build software for cash rewards</sub>
