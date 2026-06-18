# Requirements Traceability Matrix (RTM)
### e-Bike Rental Startup — Requirements Life Cycle Management

---

| Field | Details |
|---|---|
| **Document Title** | Requirements Traceability Matrix (RTM) |
| **Version** | v1.0 |
| **Date** | May 2026 |
| **Author** | Omkar Vartak, Business Analyst |
| **BABOK Area** | Requirements Life Cycle Management |
| **Technique** | Requirements Traceability |
| **Status** | Baseline |

---

## 1. Purpose

This RTM establishes a formal link between each elicited requirement and its originating stakeholder, MoSCoW priority classification, current lifecycle status, and implementation notes. It serves as the **single source of truth** for requirement tracking throughout the e-Bike Rental Startup project lifecycle.

---

## 2. Scope & Coverage

- **Total requirements tracked:** 31 (REQ-01 to REQ-28 + REQ-X1, REQ-X2, REQ-X3)
- **Requirements sourced from:** Structured stakeholder interviews — Tourists & Visitors, Corporate Employees & Enterprises, Business Owners
- **Priority classification sourced from:** MoSCoW Prioritization Register v1.0
- **Current status:** Post-MoSCoW sign-off baseline — all active requirements Approved; Won't Have requirements Deferred

---

## 3. Prioritization Summary

| Must Have | Should Have | Could Have | Won't Have |
|---|---|---|---|
| 16 Requirements | 11 Requirements | 1 Requirement | 3 Requirements |

---

## 4. Status Legend

| Status | Definition |
|---|---|
| **Approved** | Reviewed, prioritized via MoSCoW, and signed off. Ready to enter sprint backlog. |
| **In Development** | Actively being built in the current sprint. |
| **In Testing** | Implementation complete, undergoing QA or UAT. |
| **Verified** | Tested, validated, and confirmed delivered. |
| **Deferred** | Out of scope for current release. Logged for future roadmap. |
| **Cancelled** | Permanently removed from scope. |

---

## 5. Requirements Traceability Matrix

| Req ID | Description | Requirement Detail | Stakeholder | MoSCoW | Status | Comments |
|---|---|---|---|---|---|---|
| REQ-01 | Real-time bike map | The system shall allow users to locate nearby available e-bikes on a real-time map via a mobile application. | Tourists & Visitors | 🔴 Must Have | ✅ Approved | Core entry point of user journey. Requires GPS and IoT integration. |
| REQ-02 | App-based unlock/lock | The system shall allow users to unlock and lock e-bikes via the mobile app using QR code or NFC scan. | Tourists & Visitors | 🔴 Must Have | ✅ Approved | Critical for contactless, self-service bike access. |
| REQ-03 | Multiple pricing models | The app shall support multiple pricing models — hourly, daily, monthly subscription, and tourist packages. | Tourists & Visitors, Corporate | 🟠 Should Have | ✅ Approved | Flexible pricing drives adoption across all segments. |
| REQ-04 | GPS route navigation | The app shall provide GPS-integrated route navigation and guided tourist routes at key destinations. | Tourists & Visitors | 🔴 Must Have | ✅ Approved | Essential for tourist segment unfamiliar with local routes. |
| REQ-05 | Multilingual interface | The app shall support multilingual interface including Hindi and regional Indian languages. | Tourists & Visitors | 🟠 Should Have | ✅ Approved | Increases accessibility for domestic tourists and non-English users. |
| REQ-06 | Battery level display | The system shall display real-time battery charge level of each available e-bike before booking. | Tourists & Visitors, Corporate | 🔴 Must Have | ✅ Approved | Prevents mid-ride stranding. Depends on IoT sensor integration. |
| REQ-07 | Low battery alert | The system shall send automated alerts when battery level falls below a defined threshold during a ride. | Tourists & Visitors | 🔴 Must Have | ✅ Approved | Safety and reliability feature. Threshold to be defined during design. |
| REQ-08 | Digital payment support | The app shall support digital payment methods including UPI, credit/debit cards, and digital wallets. | Tourists & Visitors, Corporate | 🔴 Must Have | ✅ Approved | Mandatory for cashless operations. Payment gateway partner TBD. |
| REQ-09 | Pre-booking slot | The system shall allow users to pre-book an e-bike for a future time slot at a specific docking station. | Tourists & Visitors, Corporate | 🔵 Could Have | ✅ Approved | Deferred to post-launch sprint. Useful for planned travel and corporate use. |
| REQ-10 | Ride history & cost summary | The app shall allow users to view and download their ride history, cost summary, and distance travelled. | Corporate, Business Owners | 🟠 Should Have | ✅ Approved | Supports B2B expense reporting and employee accountability tracking. |
| REQ-11 | B2B admin dashboard | The system shall provide a B2B admin dashboard to manage employee subscriptions, usage limits, and fleet utilisation. | Corporate, Business Owners | 🔴 Must Have | ✅ Approved | Core B2B value proposition. Required for enterprise client onboarding. |
| REQ-12 | Corporate SSO integration | The system shall support integration with corporate employee ID systems or SSO for seamless login. | Corporate Employees | 🟠 Should Have | ✅ Approved | Reduces onboarding friction for large enterprise deployments. |
| REQ-13 | Monthly B2B invoicing | The system shall generate monthly consolidated invoices for B2B clients with itemised trip details per employee. | Business Owners | 🔴 Must Have | ✅ Approved | Eliminates manual reimbursement processing. Requires billing module. |
| REQ-14 | Real-time GPS tracking (B2B) | The B2B dashboard shall provide real-time GPS tracking of all active employee rides for business owners. | Business Owners | 🔴 Must Have | ✅ Approved | Directly addresses business owner concern on field team visibility. |
| REQ-15 | Per-employee usage caps | The system shall allow B2B admins to set per-employee daily distance or usage caps. | Business Owners | 🟠 Should Have | ✅ Approved | Control mechanism for B2B dashboard. Prevents cost overruns per employee. |
| REQ-16 | Sustainability reports | The system shall generate sustainability reports (fuel saved, CO₂ offset, distance) for corporate CSR reporting. | Corporate Employees | 🟠 Should Have | ✅ Approved | Supports corporate green targets. Data feeds from IoT ride metrics. |
| REQ-17 | Docking station map | The system shall display all active charging and docking station locations with real-time availability. | Tourists & Visitors, Corporate | 🔴 Must Have | ✅ Approved | Enables end-to-end ride planning from pickup to drop-off. |
| REQ-18 | Station deployment strategy | Docking and charging stations shall be deployed at tourist hotspots, metro hubs, IT parks, and commercial zones. | All Stakeholder Groups | 🔴 Must Have | ✅ Approved | Physical infrastructure requirement. Requires city-level permits and partnerships. |
| REQ-19 | IoT maintenance alerts | The system shall trigger automated maintenance alerts when a bike reports a fault or low battery via IoT sensors. | Corporate, Business Owners | 🔴 Must Have | ✅ Approved | Ensures fleet uptime and prevents service disruption for B2B clients. |
| REQ-20 | Helmet & safety gear | Each e-bike shall be equipped with a helmet and basic safety gear available at the docking station. | Tourists & Visitors, Corporate | 🟠 Should Have | ✅ Approved | Reduces liability risk and builds user confidence. Ops team to manage inventory. |
| REQ-21 | 60-second unlock SLA | The mobile app shall have a maximum booking-to-unlock time of under 60 seconds. | Tourists & Visitors | 🟠 Should Have | ✅ Approved | UX performance benchmark. To be validated during load testing phase. |
| REQ-22 | 99.5% platform uptime | The platform shall maintain 99.5% uptime with guaranteed SLA for B2B enterprise clients. | Business Owners | 🔴 Must Have | ✅ Approved | Non-negotiable for B2B trust. Downtime prevents bike unlocking entirely. |
| REQ-23 | Data security & compliance | All user payment and personal data shall be encrypted and compliant with relevant data protection regulations. | All Stakeholder Groups | 🔴 Must Have | ✅ Approved | Legal and compliance requirement. Must align with IT Act and PCI-DSS standards. |
| REQ-24 | Android & iOS support | The app shall be available on Android and iOS platforms, supporting OS versions from the last 4 years. | All Stakeholder Groups | 🔴 Must Have | ✅ Approved | Ensures widest possible user reach across smartphone market segments. |
| REQ-25 | 2-hour breakdown SLA | Breakdown replacement for a faulty bike shall be guaranteed within 2 hours under the B2B SLA agreement. | Business Owners | 🟠 Should Have | ✅ Approved | Addresses business owner reliability concern. Requires ops team SLA framework. |
| REQ-26 | 30-day B2B pilot programme | The startup shall offer a 30-day free pilot for B2B clients with cost-saving analytics at the end of the trial. | Business Owners | 🟠 Should Have | ✅ Approved | Key B2B acquisition strategy. Report to include ROI and cost savings data. |
| REQ-27 | Hotel & hospitality tie-ups | The startup shall establish hospitality tie-ups to enable e-bike bookings through hotel concierge or OTA platforms. | Tourists & Visitors | 🟠 Should Have | ✅ Approved | Channel partnership strategy. Requires API integration with hotel booking systems. |
| REQ-28 | Tourist combo packages | The startup shall offer flat-rate hourly tourist bundles at popular tourist zones as a distinct pricing tier. | Tourists & Visitors | 🔴 Must Have | ✅ Approved | Differentiates product in tourist market. Bundle pricing to be defined by business team. |
| REQ-X1 | White-label platform | White-label or co-branded e-bike platform customisation for franchise or hospitality partners. | Business Owners | ⚫ Won't Have | ⏸ Deferred | High development effort, low launch priority. Revisit in future roadmap. |
| REQ-X2 | Gamification & loyalty | In-app gamification or loyalty rewards programme for frequent riders. | General Users | ⚫ Won't Have | ⏸ Deferred | Deferred to post-growth phase. Consider after user base reaches scale. |
| REQ-X3 | OTA platform integration | Integration with third-party OTA platforms such as MakeMyTrip or Booking.com for tourist bundling. | Tourists & Visitors | ⚫ Won't Have | ⏸ Deferred | Complex third-party dependency. Revisit in Year 2 product roadmap. |

---

## 6. BA Notes

- All 28 active requirements (REQ-01 to REQ-28) carry **Approved** status, reflecting sign-off after the MoSCoW prioritization exercise. In a live project, status updates sprint-by-sprint.
- REQ-X1, REQ-X2, and REQ-X3 are formally **Deferred** — retained in the RTM for audit trail purposes.
- Requirement IDs are consistent across all project documents ensuring full horizontal traceability.
- Comments column captures key dependencies, risks, and assumptions feeding into solution design and test planning.

---

## 7. Next Steps (Agile Context)

| Action Item | Owner | Timeline |
|---|---|---|
| Convert Must Have requirements into Sprint 1 User Stories | Business Analyst | Sprint 1 |
| Map RTM requirements to test cases for QA planning | BA + QA Lead | Sprint 1–2 |
| Update RTM status as requirements move to In Development | Business Analyst | Each Sprint |
| Re-evaluate Deferred requirements at quarterly roadmap review | BA + Product Owner | Quarter 2 |
| Conduct stakeholder review of RTM for formal sign-off | BA + Project Sponsor | Sprint 2 |

---

## 8. Version History

| Version | Date | Author | Changes |
|---|---|---|---|
| v1.0 | May 2026 | Omkar Vartak | Initial RTM created post MoSCoW prioritization |

---

*This document is part of the e-Bike Rental Startup BA Case Study Portfolio.*
*BABOK Knowledge Area: Requirements Life Cycle Management | Technique: Requirements Traceability Matrix*
*Repository: https://shorturl.at/AYGsu *
