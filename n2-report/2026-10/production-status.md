# N2 Report — October 2026 Production Status

Last updated: 27 Sept 2026 (evening)

## ✅ Finished segments

| Segment | File | Length | Notes |
|---|---|---|---|
| Opener | `N2_Oct2026_01_Opener.mp4` | 15 s | Professional voice (take 1), lip-synced, autumn music bed |
| What Would Andy Do — LVP | `N2_Oct2026_04_WhatWouldAndyDo_LVP.mp4` | 32 s | Shots 1 + 3b lip-synced; 2 + 3a voiceover; AI-added wall logo removed from shot 2 in post |

Render credits used: narration ~900, Kling (47 s) ~31,900, lip-sync (33 s) ~26,700,
music ~500 → **~60,000**. Remaining balance ≈ 90,000.

Lessons: plan allows max **5 concurrent generations** — batch renders in groups of ≤5.
Check every Kling clip for invented signage/logos (shot 2 added a wall logo).

ElevenLabs canvas: https://elevenlabs.io/app/flows/H6MPouLFhu31nQROwvoW

## Decisions made

- **Host rebuilt** from Andy's headshot (option 3 + official OCH clothing logo, version A).
  Reference image saved on the canvas as "HOST - official character sheet (Sept 2026)".
- **Voice:** wait for Andy's Professional Voice Clone ("Andrews Professional Voice",
  voice id `Ian0baC9WxGLvdfHI3vR`). On 27 Sept it was still "not fine-tuned".
  Older cloned "Andrew" (`8msDbVpmdfHEQhxkKQxg`) is closer than the designed voice but not
  used. Designed "Andrew" (`3isK7tg49otq4dxPz8X1`) retired as host voice.
- **Rule:** visible speaker = lip-synced; voiceover only when the speaker is off-screen.
- **Videos wait** until the professional voice is ready (no lip-sync credits spent on a
  voice we would replace).

## Stills — all approved

| Scene | Still | Status |
|---|---|---|
| Opener (autumn playground) | New host, autumn playground | ✅ approved |
| WWAD shot 1 | Room B: host in doorway, tradesperson checking subfloor | ✅ approved |
| WWAD shot 2 | Tradesperson clicking planks, MC Dan handing planks (host off-screen) | ✅ ready |
| WWAD shot 3a | Close-up: MC Dan scoring plank against speed square | ✅ ready |
| WWAD shot 3b | Finale: all three thumbs up | ✅ ready |

## Next session checklist

1. Confirm the professional voice is fine-tuned (ElevenLabs → Voices; complete verification
   if prompted).
2. Generate narration in the new voice:
   - Opener (~10 s): "Hi everyone, and welcome to the October edition of the N2 Report!
     The leaves are turning, the mornings are getting crisp, and there's lots happening
     across our communities this month. Let's get into it!"
   - WWAD 1 / 2 / 3a / 3b — see `what-would-andy-do-lvp.md`.
3. Kling 3.0 Pro renders (price-check first):
   - Opener 15 s, WWAD 1 12 s, WWAD 2 9 s, WWAD 3a 5 s, WWAD 3b 4 s (~45 s total).
4. Lip-sync (Sync 3, `sync_mode: silence`): opener, WWAD 1, WWAD 3b (~31 s).
5. Music bed + free local mix/assembly; deliver MP4s.

## Credit estimate for the next session

| Item | Credits |
|---|---|
| Kling 3.0 Pro, ~45 s | ~30,600 |
| Lip-sync, ~31 s | ~25,000 |
| Narration + music | ~1,000 |
| **Total** | **~57,000** |

Credits used on 27 Sept (tests, first opener, host rebuild, all stills): ~33,000.
