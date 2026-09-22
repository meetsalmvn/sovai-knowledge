# Synthetic MRPL-Style Maintenance Record

## Document Title
Pump P-204A — Maintenance History and Recurring Issue Register

**Document Type:** Equipment Maintenance History
**Document ID:** SYN-MRPL-P204A-MH-001
**Revision:** Rev 1.0
**Data Classification:** Synthetic / Demonstration Data
**Purpose:** RAG prototype and artifact-generation demonstration for SovAI

> **Important:** This is synthetic demonstration data created to resemble a refinery maintenance record. It is not an actual MRPL maintenance document and must not be treated as an operational instruction or plant record.

---

## 1. Equipment Identification

| Field | Value |
|---|---|
| Equipment Tag | P-204A |
| Equipment Type | Process Cooling Water Pump |
| Service | Cooling-water circulation to process equipment |
| Pump Configuration | Horizontal centrifugal pump |
| Driver | Electric motor |
| Area | Utilities / Cooling Water Area |
| Train | Cooling Water Train A |
| Criticality | High |
| Normal Operating Status | In service / duty pump |
| Standby Equipment | P-204B |

### Associated Components

- Mechanical seal assembly
- DE and NDE bearings
- Flexible coupling
- Suction isolation valve
- Discharge isolation valve
- Motor starter / electrical supply
- Local vibration monitoring point
- Pressure gauges on suction and discharge

---

## 2. Maintenance History Summary

The following synthetic maintenance records cover the period from **January 2026 through September 2026**.

### Record MH-2026-014 — 18 January 2026

**Reported issue:** Elevated vibration observed at the pump DE bearing location.

**Observed condition:**
- Overall vibration increased above the routine baseline.
- No visible seal leakage was recorded.
- Pump discharge pressure remained available for service.
- Operator requested inspection during the next maintenance window.

**Maintenance action:**
- Checked bearing housing condition.
- Verified coupling guard condition.
- Performed alignment check.
- No immediate bearing replacement was performed.

**Finding:** Minor coupling alignment deviation suspected.

**Disposition:** Pump returned to service after inspection.

**Follow-up:** Add vibration trend monitoring to weekly operator rounds.

---

### Record MH-2026-032 — 27 March 2026

**Reported issue:** Recurrence of elevated vibration at the DE bearing area.

**Observed condition:**
- Vibration increased compared with the January inspection.
- Intermittent abnormal noise was reported during operation.
- Coupling area showed no visible damage.

**Maintenance action:**
- Pump isolated according to site maintenance procedure.
- Coupling alignment rechecked.
- Bearing housing inspected.
- Lubrication condition checked.

**Finding:** Alignment was adjusted. Bearing condition remained acceptable based on visual inspection.

**Disposition:** Pump returned to service.

**Follow-up:** Continue vibration trending and inspect bearing condition during next planned shutdown.

---

### Record MH-2026-061 — 16 June 2026

**Reported issue:** Mechanical seal leakage with increased vibration.

**Observed condition:**
- Visible leakage detected around the mechanical seal area.
- Pump vibration remained above the established operating baseline.
- Operator reported abnormal sound during operation.

**Maintenance action:**
- Pump removed from service.
- Mechanical seal inspected.
- Coupling alignment checked.
- Bearing housing inspected.

**Finding:** Mechanical seal showed wear. Coupling alignment required correction.

**Corrective action:**
- Mechanical seal replaced.
- Coupling alignment corrected.
- Post-maintenance leak check performed.

**Disposition:** Pump returned to service after satisfactory post-maintenance inspection.

**Follow-up:** Monitor seal leakage and vibration during routine rounds.

---

### Record MH-2026-083 — 29 August 2026

**Reported issue:** Repeated elevated vibration following previous corrective maintenance.

**Observed condition:**
- Vibration again increased at the DE bearing location.
- No significant seal leakage was visible at the time of inspection.
- Operator reported intermittent abnormal vibration during operation.

**Maintenance action:**
- Compared current readings with historical maintenance records.
- Rechecked coupling alignment.
- Inspected bearing housing.
- Reviewed previous vibration observations.

**Finding:** Recurring vibration pattern remained unresolved. Further detailed inspection recommended during the next planned maintenance opportunity.

**Disposition:** Pump remained in service under enhanced monitoring.

**Follow-up:**
- Perform detailed bearing inspection.
- Verify shaft/coupling alignment using calibrated equipment.
- Review vibration trend data.
- Escalate recurring vibration if trend continues to increase.

---

## 3. Recurring Issues Identified from History

Based only on the maintenance records above, the following recurring patterns are documented:

### 3.1 Elevated Vibration — Recurring

Elevated vibration was recorded in:

- January 2026
- March 2026
- June 2026
- August 2026

The DE bearing area is repeatedly referenced in the records.

### 3.2 Coupling Alignment — Repeated Intervention

Coupling alignment was checked or corrected during multiple maintenance events. The June 2026 record specifically notes alignment correction, while the August 2026 record recommends another verification.

### 3.3 Mechanical Seal Wear / Leakage

A mechanical seal leakage event was documented in June 2026. The seal was replaced and a post-maintenance leak check was completed.

### 3.4 Enhanced Monitoring Requirement

The August 2026 record recommends continued vibration monitoring and a more detailed inspection because the vibration pattern recurred after previous corrective actions.

---

## 4. Current Maintenance Status from Latest Record

**Latest historical record:** MH-2026-083 dated 29 August 2026.

**Current documented condition:**
- Pump remains in service.
- Recurring elevated vibration is still a concern.
- No significant seal leakage was observed during the latest inspection.
- Enhanced monitoring is required.
- Detailed bearing inspection is recommended at the next planned maintenance opportunity.

---

## 5. Documented Pending Follow-Up Actions

The latest record identifies the following actions:

| Action ID | Pending Action | Source Record | Status |
|---|---|---|---|
| PA-01 | Perform detailed DE/NDE bearing inspection | MH-2026-083 | Pending |
| PA-02 | Verify shaft/coupling alignment using calibrated equipment | MH-2026-083 | Pending |
| PA-03 | Review vibration trend data against historical observations | MH-2026-083 | Pending |
| PA-04 | Continue enhanced vibration monitoring during operation | MH-2026-083 | Ongoing |
| PA-05 | Escalate recurring vibration if trend continues to increase | MH-2026-083 | Conditional |

---

## 6. Evidence Map for RAG Retrieval

### Query intent: Maintenance history
Retrieve:
- MH-2026-014
- MH-2026-032
- MH-2026-061
- MH-2026-083

### Query intent: Recurring issues
Retrieve:
- Section 3
- MH-2026-014
- MH-2026-032
- MH-2026-061
- MH-2026-083

### Query intent: Current issue
Retrieve:
- Section 4
- MH-2026-083

### Query intent: Pending maintenance actions
Retrieve:
- Section 5
- MH-2026-083

### Query intent: Work-order preparation
This document can provide:
- Equipment identity
- Historical issue evidence
- Recurring vibration evidence
- Historical corrective actions
- Current pending actions

This document **does not** provide the complete maintenance procedure, safety/LOTO requirements, permit requirements, or complete tool list. Those should be retrieved from their respective source documents rather than inferred from this document.

---

## 7. Grounding Rules for SovAI

When answering questions from this document:

1. Use only the facts explicitly recorded above.
2. Do not invent vibration measurements, dates, failure causes, personnel names, work-order numbers, or inspection results.
3. Treat recurring vibration as a documented recurring condition, not as a proven root cause.
4. Do not infer that a bearing has failed; the latest record only recommends detailed inspection.
5. Do not create safety or isolation instructions from this document alone.
6. For a maintenance work order, combine this evidence with the separate maintenance procedure and safety/LOTO source documents.
7. Clearly identify information that is unavailable from the retrieved source material.

---

## 8. Suggested RAG Test Questions

1. Show me the maintenance history of pump P-204A and identify recurring issues.
2. How many maintenance events recorded elevated vibration?
3. What corrective action was taken after the June 2026 seal leakage event?
4. What issues remain unresolved according to the latest record?
5. What pending actions are associated with the recurring vibration problem?
6. Based on the maintenance history, prepare the issue section of a maintenance work order.

---

**End of Document**
