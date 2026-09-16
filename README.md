# PROJECT CONTROLS AI ASSURANCE STARTER PACK

**Use AI to prepare the evidence. Keep the project decision with the accountable human.**

Free, reusable Project Controls AI assurance toolkit: 17 editable templates, worked CE-018 examples, Power BI/Word/Excel outputs and control guidance for evidence-led, human-approved cost, schedule, risk, change, reporting and stage-gate assurance..

This repository accompanies DADA's CaSA webinar **Controlling AI, Data, Integration & Automation Programmes – A Practical Project Controls Toolkit**.

> **CONTROL PRINCIPLE**  
> An assistant may extract, link, compare, reconcile, cite, flag and prepare review material. It must not decide entitlement, approve a quotation, issue a contractual communication, instruct work or replace the named decision-maker.

## GET THE TOOLKIT

| Resource | What you get | Link |
|---|---|---|
| **Starter Pack v1.0** | 17 editable templates across four stages, plus user guide, quick-start guide and manifest | [Download ZIP](downloads/CE018_Project_Controls_AI_Assurance_Starter_Pack_v1.0.zip) |
| **Sample report outputs** | Power BI dashboard plus four scenario packs containing Word decision-readiness reports and Excel scorecards | [Download ZIP](downloads/CE018_Demo_WP_Sample_Report_Outputs_PowerBI_v1.0.zip) |
| **CaSA presentation** | The control method, decision gates and demonstration flow | [Open PDF](docs/CaSA_2026_Webinar_AI_Practical_Toolkit.pdf) |
| **Browse the templates** | Inspect the 17 template files directly in GitHub | [Open folder](starter-pack/) |
| **Browse sample outputs** | Inspect the Power BI model and the four example scenario outputs | [Open folder](sample-outputs/) |

For versioned distribution, publish the two ZIP files and presentation again as assets on the GitHub **Releases** page.

## WHAT PROBLEM DOES IT SOLVE?

AI can produce a confident answer before a project team has established whether the source is approved, the data is current, the evidence is complete or the person receiving the output has authority to act.

The Starter Pack puts a Project Controls process around that problem:

**CONTROL UNCERTAINTY → GOVERN AI USE → TEST THE OUTPUT → DECIDE & LEARN**

A fluent answer is not an accepted project output. Acceptance depends on approved evidence, traceability, configured controls and a named human decision.

## WHAT IS IN THE STARTER PACK?

The supplied pack contains **17 editable templates across four stages**. Each template contains a blank reusable version and a completed fictional CE-018 worked example.

| Stage | Purpose | Included controls |
|---|---|---|
| **01 — Control uncertainty** | Bound the use case before baselining the work | Use-Case and Controls Canvas; Uncertainty and Dependency Register |
| **02 — Govern AI use** | Set permitted purpose, data, sources, instructions and authority | Project AI Control Charter; Approved Use-Case Register; Data and Source Control Matrix; AI Toolbox Talk; Task Control Brief; Managed Assistant Instructions; Authority and Escalation Matrix |
| **03 — Test the output** | Test evidence, traceability, acceptance and configured controls | Evidence and Source Register; Four-Test Assurance Checklist; Test and Acceptance Scorecard; NEC4 Decision-Readiness Control Matrix; Evidence Exception Report |
| **04 — Decide and learn** | Record the human decision, corrective action and learning | Decision and Escalation Log; Corrective Action and Retest Register; Assurance Lessons-Learned Record |

See [RESOURCE_INDEX.md](resources/RESOURCE_INDEX.md) for the full file-by-file index.

## SAMPLE OUTPUTS INCLUDED

The companion demonstration pack has also been unpacked so visitors can see the output pattern without downloading the archive first.

• **Power BI:** `CE018_Assurance_Dashboard_v0.3_VALIDATED_MODEL.pbix`  
• **Scenario 1:** Word decision-readiness report + Excel scorecard  
• **Scenario 2:** Word decision-readiness report + Excel scorecard  
• **Scenario 3:** Word decision-readiness report + Excel scorecard  
• **Scenario 4:** Word decision-readiness report + Excel scorecard

The original packaged scenario ZIPs are retained under [`sample-outputs/packaged-scenarios/`](sample-outputs/packaged-scenarios/).

## REUSE THE SAME CONTROL PATTERN

The CE-018 example uses a controlled change/decision-readiness scenario. The method can be reconfigured for other Project Controls problems.

| Use case | How the pattern can be applied |
|---|---|
| **Cost assurance** | Reconcile reports, commitments, actuals, approved changes and forecasts; flag unsupported movements for review. |
| **Schedule assurance** | Test programme versions, data dates, logic, milestones and reported impacts against approved evidence. |
| **Risk assurance** | Identify stale, unowned or disconnected risks; prepare candidate risks and route them to the accountable owner for approval. |
| **Change control** | Check notices, instructions, quotations, assessments, clocks and authority without allowing AI to decide entitlement. |
| **Reporting assurance** | Trace Key Performance Indicators (KPIs), commentary and claims back to approved source data. |
| **Stage Gate assurance** | Collect required evidence, identify missing/outdated records, prepare the review pack and route exceptions before the gate decision. |
| **Handover to Maintenance** | Test asset records, operation and maintenance information, certificates, training, defects and outstanding actions before handover. |
| **Automated risk reporting** | Use Power Automate to route candidate risks, changes or exceptions for human review before the approved register is updated. |

## FIVE-STEP ASSURANCE ROUTE

### 1 — DEFINE THE TEST

State the use case and decision supported. Define the expected result, acceptance thresholds and critical controls before the assisted run begins.

### 2 — ASSEMBLE APPROVED EVIDENCE

Identify the approved sources. Record owner, version and date. Confirm data permissions and exclusions.

### 3 — TEST AND SCORE

Run the agreed assurance tests and record the evidence supporting each result. The supplied scorecard uses `2 = pass`, `1 = bounded limitation` and `0 = critical failure`.

### 4 — APPLY THE CRITICAL GATE

A critical-control failure overrides the overall score. Examples include an unapproved source, missing mandatory evidence, a privacy breach or no authorised approver.

### 5 — RECORD THE HUMAN DECISION

The named decision-maker records the outcome: **accept, accept with conditions, rework, or reject/escalate**. No output is accepted by score alone.

## QUICK START

1. Read [`starter-pack/README_FIRST.txt`](starter-pack/README_FIRST.txt) and the [Quick Start Guide](starter-pack/CE018_Starter_Pack_Quick_Start_Guide.pdf).
2. Pick **one bounded Project Controls decision**.
3. Configure the templates to your contract, governance, data classification and named roles.
4. Define the approved evidence and acceptance tests before using AI.
5. Run the four-stage assurance process.
6. Keep the completed records as the audit trail.
7. Reuse the control pattern for the next problem only after the first controlled review has proved useful.

## IMPORTANT BOUNDARY

The resources support controlled Project Controls assurance. They do **not** provide legal advice, certify NEC4 compliance, transfer contractual authority to AI or make an AI output authoritative simply because it has been scored.

The worked example is **Fictional Demonstration Data**. The Westbridge Station project, CE-018 event, organisations and named individuals are invented. Replace all demonstration values, roles, thresholds and contract references before operational use.

## REPOSITORY STRUCTURE

```text
.
├── README.md
├── CITATION.cff
├── CONTRIBUTING.md
├── SECURITY.md
├── USAGE_NOTICE.md
├── docs/
│   └── CaSA_2026_Webinar_AI_Practical_Toolkit.pdf
├── downloads/
│   ├── CE018_Project_Controls_AI_Assurance_Starter_Pack_v1.0.zip
│   └── CE018_Demo_WP_Sample_Report_Outputs_PowerBI_v1.0.zip
├── starter-pack/
│   ├── 01 Control uncertainty/
│   ├── 02 Govern AI use/
│   ├── 03 Test the output/
│   └── 04 Decide and learn/
├── sample-outputs/
│   ├── CE018_Assurance_Dashboard_v0.3_VALIDATED_MODEL.pbix
│   ├── scenarios/
│   └── packaged-scenarios/
├── resources/
│   ├── RESOURCE_INDEX.md
│   ├── RESOURCE_INDEX.csv
│   └── SHA256SUMS.txt
└── .github/
    ├── ISSUE_TEMPLATE/
    └── pull_request_template.md
```

## WEBINAR, WEBSITE AND SUPPORT

• DADA Downloads: https://www.big-dada.co.uk/downloads/  
• DADA website: https://www.big-dada.co.uk/  
• Contact / use-case support: https://www.big-dada.co.uk/contact/  
• LinkedIn Company Page: https://www.linkedin.com/company/dada-enterprises/

If you adapt the method to another Project Controls problem, open a GitHub issue using the **New use case** template. That gives DADA a practical way to see which examples would be most useful next.

## VERSION

Starter Pack: **v1.0**  
GitHub publishing pack: **v1.1**

---

**DADA Enterprises Limited**  
Project Controls | Risk | PMO | Digital Transformation | AI Assurance  
https://www.big-dada.co.uk/
