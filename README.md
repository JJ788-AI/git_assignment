# Git Assignment - <JJ788-AI>
#######################


a. What is an issue?  
Issues are used to track todos, bugs, feature requests, and more.

b. What is a pull request?  
  A pull request is a feature in Github that facilitates the review and intergation of code changes form one branch to another.

c. Describe the steps to open a pull request?  
1.Push Your Branch: Ensure that your changes are committed and pushed to a remote branch on the repository.
2.Navigate to the Repository: Go to the repository on your Git hosting platform (like GitHub).
3.Start a Pull Request: Find the "Pull Requests" tab and click on it. Then click on "New Pull Request" or a similar button.
4.Choose Branches: Select the branch with your changes as the source branch (the one you want to merge from) and the target branch (the one you want to merge into).
5.Add Details: Write a descriptive title and detailed description of the 6.changes you made.
6.Create Pull Request: Click the "Create Pull Request" button to open the pull request.

d. Describe the steps to add a collaborator to a repository (share write permissions)  
Navigate to the Repository: Go to the repository on your Git hosting platform.
Access Repository Settings: Click on the "Settings" tab of the repository.
Select Manage Access or Collaborators: Look for a section named "Manage Access" or "Collaborators" .
Invite a Collaborator: Click the button to invite or add a collaborator. Enter their username, email, or GitHub handle.
Set Permissions: Choose the appropriate level of access (e.g., write access) and send the invitation.
Wait for Acceptance: The invited collaborator will need to accept the invitation to gain access.

e. What is the difference between git and GitHub?  
Git: Git is a distributed version control system used to track changes in source code during software development. It allows multiple developers to work on a project simultaneously, manage different versions of code, and merge changes.
GitHub: GitHub is a web-based platform that uses Git for version control. It provides a user-friendly interface, collaboration tools (like pull requests and issues), and additional features such as project management and code review. GitHub hosts repositories online and makes it easier to collaborate with others.

f. What does git diff do?  
git diff is a Git command used to show the differences between various states of a repository.

g. What is the main branch?  
The main branch (often named main or master) is the default branch in a Git repository where the stable, production-ready code typically resides. It's the branch into which changes are merged from other branches and is generally the primary branch that represents the latest version of the project.

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?  
It is generally recommended not to push changes directly into the main branch for ongoing development. Instead, create feature branches or topic branches for each set of changes. We can then merge these branches into the main branch via pull requests, ensuring a more organized and manageable development workflow.