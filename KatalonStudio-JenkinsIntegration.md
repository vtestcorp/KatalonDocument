# KatalonStudio-Jenkins Integration

We need to follow the below steps to run the Katalon project from Jenkins.

# Jenkins installation 

Download the Jenkins from the official web-site.
https://mirrors.tuna.tsinghua.edu.cn/jenkins/war-stable/2.319.2/jenkins.war
Now go to the the path where Jenkins.war file is present
Open the command prompt
Use the command java –jar Jenkins.war and press enter

![image](https://user-images.githubusercontent.com/11056300/159328631-3b72b9cc-4b87-46e1-ad0c-13ca90708d40.png)

Once the execution is completed then open the browser.
Refer this to check the completion of the jobs.
INFO    hudson.WebAppMain$3#run: Jenkins is fully up and running.
Type the url https://localhost:8080 and provide the required details.
Login to the Jenkins and Click on New Item to create the Jenkins Job.

# Jenkins Job Creation

Login to the Jenkins and Click on New Item to create the Jenkins Job.
The below pop-up will be opened

![image](https://user-images.githubusercontent.com/11056300/159328777-ec10f444-2437-4442-a990-e159367e9da3.png)


Provide the job name under Enter an item name text field.
Select the Freestyle project
Click on Ok button. The below screen will be displayed.

![image](https://user-images.githubusercontent.com/11056300/159328831-938e8857-9616-43a6-b8ee-1ec3e148877c.png)

# Source Code Management

To provide the project details, we need to integrate with github where our Katalon project is present.
Click on Source Code Management tab.
Click on git
Provide the Repository url(We can copy it from code in GitHub).
The screen will look like as below.

![image](https://user-images.githubusercontent.com/11056300/159328918-ef6a12c8-a041-4625-bc1e-b4a0bfcd928f.png)

**Build:**

To provide the command we need to use Build component.
Click on Build 
Select Execute Windows batch command in drop-down of Add build-step

![image](https://user-images.githubusercontent.com/11056300/159329042-3ced0c34-3848-44a4-8e00-7daf6d2dbb00.png)

The screen will look like as below.

![image](https://user-images.githubusercontent.com/11056300/159329098-08d747ce-cb7e-4bef-b6db-feabad7ac7fc.png)

Click on Save

Now we will be working to generate the command and to use it in Jenkins Job.
Refer the topics Test Cases Executions from Command Prompt, how to generate the command in Katalon.
Copy the Katalon_Studio_Engine_Windows folder to  Jenkins workspace

**Providing the commands of created job**

Open the created Jenkins job and click on Build component.
Provide the path of katalon_Studio_Engine and the generated command.
Edit the command and provide the path of workspace folder instead of local.
The screen will look like as below after editing.

![image](https://user-images.githubusercontent.com/11056300/159329232-7c746ba0-aef1-4895-93d5-e26eb646e585.png)

Click on Save

**Executing Jenkins Job**

Open the created job and the screen will look like as below.

![image](https://user-images.githubusercontent.com/11056300/159329442-19e4a58c-bf7c-486d-b5b9-fe3ceb994065.png)

Click on Build Now
The test cases will start executing and the browser will launch.
Screen will look like as below

![image](https://user-images.githubusercontent.com/11056300/159329496-2efc96e7-ab07-4812-a0a0-0b2e846b86ce.png)
