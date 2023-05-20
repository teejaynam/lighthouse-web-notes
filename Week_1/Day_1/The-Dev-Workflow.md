# The Dev Workflow

## Notes

* VS Code Cheat Sheet / Shortcuts
  * [Windows shortcuts](/Week_1/Day_1/keyboard-shortcuts-windows.pdf)
  
* Git commands - Best Practices
  * [Git Cheatsheet](/Week_1/Day_1/git-cheat-sheet.pdf)
    * ``` git -v ``` - check installed version of git
    * ``` git init ``` - Initialize empty Git repo in directory
    * ``` git status ``` - Check current working branch and file changes 
    * ``` git add <file> ``` - Add the file and changes to next commit. Can do "." to add all changes
    * ``` git commit -m "msg" ``` - Commit the changes to the current working repository
    * To connect the remote and local repository : 
      * Create the repository on github then do ``` git remote add origin <url of ssh> ```
    * ``` git log ``` - View change log
    * ``` git clone <ssh url> ``` - Makes copy of a whole remote repository
    * ``` git pull <ssh url> ``` - Pulls only the changes of a remote repository
    * forking is when you want to make changes to a copy of code/repo when you do not have write access to it by copying it as a local repository
    * Branches
      * Can check for commits
  
* Incremental Development
  * Approach problem solving, step by step
    1. State the hypothesis
    2. Verify the hypothesis
    3. Make changes