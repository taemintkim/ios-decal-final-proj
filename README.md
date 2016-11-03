Roomi
===================

Author
-------------
 - Thomas (Tae Min) Kim

Purpose
-------------
Roomi is an app for easier & better communication between roommates. 

Features
-------------
 - Add your roommates and housemates via Facebook
 - Each member can add items to a global chore list 
  > "do the dishes!"
    "can somebody get more ice cream??"
 - Each task changes color based on how long they have been uncompleted for.
 - Set repeating reminders
  > "rent is due soon!"

 - Keep track of who did which tasks
  >"Dustin took out the trash last week"
  
 - Keep author of task creations/notifications anonymous!
  > nobody wants to look like a nagger

> Possible additional features:
> 
> - smart bills
>  - calculates bill splitting.
>  - integration with venmo
> 
> - task scheduler in calendar layout
> - is roomi home?
>  - shows which roomi is home

Control Flow
-------------
 - App launch
 - User log-in screen
 - Add roomi: Shows a copy&paste-able unique link that users can send to their roommates.
 - Main tasks: a list view of all of your tasks. Each task is colored by age; tapping on a task expands the cell to show more details and options; swipe left to mark and dismiss as complete; tap on a task to show your roomi's that you did it.
 - Create task: user can set
  -  title text
  - detail text 
  - deadline 
  - repeats (day/week/month)
  - notifications

Implementation
-------------
#### Model
- Task.swift
- TaskTableViewCell.swift
- Roommate.swift 
- Login.swift 
- Alarm.swift


#### View
- TaskView
- TaskTableView
- LoginView
- AddRoomiView
- TaskDetailView
- CreateTaskView
#### Controller
- TaskTableViewController
- LoginController
- AddRoomiController
- TaskDetailViewController
- CreateTaskViewController

