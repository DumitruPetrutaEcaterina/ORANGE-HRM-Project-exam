# ORANGE HRM Project-exam
### Test Plan
### Revision History
<h2>Test Plan</h2>

|Date|Description|Author|Comments|
|---|---|---|---|
|12.10.2023|v1.01|Dumitru Petruta Ecaterina|More details added on Test Implementation and Test completion|
1.	Introduction
   
1.1	Project objective

1.2	Functionalities in scope

1.3	Functionalities and tests out of scope

2.	Test process
   
2.1	Test planning
  	
2.2	Test analysis

2.3	Test design

2.4	Test implementation

2.5	Test execution

2.6	Test closure

2.7	Test monitoring and control

3.	Test deliverables
   
3.1	Test plan

3.2	Test conditions

3.3	Test cases

3.4	Daily test summary reports

3.5	Traceability matrix

3.6	Test case results

3.7	Bugs report

3.8	Test completion report




.
### 1	Introduction

This test plan document describes the strategies, process, workflows and methodologies used to plan, organize, execute and manage testing process for OrangeHRM.

#### 1.1	  Project Objective
- The scope of the final project for ITF Manual Testing Course is to use all gained knowledge through the course and apply them in practice, using a live application. 

- Application under test:
https://opensource-demo.orangehrmlive.com/web/index.php/auth/login

Username : Admin
Password : admin123

- The focus will be only on Time module – Time Sheets

- Application documentation:
https://www.orangehrm.com/assets/Files/Complete-Administrative-User-Guide.pdf
page 80

Tools: Jira


#### 1.2	  Functionalities in scope
-	All the features of Time module which were defined in business requirements need to be tested: functional testing, 
-	The below user story was created in Jira and describes functional specifications of the Time module.

#### User Story:
Example of: [User Story 1](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/User%20Story%201a.png)


#### 1.3 Functionalities and tests out of scope
-	No QA support for mobile application developed. Only web application will be tested. 
-	Automation testing is beyond scope.




.
### 2	Test process
#### 2.1	  Test planning
#### Roles and responsibilities
<h2>Test Plan</h2>

|Product Owner|Orange HRM Company|
|---|---|
|Software Developer|Diana Popescu|
|Tester |Dumitru Petruta Ecaterina|

#### Entry criteria:
-	Business specifications are defined 
-	Roles needed for the project are allocated 
-	Initial project risks were detected and mitigated 

#### Exit criteria:
-	All test cases have been executed 
-	The unresolved bugs/defects have medium priority 
-	No detected major risks remained un-mitigated 
-	All resolved bugs have been retested and approved by the testers
-	All business requirements have been covered by test cases 
-	All business requirements have been met 

#### Risks:
-	Project risks: lack of experience of QA team, lack of tools, short deadline for Jira and Zephyr Squad,
-	Product risks: the risk of defects occurring due to the complexity of the code

#### 2.2 Test analysis 
-	Analyze the business requirements to make sure that we have all the details to create the test conditions 
-	Write test conditions that will be tested in out test process 

#### 2.3 Test design
-  Test cases will be created in Jira,
-	Black Box test cases will be created in Jira, like boundary value testing test cases.
  
   Example [Boundary Value Test Case pdf](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/OP-21.pdf)

#### 2.4 Test implementation

Verify if the following elements are ready before test execution:
-	Test environment is up and running:
-	https://opensource-demo.orangehrmlive.com/web/index.php/auth/login
-	Access to test environment is given:
   username Admin, password: admin 123
-	Cycle summary was created 1.01, Ad hoc
-	Test cases were added to the cycle summary

#### 2.5 Test execution
-	Test cases are executed on the created cycle summary:
  
 [Test Execution](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/Test%20Execution.png)

Epic: [Epic pdf](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/OP-3%20(2).pdf)

-  [Story 1 pdf](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/OP-5%20(1).pdf)

-  [Story 2 pdf](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/OP-24.pdf)

-  [Story 3 pdf](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/OP-4%20(1).pdf)

-	Bugs have been created based on the failed test cases. The complete bug reports can be found here:

 [Bug pdf](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/OP-41.pdf)


#### 2.6 Test closure
-	All exit criteria were met as mentioned in the Test Planning section (3.1)
-	The traceability matrix was generated to demonstrate the business requirements coverage
-	Test execution chart was generated, the final report shows a number of 1 failed test cases of a total 28


#### 2.7 Test monitoring and control
Various periodic reports were generated to reflect the current status of the testing process, in case of major problems control measures could be taken.

![Monitoring !](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/Daily%20Test%20Monitoring.jpg)

A time report file was exported as pdf, from Jira as attached:

 [Time Report pdf](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/Time%20by%20Status%20Report%20(1).pdf)




.
### 3	Test deliverables

#### 3.1	  Test plan
The plan identifies the items to be tested, the features to be tested, the type of testing to be performed, the roles and responsibilities for the testing process, the resources and schedule required to complete testing and the risks associated with the plan. 

Project Test Plan [Project Test Plan pdf](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/Test%20plan%202_ORANGE%20HRM.pdf)




#### 3.2	  Test conditions

The following 28 tests were created based on the test conditions:

[Tests pdf](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/Issue%20List%20(Jira).pdf)

Attached the test conditions: [Conditions 1](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/Conditii.JPG)



#### 3.3	  Test cases

Test cases were done in the execution phase and exported as pdf, from Jira as attached: 

Example [Test Cases 1](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/Test%20Cases%201.JPG)


Test Cases [Test Cases pdf](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/OP-6%20(4)-combined.pdf)



#### 3.4	  Daily test summary report 

Attached the daily test report:

Example [Summary report](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/Summary%20report.jpg)


#### 3.5	  Traceability matrix

Below the Traceability matrix attched in the form of jpg and pdf.format:

![Matrix !](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/MATRICE.JPG)

Traceability Matrix:[Traceability Matrix pdf](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/Forward%20Traceability_1_11_2023.pdf)

Traceability report was also exported in pdf format:[Matrix pdf](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/Traceability%20Report%20(Recursive)%20(Jira)%20(3).pdf)

To show the time line a Gantt Chart was done:
[Gantt Chart pdf](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/Gantt%20Chart%20(Jira).pdf)


#### 3.6	  Test case results
The test cases results:

All test cases and results were exported from Jira as pdf format:


[Test Cases pdf](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/OP-6%20(4)-combined.pdf)


#### 3.7	  Bugs report

Bug Report [Bug c](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/Report%20Bug.png)

Bug [Bug pdf](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/OP-41.pdf)

A Bug Ticket was done bound by Story OP-5: Customer added by Admin in Time Module.
In the pop-up customer window, the number of characters allowed is over maximul limit.
Severity - Moderate, Priority – Low. 


#### 3.8	  Test completion report
The test completion report generated from Jira:

- A pdf was exported from Jira with test completion report


Test Report [Test Report pdf](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/Zephyr%20Test%20Steps%20%2B%20Executions%20%2B%20Results%20(Jira)%20(2).pdf)


#### 3.9	  Schedule
A test schedule includes the testing steps or tasks, the target start and end date and responsibilities. 
<h4>Test Schedule</h4>

|Task|Data|Team member|
|---|---|---|
|Setup Project in Jira|13.10.2023|Dumitru Petruta Ecaterina|
|Run functional Test Cases|15.10.2023|Dumitru Petruta Ecaterina|
|Transfer Project in GitHub|18.10.2023|Dumitru Petruta Ecaterina|

### General conclusions
- Putting the acquired knowledge into practice; testing the ORANGE HRM application: Time Module – Time Sheet, page 80,
through the JIRA application and the Zephyr plugin.
- Total number of Story: 3
- Total number of Taste Cases / Total number of Run Test Cases: 28
- Bugs: 1, medium severity, degree of affecting the user: Low
- The application was tested on the selected segment, which has optimal functionality.
- No major defects and impact on the user.
- The segment can be launched in real environment by the client.
- Application documentation:
  https://www.orangehrm.com/assets/Files/Complete-Administrative-User-Guide.pdf
- Application:
  https://opensource-demo.orangehrmlive.com/web/index.php/auth/login
Username: Admin, Password: admin 123
  



