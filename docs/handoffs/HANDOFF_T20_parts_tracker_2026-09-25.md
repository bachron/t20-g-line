# Handoff: eR9 drivetrain decision, full parts pricing, cost tracker

**Project**: HEXATI T20 build tracker (`bachron/t20-g-line`)
**Date**: 25 Sep 2026
**Branch**: `claude/happy-ritchie-0gb2ed` (all work committed and pushed)
**Build state at handoff**: tracked parts **8,049–8,574g** · known cost **S$9,490–10,572** ready to
ride, **S$9,893–11,001** with lights and mudguards

## Goal

Started from "what else can I do?" — surface the remaining work on the tracker. Became four
things: adopt the L-TWOO eR9 drivetrain, build the Chris Yeo question list and the cost tracker
that never existed, then research price + weight + configurations for **every part in the build**.

## Done this session

**Drivetrain — eR9 adopted, with the ceiling documented**
- **L-TWOO eR9 11sp wireless is the decided shifter/RD**, reversing the 24 Sep "drop-bar only"
  exclusion. That note was wrong: L-TWOO sells eR9 for 14–20" folders and flat bars, the shifter
  is a separate pod in that kit, and eR9 is the HEXATI T20 Lite's own stock drivetrain.
- **The eR9 RD caps at 11-32T.** With the 48T ring that's a **1.50:1** low gear vs **0.96:1** on
  the 11-50T — 56% harder, and the reason 48T was chosen over 54T. Corroborated three ways,
  including JackBikeSG's T20 Lite sheet already in the tracker (ships eR9 with 11-32t).
- **eRX added with real specs** — two RD versions, **11-32T and 11-36T**, carbon cage,
  288–295g published (10g *lighter* than eR9), US$583.52 AliExpress.
- **eTX added** — MTB platform, flat-bar pod, 11-46/50/52T, 426g. The only route that keeps both
  the 11-50T cassette and the 0.96:1 low gear, for ~+120g.
- **New gearing menu** in `T20_Build_Options.md` (*🔧 Gearing configurations*): 1× rings 36–54T
  against 32T and 36T cogs, the 2× subcompact route, the out-of-spec route. Gear inches and km/h
  at 90rpm on the real 406 + 50mm tyre.

**Cassette — reopened, researched, decided**
- **NUTON null¹ ROAD 12S/HG 11-32T is the tracked cassette**: **140g**, **¥21,450 (~S$189)**,
  cogs 11-12-13-14-15-16-17-19-21-24-28-32T, HG freehub, fits 11- and 12-speed bodies.
- **−152g vs the Ultegra CS-R8000 11-32T (292g) for ~S$72-104 ≈ S$0.47-0.68/g** — the best
  confirmed grams-per-dollar in the build. Added to Value Tiers as taken.
- ⚠️ **It forces a 12-speed chain.** eR9 runs in 12sp mode; the existing KMC 11sp chain is
  unusable again (that reprieve lasted one day). Only the Ultegra fallback restores 11sp.

**Two findings that change parts, not prices**
- 🚨 **Brake lever pull ratio was wrong.** The plan paired Juin Tech GT-F / Growtac Equal with
  **Extralite UltraLevers 3** — those are V-brake/long-pull, and Growtac states Equal calipers are
  short-pull only and V-brake levers are *not supported*. Fix: **UltraLevers 3S** (short ratio),
  **€199.90 (~S$294)**, 41g — correct *and* 5g lighter.
- 🚨 **Inner tubes were never counted, and the light one doesn't fit.** Schwalbe SV6A (65-70g) tops
  out at 40-406; the tyre is 50-406, so it needs **SV7 at 145g each = 290g the pair**, now a line
  in the total.

**Pricing — eleven unpriced parts closed, plus accessories**
- Wheelset S$1,557 · Fork S$689 · Rack S$468 · Crankset S$429 · Levers S$294 · Tyres S$91 ·
  Cassette S$189 · Tubes S$20-26 · Cables S$45 · Mudguards S$57 · Lights S$189-215
- **Corrections:** BB was estimated S$228, **retails S$334** in Singapore (widens the Extralite
  gap to ~S$250 — ask Chris Yeo #9 before buying) · Lightworks 48T confirmed 60g / US$149.50 ·
  H&H Ti pedals US$125 / US$135 X-Large, so the recommended pedal is lightest *and* cheapest ·
  eRX is US$583.52, not US$650.
- **Wheelset must be ordered with the HG freehub, not XDR**, or every cassette in the plan is
  stranded.

**New documents**
- `docs/CHRIS_YEO_QUESTIONS.md` — 12 questions, §1 paste-ready. Nine open plan items resolve from
  it; three (wheelset, dropout hanger, calipers) can't be ordered until he answers.
- `docs/PURCHASE_ORDER.md` — line-item costs, waves, and §4b separating assembly parts from
  optional accessories (the frame is unassembled, so clamp/locking block/easy wheels are purchases).
- `docs/PARTS_RESEARCH_2026-09-25.md` — price + weight + config tables for every part.

**Arithmetic fixed:** the purchase order briefly double-counted the headset (in the §3 subtotal
*and* as its own §5 line, S$90-155). Corrected; §3 is now S$513-1,496 and excludes the drivetrain
row because eR9's S$650 is already counted in §2. **Don't reintroduce this** — the §3 subtotal is
saddle + handlebar + pedals + chain only.

## Pending edits not yet built

None. This is a documentation repo; every change this session is committed and pushed. Nothing is
batched or waiting.

## Not yet done (priority order)

1. **Send the Chris Yeo checklist.** Three hard blockers (axle standard → wheelset + hanger;
   caliper mount → brakes; headset pattern), plus the stem weight (a 110g guess, the largest
   single unknown) and the **fork credit**, still unagreed.
2. **Settle the drivetrain route** — eR9 (1.50:1) vs eRX-36T + 38T ring (1.06:1) vs eTX (0.96:1,
   +120g) vs eR9 as 2× (1.00:1, +250-350g). **This gates the spider and chainring**, so it must be
   decided before Wave 3 or there's S$445 of re-buy.
3. **Five items still unpriced**, all blocked by network policy (see below): Ti-Parts rotors,
   rear thru-axle, G Line locking block, **L-TWOO eTX**, NUTON ROAD 11S. Only eTX matters — it's
   a route decision, not a cost one.
4. **Your own decisions:** saddle (213-689), handlebar model (189-551), pedals (71-176).
5. **Verify before ordering:** the Ti-Parts rotor weight conflict (77.27g vs 90.12g on the same
   vendor's pages) and whether the 7075 alloy rotor (74-88g) undercuts the carbon one.

## Broken / failed approaches (don't repeat)

- **Network egress blocks most retail and review domains.** `WebFetch` returns `EGRESS_BLOCKED` on
  amazon.com, bikeradar.com, djcbikes.com, wheel-parts.shop, ltwoo.com, nutoncycling.com,
  yorozuba.com, tipartstitanium.com. **WebSearch works and is the only viable route** — every
  figure this session came from search snippets, not fetched pages. Don't burn turns retrying
  WebFetch on those hosts.
- **Claude cannot change the network allowlist.** Asri must, via the cloud environment menu in the
  session title bar → Edit → Network access. **It does not affect a running container** — a *new
  session* is needed after the change.
- **Crawl4AI is not available here.** The 24 Sep handoff's Crawl4AI/Docker setup was a local
  session; this is a cloud container. So is the global `~/.claude/CLAUDE.md` web-tool rule — that
  file doesn't exist in this environment.
- **eR9 will not run the 11-50T.** 32T is the hard ceiling. Don't re-research it; a ~31T chainring
  would be needed and doesn't exist for the Lightworks 110 BCD 5-arm spider.
- **UltraLevers 3 + Growtac Equal / flat-mount cable calipers is incompatible.** Don't re-recommend
  it. ⚠️ The `[8.3kg ref]` build lists the 3 with TRP Spyre SLC — either it shares the mismatch or
  it used the 3S. Don't treat that build as proof the 3 works.
- **Schwalbe SV6A does not fit the 50-406 tyre.** 40-406 max.
- **No G Line E-hook exists.** Already logged in the tracker; confirmed again this session.

## Key decisions

| Decision | Rationale |
|---|---|
| L-TWOO eR9 11sp wireless as shifter/RD | Asri found folding-bike compatibility; confirmed — it's the T20 Lite's stock drivetrain, sold in flat-bar/folder kits |
| NUTON null¹ ROAD 11-32T as the cassette | 140g vs Ultegra's 292g for ~S$72-104 more; best grams-per-dollar in the build, no functional cost |
| Chain returns to 12-speed | Forced by the Nuton ROAD being a 12sp cassette |
| UltraLevers **3S**, not 3 | The 3 is long-pull and incompatible with the chosen calipers; the 3S is correct and 5g lighter |
| Ultegra kept as documented fallback | The only route back to an 11sp chain and steel cogs |
| Spider + chainring pulled out of Wave 1 | Both hang off the unsettled drivetrain route — S$445 of re-buy risk |
| eRX and eTX documented but not chosen | Asri asked to see them; the low-gear trade is hers to make |

## Reference (don't duplicate)

- `T20_Build_Plan.md` — the decision record; § 7 Open Decisions is the live checklist
- `T20_Build_Options.md` — full option tables, gearing menu, weight total, Value Tiers
- `docs/CHRIS_YEO_QUESTIONS.md` · `docs/PURCHASE_ORDER.md` · `docs/PARTS_RESEARCH_2026-09-25.md`
- `docs/handoffs/HANDOFF_T20_parts_tracker_2026-09-24.md` — the prior session's state
- Karpathy principles: think before acting, simplicity first, surgical changes

## Resume instructions

1. Read `docs/PARTS_RESEARCH_2026-09-25.md` first — it's the newest state and carries both
   compatibility findings.
2. **Check whether Asri added the four domains to the network allowlist** (tipartstitanium.com,
   nutoncycling.com, ltwoo.com, condorcycles.com). If yes *and this is a new session*, the five
   outstanding lookups become possible — **start with the L-TWOO eTX price**, since it's the only
   one that gates a decision.
3. If the allowlist is unchanged, don't retry those hosts. Say so once and move on.
4. **Ask whether the Chris Yeo message has gone out.** If it has, feed the answers into
   `T20_Build_Plan.md` § 7 and `docs/PURCHASE_ORDER.md` § 1 — the axle answer alone unblocks the
   wheelset and the dropout hanger, the two most expensive blocked items.
5. Any weight-table edit must be re-verified by summing the table, not by hand. Every total this
   session was checked that way. Current: **8,049 low / 8,574 high, 28 rows.**
