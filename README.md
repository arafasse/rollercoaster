To-Do:
1. If you are reading this, you have successfully accessed the Roller Coaster Admissions assignment in GitHub). You will see two files in your newly-created repository: this README file and a rollercoaster.py file, which is the file you will modify.

2. Click the green "Code" button to the top right and click "Open with GitHub Desktop."

3. In GitHub Desktop, you should now see the repository for this assignment. Click "Show in Finder," then right-click the file you wish to modify (rollercoaster.py) and open it with IDLE. Now you are ready to start writing code!

4. In your IDLE environment, write a Python program that prompts a user to enter their name, age, and height (in inches) from the console, then outputs whether the user is permitted to ride on a roller coaster. The age limit for the roller coaster is 13 and the height requirement is 60 inches; riders must satisfy both requirements. Be sure to comment your code and save your work!!!

5. When you are done, go back to GitHub Desktop. It will now show you the edits you have made to rollercoaster.py. In the text box at the bottom left, type an informative message about the changes you have made and click "commit to main."

6. Click "push origin." If you return to your online GitHub screen and refresh the page, you should now see your new commit, as well as the code you have just written. I can see it too, and I can give you feedback! :) 


Extra Challenge: See if you can modify your conditionals such that, if the user is BOTH too young and too short, they are informed that they have failed both criteria. For prospective riders who are too young, you may also wish to inform them of how long they have to wait before they can ride the roller coaster.


Programming hints:
1. Use the input function to prompt the user for various information.
2. Store the user input in three separate variables. 
3. When you first run your program - even if you've done everything correctly - Python will complain! When you enter ages and heights, it interprets those as Strings (text variables), and then it gets upset when you attempt to compare text to numbers using the < > functions. In order to overcome this difficulty, you will need to cast your String variables as integers, essentially tricking the computer into interpreting them as numbers. To do this, use the int function, which takes the String as the argument and returns the corresponding integer. For example:
          number = int("5")
5. Use if statements to determine the appropriate output.
6. You may customize your messages to the user as you see fit! 
