# floor-follows-you: PUSH post, Fri 20 Nov 2026 7–9 am Sydney (C2)

- File: floor-follows-you.mp4 (1080x1920, H.264 crf 18 yuv420p + AAC 48k, 30fps, 13.6s) · Cover: floor-follows-you-cover.png (frame at 1.0s: hook + Dave on the ladder + water tagged "drawdown limit")
- Format: Visual metaphor (wave), Hall of fame. PUSH built on "moved it just this once" (25 Oct, IG 1,827 / 8.7s / 10 shares). Kept: ONE trading idea → ONE image that escalates beat by beat, stick-figure trader (Dave, same flat look as dave-new-day / dave-moved-stop), almost no text, ends on a question. Changed: topic (trailing drawdown), image (ladder up a wharf piling, rising water), palette, sound.
- Not a pitch post. No app screens, no feature content.
- Mix: our own SFX (ladder creaks + rung knocks on every climb, water swell on every rise, long creak on the step down, splash + low boom at 9.1s, two soft chime notes under the question) + a quiet original bed (D-minor drone that tightens, woodblock tick every 0.65s, noise riser 7.7–9.1s, silence after the hit). numpy/scipy only, no recordings.
- Today's test: on-screen text amount, ≤15 words in the whole video → **15 words** (count below).
- STRATEGY: week angle "one bad day ends the account" / hook 5 family (the number you didn't know moved). Avoids the 18 Nov wording "your room is measured from your best day".

## Caption
Every new high drags the floor up behind you. And it never comes back down 🌊
Know where your drawdown floor sits before you take the next trade.
#propfirm #fundedtrader #futurestrading #daytrader #tradingmemes

## Pinned comment
Is your account trailing or end-of-day drawdown? And did you know which one before you passed? 👇

## TikTok title
The floor follows you up

## Sound for Will (he adds it in-app; the file has only our SFX + a quiet original bed)
- TikTok: "L no Theme" – Hideki Taniuchi — https://www.tiktok.com/music/x-7140118771854739457 · start 0:00 (default clip) · original audio ~20%
- Instagram: "Time" – Pink Floyd — https://www.instagram.com/reels/audio/486665065097971/ · start in the clocks/chimes intro (the default clip if it opens on the clocks; otherwise drag to the first clock ticks/chimes) · original audio ~20%
- Built for a slow tense build: climbs every 1.3s (1.3 / 2.6 / 3.9 / 5.2 / 6.5s), water rises ~0.4s after each, pullback 8.45s, splash + boom on the downbeat at 9.1s, then near-silence under the question (10.9s →).

## Beats and on-screen text
| Time | Beat | On-screen text |
|---|---|---|
| 0.0–3.4s | Dusk wharf. Dave on the lowest rungs of a ladder up a timber piling; dark teal water right under him, coral dashed line + tag on the surface. Counter beside him $50,000 | "Passed. / Then the water started rising." (frame 1, fades 3.0–3.4s) · "drawdown limit" (tag on the water, whole video) |
| 1.3, 2.6, 3.9, 5.2, 6.5s | Dave climbs a rung (creak + knock), counter ticks +$2,000 (to $60,000), then the water swells up exactly one rung behind him (swell + spray). Camera pushes in, waves get bigger, the deck and a warm lantern come into view above | (counter figures only) |
| 7.7–9.1s | Small pullback: Dave stops, looks down, sweat drop; slowly steps down ONE rung (long creak, riser) | – |
| 9.1s | Foot hits the water: splash, boom, screen shake, coral flash, counter $58,000 in coral; Dave drops in up to his chin, clinging to the ladder | "Account closed." (stamp, 9.25s → end) |
| 10.9–13.6s | Still water, the floor stays where it is. Dave sad, bobbing; two soft chime notes | "Does yours follow you up?" |

Small tags all video (not counted): "Dramatisation · example numbers" (bottom-left) and a low-opacity "@the.wharf.app" watermark (bottom-right), both inside the safe zone. No end screen.

**Word count (on-screen text):** Passed (1) Then the water started rising (5) · drawdown limit (2) · Account closed (2) · Does yours follow you up (5) = **15 words**. Counter figures ($50,000 → $60,000 → $58,000) not counted as words.

Example numbers: $50,000 account, $2,000 trailing drawdown; each rung = $2,000, so the floor trails one rung (= $2,000) under the peak; peak $60,000 → floor $58,000 → a $2,000 pullback closes it.

## Palette
Dusk teal sky/water (#0c2129, #173f47, #2c5f63, water #2c7679 → #051a20), weathered timber (#5d4d3e, #6f5d4a, rungs #d8bf98), warm lantern light (#ffc978, #fff0c8), coral accent (#ff6b5b) for the drawdown line/tag, the coral counter and the stamp; cream text #fbf1e2. Fonts: Bricolage Grotesque Bold, JetBrains Mono Bold (counter), Instrument Sans Bold (tags). Distinct from recent palettes (grey/magenta, pine/cream/berry, dawn blue + amber, saffron/ink).

## Checks
- Hook readable in frame 1 (6 words), all text within x 70–950, y 262–1480.
- ≤15 words on screen: 15.
- No app screens, no trades shown; "Dramatisation · example numbers" tag on screen the whole video. No profit/funding promise, no advice beyond "know your floor" in the caption.
- No competitor/prop firm/broker/platform names or logos. No slogan, URL, price or sign-up text. Only branding = the small watermark.
- Audio: only our own synthesized SFX + bed (numpy/scipy); no song or recording in the file.
- Dave matches our skits: white round head with thick black outline, oval eyes, thick brows, black stick limbs.
- Nuance: rules differ by firm. Some trailing drawdowns stop trailing once the floor reaches the starting balance; the video shows the "keeps trailing" case with example numbers and asks the viewer which one they have.
- Editor pass (ED, 19 Nov): hook set a little smaller (80/66px) so Dave's reaching hand at ~1.5s and ~2.9s clears "started rising." by ~40px; "Account closed." stamp now slams in from 1.12x (was 1.6x, briefly ran past the frame edges). Beats, timing, words and audio unchanged (same audio track remuxed). Cover re-taken at 1.0s.
- Source: run/c2/src (floor.html driven by setT(t), render.js, audio.py, fonts/) → suggest the-wharf tools/floor-follows/.
- Suggested post time: Fri 20 Nov 7–9 am Sydney.
