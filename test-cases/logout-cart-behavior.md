# Session Logout Test Cases

## Test Case SDQA-8

Title:
Verify cart behavior after logout

Steps:
1. Login to https://www.saucedemo.com
2. Go to inventory page
3. Add item to cart
4. Logout
5. Login again

Expected Result:
Cart behavior should follow system rules (persist or reset)

Execution result:
Cart keeps the products even after logout
