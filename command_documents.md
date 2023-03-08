# Command List

*Basics*

- init: initialize a Git repository (March 8, 2023)

-**--version** checks the current version of Git on your local machine (March 8, 2023)

- status: shows details about the repo, such as commit history, tracked files,
  and the current commit, if any is present (March 8, 2023)

- add: add a new file to be tracked by the repository (March 8, 2023)
    - usually you put a list of file names, but can also put **.** to add 
      everything in the same directory as the .git file

- commit: save the changes to the files in your repository (March 8, 2023)
    - the option **-m** adds a message to your commit that ideally details what changes you made

- remote: manage the remote repositories of your account (usually on GitHub or GitLab) (March 8, 2023)

- push: finalize a commit in the repository (March 8, 2023)
    - the option **-u** tells git to push to the upstream branch
      (usually the remote repository on Github) 

- pull: pull changed files from a repository to your  
  local machine (March 8, 2023)

- rm: remove a file being tracked by the repo (March 8, 2023)
    - the option **--cached** ensures the file is not deleted from your filesystem 

- clone: clone a repository from GitHub or GitLab onto your local machine (March 8, 2023)

*Branch Management*

- checkout: switches to a branch whose name is provided (March 8, 2023)
    - the option **-b** means we create a new branch then switch to it

- branch: 

- merge: 

*DevOps*

*Continuous Integration*