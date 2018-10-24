# X-Team 38 Project Proposal

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
We do not have enough practice problems that are unique and different from eachother for data structures on the CS400 exams. A program that could solve this problem would be a software that holds a large number of different questions and continues to give them randomly based on if your answers to the previous questions are correct or not. 

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)



2. Output: Describe the output your program will produce.  Include and example format of the output produced.



3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.



4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.



5. Types List: Break your solution idea down into units that you think can be implemented with a single class.



Name each interface or class and briefly describe its function or purpose.

Main Java Class: 
Will be used to interpret input of how the user is answering, send the data into our data structure class. Then the main class will interpret data from the data structure and use the question generator to present a new question to the user again. Eventually the main class will present the end results as well.

Data structure class
This is where we will store the question/answers, to eventually be interpreted by the main class. 

Question Generator class
This is where we will give the type of question we want to be generated and return it to the main class to be presented to the user.

Custom data structure:
The custom data structure will be a hash table that stores the question nodes. The hashtable will use an array of linked lists. The question nodes themselves will be in the linked lists. There will be fields to keep track of total number correct, total number correct and number correct per category, 

Custom Data Type  ( question node)

A question data type will contain multiple fields, such as the question itself, the answer to the question and the categories it belongs to. The data type will also have two additional status fields where information about whether the question was answered correctly earlier and whether the question has already been asked will be stored.




## Edit and Submit this file and any figures referenced by this document.

