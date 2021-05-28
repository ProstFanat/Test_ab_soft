# Test task to AB soft

This test was created for testing a feature of
Filter by Tag on https://demo.realworld.io/#/.

Test using Java 1.8 with Selenium Webdriver,TestNG and Allure
and builds with Grade.

To run the tests from Idea you need to:
1) Go to the file: Test_ab_soft/src/test/java/conduit/FilterTag
2) If you using a Linux, you need to rename from "driver = drivers.getChromeDriverWindows();" to "driver = drivers.getChromeDriverLinux();"
3) Starts the test from this file.

To run the test from Terminal you need to:
1) Open Terminal at the package with project
2) Run "gradlew test" from Windows and "./gradlew test" from Linux

To open the Allure report you need to:
From Linux - Open Terminal at the package with project and run command "./gradlew allureServe"

From Windows - Open Terminal at the package with project, go to folder "build" and run command "allure serve"

About project structure:
1) Test_ab_soft/src/test/java/conduit/ - contains java classes that started the tests
2) Test_ab_soft/src/main/java/Main/ - contains java classes with WebElements and methods for testing
3) Test_ab_soft/src/main/java/resources - contains java class BasePage with basic methods for working with Selenium Webdriver