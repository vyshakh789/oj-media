# OJ cover techniques, every style from the Oct 7 to 9 swipe

Built 2026-10-09. Type is **Nohemi Bold + Caveat Bold** (canon rule 15).
Every style below is a reusable preset, not a one-off. Engine and the full
how-to live on the Studio at `projects/OJ/photo-triage/oj-social/`
(`cover_techniques.py` + `RECIPES.md`).

**Look at this first.** This is the set at true grid size, which is the only
review that matters for the feed.

![all at grid size](_all-at-grid-size.jpg)

---

## Cover-legal, ready to use

### behind, the word behind the subject
Apple Vision cuts the subject out and it sits in front of the type.

| Oman | Bali |
|---|---|
| ![](behind_oman.jpg) | ![](behind_bali.jpg) |

### ridge, the same depth on a landscape
Vision cannot see terrain, so a second copy of the photo is laid over the word
and clipped along the horizon. The edge is invisible because the pixels match.

| Mongolia | Russia |
|---|---|
| ![](ridge_x_mongolia.jpg) | ![](ridge_russia.jpg) |

### lockup, the series engine
Caveat word over Nohemi caps, baselines overlapping. Swap the second word
forever: get OUT. / go SLOW. / get LOST. / get BACK. / take FIVE.
Repeatable by maths, never nudged by hand.

| Bali | New Zealand | Kazakhstan |
|---|---|---|
| ![](lockup_bali.jpg) | ![](lockup_x_nz_lake.jpg) | ![](lockup_kazakhstan.jpg) |

On a warm photo the colours flip: cream caps, orange script, or the type
vanishes into the sunset. That is the Kazakhstan one.

### straddle, one word on a panel edge
Photo-filled above the line, solid below. Registration is pixel-exact.

| Bhutan | Kazakhstan |
|---|---|
| ![](straddle_bhutan.jpg) | ![](straddle_x_kz_snow.jpg) |

### fill, the photo inside the letters
The Nike SWIM move. Launch covers only: it throws away most of the photo.

![](fill_bali.jpg)

### split, headline top and bottom, subject in the gap
The LIVING WITH NATURE look, with the lower word behind the subject.

![](split_x_kz_snow.jpg)

### weightflip, light line over bold line
The quietest one. Needs a calm band, not a calm frame.

![](weightflip_bhutan.jpg)

### sidelock, script beside the caps
LOOKING FOR Peace. Same two voices as lockup, looser arrangement.

![](sidelock_x_nz_lake.jpg)

### shaped, type bent to the scene
Inline SVG text on a path. Hand-built, once a quarter.

![](shaped_x_nz_lake.jpg)

---

## Breaks our cover rules on purpose

Rendered because you asked for every style. These are slide 2, an editorial
tile (max 1 in 6), or a feed post. The checker names every rule each one breaks.

| | breaks |
|---|---|
| ![](bleed_nz.jpg) **bleed** | runs past the 60px side inset by design, and into IG's view-count corner |
| ![](panel_oman.jpg) **panel** | a tint over the photo plus corner labels, 11 words |
| ![](ridge_x_mongolia_ed.jpg) **ridge + editorial furniture** | 14 words, corner labels in both reserved corners |
| ![](straddle_bhutan_ed.jpg) **straddle + editorial furniture** | 12 words, same corner problem |

---

## Every reference, and where it went

| Reference you sent | Built as |
|---|---|
| PEAK Austria, word behind the ridge | `ridge` |
| Situation, word on the horizon | `ridge` |
| get OUT. / get BACK. | `lockup` |
| quiet / Cat, word on a panel edge | `straddle` |
| Nike SWIM, photo inside the letters | `fill` |
| LIVING WITH NATURE, caps top and bottom | `split` |
| Find beauty everywhere, light over bold | `weightflip` |
| LOOKING FOR Peace, script beside caps | `sidelock` |
| fugir de locais lotados, huge type off the edge | `bleed` (editorial) |
| Play With Nature, translucent panel + corner labels | `panel` (editorial) |
| OFFLINE / TAKE IT EASY, lettering warped to the scene | `shaped` |
| Bangkok early hours / Tokyo Anime Hues, kicker stack | the standard block used by `behind` and `ridge` |
| catch the moment, one accent word + metadata footer | accent word is built in (Caveat); the footer is the editorial variant |
| IT'S NOT EASY / stages of, stacked caps + sublines | `split` and `weightflip` cover the shapes |
| speaking to yourself, marker font + circled word | **not built.** The marker face is off-brand for OJ and a circled word fails the 3-element rule. Say the word and I will add it as an editorial option. |
| SUTD, words built into a mountain silhouette | **not built.** Hand-lettering, days of work, not scriptable. `shaped` is the cheap cousin. |

---

## What is still open

- **Pick the ones you want.** Then I apply them to F1 Qatar, Bhutan, Russia,
  Oman and Bali, which are the departures that need bookings.
- The ridge auto-trace needs a hand edit on about a third of photos. It fails
  silently on gradient skies, so every trace gets a debug overlay to check.
- `nohemi.zip` in the font folder is a saved web page, not the font archive. We
  have Bold and Medium only. Re-download from Gumroad if you want more weights.

Nothing here has been posted or scheduled.
