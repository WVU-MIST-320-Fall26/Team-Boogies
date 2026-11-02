# Risk Register

**Project Name:** HEW Talent Analytics & Job Matching Platform  
**Project Manager:** Sogol Chekani  
**Date Created:** 2026-11-02  
**Last Updated:** 2026-11-02

**Scoring:** Probability (1-3) × Impact (1-3) = Risk Score. Critical (7-9), High (5-6), Medium (3-4), Low (1-2).

## Risk Register Table

| ID | Risk Description | Category | Probability (1-3) | Impact (1-3) | Risk Score | Response Strategy | Mitigation Plan | Owner | Status | Last Update |
|----|-----------------|----------|-------------------|--------------|------------|-------------------|-----------------|-------|--------|------------|
| R-01 | Resume parsing extracts skills inaccurately because students upload resumes in many different formats, which lowers the quality of all downstream matching | Technical | 3 (High) | 3 (High) | 9 | Mitigate | Test the parser on a sample of 50 real resume formats; Normalize skills to a standard skill list (#38); Let students review and correct extracted skills | Scrum Master (Bushra Nureldin) | Active | 2026-11-02 |
| R-02 | University IT is slow to grant access to the student records system (SIS) and SSO, which blocks course record imports and login | Technical | 2 (Medium) | 3 (High) | 6 | Mitigate | Submit access requests early; Build against mock SIS data until access is granted; Escalate to the Project Sponsor if there is no response within 5 business days | Systems Architect (Evangeline Johnson) | Active | 2026-11-02 |
| R-03 | FERPA compliance review finds gaps in how student data is shared with employers, requiring rework before the pilot | External | 2 (Medium) | 3 (High) | 6 | Mitigate | Complete the FERPA review in Sprint 2 (#34); Keep student opt-in consent (#33) mandatory before profiles are visible; Involve the Compliance Office in design reviews | Project Manager (Sogol Chekani) | Active | 2026-11-02 |
| R-04 | The first version of the match score does not reach the 75% employer-rated relevance target | Quality | 2 (Medium) | 3 (High) | 6 | Mitigate | Release a simple skill-overlap score first (#26); Collect employer feedback early; Tune weights in Sprint 3 (#39) | Systems Architect (Evangeline Johnson) | Active | 2026-11-02 |
| R-05 | Stakeholder scope changes after the CCB review add work to Sprint 3 and threaten the December 9 completion date | Scope | 2 (Medium) | 3 (High) | 6 | Control | Route every new request through the change-request label and CCB; Re-estimate story points before accepting work; Move lower-priority items out of Sprint 3 if needed | Project Manager (Sogol Chekani) | Active | 2026-11-02 |
| R-06 | Team availability drops during Thanksgiving week and finals, shortening Sprint 3 | Resource | 3 (High) | 2 (Medium) | 6 | Mitigate | Plan Sprint 3 at reduced capacity; Front-load high-priority work; Use asynchronous stand-ups; Cross-train so no issue depends on one person | Scrum Master (Bushra Nureldin) | Active | 2026-11-02 |
| R-07 | The team has no dedicated QA role, so defects may not be caught until user acceptance testing | Quality | 2 (Medium) | 2 (Medium) | 4 | Mitigate | Add a QA column to the board with a WIP limit; Require a teammate other than the developer to verify the Definition of Done before moving to Done | Lead Business Analyst (Gabriel Speranza) | Active | 2026-11-02 |
| R-08 | Too few employer partners post jobs or review candidates during the pilot, limiting match data and feedback | Stakeholder | 2 (Medium) | 2 (Medium) | 4 | Mitigate | Confirm the 10 pilot employers with Career Services before launch; Provide training materials (#35); Schedule check-ins with each partner | Lead Business Analyst (Gabriel Speranza) | Watchlist | 2026-11-02 |
| R-09 | Cloud hosting and database costs exceed the $25,000 budget as data volume grows | Financial | 1 (Low) | 2 (Medium) | 2 | Accept | Monitor monthly cloud spend; Use the 10% contingency reserve if needed | Project Manager (Sogol Chekani) | Watchlist | 2026-11-02 |
