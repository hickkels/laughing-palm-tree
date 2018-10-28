# X-Team 83 Scheduling Assistant

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

Our team would like to solve the problem of poor organization in workplaces.

When people's schedules are not all merged, there is a possibility scheduling conflicts arise. A program that could fix this would create an environment where everyone enters availability, and a schedule is created with all of this in mind.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

A auto-scheduling assistant for a workplace.

2. Output: Describe the output your program will produce.  Include and example format of the output produced.

It will be a GUI that will have a scrollable table with each worker, the time they work each day, and total hours worked.
 |Name  |Days of Week and Hours Working|... | Total Hours Worked For Week|  

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.

The user starts by inputing a username and password

After the username and password are verfied as a user, the user is taken to a page where they have the option to select availability for the week in the form of a grid containing days of the week and times where you can click boxes to mark when you are avaiable.


4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.

 It will be a GUI that has a scrollable table. There will be some buttons for different purposes like adding/deleting/changing a worker, adding/deleting/changing a manager, or adding/deleting/changing working time.


5. Types List: Break your solution idea down into units that you think can be implemented with a single class.

First we would start with a user class. This class would have worker and manager subclasses. Then we would implement a schedule class that implements the data structure class that generates the schedule. After that, we would do a user interface class that would have logging, employee, and manager user interfaces.

Name each interface or class and briefly describe its function or purpose.

user class - store usernames, passwords
worker subclass - normal workers input availability
manager subless - similar to worker class, can see everyone's schedule, and has seperate rules for scheduling
schedule class - generates the schedule
user interface - draws the user view to the screen


## Edit and Submit this file and any figures referenced by this document.

