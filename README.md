# ALC Mentors Management System (MMS) Mentor-Manager

This is the app for the Mentors Management system admin. MMS is a people management app that enables proper 
coordination of mentors needed to execute projects, ranging from recruitment to off-boarding.
The project will be built using 100% Kotlin and using the Model-View-ViewModel (MVVM) architecture.
You can read more about the guidelines of the recommended architecture [here](https://developer.android.com/topic/architecture)

# Prerequisites

The app has the following minimum requirements:
1. `minSdk` 21
2. `targetSdk` and `compileSdk` 32
3. Android studio Chipmunk | 2021.2.1 | Patch 1 or higher is recommended

# App Features

The main app features and functionalities are as follows:
1. Authentication/Authorization 
2. Recruitment
3. Communication and Engagement
4. Program Scheduling
5. Activities Tracking and Reporting
6. Discussion Forum

There are three groups of user categories namely `Admin`, `Mentor Manager(MM)`, and `Mentor`. The expected access levels for the group
users is listed as follows:

##  Mentor Manager
- Login/Logout
- Set up my profile
- Access assigned programs
- Add mentor to the system
- See the list of all mentors
- Browse mentor’s details
- Search mentors by name, category, region, program, engagement status
- Assign/unassign mentor to program
- Generate mentors’ report
- Share the report
- Delete mentor
- Receive notification from mentor activities
- Generate mentor certificate
- Share the certificate with Admin
- Send approval request for  mentor certificate
- Send broadcast message to all MM
- Send broadcast message to all mentors
- Chat 1:1 with any user
- Engage on the discussion forum

# Development tools of choice

For this project, stick to the recommended Jetpack Components as much as possible. The idea is to give knowledge of these tools
and your certification will be on them. You can read about them [here](https://developer.android.com/jetpack/getting-started)

# How to use this repo

To use and contribute to the project, do the following:
1. For it to your GitHub account
2. Open a feature branch. Make sure the name is descriptive for your branch but not too long. Lead with what the the branch is doing
eg new feature or bug but follow this pattern `type/branch-description` eg `feature/add-login-functionality`
3. Open a pull request against the develop branch and request a review from others.
4. Merge the PR to develop and proceed
