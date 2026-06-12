# Work Allocation Report — [Team 17]

> **Instructions:** Complete this document as a team before or alongside your final submission.
> Submit one copy per team via EEClass. This document is shared with all markers.
> Be specific — vague entries ("we all helped") will prevent individual contribution adjustments from being applied in your favour.

---

## 1. Team Members

| Full Name | Student ID | GitHub Username | Email |
|-----------|-----------|----------------|-------|
| 張藝齡| 113403013| Oeo941014|zhangyiling062@gmail.com|
| 薛閔云| 113403528| cammie20060621| |
| 松怡琳| 113403535| 1lin0| so0130366@gmail.com|

---

## 2. Task Ownership

For each task, name the **primary owner** (the person most responsible for delivering it)
and any **supporting members** (who assisted but were not the lead). Leave the Notes column
for anything that deviates from the standard expectation (e.g., task was pair-programmed,
or reassigned mid-project).

### Code Repository

| Task | Primary Owner | Supporting Member(s) | Notes |
|------|--------------|---------------------|-------|
| **Task 1** — Relational schema design (`schema.sql`) | 薛閔云| | |
| **Task 2a** — Core availability & fare queries (`query_national_rail_availability`, `query_metro_schedules`, `query_national_rail_fare`, `query_metro_fare`) | 薛閔云| | |
| **Task 2b** — Seat & user queries (`query_available_seats`, `query_user_profile`, `query_user_bookings`, `query_payment_info`) | 薛閔云| | |
| **Task 2c** — Write operations (`execute_booking`, `execute_cancellation`) | 薛閔云| | |
| **Task 2d** — Authentication queries (`login_user`, `register_user`, `get_user_secret_question`, `verify_secret_answer`, `update_password`) | 薛閔云| | |
| **Task 3** — PostgreSQL seeding (`seed_postgres.py`) | 松怡琳| | |
| **Task 4** — Neo4j graph design & seeding (`seed_neo4j.py`, `seed.cypher`) | 張藝齡| | |
| **Task 5** — Neo4j query functions (`graph/queries.py`) | 張藝齡| | |
| **Task 6** *(if attempted)* — Optional extension create | | | |

### Design Document

| Section | Primary Author | Supporting Member(s) | Notes |
|---------|--------------|---------------------|-------|
| Section 1 — ER Diagram | 松怡琳| | |
| Section 2 — Normalisation Justification | 松怡琳| | |
| Section 3 — Graph Database Design Rationale | 張藝齡| | |
| Section 4 — Vector / RAG Design | 張藝齡| | |
| Section 5 — AI Tool Usage Evidence | 薛閔云| | |
| Section 6 — Reflection & Trade-offs | 薛閔云| | |
| Section 7 — Optional Extension *(if applicable)* | | | |

---

## 3. Estimated Contribution Percentages

Based on the task allocation above, what percentage of total team effort do you estimate each member contributed?
All members must sum to 100%.

| Member | Estimated % | Brief justification |
|--------|-----------|---------------------|
| 張藝齡| 30% | Led Neo4j graph database design, seeding, and query functions (Tasks 4–5), plus authored design document Sections 3 and 4. (~11 commits, +2376/−988 lines)|
| 薛閔云| 45% | Responsible for relational schema design and the majority of SQL query implementation across Tasks 1 and 2a–2d, representing the largest codebase contribution. (~18 commits, +4707/−1024 lines)|
| 松怡琳| 25% | Implemented PostgreSQL seeding script (Task 3) and authored design document Sections 1 and 2. (~20 commits, +1787/−683 lines)|
| **Total** | **100%** | |

---

## 4. Mid-Project Changes

If any tasks were reassigned or the original plan changed significantly, document it here.
If nothing changed, write "No changes."

| Change | Original plan | Revised plan | Reason |
|--------|--------------|-------------|--------|
| no change| | | |

---

## 5. Team Declaration

We confirm that this work allocation accurately reflects how responsibilities were divided within our team.

| Name | Signature / Typed name | Date |
|------|----------------------|------|
| 張藝齡| 張藝齡| 2026/06/12|
| 薛閔云| | |
| 松怡琳| 松怡琳| 2026/06/12|
