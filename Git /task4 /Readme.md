1 intro to git


Git is a distributed version control system (DVCS) that is widely used for tracking changes in source code during software development. 
It was created by Linus Torvalds in 2005 to manage the development of the Linux kernel, and has since become one of the most popular version control systems in the world.
Here's an introduction to Git


2 CVCS vs DVCS

Version Control System (VCS):

Git is a type of version control system that allows multiple developers to collaborate on a project by tracking changes to files over time.
It maintains a history of changes made to files, along with information such as who made the change, when it was made, and why.
Distributed System:

Git is a distributed version control system (DVCS);

meaning that each user's local copy of the repository contains the entire history of changes.
This allows developers to work offline and makes collaboration more efficient, as changes can be shared directly between repositories without needing a centralized server.


3 git stages(workspace/working directory, staging/index, localrepo)(WSL)


Workspace / Working Directory:

This is where you have your actual project files. When you create, modify, or delete files in your project directory, they are in the workspace or working directory.
These changes are not yet tracked by Git until you explicitly tell Git to do so using the git add command.
Staging / Index:

The staging area, also known as the index, is a snapshot of your working directory that you prepare to commit.
After making changes to your files in the workspace, you add them to the staging area using the git add command. This prepares them for inclusion in the next commit.
Files in the staging area are not yet committed to the Git repository. They are in a pre-commit state, allowing you to review and organize your changes before committing them.
Local Repository:

The local repository is where Git permanently stores the committed changes.
After adding files to the staging area, you commit them to the local repository using the git commit command. This creates a new commit with a unique identifier (hash) and a commit message describing the changes.
Once changes are committed to the local repository, they become part of the project's history and can be viewed, reverted, or pushed to remote repositories as needed.
Here's a basic workflow illustrating how files move through these stages:

Modify Files in Workspace: Make changes to your project files in the workspace/working directory.

Stage Changes: Use the git add command to stage the changes you want to include in the next commit. For example:


git add filename
This command adds the specified file to the staging area. You can also use git add . to add all changes in the current directory to the staging area.

Review Changes: Use git status to review the changes in the staging area and ensure that you have included all the changes you want to commit.

Commit Changes: Once you're satisfied with the changes in the staging area, commit them to the local repository using the git commit command:


git commit -m "Your commit message"
This creates a new commit with the staged changes and attaches the provided commit message.

Repeat: Continue making changes to your files, staging them, and committing them to the local repository as needed.

Understanding these stages and how to work with them effectively is essential for using Git efficiently in your development workflow.



4 git init



git add
git commit -m "commit message"
git status
git log
git show <commit id>
git repo creation on remote server
git push
git config --global user.email
git config --global user.name
git config --list
git clone
git .ignore
git branch
git checkout
