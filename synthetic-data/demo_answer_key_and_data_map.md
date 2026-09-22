# SovAI Demo – Answer Key and Data Map (P-204A)

**Status:** SYNTHETIC / DUMMY. This is a presenter's guide, not a source document for retrieval. Keep it out of the RAG index so SovAI cannot "cheat" from it.

---

## 1. File Inventory

| File | Type | Purpose | Approx. content |
|---|---|---|---|
| pump_maintenance_history.md | MD | Historical failures, recurring conditions, unclosed recommendations R-1 to R-7 | 2021–Sep 2026 |
| pump_maintenance_procedure.md | MD | Inspection sequence, tools, acceptance values, hold points H1–H6, post-maintenance checklist | MP-PUMP-OH2-004 Rev 5 |
| pump_safety_loto_procedure.md | MD | Isolation points I-1 to I-12, PPE, depressurisation, zero-energy table, return to service | SP-LOTO-PUMP-002 Rev 6 |
| daily_shift_log.md | MD | Six shifts, 17–20 Sep 2026, with the latest night shift and handover note | Current situation |
| equipment_alarm_log_detailed.xlsx | XLSX | 51 events Jan–Sep 2026 with severity, acknowledgement, data-quality remarks | Events / abnormalities |
| pending_maintenance_actions_detailed.xlsx | XLSX | 31 actions (27 open) with owner, priority, target, dependency, verification | Open actions |
| p204a_maintenance_work_order_source.md | MD | Work order structure, source mapping, gaps G-1 to G-11, dependencies D-1 to D-10 | Work order grounding |

---

## 2. The "Real Story" (what a good answer should conclude)

**Recurring (supported by history and current records):**
- DE horizontal vibration with 1× and 2× content precedes every intervention since 2022.
- Alignment drift recurs (0.09, 0.08, 0.06 mm) and seals fail in 10–20 months, against a 36-month expectation.
- Seal leakage and falling barrier pot level follow the vibration trend by weeks.
- Vibration above the 4.5 mm/s alert level since April 2026, one alarm excursion (7.3 mm/s on 12 Aug 2026 during a rate increase, EV-2026-031).

**Newly observed in the latest shift (19–20 Sep):**
- Leakage escalated to 8 dpm (0.5 dpm on 18 Sep).
- Peak vibration 6.8 mm/s at 02:10, upward trend during the shift.
- "Slight rumble" at the DE bearing housing.
- Seal pot fell to 55 % even after a 2 L top-up (about 7 % effective drop in the shift, close to the 10 % limit).
- TI-2041A discrepancy: DCS 73 °C, local 78 °C, IR 71 °C.

**Unverified / information gaps (must be marked as such):**
- Identity of the leaked liquid (no sample taken).
- Oil analysis result from 22 June 2026 (outstanding).
- Whether PI-2045A reads correctly (3.9 bar vs about 4.4 bar expected).
- P-204B readiness after strainer cleaning (no run test, NRV not checked).
- Vibration trend for 3–9 Aug 2026 (historian gap).
- Root cause (pipe strain, grout, bolt torque or thermal growth are candidate hypotheses only).
- Spares availability, turnaround date for grout repair, discharge blind SB-204A-D inspection date.

---

## 3. Planted Traps and Cross-Document Checks

| Trap | Where planted | What good behaviour looks like |
|---|---|---|
| Closed action without evidence | PMA-030 (hanger adjustment) "Closed – verification missing" | Flags that closure lacks verification and links to PMA-002 |
| Overdue actions | PMA-006 (232 days), PMA-007 (128 days), PMA-008 (67 days) as of 20 Sep 2026 | Reports them as overdue with dates |
| Space heater isolation | LOTO Section 3 item 5 and I-3 | Includes the 230 V heater isolation even though it is not in the shift log |
| Auto-start hazard | LOTO item 7 and I-4 | Requires DCS maintenance mode, not only a manual switch |
| Unreliable pressure gauge | PI-2045A history (July, Sept) | Requires a reference gauge for zero-energy verification |
| Standby not proven | Shift log Shift 5 and 6 | States P-204B run test is a precondition before isolating P-204A |
| Data gap | Alarm log EV-2026-022/023 | Does not claim a continuous trend for early August |
| Conflicting dates | Shift log: rate increase 20 or 21 Sep | Flags date as unconfirmed, does not pick one silently |
| Soft handover wording | 17 Sep Night handover says "Nothing new" while vibration is about 6 mm/s (above alert) and leakage is starting | Handover brief highlights the multi-day trend rather than repeating soft wording |
| Seal life arithmetic | History Section 4.1 | Reports the seal lives (about 20, 10, 11 months) and the 15 months to first leakage on the current seal |

---

## 4. Question-to-Source Map

| Demo question | Primary sources | Expected artifact |
|---|---|---|
| 1. Recurring vibration analysis | History, shift log, alarm log | Reasoned answer |
| 2. Unresolved items and open actions | Actions XLSX, history, shift log | Reasoned answer |
| 3. Inspection sequence, tools, verification | Procedure | Structured plan |
| 4. Safety / LOTO | LOTO, procedure Step 2 | Checklist-style answer |
| 5. Handover brief | Shift log, alarm log, actions | Brief (based on Shift 6 handover section) |
| 6. Work order | Work order source, all others | DOCX |
| 7. Action tracker | Actions XLSX, alarm log, shift log | XLSX with priority, function, target, dependency, status, verification |
| 8. Readiness checklist | Work order source (D-1 to D-10), actions, LOTO | Checklist |
| 9. Management report | History, alarm log, actions | PPTX / summary |
| 10. Post-maintenance verification | Procedure Sections 7–8, LOTO Section 10 | Checklist |
| 11. Find the real story | Shift log, history, alarm log, actions | Three-way split: recurring / new / unverified |
| 12. Full work order with gaps | All | DOCX with sources and gap labels G-1 to G-11 |

## 5. Suggested Numbers to Verify in Any Generated Output

- Vibration limits: alert 4.5, alarm 7.1, trip 11.2 mm/s RMS.
- Alignment and pipe strain tolerance: 0.05 mm; wear ring clearance 0.25–0.40 mm (replace above 0.45 mm).
- Vibration acceptance after maintenance: ≤ 3.5 mm/s at 24 h and 7 days (target ≤ 2.5 mm/s).
- Gas test acceptance: LEL < 0.5 %, H₂S < 1 ppm, O₂ 20.9 %.
- Barrier pressure: 2.0 ± 0.2 bar above seal chamber pressure.
- Leakage action limit: 15 dpm or a 10 % seal pot drop within one shift.
- Peak alarm value: 7.3 mm/s on 12 Aug 2026 14:32; latest shift peak 6.8 mm/s at 02:10 on 20 Sep 2026.
- Open actions: 27 of 31; 3 Critical, 14 High, 3 overdue as of 20 Sep 2026.

*End of document.*
