# sre-github-lab
requirements documentation for a student task tracker

# Student Task Tracker

## Overview
Students need a simple way to track coursework tasks and see what remains. The proposed Student Task Tracker will help students organize their academic activities, save tasks, and monitor their progress easily.

## Scope
- In scope: Add a coursework task with a title.
- In scope: Display all saved tasks.
- In scope: Mark a task as complete.
- Out of scope: Fee payments.
- Out of scope: Automatic grading.

## Stakeholders
- Student: Records tasks and checks academic progress.
- Instructor: Reviews project requirements and understands student needs.
- Project maintainer: Manages project documentation and future updates.

## Functional requirements
- FR-01: The system shall let a student create a task with a title.
- FR-02: The system shall display the student's saved tasks.
- FR-03: The system shall let a student mark a task complete.

## Nonfunctional requirements
- NFR-01: With 100 saved tasks, the task list shall appear within 2 seconds in at least 95 of 100 trials on an agreed test device.
- NFR-02: Every task action shall work using only a keyboard, checked against each documented task workflow.

## Acceptance criteria
- FR-01: Given the title "Read Chapter 1", saving a new task makes that title appear in the task list.
- FR-02: Given two saved tasks, opening the list shows both titles.
- FR-03: Marking an incomplete task complete changes its displayed status to Complete.

## Assumptions and open questions
- Assumption A-01: Students will have access to a device and internet connection.
- Question Q-01: Should students receive reminders for upcoming tasks?
- Question Q-02: Which device will be used to test NFR-01?

## Project status and viewing
This is a documentation-only project. No application has been built.
Clone the repository and open README.md in Notepad, or read it on GitHub.

## Author
Student Author--SEF25ss

## Contributing
Create a documentation branch, edit and review README.md, commit and push the change, then open a pull request for review.

