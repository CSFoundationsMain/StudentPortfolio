# Frequently used CLI (command line interface - your terminal) commands

## Git Commands frequently used:

### how to push your code from AWS Cloud9 to GitHub repo
  1. **cd** (change directory) **projectFolderName-yourGitHubUsername**
    * the git commands MUST be run from the project folder on the terminal (CLI)
  2. **git status**
  3. **git add -A**   (adds all files that haven't been updated into staging phase)
  4. run **git status** again to check if your files have been updated that contain your code.
  5. **git commit -m "your description message of the work completed to this point"**   (or "Submit for grading" if you are done with the project)
  6. run **git status** again
  7. **git push origin main**
    * type in your GitHub username
    * copy your GitHub personal access code in place of password requested (*note cursor will NOT move when access key is pasted*)
  8. Check your project GitHub repository to confirm your push work correctly
  9.   Congratulations!  You have pushed your work successfully!!!


### how to copy or clone a starter GitHub repo to your AWS Cloud9 IDE
  1. **git clone https://yourProjectGitHubRepo.com**
     * *ALWAYS run your git clone command from the Root Directory - **/environment $** *

