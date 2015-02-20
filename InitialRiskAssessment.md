# Project 3 Initial Risk Assessment - Team 12
| Version | Release Date | Change Description |
|:--------|:-------------|:-------------------|
|1.0|03/30/2014|Initial Release.

## 1 Introduction

This document identifies potential risks to the project for extending the Mobile TODO List Manager (referred to as MTM) and developing the Web TODO List Manager (referred to as WTM) for Initech per their requirements.

## 2 Risks

### 2.1 Challenge of developing the synchronization of local database (LDB) and centralized database (CDB) requirement

A requirement given by Initech is that MTM must rely on a local database and WTM must rely on a centralized database. A local database must be synchronized with the centralized database when MTM starts or when the users perform an explicit synchronization.

Designing and coding this requirement will be challenging. Our team held a preliminary discussion on possible architectural designs and we were unable to reach a consensus. The team is also considering how conflicts can be suitably handled.

Without suitably addressing this risk, MTM and WTM will either not fulfill the synchronization requirement or the synchronization may be poorly designed.

To help mitigate this risk the team will seek out solutions recommended by other developers for such scenarios from online resources. Other developers have certainly faced similar requirements for past projects. The team will also continue to ponder and discuss possible solutions.

### 2.2 Unfamiliar with MTM Source Code

A different team of engineers developed the current version of MTM.

Our team is unfamiliar with the MTM source code and has no knowledge of its stability.

This risk threatens the team's productivity and consequently compromises the project schedule.

To help mitigate this risk the team will review the source code before beginning development in the construction phase. The project schedule includes plenty of time so that there is time to research the existing code base. The team has also generated a UML class diagram from the source code to aid in understanding the architecture.

### 2.3 Unfamiliar with Google Web Toolkit and Google App Engine

Initech strongly recommends using the Google Web Toolkit for the web part of the project and Google App Engine to deploy the back-end of the web application. Although some team members are quite experienced with other technologies, our team decided that pleasing Initech by using their preferred technologies is the optimal path to take.

Our team must research Google Web Tookit and Google App Engine in order to be competent enough to develop WTM.

This risk threatens the development of WTM. Without knowledge of these technologies, the application cannot be developed.

To mitigate this risk the project schedule includes plenty of time in order to allow team members to get acquainted with these technologies. One of the team members is already comfortable with Google App Engine, giving the team a valuable resource that can help if other team members need help.

### 2.4 Time constraints
Initech set a project timeline of approximately seven weeks and only allocated a budget for 4 part-time engineers. Initech initially set a timeline of approximately four weeks but reconsidered the project deadline after our team expressed concern regarding this tight schedule.

Our team must complete all deliverables for the project in the allotted time period, with certain deliverables required at designated checkpoints, all while working on the project part-time outside of our full-time jobs.

This risk threatens timely delivery of project artifacts to Initech.

To mitigate this risk our team has created a detailed schedule in order to ensure that the team is making sufficient progress throughout the project. The level of detail of the schedule will allow the team to quickly correct if falling behind. Although our team strives to work at a sustainable pace, if unforeseen circumstances arise that force the project to fall behind and require additional resources, the team is prepared to work on the project at a more fervent pace. The team has proven its ability to toil if necessary in the past.

### 2.5 Unfamiliar with the Unified Software Process
Initech requires our team to use the Unified Software Process during this project.

None of our team members have ever used the Unified Software Process in a real-world project.

This risk threatens the team's productivity and consequently the project schedule.

To help mitigate this risk all team members listened to lectures on the Unified Software Process from renowned computer science professor Alessandro Orso from the Georgia Institute of Technology. Additionally, team members have and will continue to consult supplementary material about the Unified Software Process as needed.
