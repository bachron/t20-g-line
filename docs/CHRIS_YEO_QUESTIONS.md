# Questions for Chris Yeo (Bromprr) — HEXATI T20 frameset

**Created 25 Sep 2026.** Every open blocker in the build that only the frame supplier can answer,
in one place. **§1 is written to be copy-pasted to him as-is.** §2 explains what each answer
unblocks and what it's worth in grams or dollars, so you can tell when an answer is good enough.

Nine of the open items in `T20_Build_Plan.md` § 7 resolve from this one conversation. Three of
them are hard blockers — the wheelset, the dropout hanger and the brake calipers cannot be
ordered until they're answered.

---

## 1. The message — copy from here

> Hi Chris, I'm building up the T20 titanium frameset unassembled and I've hit a few spec
> questions I can't answer from the listings. Could you confirm the following for the frame you'll
> be supplying me?
>
> **Rear end / axle**
> 1. What is the rear axle standard — **142 × 12mm thru-axle, or 135mm quick release**? I need this
>    before I can order the wheelset and the matching dropout hanger.
> 2. On the **100/142 thru-axle dropout**, is the rear brake caliper mount **flat mount or post
>    mount**? The reseller listing doesn't say, and it changes which calipers I buy.
> 3. Is a **rear thru-axle included** with the frame, or do I need to source one? (If not included:
>    is M12 × 1.5, 160mm correct?)
> 4. Does the rear triangle use a **Brompton-pattern rear suspension block**, or a HEXATI-specific one?
>
> **Interfaces**
> 5. Which **headset pattern** does the frame take — Brompton **A/C/P/T Line**, or **G Line**? I have
>    candidates for both but they aren't interchangeable.
> 6. What is the **handlebar clamp diameter** on the titanium stem — **31.8mm or 25.4mm**?
> 7. What **seatpost diameter** does the frame take — 31.8mm?
> 8. Does the rear triangle have **rack mounts**, and if so which platform do they match —
>    **Brompton A/C/P/T or G Line**? I'm choosing between racks for both.
> 9. What **bottom bracket shell** is it — BSA threaded, 68mm? I'm fitting a Praxis M30 spindle
>    crankset, so I need an M30-compatible BB. Do you know if an **Extralite BB (6806 / 30mm
>    bearings both sides)** fits the Praxis M30-THRU spindle, which steps down to 28mm on the
>    non-drive side?
>
> **Weights** (I'm tracking a build total and using published figures)
> 10. Actual weight of the **main frame** and the **rear triangle**?
> 11. Actual weight of the **titanium stem** (S / M)?
>
> **Commercial**
> 12. We agreed the fork comes out of the S$2,900 bundle since I'm sourcing a Silverock carbon fork
>     separately — **what's the credit for omitting it?**
>
> Thanks!

---

## 2. Why each one matters — the reference version

### Hard blockers (can't order the part without the answer)

| # | Question | What it blocks | At stake |
|---|---|---|---|
| 1 | **Rear axle: 142×12 TA or 135 QR** | Wheelset hub spec (SMC Plume DW2 is offered in both), **and** the dropout hanger | Wrong guess = a wheelset you can't fit. Also decides whether MiniMODs Ti skewers are usable at all |
| 2 | **Caliper mount: flat or post** | Whole § Brakes ranking | **~70-80g.** Flat → Juin Tech GT-F (135g/caliper, 140mm rotors, no adapter). Post → Shimano XT BR-M8100 becomes default, +~16g adapter each and 160mm rotors |
| 5 | **Headset pattern: A/C/P/T or G Line** | Headset choice | **~9g and S$65.** A/C/P/T → H&H alloy 96.3g / ~S$90. G Line → WOOdman Axis BPT 105g / ~S$155 |

### Changes which part you buy

| # | Question | What it decides | At stake |
|---|---|---|---|
| 3 | Rear thru-axle included? | Whether you buy one separately | SMC doesn't include thru-axles; TPW recommends M12×1.5 160mm. Currently **not in the weight total at all** |
| 6 | Bar clamp 31.8 or 25.4mm | Handlebar shortlist | 31.8mm → all four carbon candidates (Schmolke / Darimo / Ridea / WOOdman SL). **25.4mm → most of the carbon shortlist is out** and the H&H Ti 179g bar comes back in |
| 7 | Seatpost diameter | Confirms the WOOdman GT2 31.8mm already chosen | Sanity check on a part already picked |
| 8 | Rack mounts, which platform | Rack choice | **~160g.** G Line → TPW Ti 328g (only option found). A/C/P/T → H&H Q Mini Rack ~170g |
| 9 | BB shell + the Extralite M30 question | Bottom bracket | **~14-37g.** BBInfinite Ceramitech 80g is the safe pick; Extralite cups + M30 bearings is ~66-72g **if** the 30/28mm stepped spindle works. This has been the top open research item since 24 Sep |
| 4 | Brompton-pattern suspension block? | Whether MiniMODs rear shock options apply | Small, but it's a whole upgrade path that's either open or closed |

### Fills blanks in the weight total

| # | Question | Currently in the tracker as |
|---|---|---|
| 10 | Frame + rear triangle weight | Frame **1,351g assumed** (HEXATI press release, not your frame). Rear triangle 633g |
| 11 | Ti stem weight | **450-560g — a 110g estimate with no published figure.** The single largest unknown in the build; the range alone is wider than the entire handlebar spread |

### Commercial

| # | Question | Status |
|---|---|---|
| 12 | Fork credit | Open since the fork was deleted from the bundle. Chosen spec is the **S$2,900** Ti frame + triangle + Ti stem + carbon fork, *less* the fork. Amount never agreed |

---

## 3. What to do with the answers

1. **Axle standard** → order the wheelset (RHET vs Hubsmith R027 — RHET is ~80-85g lighter) and the
   matching TPW hanger (**GRP-21B 48g** for 135 QR, **GRP-22B 54g** for 142×12).
2. **Caliper mount** → finalise § Brakes. If post, re-rank to XT BR-M8100 and budget 160mm rotors.
3. **Headset pattern** → order H&H (A/C/P/T) or WOOdman Axis BPT (G Line).
4. **Bar clamp** → finalise the carbon handlebar model, then check the rider-weight limit.
5. **Rack mounts** → TPW Ti G Line 328g, or H&H ~170g if it turns out to be A/C/P/T.
6. **Weights** → replace the three estimates in `T20_Build_Options.md` → *Component weights* and
   recompute the total. The stem alone could move it 110g.
7. **Fork credit** → feed into `docs/PURCHASE_ORDER.md` § Frameset.

*Cross-referenced against `T20_Build_Plan.md` § 7 Open Decisions and `T20_Build_Options.md`
§ Open Questions to Track. Nothing here is answerable from published sources — all of it is
specific to your frame.*
