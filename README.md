# github-workshop
Dated: July 07, 2018

Create an account at https://github.com/

--------------------------
First Assignment - Basics
--------------------------

1. Clone the repository at https://github.com/devsjee/github-workshop.
2. Inside the 'Assignment-1/participants' folder, create a new file in your name, for ex : Rahul.txt .
3. Add the following details about yourself in the file: 

         name: 
         email:
         github user name:
         Was the morning session easy to follow ? :
   
 4. Stage and Commit the changes in local repository.
 5. Push the changes back to the online github repository.
 
 After around 15 mins,
 1. pull the changes in github repository to your local copy.
 2. Do you see the changes?  If yes, this assignment is complete.
 3. How many participants have added their files? 44?
 
 
------------------------------------------
Second Assignment - Branching and Merging
------------------------------------------

1. Login to your github account. Fork the repository at https://github.com/devsjee/github-workshop to your account. Clone your copy of github-workshop from your github account.
2. See what branch you are currently on: git branch (the * near master means you are on master branch).
3. Make a new branch: git checkout -b add-your-name (the -b means "make a new branch").
4. Now see what branch you're on: git branch (you'll see 2 branches, with the * beside add-your-name).
5. Edit the participants.java file inside 'Assignment-2' folder and include your details.
6. Test your change. If this were a big colloborated project, you would be doing this multiple times until your code works perfectly.
7. When you're ready to commit, "Stage" your files for commit.
8. Commit your change (to the add-my-name branch): git commit -m "Added my details to participants.java file".
9. Switch back to master branch: git checkout master (note: no -b).
10. Open up participants.java file again. Are your changes reflected?
         (It won't be because those changes are in add-your-name branch).
11. Merge add-your-name into master: git merge add-your-name.
12. Open up participants.java again. Now you should see your edits. Resolve any conflicts that arise.
13. Push your changes to GitHub: git push origin master.
14. Go to github.com and see your changes.
15. Keep your repository tidy! Delete the branch add-your-name now as that it's done: git branch -d add-your-name.

Did you face any conflicts while merging branch with master? Why?

-------------------------------
Third Assignment - Explore Git
------------------------------

1. What is your favourite Git command? You can either pick one from what was taught in workshop or explore to find new commands. 
   Sometimes, even a known command has many useful options that were not discussed. You can even pick one such option.
2. Pull to get the latest repository from github.
3. Edit the 'favCommands.txt' inside the 'Assignment-3' folder to include your favourite command along with an example and description of its use.
4. Stage and commit with an appropriate message.
5. Resolve any merge conflicts that arise.


--------------
References:
--------------
1. Pro Git book written by Scott Chacon and Ben Straub, availabel at https://git-scm.com/book/en/v2
2. Quick reference on github: http://rogerdudler.github.io/git-guide/
3. Assignment-2 reference: https://github.com/adamaflynn/MergingAssignment
                

