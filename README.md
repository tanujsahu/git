# GIT
 Git is a powerful tool for managing the codebase of a project and collaborating with other developers. Whether you are working on a small personal project or a large team-based project, Git is a great choice for version control.


 There are several common things related to Git that every developer should know about. Here are some of the most important 

# Repository
A repository is a central location where all the code, files, and history of a project are stored. You can create a new repository or clone an existing one to work on.

# Branch 
A branch is a separate line of development in Git that allows you to work on new features or bug fixes without affecting the main codebase. Once you're done with your changes, you can merge your branch back into the main codebase.

# Commit  
A commit is a snapshot of the changes made to a file or set of files. Each commit has a unique identifier and a commit message that describes the changes made.

# Merge 
A merge is the process of combining changes from one branch into another. This is typically done when a feature or bug fix is complete and needs to be merged back into the main codebase.

# Pull Request 
A pull request is a request to merge changes from one branch to another. It allows other developers to review the changes and provide feedback before they are merged.

# Remote 
A remote is a copy of a repository that is hosted on a server or online service, such as GitHub or GitLab. You can push your changes to a remote to share your work with other developers.

# Clone 
A clone is a copy of a repository that is downloaded to your local machine. Cloning a repository allows you to work on it locally and make changes before pushing them back to the remote.

# Fork 
A fork is a copy of a repository that is made on a remote service, such as GitHub. Forking a repository allows you to make changes to the code without affecting the original repository.

Overall, these are just a few of the many common things related to Git. Understanding these concepts is essential for anyone working with Git, as they form the foundation of version control and collaboration.



## Here is a brief description of some of the most commonly used Git commands 

# git add 
This command adds changes made to a file or set of files to the staging area. The staging area is where you can review and prepare changes before committing them.

 # Exapmle

    git add file_name   or git add .

# git commit 
This command creates a new commit with the changes made to the files in the staging area. Each commit has a unique identifier and a commit message that describes the changes made.

 # Exapmle

    git commit -m "here your message"

# git push
This command uploads changes from your local repository to a remote repository. This is typically done to share changes with other developers or to update the codebase in a shared repository.

 # Exapmle

    git push origin feature_branch_name

# git pull
This command downloads changes from a remote repository and merges them into your local repository. This is typically done to update your local repository with changes made by other developers.

 # Exapmle

    git pull origin master

# git stash
This command temporarily saves changes that are not yet ready to be committed. This is useful when you need to switch to a different branch or work on a different task without losing your changes.

 # Exapmle

    git stash

# git stash list
In This command in Git that displays a list of all stashes that are currently saved in the repository. The command displays the stash reference, the message associated with the stash, and the date and time the stash was created.

 # Exapmle

    git stash list

# git stash pop
This command applies changes saved in the stash back to the working directory. This is useful when you want to retrieve changes that were saved using git stash

 # Exapmle

    git stash pop




