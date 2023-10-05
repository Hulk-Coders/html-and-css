# PRACTICING GIT ASSIGMENT 
Follow the below steps to complete the assignment: 

## Part I: Clone you repo and create a new branch
1. Clone this repo to your local machine
    `git clone <repo-url>`
2. Create a new branch with your name using the command: 
    `git checkout -b <your-name>`

## Part II: Remove all the files from the repo except this README.md and GIT-README.md
3. Delete all files in the repo except this README.md and GIT-README.md
    `git rm -r *`
4. Review your changes by using the command: 
    `git status`
5. Add all the changes to the staging area using the command: 
    `git add .`
You can also add selected files to the staging area using the command: 
    `git add <file-name>`
6. Commit your changes using the command: 
    `git commit -m "your commit message"`
7. Push your changes to the remote repo using the command:
    `git push origin <your-name>`

## Part II: Add your previous assignment files to this repo
8. Transfer the files from your previous assignment (HTML & CSS) to this repo
9. Follow step 4 to 7 to review your changes, add them to the staging area and commit them
6. Push your changes to the remote repo:
    `git push origin`

## Part III: Create a pull request
7. Go to the repo on GitHub and create a pull request
8. Add your instructor as a reviewer to the pull request
9. Submit the pull request

## Part IV: Pull other people changes
10. Check all remote branches using the command: 
    `git branch -r`
11. Find your classmate branch and pull the changes using the command: 
    `git pull origin <your-classmate-branch-name>`
12. Review your classmate branch and note on it
13. (Optional) Create a copy of your classmate branch using the command: 
    `git checkout -b <your-classmate-branch-name>-copy`
14. (Optional) Push your classmate branch copy to the remote repo using the on step 7: