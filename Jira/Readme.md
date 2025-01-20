# Agile Process
Jira is used as a project management and bug tracking tool for Bug Resistance web application.
In this project, Agile based scrum development model is followed to build the web application.<br>
### Jira As Agile Project Management Tool
***
<b>Step 1:</b><li> Bug Resistance application requirments are collected and product backlog is designed.</li>

<b>Step 2:</b><li>In Jira, product backlog is created with epics, users stories and sub-tasks.</li>
<li>The whole application is divided into 4 epics. They are:</li><ol><li>Home</li><li>Course Admission</li><li>QA Services</li><li>Contact Us</li></ol> 
<li>Each epic is broken down in multiple user stories and each user story is broken down into multiple sub-tasks.</li><li>Some sub-tasks are inter-related or dependent on each other </li><br>

<b>Step 3:</b><li>The whole application is developed into 3 sprints.</li>
<li>Each sprints will have their own sprint backlog including selected epics, users stories and sub-tasks from profuct backlog and each sprint backlog will be organized before the sprint starts.</li>
<li>Each sprint will last for minimum 1 week to maximum 4 weeks.</li>
<li>Each sprint will result into a released version of the web application.</li><br>
<table>
<th>Sprints</th>
<th>Sprints Descriptions</th>
<th>Released Versions</th>
<th>Released Versions Descriptions</th>
<tr>
<td>BUR Sprint 1</td> 
<td>Homepage epic and it's user-stories and tasks and sub-tasks are included in the sprint.</td>
<td> Bug Resistance Version 1.0</td> 
<td>After successful completion of BUR Sprint 1, version 1.0 is released.</td>
</tr>
<tr>
<td>BUR Sprint 2</td>
<td> Course Admission epic and it's user-stories and tasks and sub-tasks are included in the sprint.</td>
<td> Bug Resistance Version 2.0</td>
<td>After successful completion of BUR Sprint 2, version 2.0 is released.</td>
</tr>
<tr>
<td>BUR Sprint 3</td>
<td> QA Services and Contacts epic and it's user-stories and tasks and sub-tasks are included in the sprint.</td>
<td> Bug Resistance Version 3.0</td>
<td> After successful completion of BUR Sprint 3, version 3.0 is released.</td>
</table>

### BUR Sprint 1
***
![Image](https://github.com/user-attachments/assets/f857677f-fb6d-4904-9964-35afea5fbd58)

### BUR Sprint 2
***
![Image](https://github.com/user-attachments/assets/32aa75ea-e5de-4000-aa24-f7ee5cdb981a)


### BUR Sprint 3
***
![Image](https://github.com/user-attachments/assets/a9c0a799-a354-4257-b689-9cd76c51590d)


### Jira Reports
***
<i><b>Bug Resistance Sprint 1,2,3 have the Jira reports discussed below.</i></b><br>
<b>Sprint Report:</b> This sprint report shows the performance of the team in each sprint. It Shows if the team is overcommiting or excessive scope creep.</b><br>
<b>Burnup Chart:</b> This chart show how much work has been completed in the Bug Resistance project. As there are total 
3 sprints in the whole project, for each sprint there is a burnup chart to show the progress of that sprint. <br>
<b>Burndown Chart:</b> A burndown chart shows how much work is remaining to be completed in the Bug Resistance project. All the 3 sprints 
have their own individual burndown chart.<br>
<b>Velocity Chart:</b> It measures how much work a team can complete in
the given time. It tracks velocity over the 3 sprint.<br>

### Jira As Bug Tracking Tool
***
<b>Defect Report:</b> All the defects found in the modules are reported to the team as defect report. The defects should be closed within that sprint or maybe prioritized later for the future sprints.<br>
<br><i>The Bug Life Cycle that is followd in the project is given below:</i><br>
![Image](https://github.com/user-attachments/assets/f64aaf7c-a31e-42fd-b5a7-eec839b88243) <br>

<li><b>Verify Bugs:</b> It is a sub-task and all bugs that are found during the sprint included here and reported to the dev.</li>
<li><b>To Do:</b> The QA stated the task as <b>To Do</b> and assigned it to the dev.</li>
<li><b>In Progress:</b> After finding the bug, it is send to the developer. The developer checks the bug and if it actually a bug then dev started working in the bug and the task is stated as <b>In progress</b> state.</li>
<li><b>Dev Done:</b> After finishing the task, dev stated the bug as <b>Dev Done</b></li>
<br><i>There are defects that are not recognized as bugs by Dev.There are multiple cases for this: </i>
<ol>
<li><b>Not a bug:</b> The defect is not an bug and though QA verifies it and when the PM approves it,the bug is closed.</li>
<li><b>Future releases:</b> Not important enugh to fix the bug in the current sprint.QA identifies those bugs and when the PM approves it, it is moved to future sprints.</li>
<li><b>Duplicate Bug:</b> The bug is duplicate and the actual bug is already reported.</li>
  <i>Every rejected bugs from the developer is tested by QA in <b>QA Done/QA Check</b> state</i>
</ol>
<li><b>Fix Bugs:</b> It is a sub-task and the dev keeps the fix bug in this subtask and assigns it to the QA.</li>
<li><b>QA Done/QA Check:</b> After that QA started to check the bug and the task is stated as <b>QA Done/QA Check</b>.</li>
<li><b>Test Done:</b> After succesfully completeing all the test on the bug, QA assigns the bug as <b>Test Done</b> and if the bug is still not fixed,QA sends the bug to <b>Verify Bugs</b> sub-task  and stated the bug as in <b>To Do</b> state.</li>
<li><b>PM Check:</b> If the testing is passed, QA assigns the bug to PM for verifying and the task is stated as <b>PM Check</b></li>
<li><b>Finished:</b> After verifying the bug, when the bug is succesfully fixed PM closes the bug and the bug is stated as <b>Finished</b> and when the bug is not successfully fixed, the bug is send back to <b>Verify Bugs</b> sub-task and the task is stated as <b>To Do</b>.</li>

