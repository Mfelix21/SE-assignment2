# SE-assignment2
To start off, I made a  simple Python program that takes user input and displays a personalized greeting.

Project Description: This project is a basic Python script that prompts the user to enter their name and then prints a personalized greeting. It was created as part of a Software Engineering assignment to practice working with Git, branches, and resolving merge conflicts.

To run this project on you would have to follow these steps:

1.Clone the repository
bash
git clone https://github.com/YourUsername/SE-assignment2.git
cd SE-assignment2

2.Run the Python script

bash
python hello.py

3. Usage Example
When the script runs, it will prompt the user for input:

The script takes the user’s name as input and prints a personalized greeting.  
It also displays messages from different branches to demonstrate Git merge handling.


During this project, I encountered a few challenges while working with GitHub and resolved them as follows:

 Issue: "Git branch not found" when trying to switch branches
 Resolution: I used git branch -a to list all available branches and ensured I had fetched all branches using git fetch --all.

 Issue: Merge conflict in hello.py when merging feature-2
Resolution: I manually edited hello.py to keep the correct version of the greeting messages, removed conflict markers (<<<<<<<, =======, >>>>>>>), and then committed the resolved file.


