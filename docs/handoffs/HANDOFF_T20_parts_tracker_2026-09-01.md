# Handoff: T20 G-line parts tracker — lightweight brand survey & G Line fitment

**Project**: HEXATI T20 build (personal bike build, not software)
**Date**: 2026-09-01
**Working folder**: `Claude Projects/T20 G-line/`

## Goal

Set up a tracked parts folder for the HEXATI T20 (titanium tri-fold 20", built to
Brompton **G Line reference geometry**), then widen the parts tracker to cover
lightweight brands that weren't being considered, with **weight and cost on every
row**. Rider priorities: city use with a **front child seat**, easier low gears
over top speed, weight-conscious, prefers Singapore sellers.

## Done this session

- Created `T20 G-line/` and copied in `T20_Build_Plan.md` + `T20_Build_Options.md`
  (Asri supplied updated versions mid-session from `~/Downloads` — the Downloads
  copies had reverted earlier edits, which were re-applied).
- **Stem finalised**: titanium, HEXATI via Chris Yeo. Frameset pricing marked at
  S$2,900 (Ti frame+triangle + Ti stem + carbon fork).
- **Fork ranked**: 1) SilverRock carbon bought separately (omitted from the Chris
  Yeo bundle to cut price), 2) HEXATI Ti, 3) HEXATI carbon stock.
- **Brand survey added** to both files: HH Innovation (H&H), Ti Parts Workshop,
  Ridea, Silverock, WOOdman, Brooks, Berk Composites, Gelu, Selle Italia, Tioga,
  Darimo, Schmolke, Extralite, Growtac, Paul, TRP, Juin Tech, Yokozuna,
  Carbon-Ti, Hassns, HT Components, Wheel Angel, MKS, Xpedo, Ergon.
- **New sections opened** that the build needed but wasn't tracking: saddle,
  handlebar, grips, pedals, rear rack, brakes (expanded), rotors, levers, tyres,
  cassette, wheelset, shifter/RD.
- **Prices researched and added** to every new row (SGD converted at ~1.30 USD /
  ~1.47 EUR, matching the doc's existing convention).
- **Brake section rebuilt and extensive**, every caliper labelled **FLAT** or
  **POST** mount, flat-mount table first (Asri's stated lean).
- **8.3kg Brompton G Line reference build** (Steven Heng) folded into every part
  table tagged `` `[8.3kg ref]` `` for direct comparison.
- **Ergon GP2 Evo** added as the ranked grip pick (230g S / ~260g L, ~S$57-73).

## Pending edits not yet built

None outstanding — every request this session has been applied to both files.

## Not yet done (priority order)

1. **Confirm the T20's own interfaces with Chris Yeo** — this gates the most
   decisions: brake mount, handlebar clamp diameter, headset pattern (A/C/P/T vs
   G Line), seatpost diameter, rear rack mounts.
2. **Fork credit** from Chris Yeo for deleting the fork from the bundle (amount
   TBC) — confirm it beats the delivered SilverRock price before ordering.
3. **Bottom bracket** — still unranked (7 options tracked, 80-103g, S$127-550).
4. **Wheelset hub** — RHET vs Hubsmith R027, and weigh the SMC Plume DW2 against
   the 1,090g reference wheelset.
5. **Brake caliper + lever + rotor** final pick.
6. **Chain** — the doc still lists a KMC **11-speed** chain against a 12-speed XT
   M8100 drivetrain. **This is an outright incompatibility and is still unfixed.**
7. Saddle, handlebar, pedals, rack final picks.
8. **Weigh the parts with no recorded weight**: WOOdman GT2 seatpost, Lightworks
   54T chainring, Nuton null¹ cassette, SMC Plume DW2 wheelset, Continental Urban
   Contact tyres, SilverRock carbon fork, HEXATI Ti stem, frame + rear triangle,
   chain.
9. **48T vs 54T chainring** — the 8.3kg build runs Lightworks 48T; Asri's stated
   priority is easier low gears. Worth revisiting the 54T.

## Broken / failed approaches (don't repeat)

- **Do not treat G Line spec as a hard parts constraint.** Asri is building a
  **T20**, not a G Line — G Line is the *design reference* only. An earlier pass
  struck out H&H headsets/racks/bars as "wrong platform"; that was wrong and has
  been reverted. Actual constraints come from the T20 frame and must be confirmed
  with Chris Yeo.
- **H&H rear racks (170/215/250g) were initially listed without checking platform.**
  They are A/C/P/T Line parts. The G Line-pattern equivalent is Ti Parts Workshop
  at 328g. Both families are now tracked as candidates pending confirmation.
- **Juin Tech GT-P was ranked #1 before checking mount.** It is **post mount**;
  G Line reference is flat mount. GT-F is the flat-mount sibling. Post mount is
  still viable via adapter (Asri's call) — see Key decisions.
- **Cane Creek "eeWings" ≠ a brake.** eeWings is their titanium crankset (already
  tracked, ~400g). Their brake product is the **eeBrake**, a **rim** caliper (78g)
  — Cane Creek makes no disc brake in any mount. Permanently ruled out.
- **Ridea is largely incompatible** with decisions already made: 54T chainring is
  130 BCD (spider is 110), 6CBB bottom bracket is BSA24 (Doon needs M30), brakes
  are rim only, OSPW cages are road-derailleur only. Only their **31.8mm carbon /
  titanium handlebars** are usable.
- **Brooks is not a lightweight brand.** The C13 with carbon rails (259-301g) is
  Brooks' lightest and still ~150g over every other tracked saddle. Tracked as a
  comfort choice, not a weight one.
- Tooling: `WebFetch` failed on `bromptuning.com` (SSL cert) and 404'd on a
  guessed `bzsportcycles.com` category URL. Fantastic4Toys and Brompton Kitchen
  collection pages worked well for range/price discovery.

## Key decisions

| Decision | Rationale |
|---|---|
| Stem = titanium (HEXATI via Chris Yeo) | Required for correct G Line geometry so the Thule Yepp Mini front seat mount fits; the carbon stem doesn't conform |
| Fork = SilverRock carbon, bought separately | Omitting it from the Chris Yeo bundle cuts the frameset price. Yepp Mini clamps the stem, not the steerer, so carbon is fine |
| Leaning **flat mount** brakes, open to post | Flat mount needs no adapter and keeps 140mm rotors |
| Post mount allowed via adapter | Asri's call. Cost: ~16g/adapter **and** adapters are +20mm so a 140mm position needs a **160mm** rotor — ~70-80g total, plus fold/rear-triangle clearance to check |
| Grips = Ergon GP2 Evo despite weight | ~175-200g over foam, but bar ends + palm support suit an upright city bike with a child in front. Logged as a deliberate comfort choice |
| Seatpost stays non-carbon | Thule Yepp Nexxt 2 Maxi clamp rule — **but see unresolved contradiction below**; titanium is safe either way |
| Ridea limited to handlebars only | Everything else collides with Praxis M30 / 110 BCD / disc / MTB-drivetrain decisions |

## Unresolved contradiction in Asri's own doc

§5 of `T20_Build_Plan.md` says the Thule Yepp Nexxt 2 Maxi is **frame**-mounted to
the seat tube, while the seatpost note says it clamps the **seatpost** — which is
the entire justification for excluding carbon posts. Both can't be true. If it's
frame-mounted, carbon seatposts come back into play. Titanium passes either way.
**Flagged twice, still unanswered by Asri.**

## Reference (don't duplicate — just point to it)

- `T20 G-line/T20_Build_Plan.md` — the build plan: decisions, status, open items.
- `T20 G-line/T20_Build_Options.md` — the options tracker: min. 3 options per part,
  weights, prices, G Line fitment section, 8.3kg reference build, Ridea section.
- Global `~/.claude/CLAUDE.md` — **web tool rule: identify whether a task is
  extraction- or action-focused, recommend a tool, and get confirmation before
  starting any web work.** Crawl4AI and Browser Use are named there but are **not
  connected in this session**; WebSearch + WebFetch were used as the stand-in with
  Asri's confirmation.
- Karpathy principles in the same CLAUDE.md: think before acting, simplicity
  first, surgical changes, goal-driven execution.

## Resume instructions

1. Open `T20 G-line/T20_Build_Options.md` — it is the detailed source of truth;
   `T20_Build_Plan.md` mirrors it more briefly.
2. **First substantive action: fix the chain.** The plan still lists a KMC
   11-speed chain against the 12-speed XT M8100. Replace with a 12-speed option
   (KMC X12/DLC12 or Shimano CN-M8100) and research weights for each.
3. Then ask Asri whether she has heard back from Chris Yeo on the five T20
   interface questions (brake mount, bar clamp, headset pattern, seatpost
   diameter, rack mounts). Several tables can't be narrowed until those land.
4. If she wants to keep researching instead, the highest-value remaining work is
   **bottom bracket ranking** and **weighing the already-chosen parts** (list in
   "Not yet done" item 8) — the build has no running weight total yet, which is
   the main thing missing for a weight-conscious build.
5. **Before any web research, follow the CLAUDE.md rule**: state whether the task
   is extraction- or action-focused, recommend the tool, and get confirmation.
6. A running build-total spreadsheet was offered and not yet taken up — worth
   re-offering once more part weights exist.
