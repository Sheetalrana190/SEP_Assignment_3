# Assignment 2: Requirements

### Student Information
**Name:** Sheetal Rana  
**Student ID:** 8994226  

---

## Given Scenario
We are working with an AI developer who uses web scraping to generate training data. The client has specific needs and challenges regarding categorizing training questions and ensuring balanced data. 
After few meetings with the client we have able narrowed down to following needs and challenges.
## [Problem 1 click me](./Problem_1.md)  : 
### Training Questions
Developers want to have categorized training questions that are separate from the answers because developers care about self-affirmation.
## [Problem 2 click me](./Problem_1.md) :
### Balanced Training Data
Developers want to know that the training data they are using is "balanced" (does not contain biases) because this will give them better AI models.

---

## System Requirements :

### Validation:
(Goal: To generate appropriate system usage requirements)
1.	Do you have any examples or use cases that illustrate your needs?
2.	Do you have preference for who have access to edit training questions and categories?
3.	Should different roles (e.g., developer, admin, manager) have different access  permissions?
4.	Should the system log all actions related to data categorization and bias detection?
5.	What security measures are you currently using what should be implemented? (e.g., encryption, 2FA, role-based access)
6.	Should access logs be kept for compliance tracking?
7.	How will you measure the success of this project?

#### System Requirements:

1.	Implement data base to store question and answer separately.
2.	Implement a classification algorithm to automatically tag training questions.
3.	Provide an interface for users to manage categorized training questions.
4.	Integrate bias detection algorithms for analyzing training data.
5.	Store training data in a secure, scalable database.
6.	Use a role-based access control system to manage permissions.
7.	Implement audit logging to track changes in training data.
8.	Integrate with existing AI model training workflows.

#### System design


This how the system will look like for client 

-	Design an interface where answers are not visible by default and require user interaction to view.
-	Only authorized users (e.g., reviewers) can access answers.
-	Ensure the AI learns from questions without seeing answers initially, followed by a separate validation phase.
-	Provides a dashboard for managing training question categories and bias detection.
-	Uses machine learning models for bias detection and classification automation.
-	Stores training data securely with version control and audit tracking.
-	Integrates seamlessly with existing AI training pipelines using API endpoints.
-	Implements an intuitive UI/UX that requires minimal onboarding for developers.

---

Note : Please view the Kanban bord here https://github.com/users/Sheetalrana190/projects/3

It contain Epic that shows the priority from top to bottom with # number

Please wiew the issue here https://github.com/Sheetalrana190/SEP_Assignment_3/issues


---
# Thank You
