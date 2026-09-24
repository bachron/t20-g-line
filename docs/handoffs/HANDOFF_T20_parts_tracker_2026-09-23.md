# Handoff: T20 G-line parts tracker — brand survey, weights, costs, upgrade path

**Project**: HEXATI T20 build (personal bike build, not software)
**Date**: 2026-09-23
**Supersedes**: `HANDOFF_T20_parts_tracker_2026-09-01.md`

## ⚙️ How to resume this work in a new session

**Working folder:**
`/Users/asri/Library/Mobile Documents/com~apple~CloudDocs/Claude Projects/T20 G-line`

It's a plain iCloud Drive folder — **not a git repo**, and it doesn't need to be.

In the Claude desktop app: click **New** in the sidebar, set the working directory to the
path above (or start it inside the existing **t20-g-line** project group), then say:

> Read docs/handoffs/HANDOFF_T20_parts_tracker_2026-09-23.md and continue.

Two files are the source of truth:
- `T20_Build_Options.md` — detailed tracker (min. 3 options per part, weights, prices)
- `T20_Build_Plan.md` — shorter mirror: decisions, status, open items

## Goal

Track every part for the HEXATI T20 (titanium tri-fold 20", built to **Brompton G Line
reference geometry**) with **weight and cost on every row**. Rider priorities: city use
with a **front child seat**, easier low gears over top speed, weight-conscious, prefers
Singapore sellers. Target ~9.4-9.6kg.

## Done since the last handoff

- **Ridea** researched — mostly incompatible with decisions already made; only their
  31.8mm carbon/Ti handlebars are usable.
- **Brakes rebuilt and labelled FLAT or POST mount** on every caliper. User leans flat
  mount but allows post via adapter.
- **8.3kg Brompton G Line reference build** (Steven Heng) folded into every part table,
  tagged `` `[8.3kg ref]` ``.
- **Crank arms + chainrings** researched extensively (THM, eeWings, Praxis range, Rotor
  Aldhu, e*thirteen, Garbaruk, Carbon-Ti, Wolf Tooth, AbsoluteBlack, Stone).
  **Conclusion: change neither.**
- **Ti frame / rear triangle / stem suppliers** added (COMEPLAY-HEXATI, EasyTi,
  Titanium-DX, tibicycles).
- **Pedals** restructured into three design families; **Aerolite** cylinder pedals and
  analogues (Ultralite Sports, Pitbull) added as 🔮 future upgrades.
- **MiniMODs** researched and sorted — most of their range doesn't apply.
- **Ergon GP2 Evo** added as the grip pick.
- **Status legend** (✅ / 🛒 / 🔮 / ❌) plus a **Future Upgrade Shortlist** with **value
  tiers** (cost-per-gram), added after the user noted the upgrade list skews expensive.

## Pending edits not yet built

None outstanding.

## Not yet done (priority order)

1. **⚠️ FIX THE CHAIN.** The plan still lists a KMC **11-speed** chain against the
   12-speed XT M8100 drivetrain. **This is an outright incompatibility and has been
   unfixed across two handoffs.** Replace with KMC X12/DLC12 or Shimano CN-M8100.
2. **Weigh what's already owned** — wheelset, tyres, seatpost, rear triangle, fork,
   stem, cassette, chain. Free, and four rows of the upgrade shortlist can't be ranked
   without it. Highest-value action left.
3. **Five questions for Chris Yeo** (each gates a decision):
   - **Axle standard** — 142×12 thru-axle vs 135mm QR? *Blocks the wheelset hub choice
     and decides whether MiniMODs Ti skewers are usable at all.*
   - Brake mount — flat or post?
   - Handlebar clamp diameter — 25.4 vs 31.8mm? *Gates the whole handlebar table.*
   - Headset pattern — A/C/P/T or G Line?
   - Seatpost diameter, and rear rack mount pattern.
4. **Decide 54T vs 48T chainring.** With the 11-50T cassette: 54T = 1.08:1 low,
   48T = 0.96:1. Free to change before purchase, and directly serves the stated
   "easier low gears" priority. The 8.3kg reference build runs Lightworks 48T.
5. **Fork credit** from Chris Yeo for deleting the fork from the bundle (amount TBC).
6. **Bottom bracket** — still unranked (7 options, 80-103g, S$127-550).
7. Final picks: brake caliper/lever/rotor, saddle, handlebar, pedals, rack.
8. **No running build-total weight exists yet.** Offered twice, not taken up.

## Broken / failed approaches (don't repeat)

- **G Line is the design REFERENCE, not a parts constraint.** User is building a T20.
  An earlier pass struck out H&H parts as "wrong platform" — wrong, reverted. Real
  constraints come from the T20 frame; confirm with Chris Yeo.
- **H&H rear racks** (170/215/250g) are A/C/P/T parts; TPW's G Line rack is 328g. Both
  families tracked as candidates pending confirmation.
- **Juin Tech GT-P is POST mount** — was ranked #1 before checking. GT-F is the
  flat-mount sibling.
- **Cane Creek "eeWings" is a crankset, not a brake.** Their eeBrake is a **rim**
  caliper — no disc brake exists from Cane Creek.
- **Carbon-Ti's 54T chainring is 110 × 4-arm**, not 5-arm — won't fit the Lightworks
  spider. Was wrongly listed as an alternative.
- **Brooks is not a lightweight brand** (C13 is 259-301g, ~150g over everything else).
- **Praxis Doon and Lightworks 54T are already near-optimal** — don't re-research.
  Doon is 2nd lightest of everything found; Lightworks 54T at 79g is the lightest 54T
  found anywhere.
- **Aerolite gold is the stock TiN finish**, not anodising (I initially said otherwise).
- Tooling: `WebFetch` 403s on eBay item pages and failed SSL on bromptuning.com.
  Fantastic4Toys, Brompton Kitchen and tibicycles pages fetch fine.

## Key decisions

| Decision | Rationale |
|---|---|
| Stem = titanium (HEXATI via Chris Yeo) | Needed for G Line geometry so the Thule Yepp Mini mount fits |
| Fork = SilverRock carbon, sourced separately | Cuts the frameset price; Yepp Mini clamps the stem, not the steerer |
| Leaning **flat mount** brakes, post allowed via adapter | Post costs ~16g/adapter **and** forces 140→160mm rotors (~70-80g total) |
| Keep Praxis Doon + Lightworks spider + 54T ring | Drive side ~455g is already near-optimal; only THM beats it, at ~S$23/g |
| Grips = Ergon GP2 Evo (230g) despite weight | Bar ends + palm support for upright city riding with a child in front |
| Pedals = H&H Ti 215g recommended | 87g under MKS, keeps a platform, no cleats, no fold compromise |
| Seatpost stays non-carbon | Thule Yepp clamp rule — **but see contradiction below** |
| Aerolite etc. logged as 🔮 upgrades only | No QR exists for cylinder pedals; conflicts with fold width + child seat |

## Unresolved contradiction in the user's own doc

§5 of `T20_Build_Plan.md` says the Thule Yepp Nexxt 2 Maxi is **frame**-mounted to the
seat tube, while the seatpost note says it clamps the **seatpost** — which is the whole
justification for excluding carbon posts. Both can't be true. Titanium is safe either
way. **Flagged three times, still unanswered.**

## Reference (don't duplicate — just point to it)

- Global `~/.claude/CLAUDE.md` — **web tool rule: state whether a task is extraction- or
  action-focused, recommend a tool, get confirmation before web work.** Crawl4AI and
  Browser Use are named there but **not connected**; WebSearch + WebFetch were used as
  the confirmed stand-in throughout.
- Karpathy principles in the same file: think before acting, simplicity first, surgical
  changes, goal-driven execution.

## Resume instructions

1. Read `T20_Build_Options.md` (source of truth); `T20_Build_Plan.md` mirrors it briefly.
2. **First action: fix the 11-speed chain entry.** Two handoffs old now.
3. Then ask whether Chris Yeo has answered the five interface questions above — several
   tables can't be narrowed until they land.
4. If the user wants to keep moving without him: rank the bottom bracket, and push on
   getting the owned parts weighed so a running build total can finally exist.
5. **Before any web research, follow the CLAUDE.md rule** (state task type, recommend
   tool, confirm).
