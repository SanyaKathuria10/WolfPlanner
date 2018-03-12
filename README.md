# WolfPlanner
### Problem Statement
With the number of tasks increasing day-by-day, it is becoming difficult for individuals to manage so many tasks considering the varying amount of time available and required to complete them. It requires continuous and active effort to create weekly schedules. This leads to wastage of valuable time, and poor planning might lead to excessive workloads. In such situations, an application that makes a schedule (time-table) for the individuals taking into account their pending tasks, deadlines will be a great asset for students. 
 

### Basic Flow of the System
Before showing a typical communication with the bot, let us discuss some points about the application.
WolfPlanner is designed for students to help them in planning their activities by generating a weekly schedule. Thus, the intended user of the system is student.

Every new student user, receives a Slack invite to join the workspace inorder to access the WolfPlanner bot.
1. Student starts conversation with the bot with a greeting like `Hi`, `Hello`
2. The bot responds to the user asking for the unity id
3. The student enters the unity ID and the student profile is created.
4. The student can now access different options such as `add task`, `add course`,  `view tasks`, `view courses`, `view tasks` and `fetch schedule`
At any point of the conversation the user can access these commands by asking for `help`.
5. The student can `add course` which the user interacts with a popup dialog which takes the course details as input,
6. The student can `add tasks` which include tasks such as Project, Interview Prep, Job, Homework among others. Task input is done in a way similar to that of adding courses.
7. Once the tasks and courses have been entered,  `view course`, `view tasks` commands can be accessed to view them respectively.
8. Now, **after the courses and tasks have been added, the student can request for the schedule** to be generated, using the `fetch schedule` command.
9. The bot generates the schedule for the student and the week's schedule is generated. 

### Use Cases
Whenever a new user joins, the conversation goes like this - 
![new user intro](https://user-images.githubusercontent.com/18022447/37309791-5b0d222a-2618-11e8-8ffb-fbe82226f80b.gif)

_**Fig 1.** When a new user starts conversation_


The most important use cases of the application are -

#### 1. Add course -

Students add a set of tasks such as lecture timings and days which stay fixed throughout the semester. 

![add courses](https://user-images.githubusercontent.com/18022447/37310346-01c44bb0-261a-11e8-9991-6f4c804d7386.gif)

_**Fig 2.** Add course_

#### 2. View courses -

Students can see their course listings, if needed, to get an idea of the time they will not be available for any task.

![view courses](https://user-images.githubusercontent.com/18022447/37310381-1b7ffa68-261a-11e8-9d62-3d256fe893d3.gif)

_**Fig 3.** View courses_

#### 3. Add task -

Students can add various other tasks to their To Do list along with the amount of time they expect to keep aside for it. These can be tasks like Home works, Coding practice, Project Discussions, etc.

![add task](https://user-images.githubusercontent.com/18022447/37311307-257c2b56-261d-11e8-9ac3-d69e3e44be44.gif)

_**Fig 4.** Add task_

#### 4. View tasks - 

Students can take a look at the tasks they have this week. This can help them make sure that they added all the tasks they want to complete in the current week and did not miss out anything. 

![view tasks](https://user-images.githubusercontent.com/18022447/37311329-36399cc6-261d-11e8-9cc4-189431084bf5.gif)

_**Fig 5.** View tasks_

#### 5. Generate schedule -

Students can generate the schedule for the week, based on the fixed tasks they have and the additional tasks they need to get done in the week. They can set the window size according to their convenience i.e. some users may want their tasks to be scheduled even in small slots of time, whereas others might want to take rest if the available amount of time is too small for their liking.  
Also, if they want to regenerate the schedule due to addition of tasks during the week, they can call this again to get the updated schedule.

![fetch schedule](https://user-images.githubusercontent.com/18022447/37311732-d86e54c2-261e-11e8-8983-24452b15b32e.gif)

_**Fig 6.** Generate schedule_

#### 6. Add to calendar -

Students can easily export their generated schedule to Google Calendar for easy access for the schedule and setting reminders about the scheduled events.


### Contributors
Neel Kapadia - [ntkapadi](https://github.com/neelkapadia)<br/>
Rohit Naik - [rtnaik](https://github.com/rohitnaik246)<br/>
Sainag Shetty - [sgshetty](https://github.com/SainagShetty)<br/>
Rohan Chandavarkar - [rgchanda](https://github.com/RohanChandavarkar)
