# Feature status — Pet care & veterinary operations

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 192 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 1 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 0 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 2 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 1 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 1 | 0 | Native records/view |
| Reports & analytics | report | 2 | 0 | Native records/view |
| Activity & audit trail | audit | 0 | 0 | Native records/view |
| Provider connections | integration | 0 | 0 | Provider request records only |
| Pet Journey | records | 1 | 0 | Native records/view |
| Travel Pet | records | 1 | 0 | Native records/view |
| Veterinary Visit | records | 1 | 0 | Native records/view |
| Pet Vaccination | records | 1 | 0 | Native records/view |
| Pet Lab Result | records | 1 | 0 | Native records/view |
| Destination Rule | records | 1 | 0 | Native records/view |
| Health Certificate | records | 1 | 0 | Native records/view |
| Airline Booking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Border Handoff | records | 1 | 0 | Native records/view |
| Operational Task | records | 1 | 0 | Native records/view |
| Rule Version | records | 1 | 0 | Native records/view |
| Document Requirement | records | 1 | 0 | Native records/view |
| Destination checklist draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vaccination date reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Veterinary packet summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Airline document checklist | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Certificate inconsistency review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Owner preparation instructions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Evidence completeness review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Operations handoff draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Animals | records | 1 | 0 | Native records/view |
| Kennels | records | 1 | 0 | Native records/view |
| Medical Records | records | 2 | 0 | Native records/view |
| Behavioral | records | 1 | 0 | Native records/view |
| Medications | records | 3 | 0 | Native records/view |
| Quarantine | records | 1 | 0 | Native records/view |
| Applications | records | 1 | 0 | Native records/view |
| Contracts | records | 1 | 0 | Native records/view |
| Foster Homes | records | 1 | 0 | Native records/view |
| Volunteers | records | 1 | 0 | Native records/view |
| Donations | records | 1 | 0 | Native records/view |
| Inventory | records | 2 | 0 | Native records/view |
| Lost & Found | records | 1 | 0 | Native records/view |
| Stray Holds | records | 1 | 0 | Native records/view |
| Foster capacity balancer | records | 1 | 0 | Native records/view |
| My Pets | records | 1 | 0 | Native records/view |
| Health Records | records | 1 | 0 | Native records/view |
| Vaccinations | records | 2 | 0 | Native records/view |
| Appointments | records | 3 | 0 | Native records/view |
| Symptoms | records | 2 | 0 | Native records/view |
| Allergies | records | 2 | 0 | Native records/view |
| Dental Care | records | 1 | 0 | Native records/view |
| Lab Results | records | 2 | 0 | Native records/view |
| Parasite Prevention | records | 1 | 0 | Native records/view |
| Behavior | records | 2 | 0 | Native records/view |
| Nutrition | records | 2 | 0 | Native records/view |
| Feeding | records | 2 | 0 | Native records/view |
| Weight | records | 2 | 0 | Native records/view |
| Activities | records | 2 | 0 | Native records/view |
| Sleep | records | 2 | 0 | Native records/view |
| Grooming | records | 2 | 0 | Native records/view |
| Training | records | 2 | 0 | Native records/view |
| Socialization | records | 2 | 0 | Native records/view |
| Symptom Checker | records | 2 | 0 | Native records/view |
| Diet Advisor | records | 2 | 0 | Native records/view |
| Behavior Analysis | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Health Report | records | 2 | 0 | Native records/view |
| Emergency AI | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Insurance Advisor | records | 4 | 0 | Native records/view |
| Find Specialists | records | 1 | 0 | Native records/view |
| Vaccination Schedule | records | 1 | 0 | Native records/view |
| Genetic Disease Risk | records | 1 | 0 | Native records/view |
| Health Trend Detect | records | 1 | 0 | Native records/view |
| Expenses | records | 2 | 0 | Native records/view |
| Supplies | records | 2 | 0 | Native records/view |
| Milestones | records | 2 | 0 | Native records/view |
| Travel & Boarding | records | 1 | 0 | Native records/view |
| Report History | records | 2 | 0 | Native records/view |
| Emergency Contacts | records | 1 | 0 | Native records/view |
| Backlog tools | records | 1 | 0 | Native records/view |
| agentic wellness monitoring | records | 1 | 0 | Native records/view |
| photo based health screening | records | 1 | 0 | Native records/view |
| emergency decision support | records | 1 | 0 | Native records/view |
| breed age specific care automation | records | 1 | 0 | Native records/view |
| veterinary cost negotiation | records | 1 | 0 | Native records/view |
| pets without genetic | records | 1 | 0 | Native records/view |
| medical history without health | records | 1 | 0 | Native records/view |
| backend collapses everything into crud js | records | 1 | 0 | Native records/view |
| veterinary clinic integration medical records i | integration | 1 | 0 | Provider request records only |
| pharmacy integration medication refills cost tr | integration | 1 | 0 | Provider request records only |
| breed database breed | records | 1 | 0 | Native records/view |
| limited community features peer support experience | records | 1 | 0 | Native records/view |
| notifications module grep 0 | records | 1 | 0 | Native records/view |
| webhooks for clinic events | integration | 1 | 0 | Provider request records only |
| Patients | records | 1 | 0 | Native records/view |
| AI Diagnostics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Diagnostic Assistant | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Treatment Recs | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Aftercare | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Wellness Reminders | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Diagnostic assistant providing differential diagno... | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Treatment recommendation suggesting evidence-based... | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Aftercare generator producing discharge instructio... | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Outbreak detection flagging potential disease outb... | records | 1 | 0 | Native records/view |
| Wellness reminder automation by species/age | records | 1 | 0 | Native records/view |
| Boarding/grooming module add-on for multi-service... | records | 1 | 0 | Native records/view |
| No diagnostic assistance AI | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| No treatment recommendation AI | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| No discharge/aftercare-instruction generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| No imaging analysis (x-ray, ultrasound) | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Limited pharmacy system integration (only stub mod... | integration | 1 | 0 | Provider request records only |
| No lab result direct integration (IDEXX, Antech) | integration | 1 | 0 | Provider request records only |
| No pet-owner self-service portal | records | 1 | 0 | Native records/view |
| No multi-clinic / hospital group support | records | 1 | 0 | Native records/view |
| No webhooks for appointment events | integration | 1 | 0 | Provider request records only |
| No notifications subsystem (despite SMS/email bein... | records | 1 | 0 | Native records/view |
| Outbreak detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lab result interpret | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pharmacy interaction check | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Owner self service faq | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Multi clinic summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pet | records | 1 | 0 | Native records/view |
| Breed | records | 1 | 0 | Native records/view |
| Vaccination record | records | 1 | 0 | Native records/view |
| Behavioral note | records | 1 | 0 | Native records/view |
| Pet photo | records | 1 | 0 | Native records/view |
| Grooming preference | records | 1 | 0 | Native records/view |
| Grooming session | records | 1 | 0 | Native records/view |
| Appointment | records | 1 | 0 | Native records/view |
| Appointment service | records | 1 | 0 | Native records/view |
| Service | records | 1 | 0 | Native records/view |
| Breed service | records | 1 | 0 | Native records/view |
| Service package | records | 1 | 0 | Native records/view |
| Package service | records | 1 | 0 | Native records/view |
| Special handling fee | records | 1 | 0 | Native records/view |
| Transaction | records | 1 | 0 | Native records/view |
| Transaction item | records | 1 | 0 | Native records/view |
| Product | records | 1 | 0 | Native records/view |
| Gift card | records | 1 | 0 | Native records/view |
| Health alert | records | 1 | 0 | Native records/view |
| Incident | records | 1 | 0 | Native records/view |
| Emergency contact | records | 1 | 0 | Native records/view |
| Breed prediction | records | 1 | 0 | Native records/view |
| Style suggestion | records | 1 | 0 | Native records/view |
| Social post | records | 1 | 0 | Native records/view |
| Business settings | records | 1 | 0 | Native records/view |
| Reminder history | records | 1 | 0 | Native records/view |
| Medical record | records | 1 | 0 | Native records/view |
| Prescription | records | 1 | 0 | Native records/view |
| Lab result | records | 1 | 0 | Native records/view |
| Surgery | records | 1 | 0 | Native records/view |
| Usage log | records | 1 | 0 | Native records/view |
| Tenant aisettings | records | 1 | 0 | Native records/view |
| Pre visit intake | records | 1 | 0 | Native records/view |
| No show prediction | records | 1 | 0 | Native records/view |
| Style preview | records | 1 | 0 | Native records/view |
| Family group | records | 1 | 0 | Native records/view |
| Family member | records | 1 | 0 | Native records/view |
| Bundle suggestion | records | 1 | 0 | Native records/view |
| Vaccine reminder job | records | 1 | 0 | Native records/view |
| Technician profile | records | 1 | 0 | Native records/view |
| Technician skill | records | 1 | 0 | Native records/view |
| Technician availability | records | 1 | 0 | Native records/view |
| Technician service area | records | 1 | 0 | Native records/view |
| Service inventory requirement | records | 1 | 0 | Native records/view |
| Grooming quote | records | 1 | 0 | Native records/view |
| Grooming quote line | records | 1 | 0 | Native records/view |
| Grooming order | records | 1 | 0 | Native records/view |
| Dispatch assignment | records | 1 | 0 | Native records/view |
| Change order | records | 1 | 0 | Native records/view |
| Change order line | records | 1 | 0 | Native records/view |
| Inventory reservation | records | 1 | 0 | Native records/view |
| Inventory movement | records | 1 | 0 | Native records/view |
| Workflow invoice | records | 1 | 0 | Native records/view |
| Workflow payment | records | 1 | 0 | Native records/view |
| Workflow refund | records | 1 | 0 | Native records/view |
| Provider connector | integration | 1 | 0 | Provider request records only |
| Integration operation | integration | 1 | 0 | Provider request records only |
| Integration webhook receipt | integration | 1 | 0 | Provider request records only |
| Customer communication | records | 1 | 0 | Native records/view |
| Offline command | records | 1 | 0 | Native records/view |
| Workflow audit event | records | 1 | 0 | Native records/view |
| Pet operation | records | 1 | 0 | Native records/view |
| Pet balance entry | records | 1 | 0 | Native records/view |
| Pet audit | records | 1 | 0 | Native records/view |
| Pet knowledge | records | 1 | 0 | Native records/view |
| Pet ai draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 192 feature pages were visited in the browser; 190 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 32 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

32 original AI entries are now grouped into **6 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
