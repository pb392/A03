# A03

PART 1: Directions on Using Webstorm.

Download the latest Git from https://git-scm.com/downloads . The version I downloaded 
on 2/14/2020 was 2.25.0. 
 
1. Find the downloaded file and install it. Usually this is done by double clicking the file.  
 
2. Optional: I uninstalled the previous version of Git and installed the new version of Git 
that I just downloaded.  
 
3. Start Webstorm. 
 
4. In Webstorm, check and install updates by choosing: Help -> Check for Updates  
(latest is 2019.3.3 – 2/14/2010) or 

6. Display the Webstorm settings, press (Ctrl+Alt+S)  
Choose Version Control -> Git. from the left side.

7. Click Test to make sure that Webstorm is connected to Git. The path in the location box 
should be C:\Program Files\Git\bin\git.exe. Auto-detect may find the git.exe file at 
C:\Program Files\Git\cmd\git.exe.  
 
If Git is installed correctly, you should get the message “Git Executed Successfully.” The 
version number is displayed. If you do not have Git installed, download Git as described 
in Step 1.  
 
8. Click OK to exit 

9. Click “Create New Project” on the Webstorm main page.  

10. NEW PROJECT: Choose a location and give the project a name. Overwrite the word 
“untitled” with the name you choose. For Example: 
 
C:\IS117Download\Webstorm\untitled  
Becomes 
C:\IS117Download\Webstorm\IS117DemoS20 
 
11. Click Create. 
 
12. Create a new file. 
Click File -> New -> HTML File -> HTML 5 
Name the file index (in lower case) 

13. Make some changes 

14. Click VCS -> Import into Version Control -> Create Git Repository 

15. Click OK. 
16. Commit the changes to GIT: 
VCS->Git -> Commit File  

Click Commit. 
If this is the first commit ever, you will have a dialog box open. Set the Git username and 
email. Use your .EDU email.  (Click Set and Commit) 

17. Add the project to GITHUB 
Click VCS -> Import into Version Control -> Share Project on Github

Click Share. 
If all goes well you will receive a message “Successfully shared project on GitHub.” 

The File is on the internet 

18. Add a new file to the GitHub Repository. 
Create a New file.  
Name it README.MD 

19. Add some text and commit. 

The new file is in the list

20. Make a change in Webstorm.  

21. Commit to Git  
VCS->Git->Commit 
Add the Commit comment and click Commit

22. Push the change to Github 
VCS -> Git -> Push (Cntl+Shift+K) 

The new line in the revised index.html file is now on GitHub.  

Good job! 
 

Part 2: Glossary to include these terms in a bulleted list.

Bold each of the Glossary words as you use them.  Bold ONLY the glossary word.

<strong>Branch</strong>: enables software development teams to work on separate parts of the same project without impacting the other.

<strong>Clone</strong>: making a copy of the selected elements

<strong>Commit</strong>: will save all staged changes with a brief description from the user in a "commit" to the local repository

<strong>Fetch</strong>: provides an inteface for manipulating parts of the HTTP pipeline, such as requests and responses

<strong>GIT</strong>: free, open-source, distributed Source Code Management system

<strong>Github</strong>: code hosting platform for collaboration and version control

<strong>Merge</strong>: combine two or more sorted sequences of data into a single sorted sequence

<strong>Merge Conflict</strong>: happens when you merge branches that have competing commits, and GIT needs help to decide which changes to incorporate 

<strong>Push</strong>: a mechanism for sending unsolicited data from a web server to a web browser

<strong>Pull</strong>: refers to a technique that enables a browser/client to request data from the server automatically without the user-intervention

<strong>Remote</strong>: files that reside on another CICS system

<strong>Repository</strong>: a place that hosts an application's code source, together with various metadata
