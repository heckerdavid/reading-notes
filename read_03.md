# Version Control

Version Control Systems (VCS) allow for tracking and storing of a project at different stages in its life, this allows you to empliment new features without 
worrying about destoring your project. Cause a massive bug you cant fix? Simply revert to a previous version. Hate the new feature you spend weeks on? revert it away.

## VCS can be

- Local
- Centralized (CVCS)
- Distributed (DVCS)

## Git

Git is a extremely popular DVCS.

- allows for multiple developers to work simultaniously on the same project
- keeps a retrieveable, historical record of changes 

### Commits

creates a snapshot of the current state

the current version(most recent commit) is referred to as the head

comments allow for information pertaining to the commit to be added, making historical reference simple

### Repositories

A collection of files with git tracking. Normally one per project, in some cases one repo is used for front end and one  for the backend.

### Git help

for more info on a command you can use

- git [commmand] --help
- man git [command]
- git help [command]

### ACP commands

- Add
  - git add [file]
    - adds [file] to staged
- Commit
  - git commit -m "comment" 
    - can be used for multiple files, comment will apply to all
  - git commit -a
    - commits all file changes  

- Push
  - git push origin main
    - pushes commited files to main repo

these commands can change the git state. Git files can exist in three different states.

1. Committed
2. Modified
3. Staged

### More commands

- git status
  - returns current status of tracked files
- git clone [link] [directory*optional]
  - copies files from the linked repo to local directory
