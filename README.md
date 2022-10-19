Assignment Name: Selenium Java 101

Module: Test Scenarios

PROBLEM STATEMENT :Test the Lambda Test portal.

Name : Ankitaa Nagavelli

URL USED:

The website used in this project is "https://www.lambdatest.com/selenium-playground".

DETAILED DESCRIPTION: Test Scenario 1:

Open LambdaTest’s Selenium Playground from https://www.lambdatest.com/selenium-playground
Click “Simple Form Demo” under Input Forms.
Validate that the URL contains “simple-form-demo”.
Create a variable for a string value E.g: “Welcome to LambdaTest”.
Use this variable to enter values in the “Enter Message” text box.
Click “Get Checked Value”.
Validate whether the same text message is displayed in the right-hand panel under the “Your Message:” section.
Test Scenario 2:

Open the https://www.lambdatest.com/selenium-playground page and click “Drag & Drop Sliders” under “Progress Bars & Sliders”.
Select the slider “Default value 15” and drag the bar to make it 95 by validating whether the range value shows 95.
Test Scenario 3:

Open the https://www.lambdatest.com/selenium-playground page and click “Input Form Submit” under “Input Forms”.
Click “Submit” without filling in any information in the form.
Assert “Please fill in the fields” error message.
Fill in Name, Email, and other fields.
From the Country drop-down, select “United States” using the text property.
Fill all fields and click “Submit”.
Once submitted, validate the success message “Thanks for contacting us, we will get back to you shortly.” on the screen.
##Tools and plugins used

Selenium version :3.141.59 jar
Maven :3.8.5
TestNG : 7.4.0
Apache POI : 4.1.0
POM.xml
Java
Testng.xml
LambdaTest platform
OUTPUTS:

Detailed console output
We can see the testscenario status in lambdatest page under Automation->Builds
OUTPUT IN CONSOL OF ECLIPSE

=============================================== Parallel Test Suite Total tests run: 12, Passes: 12, Failures: 0, Skips: 0
