# Product Quality Deviation and Incident Report – DHDT Unit-31

**Report No.:** QDR-2025-031-006
**Company:** Mangalore Refinery and Petrochemicals Limited (MRPL) – synthetic demonstration data
**Unit where the product failure was observed:** **Diesel Hydrotreater (DHDT) Unit-31**
**Product affected:** Treated diesel (BS-VI HSD blending stream), sulphur specification 10 ppm (max)
**Equipment implicated:** 31-E-102A (Feed/Effluent Heat Exchanger)
**Period:** 14 May 2025 – 20 June 2025
**Prepared by:** Quality Control Laboratory, Process Engineering and Technical Services

> **SYNTHETIC / DUMMY DATA.** Not an actual MRPL record. All values and names are invented.

---

## 1. Summary

Diesel produced by the DHDT Unit-31 failed the 10 ppm sulphur specification on three occasions between 14 May and 6 June 2025, with the deviation worsening over time. Process parameters and catalyst performance showed no explanation. On 14 June 2025 the unit was shut down and 31-E-102A was pressure tested. Multiple leaking tubes were found. The tubes were plugged and the unit restarted on 20 June 2025, after which product sulphur returned to within specification (6–8 ppm).

## 2. Unit Description

DHDT Unit-31 treats straight-run and cracked gas oil with hydrogen over a fixed catalyst bed to reduce sulphur. Feed is preheated in the feed/effluent exchangers 31-E-102A/B against hot reactor effluent before entering the charge heater. The treated product is stripped in column 31-C-103 and routed to product tank TK-3102 (rundown), then to blending.

In 31-E-102A the untreated feed flows on the **tube side** and the hot reactor effluent on the **shell side**. The feed is at a higher pressure (about 8 bar above the effluent at this point), so a tube leak transfers untreated feed into the effluent (treated) stream. This raises product sulphur without any change in catalyst performance.

---

## 3. Timeline of the Deviation

| Date / time | Event |
|---|---|
| 14 May 2025, 06:10 | On-line analyser AT-3105 (product sulphur) reads 11.6 ppm; laboratory sample at 08:00 confirms 11.8 ppm. First deviation. |
| 14 May 2025 | Shift engineer suspects analyser drift; analyser validated against a reference standard, found accurate (±0.3 ppm). |
| 15–19 May 2025 | Reactor temperature (WABT) raised by 4 °C as corrective action. Sulphur returned briefly to 9.4 ppm. |
| 21 May 2025 | Sulphur 15.4 ppm. Second deviation. Diesel diverted to slop tank TK-3109 for about 30 hours (approx. 1,800 MT). |
| 22 May 2025 | Catalyst activity review: WABT trend, hydrogen-to-oil ratio and hydrogen purity all in the normal band; catalyst ruled out as primary cause. |
| 28 May 2025 | Sample from stripper bottoms shows a sulphur profile inconsistent with catalyst deactivation (sulphur higher after the exchanger than at the reactor outlet). |
| 6 Jun 2025 | Sulphur 21.7 ppm, highest recorded. Third deviation. Additional 2,400 MT of diesel diverted for reprocessing. |
| 9 Jun 2025 | Process Engineering raises suspicion on 31-E-102A. Exchanger pressure differential across the tube side shows a small downward drift over three weeks. |
| 14 Jun 2025 | Unit taken to safe shutdown. |
| 15–17 Jun 2025 | Bundle removal not attempted. Shell-side hydrotest at 1.25× design pressure with the channel cover removed; **14 leaking tubes** identified by water weeping at the tubesheet and tube ends. |
| 17–19 Jun 2025 | Leaking tubes plugged with tapered plugs (14 tubes, bringing the total plugged to 25). Gasket renewed. Re-test acceptable. |
| 20 Jun 2025 | Unit restarted. |
| 21–30 Jun 2025 | Product sulphur 6–8 ppm, within specification. |

## 4. Laboratory Results

| Date | Sample point | Sulphur (ppm) | Spec (ppm) | Result |
|---|---|---|---|---|
| 14 May 2025 | Rundown to TK-3102 | 11.8 | ≤ 10 | Fail |
| 19 May 2025 | Rundown to TK-3102 | 9.4 | ≤ 10 | Pass (after WABT raise) |
| 21 May 2025 | Rundown to TK-3102 | 15.4 | ≤ 10 | Fail |
| 28 May 2025 | Stripper bottoms | 13.9 | ≤ 10 | Fail |
| 6 Jun 2025 | Rundown to TK-3102 | 21.7 | ≤ 10 | Fail |
| 22 Jun 2025 | Rundown to TK-3102 | 7.1 | ≤ 10 | Pass |
| 30 Jun 2025 | Rundown to TK-3102 | 6.4 | ≤ 10 | Pass |

## 5. Quantity Affected

| Item | Quantity |
|---|---|
| Off-spec diesel diverted to slop / reprocessing | About 4,200 MT |
| Off-spec diesel in tank TK-3102 (re-blended) | About 900 MT |
| Estimated production loss and reprocessing cost | ₹2.6 crore (synthetic estimate) |
| Unit downtime | 6 days (14–20 June 2025) |

## 6. Root Cause Analysis

**Direct cause:** Tube leaks in 31-E-102A allowed higher-sulphur feed to enter the treated effluent stream.

**Contributing causes:**
1. Progressive tube wall thinning at the inlet rows, recorded in the April 2025 inspection (IR-2025-04) with 11 tubes already plugged and 27 tubes above 60 % wall loss.
2. The April 2025 recommendation to replace the tube bundle in the 2026 shutdown was **not** converted into an approved project; the bundle had no spare.
3. No routine trending of exchanger differential pressure or product sulphur against exchanger condition existed. The drift in differential pressure went unnoticed for three weeks.
4. The first deviation was attributed to analyser error and catalyst activity for about three weeks before the exchanger was investigated.

**Root cause statement:** Wall loss due to under-deposit corrosion in the inlet tube rows, combined with lack of early detection of a cross-leak, resulted in contamination of the treated diesel.

## 7. Corrective and Preventive Actions

| No. | Action | Owner | Target | Status (20 Sep 2026) |
|---|---|---|---|---|
| CA-1 | Plug leaking tubes and restore unit | Maintenance | 19 Jun 2025 | Closed |
| CA-2 | Procure a spare tube bundle for 31-E-102A (Tender 0412, floated 12 Jul 2025) | Materials / Technical Services | Delivery May 2026 | Delivered 28 May 2026 |
| CA-3 | Install the new bundle during the next shutdown | Maintenance | Feb 2027 | Pending |
| CA-4 | Add exchanger ΔP and product sulphur correlation alarm in DCS | Process / Instrumentation | 31 Aug 2025 | Closed |
| CA-5 | Monthly ECT-based tube health review until bundle replaced | Inspection | Ongoing | In progress |
| CA-6 | Review 31-E-102B for similar degradation | Inspection | 30 Oct 2025 | Closed – no significant degradation |
| CA-7 | Revise decision process so inspection recommendations with a "replace" rating go to the capital committee within 30 days | Technical Services | 31 Dec 2025 | Open |

## 8. Lessons Learned

- A recurring off-spec product with a normal catalyst profile should trigger an early exchanger integrity check.
- Deferred inspection recommendations must carry an owner and due date.
- Spare critical bundles should be available for exchangers with known thinning.

*End of report.*
