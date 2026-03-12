# URL Access Test Cases

## Test Case SDQA-9

Title:
Verify direct access to checkout without login

Steps:
1. Login to https://www.saucedemo.com
2. Navigate to checkout
3. Copy the URL in checkout page
4. Logout from the session
5. Open checkout URL directly without logging in

Expected Result:
User should be redirected to login page.

Execution Result: PASS
The system redirect correctly to login page and an error message was displayed
