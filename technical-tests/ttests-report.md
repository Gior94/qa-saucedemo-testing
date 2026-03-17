# Technical Test Cases

## Technical Test Case 1

Title:
Confirm added products stay in the cart after refreshing the page

Steps:
1. Login to https://saucedemo.com
2. Add 2 product to the cart
3. Open DevTools > tab Application > Local Storage
4. Find 'cart-contents'
5. Verify product ID appears
6. Delete one of them and refresh

Expected Result:
Cart icon should shows number 1 and Local Storag shoul keep the product ID of the item that wasn't deleted.

Execution Result: PASS
Cart shows one product and Local Storage updates and keeps the ID of the keeped product

## Technical Test Case 2

Title:
Verify if the system logs out the user if the token session is modified or deleted

Steps:
1. Login to https://www.saucedemo.com
2. Open DevTools > tab Applcation > Cookies
3. Find the cookie 'session-username' and erase it (right click > Delete)
4. Refresh the page

Expected Result:
The system should detect that credentials are missing and redirect the user to the login form page

Execution Result: PASS
The system identified correctly the missing credentials and redirected to the login form page

## Technical Test Case 3

Title:
Ensure there are no failed requests and the page weight is optimized

Steps:
1. Login to https://www.saucedemo.com
2. Open DevTools > tab Network
3. Active filter 'All' and mark 'Disable cache'
4. Refresh the page
5. Check the 'Status' column and the summary in the bottom bar

Expecting Result:
All the requests should keep the Status '200 ok' and it should takes less than 2 seconds in a steady connectio

Execution Result: PASS
All the requests are '200 ok' and it took less than 10 ms
