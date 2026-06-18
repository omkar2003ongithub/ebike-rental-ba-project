# Requirements Prioritization — MoSCoW Technique
### e-Bike Rental Startup — Requirements Life Cycle Management

---

| Field | Details |
|---|---|
| **Document Title** | Requirements Prioritization — MoSCoW |
| **Version** | v1.0 |
| **Date** | May 2026 |
| **Author** | Omkar Vartak, Business Analyst |
| **BABOK Area** | Requirements Life Cycle Management |
| **Technique** | MoSCoW Prioritization |
| **Status** | Baseline |

---

## 1. Purpose

This document presents the prioritized requirements for the e-Bike Rental Startup using the **MoSCoW technique** — a standard requirements prioritization method under the BABOK Requirements Life Cycle Management knowledge area.

Requirements were elicited through structured stakeholder interviews across three groups — Tourists & Visitors, Corporate Employees & Enterprises, and Business Owners — and are categorized here to guide Agile sprint planning and product roadmap decisions.

---

## 2. MoSCoW Technique Overview

| Category | Label | Definition |
|---|---|---|
| 🔴 | **Must Have** | Critical for launch. The product cannot go live without these. Non-delivery means project failure. |
| 🟠 | **Should Have** | Important requirements that add significant value but are not launch-blocking. Delivered in early sprints post-launch. |
| 🔵 | **Could Have** | Desirable features that enhance the product but can be deferred without impacting core functionality. |
| ⚫ | **Won't Have** | Explicitly out of scope for the current release. May be reconsidered in future roadmap cycles. |

---

## 3. Prioritization Summary

| Must Have | Should Have | Could Have | Won't Have |
|---|---|---|---|
| 16 Requirements | 11 Requirements | 1 Requirement | 3 Requirements |

---

## 4. MoSCoW Prioritization Register

---

### 🔴 Must Have — Critical for Launch

| # | Req ID | Requirement | Category | Source |
|---|---|---|---|---|
| 1 | REQ-01 | The system shall allow users to locate nearby available e-bikes on a real-time map via a mobile application. | Functional — App | Tourist |
| 2 | REQ-02 | The system shall allow users to unlock and lock e-bikes via the mobile app using QR code or NFC scan. | Functional — App | Tourist |
| 3 | REQ-04 | The app shall provide GPS-integrated route navigation and guided tourist routes at key destinations. | Functional — App | Tourist |
| 4 | REQ-06 | The system shall display real-time battery charge level of each available e-bike before booking. | Functional — App | Tourist · Corporate |
| 5 | REQ-07 | The system shall send automated alerts to users when battery level falls below a defined threshold during a ride. | Functional — App | Tourist |
| 6 | REQ-08 | The app shall support digital payment methods including UPI, credit/debit cards, and digital wallets. | Functional — App | Tourist · Corporate |
| 7 | REQ-11 | The system shall provide a B2B admin dashboard allowing organisations to manage employee subscriptions, set usage limits, and view fleet utilisation. | Functional — B2B | Corporate · Business |
| 8 | REQ-13 | The system shall generate monthly consolidated invoices for B2B clients with itemised trip details per employee. | Functional — B2B | Business |
| 9 | REQ-14 | The B2B dashboard shall provide real-time GPS tracking of all active employee rides for business owners. | Functional — B2B | Business |
| 10 | REQ-17 | The system shall display locations of all active charging and docking stations on the app map with real-time availability. | Functional — Operations | Tourist · Corporate |
| 11 | REQ-18 | Docking and charging stations shall be deployed at tourist hotspots, metro/bus transit hubs, IT parks, and commercial zones. | Business | All groups |
| 12 | REQ-19 | The system shall trigger automated maintenance alerts for fleet operations when a bike reports a fault or low battery via IoT sensors. | Functional — Operations | Corporate · Business |
| 13 | REQ-22 | The platform shall maintain 99.5% uptime with guaranteed SLA for B2B enterprise clients. | Non-Functional | Business |
| 14 | REQ-23 | All user payment and personal data shall be encrypted and compliant with relevant data protection regulations. | Non-Functional | All groups |
| 15 | REQ-24 | The app shall be available on both Android and iOS platforms and support devices running OS versions from the last 4 years. | Non-Functional | All groups |
| 16 | REQ-28 | The startup shall offer tourist combo packages — flat-rate hourly bundles at popular tourist zones — as a distinct pricing tier. | Business | Tourist |

---

### 🟠 Should Have — High Value, Post-Launch Priority

| # | Req ID | Requirement | Category | Source |
|---|---|---|---|---|
| 1 | REQ-03 | The app shall support multiple pricing models — hourly, daily, monthly subscription, and tourist packages. | Functional — App | Tourist · Corporate |
| 2 | REQ-05 | The app shall support multilingual interface including Hindi and regional Indian languages. | Functional — App | Tourist |
| 3 | REQ-10 | The app shall allow users to view and download their ride history, cost summary, and distance travelled. | Functional — App | Corporate · Business |
| 4 | REQ-12 | The system shall support integration with corporate employee ID systems or SSO for seamless login. | Functional — B2B | Corporate |
| 5 | REQ-15 | The system shall allow B2B admins to set per-employee daily distance or usage caps. | Functional — B2B | Business |
| 6 | REQ-16 | The system shall generate sustainability reports (fuel saved, CO₂ offset, distance travelled) for corporate CSR reporting. | Functional — B2B | Corporate |
| 7 | REQ-20 | Each e-bike shall be equipped with a helmet and basic safety gear available at the docking station. | Business | Tourist · Corporate |
| 8 | REQ-21 | The mobile app shall have a maximum booking-to-unlock time of under 60 seconds for a seamless user experience. | Non-Functional | Tourist |
| 9 | REQ-25 | Breakdown replacement for a faulty bike shall be guaranteed within 2 hours under the B2B SLA agreement. | Non-Functional | Business |
| 10 | REQ-26 | The startup shall offer a 30-day free pilot programme for B2B clients with cost-saving analytics at end of trial. | Business | Business |
| 11 | REQ-27 | The startup shall establish hospitality and hotel tie-ups to enable e-bike bookings through hotel concierge or OTA platforms. | Business | Tourist |

---

### 🔵 Could Have — Desirable, Deferrable

| # | Req ID | Requirement | Category | Source |
|---|---|---|---|---|
| 1 | REQ-09 | The system shall allow users to pre-book an e-bike for a future time slot at a specific docking station. | Functional — App | Tourist · Corporate |

---

### ⚫ Won't Have — Out of Scope for Current Release

| # | Req ID | Requirement | Category | Source |
|---|---|---|---|---|
| 1 | REQ-X1 | White-label or co-branded e-bike platform customisation for individual franchise or hospitality partners. | Business | Business |
| 2 | REQ-X2 | In-app gamification or loyalty rewards programme for frequent riders. | Functional — App | General |
| 3 | REQ-X3 | Integration with third-party OTA platforms such as MakeMyTrip or Booking.com for tourist package bundling. | Business | Tourist |

---

## 5. BA Notes & Prioritization Rationale

- **REQ-01** (Real-time bike map) is Must Have — it is the entry point of the entire user journey. Without it, users cannot access the service at all.
- **REQ-22** (99.5% platform uptime SLA) is Must Have — downtime directly prevents bike unlocking and breaks B2B client trust instantly. Uptime is a foundational non-functional requirement.
- **REQ-10** (Ride history & cost summary) is elevated to Should Have — it directly supports corporate expense management and B2B reporting, key drivers of enterprise adoption.
- **REQ-15** (Per-employee usage caps) is elevated to Should Have — without this, the B2B admin dashboard (REQ-11, Must Have) lacks a critical control mechanism explicitly requested by business owners.
- **REQ-09** (Pre-booking) is Could Have — useful for planning ahead but not required for the core ride-and-go experience at launch.
- Won't Have requirements are not permanently rejected — they are deferred to future sprint cycles and will be re-evaluated at each quarterly roadmap review.

---

## 6. Next Steps (Agile Context)

| Action Item | Owner | Timeline |
|---|---|---|
| Map Must Have requirements to Sprint 1 backlog | Business Analyst | Sprint 1 |
| Create User Stories for all Must Have and Should Have items | Business Analyst | Sprint 1 |
| Review prioritization with project stakeholders for sign-off | BA + Project Lead | Sprint 1 |
| Build Requirements Traceability Matrix (RTM) | Business Analyst | Sprint 2 |
| Re-evaluate Could Have items at Sprint 3 retrospective | BA + Product Owner | Sprint 3 |

---

## 7. Version History

| Version | Date | Author | Changes |
|---|---|---|---|
| v1.0 | May 2026 | Omkar Vartak | Initial baseline document created |

---

*This document is part of the e-Bike Rental Startup BA Case Study Portfolio.*
*BABOK Knowledge Area: Requirements Life Cycle Management | Technique: MoSCoW Prioritization*
*Repository: [GitHub Repo Link]*
