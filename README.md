# A02

 _**GitHub and Git Tutorial**_

**Part 1**: How to Use Git and GitHub

**Step 1**: Install Git

* Go to the Git Website: https://git-scm.com/install/
* After that, you should download Git with the correct OS (Operating System)
* Follow the instructions the software gives to set up and install Git
* Once downloaded, open the command prompt
* To ensure that Git is working, type *git --version*
* After this happens, the command prompt will show that Git is installed.

**Step 2**: Sign up for GitHub

* When signing into GitHub, enter the desired email you want to use
* Create a strong password that has at least 15 characters
* Once the password is created, think of a unique username that isn't taken
* Verify your account by checking your email

**Step 3**: Create a Repository

* In the top-right corner of GitHub, press the + button
* After that, select the option that states ** New repository **
* Enter the name for your project
* Select the options private or public to determine the visibility of your repository
* Select the option *Add a README file* for GitHub to create the file
* Finally, select *create repository*

**Step 4**: Make a local Repository

  * Open the Command Prompt
  * Go to *cd project-folder* by navigating your project folder
  * After that, you have to initialize Git by entering *git init*

**Step 5**: Connecting GitHub to Git

* Copy the GitHub Repository URL that you made
*  After that, go back to the command prompt in Git
*  Connect the local Repository to GitHub by typing this: *git remote add origin https://github.com/username/project.git*
* After that, ensure that the connection is secure by entering this: *git remote -v*

**Step 6**: Track the Changes You Made

* Select Create or Edit files in your project
* Check which files have been edited by entering this: *git status*
* Add the files to Git by entering this: *git add .*

**Step 7**: Use a Commit to Save Changes

* Go back to the command prompt within Git
* After that, type this: *git commit -m "Whatever changes you made"*
* Ensure that you write in your commit the changes you made in your file

**Step 8**: Upload the Changes You Made to GitHub

* In the Git command prompt, enter *git push origin main*
* After that, go to GitHub to ensure that the changes appear in the GitHub Repository


**Part 2**: Glossary of Tutorial

* Branch: A Branch is an isolated workspace from the main codebase
* Clone: A clone is a copy of the repository from GitHub, which can be downloaded to your personal computer
* Commit: Commits are important to track changes made in the repository 
* Fetch: A fetch is when you can download commits, files, etc. from the repository that can be saved on the computer
* GIT: A system where the changes can be seen in the source code
* GitHub: GitHub is a website where you can add Git repositories
* Merge: Merge is when changes in one branch can be integrated into another branch
* Merge Conflict: This is when a merge fails
* Push: Commits are uploaded to a repository in order for other people to download those commits
* Pull: A pull is when changes are made in a repository, then merged into a branch
* Remote: A repository is hosted on GitHub
* Repository: Project files are stored here, and the changes can be seen

 **Commits**

 * Task: Created Repository
 * Fix: Edited the README file name to README.md to write definitions and the necessary terms
 * Feature: Added tutorial for Git x GitHub and added glossary + references

**References**
https://docs.github.com/en/get-started
https://docs.github.com/
https://git-scm.com/doc



    
