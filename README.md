# Katalon Studio UI Automation for saucedemo.com

This project aims to automate the user interface (UI) testing of the website [www.saucedemo.com](https://www.saucedemo.com/) using Katalon Studio. The automation script covers various scenarios, including login, adding items to the cart, verifying the summary cart, filling checkout information, checking the checkout overview, and ensuring a successful transaction.

## Scenarios

1. **Login:** The script logs in to the website using the credentials obtained from the footer's first username and password fields. These credentials are then stored in global variables for further use during the test execution.

2. **AddtoCart:** The script retrieves the price of the items listed under the "Sauce Labs Backpack" category and stores it in a global variable. It then adds the item to the cart.

3. **SummaryCart:** This scenario verifies the summary cart to ensure that the item name and price match the previously added item.

4. **CheckOutInformation:** The script fills the checkout information based on the data stored in the global variables. This step includes providing shipping details, such as name, address, and payment information.

5. **CheckOutOverview:** This scenario checks the checkout overview to confirm that the item and its price match the item added to the cart. Additionally, it ensures that the total number of items displayed corresponds to the total items added.

6. **CheckOutComplete:** The script verifies the completion of the transaction by checking for the presence of specific elements and the success message.

## Tools Used

- Katalon Studio: Katalon Studio is an integrated test automation tool that provides a comprehensive solution for web, API, mobile, and desktop application testing.
