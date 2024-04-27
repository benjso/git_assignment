# Git Assignment - benjso

a. What is an issue?
 Ans: The items can be created in a repository to plan, discuss and track work. The developer/team can use issues to track work, give or receive feedback, collaborate on ideas or tasks, and efficiently communicate with others.

b. What is a pull request?
Ans: Pull requests are created to let others know about changes beinng pushed to a branch in a repository on GitHub. Once a pull request is opened, the developer can discuss and review the potential changes with collaborators and add follow-up commits before those changes are merged into the main branch.

c. How do I open up a pull request?
Ans: In the "Pull requests" tab/section, click the button "New pull request", compare the changes between working branch and main branch, add some meaningful description about the changes to facilitate the review by others. Also, it needs to ensure the repo is public and/or add more than one reviewer for review/approval as well as other best practices.

d. Give me a step by step guide on how to add someone to your repository.
Ans: In the "Settings" tab/section, choose Collaborators in the left pane, click the button "Add people", seach the name and add the right reviewers to enable the access for them.

e. What is the difference between git and GitHub?
Ans: Git is a version control system that lets the developer/team manage and keep track of the source code history. GitHub is a cloud-based hosting service that let the developer/team manage Git repositories.

f. What does git diff do?
Ans: It is a git command with the same function to that on GitHub UI, which helps the developer/team to see, compare, and understand changes in the project. It can be used in many different situations, e.g. to look at current changes in the working copy, past changes in commits, or even to compare branches

g. What is the main branch?
Ans: By default, GitHub names the default branch main for new repository, i.e. initial branch that Git checks out locally when someone clones the repository. Unless specify a different branch, it is the base branch for new pull requests and code commits. 

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?
Ans: No, it is NOT a best practice and probably cause a big chaos later on, particularly in a large software engineering project. The right approach is to create a working branch for new changes, create a pull request instead, and invite more than one reviewers to perform the review and approve accordingly, then merge into main branch.