# Grocery Shopping and Inventory Management System

## Project Objective
Create a comprehensive grocery shopping and inventory management system that helps users organise, manage, and plan their grocery shopping effectively while also keeping track of their existing inventory of grocery items.

## Project Description
### Purpose
The project aims to provide a tool for users to efficiently manage their grocery lists, keep track of items running low in supply at home, and streamline their grocery shopping experience. Users can easily set up their inventory, manage thresholds, and optimise their shopping lists.

### Features
1. **Adding Items to Shopping List:** Users can easily add grocery items to their shopping list, specifying item names, categories (e.g., fruits, vegetables, household supplies), and quantities to purchase.

2. **Removing Items from Shopping List:** Items can be removed from the shopping list as needed.

3. **Marking Items as Bought:** Users can mark items as "bought" or "not bought" to track their shopping progress. (this will most likely just be with a checklist)

4. **Inventory Management:** Users can set up their inventory, specifying two quantities for each item:
   - **"In Stock" Quantity:** Current quantity on hand.
   - **"Right Supply" Quantity:** Desired quantity they want to have at each given time. (this will be the threshold)
   - **"They also have an option to update other items they do not have in stock:**
   (if they add the items that they do not have in their shopping list, it immediately updates to their inventory and state that it is out of stock, no supply and quantity will be zero)

5. **Inventory Status Indicators:** The app visually indicates the status of each item in the inventory based on the quantities set:
   - "(In Stock) (Right Supply)" indicates the item is currently in stock at the right amount.
   - "(In Stock) (High Supply)" indicates the item is in stock, and the quantity exceeds the right amount.
   - "(In Stock) (Low Supply)" indicates the item is in stock, but the quantity is below the right amount.
   - "(Out of Stock) (No Supply)" indicates the item is out of stock (quantity is zero).

6. **Shopping List Integration:** Items that are "(Out of Stock) (No Supply) and (In Stock) (Low Supply)" automatically populate into the shopping list with the "Right Supply" to be purchased. Users can also add items directly to their shopping list, even if they are not in their inventory (This will then be also populated on the inventory after it has been bought under uncategorised - user will add to their correct category).

7. **Shopping Interaction:** During shopping, users can mark items as "Bought" or "Not Bought" in their shopping list (more like they will checklist item and once it has been checklisted it updates to the inventory with quantity). If an item is marked as "Bought," the app updates the inventory quantity accordingly.

8. **Threshold Adjustments:** The app can suggest adjusting the "Threshold" for items based on user shopping habits. Users can choose to update the "Threshold" for specific items. (If users buy more than orbelow the threshold then there will be a suggestion for them to reduce or increase the threshold so that at each point in time they have the right supply of groceries they need. If they do not do so, it remains labeled as out of stock and low supply.)

9. **Regular Inventory Checks:** Users specify how often they shop (e.g., weekly, bi-weekly, monthly). The app sends reminders for users to run an inventory check based on their specified shopping frequency. Midway through their shopping cycle, users receive a reminder to review their inventory against their next shopping day.

### More ideas to enhance the app
- Sorting the items (i mentioned earlier that there will be category) More sorting could include - Alphabetical Sorting, Custom Sorting, Recently Bought Sorting

### Not doing
- I said i will not do the frequently bought because we don't care about them buying frequently boughts what we care about is for them to buy what they need so the most important is are they short in supply or out of stock. This will indicate to them what needs to be bought

### User Guide
- Clear and concise instructions on how to use the app, including setting up the inventory, adjusting thresholds, and using the shopping list will be created
- Tooltips or hints for new users will be included

### Documentation
- This project will be documented on GitHub with a README file explaining how to use the app and any setup instructions.
(It has already being connected to Github as we speak and frequent commits will be done throughout the lifecycle of the development)

## Project Timeline
- The estimated completion time for the basic version of the app is [29th of February, 2024].
- Additional features and improvements can be implemented in subsequent phases.