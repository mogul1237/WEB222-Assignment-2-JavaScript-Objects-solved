# WEB222-Assignment-2-JavaScript-Objects-solved

Download Here: [WEB222 Assignment 2: JavaScript Objects solved](https://jarviscodinghub.com/assignment/assignment-2-javascript-objects-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Objective
Practise JavaScript String, Array and customized objects.
Specifications
Complete the two parts of the assignment as specified below.
Part A Write a JavaScript program to perform the following tasks. No validation is required for user input – assume that the user will enter valid information. Open a Firefox Scratchpad. Create comment line(s) for each of the Steps in assignment2a.js using block comments, indicating the start point of each Steps. e.g. /***************************** * Step 1 *****************************/
To run all JavaScript code in Scratchpad, click on the Run button. To run a part of the code, highlight the part of code and click on the Run button . You’re requested to keep a Web Console open to monitor console logs and run-time errors when running JavaScript code. Variable values will be kept in memory after a piece of code is run. So, usually, you need to initialize variables to ensure the part of code can repeatedly give the same result.
Step 1:
a. Declare the following global variables without any value assigned: e1, e2, e3, e4, e5, e6, e7, str b. Run the code the in Firefox Scratchpad to test if you code has error or appropriate output. Fix the errors before going to the next step.
2
Step 2:
a. Create a function named capFirstLetter using the function declaration syntax. The function receives a single parameter of String type. Update / change the first letter of the string to upper case and other letters to lower case. The function returns the updated String. b. Write code to prompt the user to enter first name, and use your first name as default value. Accept/store the entered name in e1. c. Update / change the first letter in e1 to upper case and other letters to lower case by invoking the function. d. Repeat step 1.b (run the code and check for errors and/or outputs). e. Hint: use the property and methods of String object – length, substr(from, length), substring(from, to) , toUpperCase() and/or toLowerCase().
Step 3:
a. Create a function named getAge using the function expression syntax. This function receives one parameter of integer (number type), which is the year of a person’s birth day. The function returns the age which is calculated based on the year entered. b. Prompt the user to enter the year of the user’s birth day – accept the number in e2. For the default value, use the year when you were born. c. Calculate the age by calling the getAge() function and assign the number of age back to e2. d. Repeat step 1.b (run the code and check for errors and/or outputs). e. Hint: for getting the number of the current year, you must use the code: (new Date()).getFullYear()
Step 4:
a. Prompt the user to enter the college name the user is attending and assign the input to e3. For its default value, use seneca college. b. Change the first letter of each word of the string in variable e3 to upper case and other letters to lower case. c. Repeat step 1.b (run the code and check for errors and/or outputs). d. Hint: use the split() method of String and the capFirstLetter() function you created.
Step 5:
a. Prompt the user to enter 5 favorite sports (in lower case separated by comma) – accept the string in e4. Use hockey,football,basketball,tennis,golf as default value for the prompt. b. If the string in e4 contains “football”, replace it with the string “soccer” c. Split the sports in e4 into an array and store the array back in e4. d. Prompt the user to enter an extra favorite sport with the default value “formula 1” – accept it in e5. Then add the sport (e5) at the end of the course array (e4).
3
e. Repeat step 1.b (run the code and check for errors and/or outputs). f. Hint: use the split() and replace() method of String; use the push() method of Array.
Step 6:
a. For the courses stored in e4, do the following operations. • Update / change each sport string in the array to upper case. • Sort the courses in the array in alphabetical order. b. Repeat step 1.b (run the code and check for errors and/or outputs). c. Hint: use sort() method of Array object.
Step 7:
a. Create a function named getDateString(). This function receives one parameter of Date type and returns date string with the format of yyyy-mm-dd. e.g. 2017-09-20. Note: if the number of the month (mm) or date (dd) is less than 10, a ‘0’ is needed before the number. b. Create a date object with current date and time, and store it to e6. c. Get current date string with the format of yyyy-mm-dd by calling the getDateString() function and passing e6 as parameter. Store the date string in e7.
Step 8:
a. Concatenate all the variables e1, e2, e3, e4 and e7 with appropriate text in variable str. b. Use one statement console.log(str); to get the following output:
c. Save your file as assignment2a.js.
4
d. Hint: use ‘\n’ and ‘\t’ to create multiple lines and indents in web console.
Part B Download JavaScript file assignment2b.js from MySeneca/Blackboard under the Assignments section. The file contains some given code, including an array (named courses) of course objects and a prototype object (named student) for creating student objects. Do not change the given code. Write your code beneath the given code and complete the following tasks:
Task 1:
a. Remove the last course object form the given array courses and store the removed object to a variable. b. Output a message to web console to show the course which was removed from the array. Please see the screenshot of outputs on the browse console below. c. Create 4 course objects which should have the same properties as what the objects (in the course array) have. Store the 4 course objects in the variables ibc233, oop244, web222 and dbs201, and the object properties should have appropriate values. d. Add these course objects in the array courses. e. Use for loop to loop through the course array and output the information of the course objects in the array to web console. Please refer the screenshot below.
Task 2:
a. Create 4 student objects based on the given prototype student. Give appropriate property values for all student objects. b. Create an array named students and add all the student objects into the array. c. Use the forEach method to iterate the array students and output the information of the student objects to the web console. Please refer the screen below. d. Save your JavaScript code to file assignment2b.js.

5
Click the image to open it full-size in a new tab/window.
Assignment submission
▪ Add the following declaration at the top of your assignment2a.js and assignment2b.js files (failure to do this step will result in zero mark assigned to your assignment 2):
/******************************************************************************* * WEB222 – Assignment 2 * I declare that this assignment is my own work in accordance with Seneca * Academic Policy. No part of this assignment has been copied manually or * electronically from any other source (including web sites) or distributed to * other students. * * Name: _____________________ Student ID: ______________ Date: _______________ * ******************************************************************************/
▪ Compact your files assignment2a.js, assignment2b.js into a zip file named assignment2-.zip. ▪ Submit the zip file to the Blackboard (My.Seneca).
6
Important note
▪ NO LATE SUBMISSIONS for assignments. Late submissions will not be accepted and will receive a grade of zero (0). ▪ After the end (11:00PM) of the due date/time, the assignment submission link on the Blackboard will no longer be available. ▪ Allow enough time to upload. Do not wait for the last moment since there are transmission time/queuing delay/processing time etc. from your machine to the blackboard server.
