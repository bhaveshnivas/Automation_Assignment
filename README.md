The automation assignment is done in two ways:
1. UI Automation is done for the Ecommerce Website (i.e) Searching a product and adding to cart till checkout page
2. API Automation is done from Option 2 in the Assignment given (i.e) Testing the CRUD operations for an opensource endpoint APIs

# UI Automation:
## This framework is built using Selenium in Python
## Steps:
Run the python file using "python c:/Users/{Username}/{Porjectdirectory}/pythonProject/UI-automation/uitest.py"
1. First launch the Chrome webdriver.
2. Seach for the searchbox and Provide the Productname to be searched
3. Click on the Search button
4. Store all the details of the product like product_name, product_price, product_link into respective variables
5. Click on the first link
6. Navigate the driver to the newly opened window
7. Click on Add to Cart button
8. Click on Buy Now option
9. Verify the checkout page
10. Close the driver

# API Automation:
This framework designed to test the "JSONPlaceholder" API. 
## Technologies Used for API Automation
1. JavaScript: Programming language
2. Mocha: Framework for running tests.
3. Chai: Assertion library to perform assertions on the API responses.
4. Axios: HTTP client for making API requests.

## Execution
1. First navigate to the "api-automation-project" directory - cd api-automation-project
2. Run the "npm test" command - To run the tests in the project
3. Now run the command "npx mocha test/apiTests/getTests.js" - To execute the GET Command scripts





