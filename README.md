<p align="center">
  <img src="docs/assets/khelgrid-banner.svg" alt="KHELGRID: Every ground. Every opportunity." width="100%">
</p>

# KHELGRID: landing website

**KHELGRID** helps a District Sports Officer get more safe, fair sporting opportunity out of the grounds, coaches and budgets a district already has. It combines constraint optimisation (Google OR-Tools CP-SAT), clear data provenance and human approval.

This repository is the public **Experience** website: the story of the project, moving from India to Uttar Pradesh to Lucknow district, with links into the product.

> **Status: idea stage (November 2026).** The website and product are being built for the 24-hour AI Kaushal Hackathon (8–9 December 2026).
> **Live demo: coming soon.** The deployment link will appear here once it is live.

## What KHELGRID is

| Experience | What it does |
|---|---|
| **Experience** (this repo) | Cinematic, accessible story site with two clear calls to action: *Explore Command* and *Explore Sports Hub* |
| **Command** | The district officer's planning tool: map, KPIs, scenario editor, optimised plan vs baseline, explanations, review and export |
| **Sports Hub** | Public facility discovery and verified resources, with links to official portals |

### How the engine works
1. **Learn constraints:** facilities, coach qualifications and availability, timeslots, demand, budget. Every value carries its source and date.
2. **Optimise:** CP-SAT finds a weekly coaching plan under hard rules: no double-booking, qualified coaches only, travel and rest gaps, budget limits, and **closed or unsafe venues are never used**.
3. **Review:** the officer sees the plan compared with a baseline, with plain reasons, then approves, edits or rejects it. Every decision is logged.

## Planned stack (website)
Next.js + TypeScript, React Three Fiber (lazy-loaded, with a static fallback), Motion, Tailwind / shadcn/ui, English and Hindi, aiming for WCAG 2.2 AA, respecting `prefers-reduced-motion`.

## Honest notes
- **Independent prototype.** This is not an official government website or service. No government integration or endorsement is claimed.
- Any operational numbers shown in demos come from **synthetic (invented) data** and are clearly labelled. They are modelled, not measured, impact.
- Our original mascot, **Captain Khel Singh / कप्तान खेल सिंह**, is a fictional character.

## Team: Task Force 141 · DYS HEALTHTECH PRIVATE LIMITED

| Name | Role |
|---|---|
| Devanshu Sharma | Chief Technology Officer (CTO) |
| Yagnik Sharma | Chief Executive Officer (CEO) · Team lead |
| Sameeksha | Chief Operating Officer (COO) |

---
Built for the **AI Kaushal Hackathon 2026**, use case *AI Playground and Sports Facility Optimizer* (Department of Youth Affairs & Sports).
License: all rights reserved until the team chooses a licence.
