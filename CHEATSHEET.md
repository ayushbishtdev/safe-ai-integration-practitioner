# SAFe 6.0 AI Integration — One-Page Cheatsheet

> Print this. Pin it. Share it at PI Planning.

---

## The Number to Know

**54.3%** of Agile practitioners name "integration uncertainty" as their #1 barrier — 18 pts ahead of job replacement fears. It is a *process gap*, not a skills gap.

---

## 4-Stage AI Operating Model

| Level | Name | AI Role |
|---|---|---|
| **0** | Ad-Hoc Personal Use | LLM as personal productivity tool only |
| **1** | Team Ritual Integration | Backlog drafting, ceremony summaries — PO governs all output |
| **2** | Program-Level Coordination | Dependency detection, capacity forecasting — ART governance required |
| **3** | Value Stream Economics | Flow analytics and bottleneck prediction tied to financial outcomes |

**Self-check:** Can your team name who *owns the AI output* in a PI Planning? If not, you are at Level 1.

---

## 6 ART Automation Flows (Targets for 35% Sync Reduction)

1. **Continuous dependency detection** — scans backlogs and commit histories
2. **Flow metric aggregation** — real-time Velocity, Time, and Load across all teams
3. **Delivery drift early warning** — flags features deviating from PI objectives
4. **Backlog hygiene automation** — catches missing ACs, orphaned stories, bad sizing
5. **Ceremony summarization** — transcription + action item routing from ART Sync
6. **Capacity & load balancing insights** — dynamic rebalancing suggestions before sprint start

**What stays human:** System Demo. Confidence vote. Dependency negotiation. Escalation conversations.

---

## AI in PI Planning — 5-Step Map

| Step | AI | Human |
|---|---|---|
| **Pre: Capacity** | Forecast from historical velocity + PTO | SM validates and defends the number |
| **Pre: Draft Objectives** | Synthesize features into candidate PI objectives | Team rewrites; BOs negotiate value |
| **Live: Breakouts** | On-demand query tool only | Teams negotiate face-to-face |
| **Post: Dependency Audit** | Scan for hidden/circular dependencies | RTE and teams review flagged risks |
| **Vote** | *Nothing* | Fist-of-five is non-negotiable and fully human |

> Every AI-generated dependency needs a named human owner who can explain it. If no one can explain it, delete it.

---

## Two New Roles — Definitions

**AI Product Owner (AI PO)**
- Curates AI-generated backlog items instead of writing from scratch
- Must catch confident-but-wrong model outputs before team planning
- Owns provenance: which features were human-conceived vs. model-suggested
- Required skill: data provenance tracking for audit trails in regulated industries

**AI Model Steward**
- Sets up telemetry pipelines: accuracy, latency, bias monitoring
- Triggers retrain cycles when model precision falls below threshold
- Maintains evidence trail: prompts, model versions, training contexts used
- Can be a chartered specialization on an existing System Architect — no new headcount required immediately

---

## SAFe vs Scrum for AI Agents — Decision Rule

Use **pure Scrum** when: AI is a personal productivity layer within one team, no cross-team agent dependencies.

Use **SAFe (or SAFe + Scrum hybrid)** when: autonomous agents execute multi-step workflows, outputs can affect other teams' APIs or program boards.

**Rule of thumb:** Scrum handles localized blast radius. SAFe contains program-level blast radius.

---

## The 4-Line CFO ROI Formula

```
Line 1: Flow Economic Gain = (Pre-AI Lead Time − Post-AI Lead Time) × Weekly Cost of Delay
Line 2: Direct AI Costs    = Vendor model spend + API token costs
Line 3: Hidden Overhead    = AI-induced rework cost + Model Steward governance overhead
Line 4: Net VSM ROI        = Line 1 − (Line 2 + Line 3)
```

"AI made us faster" is not a business case. "We reduced cost-of-delay by $X, netting out $Y in model costs" is.

---

## 5-Step Certification Sequence

1. **Leading SAFe (2026)** — framework baseline, flow metrics emphasis
2. **AI-Empowered Leading SAFe bridge** — SAFe-specific LLM application
3. **Role-specific AI track** — PO: backlog provenance | SM/RTE: flow automation
4. **Governance track** — model guardrails, drift monitoring, compliance
5. **Portfolio economics** — cost-of-delay math, CFO business case

*Do not start at Step 3. You will waste the training budget.*

---

## Flow Efficiency Benchmark

Most enterprise value streams operate at **under 15% flow efficiency** (active work time vs. total elapsed time). AI VSM typically surfaces **up to 40% hidden wait states** invisible to manual whiteboard sessions.

---

*Source: Sanjay Saini, SAFe 6.0 AI Integration Survival Guide series — [agileleadershipdayindia.org](https://agileleadershipdayindia.org)*
*Data: Scrum.org AI4Agile Practitioners Report 2026 (n=289, 20+ countries)*
