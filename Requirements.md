# Requirements Document – Team 12

## 1 Introduction
In an increasingly complex and fast paced society, there is a strong need to do more with less. Therefore, it seems prudent to introduce a tool to help users get organized and maximize their productivity.

The software product delivered at the end of this project will be an Android App titled, TODO. TODO is a mobile Android application that will enable multiple users to manage a list with tasks via an intuitive and responsive UI.

TODO will be capable of adding tasks to, deleting tasks from, and editing tasks in a list. Users will be able specify specific attributes such as the task's name, priority and due date when adding tasks. Moreover, any tasks that are edited will be saved automatically and immediately to prevent data loss. 

At the end of this project, the client will receive the TODO Android app along with a user manual.

## 2 User Requirements

### 2.1 Software Interfaces
Android OS 4.0.3+  
Android OS  
Version 4.0.3 and above  
The system shall run in an Android OS device equipped with a version of the Operating System greater than or equal to 4.0.3. This should target the majority of Android users while diminishing the development effort.  

Android SDK 4.4.2  
Android SDK  
Version 4.4.2  
The system is an Android App. It shall use the Android SDK to handle the interactions between screen components and backend code.  
  
SQLite 3  
SQLite  
Version 3.4.0  
The system shall use an SQLite database to store the tasks and the different users. Communication with the database shall be done using the sqlite package of the Android SDK. Android ships with SQLite version 3.4.0.  


### 2.2 User Interfaces
The system shall interact with its users through a touch-based GUI. The common method of input in Android apps is by the user tapping on different areas of a touch-screen device or by the use of the device's sensors. This App shall not use any input methods other than the touch-screen. Common Android GUI elements, behaviors and transitions shall be used as much as possible to provide a familiar environment for the users of the App.  

### 2.3 User Characteristics
* The intended users of the product shall be Android device owners
* The level of experience of the users is unknown. It shall be assumed that it ranges from novice smartphone users to experts.
* The users' technical expertise is unknown. It shall be assumed that it ranges from people with minimal knowledge on how to run an App in a touch-screen device to people who are very proficient users.
* The users utilize a broad range of devices running the Android OS, which potentially can include different screen sizes and versions of the OS.

### 2.4 Assumptions and Dependencies
* The system shall require Android Ice Cream Sandwich (version 4.0.3) and above.  
* The system shall be targeted to run optimally on smartphone-sized devices. The system may have a specific layout for tablet-sized devices.  
* The system's language shall be English.   
* The documentation shall be in English.  
* The user shall be capable of installing Apps on his/her device.  
* The client shall provide feedback on the initial prototype and documentation no later than Tuesday, February 25th, 2014.  


## 3 System Requirements

### 3.1 Functional Requirements
Requirement Index | Requirement Information
-------------- | ---------------
Func-1 | The system shall be an Android App.  
Func-2 | The system shall display a group of users.  
Func-3 | The system shall allow the user to add a task to a user's task list.  
Func-4 | The system shall allow the user to delete a task from a user's task list.  
Func-5 | The system shall allow the user to edit a task in a user's task list.  
Func-6 | Every task shall have a name.  
Func-7 | The task name shall be a required field in the task creation process.  
Func-8 | Every task shall have a priority. The priority is a required field.
Func-9 | The priority of a task shall take one of 3 values: "Low," "Medium," and "High."
Func-10 | If not modified, the default value for the priority of a task will be "Medium."  
Func-11 | Every task shall have a due date. The due date is a required field.
Func-12 | If not modified, the default value for the due date of a task will be the next day from the moment the user created the task.  
Func-13 | Every task shall present a checkbox to allow users with an option to check and uncheck it.  
Func-14 | Checking a task shall not delete it from the list.  
Func-15 | Users shall be able to hide or show checked-off tasks.  
Func-16 | Users and tasks must be saved automatically and immediately after they are added or modified without requiring an additional step from the user.  
Func-17 | The system shall provide a default user named "Default" during the first execution.  
Func-18 | The system shall provide a way to add separate users.  
Func-19 | Each user shall have a unique name.
Func-20 | The system shall provide a way to switch from one user to another.  
Func-21 | The system shall provide a way to edit the name of a user.  
Func-22 | The system shall provide a way to delete a user.  
Func-23 | The system shall display a confirmation message alerting the user of the fact that deleting a user will delete all of its contents.  
Func-24 | Every task shall display its priority graphically.  
Func-25 | Overdue tasks should be highlighted.  
Func-26 | The system shall not display Android error codes. Natural english language shall be used on all alerts.  
Func-27 | The system shall run on Android OS versions 4.0.3 through 4.4.  
Func-28 | The system should allow the user to sort tasks by due date. In this case, priority shall be used as a secondary sorting parameter.  
Func-29 | The system should allow the user to sort tasks by priority. In this case, due date shall be used as a secondary sorting parameter.  

### 3.2 Non-Functional Requirements
Requirement Index | Requirement Information
-------------- | ---------------
NonFunc-1 | The system shall not display "Application Not Responding" (ANR) dialogs.  

#### 3.2.1 Software Quality Attributes
* Security - Best efforts shall be made to ensure the software does not contain malicious code and will not impact the hosting system in a negative way. This attribute is important because users will not be interested in using a system that impacts their device in a negative way. The stability of the system will be tested by the QA team using manual application testing. The App will be self-contained and will not access data outside its own sandbox.
* Reliability - Best efforts shall be made to ensure the system does not crash during usage, remains active as long as possible while in the background, and avoids any data loss. These attributes are important because users are more likely to stop using an application that crashes during usage or loses data they have spent time entering. As a QA parameter, the system shall be able to perform the following, consistently, without crashing or losing any data: create a minimum of 3 users with 10 tasks each, edit 2 tasks per user, eliminate 2 tasks per user, check and uncheck 2 tasks per user, filter each task list with all the options available, edit one user, and delete one user.
