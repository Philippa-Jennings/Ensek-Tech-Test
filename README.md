# Ensek-Tech-Test

**Excel spreadsheet** <br>
This document holds a number of worksheets<br>
Worksheet 1 = Test Approach and tests to be carried out<br>
Worksheet 2 = Test evidence - any screenshots and explanation required from the test findings<br>
Worksheet 3 = Defect Reports - any bugs/defects found during the tests.  All tests identified using the Test ID from the Test Approach information<br>
Worksheet 4 = UI Automation - all tests from original set that I would automate.  I have included some Locators for the buy page tests<br>

**Postman collection** <br>
This is an exported file detailing the endpoints to be tested.  I have included a test for each item within the collection which should be run per endpoint item.<br>

**Test results from Postman tests:**<br>
get energy = pass <br>
get orders = pass<br>
put buy success = pass<br>
put buy bad request = pass<br>
post login = fail - returns 500 instead of 200, unable to test other responses<br>
post reset = fail - returns 401 instead of 200, unable to test other responses<br>
<br>
