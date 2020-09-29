Understanding of Git/GitHub/Webstorm
====================================
1. Download Webstorm from https://www.jetbrains.com/webstorm/
2. Download Git from https://git-scm.com/downloads
3. Sign up for GitHub at https://github.com/ or sign in using an existing account
4. Open up webstorm and sign in.  After getting through a few personalization options, you will arrive at a window that allows you to create a new project.  Before you continue you must connect Webstorm and Git.  Start by clicking on the "configure" button at the bottom of the window and then click "settings".
5. On the left side, click to open the drop down menu for "version control" and then click "git".  At the top, find "Path to Git executable".  Verify that the Git program selected is the correct one by pressing the "test" button to the right.  Confirm that the correct Git version is selected, if not you need to find the installation location of Git and enter it to the path.
6. On the left side again, navigate to "Appearance & Behavior", then click "System Settings", and finally click "Passwords".  If the ending of the path is "c.kdbx", you are good to go.  This is where your passwords entered into Webstorm are being saved.
7. Go to https://github.com/ and make sure you are signed in.  Now create a repository by either clicking the plus arrow in the top right of the screen next to your profile picture or click the green "New" button towards the left side of you screen.
8. Enter a name for your repository that is descriptive. In addition, you can add a description of the repsoitory if you would like.  Select either public or private depending on your purpose for the repository and finally select readme to add a README file that will be populated in the future.
9. You can also create a repository from Webstorm.  On the top of the window, click the "VCS" tab, scroll down to "Import into Version Control", and then click "Create Git Repository...". Select a location to save this repository and then click "OK".
10. If you want to import a repository from GitHub, there are two options.  If you are on the main window when no projects are open, click "Get from Version Control".  The second option is when you have a project open, click the "VCS" tab on the top of the window, scroll down to "Git", and then click "Clone...".  No matter which option you select you will be directed to the same window.  If you have a url to a specific repository you can enter it into the "Repository URL" tab on the left or click on the "GitHub" tab and sign into GitHub to clone your own repositories.
11. If you want to make a new file inside of a project, click "File" in the top left, then "New", and then select the file type you would like create.  Select whichever one you want and enter a new for the file.
12. To add files to Git, right click on the file you want add from the project folder on the left.  Next scroll down to "Git" and click on "Add".  You can also add files by finding "VCS" at the top of the screen, scrolling down to "Git", and then click "Add".
13. After you add your files, you are ready to commit your changes.  You can follow the same steps from #12 and instead of clicking "Add", you click "Commit File...".  Another option is to go to the left side of your window and click on the "0: Commit" tab.  Once you have reach the "Commit Changes" windows, write a descriptive commit message that could be used as a reminder as to what the code does or what was changed just in case the new changes need to be modified in the future.
14. At this point you are ready to push your changes to a remote repository.  On the top of the window, click the "VCS" tab, scroll down to "Git", and then click "Push...".  Select the files that you committed before and click "Push".
15. Go to GitHub and your file(s) should be inside your repository.

Glossary of Terms
=================
**Branch**- a separate workspace from the master branch that allows you to develop features, fix bugs, or safely experiment with new ideas in a contained area of your repository.

**Clone**- duplicating an existing repository

**Commit**- similar to saving a file, where you can write messages to keep track of changes you have made in the past

**Fetch**- retrieve new work done by other people

**GIT**- a version-control system for tracking changes during software development

**Github**- a code hosting platform for version control and collaboration

**Merge**- combine changes made by other people with changes done locally

**Merge Conflict**- changes that have been made to the file conflicts with existing code or changes made in the same file in another location

**Push**- taking changes that have been made on local machine and uploading them to a repository in GitHub

**Pull**- combination of fetch and merge

**Remote**- a place where teams can collaborate on work

**Repository**- a directory or storage space where you can store files

References
==========
https://njit.instructure.com/courses/13292/files/984370?module_item_id=248756
