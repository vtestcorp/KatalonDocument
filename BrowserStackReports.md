# BrowserStack - Reports

The BrowserStack Jenkins plugin enables you to embed the test results from BrowserStack Automate into Jenkins. It shows summary of the build, and a grid of all the sessions of that build. The plugin helps you to debug faster by highlighting failed tests and linking tests to the Automate dashboard.

Enabling reporting is a simple process and doesn’t require any code change:

	JenkinsUI
 
	JenkinsFile

Follow the below steps: 

## Step 1:

Click on Add post-build action dropdown in Post-build Actions section.

![image](https://user-images.githubusercontent.com/11056300/157078916-8c0b1f4e-c655-4d96-af1e-0a8537c99b2e.png)


## Step 2:

Select BrowserStack Test Report from the dropdown and Click on Save.

![image](https://user-images.githubusercontent.com/11056300/157079064-f5580380-19fe-4b32-8d48-d93abd4143ff.png)


With this integration, you can now view the results of your Selenium Webdriver tests within Jenkins.You can know the summary of a build:
You can view the list of session of a build by clicking on View Full BrowserStack Report or by clicking on BrowserStack Test Report link in the sidebar.
