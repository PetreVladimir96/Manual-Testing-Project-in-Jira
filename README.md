# Testing Project for **dedeman** platform
The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice by testing a platform site. For this project I choose dedeman platform

**Application under test:** www.dedeman.ro

**Tools used**: Jira, Zephyr Squad, Windows Snipping Tool, Microsoft Power Point

<h2>Functional specifications:</h2>
The below stories created in Jira describe the functional specifications of the "CRUD operations on the wish list/cart" and "As a client I want to be able to create a new account", for which the final project is performed upon.

First story
![(story 1.png)](/story%201.png)

Second story
![(story 2.png)](/story%202.png)


<br>Here you can find the release that was created for this project:</br>
![(Release.png)](/Release.png)

<h2>Testing process</h2>
The test process was performed based on the standard test process as described below.

<h3>1.1 Test planning</h3>
The Test Plan is designed to describe all details of testing for all the modules from the Dedeman platform application.

<h4>1.1.1. Roles asigned to the project and persons allocated</h4>

<ul>
  <li>Project manager: X </li> 
  <li>Product owner: Y</li>
  <li>Software developer: Z</li>
  <li>QA Engineer Petre Tupangiu Nicolae Vladimir</li>
</ul>

<h4> 1.1.2 Entry criteria defined </h4>
<ul>
  <li>business requirements must be defined </li> 
  <li>roles must have been allocated</li>
  <li>test plan must be finished</li>
  <li>entry and exit criteria must be defined</li>
  <li>entry criteria must be fulfilled</li>
  <li>projects risks must be identified and mitigated</li>
</ul>

<h4> 1.1.3 Exit criteria defined </h4>
<ul>
  <li>All critical defects identified during testing are addressed and verified. </li> 
  <li>Performance benchmarks meet predefined thresholds for response time and resource utilization.</li>
  <li>Security vulnerabilities identified during testing are mitigated or documented with a resolution plan. </li>
  <li>Identified usability issues are addressed or prioritized for future improvements. </li>
  <li>entry criteria must be fulfilled</li>
  <li>Test documentation, including test cases, test results and any deviations are reviewed and finalized. </li>
</ul>

<h4> 1.1.4 Test scope</h4>
<h5> Tests in scope: </h5>

<ul>
  <li>Verify that the client can't create an account if is not using values for the mandatory fields </li> 
  <li>Verify that a client can create a new account using only mandatory fields</li>
  <li>Verify the warning message if the client wants to create an account using an invalid password</li>
  <li>Verify that the mandatory GDPR checkbox works if you click on it and check the default value</li>
  <li>Verify that the user can't create an account if mandatory fields are empty</li>
  <li>Verify that an client can remove an item from the "Coș"</li>
  <li>Verify that an user can add items in wish list</li>
  <li>Verify that the user can add all of the items from the wish list to his shopping cart</li>
  <li>Verify if a client is able to add items in the cart if is not logged in</li>
  <li>Verify if a user can remove an item from the wish list</li>
  <li>Verify if a user can move products to a non-existent wish list</li>
</ul>

<h4>1.1.5 Risks detected</h4>
<h5>Project risks:</h5>
<ul>
  <li>Minor/critical software defects can lead to customer dissatisfaction, delays in the delivery of more stable versions, or even the loss of major customers </li> 
  <li>Inefficient management of resources, the budget allocated to the project is not well divided, and the time allocated to the project is not well structured so that we can be as productive as possible</li>
  <li>Compatibility issues between the different devices from which the Dedeman platform is accessed.</li>
</ul>

<h5> Product risks: </h5>
<ul>
  <li>Product/site performance – when many hits are made to the site, the product may not perform as expected (high response time) </li> 
  <li>Product security – customers can have their data stolen/lost when purchasing products.</li>
</ul>

<h3>1.2 Test Monitoring and Control</h3>
Objective: Ensure the testing process is effectively tracked and controlled to meet the project objectives and quality standards. Below, we can see a report with all the issues and how many of them were resolved in a period of time.

![(created issues report.png)](/created%20issues%20report.png)


<h3> 1.3 Test Analysis </h3>
The testing process will be executed based on the application requirements. The following test conditions were found:

![(test condition.png)](/test%20condition.png)


<h3>1.4 Test Design</h3>
Functional test cases were created in Zephyr Squad based on the analysis of the specifications. 

1. For PTNV-2 story a Test Case looks like [here](/PTNV-2%20test%20case.pdf)

2. For PTNV-3 story a Test Case looks like [here](/PTNV-3%20test%20case.pdf)

<h3>1.5. Test Execution </h3>
Test cases are executed on the created test Cycle summary.

![(Test Execution Chart.png)](/Test%20Execution%20Chart.png)

Bugs have been created based on the failed tests. The complete bug reports can be found here: 

The following is a summary of the bugs that have been found

![(Bug.png)](/Bug.png)

<h3>1.6. Test Completion </h3>
The traceability report was generated using Jira tool. We can the following reports below:

![(Traceability report 1.png)](/Traceability%20report%201.png)

![(Traceability report 2.png)](/Traceability%20report%202.png)

The final report shows that a number 10 tests are with SUCCESS from a total of 11
A number of 1 total bugs were found, from which the priority is high
