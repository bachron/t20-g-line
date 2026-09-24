# Handoff: T20 G-line — sessions merged, decisions locked, ready to order

**Project**: HEXATI T20 build (personal bike build, not software)
**Date**: 2026-09-24
**Supersedes**: `HANDOFF_T20_parts_tracker_2026-09-23.md` (and the 09-01 one before it)
**Repo**: https://github.com/bachron/t20-g-line (public) — `main` is current

## ⚙️ How to resume in a new session

**Working folder:** `/Users/asri/Library/Mobile Documents/com~apple~CloudDocs/Claude Projects/T20 G-line`
Plain iCloud Drive folder + git repo. **GitHub is the source of truth; iCloud is a convenience copy.**

Click **New**, set the working directory to that path, then:
> Read docs/handoffs/HANDOFF_T20_parts_tracker_2026-09-24.md and continue.

- `T20_Build_Options.md` — detailed tracker (~925 lines), source of truth
- `T20_Build_Plan.md` — shorter mirror: decisions, status, open items

⚠️ **Do not run two sessions against these files at once.** That is exactly what caused the
19 Sep fork, a merge conflict and duplicated MiniMODs research.

## Decisions locked this session (24 Sep)

| Decision | Detail |
|---|---|
| **Frame: UNASSEMBLED** | HEXATI also sells frames pre-assembled (headset, seatpost clamp + liner, rear locking block, easy wheels, E-hook fitted). Considered, **not taken** — so those parts stay live purchase decisions |
| **T20 = exact G Line clone** | Fitment now resolves to G Line spec. Corroborated by a HEXATI reseller listing "T20 — G Line geometry" |
| **Dropout: thru-axle disc 100/142** | A frame-order choice (rim / flat mount / thru-axle 74-112, 74-142, 100-142). Only 100/142 matches G Line's 100mm front |
| **Drivetrain: 11 AND 12 speed both open** | Not forced to choose — see below |
| **Brakes: leaning flat mount**, post allowed via ~16g adapter (+20mm → 160mm rotors) |
| **Keep Praxis Doon + Lightworks 54T** | Both already near-optimal; only THM beats the crank, at ~S$23/g |
| **Grips: Ergon GP2 Evo** (230g), a deliberate comfort choice |
| **Pedals: leaning Eggbeater family** (stated); H&H Ti 215g is the lighter platform alternative |

## Done this session

- **Merged the parallel `extralite-parts-build` cloud session into main** and deleted its branch.
  Ported: Dropout / Dropout Hanger / Skewers-Thru-Axle, Lights (Magicshine), Thx4Ride,
  Extralite parts, chainring bolts, wheel-size resolution, and all Open Questions.
- Resolved the G Line fitment table (brake mount, rotor, bar clamp, headset, seatpost, rack).
- Expanded the drivetrain to 11 **and** 12 speed with L-TWOO, Wheeltop, microSHIFT, SRAM,
  Archer; chains tracked for both.
- Added the Eggbeater pedal family, Aerolite cylinder family, MiniMODs, Ti frame suppliers,
  value tiers on the upgrade shortlist.
- Repo work: PR #1 merged, everything now on `main`.

## 🔥 Highest-value open item

**Extralite Superlight/Hyper BSA bottom bracket — 21g.** Every other BB tracked is 80-103g.
If the M30 fit confirms, that is **~59g from one part** — bigger than the saddle, grips or
pedal decisions combined. The BB table has been unranked for weeks; this would settle it.
**Confirm M30 compatibility first.**

## Not yet done (priority order)

1. **Confirm the 100/142 dropout's caliper mount — flat or post.** Not stated in the listing,
   and thru-axle frames commonly default to post. **If post, the brakes section inverts**:
   Shimano XT BR-M8100 becomes the default instead of the flat-mount calipers ranked first.
2. **Confirm Extralite BB fits M30** (see above).
3. **Weigh what you already own** — wheelset, tyres, seatpost, rear triangle, fork, stem,
   cassette. Free, and four rows of the upgrade shortlist can't be ranked without it.
   **There is still no running build-total weight.**
4. **Decide 54T vs 48T chainring.** 11-50T cassette: 54T = 1.08:1 low, 48T = 0.96:1. Free
   before purchase, and directly serves the "easier low gears" priority.
5. **Fork credit** from Chris Yeo for deleting the fork from the bundle (amount TBC).
6. Rank the bottom bracket; final picks on brakes, saddle, handlebar, pedals, rack.
7. Chase: Extralite Carousell wheelset weights; SMC Lunate RHET price (conflicting figures).

## Broken / failed approaches (don't repeat)

- **G Line is the design reference, not a parts constraint** — but as of 24 Sep the user has
  decided to treat the T20 as an exact clone, so G Line spec now applies.
- **Juin Tech GT-P is POST mount**; GT-F is the flat-mount sibling.
- **Cane Creek "eeWings" is a crankset**, not a brake. Their eeBrake is a **rim** caliper.
- **Carbon-Ti 54T is 110 x 4-arm**, not 5-arm — won't fit the Lightworks spider.
- **Brooks is not a lightweight brand** (C13 259-301g, ~150g over everything else).
- **Praxis Doon and Lightworks 54T are already near-optimal** — don't re-research.
- **Aerolite gold is the stock TiN finish**, not anodising.
- **L-TWOO is no longer drop-bar only** — eRX offers flat-bar shifters. The old note in the
  plan saying otherwise is superseded.
- **11-speed Shimano MTB tops out at 11-46T**, which makes the low gear *harder* (1.17:1 vs
  1.08:1). Going 11sp to solve a chain problem is backwards.
- Tooling: `WebFetch` 403s on eBay item pages, SSL failure on bromptuning.com.
  Fantastic4Toys, Brompton Kitchen and tibicycles fetch fine.

## Unresolved contradiction in the user's own doc

§5 of `T20_Build_Plan.md` says the Thule Yepp Nexxt 2 Maxi is **frame**-mounted to the seat
tube, while the seatpost note says it clamps the **seatpost** — the entire basis for excluding
carbon posts. Both can't be true. Titanium is safe either way. **Flagged four times, still
unanswered.**

## Reference

- Global `~/.claude/CLAUDE.md` — **web tool rule: state whether the task is extraction- or
  action-focused, recommend a tool, get confirmation before web work.** Crawl4AI and Browser
  Use are named there but **not connected**; WebSearch + WebFetch are the confirmed stand-in.
- Karpathy principles in the same file.

## Resume instructions

1. Read `T20_Build_Options.md`.
2. **First action: chase the Extralite BB M30 fit** — biggest single saving available.
3. Then the dropout caliper-mount question, since it may invert the brakes ranking.
4. If the user wants to move without external answers: rank the bottom bracket, and push to
   get owned parts weighed so a running build total can finally exist.
5. **Before any web research, follow the CLAUDE.md rule.**
