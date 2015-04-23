# FeedbackForm-Generating-System
I create a python3.4 script to automatically generate feedback forms for student.

##Installation:

just download it and use a terminal to open the folder.

## Usage:

Use data_template.xlsx to store the data of students/employees, then in shell, run:

./mark.py [-i | --input=]<data_template.xlsx> [-o | --output=]<output directory> [[-n |--number=]<index> | [-a| --all]] [-t |--type=]<form type>

"-i": parameter defines where the input file is.",
"-a": parameter, will print all forms according to the student_list.
"-n": parameter should be followed by a valid index number, print the corresponding form.",
"-o": parameter defines the location of generated forms.",
"-t": parameter defines the form types.",


