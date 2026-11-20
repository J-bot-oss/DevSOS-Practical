# DevSOS Project Schedule

The editable schedule is kept locally in `docs/local/DevSOS_Project_Schedule.xlsx`. It contains Project Schedule, Gantt Chart, Milestones and Progress Tracking sheets. The approved Markdown and Word WBS versions were compared before scheduling: all 18 work packages and their descriptions, outputs and completion criteria match.

## Baseline

- Project period: **18 November to 1 December 2026**, inclusive, 14 calendar days.
- Scope: three static website pages and four troubleshooting guides covering Git, Python and Node.js.
- Budget remains provisional at UGX 50,000, including UGX 15,000 contingency.
- All 18 WBS work packages are included with the approved codes and names.
- Baseline dates are fixed inputs. Linked dates recalculate from editable durations, predecessor IDs, dependency types and lags. Actual dates do not overwrite the baseline.

## Milestones

| Milestone | Baseline date |
| --- | --- |
| Project initiation | 18 November 2026 |
| Requirements gathering | 19 November 2026 |
| Project planning baseline | 21 November 2026 |
| Website design | 22 November 2026 |
| Development / implementation complete | 27 November 2026 |
| Testing and corrections complete | 29 November 2026 |
| User acceptance review | 30 November 2026 |
| Website demonstration/deployment | 1 December 2026 |
| Project closure and handover | 1 December 2026 |

The website-design milestone comes from the charter deliverables table. The acceptance review is planned for 30 November; the WBS allows feedback and the acceptance decision to be completed by 1 December. Unavailable participants or an outstanding decision remain incomplete work.

## Dependencies and parallel work

FS means finish-to-start, with the successor beginning the next calendar day at zero lag. SS means start-to-start. FF means finish-to-finish. Lags are calendar days.

Requirements lead to the planning baseline, then design. Home follows the page design; About & Resources follows Home. The four guides are drafted and checked in sequence from 23 to 26 November. The guides page runs from 23 to 27 November, overlapping content work; its FF dependency on the fourth guide includes one day for final integration. Testing starts after the completed guides page and About & Resources page. Stakeholder review follows testing and the early stakeholder arrangements. Handover follows review and repository preparation; closure runs alongside handover on 1 December.

Monitoring and repository maintenance run alongside delivery from 18 to 30 November. Calendar durations are elapsed time, not full days of exclusive effort. The proposed effort allowance is 61.75 hours, spread across baseline intervals for an indicative daily workload. Peak estimated workload is 6.35 hours per day. These are planning estimates, not recorded work or a guaranteed resource allocation.

## Progress and evidence

Progress reports are scheduled for **24 November 2026** and **30 November 2026**. These dates are proposed planning choices because the charter leaves the two dates to the detailed schedule. The report templates include package-level planned and actual progress, evidence, issues and corrective actions. Actual report dates and results are blank.

Planned progress uses estimated effort hours and elapsed baseline days; it is a planning approximation, not earned value or proof of completion. Overall actual report progress is calculated only when all 18 package percentages and evidence references have been entered. Progress variance is actual minus planned, in percentage points.

Actual starts, finishes, percentages, milestone completions, evidence, issues and corrective actions are blank. Current schedule statuses use a fixed reporting date of **19 November 2026**, which can be updated. A blank actual field means no result has been recorded. Finish variance is actual finish minus baseline finish; a positive value means late. The Gantt uses one row per work package, grouped under the seven main deliverables. Blue bars show the baseline; green overlays show recorded progress only when an actual start, percentage and evidence are present. Progress is converted to whole calendar-day equivalents, rounded up, and capped at the actual finish or reporting date. It is an approximation rather than a daily work record. Blue outlines retain the baseline span. Purple diamonds show baseline milestones and green circles show evidenced actual milestone dates; the actual marker replaces the baseline marker when both dates coincide. Activity beyond the 14-day timeline remains visible in dates and variances even though the chart ends on 1 December.

## Decisions still to confirm

- Select the four specific guide topics during requirements gathering.
- Confirm the representative and at least two volunteer learners, their consent and review availability.
- Confirm whether the demonstration will be local or use free static hosting.
- Review the proposed effort estimates and the two report dates against actual availability.
- Preserve original dates if work is delayed; record actuals and follow-up actions rather than moving the baseline.

Sources: approved `docs/WBS.md`, matching local Word WBS, and Project Charter draft version 0.1 dated 18 November 2026. No development, testing, feedback or acceptance is claimed by this schedule.
