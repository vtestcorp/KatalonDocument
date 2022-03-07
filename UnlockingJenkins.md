# Unlocking Jenkins

When you first access a new Jenkins instance, you are asked to unlock it using an automatically-generated password.

## Step 1:

Browse to http://localhost:8080 (or whichever port you configured for Jenkins when installing it) and wait until the Unlock Jenkins page appears.

![image](https://user-images.githubusercontent.com/11056300/157043443-41b2e794-f556-4324-a1c7-d71b715f9de9.png)


## Step 2:

The initial Administrator password should be found under the Jenkins installation path (set at Step 2 in Jenkins Installation).
For default installation location to C:\Program Files\Jenkins, a file called initialAdminPassword can be found under C:\Program Files\Jenkins\secrets.
However, If a custom path for Jenkins installation was selected, then you should check that location for initialAdminPassword file.

![image](https://user-images.githubusercontent.com/11056300/157043572-d39a8a19-dff0-4b69-8511-b3514ab17683.png)


## Step 3:

Open the highlighted file and copy the content of the initialAdminPassword file.

![image](https://user-images.githubusercontent.com/11056300/157043645-5feb1dd9-4d04-448a-bdfe-1eddac26b5ca.png)


## Step 4:

On the Unlock Jenkins page, paste this password into the Administrator password field and click Continue.

Notes: 
●	You can also access Jenkins logs in the jenkins.err.log file in your Jenkins directory specified during the installation.
●	The Jenkins log file is another location (in the Jenkins home directory) where the initial password can also be obtained. 

![image](https://user-images.githubusercontent.com/11056300/157043891-3a9e490c-a1ed-4353-8b29-62b646159e3f.png)

This password must be entered in the setup wizard on new Jenkins installations before you can access Jenkins’s main UI. This password also serves as the default administrator account’s password (with username "admin") if you happen to skip the subsequent user-creation step in the setup wizard.
