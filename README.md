# SNC — Interior-Design Studio CRM & Operations Platform

I built this for **SNC**, an interior-design and construction studio, as a one-man team — design, build and deploy — driven end to end through agentic AI workflows. It's the system the studio runs on: the lead pipeline, BOQ quotations with a client portal, project delivery with its own client portal, a material master, procurement, discovery-call scheduling, HR & incentives, and letterhead / PDF generation — all in one place.

The screenshots are from a demo build — dummy data and a placeholder brand stand in for the studio's real branding, client PII and statutory identifiers (GST / PAN / DIN), all of which I keep out of the public repo.

*The source is in a private repo; glad to walk a serious reviewer through it on request.*

---

## What it does

**Lead pipeline, two tracks.** Every enquiry runs down either the Turnkey or the Virtual Design pipeline, with lead scoring (Hot / Warm / Cold), SLA tracking, qualification, source attribution and task templates.

**BOQ quotations.** Build a detailed bill-of-quantities quote from a lead (sections, rate items, materials, margins, payment milestones), preview it as a branded proposal, and share a client portal where the client reviews, messages, and accepts or declines — with an audit trail.

**Project delivery.** A won quote becomes a project with milestones, tasks, snags, payment tracking and a client portal for progress and file exchange.

**Material & rate masters.** A 100+ item material catalogue across trades (civil, carpentry, HVAC, tiling, hardware…), BOQ items and sections, with default vendors and margins.

**Procurement.** Contractors, material suppliers, vendor/contractor bids and service contracts.

**Discovery calls & e-meet.** Schedule and track discovery calls (public booking page, Google-Meet links) through booked → attended.

**HR & operations.** Staff, roles & permissions, attendance & salary, incentive dashboards, internal tasks, communication templates, and a letterhead / PDF generator.

---

## Screenshots

### Command centre
![Dashboard](screenshots/d01-dashboard.png)

### Lead pipeline
**Leads** — Turnkey & Virtual Design pipelines with scoring and SLA
![Leads](screenshots/d02-leads.png)
**Lead detail** — brief, property, scoring, tasks and activity
![Lead detail](screenshots/d03-lead-detail.png)

### Quotations & the client portal
**Quotations** ![Quotations](screenshots/d04-quotations.png)
**Proposal preview** — the branded BOQ proposal (deliverables, pricing, T&C, revision matrix)
![Quotation preview](screenshots/d05-quotation-preview.png)
**Quotation builder** — assemble the quote from sections, rate items and materials
![Quotation builder](screenshots/d06-quotation-builder.png)
**Client quotation portal** — what the client sees to review and accept
![Quotation portal](screenshots/d21-quotation-portal.png)

### Projects & the client portal
**Projects** ![Projects](screenshots/d07-projects.png)
**Project detail** ![Project detail](screenshots/d08-project-detail.png)
**Client project portal** — progress, timeline, resource upload and team contact
![Project portal](screenshots/d22-project-portal.png)

### Masters & procurement
**Materials** — 100+ item catalogue across trades ![Materials](screenshots/d10-materials.png)
**Contractors** ![Contractors](screenshots/d11-contractors.png)
**Material suppliers** ![Suppliers](screenshots/d12-material-suppliers.png)
**Service contracts** ![Service contracts](screenshots/d19-service-contracts.png)
**Payment milestones** ![Payment milestones](screenshots/d16-payment-milestones.png)

### Scheduling, HR & ops
**Discovery calls & e-meet** ![Discovery calls](screenshots/d13-discovery-calls.png)
**Internal tasks** ![Internal tasks](screenshots/d09-internal-tasks.png)
**Staff members** ![Staff](screenshots/d14-staff-members.png)
**HR operations** ![HR operations](screenshots/d15-hr-operations.png)
**Communications** ![Communications](screenshots/d17-communications.png)
**Letterhead generator** ![Letterhead](screenshots/d18-letterhead.png)
**Users & roles** ![Users & roles](screenshots/d20-users-roles.png)

### HR gamification, scheduling & the BOQ engine
**Incentive dashboard** — a points scoreboard (month / quarter / cumulative) with a payout ledger; points convert to paid leave or cash
![Incentive dashboard](screenshots/d23-incentive-dashboard.png)

**Discovery-call calendar** — a drag-to-reschedule calendar that re-notifies the client
![Discovery calendar](screenshots/d24-discovery-calendar.png)

**BOQ rate library** — the seeded rate-item catalogue every quotation is built from
![BOQ rate library](screenshots/d25-boq-rate-library.png)

**Virtual Design deliverables** — the tiered VD deliverable catalogue (essential / premium / bespoke)
![VD deliverables](screenshots/d26-vd-deliverables.png)

**Lead configuration** — funnels, sources, assignment rules, SLA targets, task templates, site-survey templates
![Lead configuration](screenshots/d29-lead-configuration.png)

### Mobile
| Incentive dashboard | Discovery calendar | BOQ rate library | VD deliverables | Lead config |
|---|---|---|---|---|
| ![](screenshots/m23-incentive-dashboard.png) | ![](screenshots/m24-discovery-calendar.png) | ![](screenshots/m25-boq-rate-library.png) | ![](screenshots/m26-vd-deliverables.png) | ![](screenshots/m29-lead-configuration.png) |

| Dashboard | Leads | Lead detail | Quotations | Proposal |
|---|---|---|---|---|
| ![](screenshots/m01-dashboard.png) | ![](screenshots/m02-leads.png) | ![](screenshots/m03-lead-detail.png) | ![](screenshots/m04-quotations.png) | ![](screenshots/m05-quotation-preview.png) |

| Projects | Materials | Discovery calls | Quotation portal | Project portal |
|---|---|---|---|---|
| ![](screenshots/m06-projects.png) | ![](screenshots/m07-materials.png) | ![](screenshots/m08-discovery-calls.png) | ![](screenshots/m09-quotation-portal.png) | ![](screenshots/m10-project-portal.png) |

---

## Tech
Laravel 13 · Filament 5 · Livewire · Alpine.js · Tailwind CSS 4 · MySQL · PHP 8.4 · PDF generation · role-based access control

---
Developed by **[@abBytes-sudo](https://github.com/abBytes-sudo)** for SNC · abhimasih0505@gmail.com · +91 73039 37702
