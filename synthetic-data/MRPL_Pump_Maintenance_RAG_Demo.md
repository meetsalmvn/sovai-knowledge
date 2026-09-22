# Synthetic Industrial Maintenance Record — Pump P-204A

> **Purpose:** Demonstration knowledge-base document for SovAI RAG + artifact generation.
>
> **Important:** This is a **synthetic demo dataset** created to simulate an MRPL-style refinery maintenance scenario. It is **not an actual MRPL maintenance record, procedure, or safety document** and must not be used for real maintenance work.

## 1. Document Control

| Field | Value |
|---|---|
| Document ID | DEMO-MNT-P204A-001 |
| Equipment ID | P-204A |
| Equipment Type | Centrifugal Process Pump |
| Service | Hydrocarbon Transfer Service |
| Area | Process Unit – Pump Bay 2 |
| Related Motor | M-204A |
| Document Owner | Maintenance Engineering – Rotating Equipment |
| Revision | Rev 02 |
| Effective Date | 15-Sep-2026 |
| Record Type | Maintenance History + Applicable Maintenance Procedure |
| Dataset Status | Synthetic / Prototype Only |

---

# 2. Equipment Overview

Pump P-204A is a horizontal centrifugal process pump used for transfer of hydrocarbon process fluid between two process sections. The pump is driven by electric motor M-204A through a flexible coupling.

### Major maintenance-relevant components

- Pump casing
- Impeller
- Mechanical seal
- Drive shaft
- Bearings
- Coupling
- Baseplate and foundation bolts
- Suction and discharge piping connections
- Local pressure and temperature indicators
- Motor and coupling guard

### Normal operating observations used in maintenance records

The maintenance team tracks:

- Bearing temperature
- Pump vibration
- Mechanical seal leakage
- Discharge pressure
- Suction pressure
- Coupling condition
- Bearing lubrication condition
- Foundation and anchor-bolt condition
- Unusual noise
- Motor current / loading

---

# 3. Maintenance History

## 3.1 Event — 06-Jun-2026

**Work Order:** WO-204A-061

**Reported issue:** Increased vibration observed near the non-drive-end bearing during routine operator rounds.

**Recorded observation:** Overall vibration measured at approximately 4.8 mm/s RMS. The condition was above the site's normal operating band for this equipment but did not result in an immediate trip.

**Inspection findings:**

- Non-drive-end bearing showed early signs of wear.
- Coupling alignment was found marginally outside the preferred alignment condition.
- No significant external leakage observed.

**Actions completed:**

1. Pump was taken out of service under the approved maintenance isolation process.
2. Bearing condition was inspected.
3. Coupling alignment was checked.
4. Coupling alignment was corrected.
5. Bearing condition was monitored after return to service.

**Post-maintenance observation:** Vibration reduced after alignment correction, but the maintenance engineer recommended continued monitoring of the non-drive-end bearing.

**Follow-up:** Add vibration trend to the next planned inspection.

---

## 3.2 Event — 19-Jul-2026

**Work Order:** WO-204A-074

**Reported issue:** Intermittent high vibration during operation.

**Recorded observation:** Vibration increased during several operating periods and was accompanied by a noticeable increase in bearing temperature compared with previous rounds.

**Inspection findings:**

- Vibration trend showed repeated excursions.
- Non-drive-end bearing remained a point of concern.
- No major process-side leak was identified.
- Coupling condition was visually acceptable after previous alignment correction.

**Actions completed:**

- Vibration readings were repeated and logged.
- Bearing temperature trend was reviewed.
- Lubrication condition was checked according to the applicable maintenance procedure.
- Equipment was placed on enhanced monitoring.

**Follow-up:** Inspect the non-drive-end bearing at the next planned shutdown and review vibration history before deciding on bearing replacement.

---

## 3.3 Event — 22-Aug-2026

**Work Order:** WO-204A-089

**Reported issue:** Minor mechanical seal leakage and recurring vibration.

**Recorded observation:**

- Minor leakage was observed around the mechanical seal area.
- Vibration remained intermittently elevated.
- Bearing temperature was higher than the baseline recorded after the June intervention.

**Inspection findings:**

- Mechanical seal showed signs consistent with wear.
- Non-drive-end bearing remained under suspicion based on trend history.
- No visible foundation crack was observed.
- Baseplate fasteners were checked; no obvious looseness was recorded.

**Actions completed:**

1. Mechanical seal condition was inspected.
2. Leakage was monitored.
3. Vibration and bearing temperature readings were recorded.
4. A recommendation was raised for planned seal replacement and detailed bearing inspection during the next suitable maintenance window.

**Follow-up:**

- Plan mechanical seal replacement.
- Inspect/replace non-drive-end bearing depending on inspection findings.
- Reconfirm shaft/coupling alignment after maintenance.
- Record post-maintenance vibration baseline.

---

## 3.4 Event — 08-Sep-2026

**Work Order:** WO-204A-097

**Reported issue:** Operator reported abnormal vibration shortly after start-up.

**Recorded observation:** Vibration was higher than the recent operating trend. A short-duration increase in bearing temperature was also noted.

**Immediate maintenance response:**

- Operator informed control-room/maintenance personnel.
- Pump condition was assessed against the approved operating and safety procedure.
- Equipment was not opened or dismantled while energized or in an unsafe state.
- The event was entered into the maintenance log for engineering review.

**Inspection status:** Detailed inspection was deferred to the next approved maintenance opportunity.

**Pending items:**

- Review full vibration trend.
- Inspect non-drive-end bearing.
- Inspect mechanical seal.
- Verify coupling alignment after inspection/repair.
- Establish a fresh vibration and temperature baseline after corrective work.

---

# 4. Recurring Issues Identified from History

Across the maintenance records from June through September 2026, the recurring issues are:

### Recurring Issue A — Elevated Vibration

Vibration has been reported repeatedly across multiple maintenance events. The non-drive-end area is repeatedly referenced as a point requiring attention.

### Recurring Issue B — Non-Drive-End Bearing Concern

The non-drive-end bearing was identified as a concern in June and remained a monitoring point in July, August and September records.

### Recurring Issue C — Mechanical Seal Wear / Leakage

Minor mechanical seal leakage was recorded in August, with a recommendation for planned replacement.

### Recurring Issue D — Alignment Verification

Coupling alignment required correction in June and is recommended for re-verification after planned maintenance.

---

# 5. Applicable Maintenance Procedure

## Procedure ID

**MNT-PROC-ROT-014 — Planned Maintenance and Inspection of Centrifugal Process Pumps**

**Revision:** Rev 04

> This procedure is synthetic and intended only for SovAI demonstration purposes.

## 5.1 Purpose

To define the maintenance and inspection sequence for centrifugal process pumps, including equipment isolation, inspection, component checks, corrective maintenance and controlled return to service.

## 5.2 Applicability

Applicable to routine inspection and planned maintenance of centrifugal process pumps in process areas where the equipment is handled under the site's approved permit, isolation and process-safety controls.

## 5.3 Preconditions

Before physical maintenance begins:

1. Confirm the equipment identity and work order scope.
2. Review current operating status and recent maintenance history.
3. Obtain the required work permit(s) under the site's permit-to-work system.
4. Confirm the pump has been removed from normal service according to the approved operating procedure.
5. Isolate the energy/process sources identified for the equipment and verify the isolation through the approved site process.
6. Depressurize, drain, vent and otherwise render the equipment safe as required by the approved site procedure for the service.
7. Confirm zero-energy / safe-to-work condition before opening or dismantling the equipment.
8. Verify required PPE and gas-testing requirements for the area/service.

## 5.4 Inspection Sequence

### Step 1 — External condition check

Inspect:

- Pump casing exterior
- Baseplate
- Foundation and anchor bolts
- Coupling guard
- Piping connections
- Visible leakage
- Signs of overheating or abnormal staining

### Step 2 — Vibration and temperature review

Review recent historical readings and compare available current values with the established equipment trend/baseline.

Record:

- Overall vibration
- Bearing temperature
- Date/time
- Operating condition
- Any abnormal noise or process condition

### Step 3 — Bearing inspection

Inspect the relevant bearing condition for:

- Wear
- Abnormal noise
- Lubrication condition
- Signs of overheating
- Evidence consistent with the vibration trend

Bearing replacement should be based on inspection findings and the approved maintenance decision process.

### Step 4 — Mechanical seal inspection

Inspect for:

- Leakage
- Visible wear or damage
- Abnormal operating condition

If replacement is required, use the approved replacement specification and installation procedure applicable to the pump.

### Step 5 — Coupling and alignment

Inspect coupling condition and verify alignment using the approved alignment method/tool.

Any alignment correction should be documented, including the before/after condition where the applicable measurement method supports it.

### Step 6 — Fasteners and foundation

Check accessible fasteners and foundation condition. Document any abnormal looseness, damage or deterioration.

### Step 7 — Post-maintenance checks

After maintenance:

- Confirm all tools/materials are removed from the equipment.
- Confirm guards and covers are correctly reinstated.
- Confirm the work area is clear.
- Confirm the equipment is ready for controlled return to service under the approved operating procedure.
- Record post-maintenance vibration and bearing-temperature baseline.
- Record any remaining follow-up action.

---

# 6. Safety Precautions and Isolation Requirements

> **Synthetic demonstration content. Real maintenance must use the current site-approved procedure, permit, isolation plan, and competent-authority instructions.**

Before maintenance starts, the following controls are required under this demo procedure:

### 6.1 Permit and authorization

- Confirm the correct maintenance work order.
- Obtain the applicable work permit(s).
- Confirm the scope of work is understood by the maintenance team.

### 6.2 Isolation

- Isolate the pump from relevant process and energy sources using the approved site isolation procedure.
- Prevent unintended start-up.
- Verify the isolation before opening, dismantling or inspecting the equipment.
- Where applicable, apply the site's lockout/tagout or equivalent energy-isolation controls.

### 6.3 Depressurization and process safety

- Confirm the pump is depressurized.
- Drain and vent the equipment through approved safe means.
- Treat residual process material as hazardous until the approved verification process establishes a safe condition.
- Perform required gas testing before intrusive work where specified by the permit or site procedure.

### 6.4 Personal protective equipment

Required PPE shall be selected according to the approved site risk assessment and service. The demonstration procedure assumes, as a minimum, the applicable refinery workwear and task-specific PPE, with additional PPE based on the identified hazards.

### 6.5 Mechanical safety

- Do not work on rotating equipment while it is operating unless an approved procedure explicitly permits a specific inspection activity.
- Reinstall coupling guards before return to service.
- Use suitable lifting equipment for heavy components.
- Keep hands and loose clothing away from rotating or pinch-point hazards.

### 6.6 Restart safety

Before restart:

- Confirm maintenance scope is complete.
- Confirm personnel are clear.
- Confirm tools and loose materials are removed.
- Confirm guards are restored.
- Confirm all required permits/clearances have been completed.
- Start the equipment under the approved operating procedure.
- Monitor vibration, bearing temperature and leakage during the controlled return to service.

---

# 7. Required Tools and Equipment

The following tools are identified for the planned inspection/work scope in this synthetic procedure:

| Tool / Equipment | Intended Use |
|---|---|
| Portable vibration meter | Record pump vibration trend |
| Infrared thermometer / approved temperature instrument | Check bearing and equipment temperature |
| Laser or approved coupling-alignment tool | Verify coupling alignment |
| Standard mechanical hand-tool set | General inspection/removal work |
| Torque wrench | Controlled tightening of specified fasteners |
| Inspection lamp | Visual inspection of accessible components |
| Feeler gauges / approved measuring tools | Where applicable during inspection/alignment work |
| Portable gas detector | Required where specified by permit/risk assessment |
| Certified lifting equipment | Handling heavy pump components where required |
| PPE required by permit/risk assessment | Personnel protection |

The exact tool selection must be confirmed against the actual equipment configuration and approved maintenance scope before field work.

---

# 8. Recommended Maintenance Work Scope

Based on the maintenance history and the applicable procedure, the planned work scope for P-204A should address the recurring issues documented in the records.

### Priority Work Item 1 — Detailed vibration investigation

- Review all available vibration readings and trend history.
- Inspect the non-drive-end bearing.
- Record inspection findings.
- Determine whether replacement is required based on approved maintenance criteria.

### Priority Work Item 2 — Mechanical seal inspection / replacement planning

- Inspect seal condition and leakage evidence.
- Replace the mechanical seal if inspection confirms replacement is required and the approved replacement specification is available.
- Record final condition.

### Priority Work Item 3 — Coupling alignment verification

- Check coupling alignment after bearing/seal-related maintenance.
- Correct alignment if required.
- Record measurement and final condition.

### Priority Work Item 4 — Baseline restoration

After corrective work:

- Record vibration baseline.
- Record bearing temperature baseline.
- Record leakage condition.
- Compare against the recent pre-maintenance trend.

---

# 9. Pending Follow-Up Actions

| Action ID | Pending Action | Suggested Priority | Status |
|---|---|---|---|
| FA-204A-01 | Detailed non-drive-end bearing inspection | High | Open |
| FA-204A-02 | Review vibration trend and establish current baseline | High | Open |
| FA-204A-03 | Inspect mechanical seal and plan replacement if required | Medium | Open |
| FA-204A-04 | Verify coupling alignment after maintenance | Medium | Open |
| FA-204A-05 | Record post-maintenance vibration and temperature baseline | Medium | Open |
| FA-204A-06 | Review recurring vibration history with maintenance engineering | Medium | Open |
| FA-204A-07 | Update maintenance history after completion of planned work | Low | Open |

---

# 10. Proposed Work Order Summary

**Work Order Title:** P-204A — Planned Inspection and Corrective Maintenance for Recurring Vibration / Seal Condition

**Equipment:** P-204A centrifugal process pump

**Primary Issue:** Recurring elevated vibration with repeated concern around the non-drive-end bearing; mechanical seal wear/leakage also recorded.

**Work Scope:**

1. Verify isolation and safe-to-work condition.
2. Review recent maintenance and vibration history.
3. Inspect pump exterior, baseplate and accessible fasteners.
4. Inspect non-drive-end bearing.
5. Inspect mechanical seal.
6. Verify coupling condition and alignment.
7. Perform approved corrective maintenance based on inspection findings.
8. Reinstate guards and equipment condition.
9. Return equipment to service under the approved operating procedure.
10. Record post-maintenance vibration, temperature and leakage baseline.

**Safety:** Follow current permit-to-work, isolation, depressurization, gas-testing, PPE and restart requirements applicable to the actual site and equipment.

**Required Tools:** Vibration meter, temperature instrument, approved alignment tool, mechanical hand tools, torque wrench, inspection lamp, measuring tools, gas detector where required, certified lifting equipment where required, and task-specific PPE.

**Follow-Up:** Close or update FA-204A-01 through FA-204A-07 based on actual inspection and maintenance results.

---

# 11. Evidence References Within This Dataset

Use these record IDs when producing grounded answers:

- **WO-204A-061** — June vibration/alignment event
- **WO-204A-074** — July recurring vibration/bearing monitoring event
- **WO-204A-089** — August mechanical seal leakage + recurring vibration
- **WO-204A-097** — September abnormal vibration after start-up
- **MNT-PROC-ROT-014 Rev 04** — applicable centrifugal pump maintenance procedure
- **FA-204A-01 to FA-204A-07** — pending follow-up actions

---

# 12. Grounding Rules for AI Retrieval

When SovAI uses this document:

1. Use only information supported by the retrieved maintenance records and procedure.
2. Distinguish historical observations from recommended future actions.
3. Do not invent equipment readings, dates, personnel names, spare-part numbers, permit numbers or inspection results.
4. If a requested field is not supported by the records, mark it as **Not available in the knowledge base**.
5. Safety-critical actions must be presented as procedure-derived requirements and should not be replaced by generic assumptions.
6. For generated artifacts, preserve the equipment ID, work-order references, issue history, required actions, safety controls, tools and pending actions from the retrieved evidence.
