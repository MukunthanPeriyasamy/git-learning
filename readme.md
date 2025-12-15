## Git Learning

1. git init
    - This command is used to initalize an empty git repo in our local machine
    - The default name for the branch will be `master` but is good practice to change the name of the branch to `main` for an industry standards

2. git branch -M branch-name

    - This command is used to change the branch name

3. git log
    - This command is used to get all the log history

4. git checkout -b branch-name
    - This command is used to create a new branch and switch to the new branch

5. git remote add origin `repo-url`
    - This command is to used to initialize the remote repo in your local machine.

6. git add 
    -  command is used to add the file to the remote repo
    - Either we can use `.` or specific file name after the `add` command. e.g : `git add .` or git add file-name.

7. git commit -m "commit-message"
    - This command is used to add a commit message.
    - This will help others to understand what is the latest commit or update via that commit message.

8. git push -u origin branch-name
    - This command is used to push the files which are `add` and `commit` to the remote repo.