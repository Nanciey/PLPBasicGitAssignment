# PLPBasicAssignment
Steps taken in order to make sure my code was pushed to github:
Step 1:Open Github and make a new repository and check the box for initializing a read.me
Step 2:Open git command line and make the PLPBasicGitAssignment folder. (mkdir PLPBasicGitAssignment)
Step 3:Change directory to PLPBasicGitAssignment. (cd PLPBasicGitAssignment/)
Step 4:Initialize git repository(git init)
Step 5: Add remote origin(>git remote add origin <repository url>)
Step 6: Open visual studio through git cmd by writing ->code .
Step 7: Add a new file to the PLPBasicGitAssignment folder and name the file as hello.txt
Step 8: Write a message in the text file
Step 9: Open a new terminal and add the file to github.(git add hello.txt)
Step 10: Commit changes to github.(git commit -m "Add hello.txt with a greeting")
Step 11: Push code to github (git push -u origin main)
Then I encountered an error with the git branch, I resolved it by changing the branch from master to main(git checkout -b main)
Attempted to push to the main branch again, resulting in another error about unrelated histories which was resolved using ->git pull origin main --allow-unrelated-histories
Then pushed my code successfully to the main branch on Github
