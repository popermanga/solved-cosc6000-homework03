Download Link: https://assignmentchef.com/product/solved-cosc6000-homework03
<br>
<h1>Part1</h1>

Write a program that will read in a weight in kilograms and grams and will output the equivalent weight in pounds and ounces.

Use at least <strong>three</strong> <strong>functions</strong>: one for input, one or more for calculating, and one for output.

State ‘precondition’ and ‘postcondition’ for each function in comment lines.

Include a loop that lets the user repeat this computation for new input values until the user says he or she wants to end the program.

There are 2.2046 pounds in a kilogram, 1,000 grams in a kilogram, and 16 ounces in a pound.

Hint: How to repeat?

Since the program asks user to input Y or N, “askYesOrNo” function will be

Note that this function doesn’t take any value as formal parameters so ‘void’ type is used. But in case user inputing ‘y’ instead of ‘Y’,

Some user may type in “Yes” so to prepare for it, bool askYesOrNo(void ){

https://tulane.instructure.com/courses/2165899/assignments/13461778           1/2 4/23/2018           Homework 03

With above, ‘Y’, ‘y’, “Yes” and “yes” work. Also “Yah”, “year”, “yahoo” work.

<strong>char ans[256];</strong> is a ‘char’ array, namely a string (this is so called C­string). We will look into it later.

<h1>Part2</h1>

Download a file from <strong><u>here</u></strong><strong><u> (http://academic.uda</u></strong><strong>y<u>ton.edu/kissock/http/Weather/</u>g<u>sod95current/LANEWORL.txt) </u></strong>.

That is daily averaged temperature data at New Orleans from 1995~present.

There are four columns: month, day, year, and temperature in Fahrenheit (F). The temperature data is ­99 if no data was available on that day.

Write a C++ code to extract the minimum temperature and the day it happened from the file.

Develop a function that <strong>takes a file stream object connected to the file </strong>and <strong>returns the minimum temperature, its year, month, and day</strong>.

State ‘precondition’ and ‘postcondition’ for each function in comment lines.

The program should not assume the number of data in the file.

Break down into some subtasks and state what each subtask does in comment lines.