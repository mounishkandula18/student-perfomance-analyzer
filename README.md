# student-perfomance-analyzer
student perfomance analyzer is implemented in python

goal:
   the goal is create  a program that checks student marks and classifies them into grades,while also counting valid and failed students.
   Inputs :
    the program takes:
    -Number of students(m)
    -Marks of each stident
    user input username("Mounish")

    Logic
    - If the username length divided by 2 and  if it is even the mark will be decremented by 1 or else,incremented by 1
    Since "Mounish" is 7 characters the marks will decremented by 1.

    Validation rules : 
    - 91-100 -> Excellent
    - 76-89 -> Very good
    - 61-74 -> Good
    - 41-59 -> Average
    - 0-39  -> Fail
    -Marks outside 0-100 -> Invalid

    Counters 
    -valid -> counts all students whose marks fall into valid ranges (0-100).
    -fail ->counts students who fall into the Fail category.

    Output
        -Prints each students adjusted mark with its grade.
        - Prints total valid students.
        -Prints total failed students.
    

 

