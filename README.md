# Git-Notes

1.2 - Initializing the Repo


- mkdir -p repos/directory_name (-p creates a parent directory) (this makes a repo directory)

-cd  repos/directory_name  (directs you to the repo directory)

- git init

- touch index

- git diff (shows the difference between the last commit and unstaged changes in the current project)

- git commit -am "Add baz" (Add baz)

- git log (confirms the change went through)



2.2 Remote Repo



- git remote add origin (link to new repository you made prior to this command) 

- git push -u origin master (This flag sets GitHub as the upstream repo which means we'll be able to download any changes)

- After the first 'git push' is executed, you should always reload the current page.



3.3 Branching and Merging


- git checkout -b NewBranchName (creates a new branch) 

-   To Add and Commit in the same line: git add -A && git commit -m"Message")

- git checkout master (to go back into master page)

- git merge NewBranchName (merging the branch with the master) 


3.4 Recovering from Errors

- git branch -d NewBranchName (deletes the topic branch) (confirm by running 'git branch' that only master branch is left






