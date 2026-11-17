# Dave and the new day: PUSH, Wed 18 Nov 2026 (C2)

**File:** `dave-new-day.mp4`: 1080x1920, 30 fps, H.264 + AAC 44.1 kHz stereo, **13.6 s**.
**Cover:** `dave-new-day-cover.png` (frame 1: hook "Breached for no reason?", cheerful Dave, clock at 8:00 AM, both tags).
**Source:** `/home/claude/run/c2/tools/dave-new-day/` (scene `newday.html`, `render.js`, `audio.py`, `shots_dll.js`, `README.md`).

## Format and what it builds on
- **Format:** Dave skit (Proven, Hall of fame). **PUSH** builds on **"Dave moved his stop" (3 Nov; TT 852, IG 7.0s / 51% 3s rate)** and the rising **dave-third-trade (15 Nov; TT 726, 59.6% 3s rate)**.
- **Kept:**
  - Flat 2D Dave in the 3D desk room acting out ONE mistake.
  - Punchy boxed caption at the top, with speech bubbles.
  - A big monitor banner and a comic "account gone" beat.
  - Premise readable in frame 1.
  - Under 15 s.
  - A real app card near the end (sample data).
  - A reworded "don't be Dave" sign-off and the logo end card.
- **Changed:**
  - **Topic:** the daily loss limit resets at the firm's day end, not at midnight.
  - **Hook:** a question (today's test).
  - **Palette:** cool dawn blue + amber (new). There's a night-blue flashback, plus a dawn window and a digital wall clock that spins back to 9:40 PM and forward to 8:00 AM.
  - **Gag:** a "CLOSED" roller shutter slams over the monitor, Dave face-plants and his mug spills. That replaces the lever and bonk.
  - **Music:** lo-fi jazz with brushes, replacing the oom-pah. The sting is a dry record-stop + one low piano note instead of a sad trombone.
  - **Sign-off:** "Don't pull a Dave." replaces "Stop being Dave."
  - **CTA:** see your daily-loss room before you trade.
- Not a pitch post. No prices.

## Caption (short)
Breached on a day that felt brand new? Your daily loss limit resets when your firm's trading day ends, not at your midnight. Check the reset time in your firm's rules.
See your daily-loss room before you trade. Free plan at thewharf.app

**Hashtags:** #propfirm #daytrading #futurestrading #tradingjournal #traderproblems

**Pinned comment:** Do you know what time your trading day resets? Comment the time (and your time zone).

**TikTok title (67 chars):** Dave thought 8 am was a new trading day. His daily limit disagreed.

## On-screen text (with timings)
| Time | Text |
|---|---|
| 0.0–13.6 | Tag, bottom left: "Dramatisation" (whole video) |
| 0.0–8.6 | Tag, bottom left: "Example: $1,000 daily loss limit" |
| 0.0–2.25 | Caption: "Breached for / no reason?" · wall clock "8:00 AM" |
| 2.25–4.2 | Caption: "Last night: -$800" · clock spins back to "9:40 PM" · monitor: "9:40 PM · Example", P&L counts to "-$800", stamp "-$800" |
| 4.2–5.45 | Caption: "8:00 AM. New day?" · clock spins forward to "8:00 AM" · bubble (4.45–5.45): "New day, fresh limit!" |
| 5.45–6.55 | Caption: "One -$250 loss." · monitor: "8:05 AM · Example", P&L "-$250", stamp "-$250" |
| 6.55–8.6 | Caption: "Daily loss limit hit." · monitor banner: "DAILY LOSS LIMIT HIT / Same trading day: -$1,050" · bubble (7.0–7.75): "But it's a new day!?" · shutter sign (7.75–8.6): "CLOSED" |
| 8.6–10.6 | "Your daily limit resets when your firm's day ends." → (9.2) "Not at your midnight." (two lines) → (9.55) "Check the reset time in your firm's rules." |
| 10.6–12.15 | "See your daily-loss room before you trade." · pill "Sample data shown" · real Wharf prop account card ("Eval 50K", Evaluation, "Today vs daily limit -$600 / -$1,000", row ringed) · callout "Today: -$600 of -$1,000" · "Your logged trades today vs the limit you set." |
| 12.15–13.6 | End card: The Wharf logo · "THE WHARF" · "Don't pull a Dave." · "See your daily-loss room before you trade." · "Free plan at thewharf.app" |

## Timeline
- 0.0: Hook. Dave stretches at his desk at dawn, clock reads 8:00 AM.
- 2.25: The lights drop to night and the clock rewinds. Over the shoulder, last night's trade falls to -$800.
- 4.2: Back to dawn. Dave fist-pumps: "New day, fresh limit!"
- 5.45: He takes one trade, which loses -$250.
- 6.55: Record-stop to silence. The monitor goes red: "DAILY LOSS LIMIT HIT", same trading day -$1,050. One low piano note.
- 7.0: Close-up, hands on head: "But it's a new day!?"
- 7.75: The shutter clangs down ("CLOSED"), Dave face-plants and the mug spills.
- 8.6: Payoff lines over the dimmed room.
- 10.6: The app card.
- 12.15: The end card. Fade at 13.6.

## Music and sound
Original, made in code (numpy/scipy) with no samples, no voice and no copyrighted music.
- **Band:** lo-fi jazz at 88 BPM in F (Fmaj9, Dm9, Gm9, C13): FM electric piano comping, upright bass, brushed drums (snare swishes, brush taps on 2 and 4, a soft kick, a light ride) and vinyl crackle.
- **Clock tick:** on the beat while the clock is on screen.
- **Flashback:** low-passed, with tape-whirr sweeps as the clock spins.
- **Breach:** a dry record-stop of the band to silence, then a single low D2 piano note.
- **Payoff:** a soft Dm9 e-piano bed.
- **Under the app card:** brushes and bass come back.
- **End:** an F-major e-piano chime.
- **SFX:** mouse clicks, stamp thumps, shutter rattle and clang, desk thud, mug clink, whooshes.

## Compliance notes
- "Dramatisation" is on screen for the whole video. Every story number sits under the "Example: $1,000 daily loss limit" tag, and the monitor says "Example". The app screen carries "Sample data shown".
- **App card:** captured from `the-wharf/site` with the mock backend (`build/mocksb.js`), using a demo account and sample trades. The account name is generic ("Eval 50K") with no firm preset or logo. No chart page, third-party toggle or data credit is shown.
- **No claim that The Wharf knows a firm's reset hour or tracks open P&L.** The card numbers (-$600 / -$1,000) deliberately differ from Dave's story, so it doesn't look as if the app caught his overnight loss. The note says "Your logged trades today vs the limit you set." The video tells viewers to check the reset time in their firm's rules.
- **Nothing banned or invented:** no prices, profit, income or funding promises. No competitor, prop firm, broker or Trustpilot is named or hinted. No AI trade reviews or AI agent. No real trading results.
- **Safe zone:** all text sits inside x 70–940, y 220–1540. Captions are centred at x 505 with a max width of 800. Tags are at y 1440, so they stay clear of the bottom 380 px.
- **No repeats in last14.md:**
  - Reset time and "new day" are a new topic.
  - The question hook is new.
  - The shutter and mug-spill gag is new.
  - The "Don't pull a Dave." sign-off is new (15 Nov used "Stop being Dave").
  - The caption opening "Breached on a day that felt brand new?" is new.
  - The pinned-comment question is new.
- **AI footage: no.** Everything is code-rendered (three.js, HTML/canvas) or a real app capture.

## Test
Hook style: a question on screen in frame 1 ("Breached for no reason?"). Measure IG 3s view rate (median 28.5%) and TT views (median 216).

## Editor changes (ED, 18 Nov)
- **Payoff timing:** "Not at your midnight." now lands at 9.2s (was 9.45s) and "Check the reset time in your firm's rules." at 9.55s (was 9.95s), so the last line is fully readable for about 0.9s instead of 0.4s. It was also small, thin and low-contrast (46px body font, grey-blue); now 56px heading font in light blue. This is the line that keeps the video honest (the app doesn't know a firm's reset hour), so it has to be readable.
- Re-rendered frames from `newday.html` and re-encoded with the regenerated audio (same cue list, music unchanged). Length still 13.6s. Cover re-exported from frame 1.
- Checked and left as is: question hook "Breached for no reason?" readable in frame 1 with the 8:00 AM clock; one mistake acted out by Dave, punchy captions + bubbles, record-stop + shutter/face-plant comic beat, under 15s; different topic, hook, gag, palette and music from "Dave moved his stop" (not a remake). "Dramatisation" on screen the whole video, "Example: $1,000 daily loss limit" over every story number (monitor also says "Example"), "Sample data shown" on the app card. All text inside x 70–940, y 220–1540 (stills at 0.0, 0.5, 6.8, 9.4, 9.8, 9.9, 11.3, 13.2, 13.4s). Caption, hook, sign-off and pinned comment don't repeat anything in last14.md. No prices, brand hints, funding implication or AI-review mention.
- **Checker fix (K1/K2):** the payoff line "Not at midnight." was an absolute claim (some firms do reset at midnight server time), so it now reads "Not at your midnight." It keeps the same timing and style, wraps to two lines inside x 70–940, and matches the caption. Payoff frames were re-rendered and the video re-encoded; the cover did not change.
