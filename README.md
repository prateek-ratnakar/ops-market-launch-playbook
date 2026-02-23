# 🌍 Ops Market Launch Playbook
### Zero-to-One Framework for Launching Operations in New International Markets

> Built from designing and delivering Amazon's international operations expansion framework from scratch — with no prior model to reference.  
> Covers everything from workforce planning to regulatory compliance to zero-defect launch execution.

---

## 📊 Results This Playbook Delivered

| Metric | Result |
|---|---|
| Ireland Launch | **Zero-defect** · April 2025 |
| Investigators Enabled | **10,000** on Day 1 |
| Annual Country Launches | Scaled from **2 → 5 per year** |
| Active Pipelines (2026) | Thailand · Indonesia · Portugal |
| Product Features Validated | **100+** per launch |
| Policies Localized | **1,000+** per market |

---

## 🧭 The Core Problem This Solves

Most ops teams launching into new international markets treat it as a project — a checklist of tasks with a go-live date.

That's why most launches have defects.

A market launch is actually a **system design problem**: you're standing up a new operating model — people, technology, policy, quality, and culture — in a context you've never operated in before, often under regulatory scrutiny, often with a hard deadline.

This playbook treats it that way.

---

## 🏗️ The 4-Pillar Launch Architecture

Every successful market launch needs all four pillars ready simultaneously. Missing even one causes launch defects.

```
┌─────────────────────────────────────────────────────────┐
│  PILLAR 1          │  PILLAR 2                          │
│  People &          │  Technology &                      │
│  Capacity          │  Tooling Readiness                 │
│                    │                                    │
│  - Headcount model │  - 100+ feature validation         │
│  - Training ramp   │  - Integration testing             │
│  - Org structure   │  - Fallback procedures             │
├────────────────────┼────────────────────────────────────┤
│  PILLAR 3          │  PILLAR 4                          │
│  Policy &          │  Quality &                         │
│  Compliance        │  Ramp Architecture                 │
│                    │                                    │
│  - 1,000+ policies │  - Quality baseline targets        │
│  - EU/local regs   │  - Ramp-up curve design            │
│  - Legal sign-off  │  - Error tolerance thresholds      │
└─────────────────────────────────────────────────────────┘
```

**Zero-defect launches happen when all 4 pillars hit green simultaneously.**  
The playbook gives you the framework to track each pillar independently and converge them on launch day.

---

## 🗂️ Framework Contents

### 1. People & Capacity Planning Model
How to size, hire, train, and ramp a workforce for a market you've never operated in.

**Key decisions this model answers:**
- How many investigators/agents do you need on Day 1 vs. Month 3?
- What's the productivity ramp curve for a new market (hours to proficiency)?
- How do you staff for uncertainty when volume forecasts are unreliable?
- What's your contingency headcount buffer and when do you trigger it?

> **Key insight:** New market volume is always wrong in the forecast. Design your staffing model around a range, not a point estimate. Build a 20% contingency buffer that can be activated within 2 weeks.

---

### 2. Technology & Tooling Readiness Checklist
The 100+ product feature validation framework used before every launch.

**Feature categories covered:**
- Core workflow tools (case routing, investigation platforms, dashboards)
- Language and localization readiness (UI, notifications, help content)
- Reporting and analytics (can leadership see the new market's data?)
- Integration dependencies (what breaks if an upstream system is unavailable?)
- Fallback and manual override procedures (what's the plan if tech fails on Day 1?)

> **Key insight:** Tech readiness is binary for launch — it either works or it doesn't. Build a RAG (Red/Amber/Green) tracker for every feature. Nothing launches with a Red item unmitigated.

---

### 3. Policy Localization & Regulatory Compliance Guide
How to localize 1,000+ policies for a new market while meeting local legal requirements.

**EU market considerations covered:**
- GDPR data handling requirements for investigation workflows
- Right-to-explanation obligations in automated decision systems
- Local labor law implications for workforce management
- Regulatory filing and notification timelines

**The localization process:**
```
Step 1: Policy Inventory      — Catalog all policies that apply to new market
Step 2: Gap Analysis          — Which policies need localization vs. direct apply?
Step 3: Legal Review          — Local counsel review of high-risk policy changes
Step 4: Translation & QA      — Linguistic accuracy + operational accuracy
Step 5: Training Integration  — New policies embedded in pre-launch training
Step 6: Sign-off Gate         — Legal + Operations dual approval before launch
```

---

### 4. Quality & Ramp-Up Architecture
How to define, measure, and protect quality standards during the most vulnerable phase — the first 90 days.

**The ramp-up quality model:**
- Set tiered quality targets: Day 1 / Day 30 / Day 90 / Steady State
- Define your error tolerance threshold (the point at which you pause launch)
- Build a daily quality pulse — not weekly — for the first 30 days
- Assign a dedicated Quality Lead per market for the first 60 days

> **Key insight:** Quality problems in new markets are almost always training gaps, not people gaps. When you see error spikes, go to the training content first before making staffing decisions.

---

### 5. The Pre-Launch War Room Protocol
How to run the final 30 days before launch — the period where everything either comes together or falls apart.

**30-day countdown structure:**
```
T-30 days: All Pillar leads confirm Green or escalate Reds
T-21 days: Full dress rehearsal with live systems
T-14 days: No-go criteria defined and signed off by all Directors
T-7 days:  Final readiness review with VP/SVP
T-2 days:  Hypercare team activated (24hr coverage begins)
T-0:       Launch + real-time monitoring dashboard live
T+7 days:  First post-launch retrospective
T+30 days: 30-day quality and productivity review
```

---

## 💡 Key Lessons from Building This from Zero

**1. The playbook is your political alignment tool.**
When different teams have different definitions of "ready," the playbook is what you point to. It makes launch readiness objective, not political.

**2. Zero-defect doesn't mean zero problems.**
It means zero *unmitigated* problems. Every launch has surprises. Zero-defect means you've anticipated enough that surprises don't become failures.

**3. Regulatory compliance is a timeline risk, not just a legal risk.**
EU regulatory requirements have hard deadlines and non-negotiable review periods. Map these on your launch timeline first — they constrain everything else.

**4. Train the trainers, not just the agents.**
In a 10,000-person launch, you can't train everyone directly. Identify and invest deeply in 50–100 training champions who cascade quality standards through the org.

**5. The hardest part is the handover.**
The launch team moves on. The steady-state team inherits. Design your playbook so that handover is a structured transition, not an abandonment.

---

## 📋 Common Launch Failure Modes (and How to Avoid Them)

| Failure Mode | Root Cause | Prevention |
|---|---|---|
| Day 1 volume surge crashes tools | Tech load testing skipped | Mandatory load test at 2x forecast volume |
| Agents can't find policies | Localization incomplete | Policy search UAT 30 days pre-launch |
| Quality below baseline at Day 30 | Training ramp underestimated | Add 1 extra week of supervised production |
| Regulatory finding post-launch | Legal review too late | Legal in the room at T-60, not T-14 |
| Key people leave after launch | Burnout from crunch | Hypercare team rotates, doesn't grind |

---

## 📁 Repository Structure

```
/
├── README.md                            ← You are here
├── /templates
│   ├── launch_readiness_tracker.xlsx    ← RAG status for all 4 pillars
│   ├── headcount_ramp_model.xlsx        ← Capacity planning with scenarios
│   ├── policy_localization_log.xlsx     ← Track 1,000+ policy decisions
│   ├── war_room_runbook.md              ← T-30 to T+30 day-by-day guide
│   └── no_go_criteria_template.md      ← What would stop your launch?
├── /checklists
│   ├── tech_readiness_100_items.md      ← Full feature validation checklist
│   ├── regulatory_compliance_EU.md      ← EU market requirements
│   └── training_sign_off_checklist.md  ← Pre-launch training gates
└── /guides
    ├── pillar_assessment_guide.md       ← How to score each pillar
    └── post_launch_retrospective.md    ← 30-day review template
```

---

## 🔗 Related Work

- [Enterprise GenAI Adoption Framework](https://github.com/prateek-ratnakar/enterprise-genai-adoption-framework) — 0% → 43.2% GenAI adoption · $9.9M saved · VP charter template
- [Ops Cost Transformation Toolkit](https://github.com/prateek-ratnakar/ops-cost-transformation-toolkit) — SQL, prioritization models & frameworks behind $130M in savings

---

## 👤 About the Author

**Prateek Ratnakar** — Senior Program Manager (Staff Track)  
11+ years at Amazon across global marketplace operations, GenAI transformation, and international expansion.

- 🏆 Amazon North Star Award — 2025 & 2021
- 🏆 Business Leader of the Year — Amazon 2019
- 📍 IIT BHU · IIM Bangalore
- 🔗 [LinkedIn](https://linkedin.com/in/prateek-ratnakar)

---

*This playbook is shared for knowledge exchange. All metrics and examples are from real programs, anonymized where required.*

