# fema-grant-service-case-study
# FEMA Grant-Making Service Design Case Study

## Jump Links

- [Executive Summary](#executive-summary)
- [Visual Summary](#visual-summary)
- [Service Design Storyboard](#service-design-storyboard)
- [My Role](#my-role)
- [The Problem](#the-problem)
- [Key Insight](#key-insight)
- [Before → After](#before--after)
- [Data Product Perspective: Enables AI](#data-product-perspective-enables-ai)
- [90-Day Mitigation Plan](#90-day-mitigation-plan)
- [Change Leadership & Constraints](#change-leadership--constraints)
- [Why This Matters](#why-this-matters)
- [Takeaway](#takeaway)

## Executive Summary

This case study examines a federal grant-making platform intended to function as a centralized service across multiple programs, including Public Assistance, Mitigation, and Preparedness.

The initial effort focused on improving **application consistency**. Through service design analysis, a deeper issue emerged:

> **The system improved the interface, but not the data or grant-making capability.**

By reframing the problem toward **data interoperability and service outcomes**, this work identifies a path to reduce burden, improve decision-making, and support national preparedness goals.

---

## Visual Summary

The visual below shows the proposed service model, highlighting the centralized applicant/project record, program overlays, and the shift from application-centric workflows to reusable service data.

![Service Model](./fema_service_artifact_aligned_script.svg)
*Service model visual: centralized service design and data reuse across programs.*

---

## Service Design Storyboard

This storyboard captures the current service-delivery journey and the opportunity to shift from a UI-driven experience toward a data-centered service.

![Service Design Storyboard](./service_design_storyboard.svg)
*Storyboard: applicant journey through application forms, program silos, review complexity, and the redesigned service model.*

### Visual Dialogue & Executive Talk Track

Use the graphic narration to make the contrast clear:

- **The Legacy Trap:** "We cannot see if the data answers your questions until we build the interface." 
  - Data label: *Disconnected Silos = Zero Intelligence.*
- **The AI Revolution:** "We secure the data foundation first. The AI answers the mission needs immediately." 
  - Data label: *Unified Data Layer = Instant ROI.*

When presenting this slide, lead with these points:

- **The Setup:** "Leaders face a critical choice in how we modernize grant systems. We can continue down the legacy road of UI-first delivery, or we can pivot to a data-first AI architecture."
- **The Problem:** "The left side shows the current industry trap. We spend 18 months or more gathering requirements, drawing screens, and building manual workflows. Data is treated as a mere byproduct that falls out at the very end of the pipeline. We do not know if the system can answer higher-value oversight questions until we launch it. That is high-risk, high-cost, and creates more data silos."
- **The Solution:** "The right side is our future state. We do not start with forms. We start with the data. By building a unified data layer first, we feed the mission rules directly into an AI core. Instantly, we unlock automated risk flagging, mission impact visibility, and the ability to answer sudden Congressional queries. The system builds itself around the data, not the other way around."
- **The Close:** "If we want to act as a shared service for other agencies, we must stop building forms. We must start delivering outcomes. This architecture is how we do it."

Would you like to turn this into a short video script or a one-page executive summary handout?

### Policy & Service Alignment

This case study is grounded in federal service and data requirements that shape FEMA program delivery:

- **GPRA Modernization Act of 2010:** Mandates quarterly performance assessments to ensure mission goals are actively measured and met.
- **Open Data Policy (M-13-13):** Directs FEMA to manage information as a continuous asset and publish open, machine-readable data for transparency.
- **Paperwork Reduction Act:** Requires public comment and OMB approval before collecting customer satisfaction survey data used to improve program delivery.

These mandates reinforce the need for a service model that supports reliable data, measurable outcomes, and reduced burden.

---

## My Role

**Service Design Lead**

I worked across product, engineering, program, and policy stakeholders to identify gaps, secure buy-in, and shape a prototype path that aligned service design with product performance.

- Identified **systemic service gaps** across application, review, and funding workflows
- Secured stakeholder buy-in and aligned the effort with **product performance metrics** and mission outcomes
- Led design for a prototype built on **"collect once, reuse everywhere"** principles
- Led **user research planning and synthesis** with applicants, program staff, and grants managers
- Directed **contractor design reviews** and aligned design work to service outcomes
- Translated insights into **backlog priorities, ticket grooming, and delivery strategy**
- Framed the initiative as a better employee experience: reduced time, increased happiness, and greater confidence
- Navigated product, engineering, and policy constraints to move work forward

---

## The Problem

The system aimed to standardize the application experience across programs.

Due to program complexity and eligibility variability:

- Applications were rebuilt or reconfigured annually through a workbook-driven model
- Users re-entered similar data across programs
- Unstructured fields and attachments were used as workarounds for program variability
- Program workflows remained siloed
- Data was not interoperable across programs

**Result:**  
Consistent interface, but inconsistent and non-reusable data.

---

## Key Insight

> **Consistent interface ≠ consistent data**

Workarounds for variability increased:

- Applicant burden
- Manual review effort
- Data inconsistency
- Risk in funding and oversight decisions

Oversight findings reinforce the pattern: disparate systems, limited interoperability, labor-intensive manual processes, and limited cross-program reporting capability.

---

## Before → After

### Before: Current State

This storyboard shows the current service-delivery experience before the data-centered shift.

1. **Applicant begins the process** with a form built around a specific program application.
2. **Context is lost between programs** as the user moves from one application to the next.
3. **The same information is re-entered repeatedly,** because each program workbook creates its own silo.
4. **Review teams work from unstructured inputs and attachments,** generating manual interpretation and extra effort.
5. **Oversight is fragmented,** because the data is not reusable or connected across the service.
6. **Staff spend hours reconciling Excel dashboards and manual exports** instead of trusting a single system of record.

**Impact:**

- Increased review time
- Inconsistent data quality
- Limited oversight visibility
- Reduced confidence in cross-program reporting
- Delayed decisions caused by dashboard reconciliation

---

### After: Service Design Direction

- Data-centered service model
- Single **applicant + project record**
- Structured, reusable data across programs
- Program overlays instead of separate applications
- Reduced reliance on unstructured inputs
- Integration with authoritative data sources where reliable
- A trusted system of record that replaces Excel dashboard reconciliation
- National outcomes tracking that supports confident performance measurement

**Impact:**

- Reduced duplicate entry and rework
- Reduced manual review effort
- Improved data consistency
- Increased cross-program visibility
- Faster decisions and more confident outcomes
- Better support for oversight and decision-making

---

## UI-First Design vs Data Product Model

The current delivery model often begins with the interface, which can make the experience appear improved while leaving the underlying service and data architecture unchanged. This comparison shows why shifting to a data-first model is the better path for grant-making service outcomes.

*Data product visual: how structured data enables reusable service layers and AI-enabled decision support.*

### Current UI-First Model

**UI → Form → Unstructured Data → Manual Review → Limited Insight**

### Future Data Product Model

**Structured Data → Reusable Data Layer → Grant-Making Service → AI-Enabled Decision Support**

> AI is not the starting point. It is enabled by structured, reliable data.

---

## 90-Day Mitigation Plan

**Objective:** Improve mitigation grant-making capability through targeted, data-centered changes.

### Phase 1 — Diagnose & Align

- Map mitigation workflows for HMGP / BRIC
- Identify duplication and data gaps
- Audit unstructured fields, attachments, and workbook-driven configurations
- Align stakeholders on the top service and data opportunities

### Phase 2 — Pilot Improvements

- Define a minimum viable data model for mitigation projects
- Reduce unstructured inputs and attachments where structured fields can work
- Pilot within one mitigation workflow, such as property-level projects or buyouts
- Add backlog items for pre-population, validation, and reuse

### Phase 3 — Scale & Enable

- Expand reuse across workflows
- Enable basic cross-project reporting
- Demonstrate reduced review effort and improved visibility
- Position the model for future AI-enabled validation, triage, and decision support

---

## Change Leadership & Constraints

### Challenges

- Inconsistent data models across programs and legacy systems
- Resistance to change and ownership dynamics
- Culture of limited data sharing across program boundaries
- Product backlog focused on application-level improvements rather than service transformation
- Engineering focus on delivery and infrastructure rather than service/data outcomes
- Limited resources with AI product and data strategy expertise
- External data reliability constraints, including variability in SAM.gov data quality
- Private sector reuse of federal data without strong accountability or feedback loops

### Approach

- Align the solution to **SES-level priorities**: oversight, accountability, transparency, and outcomes
- Position the work as a **leadership capability**, not a design critique
- Introduce incremental change through pilots rather than a full system redesign
- Tie developer efficiency to better data structures and reduced annual rework
- Build the data foundation before introducing advanced AI capabilities

---

## Why This Matters

The system can report on activity, but struggles to answer higher-value oversight and outcome questions:

- How many projects were funded across programs?
- Where was funding distributed?
- What types of projects were funded?
- Are national preparedness goals being met?
- Can leadership answer Congressional data calls with confidence?

These are **data interoperability and service design challenges**, not interface problems.

---

## Full Maturity Vision: Federated National Grants Ecosystem

Today, federal grant management is fractured. Systems track basic activities but fail to answer executive questions about ROI, national preparedness, and strategic impact. These are data interoperability and service design failures — not cosmetic interface issues — and isolated agency platforms cannot solve them.

The future state transforms your agency from a siloed funder into the premier shared-services hub for federal grant intelligence and administration. By solving the root data challenges, we do not just fix our own oversight gaps; we create a scalable, secure utility that other struggling agencies can adopt. This eliminates redundant government spending and provides the Presidency, Congress, and the public with a single, clear picture of national investment outcomes.

### The Four Pillars of Future State Success

#### 1. Command-Level Visibility & Executive ROI

- Today: Leaders operate in the dark, struggling to map funding to specific project types, geographies, and national preparedness goals.
- Future State: An executive dashboard powered by pure data interoperability. Leadership can trace every dollar from Congressional appropriation to community impact in real time.
- Success Metric: Answering a complex Congressional data call with 100% confidence in minutes, not weeks.

#### 2. The Multi-Agency Shared Service Hub

- Today: Peer agencies independently waste millions building redundant, subpar grant management systems that cannot communicate with one another.
- Future State: Your agency operates as a centralized Grant Management Shared Service. Other agencies offload administrative burdens by plugging directly into your optimized infrastructure.
- Success Metric: Reducing duplicative federal IT spend by onboarding at least two external agency partners within the first phase.

#### 3. Unified Service Design for Grantees

- Today: States, tribes, and local governments are drowning in the administrative burden of navigating dozens of different federal application portals.
- Future State: A frictionless, standardized experience for fund recipients. By sharing our service design with other agencies, we create a predictable, unified front door for federal aid.
- Success Metric: Shifting local partner focus from 60% paperwork to 90% direct community mission execution.

#### 4. Continuous Compliance & Audit Readiness

- Today: Agencies face high risks of improper payments and hostile Inspector General audits due to manual tracking and disconnected systems.
- Future State: Automated compliance guardrails and standardized reporting natively built into the shared platform.
- Success Metric: Zero high-risk audit findings across all participating partner agencies.

This is full maturity: a BIG impact that leadership can confirm as a win.

---

## Takeaway

> Improving the form improves the experience.  
> Improving the grant-making system improves the outcome.

This work demonstrates how service design enables **measurable, outcome-driven public sector performance** by connecting user experience, data quality, operational efficiency, oversight, and mission outcomes.
