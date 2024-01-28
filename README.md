# Selenium-MI-Page

Steps to Import the code
1) Unzip the files and check the contents available in the Folder
2) Open the eclipse. File-> Import-> Existing Maven dependencies.
3) Once the importing is done we can see all the existing files.

About the code:
1) In Selenium Framework we have src/test/java where we have the main code of the program. In which we have 4 types of packages.
2) Core: This is the part where we have Test Drivers and Annotations.
3) Objects: This is the package where one can find the Xpaths and page objects.
4) Test: With the help of POM and the code present in Objects we will be writning the test cases accordingly.
5) Util: In this package we can find the all the utilities code which will help the code become more effective.
6) We have the reports folder where we can see the reports of the tests executed.
7) Suite.xml file is the main part, with the help of Suite.xml we can executre the code using Test NG

Note: 
1) In this praticular framework we have issue with chrome browser. Please use firefox for execution (In Suite.xml use "FF").
2) In Resources file we have Test Data excel with the help of which we can store the data and call in form of function
3) Please make sure you have all the Maven and TestNG jar files imported. And try to maintain the lastest versions of the softwares.
