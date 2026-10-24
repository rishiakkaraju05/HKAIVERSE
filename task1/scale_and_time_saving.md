# Task 1 — Step 4: Problem Scale and Net Time-Saving Estimate

**Prepared:** 24 October 2026  
**Status:** Illustrative estimate for a proposed workflow; not measured ICFAI SIS data  
**Evidence basis:** User-described workflow and synthetic desk-tests; no internal ticket data or direct observations were available

## 1. Problem statement

In the workflow described for this investigation, a student reports an SIS problem to management, management reviews it, and the issue is passed to the relevant team for investigation or repair. If reports arrive with incomplete details, are routed more than once, or lack a clear owner and status update, the process may require extra clarification and follow-up. The proposed structured report and ticket workflow is intended to reduce that avoidable handling.

This is a plausible problem to investigate, not a confirmed finding about the frequency or performance of ICFAI's internal process. No actual SIS tickets, service logs, or staff timings were available for this assessment.

## 2. Estimating scale

The actual number of SIS issue reports per week or month is unknown. It would be misleading to present an invented number as ICFAI's real workload. For a transparent planning scenario, use **10 reports per month** as an illustrative input and replace it with an observed count if authorised aggregate data becomes available.

| Measure | Value used | Classification | Explanation |
|---|---:|---|---|
| Reports per month | 10 | Assumption for illustration | Not an observed ICFAI count |
| Reports requiring clarification or rerouting | 40% (4 reports) | Assumption for illustration | Used to estimate avoidable handling |
| Current handling time per report | 12 minutes | Assumption for illustration | Coordinator's total initial handling and follow-up time |
| Proposed coordinator time per report | 7 minutes | Assumption for illustration | Structured intake, triage, and routing |
| Extra review/support time per report | 2 minutes | Assumption for illustration | Time to review the proposed ticket and assist with exceptions |

These inputs are deliberately editable. The report count and timings should be measured from a small sample of reports before anyone claims that the redesigned workflow saves this amount of time.

## 3. Time-saving calculation

For this illustrative comparison:

- Current handling = reports per month × current handling minutes per report.
- Proposed handling = reports per month × (proposed coordinator minutes + extra review/support minutes per report).
- Net time saved = current handling − proposed handling.

Using the illustrative values above:

| Calculation | Formula | Result |
|---|---|---:|
| Current monthly handling | 10 × 12 minutes | 120 minutes |
| Proposed monthly handling, including review/support | 10 × (7 + 2) minutes | 90 minutes |
| **Net time saved per month** | 120 − 90 minutes | **30 minutes** |
| Net time saved per report | 30 ÷ 10 minutes | 3 minutes |
| Percentage reduction in handling time | (30 ÷ 120) × 100 | 25% |
| Illustrative annual net saving, if volume and timings remain constant | 30 × 12 minutes | 360 minutes (6 hours) |

**Interpretation:** Under these assumptions, the proposed workflow saves an estimated 3 minutes per report after accounting for 2 minutes of additional review/support. At 10 reports per month, that is 30 minutes monthly. These figures demonstrate the calculation method; they are not measured savings and should not be presented as actual ICFAI performance.

The estimate does not include time spent by the technical team diagnosing and fixing the underlying software problem, because the proposed intake process cannot be assumed to reduce the technical effort required to resolve a defect. It estimates only report-handling time.

## 4. Sensitivity check

The result depends on the time required by the proposed process, including review and support. Holding the illustrative workload at 10 reports per month and current handling at 12 minutes per report:

| Proposed coordinator + review/support time per report | Proposed monthly time | Net time saved per month |
|---:|---:|---:|
| 8 minutes | 80 minutes | 40 minutes |
| 9 minutes | 90 minutes | 30 minutes |
| 10 minutes | 100 minutes | 20 minutes |
| 12 minutes | 120 minutes | 0 minutes |
| 13 minutes | 130 minutes | −10 minutes (net increase) |

This check shows that the redesigned process is useful only if it reduces total handling effort. If extra triage or review consumes all the time saved, there is no net saving.

## 5. How to validate the estimate

If authorised aggregate information becomes available, collect a small sample without copying student identifiers or private report content:

1. Count reports received over a defined period.
2. Record handling time for each report, including clarification, routing, and follow-up.
3. Record how many reports needed clarification, rerouting, or duplicate handling.
4. Run the same set of synthetic cases through a prototype, if one is built, and time the workflow.
5. Include all new review/support time in the proposed-process total.
6. Compare like with like and state the sample size, period, and limitations.

A simple data table for later validation could use these columns: `period`, `report_count`, `current_minutes_total`, `proposed_minutes_total`, `extra_review_minutes`, `clarification_count`, `reroute_count`, and `duplicate_count`. Use aggregated or synthetic data only unless there is explicit permission and an approved privacy-safe process.

## 6. Evidence log

| Date | Item | Classification | Use | Limitation |
|---|---|---|---|---|
| 24 Oct 2026 | Workflow description supplied for this investigation | User-provided context | Establishes the broad report → management review → responsible team path | Does not verify the detailed internal process |
| 24 Oct 2026 | Structured ticket workflow and five synthetic test cases | Proposed design / desk-test | Defines the improvement being estimated | Not implemented or tested in the live SIS |
| 24 Oct 2026 | 10 reports/month; 12 current minutes; 7 proposed coordinator minutes; 2 review/support minutes | Explicit assumptions | Demonstrates transparent net-time calculation | Must be replaced by measured data for a real impact claim |

## 7. Conclusion

A structured intake form, clear ticket owner, duplicate linking, status tracking, and a safe fallback could reduce avoidable report-handling effort and make progress easier for students to follow. In the illustrative scenario, net handling time falls from 12 to 9 minutes per report after including review/support, saving 3 minutes per report. Actual scale and savings remain unverified; they should be measured with authorised aggregate data before the result is treated as an institutional finding.
