![image](https://github.com/drmathew23/Jira-Automation/assets/155710334/a3a46a47-e60a-4d92-8dfb-2613ec848d0f)
# Jira Service Management: Configuration, Workflows and Automation
This project is designed to optimize IT support processes using Jira's powerful features. I will focus on the meticulous configuration of Jira settings, the creation of efficient workflows, and the implementation of smart automation rules. By customizing issue types, fields, screens, and automation rules, we establish a clear and efficient pathway for each ticket from the moment it is reported until it is resolved.

## Objectives
#### Streamline Ticket Management:
+ Simplify the process of creating, tracking, and managing tickets through customized workflows and fields tailored to various types of IT support requests.
#### Automate Routine Tasks:
+ Implement automation rules to handle repetitive tasks such as ticket assignments, status updates, and notifications.
#### Enhance Communication:
+ Facilitate better communication within the support team and with end-users through automated notifications and updates.
## Environments and Technologies Used
+ Jira Service Management
+ Windows 11
## Customizing Issue Types
Jira allows you to customize the types of issues that can be created within your project. This is essential for categorizing the different kinds of requests and problems your help desk will handle.

![image](https://github.com/drmathew23/Jira-Automation/assets/155710334/b505481a-92b1-47c7-b0ba-196899980002)
.

.

## Standard Issue Types for IT Help Desk:
#### 1. Bug Report
![image](https://github.com/drmathew23/Jira-Automation/assets/155710334/37595937-109d-4395-8cc5-a9e46f883e11)

#### 2. Hardware Request
![image](https://github.com/drmathew23/Jira-Automation/assets/155710334/f69f2431-9b14-4e47-914e-deba20541ed7)

#### 3. Software Installation
![image](https://github.com/drmathew23/Jira-Automation/assets/155710334/c0a2788d-3e92-4a98-ab4e-2090002f02e1)

#### 4. Network Issue
![image](https://github.com/drmathew23/Jira-Automation/assets/155710334/f1a924d7-7c48-4365-8404-f7ddd30b16bd)

#### 4. Access Request
![image](https://github.com/drmathew23/Jira-Automation/assets/155710334/ab849d14-58f7-4159-98c1-f687061fe95b)

## Defining a Workflow
A workflow defines the lifecycle of an issue, from creation to resolution. Customizing the workflow allows you to mirror your organization's process for handling IT support requests.
![image](https://github.com/drmathew23/Jira-Automation/assets/155710334/2c18fce8-a0ad-4c5c-b23a-e24038295aaf)
.

.

## Standard Workflow Stages for IT Help Desk:
![image](https://github.com/drmathew23/Jira-Automation/assets/155710334/be157ea3-8fbd-4e0f-b969-73bdb1b3a15a)


**Open:** The initial status of a new issue.

**In Progress:** The issue is being worked on by IT staff.

**Awaiting User:** Waiting for more information or confirmation from the user.

**Resolved:** The issue has been addressed, awaiting closure.

**Closed:** The issue is fully resolved and closed.


![image](https://github.com/drmathew23/Jira-configurations-workflow-automation/assets/155710334/d34972ab-cf89-4f4c-af0a-aff820dabceb)

.

.

.

## Custom Fields
Custom fields allow you to capture specific information related to different issue types.

![image](https://github.com/drmathew23/Jira-configurations-workflow-automation/assets/155710334/a92ab1e3-54e2-417b-87bd-70d6e555cb0f)

**Severity Level:** Helps prioritize issues based on their impact on the business.

**Affected System:** Identifies which system or application is impacted by the issue.

**Reported By:** Captures whether the issue was reported by an employee, customer, or vendor.

**Expected Resolution Time:** Provides an estimate of how long it will take to resolve the issue, which can be crucial for managing expectations.

**Root Cause Analysis:** A text field for documenting the underlying cause of the issue once it has been identified. This is valuable for preventing future occurrences.


## Customizing Screens
Screens in Jira determine which fields are displayed to users when they create, view, or edit an issue. Customizing these screens allows you to ensure that users are prompted for all relevant information when reporting an issue or moving it through its lifecycle.

![image](https://github.com/drmathew23/Jira-configurations-workflow-automation/assets/155710334/f8d330d5-13f2-4550-9242-eb2a5fb3faf7)


## Understanding Jira Automation
Jira Automation is a powerful tool that allows you to create rules based on triggers, conditions, and actions. These rules can automate various aspects of your workflow, from issue assignment to notifications and field updates.

![image](https://github.com/drmathew23/Jira-configurations-workflow-automation/assets/155710334/5e68914b-aaa2-4a6a-919e-57a6dc2e09f6)

.

.

## Key Concepts for Automation
**Triggers:** What initiates the automation rule. For example, creating an issue, updating an issue, or transitioning an issue could be triggers.

**Conditions:** Criteria that must be met for the automation rule to execute. Conditions help ensure that actions are taken only when relevant.

**Actions:** The operations performed when the trigger fires and the conditions are met. Actions can include updating an issue, sending an email, or transitioning an issue to a different status.

### Examples of Automation Rules for an IT Help Desk
#### Auto-Assigning Issues Based on Severity or Type

+ Trigger: Issue created.
+ Condition: Check the issue's severity or type (e.g., "Critical" severity or "Network Issue" type).
+ Action: Assign the issue to a specific user or group responsible for that type of issue.
![image](https://github.com/drmathew23/Jira-configurations-workflow-automation/assets/155710334/b09cc343-98bf-4024-b704-8ffe34fa38da)
.

.

#### Notifying Team Members of High-Severity Issues

+ Trigger: Issue created with a "Critical" severity.
+ Condition: Issue severity is set to "Critical."
+ Action: Send an email notification to the Admins
![image](https://github.com/drmathew23/Jira-configurations-workflow-automation/assets/155710334/7a2597ff-2d80-4b88-a9e9-b6f2863b2a02)
.

.

#### Automated Reminders for Pending Issues

+ Trigger: Scheduled trigger (e.g., run daily).
+ Condition: Check for issues in "In Progress" status for more than a specified time (e.g., 3 days).
+ Action: Send a reminder to the assignee or post a comment on the issue.
pending issues
![image](https://github.com/drmathew23/Jira-configurations-workflow-automation/assets/155710334/6a66c66e-deb2-47dc-979d-912efa29632d)
## Conclusion
The "Jira Service Management: Configuration, Workflows, and Automation" project showcases the various features of Jira that optimize IT service management processes. By carefully configuring Jira Service Management, designing efficient workflows, and implementing smart automation, organizations can significantly improve the speed, accuracy, and quality of their IT services.

## Future Directions
In the following project, we will look at example scenarios and study the lifecycle of a ticket from creation to resolution.

# Thank you! 🎉

