# Mini-cnc-printer
## Table of contents
* [introduction](#introduction)
* [Technologies](#technologies)
* [Setup](#setup)

## introduction 
![image](https://user-images.githubusercontent.com/40560478/171049168-18df6518-2532-4925-810c-2175f744b89a.png)
CNC means Computer Numerical Control. A Computer Numerical Control
(CNC) is the automation of machine tools by which we can draw different type of letter ,picture provided by computer using software into it,s controller .
This means computer converts the design into numbers which the computer uses to control cutting or shaping of the material.
The code which use to programm cnc machine is called G_code
G-code give CNC machine the coordinates


## Technologies
Project is created with:
* c language
* arduino  
* Inkscape:
Inkscape is used to design the plotted diagram or text. 
In this project by using this software
G-code file of a selected image or text is created G-code is a commonly used numerical control
programming language which includes X, Y, Z coordinates.
![image](https://user-images.githubusercontent.com/40560478/171049444-d176b4c9-7562-4c5b-bfb1-467a2370c67c.png)
* Processing
Processing is open source programming language software which is used for electronic drawings. GTCRL processing program is used to send G-code file from user interface to CNC plotter![image](https://user-images.githubusercontent.com/40560478/171049473-a1bef4af-b365-4089-b78d-2be939875419.png)

 

## Setup
### hardware require:
*  stepper motor *2
*  Arduino uno R3
*  L293 motor shield
*  MG 90S Micro Servo  
*  NUT AND BOLTS AS REQUIRED
*  SOME WIRES FOR MOTOR CONNECTION



## who project is work ?
* Controlled by G-CODE, Which is generating by computer software .
* These are numbers values and co-ordinates . 
* Then the G-CODE uploaded on Microcontroller of the CNC machine . 
* CNC shield will be converting the command of G codes in digital pulse by Stepper motor.  
* In X direction Stepper motor will be move left and Right ,Y direction stepper motor will be move in front and back direction, Z direction Stepper motor will be move in Up and down. 


## circuit diagram 
![image](https://user-images.githubusercontent.com/40560478/171049517-147af061-0139-4b4c-8ad1-cc8b1d6cff56.png)

## code
* https://github.com/AltwilMohammed/Mini-cnc-printer/blob/main/cnc%20code.ino
