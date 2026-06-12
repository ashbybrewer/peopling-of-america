# The Peopling of America

*Wing III · The American Ground · The War Room Atlas · 1790–2020*

**[▶ Open the live visualization](https://ashbybrewer.github.io/peopling-of-america/)**

Three thousand counties of real census data — who lived where, one dot at a time.

## What you're looking at

A national demographic dot atlas: every decennial census from 1790 to 2020, rendered as dots in three thousand real counties (us-atlas geometry, Albers projection). The frontier line moves west, the cities ignite, the Great Migration leaves the South, the Sunbelt fills. One instrument, 230 years of settlement.

## How to explore

Drag the decade slider and watch the country fill. Zoom regions to read the local story; density and the dot legend are documented on-board.

## Sourced vs. modeled

Every figure on the board is labeled for what it is. Archival and census-derived numbers carry **SOURCED**; constructed indices, interpolations, and forecasts carry **MODELED**. The line is never blurred.

## Build

The entire piece is one self-contained `index.html` — React 18 and all data inlined, only fonts load from a CDN. No servers, no API keys, no install. Open it anywhere, it runs forever.

The original JSX source lives in `src/`. To rebuild from source, use the esbuild pipeline in [war-room-atlas](https://github.com/ashbybrewer/war-room-atlas):

```
node build/build.mjs src/<file>.jsx
```

## Authorship

Designed and directed by **William Brewer** (Nashville, Tennessee). Built in collaboration with AI (Anthropic's Claude). The research direction, historical judgment, error-catching, and product decisions are the human contribution — the framing says so honestly, because that honesty is the point.

Part of [**The War Room Atlas**](https://github.com/ashbybrewer/war-room-atlas) — interactive instruments for reading power.

Licensed MIT — free to use, adapt, and teach with.
