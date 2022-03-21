# KatalonStudio-GitLab CI And CD

Follow the below steps to make setup of GitLab CI/CD:
1.	Login To Your GitLab Account
2.	If our project not on github then we can create New repository/Project  in  GitLab
3.	If your project is available to GitHub then import GitHub project to GitLab
After Importing project it looks like following

![image](https://user-images.githubusercontent.com/11056300/159329721-9a9300ea-c5d1-49d4-a9e8-481027d7062d.png)

4.	Now Click on Go to project
5.	Our Project is successfully imported to GitLab.
6.	Now Register and Install GitLab Runner
Step1 : Go to this link https://docs.gitlab.com/runner/ click on install then scroll down and in binaries you will see installations for different OS so now click on Install on Windows then you will see 32 or 62 bit so install as per your machine.

Step 2: Then go to C drive and create a folder that the name GitLab-Runner and copy the installer that you have download and paste in GitLab-Runner folder and rename the installer with the name gitlab-runner. 
Step 3: Then go to command prompt (Administrator)and type first command 
cd C:\GitLab-Runner

Step 4: Then run the command .\gitlab-runner.exe install for install
Step 5: We can also check details of GitLab using .\gitlab-runner  --version command

![image](https://user-images.githubusercontent.com/11056300/159329779-39d507d8-ac9c-4c35-90db-403a5dd6c506.png)

**Registering GitLab Runner**

Step 1: First Run the Command .\gitlab-runner register
![image](https://user-images.githubusercontent.com/11056300/159329886-39f6d5ca-9b31-4247-820a-1bb9bc36cd6c.png)

Step 2: Enter the URL so copy the URL in bracket and paste it
![image](https://user-images.githubusercontent.com/11056300/159329932-f83a0849-17c6-4949-8618-d415fcc8c95c.png)

Step 3: Enter Registration Token 
•	Firstly Goto GitLab Account
•	Click On Project
•	Then Click on Setting -> CI/CD

![image](https://user-images.githubusercontent.com/11056300/159330044-e79f1281-79b0-4b3b-9ac2-d16eea189736.png)

•	Click on Runner expand scroll down and copy registration token and paste on command prompt

![image](https://user-images.githubusercontent.com/11056300/159330096-fee4e173-1984-4e14-be5e-0bbb2ffa43e7.png)

![image](https://user-images.githubusercontent.com/11056300/159330129-4a4db67d-cf68-4419-82f5-08b8e18252e0.png)

•	Then Enter meaning ful description of runner

•	Enter Tags for runner (eg: SSH, ci)
•	Choose any executor
•	Runner Registered Successfully message shows

•	Enter Tags for runner (eg: SSH, ci)
•	Choose any executor
•	Runner Registered Successfully message shows

**Starting Runner**

Run the command .\gitlab-runner.exe start

Note: Currently on executing the configured gitLab pipeline project it’s failing and we are working on it.
