# User Stories - Campus Cafeteria Ordering

## Group Information
- **Group Number:** G03
- **Module:** Campus Cafeteria Ordering
- **Group Label:** team-03
- **Product Owner:** Mian Habib Ullah
- **Story Writer:** Mian Habib Ullah
- **Task Planner:** Mian Habib Ullah
- **Tester:** Mian Habib Ullah
- **Reviewer:** Mian Habib Ullah

---

## US-01 - View the cafeteria menu

### User Story
As a student,
I want to view the cafeteria menu,
so that I can see what food is available before I reach the cafeteria.

### Acceptance Criteria
- [ ] The menu page lists all food items.
- [ ] Each item shows its name, price and category.
- [ ] A food item that is out of stock is marked Unavailable.

### Technical Tasks
- [ ] Design the menu page layout.
- [ ] Create the food item data (name, price, category, availability).
- [ ] Implement the function that loads and displays the menu.
- [ ] Show Unavailable for out-of-stock items.
- [ ] Test the menu with available and unavailable items.

### Story Information
- **Priority:** High
- **Assignee:** habibch46
- **Status:** Backlog
- **Labels:** `type:user-story`, `team-03`

### Definition of Done
- [ ] All acceptance criteria are satisfied.
- [ ] The assigned tester has verified the story.
- [ ] Another group member has reviewed the work.
- [ ] The team has recorded the required evidence.

---

## US-02 - Search or filter food items

### User Story
As a student,
I want to search or filter food items,
so that I can find the food I want quickly.

### Acceptance Criteria
- [ ] The student can enter a complete or partial food name in a search box.
- [ ] The student can filter items by category.
- [ ] The system displays No items found when nothing matches.

### Technical Tasks
- [ ] Design the search box and filter options.
- [ ] Implement search by food name.
- [ ] Implement the category filter.
- [ ] Display the matching items or the No items found message.
- [ ] Test valid, partial and invalid search values.

### Story Information
- **Priority:** Medium
- **Assignee:** habibch46
- **Status:** Backlog
- **Labels:** `type:user-story`, `team-03`

### Definition of Done
- [ ] All acceptance criteria are satisfied.
- [ ] The assigned tester has verified the story.
- [ ] Another group member has reviewed the work.
- [ ] The team has recorded the required evidence.

---

## US-03 - Add items to the cart

### User Story
As a student,
I want to add food items to a cart,
so that I can order several items together.

### Acceptance Criteria
- [ ] Every available item has an Add to Cart button.
- [ ] The cart shows the name, quantity and price of each item.
- [ ] The cart total updates when an item is added or removed.
- [ ] An unavailable item cannot be added to the cart.

### Technical Tasks
- [ ] Design the cart page.
- [ ] Implement the add to cart function.
- [ ] Implement quantity change and remove item.
- [ ] Calculate the cart total.
- [ ] Test adding, removing and unavailable items.

### Story Information
- **Priority:** High
- **Assignee:** habibch46
- **Status:** Backlog
- **Labels:** `type:user-story`, `team-03`

### Definition of Done
- [ ] All acceptance criteria are satisfied.
- [ ] The assigned tester has verified the story.
- [ ] Another group member has reviewed the work.
- [ ] The team has recorded the required evidence.

---

## US-04 - Place an order

### User Story
As a student,
I want to place an order for the items in my cart,
so that my food is prepared before I reach the cafeteria.

### Acceptance Criteria
- [ ] The student can place an order only when the cart has at least one item.
- [ ] The system shows an order summary before the order is confirmed.
- [ ] After confirmation, the system shows an order number.
- [ ] If an item in the cart becomes unavailable, the system tells the student and removes it before the order is placed.

### Technical Tasks
- [ ] Design the order summary screen.
- [ ] Implement the place order function.
- [ ] Validate that the cart is not empty.
- [ ] Generate an order number.
- [ ] Re-check item availability before the order is placed.
- [ ] Test an empty cart, a valid order and an unavailable item.

### Story Information
- **Priority:** High
- **Assignee:** habibch46
- **Status:** Backlog
- **Labels:** `type:user-story`, `team-03`

### Definition of Done
- [ ] All acceptance criteria are satisfied.
- [ ] The assigned tester has verified the story.
- [ ] Another group member has reviewed the work.
- [ ] The team has recorded the required evidence.

---

## US-05 - View the order status

### User Story
As a student,
I want to view the status of my order,
so that I know when to collect my food.

### Acceptance Criteria
- [ ] The student can see the order number and its status.
- [ ] The status is one of Received, Preparing or Ready.
- [ ] The status changes when the cafeteria staff update the order.

### Technical Tasks
- [ ] Design the order status screen.
- [ ] Define the status values.
- [ ] Implement the function that reads an order status by order number.
- [ ] Update the display when the status changes.
- [ ] Test each status value.

### Story Information
- **Priority:** Medium
- **Assignee:** habibch46
- **Status:** Backlog
- **Labels:** `type:user-story`, `team-03`

### Definition of Done
- [ ] All acceptance criteria are satisfied.
- [ ] The assigned tester has verified the story.
- [ ] Another group member has reviewed the work.
- [ ] The team has recorded the required evidence.

---

## Change Challenge Response
- **Affected User Story:** US-04
- **New Requirement:** A food item becomes unavailable after a student has added it to the cart.
- **Updated Acceptance Criterion:** If an item in the cart becomes unavailable, the system tells the student and removes it before the order is placed.
- **New or Updated Task:** Re-check the availability of every cart item before the order is placed.

## Peer Review
- **Reviewed By Group:** G04
- **User role is clear:** Yes
- **User value is clear:** Yes
- **Acceptance criteria are testable:** Yes
- **Missing condition:** US-03 does not say what happens when a student adds more items than the cafeteria has in stock.
- **Recommended improvement:** Add a maximum quantity per item and a criterion that shows a message when the limit is reached.
