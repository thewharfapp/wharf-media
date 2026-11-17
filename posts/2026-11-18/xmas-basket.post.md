# Wed 18 Nov 2026: TEST (C1): "Brr basket build" (Christmas pitch post)

## Format (for FORMATS.md)
**Brr basket build** (**new**): each item is named and dropped into a basket on the beat (5 items), the basket overflows and topples, everything swaps for one small gift box, and the reveal pops out of it. 10–13s, premise readable in frame 1.

Trend examples (from the brief): [TikTok example](https://www.tiktok.com/@amandaxcanales/video/7703198768618835231) · [Takema, Nov 2026 trends](https://www.takema-studio.com/marques/trends-tiktok-novembre-2026) · [Dexerto explainer](https://dexerto.com/entertainment/what-is-a-burr-basket-on-tiktok-everything-you-need-to-make-one-this-winter-2389950). We copied the structure and pacing only (named items dropping in on the beat, then the reveal). Script, visuals and music are all ours.

## Files
- Video: `/home/claude/run/c1/xmas-basket.mp4`: 1080x1920, 30fps, H.264 (crf 18) + AAC 192k, **12.87s**
- Cover: `/home/claude/run/c1/xmas-basket-cover.png` (frame 1: the question "What's in a trader's Christmas basket?" over the empty basket)
- Source: `/home/claude/run/c1/tools/xmas-basket/` (README.md, capture.js, scene.html, render.js, music.py, mux.sh)

## Caption
Five tools in the basket, or one small box that covers the same jobs: journal, charts, bar replay, backtesting and prop rules. All the trading tools you're paying for separately, in one small subscription. Free plan at thewharf.app; charts and bar replay are Pro.

#tradingjournal #proptrader #daytrading #futurestrading #christmas

## Pinned comment
Which one would you take out of your basket first: the journal, the charts, the replay tool, the backtester or the rules tracker?

## TikTok title (≤ 90 chars)
What's in a trader's Christmas basket? Journal, charts, replay, backtests, rules (80 chars)

## On-screen text (with timings)
| Time (s) | Text |
|---|---|
| 0.00–6.6 | "What's in a trader's / Christmas basket?" (full size from frame 1, shrinks to the top at 1.2–1.6s, fades at 6.43) |
| 1.56–2.68 | "+ a trading journal" |
| 2.63–3.75 | "+ a charting plan" |
| 3.70–4.82 | "+ a replay tool" |
| 4.77–5.89 | "+ a backtester" |
| 5.84–6.43 | "+ a prop rules tracker" |
| 6.43–7.50 | "Bit heavy, / isn't it?" (the basket wobbles and topples) |
| 7.50–8.42 | "Or… one / small box." (gift box, tag with The Wharf logo: "The Wharf", on screen to the end) |
| 8.42–12.87 | "All the trading tools / you're paying for separately, / in one small subscription." (PITCH.md core line) |
| 8.52–9.11 | Card label "Journal" (real trade card) + "Sample data shown" |
| 9.06–9.64 | Card label "Charts" (Wharf chart, cropped to the chart) + "Sample data shown" |
| 9.59–10.18 | Card label "Bar replay" (replay controls) + "Sample data shown" |
| 10.13–12.87 | Card label "Prop rules" (Eval 50K card: drawdown room, today vs daily limit) + "Sample data shown" |
| 11.25–12.87 | "thewharf.app" |
| 11.45–12.87 | "Free plan · charts & bar replay are Pro" |

All text sits inside x 70–940, y 220–1540 (checked against a safe-zone overlay on stills at 0.5s, 6.4s, 9.9s and 12.6s).

## Music
Original, synthesised in numpy/scipy (`music.py`), no samples, no song melody. 112 BPM in F major: sleigh bells on the 8ths, a glockenspiel figure of our own (an arpeggio climbing over F–Dm–Bb), and a pizzicato bass. A soft wicker "thump" and a rising pling on each drop. A creak and shaking bells on the wobble, a wood clatter on the topple, then a whoosh, a bell and a glock glissando when the gift box arrives. A bright Bb–C–F chorus with a small pop for each app screen, and a bell on the end card.

## Timeline
- 0.0–1.6: hook question over an empty wicker basket (pine green, cream and berry red, falling snow, fairy lights)
- 1.6–6.4: five items fall in, one every 2 beats: a journal, a framed chart, a rewind remote, a lab flask and a clipboard
- 6.4–7.5: the basket wobbles, then topples; the items fly out. "Bit heavy, isn't it?"
- 7.5–8.6: a sparkle poof, and one small red gift box with The Wharf tag. "Or… one small box."
- 8.6–10.7: the lid flies off and four real app screens pop out, one per beat (Journal, Charts, Bar replay, Prop rules), under "All the trading tools you're paying for separately, in one small subscription."
- 11.25–12.87: end card: "thewharf.app", "Free plan · charts & bar replay are Pro"

## Compliance notes
- **Pitch:** follows PITCH.md and this week's STRATEGY. **No prices anywhere** (on screen or in the caption): no journal price, no US$62–119 total and no A$ price. Category names only ("a trading journal", "a charting plan", "a replay tool", "a backtester", "a prop rules tracker"). Uses the PITCH.md core line "All the trading tools you're paying for separately, in one small subscription." (see Editor changes for why). The caption says the box "covers the same jobs" and never claims it fully replaces anything. STRATEGY (16–22 Nov) names two lines for pitch posts this week; the core line is used instead because both of those, and the requested replacement, are inside the 14-day window or need a price comparison avoided today. It contains no price.
- **App screens:** real screens from `the-wharf/site` (main at 0ed0f9b) with the mock backend and demo account (`capture.js`, based on tools/organic/shots.js). Every card shows "Sample data shown". Account names are generic (Eval 150K on the trade card, Eval 50K on the prop card), with no firm preset. The chart and replay screens are cropped to the chart card, so the page's third-party chart toggle and data-source line are not shown. No other product's brand appears anywhere.
- The dollar figures on the cards (trade P&L, the sample account balance, the daily limit) are sample account data, not prices.
- Free vs Pro: the end card and caption say charts and bar replay are Pro. No AI features are mentioned. No profit, income or funding promises, no prize or certificate, no countdowns, no Black Friday mention.
- No real people, no voice, no stock or third-party footage, no other creator's content. The music is original and has no Christmas song melody or lyrics.
- The caption opening, hook and joke ("Bit heavy, isn't it?", "Or… one small box.") don't repeat anything in last14.md.
- **AI-generated footage: none.** Everything is drawn in code (canvas) or captured from the real app, so no AI label is needed.
- Today's test: the hook is a question on screen in frame 1. Measure the IG 3s view rate and TT views against the medians (IG 3s 28.5%, TT 216).

## Suggested slot
Melbourne evening, 6–9 pm (or the TEST slot the Manager uses, 12:10 pm).

## Editor changes (ED, 18 Nov)
- **Pitch line swapped (video + caption + notes).** "One subscription instead of three or four." was used on 17 Nov (renewal-day). The requested replacement, "Journal, charts, replay, backtester and prop rules. One app.", is also inside the 14-day window: it is the exact end line of the 11 Nov TEST `posts/2026-11-11/dont-let-tabs-see.mp4` (checked on its frames at 5.5–7s). So I used the PITCH.md **core line** instead: "All the trading tools you're paying for separately, in one small subscription." It is not in any post from the last 14 days, carries no price, and fits the basket (five tools bought separately → one small box; it also echoes "Or… one small box."). On screen as three lines at 8.4–12.9s (68/56/64px, inside x 70–940). If Will or the Manager prefer another line, change the three `txt(...)` calls under "PITCH.md core line" in `scene.html` and re-render (`node render.js full` + `./mux.sh`); timings don't move. Lines used in the last 14 days: 17 Nov "Your trading tools shouldn't cost more than your trading." + "One subscription instead of three or four."; 11 Nov "Journal, charts, replay, backtester and prop rules. One app." Still unused: "Stop paying for three trading subscriptions." and "Less than one journal subscription, and the journal is only part of it."
- **Small gift tags on the basket items removed.** They overlapped as the pile grew (e.g. "journal"/"charts" at 3–5s); the big white caption already names each item on its beat.
- Checked: hook question readable at full size in frame 1; length 12.87s (unchanged, music unchanged); every app card shows "Sample data shown"; no prices on screen or in the caption; nothing in the right 140px, top 220px or bottom 380px (stills at 0.0, 0.5, 2.2, 4.5, 6.0, 6.4, 9.0, 10.2, 10.4, 12.6, 12.7s). Re-rendered from source and re-muxed; cover re-exported from frame 1.
