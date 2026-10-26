### Section 1:
Selected functionalities

The group is working with Use Case 1: Producer Listing and Inventory Management. We have picked 2 major functionalities from the use case.

F1: Listing and Verification

A producer needs to be able to submit new product details with all the fields that come with that, like (name, price, category, quantity, availability period, farm origin, allergens, best-before date, organic status).

should also consider what happens if the external verification service is unavailable or validation fails.

The system then checks if the details provided by the producer are valid. If not, then they are returned back to the producer in order to refill and resubmit.

If the product is marked organic by the producer, then it must pass a verification service externally.

Once everything is done, the product is published to the customers.

F2: Inventory and Seasonal Availability Management

A producer updates stock quantity or seasonal dates.

When the stock is finished, the product is marked unavailable for purchase.

When stock is replenished, the system marks it available again.

Why I picked them

Both from Use Case 1.

Each one runs a complete process end to end, with auto form check, decision points, data being stored and an error path.

Both will be reused in the final product for Task 2.