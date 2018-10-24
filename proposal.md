# X-Team 25 Project Proposal

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

Briefly describe a problem that your team would like to solve.  
Describe at a high level a program that could solve that problem.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

Four Year Planner

2. Output: Describe the output your program will produce.  Include and example format of the output produced.

Several possible schedules that satisfy the input conditions. The student can choose which option works best for them. Any options that the student doesn't specify can be used to generate more schedule options. For example, if the student does not have a preference of how many credits to take per semester, both an 8-semester and a 9-semester graduation schedule could be displayed.

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.

There are two inputs: the classes that a student must take to graduate, and various information about the student. Student input includes: previous courses taken, how many credits they prefer to take per semester, and how many semesters they have remaining. Every class has input information including: the number of credits, whether it is offered Fall/Spring, and any prerequisite courses.

Input format could be a CSV table of class information:
CS 400, 3, FS, CS 300
PHYSICS 322, 3, F, PHYSICS 321, MATH 321 //multiple prereqs are extended at end of line

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.

Input area for name, major, and desired credits per semester.

5. Types List: Break your solution idea down into units that you think can be implemented with a single class.

The main class of our program will start by taking inputs from the user such as their name, the major they are in, and their desired amount of credits per semester. The program will then form several graphs with different options of class paths that they may take to graduate with that major. The user can then select the path that works best for them.

Name each interface or class and briefly describe its function or purpose.

The Student class will take all data given by the user on the prompt screen of the GUI and will be used in the scheduling algorithm to generate a four year plan.
ClassNode will be used to store all data related to each class this includes all prereqs, the number of credits, and the times offered. The Graph will hold all of the ClassNodes and connect them to their prereqs and to the semesters they are offered in.
Our UIClass will display the the fields to take in user data and then displaay the output from the algorithm.
Finally we will use either a Path or a Semester class to hold the data calculated from the main planning algorithm to be displayed as output for the user.

## Edit and Submit this file and any figures referenced by this document.

