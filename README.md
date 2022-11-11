<p>
<img height=70 src="https://www.vectorlogo.zone/logos/kotlinlang/kotlinlang-ar21.svg"/>
 
 
<img height=70 src="https://www.vectorlogo.zone/logos/android/android-ar21.svg">
 
 
<img height="70" src="https://www.vectorlogo.zone/logos/git-scm/git-scm-ar21.svg">
</p>

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
#### Libraries:
- Dagger Hilt
- Retrofit
- ViewModel
- LiveData
- Coroutines
- ViewBinding
- Navigation Components
- etc. 

# How to use this repo

To use and contribute to the project, do the following:
1. Fork it to your GitHub account.
2. Clone the repo with the command git clone to your local mechine.
3. Open a feature branch from the 'develop' branch. 
4. Make sure the name is descriptive for your branch but not too long. Lead with what the the branch is doing
eg new feature or bug but follow this pattern `type/branch-description` eg `feature/add-login-functionality`.
5. Ensure your branch is up to date with latest changes before pushing.
6. Reference the issue you worked on in your PRReference the issue you worked on in your PR.
7. Open a pull request against the develop branch and request a review from your Team Lead.

## Design
- The design can be find [here](https://www.figma.com/file/JNZKj3lachPypSOMBOhC1e/MMS-ALC-Mobile-Project?node-id=0%3A1) 
- Work on your Team assigned task eg. Team 1, Team 2 etc.
- NOTE: Stickly adhere to the style guide on the design, buttons, texts etc. 

## Creating issue for your Teams
- Your Issues should take this simple pattern for easy identification by your team members: feature or bug name-mmm-team-5
- Find a sample [here](https://github.com/ALCOpenSource/alc-MMSystem-mentorManager/issues/7)
