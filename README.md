# Computer-Database
Backbase - Computer Database Automation Scripts

# Project Structure

The project follows the standard Maven structure, so all the tests go in the src/test/java folder.Tests should inherit from the TestBase class that performs common setup.ComputerDataBaseTest class (in src/test/java) is a test class for testing the CRUD functionality of a web application.In the setup method of this class, the PageFactory classes go to src/main/java and it is used to help supporting the [PageObjects](https://www.seleniumhq.org/docs/06_test_design_considerations.jsp) pattern.

Pre-requisite - Chrome and Eclipse should be installed on the machine

# Project Configuration Steps

1. Clone this repository [CLONE](https://github.com/Nomad27/computer-database.git)

2. Import project in Eclipse as a Maven Project

3. Run clean install target of Maven project

4. Right click on 'testng.xml'

5. Run as TestNG suite

6. Location of report (Refresh the project to find reports)

7. TestNG report will be available in test-output -> index.html

Now done with the Automation Scripts with coverage of CRUD functionality. As we always have a room of improvments, same here also i found some improvement points.
# Points
1. Though we have built-in reports that provide information on the steps that are executed as part of the test case but there is a need of more customization of reports that is to be shared with all the major project stakeholders.So that they also can easily understand the test result reports.To beautify the test result report we have different different plugins in selenium like Extent Reports even we can customize the TestNG reports too.
2. We have covered the major functionality of Computer Database application. If we would have been more time we could cover more functionality.
3. We can configure this automation script with jenkin pipleline and run it.
4. We can send the notification email once the test result report generates .

It is good if we have the Automation Suits ready with us.It would help us to achieve fully the CICD journey.

If any points which is need to be added please notify me i will work upon that.
Thank you. Have a Good Day


Regards,
Ritu



