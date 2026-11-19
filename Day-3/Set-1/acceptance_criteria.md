
# Acceptance Criteria – Online Grocery Delivery

## 1. Browse Grocery Categories

**Scenario: View available categories**

- Given the customer opens the grocery application
- When the customer visits the categories section
- Then the application should display available grocery categories

## 2. Search for Products

**Scenario: Search for an existing product**

- Given the customer is on the product page
- When the customer enters a product name in the search bar
- Then the application should display matching products

## 3. Add Products to Cart

**Scenario: Add an available product**

- Given the customer selects an available product
- When the customer clicks Add to Cart
- Then the product should be added to the cart

## 4. Make Secure Payment

**Scenario: Successful payment**

- Given the customer has items in the cart
- When the customer completes payment successfully
- Then the order should be confirmed

**Negative Scenario: Payment failure**

- Given the customer is making a payment
- When the payment fails
- Then the application should display a payment failure message and should not confirm the order

## 5. View Order Status

**Scenario: Check order status**

- Given the customer has placed an order
- When the customer opens the order tracking section
- Then the application should display the current order status
