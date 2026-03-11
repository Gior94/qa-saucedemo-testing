# Checkout Test Cases

## Test Case SDQA-4

Title:
Chekout process allows purchase with empty cart

Environment:
MacOS Tahoe 26.1
Chrome Browser

Steps:
1. Login to https://www.saucedemo.com
2. Do not any products to the cart
3. Navigate to cart
4. Click "Checkout"
5. Enter checkout information
6. Click "Continue"
7. Click "Finish"

Expected Result:
The system should prevent checkout when the cart is empty or display a message indicating the cart has no items.

Execution Result: FAIL
The system allows the checkout process to complete with no items or a total of $0.00
