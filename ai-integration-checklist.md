# SAFe AI Integration Checklist

40 checkpoints organized by event. Use this before, during, and after each ART cycle to catch governance gaps before they cascade across the program board.

---

## Pre-PI-Planning Preparation (AI Readiness)

**Governance baseline**
- [ ] A named AI Model Steward (or System Architect with Steward charter) is identified for this PI cycle
- [ ] Model drift monitoring telemetry is active and was reviewed in the last iteration
- [ ] Prompt governance standards are documented — teams know which approved prompts generate backlog items
- [ ] A pre-AI baseline exists for lead time, deployment frequency, and flow efficiency (required to measure ROI)

**AI-assisted preparation tasks**
- [ ] AI has been given historical velocity data, known PTO, and past PI completion metrics to generate capacity forecasts
- [ ] Each team's Scrum Master has reviewed and validated the AI-generated capacity forecast before the event
- [ ] AI has generated candidate PI objectives from the prioritized feature backlog
- [ ] Each team has rewritten AI-drafted PI objectives to reflect actual business intent — no raw AI output goes to the room
- [ ] AI has performed a pre-event dependency audit on the backlog and flagged potential cross-team conflicts
- [ ] Each AI-flagged dependency has been reviewed and given a named human owner or discarded

**Backlog health**
- [ ] Backlog hygiene automation has been run — no Epics or Features with missing acceptance criteria in scope for this PI
- [ ] Orphaned stories (no parent Epic/Feature linkage) have been resolved or explicitly parked
- [ ] AI Product Owner has verified that AI-generated backlog items have clear provenance tracking

---

## During PI Planning

**Day 1 — Program Vision and Breakouts**
- [ ] AI is configured as an on-demand query tool only during live breakouts — proactive agent mode is off
- [ ] Teams have access to the AI-generated capacity forecasts as reference, not as binding commitments
- [ ] Facilitator confirms that cross-team dependency negotiation is happening in real conversation, not by accepting AI-suggested strings
- [ ] Any AI query answers given during breakouts are verbally confirmed by the relevant team before going on the board
- [ ] Business Owners are negotiating PI objective value scores with human teams — AI is not scoring objectives

**Day 2 — Risk and Confidence**
- [ ] After draft program board is complete, AI dependency audit is run to surface hidden or circular dependencies humans missed
- [ ] Each new AI-flagged dependency is reviewed: assign a human owner or explicitly remove it from the board
- [ ] RTE has reviewed all AI-surfaced risks and can articulate each one in their own words
- [ ] The confidence vote is conducted with zero AI input. Fist-of-five is a human psychological commitment.
- [ ] Post-planning: committed PI objectives and the final program board are saved as the baseline for drift monitoring

---

## ART Execution (Every Iteration)

**Flow monitoring**
- [ ] Flow Velocity, Flow Time, and Flow Load dashboards are populated by automated aggregation (not manually built by RTEs/SMs)
- [ ] Delivery drift alerts are active — teams are notified when a feature's trajectory deviates from committed PI objectives
- [ ] Continuous cross-team dependency detection is running against the live backlogs and commit history

**ART Sync preparation**
- [ ] AI ceremony summarization is configured to transcribe the ART Sync and auto-extract action items
- [ ] Action items from last ART Sync summary have been validated and routed to the correct team backlogs
- [ ] RTE has reviewed AI-aggregated flow metrics before the sync to prepare challenges — not reading dashboards live in the room
- [ ] Any AI-generated capacity or load balancing suggestions have been reviewed by relevant Scrum Masters before being acted on

---

## Model Steward Governance Audit (Per PI)

**Model health**
- [ ] Model precision and accuracy rates have been reviewed against the threshold established at PI start
- [ ] No significant model drift has been detected in output quality since last audit
- [ ] If drift was detected: a retrain cycle or failsafe parameters were triggered and documented
- [ ] Token costs and API spend have been reviewed against the Line 2 budget set in the AI ROI model

**Compliance and audit trail**
- [ ] All AI-assisted system decisions during this PI have an evidence trail: prompts used, model version, training context
- [ ] The AI Product Owner can produce a provenance report for any AI-influenced prioritization decision on request
- [ ] No AI-generated code or recommendations were pushed to production without human review and sign-off
- [ ] If any regulated outputs (financial, medical, legal data) were involved: compliance sign-off is documented

**Continuous improvement**
- [ ] Post-PI: actual flow metrics are compared against the pre-AI baseline to calculate Line 1 of the ROI formula
- [ ] Hidden overhead (rework caused by AI output) is captured for Line 3 of the ROI formula
- [ ] A decision has been made to progress the team's AI Operating Model stage, maintain current stage, or step back — with rationale documented

---

## Usage Notes

**When to use this:** Run the Pre-PI section 1-2 weeks before PI Planning. Run During-Planning sections live. Run Execution section at each ART Sync prep. Run the Governance Audit in the final iteration of the PI.

**When a box is unchecked:** Do not skip governance checkpoints to hit a deadline. An unchecked compliance item is a risk that needs to be surfaced, not ignored.

**Ownership:** Assign a named owner to this checklist per PI cycle. Recommend: the RTE owns Pre-PI and Execution sections; the AI Model Steward owns the Governance Audit section; the AI PO owns the backlog health items.

---

Source: Sanjay Saini, SAFe 6.0 AI Integration Survival Guide series — https://agileleadershipdayindia.org
