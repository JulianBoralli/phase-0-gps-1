# phase-0-gps-1
GPS 1.1 Assignment (Git)
  559  git clone https://github.com/JulianBoralli/phase-0-gps-1.git   phase-0-gps-1

It establishes the connecting between the remote repo (GitHub) with local (computer)

  560  cd phase-0-gps-1/ && ls
cd changes directory and ls lists whatever is inside the current directory

  561  git pull

fetches and merges updates from the remote repo to local repo.

  562  touch awesome_page.md

creates a new file

  563  ls

list files in the directory

  564  git add -A

Tracks and Stages a file to be committed.

  565  git status

Show current state of the repository. For ex: show untracked / uncommitted files

  566  git commit -m "Add awesome_page.md file"

Updates the changes staged to the current version, creating a safe point. -m add a descriptive message.

  567  git help push
Getting help description for push command

  568  git push -u origin master
Pushing from local to remote the update version.

  569  git co -b add-command-log
Create new branch (-b option) and switch to new branch

  570  git branch

  list all the branch available
  571  history
  lists all previouly typed commands on CLI.
  572  ls
  
  573  history | tail -n 15 >> README.md 
