# Musala_SN_Automation_Task
# Testing

TestNG -Test automation framework developed using Java and Selenium with page object model.
Developed as a Maven project. 


***************************************************About the project*********************************************

Test automation framework contains following packages and files as shown in the below image
1. Project: Testing
2. Packages

1. pages Package
This package contains all the page classes. All the static methods that are defined in the each page class can be re used 
in test classes by importing the class to perform actions on web elements.

2.	testClassPackage.
This package contains test classes where all the test cases are written using the methods that are defined in page 
classes to validate expense tracker end to end as per the user stories.

3. Xml files.
 	1. pom.xml
Contains all the plugins and dependencies that are required to run the test as maven project. TestNG.xml is configured 
in this pom.xml to trigger the test.

	2.TestNG.xml
	Contains the all class names that are to be triggered to run the complete suite of test cases.

****************************************************************************************************************************


Instructions to run the test automation:

Method1 : To Run as Maven Project locally

1. Install and set up Java

2. Install and set up Maven plugin

3. Clone the project.
4. Open Eclipse IDE , from file menu press import -> Maven -> Existing maven projects
Run as maven project. use below commands to run
Navigate to the project main folder using terminal or cmd and type below commands
========>  mvn test




