Bug ID SDQA-4

Title:
Checkout process allows purchase with empty cart

Environment:
MacOS Tahoe 26.1
Chrome browser (V 145.0.7632.160)

Steps to reproduce:
1. Navigate to https://www.saucedemo.com
2. Login with valid credentials
3. Do not add any products to the cart
4. Navigate to the cart page
5. Click "Checkout"
6. Enter checkout information
7. Click "Continue"
8. Click "Finish"

Expected Result:
The system should prevent the cart when the cart is empty.

Actual Result:
The system allows the checkout process to complete with no products and a total of $0.00
