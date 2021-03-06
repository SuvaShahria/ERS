# Project-1: Employee Reimbursment System (ERS)


## Front End
The front end was made using html,css, javascript and particle.js
Particle.js was used to make an interactive background.
<br />
**Particle.js** 
<br />
![](./imgs/video.gif)

### Example pages
![](./imgs/view2.png)
<br />
![](./imgs/view3.png)


## Executive Summary
* The Expense Reimbursement System (ERS) will manage the process of reimbursing employees for expenses incurred while on company time. 
* All employees in the company can login and submit requests for reimbursement and view their past tickets and pending requests. 
* Finance managers can log in and view all reimbursement requests and past history for all employees in the company. 
* Finance managers are authorized to approve and deny requests for expense reimbursement.

#### Employee User Stories 
- An Employee can login
- An Employee can view the Employee Homepage
- An Employee can logout
- An Employee can submit a reimbursement request
- An Employee can view their pending reimbursement requests
- An Employee can view their resolved reimbursement requests
- An Employee can view their information
- An Employee can update their information

#### Manager User Stories
- A Manager can login
- A Manager can view the Manager Homepage
- A Manager can logout
- A Manager can approve/deny pending reimbursement requests
- A Manager can view all pending requests from all employees
- A Manager can view all resolved requests from all employees and see which manager resolved it
- A Manager can view all Employees
- A Manager can view reimbursement requests from a single Employee 



**State-chart Diagram (Reimbursement Statuses)** 
<br />
![](./imgs/state-chart.jpg)

**Reimbursement Types**

Employees must select the type of reimbursement as: LODGING, TRAVEL, FOOD, or OTHER.

**Logical Model**
<br />
![](./imgs/logical.jpg)

**Physical Model**
<br />
![](./imgs/physical.jpg)

**Use Case Diagram**
<br />
![](./imgs/use-case.jpg)

**Activity Diagram**
<br />
![](./imgs/activity.jpg)

## Technologies

* The back-end system uses **Hibernate** to connect to an **AWS RDS Postgres database**. 
* The application deploys onto a Tomcat Server. 
* The middle tier uses Servlet technology for dynamic Web application development. 
* The front-end view uses HTML/JavaScript to make an application that can call server-side components. 
* Passwords are encrypted in Java and securely stored in the database. 
* The middle tier follows proper layered architecture, have reasonable (~70%) test coverage of the service layer, and implement log4j for appropriate logging. 

