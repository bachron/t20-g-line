# Parts research — price + weight + configurations (25 Sep 2026)

Research pass over **every part currently in the build**, for price, weight, and the
configuration options of each. Closes the *"decided but never priced"* gap in
`docs/PURCHASE_ORDER.md` § 4.

**Conversions:** US$1 ≈ S$1.30, €1 ≈ S$1.47, ¥100 ≈ S$0.88. Figures are published/retail research,
not quotes — re-check before paying.

> ⚠️ **Method note.** This session's network blocked most retailer and review domains, so these
> figures come from search-result summaries rather than fetched product pages. Anything marked
> ⚠️ is a conflict or a gap I could not close from here — **verify those before ordering.**

---

## 🚨 Two findings that change parts, not just prices

### 1. Your brake levers are the wrong pull ratio

`T20_Build_Plan.md` § 3 recommends **Juin Tech GT-F or Growtac Equal + Extralite UltraLevers 3**.
That pairing does not work:

- **Extralite UltraLevers 3 are V-brake / rim-brake specific** — long-pull, per Extralite's own
  product page.
- **Growtac states plainly that Equal calipers are short-pull only**, that a V-brake lever makes
  braking "weaker … this combination does not allow the caliper to perform as designed," and that
  **V-brake levers are not supported.** Growtac's own guidance for flat bars is to fit *short-pull
  compatible flat-bar levers*.

**The fix is Extralite's own short-pull model — and it's lighter:**

| Lever | Pull ratio | Weight | Works with Growtac Equal / flat-mount cable calipers? |
|---|---|---|---|
| UltraLevers **3** *(currently in the plan)* | **Long-pull (V-brake)** | 22.5g ea / **46g pair** | ❌ **No** |
| ⭐ UltraLevers **3S** | **Short ratio — "caliper and cantilever rim brake specific"** | **20.5g ea / 41g pair** | ✅ Yes |

**Switching to the 3S is correct *and* saves 5g.** ⚠️ The `[8.3kg ref]` build pairs UltraLevers 3
with TRP Spyre SLC — either that build has the same mismatch, or it used the 3S. Don't take the
reference build as proof the 3 works.

### 2. Your tyre is too wide for the light tube

Nobody has priced or weighed tubes, and the obvious lightweight choice doesn't fit:

| Tube | Fits | Weight each |
|---|---|---|
| Schwalbe **SV6A XLight** | 23-406 → **40-406 only** | 65-70g |
| ✅ Schwalbe **SV7** *(needed)* | 40-406 → **62-406** — covers your **50-406** | **145g** ⚠️ one source says 205g |

**Your Continental Contact Urban is 50-406, so the SV6A is out of range.** Tubes are **~290g per
pair**, and they were **not in the running total at all**. That is a bigger miss than most of the
upgrade shortlist.

---

## Priced this pass — the eleven that had no cost

| Part | Model | Weight | Price | Source note |
|---|---|---|---|---|
| **Wheelset** | SMC PLUME-406-DW2 | 945-1,045g | **US$1,198 (~S$1,557)** | Speed Mini Cycle. 22mm rim, 24H f/r, Hubsmith straight-pull + TPI ceramic bearings. ⚠️ This is also the figure that was logged as the disputed "SMC Lunate RHET" price — likely the same number, misfiled |
| **Crankset** | Praxis Doon carbon, M30-THRU | 335-342g | **US$330 (~S$429)** arm set | Universal Cycles. Arms + M30 alloy spindle. 147mm Q-factor, 44.5mm chainline |
| **Fork** | Silverock carbon, G Line, M12×100 TA | 365g fork / **393g w/ axle** | **US$529.99 (~S$689)** | eBay (Silverock store). ⚠️ Tracker has 388g from Fantastic4Toys vs 393g here — ±10g, immaterial |
| **Rack** | Ti Parts Workshop Ti, **G Line** | 328g | **US$360 (~S$468)** | All-titanium. Raw / black / gold. Still the only correct G Line option found |
| **Cassette** *(eR9 route)* | ✅ **NUTON null¹ ROAD 12S/HG 11-32T** *(tracked)* | **140g** | **¥21,450 (~S$189)** | Ultegra CS-R8000 11-32T (292g, ~S$85-117) is the fallback. See the ratio table below |
| **Tyres ×2** | Continental Contact Urban 50-406 | 860g | **US$34.99 ea (~S$45)** → **~S$91 pair** | Bikeinn |
| **Tubes ×2** | Schwalbe SV7 (20×1.5-2.5) | **~290g** 🆕 | ~S$10-13 ea *(est.)* | 🆕 **New line — was missing entirely** |
| **Brake levers** | Extralite UltraLevers 3 → **3S** | 46g → **41g** | **~US$218 (~S$283)** for the 3 · 3S ⚠️ unpriced | See finding #1 |
| **Rotors ×2** | Ti-Parts carbon aero 140mm | 77.3-90.1g ea ⚠️ | ⚠️ **still unpriced** | See the rotor table below |
| **Rear thru-axle** | M12×1.5, 160mm | ⚠️ not published | ⚠️ **still unpriced** | Ti and AL7075 options exist (Carbon-Ti, HEPPE, Pioneer). ⛔ may be included with the frame — Chris Yeo question #3 |
| **Cables + housing** | — | not tracked | ⚠️ **still unpriced** | Small, but real |

---

## Corrections to figures already in the tracker

| Part | Tracker said | Research says | Impact |
|---|---|---|---|
| **Bottom bracket** | BBInfinite Ceramitech ~US$175 **(est.)** ≈ S$228 | **S$334** retail in Singapore (Bikemart SG; also stocked by Bike Stop SG) | **+S$106.** The "est." was low by nearly 50%. It also widens the gap to the Extralite route (~S$76-93) to **~S$250**, on top of the ~10g |
| **Chainring** | Lightworks V2, ~US$150, 56-60g *(price was for the 54T)* | **48T confirmed: 60g, US$149.50 (~S$194)** | Confirmed at the size you actually chose |
| **Pedals** | H&H Ti 215g, **no price** | **US$125 standard / US$135 X-Large (~S$163-176)**, 215g/pair confirmed, left pedal detachable | The recommended pedal is now priced — and it's cheaper than the Eggbeater 3 |
| **Rotor weight** | "Ti-Parts carbon aero 77.3g" | ⚠️ **Conflict:** the same vendor's pages give **77.27g** (carbon Aerotor 140mm, no adapter) and **90.12g** | Up to **+26g for the pair** if 90g is the real figure. **Verify before trusting the build total** |

---

## Configuration options, part by part

### Cassette — the ratio table

**eR9 caps at 32T**, so on that route only the top three rows are usable.

| Model | Speeds | Ratio | Weight | Price | Note |
|---|---|---|---|---|---|
| Ultegra CS-R8000 | 11 | **11-32T** | **292g** | ~S$85-117 | The tracked eR9 pick |
| Ultegra CS-R8000 | 11 | 11-30T | **269g** | ~S$85-117 | −23g, and a *harder* low gear |
| Ultegra CS-R8000 | 11 | 11-28T | **251g** | ~S$85-117 | −41g, harder still |
| Ultegra CS-R8000 | 11 | 11-25T | 232g | — | Race ratio. Not for a loaded folder |
| ✅ **NUTON null¹ ROAD 12S/HG** | **12** | **11-32T** | ✅ **140g** (catalog, incl. alloy lock ring) | ✅ **¥21,450 incl. tax (~S$189)** | **TRACKED PICK from 25 Sep.** Cogs 11-12-13-14-15-16-17-19-21-24-28-32T. Fits 11- **and** 12-speed HG bodies. **−152g vs the Ultegra for ~S$72-104 more.** Cheaper than the 11-50T MTB version |
| 🔥 **NUTON null¹ ROAD 11S/HG** | **11** | **11-32T** | **135g** ⚠️ single source | ⚠️ not found — range starts US$115 | The 11-speed sibling, 5g lighter. Cogs 11-12-13-14-15-17-19-21-24-28-32T |
| NUTON null¹ MTB 12S/HG | 12 | 11-50T | 286g | ¥28,600 (~S$250) | The 24 Sep pick. Needs eTX or mechanical XT |
| NUTON null¹ MTB 11S/HG | **11** | 11-46T | **310g** | ¥26,400 (~S$231) | 🆕 An 11-speed Nuton exists. Heavier than the 12S, and still needs a 46T-rated derailleur |

📌 **CONFIRMED 25 Sep — the best thing found this pass.** The **NUTON null¹ ROAD 12S/HG 11-32T is
140g at ¥21,450 (~S$189)**, against the Ultegra's 292g at ~S$85-117. **152g for S$72-104 extra —
about S$0.47-0.68 per gram**, on a part where nothing else about the bike changes: same 11-32T
ratio, same HG freehub, same shifting. That is better value per gram than anything else in the
build, including the ESI grips, and unlike the grips it costs no comfort.

**✅ Adopted as the tracked cassette on 25 Sep**, taking the running total from 8,194-8,731g to
**8,049-8,574g**.

⚠️ **The string attached:** it is a **12-speed** cassette, so eR9 runs in 12-speed mode and the
chain goes back to 12sp (KMC X12 234g / CN-M8100 252g). **The existing KMC 11-speed chain is
unusable again** — the 11-speed reprieve noted earlier the same day is reversed. Only the Ultegra
fallback puts you back on an 11sp chain.

It does **not** fix the eR9's 1.50:1 low gear — but it removes most of the weight cost of the
eR9 route. An 11-speed version of the same ratio exists at **135g** (5g lighter, price not found,
single source).

⚠️ **Two cautions.** 140g is the catalog figure, not a verified scale weight. And the top three
cogs are aluminium — light, but softer than steel, so expect a shorter service life than the
Ultegra under daily city use with a child on board.

### Rotors — four options at this vendor, none priced

| Model | 140mm | 160mm | Note |
|---|---|---|---|
| Ti-Parts **carbon Aerotor** | **77.27g** *(no adapter)* / ⚠️ 90.12g elsewhere | 105.6g | The tracker's pick. Centerlock + 6-bolt |
| Carbon-Ti **X-Rotor SteelCarbon 3** | **86g** | — | Already in the tracker |
| Carbon-Ti **X-Rotor Aero** | **93g** | — | Steel braking surface, carbon body, Ti rivets |
| Ti-Parts **7075 aluminium ultralight** | **74-88g** | 74-88g | 🆕 Possibly **lighter than the carbon**, likely much cheaper. Worth pricing |

### Tyres — width options

| Size | Width | Weight ea | Note |
|---|---|---|---|
| ✅ **50-406** (20×2.0) | 2.0" | **430g** | The pick. Stock G Line width |
| 42-406 (20×1.6) | 1.6" | **355g** | **−150g the pair.** Narrower, less cushioning — and lets you use the **65-70g SV6A tube**, so the real saving is **~300g the pair** |
| 32-406 (20×1.25) | 1.25" | 300g | −260g the pair. Too narrow for a loaded city folder with a child seat |

💡 **The 42-406 + SV6A combination is the biggest unexploited weight saving found this pass:
~300g for tyre-and-tube money.** It costs cushioning and some puncture margin — a deliberate
trade the plan made on purpose, but worth re-examining now the tube weight is visible.

### Pedals

| Model | Weight | Price | Note |
|---|---|---|---|
| ⭐ **H&H Ti, standard** | **215g/pair** | **US$125 (~S$163)** | Left pedal detachable — the folding requirement |
| **H&H Ti, X-Large** | 215g/pair | US$135 (~S$176) | 38% larger platform, same weight. €155 in the EU |
| MKS Compact Ezy | 302g | ~S$114-135 | |
| Crankbrothers Eggbeater 3 | 280g | ~US$135 (~S$176) | Needle bearings |

**H&H is now both the lightest and among the cheapest** — the recommendation holds, and the
X-Large is +S$13 for a bigger platform at no weight cost.

### Wheelset

| Config | Effect |
|---|---|
| Rim: **C22-25 clincher** vs **T22-30 tubeless** | 945g vs 1,045g — **100g** |
| Hub: **RHET** vs **Hubsmith R027** | RHET is **~80-85g lighter** |
| Freehub: **Shimano 11-speed** vs **XDR 12-speed** | ⚠️ **Order the HG/Shimano body** — every cassette in your plan (Ultegra 11sp, both NUTON null¹ HG) is HG. XDR would strand all of them |
| Axle: 135 QR vs 100/142 TA | ⛔ Chris Yeo question #1 |

### Crankset / chainring

| Part | Config | Weight | Price |
|---|---|---|---|
| Praxis Doon arms | 160 / 165 / **170** / 172.5mm | 335-342g | US$330 (~S$429) |
| Lightworks V2 ring | **48T** (chosen) | **60g** | **US$149.50 (~S$194)** |
| Lightworks V2 ring | 54T | 79g | ~US$150 |

---

## What is still unpriced after this pass

1. **Rotors** — no vendor price visible from here, four candidate models
2. **UltraLevers 3S** — the 3 is ~US$218; the 3S price wasn't shown
3. **Rear thru-axle** — may be included with the frame (Chris Yeo #3)
4. **Cables + housing, seatpost clamp, hinge hardware, lights, mudguards**
5. ~~**NUTON null¹ ROAD 11-32T** — price and exact weight both need confirming~~ ✅ **Done 25 Sep: 140g, ¥21,450 (~S$189).** Only the 11-speed variant's price is still open

*All five are small relative to the wheelset, fork and rack — the cost picture is now
substantially complete.*
