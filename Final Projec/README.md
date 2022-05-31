# Final project for ITF Manual Testing Course

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application. 

Application under test: https://opensource-demo.orangehrmlive.com/

API Documentation: https://orangehrm.github.io/orangehrm-api-doc/

**The final project is split into 2 sections: [Testing section](https://github.com/ninaninuk/manual_testing_portofolio/blob/main/Final%20Projec/README.md#1-testing-section) and [SQL section](https://github.com/ninaninuk/manual_testing_portofolio/blob/main/Final%20Projec/README.md#2-sql-section).**

Tools used: JIRA, Zephyr Squad, Postman, MySQL Workbench

# Functional specifications

-> scr 1 Jira
![image](https://user-images.githubusercontent.com/103954664/170871991-08bfac0e-bd51-4f7c-b7d8-6ba4bf211608.png)


# 1 Testing section

## 1.1 Test Planning

The Test Plan is designed to describe all details of testing for the X module from the OrangeHRM application. 

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan


![image](https://user-images.githubusercontent.com/103954664/170875811-e84e2264-4db9-4584-93c1-aa0247076aec.png)



#### 1.1.1 Roles assigned to the project and persons allocated
 * Project manager- Albu Iulia
 * Bisness Analyst- Olariu Razvan
 * Developer-Succiu Tiberiu
 * QA Enhineer- Hatos Valy
 * Tester- Macuh Nina

#### 1.1.2 Entry criteria defined
* The application must be prepared.
* Functional specifications are defined
* Initial project risks were detected and mitigated
* Roles needed for the project are allocated
* Test data should be ready.


#### 1.1.3 Exit criteria defined
 * Exploratory regression testing must be performed on the My Info module, which includes the Languages section
 * All user stories in the sprint backlog must be completed 
 * All design tasks and special tasks picked for the sprint must be completed
 * Regression testing of all features developed in all previous sprints must be executed
 * No critical issues must be open
#### 1.1.4 Test scope

* __Tests in scope:__  All the feature of Dependents module which were defined in software requirement specs need to be tested: functional testing, GUI testing and API testing
* __Tests not in scope:__  Performance testing, integrations of the dependents module with other modules, compatibility testing with multiple browsers

#### 1.1.5 Risks detected

* Project risks: lack of experience of the QA team, short deadline of Zephyr Squad trial, unavailability of test environment;  communication with the team ; 
* Project risks: validation constraints on the fields might be too restrictive to the end-user; poor quality;

#### 1.1.6 Evaluating entry criteria

The entry criterias defined in the Test Planning phase have been achieved and the test process can continue. 

## 1.2 Test Monitoring and Control

It will be done by generating periodic reports that reflect the current status of the test.

## 1.3 Test Analysis

The testing process will be executed based on the above requirements for the Languages module. The following test conditions were found:
 
 
  * Enter data only for mandatory fields and check that the language is created/updated
  * Enter data for all available fields and check that the language is created/updated
  * Leave mandatory fields empty and check that the language cannot be created/updated
  * View language details and check they are correct
  * View all languages in a list
  * Check all validation constraints for the fields
  * Check that a languages can be deleted


## 1.4 Test Design

Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, the test design techniques used for generating test cases 
are:

**Test cases:**
-> enter here test cases or at least the titles

![image](https://user-images.githubusercontent.com/103954664/171159645-cc794b91-a391-4c6a-ad64-9854202663d3.png)

The test cases with steps can be viewed here: [test_cases.pdf]()

## 1.5 Test Implementation

The following elements are needed to be ready before the test execution phase begins:

* enter here what needs to be ready for the test execution to begin

## 1.6 Test Execution

* Test cases are executed on the created test Cycle summary: [cycle_summary_execution.pdf]()
* Bugs have been created based on the failed tests. The complete bug reports can be found here: [created_bugs.pdf]()
    *  enter here bug titles


## 1.7 Test Completion

* Exit criteria was evaluated and passed
* The traceability matrix was generated and can be found here: [Traceability_matrix.csv]()
* Test execution chart was generated, the final report shows.... -> describe the final report

-> enter here test execution report/chart

# 2 SQL section

Created a database named 'orange hrm' and a table named 'languages' with all the columns needed to save data per specifications. Performed different queries inside the sql file:[languages.sql](https://github.com/ninaninuk/manual_testing_portofolio/blob/temp-2/Final%20Projec/languages.sql)

