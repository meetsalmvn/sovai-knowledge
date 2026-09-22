# MRPL Demo – Answer Key and Data Map

**Status:** SYNTHETIC / DUMMY. Presenter's guide only. Keep this file out of the RAG index.
MRPL (Mangalore Refinery and Petrochemicals Limited) is used as the demo setting. All vendors, numbers, tender IDs and people are fictional.

---

## 1. Files

| File | Type | Answers |
|---|---|---|
| mrpl_tender_summary_report_0412.md | MD | Q1 tender summary |
| mrpl_tender_register_2025.xlsx | XLSX | Q1 (register, document purchase log, bid evaluation) |
| mrpl_product_failure_incident_report.md | MD | Q2 unit of product failure, and background for Q3 |
| mrpl_equipment_history_31E102A.md | MD | Q3 what happened last time, Q4 |
| mrpl_maintenance_records_31E102A.xlsx | XLSX | Q4 previous maintenance |
| mrpl_inspection_reports_31E102A.md | MD | Q5 changes between inspections |
| mrpl_inspection_readings_31E102A.xlsx | XLSX | Q5 numeric evidence with formulas |

---

## 2. Expected Answers

### Q1. "Give me the summary report of the tender bought on 12 July 2025."

Expected: Tender **MRPL/PUR/MECH/2025-26/0412**, published 12 July 2025, for a replacement tube bundle for exchanger 31-E-102A in DHDT Unit-31.

Key facts: estimate ₹4.20 crore; six firms bought documents (three of them on 12 July: Vishwa Thermal, Coastal Exchangers, Nordhaus-Rao); four bids received; Nordhaus-Rao technically disqualified; L1 Vishwa Thermal ₹3.87 crore, L2 Coastal ₹4.05 crore, L3 Kaveri ₹4.31 crore; negotiated award ₹3.79 crore; LOA 14 Oct 2025; delivery due 12 May 2026, actual 28 May 2026; installation planned Feb 2027; LD of about ₹3.8 lakh not yet deducted.

**Ambiguity trap:** "bought on 12 July 2025" can mean *published/documents on sale* or *documents purchased*. Two firms also bought documents for **Tender 0388** (hydrojetting rate contract, published 18 June 2025) on 12 July 2025. A strong answer picks 0412 as the tender published on 12 July 2025 and mentions the 0388 purchases as an alternative reading. There is also a **12 July 2024** tender (cooling tower fill, CIV/2024-25/0731) that must not be confused with it.

### Q2. "In which unit was the product failure observed?"

Expected: **Diesel Hydrotreater (DHDT) Unit-31**. Treated diesel failed the 10 ppm sulphur specification on 14 May (11.8 ppm), 21 May (15.4 ppm) and 6 June 2025 (21.7 ppm). Implicated equipment: feed/effluent exchanger 31-E-102A. About 4,200 MT diverted for reprocessing and about 900 MT re-blended.

### Q3. "What happened to this equipment last time?"

Expected: 14–20 June 2025 emergency shutdown. Shell-side hydrotest found 14 leaking tubes in rows 1–4; all plugged (25 of 640 total, 3.9 %); channel gasket renewed; restart on 20 June 2025; product sulphur back to 6–8 ppm. Root cause: under-deposit corrosion wall loss in inlet rows with a deferred replacement recommendation from April 2025. Follow-up: spare bundle ordered (Tender 0412), delivered 28 May 2026, not yet installed.

### Q4. "What maintenance was performed previously?"

Expected (from the maintenance workbook and history card): annual cleaning 2016 and 2017; full turnaround March 2019 (bundle pull, ECT, no plugging); gasket weep repair May 2021; shell flange leak Aug 2022; opportunity shutdown Nov 2023 (4 tubes plugged); head gasket Feb 2024; planned shutdown April 2025 (7 more plugged, total 11); emergency repair June 2025 (14 plugged, total 25); quarterly ECT screening Sep 2025 to Jun 2026; DP transmitter calibration Feb 2026; bundle receipt May 2026; replacement planned Feb 2027 (not executed).

### Q5. "What changed between the last two inspections?"

**By date, the last two inspections are IR-2025-04 (14 Apr 2025) and IR-2025-06 (16 Jun 2025).**
Expected changes: plugged tubes 11 → 25 (+14); leaking tubes 0 → 14; tubes ≥ 80 % wall loss 7 → 12; tubes 60–79 % 20 → 24; minimum row 1 wall 2.14 → 2.08 mm; tubesheet pitting 0.4 → 0.5 mm; gasket replaced again; recommendation urgency raised (remaining life under 12 months).

**Ambiguity trap:** IR-2025-06 is an emergency post-failure inspection, not a scheduled one. If the user means the last two *scheduled* inspections, the comparison is IR-2023-11 vs IR-2025-04 (plugged 4 → 11; tubes above 60 % loss 9 → 27; row 1 wall 2.31 → 2.14 mm; row 1 loss rate about 0.03 → 0.12 mm/yr). A good answer states which pair it used and offers the other.

---

## 3. Planted Details and Gaps

| Item | Where | Why it matters |
|---|---|---|
| Two tenders with purchases on 12 Jul 2025 | Doc_Purchase_Log | Tests disambiguation |
| Tender with NIT on 12 Jul 2024 | Tender_Register | Tests date precision |
| Tenders published after the failure but the recommendation predates it | Inspection report April 2025 | Tests cross-document narrative |
| April 2025 report lacks plugged tube coordinates | Inspection reports INS-3 | Information gap |
| LD not yet deducted; PBG validity short of warranty | Tender summary sections 10–11 | Open commercial issues |
| Historian tag renamed March 2024 | Equipment history section 5 | Missing DP trend |
| First deviation attributed to analyser and catalyst for about three weeks | Incident report | Diagnostic delay |
| Planned job WO-2027-0201 is not completed | Maintenance workbook | Should not be reported as done |

## 4. Numbers to Verify

- Tubes: 640; plugging limit 10 % (64); plugged 0 → 4 → 11 → 25.
- Minimum required wall 1.90 mm; row 1 wall 2.45 → 2.31 → 2.14 → 2.08 mm.
- Sulphur deviations: 11.8, 15.4, 21.7 ppm against 10 ppm; back to 7.1 and 6.4 ppm after repair.
- Tender: estimate ₹4.20 crore; L1 ₹3.87 crore; award ₹3.79 crore (−9.8 % vs estimate, −2.1 % vs L1).
- Workbook totals: 16 completed work orders, 1,134 hours downtime and ₹129.2 lakh cost across completed jobs.

*End of document.*
