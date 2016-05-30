# FeedbackForm-Generating-System
I create a python3.4 script to automatically generate feedback forms for students/employees.

##Installation:

just download it and use a terminal to open the folder.

## Usage:

Use data_template.xlsx to store the data of students/employees, then in shell, run:

./mark.py [-i | --input=] data_template.xlsx [-o | --output=] output directory [[-n |--number=] index number | [-a| --all]]
[-t |--type=] form type

"-i": parameter defines where the input file is.

"-a": parameter, will print all forms according to the student_list.

"-n": parameter should be followed by a valid index number, print the corresponding form.

"-o": parameter defines the location of generated forms.

"-t": parameter defines the form types.

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.


