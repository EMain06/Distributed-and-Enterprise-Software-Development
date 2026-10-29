# Major Business Processes and Responsibilities

## Individual Contributions

| Htet Oo Wai | Samuel St Clair | Both |
|---|---|---|
| Product Listing and Publication | Customer Ordering | Other enterprise activities |
| Inventory and Seasonal Availability | Order Preparation and Delivery/Collection Coordination | |
| Organic-certification Verification | Payments and Producer Settlements | |

## Purpose and Scope

The Bristol Regional Food Network marketplace connects local food producers with customers. Its purpose is to make local food easier to buy and reduce the effort involved in coordinating sales across multiple producers.

This analysis identifies the major business activities, participants, responsibilities and connections within the marketplace.

## Product listing and publication

Proposed owner: Htet Oo Wai

| Question | Analysis |
|---|---|
| Purpose | Allow producers to offer products through the marketplace, with sufficient information for customers to understand what is being sold |
| Participants and responsibilities | **Producer**: Submit product details and correct missing or invalid information<br>**Marketplace system**: Validate the submission, request corrections and publish the product once required checks succeed.<br>**Verification Service**: Check organic certification information when the producer submits certification. |
| Information needed | Product name, description, best before/ use by date, category, price, available quantity, availability period, farm origin |
| Main activities | The producer submits product information. The system checks whether required information is present and valid. The producer is asked to correct problems. Organic certification is checked when claimed. Successful completion of the required validation allows publication. |
| Outcome | A product listing in published with validated required information and can be made available to customers with stock and seasonal-availability rules. |
| Connections | • Depends on certification verification when organic certification is claimed.<br>• Shows product information to customer browsing and ordering.<br>• Depends on inventory and seasonal availability to determine order.<br>• Provides product information relevant to food-quality communication. |
| Source | Use case 1, page 1; case study, pages 1-2. |

## Inventory and seasonal availability

Proposed owner: Htet Oo Wai

| Question | Analysis |
|---|---|
| Purpose | Keep product availability accurate so customers do not place new orders for products that are out of stock or outside their availability period. |
| Participants and responsibilities | **Producer**: Update product quantities and seasonal availability.<br>**Marketplace system**: Maintain the updated information and automatically make zero-stock products unavailable for new orders.<br>**Ordering process**: Uses availability information when checking customer orders. |
| Information needed | Product identifier, available quantity and period, comparing availability with the current date |
| Main activities | The producer updates stock or seasonal availability. The system maintains the products’ order availability. When stock reaches zero, the product becomes unavailable for new orders. Replenished stock can become available again if it is still within the seasonal availability period. |
| Outcome | Customers are presented with availability consistent with stock and seasonal information. |
| Connections | • Supports accurate product listings.<br>• Supplies availability information to ordering.<br>• Requires coordination with stock changes from successful orders in the marketplace. |
| Source | Use Case 1, page 1; case study, page 2. |

## Organic-certification verification

Proposed owner: Htet Oo Wai

| Question | Analysis |
|---|---|
| Purpose | Check certification information when a producer claims that a product is organically certified. |
| Participants and responsibilities | **Producer**: Supply certification information and respond to identified problems.<br>**Marketplace system**: Request verification, use the response and handle unsuccessful checks or service unavailability.<br>**External or simulated verification service**: Check the supplied certification information and return a result. |
| Information needed | Organic claim, certificate number, product identifier, certification organization, expiry date |
| Main activities | When organic certification is claimed, the marketplace requests a check. It distinguishes successful verification, unsuccessful verification and an unavailable service. |
| Outcome | The organic claim is checked, or the unresolved condition is identified and handled. Required validation must succeed before publication.<br>Failed verification: Explain the problem and allow the producer to correct the information.<br>Service unavailable: Leave verification unresolved and provide an appropriate time to retry later. |
| Connections | Verification supports product validation and publication. Service unavailability does not equal to invalid verification. |
| Source | Use Case, page 1. |

## Customer ordering

Proposed owner: Samuel St Clair

| Question | Analysis |
|---|---|
| Purpose | Let customers buy and find local products from multiple producers |
| Participants and responsibilities | Customers (families, community groups, business owners, restaurants, cafes) |
| Information needed | Published products with correct information (name, description, category, price, harvest date, farm origin, allergens, best before, use buy), stock levels, seasonal availability periods, customer account details, customer card details, basket contents |
| Main activities | Browse products, browse by category, view product details, add to basked, remove from basket, checkout, system checks stock availability, order created, update stock |
| Outcome | A customer will be able to purchase only available products, when products are out of stock it will be clear. |
| Connections | Relies on: Product listing and inventory - customers can only order products that are in stock and in season<br>Supports: Payments, food and traceability. |
| Source | Use case 1, page 1; case study, pages 1-2. |

## Order preparation and delivery/collection coordination

Proposed owner: Samuel St Clair

| Question | Analysis |
|---|---|
| Purpose | Ensure producers can see incoming orders with a 48 hours lead time, can prepare the order, and each order reaches the customer by the delivery date. |
| Participants and responsibilities | Producers (prepare, package and hand over to driver), the platform itself (send emails/updates for communication to the producer, driver and customer) delivery service |
| Information needed | Producers products ordered (item and quantity), delivery date, delivery or collection, address, customer contact details, best before/use by, allergen information and order status |
| Main activities | notify producer - producer accepts order - prepare products - arrange delivery or collection - deliver product - mark as order fulfilled - update the customer status |
| Outcome | Each order gets fulfilled and the status is recorded |
| Connections | Relies on: customer ordering (triggers payment and sends the order through), product listing and inventory, order preparation, delivery being on time<br>Supports: payments and settlements (once the order is fulfilled we give the money to producer (or a few days after to ensure quality and have a safety net for refunds)) and food quality and traceability.<br>Feeds back to: product listing and inventory |
| Source | Use case 1, page 1; case study, pages 1-2. |

## Payments and producer settlements

Proposed owner: Samuel St Clair

| Question | Analysis |
|---|---|
| Purpose | Take payment securely, split between different producers, calculate service charge. |
| Participants and responsibilities | Customer (pays), external payment service, the platform itself for calculations and records, producers |
| Information needed | Order totals, product prices, 5% commission, payment reference and status, producer pay-out details, settlement period, fulfilment status. |
| Main activities | Payment submitted - stock levels change - calculate amounts split between producer and commission - record transaction - wait for the settlement - weekly settlement pay-out - producer statement |
| Outcome | Paid orders and weekly producer pay-outs with a transparent auditable record |
| Connections | Relies on: customer ordering, product listing and inventory, order preparation<br>Supports: Customer ordering and product listing and inventory |
| Source | Use case 1, page 1; case study, pages 1-2. |

## Other enterprise activities

Proposed owners: Samuel St Clair, Htet Oo Wai

| Area | Purpose and who does that | Information/Outcome | Connections/Questions |
|---|---|---|---|
| Food quality and traceability | Support food safety and communication, producers would declare organic status, allergens and use-by/best-before dates when listing, and also using an external verification to get a organic verification when the certification is claimed. | Records linking customers, products and producers<br>Outcome: traceable products and the ability to contact affected customers quickly | |
| Sustainability | Report the networks environmental impact, the platform can calculate food miles using postcode based distances. | Producers origin postcode and customer postcode would give food mile figures | • Ask with the group about sustainability |
| Surplus produce and discounts | Producers communicate surplus availability and offer last-minute discounts to reduce food waste. | Information: Surplus product, quantity, discounted price and offer availability.<br>Outcome: Customers can discover discounted surplus food. | Connects to the listings, inventory and ordering, clarify how last-minute offers interact with preparation time |
| Community Information | Producers share seasonal recipes, storage guidance and farm stories to support food education and community connections. | Information: Producer-written recipes, guidance and stories.<br>Outcome: Customers can learn about recipes and more information on how to handle food safely. | |

## Questions and proposed decisions

*(Inline Notion database with columns: Questions, Proposed answer, Status. No rows were returned.)*
