# Product Backlog and Sprint Plans
 
**Module:** UFCFTR-30-3 Distributed and Enterprise Software Development (Task 1)
**Case study:** Bristol Regional Food Network - Digital Marketplace
**Chosen use case:** Use Case 1 - Producer Product Listing and Inventory Management
 
> Exported from the group's Notion board on 19/11/2026. Notion remains the working copy; update this file when the backlog changes.
 
## Sprint plans
 
### Sprint 1 plan
 
Goal: Strategic BPMN, identified and scoped functionalities, a product backlog and an active repo.
 
| Week | Focus |
|---|---|
| 1 | Stakeholder analysis, set out roles for the current sprint, created the GitHub repo and Notion board |
| 2 | Analysis of the case study and use cases (mostly assessment analysis) |
| 3 | Went through each use case and decided, completed the strategic BPMN, identified the scope of the 2 major functionalities, and analysed major business processes and organisational responsibilities |
 
### Sprint 2 plan (29 Oct - 19 Nov 2026)
 
Goal: Complete the i\* SD and SR models with two detailed operational BPMN models for both agreed major functionalities, with clear traceability between BPMN models and i\*. Complete an initial executable Camunda process with Camunda user tasks and forms.
 
| Week | Dates | Focus |
|---|---|---|
| 1 | 29 Oct - 5 Nov | Confirm the two functionalities with the module team, finish the strategic BPMN, and complete the i\* models |
| 2 | 5 Nov - 12 Nov | Complete the 2 detailed BPMN models and the traceability table; start the Camunda build in parallel (forms, initial service task implementation where appropriate: validation service task, mock certification service) |
| 3 | 12 Nov - 19 Nov | Complete the executable Camunda process (gateways, process variables, business logic), run a consistency check across i\*, strategic BPMN, operational BPMN and Camunda, check repo history and rehearse the demo |
 
**Throughout:** commit and push work regularly so GitHub shows continued iterative development from every member.
 
**Sprint review:** 19 Nov
 
### Sprint 3 plan (19 Nov - 10 Dec 2026)
 
Goal: Both major functionalities (A: product listing, validation and publication; B: inventory and seasonal availability) run end to end in Camunda with forms, service tasks, process variables, business decisions and exception paths. The components are integrated, the i\*, strategic BPMN, operational BPMN and implementation are consistent, legal, ethical, social and professional (LESP) considerations are evaluated, and the repo is complete and ready for Task 2.
 
| Week | Dates | Focus |
|---|---|---|
| 1 | 19 Nov - 26 Nov | Act on Sprint 2 feedback and fix any model inconsistencies; build the certification check with retry and service-unavailable path, the administrator manual review fallback, the publish step and the DMN availability decision |
| 2 | 26 Nov - 3 Dec | Build zero-stock, restock and seasonal-end timer logic; integrate Functionality A and B and document process variables and data flow; polish the Camunda Forms; update the i\* and BPMN models to match the implementation; start the LESP evaluation. Feature freeze at the end of the week |
| 3 | 3 Dec - 10 Dec | No new features. End-to-end testing of both processes including failure paths, bug fixes, finish the LESP evaluation with UWE Harvard references, README and run instructions, Task 2 readiness, AI-use log, signed Contribution Matrix, repo audit, and demo rehearsal with Q&A preparation for every member |
 
**Sprint review:** 10 Dec (final submission before 14:00)
 
## Product backlog
 
Priority: High / Medium / Low. Status: `[x]` done, `[ ]` open. The Sprint column matches the Sprint column on the Notion board. "All members" means Eddie Main, Lonique Mayoua, Htet Oo Wai, Samuel St Clair and Shivam Puri.
 
| ID | Item | Priority | Sprint | Owner(s) | Status |
|---|---|---|---|---|---|
| 1 | Create GitHub repo + Notion | Medium | 1 | Eddie Main | [x] |
| 2 | Set up Notion structure | Medium | 1 | Eddie Main | [x] |
| 3 | Stakeholder analysis | Medium | 1 | All members | [x] |
| 4 | Requirements set out | Medium | 1 | Eddie Main, Shivam Puri | [x] |
| 5 | Use cases analysis | High | 1 | All members | [x] |
| 6 | Pick use case | High | 1 | All members | [x] |
| 7 | Strategic BPMN model created covering Use Case 1 | High | 1 | Lonique Mayoua | [x] |
| 8 | Analysis of major business processes and organisational responsibilities | High | 1 | Htet Oo Wai, Samuel St Clair | [x] |
| 9 | Identification and scoping of the two candidate major functionalities | High | 1 | Shivam Puri, Eddie Main | [x] |
| 11 | Initial backlog and sprint plan | Medium | 1 | Eddie Main | [x] |
| 12 | Initial i\* model creation | High | 2 | Eddie Main, Shivam Puri, Samuel St Clair | [x] |
| 13 | Complete 2 detailed BPMN models | High | 2 | Htet Oo Wai, Lonique Mayoua | [ ] |
| 14 | Complete executable Camunda process | High | 2-3 | Lonique Mayoua, Htet Oo Wai, Eddie Main | [ ] |
| 15 | i\* Strategic Dependency (SD) model | High | 2 | Shivam Puri | [x] |
| 16 | i\* Strategic Rationale (SR) model | High | 2 | Eddie Main | [x] |
| 17 | Operational BPMN: Functionality A - product listing, validation and publication | High | 2 | Lonique Mayoua, Htet Oo Wai, Samuel St Clair | [ ] |
| 18 | Operational BPMN: Functionality B - inventory and seasonal availability | High | 2 | Htet Oo Wai, Lonique Mayoua, Samuel St Clair | [ ] |
| 19 | Traceability table: i\* to strategic BPMN to operational BPMN | High | 2 | Htet Oo Wai | [ ] |
| 20 | Camunda Forms: product submission form and stock/availability update form | High | 2 | Eddie Main, Shivam Puri | [ ] |
| 21 | Validation service task (mandatory fields, price, dates) | High | 2 | Shivam Puri, Htet Oo Wai | [ ] |
| 22 | Mock organic certification service with a switch to simulate failure | High | 2 | Shivam Puri | [ ] |
| 23 | Certification check service task with retry and service-unavailable path | Medium | 3 | Htet Oo Wai | [ ] |
| 24 | Administrator manual review fallback user task | Medium | 3 | Lonique Mayoua | [ ] |
| 25 | DMN decision table for product availability (stock and season dates) | High | 3 | Unassigned | [ ] |
| 26 | Zero-stock auto-unavailable, restock re-availability and seasonal end timer | Medium | 3 | Unassigned | [ ] |
| 27 | End-to-end testing of both processes including failure paths | High | 3 | Eddie Main | [ ] |
| 28 | Legal, ethical, social and professional (LESP) evaluation with UWE Harvard references | High | 3 | Unassigned | [ ] |
| 29 | Keep Contribution Matrix up to date | High | 1-3 | Unassigned | [ ] |
| 30 | Log any AI use on code and be able to explain the logic | Medium | 1-3 | All members | [ ] |
| 31 | Weekly stand-up preparation (done, next, blockers, evidence) | Medium | 1-3 | Unassigned | [ ] |
| 32 | Sprint 3 plan | Medium | 3 | Eddie Main | [x] |
| 33 | Demo rehearsal and Q&A preparation for every member | High | 3 | All members | [ ] |
| 34 | Task 2 integration readiness (structure, README, run instructions) | Low | 3 | Shivam Puri | [ ] |
 
Item 10 does not appear because it was removed from the Notion board.
 