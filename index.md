The Idea
--------

The idea behind PrismaLog is to use a simple time tracking application. Most applications try to cover the complete process with many functions or to combine the simple process into a smart design. This often leads to complex apps. 

PrismaLog has been intentionally reduced to a few features. Reporting, analytics, invoicing, scheduling and many other tasks can be done with the exported data in other applications.

With PrismaLog, the focus is on the simplest possible time recording with a clearly defined specification of a 3-level hierarchy. First the projects are defined, then the stories and then the tasks. Under this hierarchy, as many log entries as desired will be created for each task.

Introduction
------------

After startup, the application shows all existing projects (or empty tables). The layout shows projects, the corresponding stories for each project and the tasks for each project. A multiple number of log entries can be created for each task.

<div class="extended-markdown tip border rounded-1 mb-4 p-3 border-blue bg-blue-light f5">
<Strong>Note:</Strong> Double click on a row opens the edit mode for the clicked entry.
</div>

### Content

- Definition
- Functions
- Feature list
- [Privacy Policy](privacy_policy.md)

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

### Favorites

Favorites are used to quickly start and stop a task. A favorite can be set in a task. Double click on a task entry and click the favority icon (on or off).

![status bar icon](img/statusbar-entry.png)

<div class="extended-markdown tip border rounded-1 mb-4 p-3 border-red bg-red-light f5">
<Strong>Note:</Strong> Adding new favorites is only possible with stopped logging. 
</div>

If a task is set as a favorite a new entry is available in the status bar of the PrismaLog Mac OS Icon.

In the status bar it is also possible to reopen the window of the application or to close the application.


### Export

The recorded log entries can be exported as a csv file. This makes it possible to import them into other applications in order to analyze the workload.

<div class="extended-markdown tip border rounded-1 mb-4 p-3 border-red bg-red-light f5">
<Strong>Note:</Strong> Only the log entries are exported. Projects, stories and tasks without log entries will not be exported!
</div>

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
	- edit name and comment
	- Delete function


### Stories

- List with names and time per story
- sortable columns
- double click opens edit mode to the clicked story
	- edit name and comment
	- Delete function
	- Move story to different project (with all of the tasks and logs)

### Tasks

- List with names and time per task
- sortable columns
- double click opens edit mode to the clicked task
	- edit name and comment
	- set task as favorite
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
	- Edit all entries (begin, end, comment, ...)
	- Delete log
	- Move log to different project and/or story and/or task

### Mac OS status bar

- start/stop logging of favorites
- reopen application window
- quit application

### Export

- Export as simple csv-file with basic information
- Export as detailed csv-file with IDs of all records


- - -

[Privacy Policy](privacy_policy.md)