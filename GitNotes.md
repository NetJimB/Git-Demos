# H1 Git and GitHub for Beginners - Crash Course on YouTube

[freeCodeCamp.org on YouTube] https://www.youtube.com/watch?v=RGOj5yH7evk

[GitHub] https://github.com/gwenf/demo-repo
## Set Default Profile
    Open Visual Studio Code and press and hold Ctrl + ` to open the terminal.
    Open the command palette using Ctrl + Shift + P .
    Type - Select Default Profile.
    Select Git Bash from the options.
    Click on the + icon in the terminal window.
    The new terminal now will be a Git Bash terminal.

[YouTube Notes] C:\Users\User\OneDrive\GitRepo\GitAndGithubForBeginnersCourse\Git and GitHub for Beginners.md



## Example Flow
    git clone "Type Repositary URL"

    git status

    git add . **it means we are telling git to track all files and save
    OR
    git add "Filename.extention"

    git commit -m "[comments]"

    git push origin [repo]

    Note: git init 
            
    Note: Short cut to upload
        git push -u origin master
            -u will allow git push without adding the origin and master parameters
            This is the same command as --set-upstream

Note:
    git commit -am "using a "adds" a new file and m is still message"
        adds and commits at the same time but only for MODIFIED files

Add a line to test

# SSH example
ssh-keygen -t rsa 4096 -C "netjimb@yahoo.com"
    (/Users/[username]/.ssh/id_rsa): [filename]

        [filename] Private
        [filename.pub]  Public

# Branching

    git branch
        enter q to exit
    git checkout -b [BranchName]
        -b to create a new branch
        Use the BranchName as the description
        NOTE: Auto Tab complete will pick up on any part of the name

    git diff
        enter q to exit

