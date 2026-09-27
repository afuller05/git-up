# The N2 Report — Show Template

Monthly video communication for Ottawa Community Housing.
This file is the single source of truth for the show's look, cast, structure and
production workflow, so every episode matches and new episodes start fast.

Reference episode: **June 2026** — Adobe Creative Cloud folder `N2 Report June 2026`
(edited in Adobe Express as `Timeline 1`).

---

## 1. Format at a glance

A friendly monthly "news show" hosted by a 3D cartoon presenter in a navy OCH polo.
The host speaks to camera in a home-base location, then introduces segments that
visit staff, programs and properties.

## 2. Episode structure (June 2026 run-down)

| # | Segment | Visual | Notes |
|---|---|---|---|
| 01 | Cold open | Host alone, townhouse playground | Hook / what's in this episode |
| 02 | Title card | "THE N2 REPORT / Ottawa Community Housing / Month Year" | Static graphic + narration |
| 03 | Seasonal opener | Host, townhouse playground (different angle) | Season / weather / timely reminder |
| 04 | Welcome | Host + new team member, playground | e.g. "Martin welcome" |
| 05 | Introduction | Host + staff member at a high-rise property | e.g. "Rodrigo introduction" |
| 06 | Program spotlight | Host + guests in an office/lobby | e.g. IPM (pest control) |
| 07 | New tools | Host presenting a screen in an office | e.g. "New Apps" (call centre tool) |
| 08 | What Would Andy Do | Host + tradesperson in an apartment hallway (2 clips) | Recurring scenario segment |
| 09 | Montage / results | 6 short clips (9a–9f), e.g. boardroom with performance dashboards | Stats, wins, updates |
| 10 | Closing | Full cast waving on dark navy background | Sign-off |
| 11–15 | Closing narration | Narration tracks | Thanks / reminders / see you next month |

Segments 01, 02, 03, 10 are **fixed every month** (only the words change).
Segments 04–09 rotate with the month's news; drop or repeat as needed.

## 3. Visual style

**Style prompt (paste into every image/video prompt):**

> Stylised 3D animated cartoon, Pixar-like feature-film look: rounded friendly
> characters with large expressive eyes, soft global illumination, warm natural
> lighting, gentle depth of field, clean detailed environments, realistic
> materials, cheerful but grounded tone. 16:9 widescreen.

**Brand (OCH 2023 Branding Guide, in Creative Cloud "N2 Report Characters"):** clothing
logo = house icon + stacked "OCH / LCO" (on navy garments use white lettering). Colours:
dark green PMS 568, navy PMS 540, red #F04937 (PMS 179), cyan #1FC0DA (PMS 311),
grey PMS 420. Fonts: Montserrat (design), Arial (documents).

**Title card:** dark navy tech background with faint network lines, two glowing teal
horizontal rules, "THE N2 REPORT" in white bold condensed caps, subtitle
"Ottawa Community Housing" and "Month Year" in white below.

## 4. Cast

| Character | Look (keep consistent) | Seen in |
|---|---|---|
| **Host (Andy)** | **Rebuilt Sept 2026 from Andy's headshot:** 6', ~290 lb, broad heavyset build; round full face, receding thin mid-brown hair, smaller warm eyes with smile lines, soft brows, closed-mouth smile. Navy polo with official OCH clothing logo (icon + white "OCH / LCO") on left chest, charcoal slacks, brown belt/shoes, wristwatch. Reference files: Creative Cloud "N2 Report Characters" | Every episode |
| Coordinator (MC Dan) | Short ginger beard, black cap, black OCH t-shirt, dark jeans, brown boots | What Would Andy Do (Oct 2026) |
| Staff — black shirt | Bald man, short grey beard, black button shirt with logo, grey trousers | Welcome (04) |
| Staff — navy polo #2 | Dark hair, navy OCH polo, grey trousers | Introduction (05), high-rise |
| IPM guests | Man with glasses, beard, light-blue shirt and tie; young man in white shirt (thumbs up) | IPM (06) |
| Tradesperson | Ginger beard, cap, grey OCH polo, tool belt | What Would Andy Do (08) |
| Closing cast | Six characters waving (plaid shirt, glasses/blue shirt, host, bald/grey jacket, white shirt, small character on shoulders) | Closing (10) |

> TODO: confirm names for each recurring character and save one clean
> front-facing reference image per character (see §7).

## 5. Locations

- **Home base:** townhouse community playground, mulch, orange/red slides, pine trees
- High-rise apartment exterior with sidewalk and lawn
- Office lobby with large windows (OCH pest control van outside)
- Call-centre / open office with presentation screen on a rolling stand
- Apartment building hallway (carpet, beige walls, unit doors)
- Boardroom with performance dashboards on wall screens

## 6. Audio

- **Narration voice:** ElevenLabs voice "Andrew" (used in June).
  June settings from the file name: speed ≈ 0.99, stability 80, similarity 75,
  style 20, speaker boost on, Multilingual v2.
- One narration clip per segment, numbered to match the segment (`01.mp3`, `02.mp3` …).
- One background music bed under the whole episode, ducked under narration.
- Optional: French version of the narration (same video, second audio track).

## 7. Production workflow (ElevenLabs + Adobe)

1. **Intake (you):** create Creative Cloud folder `N2 Report <Month> <Year>`, add real
   photos, and send bullet points per segment (see §8).
2. **Script (Claude):** writes one narration block per segment, in plain language.
3. **Stills (Claude):** converts each photo to the 3D style using the style prompt
   plus character references. **You approve stills before any animation.**
4. **Animation (Claude):** animates approved stills with Kling. Price check first.
5. **Voice + music (Claude):** narration in the "Andrew" voice, music bed.
6. **Assembly (Claude):** composition of clips + narration + music into one video.
7. **Review + send (you):** watch, request fixes, then email a thumbnail + link.

### Cost guide (ElevenLabs, per ~5 s clip at default settings, Sept 2026)

| Model | Credits | ≈ USD | Use for |
|---|---|---|---|
| Kling 3.0 Pro | ~5,090 | ~$1.02 | Final renders |
| Kling 2.5 Turbo | ~2,120 | ~$0.42 | Drafts, simple scenes |

A June-sized episode (~15–18 clips) ≈ US$15–20 in final-render credits.
Rules: approve stills first; price-check before every batch; draft cheap, finish on 3.0 Pro.

### Scene recipes (learned from June 2026 + October 2026 opener)

June clips were single continuous 15 s shots rendered **silent**; narration was laid on
top afterwards, which is why mouths did not match. Only the host speaks on camera;
other characters act (walk in, slide gag) but do not talk.

| Scene type | Example | Method | ≈ Credits / 15 s |
|---|---|---|---|
| Host talks + walks, guests act | Cold open (host walks, catches kid off slide) | Kling 3.0 Pro (silent, start frame) → Sync 3 lip-sync with Andrew narration (`sync_mode: silence`) | ~22,300 |
| Guest walks in from off-screen | Martin welcome | Kling 3.0 Pro with start frame (host alone) + end frame (host + guest) → Sync 3 lip-sync | ~23,100 incl. 2 stills |
| Guest enters, no fixed ending | — | Kling O3 Pro (start frame + guest reference image) → Sync 3 lip-sync | ~22,300 |
| Host talks, little movement | Straight to-camera line | OmniHuman 1.5 (still + narration) | ~10,000 per ~10 s |
| No one talks on camera | Montage, building shots, office action | Kling animation + narration as voiceover (no lip-sync) | ~10,200 |
| Candidate to test | Host talks + walks, cheaper | Kling 3.0 Pro with native audio → voice changer to Andrew | ~15,400 |
| Rejected | — | Seedance 2.5 with reference audio | ~94,000 (too expensive) |

**Only the host speaks.** Other characters act on screen but never have speaking lines —
this is the show's long-standing format.

**Lip-sync rule (from the producer):** if the person speaking is visible in the shot — even
in the background — their lips must be synced to the audio. Voiceover is only allowed when
the speaker is completely out of frame (e.g. close-up of hands doing a task). Write prompts
for voiceover shots so the speaker is clearly off-screen.

**Procedural accuracy (trade techniques)** — Oct 2026 feedback: Kling showed a plank laid on
top of another instead of at the open end of the row, and a random cut/snap instead of
scoring along the square. AI video knows what tools look like, not how the job is done.
1. **Best: Motion Control** (`kling-3-pro-motion-control`, inputs: character `image` +
   reference `video`). Film 5–10 s of the real action on a phone (landscape, steady, good
   light, action fills the frame, one action per clip); the character copies it exactly.
   Plan to film real crews (e.g. IPM exclusion work) whenever a segment shows a technique.
2. **Start + end frames for every procedure** (e.g. plank angled at the open end of the
   row → plank flat and locked; knife at one end of the line against the square → at the
   other end with a scored line; scored plank → two clean pieces split on the line).
3. **One action per clip** (score and snap = two 3 s shots).
4. **Producer storyboard check**: Andy approves start/end stills for each action before any
   animation.
5. **Precise prompts + negatives** ("insert at the open end of the last row, angled into the
   groove, press flat until it locks"; "no plank on top of another plank, no random cuts").

Rules of thumb:
- **Default for guest entrances: start + end frame.** Start still = host alone; end still =
  host + guest together (approve both stills first, ~420 credits each). Kling 3.0 Pro
  animates between them from a prompt describing the entrance. Guaranteed ending
  composition and guest likeness. Likely how the June Martin welcome was made.
- Alternative (no fixed ending, e.g. slide gag): **Kling O3 Pro** with the host-only still as
  `start_frame` plus each guest as a `reference_images` input (same cost as Kling 3.0 Pro,
  ~10,180 credits / 15 s). This is how the June Martin welcome was made in Firefly.
  (Kling 3.0 Pro only takes a start frame, so there guests must already be in the still.)
- With two faces in frame, check that lip-sync animates the host, not the guest.
- Music + narration mixing and final assembly can be done free (ElevenLabs composition
  costs 0 credits, or a local ffmpeg mix).
- Budget: ElevenLabs Creator plan = 121k credits/month ≈ 5 lip-synced host scenes.

## 8. Monthly intake checklist (send this to Claude)

- [ ] Month / year
- [ ] Cold open hook (1 line)
- [ ] Seasonal topic / reminder
- [ ] Welcome: name + role of new team member (+ photo)
- [ ] Introduction: name + role + property (+ photo)
- [ ] Program spotlight: topic + key facts (+ photos)
- [ ] New tools / apps: what it is, who uses it, why it matters (+ screenshot)
- [ ] What Would Andy Do: the scenario + the right answer
- [ ] Results / montage: stats or wins to show
- [ ] Closing reminders / dates
- [ ] English only, or English + French?

## 9. Distribution

- Final video is too large to email as an attachment: email a thumbnail image that
  links to the video (YouTube unlisted, Vimeo, SharePoint/OneDrive or Adobe share link).
- Provide a caption file (`.srt`) generated from the narration for accessibility (AODA).
