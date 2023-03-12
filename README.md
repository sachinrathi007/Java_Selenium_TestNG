# Java_Selenium_TestNG
MasterSeleniumFramework
It has a concept of Atomic tests (Achieved by Selenium WebDriver API and RestAssured API)
Atomic Tests:
------------------------------------------------------------
Updations done:
Screenshots are attached in the ExtentReport as Base64 format.
Allure Reports
User has options for customization
Email to User(s) using Java mail API
Others implementations:

Retry failed test cases
Custom Enums, Exceptions, Annotations
Serialization and Deserialization using Jackson-Databind dependency
Data Driven testing using JSON file
Icons addition in ExtentReport a. Browser icon with every test case b. Test status Test Description -> Last -> Pass (Happy), Fail (Sad) c. WIN + Browser d. Navigating to Right e. Details (Add Rajat linkedIn and Github URL) Make them Links and align it with Name
Zip the ExtentReports directory into Project path (you can send this Zip file as well as an Attachment in Email)
Automatically open the report after tests execution.
Send EMail using Java mail API to User(s) with attachment(s).
https://mvnrepository.com/artifact/javax.mail/mail/1.4.7
https://www.tutorialspoint.com/java/java_sending_email.htm
Gmail -> Manage your Google account:
Security -> Turn on : Less Secure App access:
How to run the Project from Local machine

Pull the code into your machine and import in IDE (Eclipse/intelliJ).
Go to testng_Local.xml -> Run this file as TestNG suite It should start the execution -> Parallel Cross Browser Testing.
NOTE: stg_config.properties is the default configuration file.
To view the Allure reports
Setup the Allure in your machine
Go to URL (https://docs.qameta.io/allure/) -> Search for Manual installation -> Steps are mentioned
Go to your project location
Open command prompt -> allure serve allure-results
------------------------------------------------------------
