# Jenkins Installation

## How to install Jenkins on Windows

Refer to the Windows section of the Downloading Jenkins page to download either an LTS release or a weekly release of the Windows installer. After the download completes, open the Windows installer and follow the steps below to install Jenkins.


## Step 1: Setup wizard

On opening the Windows Installer, an Installation Setup Wizard appears, Click Next on the Setup Wizard to start your installation.

![image](https://user-images.githubusercontent.com/11056300/157041967-03b99ac5-63cc-4e76-9f88-9083ddb8d066.png)


## Step 2: Select destination folder

Select the destination folder to store your Jenkins Installation and click Next to continue.

![image](https://user-images.githubusercontent.com/11056300/157042084-91328c30-5a26-405a-aee7-d077379cb4ca.png)


## Step 3: Service logon credentials

When Installing Jenkins, it is recommended to install and run Jenkins as an independent windows service using a local or domain user as it is much safer than running Jenkins using LocalSystem(Windows equivalent of root) which will grant Jenkins full access to your machine and services.
To run Jenkins service using a local or domain user, specify the domain user name and password with which you want to run Jenkins, click on Test Credentials to test your domain credentials and click on Next.

![image](https://user-images.githubusercontent.com/11056300/157042181-5e993234-a3a1-48bc-9064-e35fdb6e88c9.png)


## Step 4: Port selection

Specify the port on which Jenkins will be running, Test Port button to validate whether the specified port if free on your machine or not. Consequently, if the port is free, it will show a green tick mark as shown below, then click on Next.

![image](https://user-images.githubusercontent.com/11056300/157042255-2b1dbcc8-102f-46fe-a922-12dea4325f37.png)

## Step 5: Select Java home directory

The installation process checks for Java on your machine and prefills the dialog with the Java home directory. If the needed Java version is not installed on your machine, you will be prompted to install it.
Once your Java home directory has been selected, click on Next to continue.

![image](https://user-images.githubusercontent.com/11056300/157042380-794a07c2-b82b-4109-8d55-d18ce4e8eae5.png)


## Step 6: Custom setup

Select other services that need to be installed with Jenkins and click on Next.

![image](https://user-images.githubusercontent.com/11056300/157042477-53791f67-d0bf-4fd3-a2b8-e481b5880d86.png)


## Step 7: Install Jenkins

Click on the Install button to start the installation of Jenkins.

![image](https://user-images.githubusercontent.com/11056300/157042586-fcb32d90-5dc6-43c4-bf35-b32e3b289e8c.png)

Additionally, clicking on the Install button will show the progress bar of installation, as shown below:

![image](https://user-images.githubusercontent.com/11056300/157042660-10770de7-6628-4d9d-8523-564f4790e4f2.png)


## Step 8: Finish Jenkins installation

Once the installation completes, click on Finish to complete the installation.
Jenkins will be installed as a Windows Service. You can validate this by browsing the services section, as shown below:

![image](https://user-images.githubusercontent.com/11056300/157042759-a91ea4e2-b474-42d9-b42d-8727fa64325d.png)
