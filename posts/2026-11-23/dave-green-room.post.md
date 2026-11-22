# dave-green-room — Mon 23 Nov 2026 (PUSH)

- **File:** dave-green-room.mp4 (1080x1920, 30 fps, H.264 + AAC 44.1 kHz)
- **Cover:** dave-green-room-cover.png. This is the frame-1 premise card. **Cover frame time: 33 ms** (frame 1; 0 ms also works, same card).
- **Length:** 13.33 s
- **Format:** Dave skit × Guess before the reveal (PUSH)
- **Builds on:** Hall of fame "Dave moved his stop" (3 Nov, TT 852, IG 6.95s / 50.8%) and the top-third dave-new-day (18 Nov, IG 457 / 6.56s / 54.0%, TT 645), using the Proven Guess before the reveal structure (guess-my-consistency, 8 Nov). Kept: Dave acting out ONE mistake, a premise readable in frame 1, a top caption that changes each beat, the monitor carrying the gag, the guess → drumroll → reveal, the deadpan stare payoff, and under 15 s. New: topic (trailing drawdown after a green day), a question hook, the sticky-note guess, and the palette.
- **Today's test:** an ultra-short caption (4 words + 1 emoji). All the context and the soft CTA go in the pinned comment. Measure shares and comments per 1,000 views against recent posts.

## Caption
Dave did the maths. 🤨

## Pinned comment
Trailing drawdown: a green day moves your floor up, so your room doesn't grow with your balance (Example: $50K account, $2,000 trail, +$800 → floor $48,800, room still $2,000). Check your own rules: trails differ. The Wharf tracks trailing drawdown per prop account, so you see today's room before the next trade. Free plan covers 1 prop account. What did you guess? 👇

## Hashtags
#propfirm #trailingdrawdown #futurestrading #daytrading #fundedtrader #tradingjournal

## TikTok title
Dave's up $800. How much room does he have now?

## Palette
A lilac evening room (walls #7a6aa6 / #6a5b96) with a graphite floor and chair, a pale birch desk, and mint accents (#8ff0c8: monitor line, lamp shade, mug, caption borders). There's a pink sunset window glow and a pink sticky note (#ffd3e0). End screen is #15121d. None of the recent Dave palettes (navy/ochre, autumn rust, sage/oat, dawn blue/amber, mustard/terracotta) are reused.

## Audio
- **Music:** original, made in code with numpy/scipy. A playful game-show-ish synth bed at **108 BPM in E minor**: Em | C | Am B7 (drumroll) | Em (reveal) | C. Karplus-Strong pluck arpeggios on 8ths, a round sub bass with an octave bounce, a soft detuned saw pad, kick / closed hat / light clap.
- **How it follows the edit:** the bed ducks a little under the scribbles. Under the drumroll it is low-passed while a synth snare roll speeds up and swells (8ths → 16ths → 32nds → buzz). It lands on Em with a reveal hit (kick + noise crash + stab chord). At the stare it **hard-cuts** to near-silence: one low E note with a faint drone and room tone.
- **SFX:** trade "ding", whooshes, three pen scribbles plus an underline, pen tap, drumroll, reveal hit, highlight tick, marker strike, pop, two soft toks, and a soft end chime.
- **Copyright:** no samples, no recordings, no copyrighted audio. Will can add a trending sound in-app if he wants.
- **Loudness (measured with ffmpeg ebur128 on the final mp4):** integrated **−17.1 LUFS**, sample peak −0.9 dBFS. The stare section sits at about −19 to −25 LUFS momentary, so it is quiet but never silent.

## Beat sheet (on-screen text)
| t (s) | picture | top caption / text |
|---|---|---|
| 0.00–2.22 | Over-shoulder: Dave cheers with his arms up. The monitor shows "Eval 50K · Closed · today · +$800 · Example" and a rising mint line. Trade ding. | **"Dave's up $800. How much room now?"** + tags "Dramatisation" and "Example: $50K account, $2,000 trailing drawdown" + faint "The Wharf" watermark |
| 2.22–4.44 | Insert: a pink sticky note, written by pen with scribble SFX: "$2,000" / "+ $800" / underline / "Room: $2,800?" | "Dave's guess:" |
| 4.44–6.67 | Drumroll. Dave drums on the desk. The monitor reads "Room left today · Checking…" with spinning digits, and the sticky note is stuck on the corner. Hopeful face cut at 5.56–6.11 (on beats 10–11). | "Checking the app…" |
| 6.67 | **Reveal hit: hard cut** on the hit frame (no crossfade). The real Wharf account card (site/ + mock backend): Eval 50K $50,800 · Drawdown room (floor $48,800) **$2,000** · Today $0 / −$1,000 | "Room: still $2,000." + "Sample data shown" pill |
| 7.22 / 7.67 / 8.02 | A mint ring highlights the drawdown row. The mini sticky note "$2,800?" gets a red strike. A chip pops in. | chip "Floor: $48,000 → $48,800 · moved up with the $800 · Example"; tags "Dramatisation", "Example" |
| 9.44 | Hard drop to near-silence plus one low note. Dave stares deadpan at the camera. | (no caption: the stare) + "Dramatisation" |
| 10.00 | Stare holds. | **"A green day lifts the floor."** |
| 11.11 | Stare holds, with one blink at 11.6. | + "Check your own rules." |
| 12.22–13.33 | Plain end screen, 1.1 s, soft chime. | "The Wharf" (logo + name only) |

## Self-check
- I looked at stills at 0.5 s, 3.95, 5.9, 6.67 (midpoint), 7.0, 10.5, 11.8 and 13.2.
- All text sits inside y 250–1500 and x < 940. The highlight ring edge reaches x 950, but it is a graphic, not text.
- Nothing is clipped.
- "Dramatisation" is on until the end screen. "Example" is on every invented number. "Sample data shown" is on the app card.
- No URL, price, "free plan", slogan, or other brand on screen. The end screen is 1.1 s and shows only "The Wharf".
- The trailing-drawdown numbers come from the REAL app card (`.acct-card` in site/, captured via build/mocksb.js, generic "Eval 50K", no firm preset). They match the STRATEGY.md worked example exactly.

## Editor pass (ED, 23 Nov)
- The reveal at 6.67 s is now a hard cut. The card, the dim and the "Room: still $2,000." caption are all fully on at frame 200, exactly on the hit; before this they faded in over about 2 frames, so the hit landed on the old picture. The "Sample data shown" pill still pops in 0.1 s later.
- The hopeful face cut moved from 5.64 s to 5.56 s (and the cut back from 6.19 s to 6.11 s) so both land on the 108 BPM grid. Its whoosh moved with it. All the other cuts were already on the beat (2.22, 4.44, 6.67, 9.44, 12.22).
- Re-muxed. Integrated loudness is still **−17.1 LUFS**, sample peak −0.9 dBFS, length 13.33 s.
