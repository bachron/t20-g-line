# Handoff: T20 build comparison, seatposts, e-shifter battery rule

**Project**: HEXATI T20 build (personal bike build, not software)
**Date**: 2026-09-26
**Supersedes**: `HANDOFF_T20_parts_tracker_2026-09-24.md`
**Branch**: `claude/laughing-cray-ootu2f`. ⚠️ **Not merged to `main` yet.** Everything from this session lives only on this branch until it's merged (no PR opened).

## Goal

Lay out alternative builds to weigh on **weight, comfort and cost**, then refine the parts lists (seatposts, Brompfication, electronic shifting).

## Done this session

- **New file `T20_Build_Comparison.md`**: four builds compared.
  - **T20-A**: complete T20 from Chris Yeo with Shimano 105 (user says S$2,900), strip and resell stock parts. ~8.5-9.0 kg, ~S$5,100-6,500 net.
  - **T20-B**: T20 frameset only, unassembled (S$2,900 incl. Ti stem + carbon fork). ~8.5-8.9 kg, ~S$6,600-7,500.
  - **G1 / G2**: used Brompton G Line (~S$3,000 on Carousell), keep main frame only, Ti rear triangle (tibicycles / Titanium-DX). ~9.4-10.0 kg, ~S$5,500-8,900.
  - Shared parts table (22 parts fit every build, since the T20 is a G Line clone), used-price assumption 55-70% of new, verdict (a T20 build; A vs B depends on the real complete-bike price).
- **"Purchased" labels corrected**: nothing has been bought yet (user confirmed 25 Sep).
- **Seatposts** (`T20_Build_Options.md` § Seatpost, `T20_Build_Plan.md` §5):
  - Added HEXATI/COMEPLAY Ti post: **268g without plug**, 31.8mm, GR9, 535mm std (540-600 offered), 1.2 or 1.5mm wall, **US$40 direct** / S$100 via Chris Yeo.
  - Added **Brompfication** Ti post (integrated clamp, 310-345g all-in, ~US$240) and Pentaclip version (~260g + Pentaclip 92-108g).
  - Added **COMEPLAY "Brompfication-style"** Ti post, US$80 on tibicycles, integrated clamp, 540-600mm, weight not published. It's a COMEPLAY copy, not genuine Brompfication.
  - Added a "compare like with like" note: weights include different parts (plug, saddle clamp).
- **31.8mm seatpost diameter confirmed** for the T20 frame (user, 26 Sep). Marked resolved everywhere.
- **Brompfication brand section** added to `T20_Build_Options.md`: QR magnesium pedals (175g, ~US$142, S$120 used SG) is the strong candidate; the hinge clamps, seat clamp and bolts are classic-Brompton pattern.
- **Electronic shifting, removable-battery rule** (new table in `T20_Build_Options.md` § Shifter/RD; summary in the Plan):
  - L-TWOO eRX/eR9 marked **non-removable battery** and kept.
  - Wheeltop charges on the bike, so it fails the rule.
  - Shortlist: **Shimano XTR Di2 M9250** (389-391g + 24g battery), **XT Di2 M8250** (447g), Deore Di2 kit, used **SRAM XX1/X01 Eagle AXS non-T-Type**.
  - SRAM Transmission ❌ (needs a UDH frame).

## Pending edits not yet built

None.

## Not yet done (priority order)

1. **Ask Chris Yeo the complete-bike price.** The user says S$2,900 with 105. The tracker's vendor table has complete T20 Lite + 105 = **S$3,200** and S$2,900 = frameset. This decides T20-A vs T20-B.
2. Ask Chris Yeo:
   - Can the complete bike come with the **Ti stem** (the carbon stem doesn't fit the Yepp Mini)?
   - What wheels and tyres are stock, and what does the stock fork weigh?
   - HEXATI seatpost: which wall thickness weighs 268g, and is a saddle clamp included? The "necking down" post likely needs a Pentaclip.
   - What does the US$80 COMEPLAY Brompfication-style post weigh?
3. Seatpost pick: the WOOdman GT2 is still ✅. The user hasn't decided whether to switch. Stale notes remain in the Options seatpost section ("must be aluminium" heading, TPW "lightest tracked", "switching to Ti gains nothing"). Offered to fix; not yet accepted.
4. Decide mechanical XT M8100 vs electronic (XTR/XT Di2). The comparison doc still prices mechanical.
5. Carried over from 24 Sep: fork credit, flat vs post brake mount (deferred to purchase), Extralite BB M30 fit, stem weight, rack pattern.
6. Merge `claude/laughing-cray-ootu2f` into `main` (offered a PR; the user hasn't answered).

## Broken / failed approaches (don't repeat)

- **The cloud session's network blocks** brompfication.com, tibicycles.com, ebay.com, bromptonkitchen.com and cyclopesco.com. WebSearch snippets work. **Ask the user for screenshots** of product pages (they're happy to send them).
- **Don't compare seatpost weights as listed.** The WOOdman includes its plug; H&H includes plug and clamp; HEXATI 268g is a bare tube.
- **Battery rule wording.** The user typed "must have non removable battery", but the context (L-TWOO rejected for non-removable) means **must be REMOVABLE**. Interpreted that way and told the user; they haven't objected.

## Key decisions

| Decision | Rationale |
|---|---|
| Nothing bought yet | User confirmed 25 Sep |
| T20 split into A (complete bike) and B (frame only) | User request 26 Sep |
| Most parts used; **BB, grips, brake and shift cables/housing new** | User rule. Suggested also new: chain, tyres, tubes, carbon bar (user's call) |
| Seat tube / seatpost 31.8mm | User confirmed 26 Sep |
| E-shifter battery must be removable for charging | User rule 26 Sep. L-TWOO kept in list, marked non-removable |
| S$2,900 bundle = Ti frame + Ti rear triangle + Ti stem + **carbon** front fork | From tracker; user had forgotten |

## Reference (don't duplicate)

- `T20_Build_Comparison.md`: the four builds, costs, verdict.
- `T20_Build_Options.md`: full option tables (seatpost, Brompfication, e-shifter battery table).
- `T20_Build_Plan.md`: decisions and short tables.
- Previous handoff `HANDOFF_T20_parts_tracker_2026-09-24.md`: working-folder and iCloud notes, Crawl4AI setup (local Mac only), older open items.

## Resume instructions

1. Check out `claude/laughing-cray-ootu2f` (or `main` if it has been merged) and read `T20_Build_Comparison.md`.
2. Ask the user whether Chris Yeo has answered the Not-yet-done #1-2 questions. Update T20-A's cost and the seatpost rows with any answers.
3. If the user picks a seatpost or e-shifter, update the ✅ pick and re-run the weight and cost totals in `T20_Build_Comparison.md` §3-5.
4. Offer the PR to merge into `main` if still unmerged.
