# Order & Supply Chain Operations Analytics

## Project Status

In progress

## Project Overview


This project demonstrates how business analysis, process improvement, and data visualization can be used to improve order visibility and proactively manage delivery risks.
## Business Scenario

A regional operations team manages customer orders across multiple APAC markets.

The existing process relies on several disconnected reports and manual follow-ups. As a result, stakeholders often identify delivery risks too late, order status updates are inconsistent, and operations teams spend significant time consolidating information from different sources.

The objective of this project is to design an order-risk monitoring solution that helps operations teams:

- Identify potentially delayed orders earlier
- Understand the main causes of delivery risk
- Prioritize high-impact cases
- Improve communication between sales, supply planning, logistics, and customer operations
- Reduce manual reporting effort
 ## Problem Statement

The regional operations team lacks a consistent and proactive way to monitor delivery risk across customer orders.

Order information is distributed across multiple reports, while status updates and follow-up actions depend heavily on manual coordination. This makes it difficult to identify high-risk orders early, understand the causes of delay, and prioritize the cases with the greatest customer or business impact.

The project aims to design a structured order-risk monitoring approach that improves visibility, supports faster decision-making, and reduces manual reporting effort.

## Success Metrics


| Stakeholder | Primary Responsibilities | Key Needs | Typical Decisions |
|---|---|---|---|
| Sales | Manage customer expectations and commercial relationships | Clear delivery status, customer impact, and escalation updates | Whether to communicate delays or renegotiate commitments |
| Supply Planning | Balance demand, inventory, and production availability | Demand priorities, supply gaps, and allocation risks | How to allocate limited supply and adjust planning priorities |
| Logistics | Coordinate shipment execution and transportation | Shipment readiness, carrier status, and logistics exceptions | Whether to expedite, reroute, or escalate a shipment |
| Customer Operations | Monitor orders and coordinate cross-functional follow-up | Consolidated order status, risk reasons, and action owners | Which orders require immediate follow-up |
| Operations Manager | Oversee service performance and operational risk | KPI trends, major risks, unresolved issues, and team workload | Where to prioritize resources and escalate systemic problems |
## Stakeholder Analysis

Different stakeholders require different levels of detail.

Sales needs concise customer-impact information, while supply planning and logistics require more detailed operational data. Operations managers need aggregated KPIs, major risks, and unresolved actions.

The proposed solution should therefore provide both:

- An executive-level summary for decision-makers
- A detailed operational view for teams responsible for follow-up
## RACI Matrix

RACI defines how responsibilities are assigned across key activities:

- **R — Responsible:** Performs the work
- **A — Accountable:** Owns the final outcome
- **C — Consulted:** Provides input before a decision or action
- **I — Informed:** Receives updates

| Activity | Sales | Supply Planning | Logistics | Customer Operations | Operations Manager |
|---|---|---|---|---|---|
| Monitor order status and delivery risks | I | C | C | R | A |
| Validate supply-related risk reasons | I | R | C | C | A |
| Validate shipment and transportation status | I | C | R | C | A |
| Prioritize high-impact customer orders | C | C | C | R | A |
| Assign and track follow-up actions | I | C | C | R | A |
| Communicate delivery risks to customers | R | C | C | C | A |
| Approve major escalation or exception handling | C | C | C | R | A |
| Review operational KPIs and recurring issues | I | C | C | R | A |
## Responsibility Design Notes

The matrix is designed to avoid unclear ownership and duplicated follow-up.

Customer Operations is responsible for consolidating information and coordinating daily actions, while the Operations Manager remains accountable for overall service performance and major escalations.

Supply Planning and Logistics are responsible for validating risks within their respective areas. Sales owns customer communication but should base updates on confirmed operational information.
## Business Questions

- Which orders are at risk of late delivery?
- What are the main causes of fulfillment delays?
- Which products, regions, or process stages require attention?
- How can stakeholders receive earlier and clearer risk signals?

## Planned Deliverables

- Business problem statement
- Stakeholder map
- Current-state process map
- KPI framework
- Synthetic dataset
- Power BI dashboard
- Root cause analysis
- Business recommendations

## Data Privacy

This project uses synthetic data only. No confidential company or customer information is included.
