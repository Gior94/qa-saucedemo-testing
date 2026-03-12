# Checkout Test Cases

## Test Case SDQA-10

Title:
Verify checkout cannot be submited multiple times

Steps:
1. Login to https://www.saucedemo.com
2. Add some products to the cart
3. Go to checkout page to complete the fields
4. Click "Finish" multiple times quickly

Expected Result:
System should prevent duplicate order submissions.

Execution Result: PASS
The system complete the checkout process correctly with no duplicated order submissions. It redirects instantly to the order confirmation page.
