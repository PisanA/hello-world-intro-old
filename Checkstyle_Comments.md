# Checkstyle

![image](https://user-images.githubusercontent.com/54456351/119812559-1ec06400-be9d-11eb-907d-e1b71a97a447.png) <br>
![image](https://user-images.githubusercontent.com/54456351/119814435-3f89b900-be9f-11eb-8578-2272566be21c.png) <br>

Checkstyle is a tool for checking Java source code for adherence to the Google Java Style Guide.<br>
Click "checkstyle" to view the report. The report should look like this:
![image](https://user-images.githubusercontent.com/54456351/120709943-5ec1b100-c472-11eb-93a1-1aafa7de830a.png) <br>
<br /> <br /> <br />
You can access each code line violating the coding standard through "Findings(37)"
![image](https://user-images.githubusercontent.com/54456351/120710983-b01e7000-c473-11eb-873d-e57b75aeab5c.png) <br>

The following is some comments you might find in the report:
## 'method def modifier' has incorrect indentation level 4, expected level should be 2.
Google style uses an indentation of 2 spaces, but most IDEs use 4 spaced indentation. Therefore, if you want to use 4 spaced indentation, you can ignore this comment. 
<br><br>
## Line is longer than 100 characters (found 109).
A normal computer screen cannot show more than 100 characters horizontally. The long line should be broken into shorter lines to ensure readability. 
<br><br>
## '{' at column 5 should be on the previous line.
'{' should not be in a new line. For example,  <br>
if (condition) {  <br>
&emsp;    statement; <br>
} 
<br><br>
## 'if' construct must use '{}'s.
Even when you only have 1 statement in your constructor, you should uses '{}' 
<br><br>
## Only one statement per line allowed.
Code should only have 1 statement per line for readability.
<br><br>
## WhitespaceAround: '=' is not preceded with whitespace **and** WhitespaceAround: '=' is not followed by whitespace. Empty blocks may only be represented as {} when not part of a multi-block statement (4.1.3).
There should be a space before and after '+', '-', '*', '/', '=', '<', '>', ... ';' should be followed by a space if there is anything after it
