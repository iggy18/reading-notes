# git intro 

## Version control
- version control allows you to visit various versions of a file. if you mess up or need to see what changes were made you can go back to a previous version of the file.
- **local version control** is a database on *your* computer.
- **centralized version control** is a database stored on a server that is able to be accessed, changed, and saved, by many people.
- **distributed version control** allows clients to create a copy of the files stored on the server to their own computer. they can create, edit, and save on their computer and then push changes to othe server.

# So what is Git?

- **git is a DVCS** each time you commit a file git creats a snapshot of the file and store a reference to it.
- **git minimizes the possibility of irreversible damage to a file**
- Files in Git can reside in three main states: **committed, modified and staged**.
- You can create a copy of a Git repository from a server by using the **clone command** with a repository’s URL. ***git clone website url***
- Tracked files can be modified, unmodified, or staged.
- Untracked files were not in the last snapshot and do not currently reside in the staging area.
- the **git status** command will tel you if you have changes to commit, or if you dont.
- **Git add filename** (for one file) or **git add .** (for all files in repository) wil track and stage changes to be commited.
- **git commit** lets you add a comment to the file so you know what was changed.
- **git push origin master** this command pushes the changes youve made to the server.