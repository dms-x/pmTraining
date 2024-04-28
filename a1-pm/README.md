### A1 - Git
Hello Haize,
In here, you will learn how to use git/github.  
The point of this is to learn how to get code from one machine to another machine.  

If you are reading this, you will  be in /pmTraining/a1pm in github. Good job! You will be required to come to this website for future assignemnts too.   


Now, let's move the whole thing into your machine.   

First, a directory(folder) using Visual Studio Code in a location where you want all these codes to go within your machine. Then, open terminal in VSCode. In the terminal console, you will see your cursor blinking next to your computer's name and the folder's name.  

In the terminal, enter **"git init"** <= this initiates the folder to enable git (press enter to submit your command to the machine)  

Then, enter **"git clone https://github.com/dms-x/pmTraining.git"** to clone the repository into your local machine.  
You will see something like "Cloning into 'folder name'... done. done. done." showing the download process. After all finished, you will see the files added to your local folder in the left menubar of the VSCode.  

When you see it, go to the file in the terminal by typing **"cd pmTraining"**. (Change Directory). Then, you will see that the folder name in the terminal is now pmTraining. Wow! great job! That's how you clone and navigate through the code from the internet.  

Now, change this README.md file by answer this question below. What is your name?  
-> 

After typing that, let's now save the changes for everyone.  
In the terminal, type **"git add a1-pm/"** -> this adds only the a1pm folder to a state where it is ready to be changed.  
Then, type: **git commit -m "name change(or anything to describe the change you made to the code)"**  
That label describes what changes you have made.   

Last step. Now, type **"git push"**. This pushes your code to the git world. Great job! Now I can see the changes you made!  
Just like this, you will be submitting your codes to the repository.  

One of the most important thing is, when there's a change in the repository before you make any changes, do **"git pull"** to pull the updated code base from the github. Great Job! 

Last thing, when you push one of these projects, always push one folder at a time by adding one folder at a time during "git add " stage.


