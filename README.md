<p align="center">
  <img src="docs/assets/khelgrid-banner.svg" alt="KHELGRID: Every ground. Every opportunity." width="100%">
</p>

# KHELGRID

KHELGRID is a planning tool for district sports officers. It looks at the grounds, coaches and timeslots a district already has and works out a weekly coaching schedule that reaches more players, especially in areas that get left out today.

We are starting with Lucknow district. This repo holds our public website. The live link will go here once it is deployed.

**Status:** idea stage, built for the AI Kaushal Hackathon 2026 (use case: AI Playground and Sports Facility Optimizer).

## How it works

The officer enters what they have: facilities, which coaches are free and when, what each coach is qualified for, and how much demand there is in each area. KHELGRID uses Google OR-Tools (CP-SAT) to find the best schedule that follows the rules. A coach can't be in two places at once, can't teach a sport they aren't qualified for, and a venue that is closed for safety never gets a session.

The officer then sees the new plan next to the current one and decides whether to approve it.

In a test week with made-up data, the solver planned 2,082 player-slots against 1,482 from a simple nearest-coach schedule, and raised coverage in the rural area from 36% to 100%.

## What we are building

- **Command**: the officer's map, scenario settings and plan comparison
- **Sports Hub**: a public page to find facilities by sport and area, with links to official portals like Khelo India and Khel Saathi
- **This website**: the story of the project, in English and Hindi

## Team

**Task Force 141**, DYS HEALTHTECH PRIVATE LIMITED

<table>
  <tr>
    <td align="center"><img src="docs/assets/team/devanshu.jpg" width="150" alt="Devanshu Sharma"><br><b>Devanshu Sharma</b><br>CTO</td>
    <td align="center"><img src="docs/assets/team/yagnik.jpg" width="150" alt="Yagnik Sharma"><br><b>Yagnik Sharma</b><br>CEO, team lead</td>
    <td align="center"><img src="docs/assets/team/sameeksha.jpg" width="150" alt="Sameeksha"><br><b>Sameeksha</b><br>COO</td>
  </tr>
</table>

KHELGRID is an independent project and is not affiliated with any government body.
