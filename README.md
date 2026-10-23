# Construction & Interior Design Firm — CRM / ERP

**Status:** deployed May 2026 on SNC's own domain; team rollout pending.
**My role:** requirements and an AI-assisted build (I direct AI coding agents; I don't hand-code).
**▶ [Interactive demo](https://abbytes-sudo.github.io/interior-design-crm-showcase/)** · source in a private repo; walkthrough on request.

SNC is a New Delhi construction and interiors firm. This CRM/ERP is designed to bring the studio's quoting and project delivery into one system: a two-track lead pipeline, BOQ quotations with a client portal, project delivery with its own client portal, a material master, procurement, discovery-call scheduling, HR & incentives, and letterhead / PDF generation. It was built over about two months.

**What's in place**
- BOQ quotations priced from SNC's rate card: a 569-item rate library in 33 sections.
- A won quote becomes a project plan (tasks and milestones) in one step (verified once on the production install).
- Client portals for quotes and for projects.

Screenshots are from a demo build: a placeholder brand ("abBytes", not a real company), fictional people and placeholder numbers, addresses and statutory IDs. Layouts and flows match the deployed system.

---

## What it does

**Lead pipeline, two tracks.** Each enquiry follows either the Turnkey or the Virtual Design pipeline, with lead scoring (Hot / Warm / Cold), SLA tracking, qualification, source attribution and task templates.

**BOQ quotations.** Build a detailed bill-of-quantities quote from a lead (sections, rate items, materials, margins, payment milestones), preview it as a branded proposal, and share a client portal where the client reviews, messages, and accepts or declines, with an audit trail.

**Project delivery.** A won quote becomes a project with milestones, tasks, snags, payment tracking and a client portal for progress and file exchange.

**Material & rate masters.** The 569-item BOQ rate library (33 sections) and a material catalogue across trades (civil, carpentry, HVAC, tiling, hardware…), with default vendors and margins.

**Procurement.** Contractors, material suppliers, vendor/contractor bids and service contracts.

**Discovery calls & e-meet.** Schedule and track discovery calls (public booking page, Google Meet links) from booked to attended.

**HR & operations.** Staff, roles & permissions, an attendance & salary sheet, incentive dashboards, internal tasks, communication templates, and a letterhead / PDF generator.

---

## Screenshots

*The lead list, lead detail, quote builder, project detail, discovery-call list, salary sheet, user list and the two client-portal screens are left out of this write-up until they are re-captured from fully masked demo data.*

### Command centre
![Dashboard: points this month, this year and all time, tasks due this week and active leads](screenshots/d01-dashboard.jpg)

### Quotations
![Quotations list with status per quote](screenshots/d04-quotations.jpg)

### Projects
![Projects list](screenshots/d07-projects.jpg)

### Masters & payments
**Materials**: catalogue across trades
![Materials master with purchase, sell and margin](screenshots/d10-materials.jpg)
**Payment milestones**
![Payment milestones per track](screenshots/d16-payment-milestones.jpg)

*Contractor, supplier and service-contract screens are left out of this public write-up because they list vendor contacts.*

### HR & ops
**Internal tasks**
![Internal tasks list](screenshots/d09-internal-tasks.jpg)
**Staff members**
![Staff members with roles, codes and designations](screenshots/d14-staff-members.jpg)
**Communications**
![Communication templates](screenshots/d17-communications.jpg)
**Letterhead generator**
![Letterhead generator](screenshots/d18-letterhead.jpg)

### Incentives, scheduling & the BOQ engine
**Incentive dashboard**: a points scoreboard (month / quarter / cumulative) and a payout log; designed so points can convert to paid leave or cash
![Incentive dashboard with scoreboard and payout log](screenshots/d23-incentive-dashboard.jpg)

**Discovery-call calendar**: drag a booked call to a new slot and the client is emailed the new time
![Discovery-call calendar, week view](screenshots/d24-discovery-calendar.jpg)

**BOQ rate library**: SNC's rate card as a 569-item, 33-section library that turnkey quotes price from (costs are masked in this screenshot)
![BOQ rate library, costs masked](screenshots/d25-boq-rate-library.jpg)

**Virtual Design deliverables**: the tiered VD deliverable catalogue (essential / premium / bespoke)
![Virtual Design deliverables catalogue](screenshots/d26-vd-deliverables.jpg)

**Lead configuration**: funnels, sources, assignment rules, SLA targets, task templates, site-survey templates
![Lead configuration: task templates per stage with SLA](screenshots/d29-lead-configuration.jpg)

### Mobile
| Incentive dashboard | Discovery calendar | BOQ rate library | VD deliverables | Lead config |
|---|---|---|---|---|
| ![Mobile: incentive dashboard](screenshots/m23-incentive-dashboard.jpg) | ![Mobile: discovery calendar](screenshots/m24-discovery-calendar.jpg) | ![Mobile: BOQ rate library](screenshots/m25-boq-rate-library.jpg) | ![Mobile: VD deliverables](screenshots/m26-vd-deliverables.jpg) | ![Mobile: lead configuration](screenshots/m29-lead-configuration.jpg) |

| Dashboard | Quotations | Projects | Materials |
|---|---|---|---|
| ![Mobile: dashboard](screenshots/m01-dashboard.jpg) | ![Mobile: quotations](screenshots/m04-quotations.jpg) | ![Mobile: projects](screenshots/m06-projects.jpg) | ![Mobile: materials](screenshots/m07-materials.jpg) |

---

## Tech
Laravel 13 · Filament 5 · Livewire · Alpine.js · Tailwind CSS 4 · MySQL · PHP 8.4 · PDF generation · role-based access control

---
Developed by **[@abBytes-sudo](https://github.com/abBytes-sudo)** for SNC

© 2026 Abhishek Anand Masih. Write-up and screenshots shared for portfolio review; not licensed for reuse.
