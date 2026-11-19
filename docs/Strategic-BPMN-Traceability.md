# Strategic BPMN - Traceability Matrix

**Module:** UFCFTR-30-3 Distributed and Enterprise Software Development (Task 1, Sprint 2)
**Case study:** Bristol Regional Food Network - Digital Marketplace

This matrix traces each major business process to the stakeholders and requirements behind it, the Business Process Analysis (the Notion page "Major Business Processes and Responsibilities"), and where it appears in the strategic BPMN model. It also shows which functionality or scope area each process belongs to.

> Exported from the group's Notion board. Notion remains the working copy; update this file when the matrix changes. The strategic BPMN diagram is `Strategic_BPMN.png` on the Notion page.

## Matrix

| # | Business process | Functionality / scope | Stakeholders | Requirements | Strategic BPMN match | Coverage | Note |
|---|---|---|---|---|---|---|---|
| 1 | Product listing and publication | F1 - Listing and Verification | Producers, Certificate Verification, Customers | Producer Adding Product | No direct match in current diagram | No direct match | |
| 2 | Inventory and seasonal availability | F2 - Inventory and Seasonal Availability | Customers, Producers | Producer Editing Product Info | No direct match. Related task: Validate Order (Marketplace > System Automation) | No direct match | Order validation uses availability information. Detailed rules belong in the operational BPMN. |
| 3 | Organic-certification verification | F1 - Listing and Verification | Producers, Certificate Verification | Product Certificate Authenticator | Verify Certificate (Verification pool) | Partial | |
| 4 | Customer ordering | Wider Marketplace | Customers, Producers | Consumer able to Buy Products; Multi-Vendor Baskets | Place an order (Customer pool); Validate Order and Split Multi Vendor Orders (Marketplace > System Automation) | Covered at strategic level | |
| 5 | Order preparation and delivery/collection coordination | Wider Marketplace | Producers, Customers, Delivery Service | Producer view incoming Orders; System must provide producers 48 hours' notice to prepare orders; Customers must be informed about delivery/collection information | Order Received and Accept and Prepare Orders (Producer pool); Communication delays and Deliver Updates (Marketplace > Customer Service); Receive Delivery or Collection information (Customer pool) | Covered at strategic level | Does not show the 48-hour minimum lead time. |
| 6 | Payments and producers settlement | Wider Marketplace | Customers, Producers, Payment Providers | Payment; System must provide weekly payments to producers; System must provide transparent financial audit trails | Trigger payment request and Payment received? (Marketplace > System Automation); Apply 5% commission, Generate Audit Trail and Weekly Settlements (Marketplace > Finance); Receive Payment Settlements (Producer) | Covered at strategic level | |
| 7 | Food quality and traceability | Wider Marketplace | Customers, Producers | None linked | Customer queries and quality issues (Marketplace pool > Customer Service lane) | Partial | |
| 8 | Sustainability - Food miles | Wider Marketplace | Producers, Customers | None linked | No direct match | No direct match | |
| 9 | Surplus produce and discounts | Wider Marketplace | Producers, Customers | None linked | No direct match | No direct match | |
| 10 | Community Information | Wider Marketplace | Producers, Customers | None linked | No direct match | No direct match | |

## Coverage summary

| Coverage | Count | Processes |
|---|---|---|
| Covered at strategic level | 3 | Customer ordering; Order preparation and delivery/collection coordination; Payments and producers settlement |
| Partial | 2 | Organic-certification verification; Food quality and traceability |
| No direct match | 5 | Product listing and publication; Inventory and seasonal availability; Sustainability - Food miles; Surplus produce and discounts; Community Information |

## Requirement reference

Requirements as recorded on the Sprint 1 Requirements board (all currently Draft).

| ID | Requirement | MoSCoW | Type | Stakeholders |
|---|---|---|---|---|
| 1 | Producer Adding Product | Must | Functional | Producers |
| 2 | Producer Editing Product Info | Must | Functional | Producers |
| 3 | Product Certificate Authenticator | Must | Functional | Certificate Verification |
| 4 | Consumer able to Buy Products | Must | Functional | Customers |
| 5 | Payment | Must | Functional | Payment Providers |
| 6 | Multi-Vendor Baskets | Must | Functional | Customers, Producers |
| 7 | Producer view incoming Orders | Must | Functional | Producers |
| 8 | System must provide producers 48 hours' notice to prepare orders | Must | Non-Functional Q | Producers |
| 9 | System must provide weekly payments to producers | Must | Functional | Producers, Payment Providers |
| 10 | System must provide transparent financial audit trails | Must | Not set | Producers, Developers |
| 11 | The product management interface must be intuitive and easy for producers with limited technical knowledge | Must | Non-Functional Q | Producers, Developers |
| 12 | Customers must be able to browse products | Must | Not set | Customers |
| 13 | Products must be categorised | Must | Not set | Customers |
| 14 | Customers able to search for products | Must | Not set | Customers |
| 15 | Customers must be able to view information about the product | Must | Not set | Customers |
| 16 | Customers must be informed of individual supplier responsibilities | Must | Not set | Customers |
| 17 | Customers must be informed about delivery/collection information | Must | Not set | Customers, Delivery Service |
| 18 | (blank row on the board) | | | |
