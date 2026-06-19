README DOCUMENT

Project Name: Task Manager

Description

Task Manager is a Java-based application used to create, manage, organize, and track tasks. Users can create tasks, assign priorities, update task statuses, set due dates, add tags, and monitor overdue tasks.

Features

A. Create new tasks

B. Update task status

C. Set task priorities

D. Add and remove tags

E. Set due dates

F. Track overdue tasks

G. View task statistics

H. Store and retrieve task information

Technologies Used

A. Java

B. LocalDate and LocalDateTime API

C. Collections Framework

D. File-based storage system

Installation Requirements

A. Java Development Kit (JDK)

B. IntelliJ IDEA

C. Git (optional)

Installation

A. Download or clone the project.

B. Open the project in IntelliJ IDEA.

C. Configure the correct JDK.

D. Build and run the application.

Basic Usage

A. Create a task.

B. View tasks.

C. Update task status.

D. Change priority levels.

E. Set due dates.

F. Add or remove tags.

G. View statistics.

Project Structure

A. TaskManager.java
Handles task creation, updates, deletion, and statistics.

B. Task.java
Represents a task and contains business rules.

C. TaskPriority.java
Defines available priority levels.

D. TaskStatus.java
Defines available task statuses.

E. TaskStorage.java
Handles saving and loading tasks.

Configuration

A. Storage location is provided when creating a TaskManager object.

B. Task data is saved using the storage layer.

Troubleshooting

A. Invalid Date Format

Use the format YYYY-MM-DD.

B. Task Not Found

Verify the task ID exists.

C. Data Not Saving

Check that the storage file path is valid.

Contributing

A. Fork the repository.

B. Create a branch.

C. Make and test changes.

D. Commit and push changes.

E. Submit a pull request.

License

Educational use only.


STEP-BY-STEP GUIDE

How to Create and Complete a Task

Prerequisites

A. Task Manager must be installed.

B. User must have access to the application.

Steps

1. Create a Task

Enter the task title, description, priority, due date, and tags.

The system creates a new Task object and stores it.

2. View the Task

Display the task list and verify the task exists.

3. Update Task Progress

Change the status from TODO to IN_PROGRESS.

4. Complete the Task

Change the status from IN_PROGRESS to DONE.

The system will:

A. Update the task status.

B. Record the completion date and time.

C. Save the updated task.

Common Mistakes

A. Using the wrong date format.

B. Using an invalid task ID.

C. Forgetting to save updates.

Troubleshooting

A. Task does not appear.

Verify the task was created successfully.

B. Status does not change.

Check the task ID and status value.

C. Completion date is missing.

Ensure the status was changed to DONE.


FAQ DOCUMENT

1. What is Task Manager?

Task Manager is an application used to create, organize, and track tasks.

2. How do I create a task?

Provide a title and optional details such as description, priority, due date, and tags.

3. What statuses are available?

A. TODO

B. IN_PROGRESS

C. DONE

4. What are priorities used for?

Priorities help determine the importance of tasks.

5. Can I add tags?

Yes. Tags can be added or removed from tasks.

6. What makes a task overdue?

A task is overdue when its due date has passed and its status is not DONE.

7. How do I complete a task?

Update the task status to DONE.

8. What happens when a task is completed?

A. Status changes to DONE.

B. Completion time is recorded.

C. Task information is updated.

9. Can I change a task's priority?

Yes. Priority can be updated after task creation.

10. Can I change a due date?

Yes. Due dates can be modified at any time.

11. Why am I getting a date format error?

Dates must use the format YYYY-MM-DD.

12. How is data stored?

Data is stored using the TaskStorage component.

13. Can I view statistics?

Yes. Statistics include:

A. Total tasks

B. Tasks by status

C. Tasks by priority

D. Overdue tasks

E. Recently completed tasks

14. What should I do if a task cannot be found?

Verify the task ID is correct.

15. What should I do if changes are not saved?

Check the storage path and verify the application can write to the file.


What I Learned

A. README files explain the project structure, setup process, and usage.

B. Step-by-step guides help users perform specific tasks.

C. FAQ documents answer common user questions.

D. AI can quickly generate documentation, but developers should verify accuracy before publishing.
