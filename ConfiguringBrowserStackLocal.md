# BrowserStack-Local Configuration

## UI allows user to reset password with small screen size

BrowserStack Local Testing allows you to test web applications hosted on private, development, and internal servers. With the Local testing binary, you can create a secure, private connection between the BrowserStack Selenium Grid and your internal servers. 

The BrowserStack Jenkins plugin is responsible for:

	Downloading the BrowserStack Local binary for every platform that the build job is running on
   
	Setting up and tearing down the secure tunnel.
   
Note: BrowserStack Local can only be configured per job and not via global configuration.

To enable BrowserStack Local follow these steps:

	JenkinsUI
   
	JenkinsFile
   
Under the Build Environment section check the box next to BrowserStack Local.

![image](https://user-images.githubusercontent.com/11056300/157077081-1a6e3435-7fed-4b93-b54f-b450e12c49ab.png)

Notes:

1.	If you are using an externally downloaded binary, you can enter its location at BrowserStack Local Path. If left empty, the plugin will automatically download the binary (recommended). This is recommended especially if you are using Jenkins in master-slave configurations, since the plugin will download the appropriate binary for the build agent OS.

2.	Use BrowserStack Local Options to set any additional configuration options when running the binary (See the full list of local testing options)
Once you’ve integrated BrowserStack Local through the Jenkins plugin, you can run your Selenium tests on websites hosted on private, development, and internal servers safely and securely. Refer to the sample code in the below section.
