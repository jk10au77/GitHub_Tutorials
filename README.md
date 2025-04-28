# GitHub_Tutorials
Here we are going to learn GitHub basics
-------------
Introduction:
-------------
Here you will learn GitHub basics like. 
  a. What are Repositories, how to create and use them.
  b. What are Branches and how to start and manage new branch. 
  c. What are Commmits. How to make changes to a file and push them to GitHub as commits.
  d. What are Pull Requests? How to Open and merge a pull request.

-------------
Prerequisites:
--------------
a. You must have a GitHub account. Use the below link to create GitHub account:
https://docs.github.com/en/get-started/start-your-journey/creating-an-account-on-github

--------------------------
Step1: Create Repository:
--------------------------
a. Think Repository as a Folder
b. It contains all related items such as files, images, videos, or even other folders.
c. It often includes README file which contains information about your project.
d. README files are written in Markdown, which is an easy-to-read, easy-to-write language for formatting plain text.
e. GitHub creates README file at the time of Repository creation time. 

----------------------------
Steps to create Repository:
----------------------------
a. In the upper-right corner of any page, select , then click New repository.
b. In the "Repository name" box, type the 'REPOSITORY NAME' 
C. In the "Description" box, type a short description. For example, type "This repository is for GitHub Tutorial."
d. Select whether your repository will be Public or Private.
e. Select Add a README file.
f. Click Create repository.

----------------------
Step2: Create Branch:
----------------------

a. Uses: Branching lets us to have different versions of repository at the same time.
b. By default, Every repository has one brance called main 
c. We can create additional branches off of the main in the repository.
d. Using branchning, we add new features to the project without changing the main source code. To reflect those new 
   changes in main source code, we need to merge our new features in the brach into the main source code.
e. Creating a branch means you are creating a copy or snapshot of the source code in the main branch.
f. If someone else is making changes to the main branch while you were working on your branch, you could pull in those changes.

--------------------------
Steps to create a branch:
--------------------------
1. Click the 'Code' tab of your hello-world repository.
2. Above the file list, click the dropdown menu that says main.
3. Type a branch name, say YOUR 'BRANCH_NAME' into the text box.

Now you have two branches, main and your 'BRANCH NAME'. Both these branches have same content.

Next add your changes in your 'BRANCH NAME' branch.
----------------------------------------
Step3: Make Changes and Commit changes:
----------------------------------------
a. After creating a new branch, this new branch contains a copy of the 'main' branch content. 
b. Now we add our changes, Then save ou change. Saved changes are called commits.
c. Each commit has associated commmit messages, which explains the description of changes. Commit messages capture the history of 
   your changes so that other ontributors can understand what you’ve done and why.

-----------------------------------
Steps to make and commit changes:
-----------------------------------
a. Under your 'BRANCH NAME', click the README.md file.
B. To edit the file
C. In the editor, add your changes.
d. Click Commit changes.
e. In the "Commit changes" box, write a commit message that describes your changes.
f. Click Commit changes.

These changes will be made only to the README file on your 'BRANCH NAME' branch, so now this branch contains content that's different from main.

-------------------------------
Step4: Open a Pull Request:
-------------------------------
a. Now you have made all the changes in a branch off of 'main'. Now create a 'Pull' request.
b. Pull requests are the heart of collaboration on the GitHub.
c. When you open a 'Pull' request, you are doing the following tasks
    1. You are proposing changes and requesting your peers to review and pull in your contributions 
    2. Merge them into their branch.
d. Pull requests show diffs or differences of the content from both branches. The changes, additions, and subtractions are shown in different colors.
e. You can open a pull request as soon as you make a commit 

-----------------------------
Steps to open Pull request:
-----------------------------
1. Click the Pull requests tab of your repository.
2. Click New pull request.
3. see the content changes between your 'BRANCH NAME' and the 'main' branch
4. Look over your changes in the diffs on the Compare page, make sure they're what you want to submit.
5. Click Create pull request.
6. Give your pull request a title and write a brief description of your changes. You can include emojis and drag and drop images and gifs.
7. Click Create pull request.

--------------
Peer review:
--------------
In collaboration work, this is the time you would ask for peer review. This allows your collaborators to comment on, or propose changes to, 
your pull request before you merge the changes into the main branch.

--------------------------------
Step5: Merge Your pull request
--------------------------------

a. This is the final step. Here we will merge our branch content into 'main' brain.
b. After you merge your pull request, the changes in branch will be incorporated into the main branch.
c. a pull request may introduce changes to code that conflict with the existing code on main. If there are any conflicts, GitHub will alert you about the conflicting code and prevent merging   
     until the conflicts are resolved. You can make a commit that resolves the conflicts or use comments in the pull request to discuss the conflicts with your team members.

----------------------------------
steps to merge your pull request:
----------------------------------
a. At the bottom of the pull request, click Merge pull request to merge the changes into main.
b. Click Confirm merge. You will receive a message that the request was successfully merged and the request was closed.
c. Click Delete branch. Now that your pull request is merged and your changes are on main, you can safely delete the readme-edits branch.
d. click code tab of your repository to see your published changes on the 'main' branch
