# Experiment-15
## The study of the Selenium Web Testing Tool reveals its effectiveness in automating web applications for testing purposes across different browsers and platforms.
### What is Selenium? 
JavaScript framework that runs in your web browser Works anywhere JavaScript is supported 
Hooks for many other languages Java, Ruby, Python Can simulate a user navigating through 
pages and then assert for specific marks on the pages All you need to really know is HTML to 
start using it right away 
### Selenium IDE 
Selenium Integrated Development Environment (IDE) is a Firefox plugin that lets testers to record 
their actions as they follow the workflow that they need to test. 
It provides a Graphical User Interface for recording user actions using Firefox which is used 
to learn and use Selenium, but it can only be used with Firefox browser as other browsers are 
not supported. 
However, the recorded scripts can be converted into various programming languages 
supported by Selenium and the scripts can be executed on other browsers as well. 
### Selenium-IDEDownload 
Step 1 − Launch Firefox and navigate to the following URL - http://seleniumhq.org/download/. 
Under the Selenium IDE section, click on the link that shows the current version number as shown 
below. 
![image](https://github.com/user-attachments/assets/9640140e-34bb-42cd-b4cd-f55f7b166e2b)

Step 2 − Firefox add-ons notifier pops up with allow and disallow options. User has to allow theinstallation. 

![image](https://github.com/user-attachments/assets/6780c850-f3b6-469d-824f-b2b236cf6675)

Step 3 − The add-ons installer warns the user about untrusted add-ons. Click 'Install Now'. 

![image](https://github.com/user-attachments/assets/52e37156-2320-4adc-88f9-6117823b9219)

Step 4 − The Selenium IDE can now be accessed by navigating to Tools >>Selenium IDE. 

![image](https://github.com/user-attachments/assets/f372f56c-f36e-46a4-86fb-b846354bd006)

Step 5 − The Selenium IDE can also be accessed directly from the quick access 
menu bar as shown below. 

![image](https://github.com/user-attachments/assets/844807c4-b79c-4380-a24b-c3ae3b310f0c)

### Selenium IDE Features 
This section deals with the features available in Selenium IDE. 
The following image shows the features of Selenium IDE with the help of a simple tool-tip.

![image](https://github.com/user-attachments/assets/308658dc-e78a-4343-bffc-0fd3f27fb72b)

The features of the record tool bar are explained below. 

![image](https://github.com/user-attachments/assets/48bdbef0-38f1-4550-b686-6c861300963d)

### Creating Selenium IDE Tests 
This section deals with how to create IDE tests using 
recording feature. The following steps are involved in 
creating Selenium tests using IDE − 
 Recording and adding commands in a test 
Saving the recorded test 
Saving the test suite 
Executing 
the recorded test 
RecordingandAdding 
CommandsinaTest 
We will use www.ncalculators.com to demonstrate the features of Selenium. 

Step 1 − Launch the Firefox browser and navigate to the website - 
https://www.ncalculators.com/ 

Step 2 − Open Selenium IDE from the Tools menu and press the record button that 
is on the top- right corner. 

![image](https://github.com/user-attachments/assets/db9d878e-8aad-499e-943f-bcb176a18712)

Step 3 − Navigate to "Math Calculator" >> "Percent Calculator >> enter "10" as 
number1 and 50 as number2 and click "calculate". 

![image](https://github.com/user-attachments/assets/0106ae43-ba92-4458-8379-bf6c60ba3b96)

Step 4 − User can then insert a checkpoint by right clicking on the webelement and select 
"Show all available commands" >> select "assert text css=b 5"

![image](https://github.com/user-attachments/assets/be6ff515-306b-4d31-8fed-9b8a906be672)

Step 5 − The recorded script is generated and the script is displayed as shown below. 

![image](https://github.com/user-attachments/assets/a7b0939c-ff86-4147-8037-761eb2483af3)

### SavingtheRecordedTest 
Step 1 − Save the Test Case by navigating to "File" >> "Save Test" and save the 
file in the location of your choice. The file is saved as .HTML as default. 
The test can also be saved with an extension htm, shtml, and xhtml.

![image](https://github.com/user-attachments/assets/29cee702-8d26-4c2b-a4dd-658acf8de20a)

### SavingtheTest Suite 
A test suite is a collection of tests that can be executed as a single entity. 
 
Step 1 − Create a test suite by navigating to "File" >> "New Test Suite" as shown below. 

![image](https://github.com/user-attachments/assets/8816e8fc-8f0b-47e4-83d9-63c3b43386a4)

Step 2 − The tests can be recorded one by one by choosing the option "New Test Case" 
from the "File" Menu. 

Step 3 −   The individual tests are saved with a name along 
with saving a "Test Suite".

![image](https://github.com/user-attachments/assets/424d8df0-8ddb-4885-a0ec-f83e138178f9)

### Executingthe RecordedTest 
The recorded scripts can then be executed either by clicking "Play entire suite" or "Play current test" 
button in the toolbar. 

Step 1 − The Run status can be seen in the status pane that displays the number of tests passed and failed. 
 
Step 2 − Once a step is executed, the user can see the result in the "Log" Pane. 
 
Step 3 − After executing each step, the background of the test step turns "Green" if passed and "Red" if failed 
as shown below.

![image](https://github.com/user-attachments/assets/de10a1f0-3418-4a52-be9e-59c80706b8b7)

### Selenium IDE Script Debugging 
This section deals with debugging the Selenium IDE script.
Debugging is the process of finding and fixing errors in the test script. It is a common step in any script development.
To make the process more robust, we can make use a plugin "Power Debugger" for Selenium IDE. 

Step 1 − To install Power Debugger for Selenium IDE, navigate to 
https://addons.mozilla.org/en- US/firefox/addon/power-debugger-selenium-ide/ and 
click "Add to Firefox" as shown below.

![image](https://github.com/user-attachments/assets/0fef1f06-acf8-4b39-8946-a373baba2006)

Step 2 − Now launch 'Selenium IDE' and you will notice a new icon, "Pause on Fail" 
on recording toolbar as shown below. Click it to turn it ON. Upon clicking again, itwould be turned "OFF".

![image](https://github.com/user-attachments/assets/4ee36fd5-d480-4dfd-96b4-0817c03cbb6e)

Step 3 − Users can turn "pause on fail" on or off any time even when the test is running. 
 
Step 4 − Once the test case pauses due to a failed step, you can use the resume/step 
buttons to continue the test execution. The execution will NOT be paused if the failure 
is on the last command of any test case. 

Step 5 − We can also use breakpoints to understand what exactly happens during the 
step. To insert a breakpoint on a particular step, "Right Click" and select "Toggle 
Breakpoint" from the context- sensitive menu.

![image](https://github.com/user-attachments/assets/55acedf6-e22a-4c7f-801c-d6d3b05c76f7)

Step 6 − Upon inserting the breakpoint, the particular step is displayed with a 
pause icon as shown below. 

![image](https://github.com/user-attachments/assets/c3845b7b-7b46-48f0-adec-cc471821af4a)

Step 7 − When we execute the script, the script execution is paused where the 
breakpoint is inserted. This will help the user to evaluate the value/presence of an 
element when the execution is inprogress. 

![image](https://github.com/user-attachments/assets/d8877cde-5df2-410f-9aba-5287e674d808)

### Inserting Verification Points 
This section describes how to insert verification points in Selenium IDE. 
 
The test cases that we develop also need to check the properties of a web page. It requires assert and 
verify commands. There are two ways to insert verification points into the script. 
To insert a verification point in recording mode, "Right click" on the element and choose "Show all 
Available Commands" as shown below. 

![image](https://github.com/user-attachments/assets/818415c3-c52c-4afa-bed1-a7ee47af342b)

We can also insert a command by performing a "Right-Click" and choosing "Insert New 
Command". 

![image](https://github.com/user-attachments/assets/e3760cf5-e8d5-4ce3-9742-27de030267bb)

 
After inserting a new command, click 'Command' dropdown and select appropriate 
verification point from the available list of commands as shown below.

![image](https://github.com/user-attachments/assets/0037771e-ae3a-4223-82a2-482cf85ab9c4)

Given below are the mostly used verification commands that help us check if a 
particular step has passed or failed. 
 
 verifyElementPresent 
 assertElementPresent 
 verifyElementNotPresent 
 assertElementNotPresent 
 verifyText 
 assertText 
 verifyAttribute 
 assertAttribute 
 verifyChecked 
 assertChecked
 verifyAlert 
 assertAlert
 verifyTitle
 assertTitle
 
### SynchronizationPoints 

During script execution, the application might respond based on server load, hence it is 
required for the application and script to be in sync. Given below are few a commands that we can use to 
ensure that the script and application are in sync. 

waitForAlertNotPresent 

waitForAlertPresent 

waitForElementPresent 

waitForElementNotPresent 

waitForTextPresent 

waitForTextNotPresent 

waitForPageToLoad 


waitForFrameToLoad 

### Selenium Pattern Matching 

□ This section deals with how to work with regular expressions using IDE. 
Like locators, patterns are a type of parameter frequently used by Selenium. It allows users to describe 
patterns with the help of special characters. Many a time, the text that we would like to verify are 
dynamic; in that case, pattern matching is very useful. 

Pattern matching is used with all the verification point commands - verifyTextPresent, verifyTitle, 
verifyAlert, assertConfirmation, verifyText, and verifyPrompt. 
There are three ways to define a pattern −

Globbing 

Globbing 

regular expressions, and exact patterns. 

Most techies who have used file matching patterns in Linux or Windows while searching for a 
certain file type like *.doc or *.jpg. would be familiar with term "globbing" 

Globbing in Selenium supports only three special characters: *, ?, and [ ]. 

• * − matches any number of characters. 

• ? − matches a single character.

□ [ ] − called a character class, lets you match any single character found within the brackets. [0- 9] matches any 
digit. 

To specify a glob in a Selenium command, prefix the pattern with the keyword 'glob:'. For example, if you would 
like to search for the texts "tax year 2013" or "tax year 2014", then you can use the golb "tax year *" as shown 
below. 

However the usage of "glob:" is optional while specifying a text pattern because globbing patterns are the default 
in Selenium. 

![image](https://github.com/user-attachments/assets/b2564055-23cb-446b-b830-6a35052f59c5)

### ExactPatterns 
Patterns with the prefix 'exact:' will match the given text as it is. Let us say, the user wants an exact match with  
the value string, i.e., without the glob operator doing its work, one can use the 'exact' pattern as shown below. In this 
example the operator '*' will work as a normal character rather than apattern- matching wildcard character. 

![image](https://github.com/user-attachments/assets/c046e6b1-3f7b-4968-b4fb-b40fb049e5b7)

### RegularExpressions 
Regular expressions are the most useful among the pattern matching techniques available. Selenium supports  
the complete set of regular expression patterns that Javascript supports. Hence the users are no longer limited  
by *, ? and [] globbing patterns. 

To use RegEx patterns, we need to prefix with either "regexp:" or "regexpi:". The prefix "regexpi" is  
case- insensitive. The glob: and the exact: patterns are the subsets of the Regular Expression patterns.  
Everything that is done with glob: or exact: can be accomplished with the help of RegExp. 
### Example 
For example, the following will test if an input field with the id 'name' contains the string 'tax year', 'Tax Year',  
or  'tax Year'

![image](https://github.com/user-attachments/assets/8b24410d-05cd-4ca1-93af-c0498eef9179)

### Selenium User Extensions 
The Java script that allows users to customize or add new functionality. 
 
It is easy to extend Selenium IDE by adding customized actions, assertions, and locator-strategies. It is done 
with the help of JavaScript by adding methods to the Selenium object prototype. On startup, Selenium will 
automatically look through the methods on these prototypes, using name patterns to recognize which ones are 
actions, assertions, and locators. 

Let us add a 'while' Loop in Selenium IDE with the help of JavaScript. 
 
Step 1 − To add the js file, first navigate 
to https://github.com/darrenderidder/sideflow/blob/master/sideflow.js and copy the script and place save it as 'sideflow.js' in your local folder as shown below

![image](https://github.com/user-attachments/assets/554e8b6b-16c2-4366-86bb-859da0038624)

Step 2 − Now launch 'Selenium IDE' and navigate to "Options" >> "Options" as shown below.

![image](https://github.com/user-attachments/assets/b03e8937-c506-4604-a814-cfb9b5584c21)

Step 3 − Click the 'Browse' button under 'Selenium Core Extensions' area and point to the js file that we have 
saved in Step 1.

![image](https://github.com/user-attachments/assets/cc4b7c64-99bf-4f2b-b43a-ee390b6bfff6)

Step 4 − Restart Selenium IDE. 
 
Step 5 − Now you will have access to a few more commands such as "Label", "While" etc. 
 
Step 6 − Now we will be able to create a While loop within Selenium IDE and it 
will execute as shown below. 

![image](https://github.com/user-attachments/assets/72f6fa67-f830-470e-a01a-61906e2a04c2)

## Result: 
Thus, the study of selenium web testing tool is conducted and the results were noted.
