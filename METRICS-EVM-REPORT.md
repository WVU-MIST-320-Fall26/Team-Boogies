# Metrics & EVM Report: Sprint 2

**Project:** HEW Talent Analytics & Job Matching Platform  
**Team:** Team-Boogies  
**Project Sponsor:** Director, HEW University Career Services  
**Prepared by:** Sogol Chekani, Project Manager  
**Reporting Period:** Sprint 1 (Oct 12) through end of Sprint 2 (Nov 8, 2026)

---

## 1. Velocity & Burn-Up Performance Analysis

### Sprint Velocity

| Sprint | Dates | Points Committed | Points Completed (DoD Met) | Issues Completed | Say/Do Ratio |
|---|---|---|---|---|---|
| Sprint 1 | Oct 12 to Oct 25 | 31 | 31 | 6 | 100% |
| Sprint 2 | Oct 26 to Nov 8 | 31 | 31 | 6 | 100% |
| **Average Velocity** | | **31** | **31 SP / sprint** | **6** | **100%** |

Only work that met the Definition of Done (DoD) is counted as completed.

### Velocity Trend

- **Stable and predictable.** The team completed exactly what it committed to in both sprints. Velocity held flat at 31 story points (SP) per sprint, so the team's capacity planning is accurate.
- **Balanced workload.** Sprint 2 work was spread across all four team members after the Sprint 1 retrospective found that ownership wasn't visible when every issue sat on one account.
- **The problem is planned pace, not delivery reliability.** The baseline has 176 SP. Finishing in 3 sprints required a planned velocity of about 59 SP per sprint (176 ÷ 3). The team's actual velocity of 31 SP per sprint is about half of that.
- Velocity is used here only as an internal calibration metric to forecast this team's remaining work. It is not a measure for comparing teams.

### Burn-Up Chart

![Burn-up chart from GitHub Projects Insights](images/burnup-chart.png)

**Reading the chart:** A burn-up chart tracks two lines:

- **Total Scope line:** Stays flat at 176 SP. The CCB deferred the video interview request (Assignment 4), so no new scope entered the baseline. The deferred items (#40-#46) have no points and sit outside the baseline. A flat scope line shows that the schedule gap is not caused by scope creep.
- **Completed Work line:** Climbs in two even steps of 31 SP, on top of the 28 SP of planning work completed before Sprint 1. The steady slope confirms consistent throughput with no stalled sprints.

The 86 SP gap between the two lines at the end of Sprint 2 is the remaining release backlog.

| Point in Time | Completed (cumulative SP) | Total Scope (SP) | % Complete | Planned % Complete |
|---|---|---|---|---|
| Before Sprint 1 (planning) | 28 | 176 | 16% | N/A |
| End of Sprint 1 | 59 | 176 | 34% | 33% |
| End of Sprint 2 | 90 | 176 | 51% | 67% |

---

## 2. Earned Value Management (EVM) Calculations

### Baseline Parameters (Agile EVM)

| Parameter | Value |
|---|---|
| **Budget at Completion (BAC)** | 176 SP / $286,000 (from the project charter) |
| **Planned release length** | 3 sprints |
| **Target cost per story point** | $286,000 ÷ 176 SP = **$1,625 / SP** |
| **Planned Value basis** | 2 of 3 sprints complete → 2/3 of all story points |
| **Actual Cost basis** | 2/3 of the overall budget spent, as directed |
| **Earned Value basis** | Completed and accepted SP (DoD met) × $1,625 |

### Baseline Metrics Through Sprint 2

| Metric | Formula | Story Points | Dollars | Interpretation |
|---|---|---|---|---|
| **Planned Value (PV)** | 2/3 × BAC | 117.3 SP | $190,667 | Work planned to be done by now |
| **Earned Value (EV)** | Completed SP × $1,625 | 90 SP | $146,250 | Value of work actually done |
| **Actual Cost (AC)** | 2/3 × BAC | N/A | $190,667 | Money actually spent |
| **Schedule Variance (SV)** | EV - PV | -27.3 SP | -$44,417 | SV < 0 → **Behind schedule** |
| **Cost Variance (CV)** | EV - AC | N/A | -$44,417 | CV < 0 → **Over budget** |
| **Schedule Performance Index (SPI)** | EV ÷ PV | 90 ÷ 117.3 | **0.77** | SPI < 1.0 → **Behind schedule** |
| **Cost Performance Index (CPI)** | EV ÷ AC | N/A | **0.77** | CPI < 1.0 → **Cost inefficient** |

### What the Indexes Mean

- **SPI = 0.77:** The project is converting planned time into delivered work at 77% of the expected rate, about 23% behind schedule. It is 51% complete when the plan called for 67%.
- **CPI = 0.77:** For every $1.00 spent, the project has earned $0.77 of planned value.
- **Why SPI and CPI match:** AC and PV both equal 2/3 of the budget, so the schedule shortfall and the cost shortfall come from the same root cause. The baseline assumed a velocity of about 59 SP per sprint, but the team's proven velocity is 31 SP.

---

## 3. Sprint 3 Forecasting

### Cost Forecast

| Metric | Formula | Value | Interpretation |
|---|---|---|---|
| **Estimate at Completion (EAC)** | BAC ÷ CPI = $286,000 ÷ 0.767 | **$372,859** | Projected final cost if CPI holds constant |
| **Estimate to Complete (ETC)** | EAC - AC = $372,859 - $190,667 | **$182,192** | Money still needed to finish |
| **Variance at Completion (VAC)** | BAC - EAC | **-$86,859** | Projected deficit (30% over budget) |
| **Contingency Reserve** | From charter | $26,000 | Covers only 30% of the projected deficit |
| **To-Complete Performance Index (TCPI)** | (BAC - EV) ÷ (BAC - AC) = $139,750 ÷ $95,333 | **1.47** | Efficiency required to finish within BAC |

### Schedule Forecast (Velocity-Based)

| Scenario | Assumed Velocity | Remaining SP | Sprints Needed | Projected Finish |
|---|---|---|---|---|
| **Best case:** descope analytics and course recommendations (#30, #31, #32) | 31 SP | 65 | 2.1 | about Dec 20, 2026 |
| **Expected case:** current velocity holds | 31 SP | 86 | 2.8 | about Dec 20, 2026 |
| **Worst case:** holiday capacity loss | 25 SP | 86 | 3.4 | about Jan 3, 2027 |

The baseline has all work finishing in Sprint 3 (Nov 9 to Nov 22), with pilot launch and closeout by **Dec 9, 2026**. Every scenario misses that date, so a scope reduction and/or re-baseline is required.

### Forecast Interpretation

- **Cost:** If current efficiency continues, the project will cost about **$372,859**, which is **$86,859 over budget** and well beyond the $26,000 contingency reserve.
- **TCPI reality check:** A TCPI of **1.47** means the team would have to perform 47% more efficiently on all remaining work than it has so far (CPI 0.77). Any TCPI above 1.20 makes finishing within the original budget virtually impossible without cutting scope. This is the mathematical basis for asking the sponsor for a revised baseline.
- **Schedule:** Sprint 3 holds 86 SP, nearly 3 times the team's proven velocity.

### Recommended Corrective Actions

1. **Reduce scope, not quality.** Do not skip testing or weaken the Definition of Done to hit the date. A defect fixed in design costs about $1; in QA, $10; after release, $100 or more (the 1-10-100 rule). UAT (#10) and the DoD stay in place.
2. **Prioritize the core pilot path.** Commit Sprint 3 first to job matches (#27, #39), employer review (#24, #25), skill gaps (#29), UAT (#10), and launch (#11).
3. **Submit a change request to re-baseline.** Ask the CCB to either move analytics (#31, #32) and course recommendations (#30) to a post-pilot phase or approve a revised cost and schedule baseline.
4. **Weigh schedule compression carefully.**
   - *Crashing* (adding people) raises cost and adds communication overhead late in a project (Brooks' Law).
   - *Fast-tracking* (running UAT in parallel with the final build) risks rework.
   - Scope reduction is the lower-risk option.
5. **Plan by capacity.** Apply each member's resource calendar for Thanksgiving week and finals when committing Sprint 3 work, rather than over-allocating the team.
6. **Check in at mid-sprint.** Review the burn-up on Nov 15. If fewer than 15 SP are complete (half of a normal sprint), escalate to the Project Sponsor.
7. **Protect scope.** Keep the deferred video interview features (#40-#46) in the backlog, and route all new requests through the CCB.
