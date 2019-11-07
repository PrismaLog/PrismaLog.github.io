The Idea
--------

The idea behind PrismaLog is to use a simple time tracking application. Most applications try to cover the complete process with many functions or to combine the simple process into a smart design. This often leads to complex apps. 

PrismaLog has been intentionally reduced to a few features. Reporting, analytics, invoicing, scheduling and many other tasks can be done with the exported data in other applications.

With PrismaLog, the focus is on the simplest possible time recording with a clearly defined specification of a 3-level hierarchy. First the projects are defined, then the stories and then the tasks. Under this hierarchy, as many log entries as desired will be created for each task.

Introduction
------------

After startup, the application shows all existing projects (or empty tables). The layout shows projects, the corresponding stories for each project and the tasks for each project. A multiple number of log entries can be created for each task.

Note: Double click on a row opens the edit mode for the clicked entry.

### Content

- Definition
- Functions
- Feature list

Definition
----------

A project is a distinct target of related activities. Related activities (tasks) are summarized as stories. Since tasks can also be stopped, a task can contain a large number of logs.

For example: A story represents a user feature or use case. A task represents a set of engineering work.

![PrismaLog-Screen](img/01.png)

Functions
---------

Projects can be created at any time; a double-click on a project line opens project editing.

Each project (as well as each story and task) gets a name and can (optionally) get a comment.

![Buttons](img/17.png)

To create new projects (stories or tasks), use the buttons in the toolbar. The left button is used to create a new project. The second button is used to create stories for a project. To do this, the corresponding project must be selected beforehand.

The third button for new tasks has to be used accordingly. Only after selecting a story a task can be created for this story. - The recording of the time can be started after a task has been selected (the button with the triangle on the right hand side of the toolbar).

### Export

The recorded log entries can be exported as a csv file. This makes it possible to import them into other applications in order to analyze the workload.

The export function can be found in the menu bar of the application at "File -> Export"

![Export-Menu](img/16.png)

Feature list
------------

Note: Double click on a row opens the edit mode for the clicked entry.

### Toolbar

- Button for creating a new project
- Button for creating a new story
- Button for creating a new task
- Button for starting/stopping logging
- Text box for information

### Projects

- List with names and time per project
- sortable columns
- double click opens edit mode to the clicked project
- Information for project comment
- Delete function


### Stories

- List with names and time per story
- sortable columns
- double click opens edit mode to the clicked story
- Information for story comment
- Delete function
- Move story to different project (with all of the tasks and logs)

### Tasks

- List with names and time per task
- sortable columns
- double click opens edit mode to the clicked task
- Information for task comment
- Delete function
- Move task to different project and/or story (with all logs)

### Logs

- List with
	- begin
	- end
	- duration
	- project name
	- story name
	- task name
	- and comment
- sortable columns
- double click opens edit mode to the clicked log entry
- Delete function
- Move log to different project and/or story and/or task

### Export

- Export as simple csv-file with basic information
- Export as detailed csv-file with IDs of all records

