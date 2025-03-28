# CS121 - EduFlow

The goal of this project is to create a program in Java that will be used to help students and advisors schedule classes. The interfaces for the students and advisors will be different and will have different methods. 

The student will be able to: 
- See the classes
- Add classes to their schedule
- Drop classes from their schedule
- See their semester credit hours

The advisor will be able to: 
- See the students assigned to them
- Add students
- Open a student's schedule
- Add classes to a student's schedule
- Drop classes from a student's schedule
- See a student's semester credit hours

Sample flow
```
Welcome to EduFlow - A Class Scheduling software!
0) Exit
1) View all students
2) View all student schedules
3) View student schedule
Action: 1

Ilo Adams
Credits: 12
=================
Billy Bob Jones
Credits: 18
=================
Alan Turing
Credits: 16
=================
0) Exit
1) View all students
2) View all student schedules
3) Access student schedule
Action: 2

Ilo Adams
Credits: 12
CS120-2 Intro to Computer Science: Harris, Andy
MATH160-1 College Algebra: Duck, Donald
ENG110-3 English for Dummies:  Hasselhoff, David
================================================
Billy Bob Jones
Credits: 18
MATH200-1 Calculus for Cats: Gebra, Al
PSY100-2 Intro to Psych: Freud, Sigmund
ENG110-3 English for Dummies: Hasselhoff, David
PFW100-4 Weightlifting for Weaklings: Spotter, Anita
MATH211-2 Differential Equations: Newton, Isaac
================================================
Alan Turing
Credits: 16
CS340-1 Coding for Experts: Sharp, Cee
CS498-2 Senior Seminar: Minutt, Last
ENG110-3 English for Dummies: Hasselhoff, David
PFW101-4 Swimming for Fish: Fish, Gold
================================================
0) Exit
1) View all students
2) View all student schedules
3) View student schedule
Action: 3
First name: Alan
Last name: Turing

Alan Turing
Credits: 16
CS340-1 Coding for Experts: Sharp, Cee
CS498-2 Senior Seminar: Minutt, Last
ENG110-3 English for Dummies: Hasselhoff, David
PFW101-4 Swimming for Fish: Fish, Gold
===============================================
0) Exit to Main
1) Add class
2) Drop class
Action: 1
Course Code: CS222
CS222 added!
0) Exit to Main
1) Add class
2) Drop class
Action: 2
Course Code: CS222
CS222 dropped!
```
