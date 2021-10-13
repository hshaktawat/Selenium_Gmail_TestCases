# Selenium_Gmail_TestCases

The chromedriver version supported by the framework is 94, the system should have chrome browser with version 94.

This automation framework is based on a POM. 
It has two test cases that it runs on gmail account.
The dependencies have been added in the POM.xml and the Test cases runner is TestNG.
TestNG xml file is configured to run all the test cases present in HomePageTest.java file.

Automated Test Scripts in HomePageTest.java: 
TC01 : Log into any email account and check if there is an email.
TC02 : Verify that the subject and body of the email contains a predefined string.
