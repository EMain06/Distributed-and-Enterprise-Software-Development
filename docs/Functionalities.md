 ### Section 1: Selected Functionalities

The group is working with Use Case 1: Producer Listing and Inventory Management. We have picked 2 major functionalities from the use case.

#### F1: Listing and Verification

A producer needs to be able to submit new product details with all the fields that come with that, like (name, price, category, quantity, availability period, farm origin, allergens, best-before date, organic status).

The system then checks if the details provided by the producer are valid. If not, then they are returned back to the producer in order to refill and resubmit.

If the product is marked organic by the producer, then it must pass a verification service externally.

The process should also consider what happens if the external verification service is unavailable or validation fails.

Once everything is done, the product is published to the customers.

#### F2: Inventory and Seasonal Availability Management

A producer updates stock quantity or seasonal dates.

When the stock is finished, the product is marked unavailable for purchase.

When stock is replenished and the product is still in season, the system marks it available again.

#### Why we picked them

Both are from Use Case 1.

Each one runs a complete process end to end, with auto form check, decision points, data being stored and an error path.

Both will be reused in the final product for Task 2.

### Section 2: F1 Listing and Verification Scope

**Starts:** Producer submits new product.

**Steps:**
- The system checks all the fields are filled and valid.
- If the product is marked as organic, it is checked by an external service.
- Then the product is published to the marketplace.

**Errors:**
- Missing or invalid details are sent back to producer to fix.
- If the organic verification fails, the producer is notified and the product is not published as organic.
- If the verification service is out, the check is retried and then passed to the admin for manual verification.

**Ends:** The product is either live or rejected; it has only 2 states.

### Section 3: F2 Inventory and Seasonal Availability Scope

**Starts:** A producer updates stock quantity or seasonal dates.

**Steps:**
- The system checks if the update is valid.
- The new stock and dates are saved.
- The system then checks the season and the stock to mark product as available or unavailable.

**Errors:**
- Invalid updates (e.g. negative stock, end date before start date) are sent back to the producer.
- Restocked but out of season products: the product is marked unavailable.

**Ends:** The product has 2 states, available or unavailable.