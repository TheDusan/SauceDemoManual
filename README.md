# Manual Testing for SauceDemo.com

This repository contains manual testing documentation for the website **https://www.saucedemo.com**. The tests cover the following core functionalities:

## Functionalities Tested

### 1. **Login Functionality**
Tests the behavior of the login process with valid and invalid credentials.  
- **Valid login**: Verifies that the user can successfully log in with the correct username and password.
- **Invalid login**: Verifies that the system prevents login with incorrect credentials (either username or password).
- **Empty fields**: Verifies that the system shows appropriate error messages when the username or password field is left empty.

### 2. **Inventory Page**
Tests the functionality and display of products on the inventory page after a successful login.  
- **Product display**: Ensures that products are displayed correctly.
- **Product details**: Verifies that product images, descriptions, and prices are visible and match the expected data.
- **Interaction**: Tests the ability to interact with the products (e.g., selecting, adding to cart).

### 3. **Cart Functionality**
Tests the behavior of the shopping cart after adding products.  
- **Add to cart**: Verifies that items can be added to the cart.
- **View cart**: Ensures that the cart displays the correct products, quantities, and prices.
- **Remove from cart**: Verifies that products can be removed from the cart.

### 4. **Checkout Functionality**
Tests the entire checkout process from cart to payment.  
- **Proceed to checkout**: Verifies that the user can navigate to the checkout page from the cart.
- **Order summary**: Ensures that the order summary displays accurate product details, total price, and customer information.
- **Complete purchase**: Verifies that the checkout process can be completed successfully and that the user receives a confirmation.

## Bug Reports
If any bugs or issues are discovered during testing, they will be documented and reported.  
The **bug reports** will include:
- **Detailed descriptions** of the issue encountered.
- **Screenshots** illustrating the issue.
- **Video recordings** demonstrating the issue in action.

The bug reports can be found in the `bug-reports` section of this repository.

## Getting Started

To begin manual testing:
1. Clone this repository to your local machine.
2. Follow the instructions for each functionality to reproduce the tests.
3. Report any issues discovered in the `bug-reports` section.

## Tools Used
- **Browser**: Microsoft Edge (used for testing).
- **Website**: [SauceDemo](https://www.saucedemo.com).

## Conclusion

This repository serves as the documentation for the manual testing process conducted on the SauceDemo website. It covers critical aspects of the login process, inventory management, shopping cart, and checkout functionality to ensure that all features work as expected.

