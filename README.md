![Alt text](https://github.com/matthewsides/Project01-TraceBall/blob/master/traceballprojectlogo.png?raw=true "Optional Title")

 | Version 1.01    |
 |-----------------|
 | 28 November 2017|
     

# Revision List

| Version     | Author          | Date                 | Comments                       |
|-------------|-----------------|----------------------|--------------------------------|
| 1.00        |  Matthew Sides  |              2017    | Initial Version                |
| 1.01        |  Matthew Sides  |              2017    |                                | 
|             |                 |                      |                                | 
|             |                 |                      |                                |
|             |                 |                      |                                |
|                                                                                       |                         


# Table Of Contents

[1] Introduction 

[2] Scope

[3] Type Conventions
     
[4]  Research

[5] References 

[6] Target System 

[7] Specification 

[8]  High Level Non-Functional Requirements

[9] High Level Functional Requirements

[10] User Stories

[11] Project Backlog

[12] Flow Chart

[13] Cordinates System

[14] Process of implementation Algorithm

[15] Description of IDE used and features it provided

[16] Debugging process and debugging facilities in your chosen IDE

[17] Implementation of an algorithm in a suitable language

[18] Written algorithm and Code variant relationship


### [1] Introduction

This document specifies a design for the conceptual features and mechanics (gameplay) of a game with the provisional title “TraceBall” . It is based on elements found within a given brief specifying for a game based around a square following a mouse on screen.  

### [2] Scope

This documentation is intended to be read by programmers, artists and producers involved in the design implementation and testing of the HTML internet game "TraceBall".

### [3] Type Conventions

Things that have been discussed in a meeting are presented in this document with no asterisks.

Things that have not been offically agreed on but which are suggested by the author are presented with asterisks, like this (*),being marked as omitted until it has been agreed upon that it may be of use or implemented.

### [4] Research

This segment marks 

### [5] References

N/A


### [6] Target System
TraceBall will be produced for the following platforms: Windows all versions running on HTML 5 (Internet Browser), Chrome and Explorer, written in Java Script though the ID Notepad. This Documentation is primary concerned with the internet browsers chrome and explorer though maybe expanded and branch out to other browsers at a later date.

### [7] Specification 

A non-playing character NPC (that is a character controlled by the computer) targets the users mouse position as the player moves across the screen, the game is over once the NPC touches the players mouse position 3 times. 

### [8] High Level Function Requirements

Create Canvas

Create 2 dimensional character

Create NPC

User mouse movement moves character

Have NPC move to player position

Character stays within Canvas

Collision detection and display

Start and stop game

### [9] High Level Non-Functional Requirements

Canvas Colour

Character and NPC shape

Player and NPC colour

Canvas size

### [10] User Stories

I would like to be able to view the game within a browser. -  View in Browser  
I would like to be able to see and have the NPC model (square) follow me across a screen. - NPC follow me  
I would like to be able to end the game. - Initiate and End the Game 
I would like to be able to move across a screen. - Be able to move    
I would like to be able to get feedback on the amount of lives I have concurrent to whats happening on screen. - Amount of Lives (Feedback) 


### [11] Project Back Log

| User Story  | Description                  | Points | Due Date | Mo | Tu | We | Th | Fr |
|-------------|------------------------------|--------|----------|----|----|----|----|----|
| 1           | View in Browser              | 2      |22 Sep    |    |    |    |    |    |
| 2           | NPC follow me                | 1      |22 Sep    |    |    |    |    |    |
| 3           | Initiate and End the Game    | 1      |22 Sep    |    |    |    |    |    |
| 4           | Be able to move              | 3      |22 Sep    |    |    |    |    |    |
| 5           | Amount of Lives (Feedback)   | 2      |22 Sep    |    |    |    |    |    |
| Total Points| 9                 |

### [12] Algorithm - (Flowchart)

![Alt text](https://github.com/matthewsides/Project01-TraceBall/blob/master/FlowChartP1.jpg?raw=true "Optional Title")


### [13] Cordinates System

The cordinate system consisted of or relates to the formation of multiple shapes on screen, through defining pre-set X and Y variables that were then used inconjunction with a similiar methodlogy to Pythagorean theorem to measure the distance with a fill function thus filling the internal area making the shape appear visible as merely measuring the distance and forming a shape will not actually present an asthetical output. 

Thereafter the shapes were then used inset to the cordinates of the mouse on screen 


essentially relates to the formation of a shape which held pre-set or determined x and y cords that, through using a similiar methodology to the Pythagorean theorem rom (formulae) were   connected together and were filled 
You used coordinates to create a shape (or image) and made this shape (or image) follow the mouse. The mouse is the input and the shape (or image) is the output element. And you had to use coordinates to implement them. All you need to do is describe this process and provide a link to your project 1.
### [14] Process of implementation Algorithm

The HTML page was first developed, whilst a canvas was thereafter defined, then another square was defined within the canvas. Furthermore the mouse was is then required to be tracked on the screen to the canvas, whilst the cords of the square are also needed to be retrieved. The cords then need to be compared minus or adding onto the cords of the square if certain conditions are met, including a timer to ensure that the square movement is smooth and doesnt look like its teleporting around or about the page or screen. Inaddition the square and mouse then need to have a defined area or set cords or x and y with a conditional statement comparing them seeing whether the cords are eqaul or enroach on one another.Moreover adding at the end of the statement to minus lives, creating or defining a lives variable where if there is collision a life or numerical value is subtracted or taken away from the variable. While the code is held or indented within a loop where if certain conditions are met i.e: the user runs out of lives or the variable lives hits a certain defined numerical value the game ends.

### [15] Description of IDE used and features it provided

The IDE ( Integrated Development Environment) used was notepad, though notepad is a questionable IDE as it has no redefining features and doesnt provide any comprehensive facilities except an area to write code and save the file in relation to the type of code written.

![Alt text](https://github.com/matthewsides/Project01-TraceBall/blob/master/IDENotepad.png?raw=true "Optional Title")

### [16] Debugging process and debugging facilities in your chosen IDE

The IDE or notepad does not have any debugging facilities,but the debugging proccess has to be done manually either scrolling through code to locate and fix the problem or using preset code that is indented into the program and debugs the code, finding the problem for it to be solved (fixed).

### [17] Implementation of an algorithm in a suitable language

The algorithm in this precedent was displayed through a flow chart and implemented into a suitable language (High-Level Language), being Javascript in this instance, with the code structure being based around the flowchart. The code once translated to High Level Language (JavaScipt) was then compiled using Notepad which is easier than some editors as Notepad does not add formatting codes which made it easier to compile. Once the code was translated from High level to Machine code and compiled, etc. the file after being saved as an HTML file was able to display output when the file was clicked and a window opened. 

### [18] Written algorithm and Code variant relationship

The relationship between the written algorithm and the code variant is that the algorithm, in this instance being represented in a flow chart diagram, shows the workflow or process of how the application should function or work, whilst the code variant is essentially the algorithm translated or converted into High-Level-Language (in this instance javascript) as to the contrasting differences between how they function since the algorithm is the basis on which the code variant is structured around and the structure or workflow was followed the compiled machine code and outcome met the structure of the algorithm with the exception of an end state displayed in the flowchart but not implemented in the code as after a collision unlike as is stated in the flow chart, rather than having an end state the postion of the NPC is merely reset. 

Therefore due to the mirrored algorithm with only a slight difference the Code variant is acceptable, whilst the Written code is applicable to be used as a representation for the functionality or flow of the program and the relationship is solid. 


