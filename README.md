# Capstone-Project
1. Describe the PROBLEM you are attempting to solve in detail
	Teachers have different preferences where they like to assign homework.
	Students are involved in many activities.
	This creates a complication where students are trying to manage where all of their assignments are while trying to fit it all into their busy schedules. 
	Currently there is not one place students can look and find all of their assignments, instead they have to go to different sites which depend on the teacher’s choice of where they like to assign homework.

2. CRITERIA. List your criteria
	Need to collect assignments from multiple sources (OnCampus, Google Classroom).
	Need to organize them into a sorted order making it easy for the user, which is the student, to see what they need to do and when they need to do it by
	Need to be able to complete assignments and update the list of homework
	Want to be efficient in size as possible, because this project is built for everyday use in a school we do not want to have to attach a huge device to a computer

3. DESIGN CONSTRAINTS.
	How the computers we use in school work, our program is designed for students in school so it must be compatible with a mac.
	The ways teachers currently assign homework, currently in Totino-Grace teachers use OnCampus and Google Classroom, we can not modify this greatly as teachers’ plans are already connected to one of these methods of assigning homework.
	How Google Classroom and OnCampus currently work, due to both programs being established, we are not able to change how they function
4.  RESEARCH: 
	Many useful google applications are organized together in a simple interface that is easy to use. This solves the problem of having to go to completely different locations for everyday apps which wastes time and presents the risk of losing information by forgetting where it is kept. This is similar to our problem as to find every assigned homework, students must go to OnCampus and google classroom to find every assignment. Although this solution is efficient, it is not tailored to a student’s needs. It does not present an easy way to find homework, with it being buried in the classroom app, making it easy to forget assignments when faced with a lack of time. 

	The Apple home screen gives an organized layout which combines any application for easy access. The home screen’s simplicity allows it to be understood by any user, making it suitable for anyone who uses an Apple device. Although this works well for what it was designed to do, it does not provide a space that is dedicated to assignments, making it difficult to see what homework is expected of the user.

	The Apple Mac’s Stickies app offers an easy to use space for putting any homework that is assigned. This is a great way for students to track what homework they need to complete in one place and is simplistic in its design. Where the stickies app falls short is that it is not connected to the teacher’s assignments. Although it is a great tool for those who use it and are able to keep it perfectly updated, it requires time and effort to align it with what the teacher assigns and then rotate out what homework is due. In addition, the Stickies app presents the risk of not creating a note for an assignment, which could lead to a student completely forgetting to complete the homework.

	Apple’s Reminders app has the ability to regularly update what assignments are due on a daily basis. When the reminders app is perfectly utilized, it enables the user to see what homework is due and plan their schedule accordingly. Although it is theoretically a great solution, due to the constant need to be updating the reminders with creating new ones and scheduling times, it creates risk of the student either not setting the date right or forgetting to create a new reminder. In addition, it was not primarily centered on schooling which, when used by a student, does not offer many essential aspects such as being able to group reminders into school subjects.

	Although basic, a calendar offers a single space to combine many assignments in one place for an easy look at what the user needs to do for the week. What a calendar does that the other solutions do not is effectively create a chart where someone can see all they need to do for the next day, week, or month. The calendar shows the user what they need to complete in a neat order, but the calendar can not update itself. This leads to the possibility of human error in either not putting an assignment on the calendar or, because the calendar is not a computer application, easily being misplaced and forgotten about.

	Whiteboards offer a space where teachers can show their assignments and what needs to be done. When visible, students can see the teacher's written notes about what homework is assigned and plan accordingly. Through using a whiteboard, teachers are able to communicate anything they want about a homework assignment, but only when class is in session. When students are outside of the classroom or at home, they are not able to see the homework assigned, which often leads to students forgetting about homework assignments.
5.  GOOGLE PATENTS RESEARCH.
https://patents.google.com/patent/US9558475 - Location based to-do list reminders(Avaya)
	
	Reminds a user to complete a task based off of a geographical location.
	Pros: Would be able to remind you to do homework at home or turn in homework at school
	Cons: Need to be able to obtain location all the time
		
https://patents.google.com/patent/US20110314402A1/en - Flagging, Capturing and Generating Task List Items (Microsoft)
	
	This patent automatically generates reminders off of content given to the program
	Pros: Can generate a reminder without a lot of user interference
	Cons: Takes a lot of space to show a reminder, we would like to be more efficient in how we show the tasks

https://patents.google.com/patent/US10241644B2/en - Actionable reminder entries(Apple)
	
	This patent creates a way to check if the task has been completed
	Pros: Able to automatically check to see if an item from an assignment list should be removed
	Cons: Would be difficult to make sure the app would recognize that the action was completed, and the user needs to create the reminder


https://patents.google.com/patent/US10977621B2/en - Action based to-do list
	
	This program creates a to-do list and updates it according to the user’s actions.
	Pros: Utilizes different actions to determine if the task has been completed to automatically update the list
	Cons: Must be manually updated to add assignments


https://patents.google.com/patent/US10453325B2/en?q=create+reminders&oq=create+reminders - Creation of reminders using activity state of application

	This product will update a list of reminders once an activity state (a screen showing that a task has been completed) has been reached
	Pros: Way to automatically update a to-do list and tell the user what they still need to complete
	Cons: requires a screen that shows that the activity has been completed, would need to be added into many assignments

6. EXPERTISE
	The most important skill that we need to completely understand is computer science. Due to our project most likely using a program, the understanding of software and how it functions and can be modified is required. We must also be experts on what our target audience looks for in a homework list. We must know what students expect from a homework displaying program and where they feel currently that technology fails them in terms of notifying them about homework. We must also know the needs of a teacher. We must know what a teacher values most in assigning homework and their perspective on the effectiveness of the current software.

7.  BRAINSTORMING:
	Our first idea is that there is a device in the doorway of every classroom and when a student places their computer by the machine, it updates a calendar and adds an assignment that the teacher puts on the machine. It could then sort through and make a list of assignments that need to be completed.
	There would be a unique code that would be put on each piece of homework that could be recognized and scanned through using light sensors, and then be sent to an app to be stored in one place. At the start of each week it would show you what needs to be done throughout the week, and at the start of each day it would show you what is homework for the next day. 

	An app that can see the email that is sent when a teacher assigns homework and create a note on a calendar that has homework that is assigned. It would then create a window that displays what needs to be completed. 
	A screen made of LEDs that could be attached to the back of a laptop case. There would be three LED lights for each subject, and when homework is assigned, you would tell an attached app what homework it is and when it is due, and then when the due date approaches it would light up. For each subject, It would show one light to signal that there is at least one assignment ongoing, two to show that it needs to be completed in a week, and three to show that it needs to be completed by the next day

	Our final idea is to make an extension that combines assignments from OnCampus and Google Classroom and puts them into a homework list. This list could then be sorted and would display all the assignments that still need to be completed. Because it is tied to OnCampus and Google Classroom, the user would not have to enter in the assignments reducing the risk of not seeing homework that was assigned.
