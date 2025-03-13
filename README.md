# Manual Testing in JIRA using Zephyr Plugin

This repository contains **manual testing** of web Application- **CURA HEALTHCARE SERVICES** & **OPEN CART** in **JIRA Software** using the **Zephyr for Jira** plugin. **Zephyr** is a popular test management tool integrated into JIRA, allowing for seamless management, execution, and tracking of test cases.

## Table of Contents

1. [Overview](#overview)
2. [Prerequisites](#prerequisites)
3. [Setup](#setup)
4. [Manual Testing Process with Zephyr](#manual-testing-process-with-zephyr)
5. [Test Case Management](#test-case-management)
6. [Executing Tests](#executing-tests)
7. [Bug Reporting in JIRA](#bug-reporting-in-jira)
8. [Common Issues](#common-issues)
9. [Contributing](#contributing)
10. [License](#license)

## Overview

This project provides an end-to-end guide for conducting **manual testing** using **Zephyr for JIRA**. Zephyr integrates with JIRA to provide test case management features directly inside the JIRA interface. It includes test planning, test case execution, defect tracking, and reporting.

Key features:

- Create and manage test cases directly in JIRA.
- Track the status of test executions and link defects.
- Integrate with other JIRA projects, making it easier to report and manage issues.
- Enhanced reporting features for test coverage and test execution status.

## Prerequisites

Before getting started, make sure you have the following:

- **JIRA Software** account (Cloud or Server).
- **Zephyr for JIRA** plugin installed in your JIRA instance (Zephyr is available on the Atlassian Marketplace).
- Appropriate permissions in JIRA to create and manage issues, including Zephyr-specific permissions.
- Basic understanding of manual testing, test case creation, and defect reporting in JIRA.

## Setup

1. **Install Zephyr for Jira Plugin**:
   - Navigate to the **JIRA Marketplace** and install **Zephyr for Jira**.
   - If you're using JIRA Cloud, go to **Jira Settings > Apps** and search for Zephyr.
   - If you're using JIRA Server/Data Center, go to **Administration > Manage apps** and install Zephyr from the marketplace.

2. **Clone this repository**:
   ```bash
   git clone https://github.com/yourusername/manual-testing-zephyr-jira.git

## Manual Testing Process with Zephyr
Follow these steps to perform manual testing using Zephyr in JIRA:

## 1. Test Planning
Create a Test Cycle in Zephyr. This acts as a container for your test cases and their execution.
Set the Version or Release you want to test within the Test Cycle.
## 2. Test Case Creation
Create a Test Case: Navigate to Zephyr > Test Cases in your JIRA project and create a new test case.

## Provide details such as:

**Summary:** A concise name for the test case.
**Description:** A detailed description of the test steps, expected results, and preconditions.
**Test Steps:** Break down the test into individual steps with the expected outcome for each.
**Priority:** Set the importance of the test case.
Link Test Cases to User Stories: If applicable, link the test cases to relevant User Stories or JIRA Issues to ensure traceability.

## 3. Test Execution
Execute Test Cases: Once test cases are created, you can begin execution.
In the Test Cycle, select the test case and choose Execute.
As you execute the test, log the results by selecting the Test Status (e.g., Passed, Failed, Blocked).
Capture any relevant information, including screenshots or logs, if necessary.
## 4. Tracking and Reporting
Test Execution Results: Zephyr provides detailed reports on test case execution, including Pass/Fail status, execution times, and linked defects.
Defects: If a test case fails, log a JIRA bug directly from the Zephyr interface and link it to the corresponding test case.
## Test Case Management
Zephyr helps organize and manage test cases effectively within JIRA:

## Organizing Test Cases:

Test cases are organized within Test Cycles or Test Plans.
Test cases can be categorized by components or labels for easy tracking.
Linking to Issues:

Link your test cases to related JIRA issues, such as User Stories, Epics, or Bugs for traceability.
This allows you to easily trace which test cases are associated with which feature or bug.
Test Case Reusability:

Reuse test cases across multiple test cycles or projects.
Edit existing test cases as needed and update them in real-time.
Executing Tests
Start Execution: Go to the Test Cycle and begin executing tests.
Mark Status: After execution, mark the test result as Pass, Fail, Blocked, etc.
Log Defects: If a test case fails, log a defect directly in JIRA from within Zephyr.
The bug report is automatically linked to the test case, ensuring traceability.
Bug Reporting in JIRA
When a bug is found during manual testing, follow these steps:

## Create a Bug Issue in JIRA with detailed information:
**Summary:** Provide a clear, concise bug title.
**Description:** Include steps to reproduce, expected vs. actual results, and environment details.
**Severity/Priority:** Define the bug’s impact and urgency.
**Screenshots/Attachments:** Include relevant screenshots or logs to help developers.
**Link Bug to Test Case:** Once the bug is created, ensure it is linked to the test case that failed.
