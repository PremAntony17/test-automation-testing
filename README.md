# test-automation-testing
I practice source.demo to hone my  selenium  skills.
A UI test automation project developed using selenium web driver and java as part of the automation testing frame programme. the project automates a website with a focus of reusable automation, dynamic test data and test validation.
Tech Stack
Technology	Usage
Java	Programming Language
Selenium WebDriver	UI Automation
TestNG	Test Framework
Maven	Build & Dependency Management
MySQL	Test Data Source
JDBC	Database Connectivity
ChromeDriver	Browser Automation
Git & GitHub	Version Control
Automated Test Scenarios
User Signup
Navigate to the Signup page.
Retrieve customer information from the MySQL database.
Select a customer randomly from predefined customer IDs.
Generate dynamic test data.
Populate the registration form automatically.
Handle Country and Region dropdowns.
Generate a unique email address.
Generate dynamic login credentials.
Accept the Terms & Conditions.
Submit the registration form.
Validate successful account creation using URL assertions.
Database-Driven Testing
The project integrates Selenium automation with a MySQL classicmodels database using JDBC.

Customer information is retrieved dynamically instead of hard-coding test data.

Example data retrieved from the database:

Customer Number
First Name
Last Name
Address
City
Postal Code
Random customer IDs are selected during test execution to provide dynamic test data.

Dynamic Test Data
The automation generates dynamic data to reduce duplicate registration failures.

Examples include:

Random customer selection
Dynamic email addresses
Dynamic registration data
Randomized test values
