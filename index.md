---
layout: default
title: From Waste to Worth
---

[Deliverables](#deliverables-and-schedule)   –   [Problem](#the-problem)   –   [Goals](#what-the-system-should-achieve)   –   [Team](#team)   –   [Updates](#project-updates)

# Getting surplus campus food to food banks before it expires

We are Group 3 in CSC 375 at the University of Victoria. This term we are analyzing and designing a system that helps UVic food services record edible surplus food, match it with food banks and community organizations, and arrange pickup in time.

**Our client** is the UVic Campus Food Recovery Program, which coordinates donations from participating campus food services to approved recipient organizations. Two members of our team represent the client. The other four form the analyst team.

## Deliverables and schedule

<!-- To update: upload the PDF next to index.md, turn the name into a link, and change the status. -->

| Deliverable | Due | Status |
|---|---|---|
| [Request for Proposal](RFP.pdf) | Sep 27 | Submitted |
| [Project Charter](Project_Charter.pdf) | Oct 5 | Submitted |
| Project website | Oct 7 | This page |
| Requirements | Oct 11 | **Due next** |
| Use cases | Oct 25 | Upcoming |
| Data model | Nov 1 | Upcoming |
| Process model | Nov 8 | Upcoming |
| UI prototype | Nov 15 | Upcoming |
| Final report | Nov 22 | Upcoming |
| Final presentation | Nov 23 | Upcoming |

## The problem

Prepared food that is still safe to eat often has only hours of usable life left. Today, campus food services arrange donations by phone, email and in person. There is no shared record of what is available, who has accepted it, or whether it was picked up, so when one step is missed, the food is thrown out.

### Why not use FoodRescue.ca?

FoodRescue.ca, run by Second Harvest, matches individual food businesses with registered non-profits across Canada. Our system covers the work inside one institution: recording surplus at several campus outlets, applying the same eligibility and food safety checks, assigning pickups to the program's own drivers, and keeping one set of records for reporting. FoodRescue.ca can stay one of the channels the client uses.

## How a donation moves through the system

1. **Record:** food-service staff enter the food type, quantity, pickup location and pickup window.
2. **Check and match:** the donation passes an eligibility and food safety check and is offered to approved recipients.
3. **Pickup:** a driver collects the food and confirms delivery in the system.
4. **Track and report:** the donation gets a final status, and the record feeds into monthly reporting.

## What the system should achieve

| Goal | Target |
|---|---|
| Record surplus food quickly and consistently, with an eligibility check before anything is offered | A listing takes under 3 minutes, and every listing is checked before it reaches recipients |
| Connect food services with recipients, who accept or decline available donations | 90% of donations get an answer within 30 minutes of posting |
| Coordinate pickup and delivery, with drivers confirming each step in the system | 90% of accepted donations are picked up within 2 hours |
| Track every donation from posting to completion and report on it | Every donation ends with a recorded final status, and a monthly report in kg comes straight from the system |

## Scope

**This project covers**

- Analysis of the redistribution process for selected UVic food services
- Requirements and use cases
- Data and process models
- A UI prototype
- A final report and presentation

**It does not cover**

- Building or deploying a working system
- Locations outside the UVic campus
- Community members using the system directly
- Selling donated food

## Team

| Name | Role | Side |
|---|---|---|
| Marissa Bumagat | Project Manager | Client |
| Bowen Zhang | System Analyst | Client |
| Iris Ho | Project Manager | Analyst team |
| Michal Dvoracek | System Analyst | Analyst team |
| Artan Abdolrahimzadeh | Data Analyst | Analyst team |
| Jonathan Luelfesmann | System Developer | Analyst team |

## Project updates

- **Oct 6:** Named our client and set measurable targets for each project goal. Both will go into the next revision of the Project Charter.
- **Oct 5:** Submitted the Project Charter and published this website.
- **Oct 2:** Received RFP feedback: name the client, compare our idea with FoodRescue.ca, and base the constraints on food safety, donor liability and privacy.
- **Sep 27:** Submitted the Request for Proposal.
- **Sep 26:** On the professor's advice, narrowed the scope from restaurant chains to UVic food services.
- **Sep 22:** Chose food redistribution as our project and split the RFP sections.
- **Sep 17:** Pitched two ideas to the class: a personal health history roadmap and a food waste redistribution system.

---

CSC 375 Systems Analysis, University of Victoria, Fall 2026. Instructor: Niloofar G. Larimi. A student analysis and design project; no working system is deployed.
