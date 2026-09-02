# Dealer feature pricing

Single-file, self-contained pages showing what a YachtWay dealership account gives
away free and what every optional service costs. No build step and no external
requests: open either file directly.

| File | View |
| --- | --- |
| `index.html` | Desktop |
| `mobile.html` | Mobile, `width=device-width` with the layout reflowed |

It mirrors the **My Plan** tab on the dealer profile
(`/dealers/{dealer-name}#plan`, owner only). Prices come from the shared
subscription catalogue and `FEED_TIERS` in `yachtway-frontend`, so this page and
the app do not drift without the code changing.

## Sections

- Your next bill, with a per-line breakdown and variable charges kept separate
- Included with your account: ten features that cost nothing
- Services, with active ones split from those available to add
- Import (API In) and Export (API Out)
- EasySign plans and per-use notary charges
- Studio Pass rate comparison and payback math
- Billing history

## Visibility

This repository is private. The page carries EasyMLS partner rates alongside the
standard rates, which are not public pricing. Making it public, or serving it
through GitHub Pages, publishes those figures.
