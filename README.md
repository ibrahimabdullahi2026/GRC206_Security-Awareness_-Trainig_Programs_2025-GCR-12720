# Northbridge Logistics: 12-Month Security Awareness Program

**Institution:** International Cybersecurity and Digital Forensics Academy (ICDFA)  
**Course:** GRC206 · Security Awareness & Training Programs  
**Assignment:** Northbridge Logistics: 12-Month Security Awareness Program  

| Student Information | Details |
| :--- | :--- |
| **Student** | Ibrahim Abdullahi |
| **Registration Number** | 2025/GCR/12720 |
| **Official Email** | gcr2512720@students.icdfa.edu.ng |
| **Program** | GRC Engineering (CGRCE) |
| **School** | School of Cyber Risk, Governance and Compliance |
| **Cohort** | Batch B2025 |
| **Academic Session** | 2026 |
| **Level / Year** | Level 1 / Year 1 |

---

## Executive Overview

This report applies the five-stage lifecycle (**Assess, Plan, Deliver, Measure, Improve**) to Northbridge Logistics, in line with the lifecycle approach to learning programmes in **NIST SP 800-50r1** (Merritt et al., 2024). 

* Facts taken directly from the assignment brief are marked **(S)**. 
* Planning assumptions are marked **(A1–A6)**, and all remaining elements represent proposed program designs. 
* All figures and targets are illustrative planning choices rather than existing Northbridge operational results.

---

## Assumptions Used Throughout

* **A1 — Workforce Segments (Total 800 (S)):** Finance, procurement, and payroll (35); executives and assistants (25); office-based staff including IT (215); remote sales (100); warehouse supervisors (45); warehouse operatives (380).
* **A2 — Systems:** Corporate email supports a one-click report button, MFA, and simulations; warehouse operatives mostly use shared handhelds and have little or no desk time.
* **A3 — Delivery Team:** Security Manager plus two analysts (the brief notes a "small" team **(S)**); HR/L&D partner at 0.2 FTE; approximately 20 volunteer champions at roughly 2 hours per month.
* **A4 — Budget:** Approximately USD 30,000 for the year covering tools, printing, translation, and recognition, excluding salaries (the brief notes a "modest" budget **(S)**).
* **A5 — Governance Authority:** The executive sponsor can release 10 paid minutes per shift per month; HR and Legal approve phishing simulations and the staff no-blame notice.
* **A6 — Languages & Law:** English plus at least one local language on site; no specific jurisdiction is stated, so applicable data-protection law is assumed to apply to the regulated customer data **(S)**.

---

## Task 1: Assess

### 1.1 Top Three Human-Driven Risks

| Risk ID & Title | Scenario Evidence | Why It Ranks High | Unsafe Behaviour $\rightarrow$ Safer Action |
| :--- | :--- | :--- | :--- |
| **R1: Invoice fraud and payment redirection** | Recent invoice-fraud attempts **(S)**. | Direct financial loss. Business email compromise produced 24,768 complaints and about USD 3.05 billion in reported losses to the FBI in 2025 (FBI IC3, 2026). | Pays, or changes bank details, on an emailed or phoned request $\rightarrow$ Verifies by calling a known number and uses two-person approval. |
| **R2: Password reuse and weak credential hygiene** | Two staff reused passwords after a breach **(S)**. Regulated customer data **(S)**. | One reused password turns a single breach into many. Credential abuse appeared in about 39% of breaches in 2025 (Verizon, 2026). | Reuses passwords or shares logins on shared devices $\rightarrow$ Uses unique passwords in an approved manager with MFA and reports suspected exposure at once. |
| **R3: Social engineering across email, SMS and phone, and delayed reporting** | Staff in three work settings, including remote sales **(S)**. | The human element was involved in 62% of breaches (Verizon, 2026). Silence turns a small mistake into an incident, and click-focused training alone changed little in a 19,500-employee trial (Ho et al., 2025). | Ignores, deletes, or hides a suspicious message or their own mistake $\rightarrow$ Reports within minutes through one simple route, without blame. |

> **Scope Note:** The ranking weighs scenario evidence, the potential impact on money and regulated data, and how directly behaviour can change the outcome. Mishandling customer data (for example, misdirected email or unapproved AI tools) was considered and is covered as a topic for office and remote audiences under **R2** and **R3** rather than as a fourth separate risk.

### 1.2 Audiences and Their Needs

| Audience (Assumed Size, A1) | Work Context & Needs | Priority Topics (Risk) |
| :--- | :--- | :--- |
| **Finance, procurement and payroll (35)** | Handle invoices, bank-detail changes, and urgent requests; need quick, practical verification steps and the authority to say no. | Verify-before-pay; vendor and executive impersonation; reporting attempts **(R1, R3)** |
| **Executives and assistants (25)** | Frequent impersonation targets who approve payments and set the tone; very little time. | Urgent-request discipline; voice and email impersonation; visible no-blame stance **(R1, R3)** |
| **Office-based staff incl. IT (215)** | Daily email and cloud tools; access to regulated customer data; some desk time. | Phishing and reporting; passwords, MFA and password manager; safe data handling **(R2, R3)** |
| **Remote sales (100)** | Work off-site on mobiles and public networks; handle customer data; isolated from colleagues; exposed to SMS and phone approaches. | Smishing and vishing; MFA prompts; device and Wi-Fi safety; reporting **(R2, R3)** |
| **Warehouse supervisors (45)** | Lead shifts and are the first contact for operatives; limited desk time. | Running toolbox talks; receiving and escalating reports; shared-login rules **(R2, R3)** |
| **Warehouse operatives (380)** | Shift work on shared handhelds; little desk time; varied language and reading preferences; may receive suspicious calls or texts. | Short practical routines: no shared logins, spot suspicious calls and texts, know how to report **(R2, R3)** |

### 1.3 Pre-Launch Baseline (Months 1–2)

* **Fraud (R1):** 12-month log of invoice-fraud attempts and near misses (how many, how detected, how many reported, any loss). *Sources:* Accounts payable records, email gateway logs, incident register.
* **Credentials (R2):** Share of accounts with MFA; number of accounts with breached or reused passwords found by screening against known breach data; password-manager adoption. *Sources:* Identity-provider and IT admin reports.
* **Reporting (R3):** One low-difficulty baseline phishing simulation for office and remote staff, recording report rate and time-to-report. Click rate is recorded but treated as secondary (Ho et al., 2025).
* **Culture and Knowledge:** Anonymous 8-question pulse survey (paper or QR code for warehouse): *Do you know how to report? Would you report a mistake without fear? How confident are you spotting fraud?*
* **Incident History & Context:** Human-error incidents and time-to-report over the last 12 months (incident register, service-desk tickets); observation of two shift starts and interviews with four supervisors to learn real constraints on time, devices, and language.

---

## Task 2: Plan

### 2.1 Sponsor and Owners (By Role)

| Role | Responsibilities |
| :--- | :--- |
| **Executive Sponsor: Chief Operating Officer** *(assumed title)* | Approves budget and paid shift time, publicly backs the no-blame principle, receives the quarterly review, and makes the decisions it needs. |
| **Programme Owner: Security Manager** | Owns the plan, content, simulations, dashboard, and quarterly review; leads Objective 3; escalates risks to the sponsor. |
| **Finance Controller** | Owns the verify-before-pay procedure and Objective 1; supplies fraud-attempt data and audits bank-detail changes. |
| **Head of IT Operations** | Owns MFA and password-manager rollout (Objective 2) and the report button, hotline, and triage at the service desk. |
| **Warehouse Operations Manager** | Schedules toolbox talks, protects supervisor time, and relays feedback from every shift. |
| **HR/L&D Lead (0.2 FTE)** | Runs onboarding, learning records, surveys, and recognition logistics. |
| **Champions (~20)** | At least one per site and shift, plus finance and sales: local reminders, listening circles, and feedback (about 2 hours a month). |

### 2.2 Measurable Objectives (Proposed Targets)

| Objective (Risk) | Proposed Target & Deadline | Evidence | Accountable Owner |
| :--- | :--- | :--- | :--- |
| **O1: Verify before paying (R1)** | At least **95%** of vendor bank-detail changes and urgent payment requests verified by call-back to a known number before payment by end of **Month 6**, sustained to **Month 12**. | Monthly audit of all bank-detail changes. | Finance Controller |
| **O2: Stronger credentials (R2)** | By end of **Month 9**, at least **90%** of staff with corporate accounts use MFA and the approved password manager; breached or reused password findings fall by at least **80%** from the Month 2 baseline by **Month 12**. | Identity-provider and password-manager reports; repeat screening. | Head of IT Operations |
| **O3: Fast reporting (R3)** | At least **60%** of simulated phishing messages reported by **Month 6** and **70%** by **Month 12**, with median time-to-report **under 30 minutes**; at least **90%** of warehouse staff sampled can describe the reporting route at the Month 6 spot check. | Simulation platform, report-button and hotline logs, spot-check sheet. | Security Manager |

> Targets will be re-checked against the Month 2 baseline and reset if the baseline shows they are unrealistic. Topics for each audience are linked to the risks in Section 1.2, and every activity in the calendar traces back to one of **R1–R3**.

---

## Task 3: Deliver

Formats follow how each audience actually works, pairing training with technical and procedural controls that make the safer action the easy one: a call-back procedure, MFA, a password manager, and one-click reporting. A trial with 19,500 hospital employees found that commonly deployed phishing training had little practical effect on clicks (Ho et al., 2025), so this programme does not rely on training alone or on click rates.

### 3.1 Formats by Audience

| Audience | Format & Cadence | Why It Fits |
| :--- | :--- | :--- |
| **Finance, procurement and payroll** | 75-minute workshop using redacted real fraud attempts; desk job-aid card; 20-minute refreshers in Months 6 and 9. | Rehearses the exact verification steps in a small group and keeps a prompt at the point of action. |
| **Executives and assistants** | 30-minute briefing plus an urgent-request tabletop (Months 3 and 9). | Respects their time; they are impersonation targets and approvers. |
| **Office-based staff** | 10-minute monthly microlearning; drop-in MFA and password-manager clinics; quarterly simulation. | Short and regular with no workload spike; clinics help staff set up password managers, which current NIST authentication guidance supports (NIST, 2025). |
| **Remote sales** | Two live 20-minute online sessions at different times; mobile-friendly microlearning; SMS and phone scam drill. | Fits dispersed schedules and mobile working, and covers voice and text lures. |
| **Warehouse supervisors** | 45-minute train-the-trainer session plus a facilitator card. | They deliver the talks, so they are equipped first. |
| **Warehouse operatives** | Monthly 10-minute toolbox talk at shift start, led by supervisors in paid time; picture-led one-page card; QR posters at handhelds and break rooms. | No desk time is needed; it reuses the existing safety-briefing habit; plain language, translated where needed. |

### 3.2 Onboarding
Every new starter completes a **30-minute security induction** in Week 1 (covering the reporting route, passwords and MFA, payment verification where relevant, and the no-blame message) and a short role module within 30 days. HR records completion. Warehouse starters receive the toolbox talk on their first shift.

### 3.3 Phishing Simulation Approach
* **Schedule:** Baseline in Month 2, then quarterly (Months 4, 7, and 10) for office and remote staff, with an SMS and phone drill for remote sales (Month 8) and supervisors (Month 9). Simulations use work channels only.
* **Fairness:** HR and Legal approve the design; staff are told simulations take place; difficulty varies; no punishment and no naming of individuals; results are reported only in aggregate for groups of at least 10.
* **Supportive Follow-Up:** An immediate 60-second *"what to look for"* page; reporters are thanked first; repeat clickers are offered an optional 10-minute chat with a champion, never a disciplinary step; if many people fall for the same lure, the process or filter is fixed.
* **Measure of Success:** Reporting and verification, not click avoidance. Email filtering and MFA remain the main technical defences.

### 3.4 No-Blame Reporting Route
One simple route for every audience:
1. A **"Report"** button in email.
2. A **short phone number and QR code** answered by the service desk (with a 24-hour answerphone for shift workers) for texts, calls, and anything else.
3. Every report is **acknowledged at once** and given an outcome note within one working day.
4. A **sponsor-signed statement** confirming that reporting a mistake within one hour is never grounds for discipline (deliberate policy breaches remain a separate HR matter).

---

## Task 4: Measure

Metrics separate **reach** (who was covered), **behaviour** (what people do), and **outcomes** (what happens). Each is compared against the Month 1–2 baseline.

| Metric (Type) | Calculation | Data Source | Owner | Review Cadence |
| :--- | :--- | :--- | :--- | :--- |
| **M1: Role-relevant participation** *(Reach)* | $\frac{\text{Staff who completed scheduled activity}}{\text{Staff assigned}}$ (by audience and shift) | HR learning records; toolbox attendance sheets. | HR/L&D Lead | Monthly |
| **M2: Report rate and time-to-report** *(Behaviour)* | $\frac{\text{Simulated messages reported}}{\text{Simulated messages delivered}}$; median minutes from delivery to report; count of real reports. | Simulation platform; report-button and hotline logs. | Security Manager | Each simulation; real reports monthly |
| **M3: Payment verification rate** *(Behaviour)* | $\frac{\text{Bank changes \& urgent requests verified by call-back}}{\text{Total requests in the month}}$ | Accounts payable change log; audit. | Finance Controller | Monthly |
| **M4: Credential hygiene** *(Behaviour)* | Share of accounts with MFA; share using approved password manager; breached or reused passwords found at screening. | Identity-provider report; password-manager console; screening. | Head of IT Operations | Monthly |
| **M5: Human-error incidents** *(Outcome)* | Confirmed incidents with a human-behaviour cause per 100 staff, with median time to report and contain. | Incident register. | Security Manager | Quarterly |
| **M6: Fraud outcome** *(Outcome)* | Invoice-fraud attempts that reached payment stage; value paid versus value stopped. | Finance records; incident register. | Finance Controller | Quarterly |
| **M7: Reporting climate** *(Behaviour)* | Share agreeing *"I know how to report"* and *"I would report a mistake without fear"*. | Pulse survey (paper or QR for warehouse). | HR/L&D Lead | Months 2, 6, 12 |

### 4.1 Interpreting Metric Movements
* **M1 high, M2 and M3 flat:** Content is reaching people but not changing behaviour $\rightarrow$ revisit the format or supporting control. Low M1 on one shift points to a scheduling or access barrier, not unwillingness.
* **M2 and real reports rising:** More incidents become visible, so M5 may rise initially. Read alongside severity and time-to-contain, this signals a healthier reporting culture rather than failure.
* **Clicks falling without more reporting:** Treated with caution; click rate is recorded but is not a target (Ho et al., 2025).
* **M3 and M6 together:** Show whether the call-back control and awareness are protecting funds; **M4** separates technical adoption from awareness.

### 4.2 Leadership Reporting
* **Monthly:** A one-page dashboard (trend against baseline, Red-Amber-Green) sent to the sponsor and department heads.
* **Quarterly:** A 30-minute briefing inside the review, explicitly stating limitations (small numbers within some audiences, simulations are not real attacks, survey answers are self-reported, baseline covers only two months) and decisions needed (such as protecting shift time, enforcing the call-back rule, or funding).
* **Year-End:** A comprehensive evaluation comparing Month 12 with the baseline and recommending next-year priorities.

---

## Task 5: Improve and Sustain

### 5.1 Quarterly Review Routine (Months 3, 6, 9, and 12)
A 60-minute meeting chaired by the Security Manager and attended by the Executive Sponsor, Finance Controller, Head of IT Operations, Warehouse Operations Manager, HR/L&D Lead, and two champions (including one warehouse supervisor). It examines the dashboard, incident lessons, simulation results, learner feedback, and threat updates. Decisions are logged with an owner, due date, and status, and each meeting opens by reviewing prior actions.

**Triggers for Content Updates:**
1. A confirmed incident or near miss with a human cause (triggers a micro-update within 14 days).
2. An emerging scam seen internally or in threat advisories (e.g., vendor impersonation, voice cloning, SMS lures).
3. A process or system change (e.g., new payment portal or MFA workflow change).
4. A metric off target for two consecutive reviews (e.g., report rate below target or verification under 90%).
5. Repeated themes in learner feedback.

### 5.2 Listening to Learners
* A two-question feedback card or QR code follows every learning activity.
* Champions run a 30-minute listening circle on each shift every quarter (including nights and weekends).
* Anonymous feedback is accepted anytime via the reporting route.
* Pulse surveys in Months 2, 6, and 12 allow audience-level comparison, supported by a quarterly *"You Said, We Did"* notice highlighting improvements.

### 5.3 Recognising Good Behaviour Without Shaming
* **"Great Catch" Recognition:** Monthly (with consent), a short note highlights a person or team that made a useful report, accompanied by a thank-you from the sponsor and a small non-cash token.
* **Near-Miss Stories:** In quarterly team meetings, volunteers who made a mistake and reported it quickly are thanked and their lesson is shared (anonymised unless they choose otherwise). Recognition is never used for ranking or league tables.

### 5.4 Sustainability for a Small Team
Estimated ongoing effort:
* **Security Manager:** ~0.3 FTE
* **Security Analysts:** ~0.2 FTE (simulations and triage)
* **HR/L&D Lead:** ~0.2 FTE
* **Champions:** ~2 hours/month per champion
* **Warehouse Supervisors:** 10 minutes/shift/month

No audience receives more than two activities in any single month, and the calendar staggers simulations and talks so preparation, delivery, and follow-up never collide in the same weeks.

---

## 12-Month Program Calendar

**Key:** `A` = Activity delivered | `M` = Measurement point | `R` = Quarterly review  
**Owners:** `COO` = Sponsor | `SM` = Security Manager | `FC` = Finance Controller | `ITO` = Head of IT Operations | `WOM` = Warehouse Operations Manager | `HR` = HR/L&D Lead | `CH` = Champions | `SUP` = Supervisors  

*(Note: Each activity traces directly to a risk in the report: **R1** invoice fraud [rows 9–11], **R2** credentials [row 8], **R3** reporting and social engineering [rows 7, 12–20].)*

| # | Activity | Audience | Owner | M1 | M2 | M3 | M4 | M5 | M6 | M7 | M8 | M9 | M10 | M11 | M12 |
| :- | :--- | :--- | :--- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| **GOVERNANCE AND MEASUREMENT** | | | | | | | | | | | | | | | |
| 1 | Approve plan and budget; appoint owners and ~20 champions | Leadership | COO; SM | `A` | | | | | | | | | | | |
| 2 | Capture baseline: logs, breached-password screen, baseline sim, pulse survey, shift observation | All | SM; HR | `A` | `M` | | | | | | | | | | |
| 3 | Monthly one-page dashboard to sponsor and department heads | Leadership | SM | | | `M` | `M` | `M` | `M` | `M` | `M` | `M` | `M` | `M` | `M` |
| 4 | Quarterly review and action log | Review group | SM (chair); COO | | | `R` | | | `R` | | | `R` | | | `R` |
| 5 | Pulse surveys and warehouse reporting spot check | All | HR; CH | | | | | | `M` | | | | | | `M` |
| 6 | Year-end evaluation and next-year plan | Leadership | SM | | | | | | | | | | | | `A` |
| **CONTROLS AND REPORTING** | | | | | | | | | | | | | | | |
| 7 | Launch report button, hotline/QR code and no-blame statement | All | ITO; COO | | `A` | `A` | | | | | | | | | |
| 8 | MFA and password-manager rollout in waves, with drop-in clinics | Finance, office, remote, supervisors | ITO | | | `A` | `A` | `A` | `A` | `A` | | | | | |
| 9 | Verify-before-pay procedure live; monthly audit of bank-detail changes | Finance | FC | | | `A` | `M` | `M` | `M` | `M` | `M` | `M` | `M` | `M` | `M` |
| **ROLE-BASED DELIVERY** | | | | | | | | | | | | | | | |
| 10 | Finance: 75-minute workshop, then 20-minute refreshers | Finance, procurement, payroll | FC; SM | | | `A` | | | `A` | | | `A` | | | |
| 11 | Executives and assistants: briefing and urgent-request tabletop | Executives, assistants | SM | | | `A` | | | | | | `A` | | | |
| 12 | Onboarding: week-1 induction and 30-day role module | New starters | HR | `A` | `A` | `A` | `A` | `A` | `A` | `A` | `A` | `A` | `A` | `A` | `A` |
| 13 | Monthly 10-minute microlearning (topics rotate) | Office, remote | SM; HR | | | `A` | `A` | `A` | `A` | `A` | `A` | `A` | `A` | `A` | `A` |
| 14 | Phishing simulations with supportive follow-up | Office, remote | SM | | | | `A` | | | `A` | | | `A` | | |
| 15 | Live sessions (two time slots); SMS and phone scam drill | Remote sales | SM | | | | `A` | | | | `A` | | | | |
| 16 | Train-the-trainer and facilitator card; scam call/SMS drill in Month 9 | Warehouse supervisors | WOM; SM | | | `A` | | | | | | `A` | | | |
| 17 | Monthly 10-minute toolbox talk; QR posters at handhelds and break rooms | Warehouse operatives | SUP; WOM | | | | `A` | `A` | `A` | `A` | `A` | `A` | `A` | `A` | `A` |
| **RECOGNITION AND IMPROVEMENT** | | | | | | | | | | | | | | | |
| 18 | "Great catch" recognition | All | COO; HR | | | | `A` | `A` | `A` | `A` | `A` | `A` | `A` | `A` | `A` |
| 19 | Champion-led listening circles by shift | All shifts | CH | | | | | `A` | | | `A` | | | `A` | |
| 20 | Content refresh from review actions and triggers | All | SM | | | | `A` | | | `A` | | | `A` | | |

---

## Critical Reflection

The hardest part was designing for the warehouse. Most of the 380 operatives have little desk time, share devices, and cannot be reached reliably by email, so a standard e-learning plan would have reached them only on paper. I built that part around ten-minute supervisor-led toolbox talks and a reporting route that works by phone or QR code, though I remain mindful of whether supervisors will consistently have the time and confidence to deliver them. I also had to keep the plan light enough for a three-person security team to maintain.

The main trade-off was between realistic phishing simulations and staff trust. Because click-focused training appears to change little (Ho et al., 2025), I chose reporting and verification as the behaviours to measure, and kept simulations no-blame and aggregate-only. The biggest uncertainty is the baseline: my headcounts and targets are assumptions, so the Month 2 baseline may require resetting them.

---

## References

* Federal Bureau of Investigation, Internet Crime Complaint Center. (2026). *2025 Internet crime report*. https://www.ic3.gov/
* Ho, G., Mirian, A., Luo, E., Tong, K., Lee, E., Liu, L., Longhurst, C. A., Dameff, C., Savage, S., & Voelker, G. M. (2025). *Understanding the efficacy of phishing training in practice*. 2025 IEEE Symposium on Security and Privacy. Summary: https://today.ucsd.edu/story/cybersecurity-training-programs-dont-prevent-employees-from-falling-for-phishing-scams
* Merritt, M., Hansche, S., Ellis, B., Sanchez-Cherry, K., Snyder, J. N., & Walden, D. (2024). *Building a cybersecurity and privacy learning program (NIST Special Publication 800-50r1)*. National Institute of Standards and Technology. https://doi.org/10.6028/NIST.SP.800-50r1
* National Institute of Standards and Technology. (2025). *Digital identity guidelines: Authentication and authenticator management (NIST Special Publication 800-63B-4)*. https://doi.org/10.6028/NIST.SP.800-63b-4
* Verizon. (2026). *2026 data breach investigations report*. https://www.verizon.com/business/resources/reports/dbir/

---

## AI-Assistance Declaration

I used Claude (Anthropic) to help draft and structure this report, the calendar, and the reflection from the assignment brief, and to format the document. I reviewed and edited the content of the assignment; I am responsible for it, and I disclose this assistance in line with ICDFA policy. Scenario facts are taken from the brief; all other figures, headcounts, and targets are my assumptions or proposals and are labelled as such.
