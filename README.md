# Robot-Arm-Control-Interface
Create a robotic arm control interface page and link it with the database.

I've created a web page to control the robot arm by using Notepad++. What I do is I used HTML to create the web page structure and CSS for page layout and Javascript to show the value when moving the range slider, then I saved the page in .php extention.

Then I created a database using xampp and phpmyadmin called Robot Arm Control, then I created a table that contains 8 columns, 6 of them are expressing motors (base, shoulder, elbow, wrist1. wrist2, gripper) and one of them expresses the id of each piece, and the other column expresses the status of the motor whether it is on or off.

I have also linked the database to the user interface where if the user clicks the "save" button, the values for range sliders will be sent to the table in the database, and if the user clicks the "run" button, the robot status will convert from "off" to "on".
I have also created a page where the degrees of the arm pieces are shown, this data has been fetched from the database.
