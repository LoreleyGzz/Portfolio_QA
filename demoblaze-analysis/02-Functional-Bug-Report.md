Title: [Functional] Purchase form allows processing orders with past or invalid dates.

Steps to Reproduce:
  1.- Navigate to https://www.demoblaze.com/.
  2.- Add any product to the shopping cart.
  3.- Click "Cart" in the navigation bar.
  4.- Click the "Place Order" button.
  5.- Fill in all mandatory fields in the form (Name, Country, etc.).
  6.- In the "Month" field, enter 1.
  7.- In the "Year" field, enter 1990.
  8.- Click the "Purchase" button.

Expected Result: The page should reject the transaction, display a clear error message to the user (e.g., "The entered date is invalid"), and highlight the "Month" and "Year" fields for correction.

Actual Result: The page accepts the purchase order and displays a confirmation message, despite the invalid date entered.

Evidence: 
https://docs.google.com/document/d/13yZH4cDIEl9BsE_GiWdE9vqBLXUpHz1RyKoyKi8Fyig/edit?tab=t.0
