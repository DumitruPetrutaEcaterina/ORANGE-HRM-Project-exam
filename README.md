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
User Story [ User Story 1]                            (https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/User%20Story%201a.png)

![ User Story 2!](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/User%20Story%201b.png)

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
-	Regression testing have been ran and no major bugs detected  
-	All business requirements have been covered by test cases 
-	All business requirements have been met 

#### Risks:
-	Project risks: lack of experience of QA team, lack of tools, short deadline for Jira and Zephyr Squad,
-	Product risks: Validation constraints on the fields might be too restrictive to the end user 

#### 2.2 Test analysis 
-	Analyze the business requirements to make sure that we have all the details to create the test conditions 
-	Write test conditions that will be tested in out test process 

#### 2.3 Test design
-	Functional test cases will be created in Jira 

#### 2.4 Test implementation

Verify if the following elements are ready before test execution:
-	Test environment is up and running:
-	https://opensource-demo.orangehrmlive.com/web/index.php/auth/login
-	Access to test environment is given:
   username Admin, password: admin 123
-	Cycle summary was created 1.01, Ad hoc
-	Test cases were added to the cycle summary

#### 2.5 Test execution
-	Test cases are executed on the created cycle summary 

#### Test Execution:

Test Execution [ Test Execution ]                          (https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/Test%20Execution.png)

-	Bugs have been created based on the failed test cases. The complete bug reports can be found here:
  
#### Bug:

![ Bug !](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/Bug%20a.png)
![ Bug !](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/Bug%20b.png)

Bug [ Bug pdf ]                (https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/OP-41.pdf)


#### 2.6 Test closure
-	All exit criteria were met as mentioned in the Test Planning section (2.1)
-	The traceability matrix was generated to demonstrate the business requirements coverage
-	Test execution chart was generated, the final report shows a number of 1 failed test cases of a total 28


#### 2.7 Test monitoring and control
Various periodic reports were generated to reflect the current status of the testing process, in case of major problems control measures could be taken.

![ Monitoring !](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/Daily%20Test%20Monitoring.jpg)

Time Report [ Time Report pdf ]                                           (https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/Time%20by%20Status%20Report%20(1).pdf)




.
### 3	Test deliverables

#### 3.1	  Test plan
The plan identifies the items to be tested, the features to be tested, the type of testing to be performed, the roles and responsibilities for the testing process, the resources and schedule required to complete testing and the risks associated with the plan. 

Project Test Plan [ Project Test Plan pdf ]                                (https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/Test%20plan%20ORANGE%20HRM.pdf)

Epic [ Epic pdf ]                                                          (https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/OP-3%20(2).pdf)

Story 1 [ Story 1 pdf ]                                                    (https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/OP-5%20(1).pdf)

Story 2 [ Story 2 pdf ]                                                    (https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/OP-24.pdf)

Story 3 [ Story 3 pdf ]                                                    (https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/OP-4%20(1).pdf)


#### 3.2	  Test conditions

![ Conditions 1 !](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/Conditions%201.png)

![ Conditions 2 !](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/Conditions%202.png)


#### 3.3	  Test cases

-pdf exported from Jira with all test cases 

![ Test Cases 1 !](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/Test%20Cases%201.JPG)


Test Cases [ Test Cases pdf ]                                              (https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/OP-6%20(4)-combined.pdf)



#### 3.4	  Daily test summary report 

![ Summary report !](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/Summary%20report.jpg)


#### 3.5	  Traceability matrix

![ Matrix !](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/Matrix.png)

Matrix [ Matrix pdf ]                                                       (https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/Traceability%20Report%20(Recursive)%20(Jira)%20(3).pdf)


Gant Chart [ Gantt Chart pdf ]                                               (https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/Gantt%20Chart%20(Jira).pdf)


#### 3.6	  Test case results
The test cases results:

-pdf exported from Jira with all test cases and results


Test Cases [ Test Cases pdf ]                                                 (https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/OP-6%20(4)-combined.pdf)


#### 3.7	  Bugs report

![ Bug a !](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/Bug%20a.png)
![ Bug b !](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/Bug%20b.png)


![ Bug c !](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/Report%20Bug.png)

Bug [ Bug pdf ]                                                                (https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/OP-41.pdf)


#### 3.8	  Test completion report
The test completion report generated from Jira:

-pdf exported from Jira with test completion report


[ Test Report pdf ](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/blob/main/Zephyr%20Test%20Steps%20%2B%20Executions%20%2B%20Results%20(Jira)%20(2).pdf)


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
- Application documentation:
  https://www.orangehrm.com/assets/Files/Complete-Administrative-User-Guide.pdf
![image](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/assets/132688919/b478f5eb-5317-4e23-b9a2-4b83623dcb55)
- Application:
  https://opensource-demo.orangehrmlive.com/web/index.php/auth/login
![image](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/assets/132688919/4d2c27e0-5e6c-4864-9c2e-abe7fb0e8d00)
Username: Admin, Password: admin 123
![image](https://github.com/DumitruPetrutaEcaterina/ORANGE-HRM-Project-exam/assets/132688919/03e5dc96-8a61-4851-b8ac-1ffd39c48380)



