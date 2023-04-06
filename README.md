# gitproject


Git and GitHub Training 
PROJECT – Branching Development Model
BY
JAYAMURGAN SEKAR
SIMPLI LEARN
MASTERS IN DEVOPS ENGINEER

Branching Development Model
Course-end Project 1
DESCRIPTION
Create a branching model to help your team understand the Git Feature Branch Workflow for faster and efficient integration of work
 
Background of the problem statement:
M-theta Technology Solutions hired you as a DevOps Architect. It is undergoing an infrastructural change to implement DevOps to develop and deliver the products. Since M-theta is an Agile organization, they follow the Scrum methodology to develop the projects incrementally. Hence, the company wants to adopt Git as a Source Code Management (SCM) tool for faster integration of work and smooth transition into DevOps.
So, as a DevOps Architect, you have been asked to build a branching model to demonstrate the Git Feature Branch Workflow for the company’s engineering team. In the branching model, you are required to create a Production branch which will act as the main (master) branch, an Integration branch which will again have two branches inside it namely Feature 1 and Feature 2, and a Hotfix branch which will be used for fixing any issues that could come up from Integration or Production branches.
 
 
 
You must use the following:
Git: To build the branching model
 
Steps to perform:
1.	Start with the Production branch (master branch), and then create a HotFix  and Integration branch
2.	Subsequently, create Feature 1 and 2 branches that integrate to the Integration branch as shown in the above figure
3.	Commit some changes in the Feature 2 branch and merge it into the Integration branch. Delete this branch once merging is complete
4.	Commit some changes in the Feature 1 branch and rebase it to the Integration branch
5.	Merge the Integration branch into Hotfix and Production branch to update these branches
6.	Commit some changes in Feature 1 branch, and then merge it into Integration, Hotfix, and Production branch. Delete this branch once merging is complete
7.	Commit some changes in the Hotfix branch and merge it into the Production as well as the Integration branch
Step 1: Create the Production Branch (Master Branch):

Create a new repository on a Git hosting service like GitHub, GitLab, or Bitbucket.
•	To Create a new branch called "Production" or "Master" using the git branch command.
•	To rename the master branch to production using the git branch -m production command, for better understanding.
 

Step 2: Create the Hotfix Branch:
•	Create a new branch called "Hotfix" using the git checkout -b hotfix command.
•	Make any necessary changes or fixes to the code in the Hotfix branch.
•	Once the Hotfix is complete, merge it into the Production branch using the git merge command.

 

Step3:Create the Integration Branch:

•	Create a new branch called "Integration" using the git branch command.
•	Create two new branches called "Feature 1" and "Feature 2" using the git branch command.
•	Work on the code changes for each feature in their respective Feature branches.
•	Once the features are complete, merge Feature 2 into the Integration branch using the git merge command.
•	Delete the Feature 2 branch using the git branch -d command.
•	Rebase Feature 1 branch onto the Integration branch using the git rebase command.



 
 
 
Step3: Merge the Integration Branch into Hotfix and Production Branch:

•	Merge the Integration branch into the Hotfix branch using the git merge command.
•	Merge the Integration branch into the Production branch using the git merge command.
 
Step4: Merge Feature 1 Branch into Integration, Hotfix, and Production Branch:

•	Merge the Feature 1 branch into the Integration branch using the git merge command.
•	Merge the Feature 1 branch into the Hotfix branch using the git merge command.
•	Merge the Feature 1 branch into the Production branch using the git merge command.
•	Delete the Feature 1 branch using the git branch -d command.
 
Step 5: Make Changes in Hotfix Branch:

•	Make any necessary changes or fixes to the code in the Hotfix branch.
•	Merge the Hotfix branch into the Production branch using the git merge command.
•	Merge the Hotfix branch into the Integration branch using the git merge command.
 

