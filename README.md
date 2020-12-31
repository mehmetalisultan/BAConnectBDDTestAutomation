# BAConnectBDDTestAutomation
Test Automation Framework for SBA Connect it is built with Gradle it uses Selenium JAVA, it is a Cucumber BDD framework.
To run this automation framework you have to install ItelliJ IDEA. The instruction to run and generate report for this framework is in info.txt. You can see the report in index.html.
The SBA connect application requires two-factor authentication so it is better to have bypass account from login.gov(has to have static one time code/OTP). Another option to test, you have to have backup code for your email credential.
Currently, all data for the application are hardcoded in step definition, to run you have to update in your own credential.
The elements in the request access page does not have ID or name, it is better to have ID/name to easily locate the elements(I have informed the developers, they started to add it.)
