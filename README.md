# Smart_Air-— Android Team Project
Smart_Air is an Android application built by a team to allow children suffering with asthma, their parents, and their doctor to track and manage their condition
The app uses a real-time backend to store and sync user data across devices.

This repository documents my **personal contributions** to the project.

## Team repository

Full team project (including all members’ contributions & features) is here:
https://github.com/ericproud/Smart_Air_App 

This repo exists to document my individual contributions.
## Demo



https://github.com/user-attachments/assets/3ce8f39e-daff-4d8d-820f-11fce62c7546



## Project features (from team project repo)
>  * Logging and viewing medicine uses
> 
> * Storing medicine inventory amounts
> 
> * Triaging children based on their current condition to provide guidance on next steps during a possible asthma attack
> 
> * Ability to share important summaries and logs with a childs doctor at a parents discretion
> 
> * Motivational materials encouraging proper management of a child's condition
> 
> Much more

## Tech Stack
* Tech stack
* Java (Android backend logic)
* XML (UI layouts)
* Firebase Realtime Database (backend data storage & sync)
* Android Studio
* Jira (sprint planning and issue tracking)

## Professional Process (Agile/Scrum)
We developed this application over three sprints, adhering to strict industry-standard Scrum practices: 
* Jira Management: Used Jira to track user stories and assign story points based on task complexity.
* Daily Standups: Participated in at least three "Standup" meetings per week to discuss completions, upcoming tasks, and blockers.
* Team Agreement: Established a signed agreement for communication protocols, response times, and contingency planning.

## My contributions
* Built the Streaks & Badges system (frontend + backend), which tracks medication adherence (Controller, Technique, Rescue) by reading from Firebase and displaying real-time progress as streaks and achievement badges.
* Designed and implemented the Controller Training page, including:
  * Instructional video and usage description
  *   Built-in medication timer
  *   Emergency escalation logic that notifies a parent
* Implemented a 3-page Daily Check-In logging flow:
  *  Form page that collects symptom and usage data and writes it to Firebase
  *  History page that reads and displays past logs from Firebase
  *  Navigation hub page that routes users between logging and history views
* Developed responsive Android UI layouts using ConstraintLayout and MaterialCardView to present health data clearly and accessibly for children and parents. 
  

