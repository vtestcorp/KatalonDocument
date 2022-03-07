# BrowserStack- Credentials Configuration

Once you’ve installed the plugin, you will need to configure your BrowserStack credentials to complete the integration between Jenkins and your Selenium Webdriver tests. This can be done by either using Jenkins UI or using a Jenkinsfile.

	JenkinsUI
 
	JenkinsFile

Follow the below steps to configure BrowserStack details inside Jenkins:

## Step 1:

1.	Login to Jenkins and Open the configured Jenkins Job
2.	Go to Manage Jenkins > Configure System.


## Step 2:

Under the BrowserStack section, click on the Add button next to BrowserStack Credentials. 

![image](https://user-images.githubusercontent.com/11056300/157075479-e388d6c5-113e-44b6-b00e-316937e81230.png)


## Step 3:

Enter your BrowserStack Username and Access Key which you can find on your BrowserStack Account Settings page. 

![image](https://user-images.githubusercontent.com/11056300/157075600-d17ee767-1163-4b8d-87ee-b5cf1651307d.png)

## Step 4:
 
 Once you add your credentials, Jenkins generates an unique CredentialD which is used in the Jenkinsfile, this ID is changed every time you add your credentials. 

![image](https://user-images.githubusercontent.com/11056300/157075739-11ed3585-c5d7-49c4-9b99-5e2a6a1ec2bb.png)


## Step 5:

In order to avoid new CredentialD, you can provide custom credentialD while adding credentials. Hence, you will not be required to update Jenkins file every time. Follow the below steps to add custom CredentialID.
a. Click on Advanced as highlighted in the following figure: 

![image](https://user-images.githubusercontent.com/11056300/157075894-609b250d-cf11-4d6b-a87c-29375b1142d9.png)

b. Add the custom ID in the ID field and Save the changes: 

![image](https://user-images.githubusercontent.com/11056300/157075982-fa899ef3-2683-4c75-8278-957a71a0dfc7.png)
