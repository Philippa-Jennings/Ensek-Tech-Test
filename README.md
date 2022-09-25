# Ensek-Tech-Test

Excel spreadsheet - This document holds a number of worksheets
Worksheet 1 = Test Approach and tests to be carried out
Worksheet 2 = Test evidence - any screenshots and explanation required from the test findings
Worksheet 3 = Defect Reports - any bugs/defects found during the tests.  All tests identified using the Test ID from the Test Approach information
Worksheet 4 = UI Automation - all tests from original set that I would automate.  I have included some Locators for the buy page tests

Postman collection - This is an exported file detailing the endpoints to be tested.  I have included a test for each item within the collection which should be run per endpoint item.

Test results from Postman tests:
get energy = pass 
get orders = pass
put buy success = pass
put buy bad request = pass
post login = fail - returns 500 instead of 200, unable to test other responses
post reset = fail - returns 401 instead of 200, unable to test other responses
