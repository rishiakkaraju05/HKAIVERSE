# Task 1 — Step 3: Synthetic Test Cases for the Proposed SIS Workflow

**Prepared:** 24 October 2026  
**Status:** Desk-test of a proposed workflow; not a test of the live ICFAI SIS  
**Test data:** Fictional examples only

## 1. Test objective

Check whether the proposed issue-reporting workflow handles five required situations: a normal report, missing information, a duplicate, an unauthorised request, and a failed step. Each case specifies the expected outcome and recovery. These are scenario-based tests of the design, not evidence that ICFAI's live system behaves this way.

## 2. Test cases

| Test ID | Scenario / synthetic input | Expected workflow behaviour | Expected status / owner | Recovery or control | Pass condition |
|---|---|---|---|---|---|
| TC-01 | **Normal report:** A fictional student reports that a non-sensitive SIS page shows an error. They provide the page name, approximate time, error text, expected result, and reproduction steps. | Validate required fields, create a ticket reference, check for duplicates, route to the SIS technical team, and send confirmation. | `Assigned` after triage; coordinator owns intake, assigned technical owner handles investigation. | Owner records findings, follows the approved fix process, then sends a resolution summary. Reopen if the problem persists. | Ticket has a reference, owner, status history, and student-facing confirmation; no sensitive information is requested. |
| TC-02 | **Missing information:** A fictional report says “SIS is not working” but names no page, time, or observed behaviour. | Do not route it as a fully actionable technical issue. Ask for specific missing details. | `Needs information`; coordinator remains responsible. | Student supplies details; coordinator checks completeness and resumes triage. If the student cannot provide a detail, record that fact and route only if enough information remains to investigate safely. | The report is not silently discarded or marked resolved; the requested details and next action are clear. |
| TC-03 | **Duplicate:** A fictional student reports the same page error already recorded in an open synthetic ticket, `SIS-DEMO-014`. | Link the new report to the existing ticket and retain the new report as a linked report for impact counting. | Existing ticket keeps its investigation status and owner; new report is marked as linked duplicate according to the prototype's status convention. | Tell the student the existing reference and update path. Keep it separate if evidence shows a distinct failure. | No second investigation is started unnecessarily; the new reporter receives a reference, and the additional report remains countable. |
| TC-04 | **Unauthorised request:** A fictional user asks support to change another student's marks through an SIS issue ticket, without authorisation. | Do not make the change. Explain that the ticketing route cannot authorise a protected record change. Route the request only through an approved academic-record process if appropriate. | The ticket remains with the coordinator pending authorised routing, or is closed as out of scope with a clear explanation if no legitimate issue is being reported. | Escalate through the institution's authorised process if the request raises a security or privacy concern. Do not disclose the other student's information. | No unauthorised data change occurs; access boundaries are respected and the action/reason is recorded. |
| TC-05 | **Failed step:** The proposed form fails while creating a ticket and no ticket reference is generated. | Do not display a false success message or claim the report was received. | No valid ticket exists yet; coordinator is not considered to have received it until the fallback report is logged. | Tell the student to retry or use an institution-approved alternate support channel. If a report is received through the fallback, log it manually with a timestamp and note that it came through the fallback. Check for accidental duplicates if the student retries. | The failure is clear to the student, there is a usable recovery path, and no report is falsely treated as successfully submitted. |

## 3. Test results

These are **expected results from a desk review of the design**, not observed results from a running application.

| Test ID | Design review result | Reason |
|---|---|---|
| TC-01 | Pass by design | Complete information can proceed through ticket creation, assignment, and resolution. |
| TC-02 | Pass by design | Missing details trigger a request for information while ownership remains clear. |
| TC-03 | Pass by design | Duplicate reports are linked rather than silently discarded. |
| TC-04 | Pass by design | The workflow blocks unauthorised changes and requires an authorised route. |
| TC-05 | Pass by design | The workflow does not claim success when ticket creation fails and provides a fallback. |

**Important limitation:** “Pass by design” means the proposed rules specify the desired behaviour. It does not mean that code was executed or that the live SIS was tested. If a prototype is later built, rerun these cases and replace the design-review results with actual test evidence.

## 4. What these tests reveal

- A ticket reference and owner should be created only after successful submission.
- Missing information needs an explicit state and a clear follow-up request.
- Duplicate handling should preserve the fact that multiple students may be affected.
- Ticket creation and ticket approval are different: a report does not grant permission to alter protected records.
- A failed form must have a safe fallback and must not create a false confirmation.
- A status history helps explain what happened, who acted, and why a ticket was reopened or escalated.

## 5. Evidence log entry

| Date | Evidence item | Classification | What it supports | Limitation |
|---|---|---|---|---|
| 24 Oct 2026 | TC-01 to TC-05 scenario review | Synthetic desk-test / design review | Shows how the proposed workflow is intended to respond to five required cases | No live SIS access, real student reports, executable prototype, or institutional procedure was tested |

## 6. Next step

Estimate the workflow's scale and net time saved. Keep the calculation transparent: distinguish assumptions from observed data and subtract any new triage, review, or support effort from the time saved. Do not describe illustrative numbers as measured ICFAI results.
