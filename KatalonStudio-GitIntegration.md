# KatalonStudio-Git Integration

# Token generation 

Open Github Account Click On Profile Icon ->Settings

![image](https://user-images.githubusercontent.com/11056300/159326029-708d6cea-b97d-4cfd-83b8-ec0601449562.png)

1.	Click on Developer Settings

![image](https://user-images.githubusercontent.com/11056300/159326166-d1343f5f-7346-4030-b7f4-040e03015b4d.png)

2.	Click on Personal Access Token

![image](https://user-images.githubusercontent.com/11056300/159326241-def1691f-6871-47bf-95d1-61d580d96f09.png)

3.	Click on Generate New Token button

![image](https://user-images.githubusercontent.com/11056300/159326310-da9ab8c5-6b61-4ec7-bd6b-49d3031cc4ca.png)

4.	Enter password of github Account

![image](https://user-images.githubusercontent.com/11056300/159326392-53630943-9b96-481e-8ecf-936551e5c827.png)

5.	Enter note name and click on Generate Token button

![image](https://user-images.githubusercontent.com/11056300/159326450-d1a745dd-eb8b-4958-a12e-a0acea3d22c9.png)

![image](https://user-images.githubusercontent.com/11056300/159326476-14ed7116-4aaf-45dd-ba3c-26d3d25a9406.png)

6.	Copy that generated Token and used as password while Pushing code

# Configuring Git Integration

By default the git option will be disabled in Katalon. So we need to enable it. We can enable on following the below steps.
1)	Click on Window
2)	Click on Katalon Studio Preferences
3)	The screen will look like as below

![image](https://user-images.githubusercontent.com/11056300/159326643-abdc10d8-0e6b-47d0-bbab-cc078dc1a1b3.png)

4)	Click on Katalon
5)	Click on Git
6)	The screen will look like as below

![image](https://user-images.githubusercontent.com/11056300/159326684-8c7e6233-6a9a-4197-867c-a8193f49d44f.png)

7)	Select the check box of ‘Enable Git Integration’
8)	Click on Apply
9)	Click on Apply and Close

'Now the git Integration feature should be enabled. We are ready to use the Git from Katalon Studio.'

# Cloning Katalon Studio project from git repository

After enabling Git Integration, we can clone an existing Git repository into a newly-created directory on the local machine.
We can create the new git repository on following the below steps if we don’t have any existing.

1)	Login to GitHub
2)	Click on + icon as shown in below screen.

![image](https://user-images.githubusercontent.com/11056300/159326899-6971e4bc-f8a7-4c28-9afc-a34cacb29140.png)

3)	Click on New repository, screen will be shown as below

![image](https://user-images.githubusercontent.com/11056300/159326954-48438230-8d8a-4cfb-a7c7-ef8e9b2b29c4.png)

4)	Enter the repository name
5)	Click on Create Repository
6)	Now go to Katalon Studio
7)	Click on drop-down icon of git
8)	The list will be displayed as below

![image](https://user-images.githubusercontent.com/11056300/159327039-9c23e155-d90b-410d-ba5a-83127d5078e2.png)

9)	Click on Clone Project
The pop up will be opened as below.  Provide the repository url: https://github.com/vtestcorp/CrossCountry.git

![image](https://user-images.githubusercontent.com/11056300/159327102-c08c6460-0ee7-4796-a06d-6aefc2de70be.png)

10)	Provide the repository url and credentials
11)	Click on Next

![image](https://user-images.githubusercontent.com/11056300/159327152-35b08bb4-64bd-406c-8d03-feb633eb8e38.png)

12)	Select the branch as master and Click on Next
13)	The project will be cloned to your local and will look like as below.

![image](https://user-images.githubusercontent.com/11056300/159327200-c28e4857-3376-47a7-8001-3225cec52663.png)

# Committing the changes to git repository

1)	Click on git drop-down and click on Commit

![image](https://user-images.githubusercontent.com/11056300/159327285-ba273033-7ad4-496f-8e93-d608d06cea0e.png)

2)	The next screen will look like as below

![image](https://user-images.githubusercontent.com/11056300/159327327-2288c1de-6581-4d50-9872-3f6ffac79f86.png)

i)	From the Unstaged Changes list, select the changes to be committed, then right-click on them and select Add To Index. 
Selected changes are added to the Staged Changes list.
ii)	Enter your comments into the Commit Message, then click on Commit and Push to store your staged changes into the local branch.
The new pop-up will be opened as below.

![image](https://user-images.githubusercontent.com/11056300/159327412-6a441f05-c0fc-46c2-a8c1-cb573b85e233.png)

3)	Enter Username of github and Personal Token Access as a Password and Click on Ok Button
4)	Check Github Repository now changes are updated.

GitHub url with the Katalon Project:
https://github.com/vtestcorp/CrossCountry.git

# Manage Branches

We can perform a couple of operations under manage branches like creating new branch, checkout branch, Delete branch etc.
i)	Click on git drop-down
ii)	Mouse hover to Manage Branches
iii)	The screen will look like as below:

![image](https://user-images.githubusercontent.com/11056300/159327509-e36396ea-b5e5-46b0-90cc-3a1f0b63145f.png)

**1)	New Branch creation:**
i)	Click on git drop-down
ii)	Mouse hover to Manage Branches
iii)	Click on New Branch
iv)	A new pop-up will be opened with Create Branch
v)	Click on Select and select the source
vi)	Provide the branch name
vii)	Let it be the Checkout New Branch to be checked
viii)	Click on Finish

![image](https://user-images.githubusercontent.com/11056300/159327588-7a206a7d-85fe-49f9-854c-cb92db09b74b.png)

**2)	Checkout Branch:**
i)	Click on git drop-down
ii)	Mouse hover to Manage Branches
iii)	Click on Checkout Branch
iv)	Select the branch and click on Ok

![image](https://user-images.githubusercontent.com/11056300/159327701-8454171a-4c71-45bf-bf12-2f1bc64c37b8.png)


**3)	Delete Branch: **
i)	Click on git drop-down
ii)	Mouse hover to Manage Branches
iii)	Click on Delete Branch
iv)	Select the branch the one which want to delete and click on Ok

![image](https://user-images.githubusercontent.com/11056300/159327770-52af3a6e-71f2-421c-b984-cd5c3ecd6e61.png)
