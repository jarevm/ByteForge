# Team Charter: Team ByteForge

> **NOTE: Charter is subject to change/revision and is currently in the drafting stage.** Once our team has chosen a topic the charter will be updated accordingly.

**Course:** CCSFEN1L Software Engineering · 2nd Term, A.Y. 2026-2027

**Version:** 1.1, revised at the Week 6 checkpoint (first signed in Week 1)

## 1. Purpose

(Project purpose will be added once topic is chosen)

## 2. Roles

Everyone codes and everyone writes. The role names who is accountable for an area, not who does all the work in it.

| Role | Member | Backup | Accountable for |
| --- | --- | --- | --- |
| Project lead (Scrum Master) | Cabrera, Edrei Ansel N. | Nepomuceno, Julliana P. | Sprints, backlog, stand-ups, risk log, timeline, Gantt chart, submissions |
| Technical lead (architect) | Madanglog, John Rev D. | Nepomuceno, Julliana P. | Architecture, repository standards, code review, methodology section |
| Research lead | Nepomuceno, Julliana P. | Cabrera, Edrei Ansel N. | Requirements, user stories, review of related literature, IEEE references |
| QA and data lead | Madanglog, John Rev D. | Cabrera, Edrei Ansel N. | Testing, CI pipeline, data handling and consent forms, evaluation design |

## 3. Working norms and communication plan

**Meetings**

| What | When | Where |
| --- | --- | --- |
| Team meeting | Tuesdays, 4:00 to 5:00 p.m. | Campus or Google Meet |
| Sprint planning, review, and retrospective | Every other Tuesday, as part of the team meeting | Same |
| Stand-up with the instructor | Weekly, 5 minutes, during the lab | Lab room |
| Written check-in (done / next / blocked) | Monday, Wednesday, and Friday by 9:00 p.m. | `#standup` channel |

**Channels**

| Channel | Used for | Our rule |
| --- | --- | --- |
| Team chat (Discord) | Quick questions, check-ins, scheduling | Reply within 12 hours on weekdays, 24 hours on weekends |
| GitHub Issues and Projects | Every task, bug, and user story | Assignee updates status at least twice a week |
| Pull request reviews | Code and documentation review | First review within 24 hours |
| Overleaf / VS code | Proposal chapters (LaTeX, IEEE template) | Each chapter has one owner; others comment instead of rewriting |
| Zotero group library | All references | Add a source the day you cite it |
| Restricted Google Drive folder | Consent forms and raw field photos | Shared only with the team and the instructor |

- Quiet hours are 10:00 p.m. to 7:00 a.m. Nobody is expected to reply then.
- Tell the team at least 24 hours before missing a meeting or a task deadline. Your backup takes over if needed.
- Raw photos with farmer details, consent forms, and API keys never go into the repository.

## 4. Decision-making

- **Default:** consensus. If there is none after 10 minutes, the accountable role decides after hearing everyone.
- **Whole-team decisions:** the thesis topic, changes to scope or objectives, and anything sent to the panel. These need consensus, or 3 of 4 votes if consensus fails.
- **Technical decisions:** the technical lead records them as architecture decision records in `docs/adr/`.
- **Decision log:** every decision goes in `docs/decisions.md` with the date and who decided.

## 5. Conflict process

We discuss issues, not people, and assume good intent until shown otherwise.

1. **Talk privately** with the person within 48 hours of noticing the problem.
2. **Raise it at the next team meeting** if it is not resolved. The project lead facilitates. If the project lead is involved, the research lead facilitates. Agreed actions go in the decision log.
3. **Ask the instructor to mediate** if it is still unresolved after one week. Do the same if a member misses two assigned tasks in one sprint without notice. Bring the sprint board and the commit history.
4. **Accept the instructor's decision.** Contributions are also reflected in the peer evaluations in Weeks 6 and 11.

## 6. Quality standards

**Definition of Done** (for every story):

- Code is merged into `main` through a reviewed pull request.
- Automated tests pass, and new code has tests.
- The story's acceptance criteria are met and demonstrated.
- Documentation (README, comments, or the proposal section) is updated.
- No known high-severity defects remain open for the story.

**For proposal writing:**

- Every cited source is in Zotero, in IEEE style, and was read by at least one member.
- AI-generated citations are never used unverified. AI tool use is disclosed in the appendix.
- Each chapter is reviewed by one member other than its author before submission.

## 7. Contribution tracking

- Every task is a GitHub issue with one assignee and an estimate, tracked on the Projects board.
- Commits and pull requests reference their issue, for example `Closes #23`.
- Each member reviews at least one pull request per week.
- Each lab's `REPORT.md` lists who did what.
- Peer evaluations in Weeks 6 and 11 are read together with the board and Git history.

## Revision log

| Version | When | Change |
| --- | --- | --- |
| 1.0 | Week 1 | First charter. Purpose: choose a thesis topic from the lab paradigms by Week 4. |
| 1.1 | Week 6 | --- |

## Agreement

We have read this charter and agree to follow it. We will revisit it at the Week 6 checkpoint and after any serious disagreement.

| Member | Signed (typed) | Date |
| --- | --- | --- |
| Cabrera, Edrei Ansel N. | Cabrera, Edrei Ansel N. | Week 1 |
| Madanglog, John Rev D. | Madanglog, John Rev D. | Week 1 |
| Nepomuceno, Julliana P. | Nepomuceno, Julliana P. | Week 1 |