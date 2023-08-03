# Designing and programming robotic arm control interface using HTML/CSS, JavaScript, PHP, and SQL

I've developed a web page using Notepad++ to control a robotic arm. The page structure was created using HTML, CSS was used for page layout, and Javascript was implemented to display the value when moving the range slider. The page was saved as .php extension.

To store data, I set up a database using XAMPP and PHPMyAdmin called "Robot Arm Control". Within this database, I created a table with 8 columns, 6 of these columns represent the motors (base, shoulder, elbow, wrist1. wrist2, gripper), one column represents the ID of each motor piece, and the remaining column indicates whether the motor is turned on or off.

I successfully linked the database to the user interface. When the user clicks the "save" button, the values of the range sliders are sent to the table in the database. Similarly, when the user clicks the "run" button, the status of the robot changes from "off" to "on". Additionally, I created a page that displays the degrees of each arm piece, and this data fetched from the database.
