# KatalonStudio-Global Variables and Profile Execution

**Execution Profile**
Execution Profile helps cover multiple and different environments to execute your automation test scripts with ease. 
You can configure the testing environment in terms of data and behaviors through Global variables.

**Create a profile**
Like other test artifacts, you can CRUD the Execution Profile in the Tests Explorer.

![image](https://user-images.githubusercontent.com/11056300/159319764-37540e49-524b-432d-92a5-5a6b7fb5b30c.png)

You need to define a profile's content by adding Global variables As-. Select a profile > click Add. In the New Variable dialog, 
specify details for the variable > click OK.

![image](https://user-images.githubusercontent.com/11056300/159320326-f2dceb5d-eccf-4075-89a2-170c8be61ce8.png)

1.	The variable is added to the profile accordingly, you need to specify Name, Value Type, and Value. 

![image](https://user-images.githubusercontent.com/11056300/159320621-901e99f4-8295-4afd-82bf-a6b460bdc3ca.png)

Set default profile at project level
A default profile is considered as a place to comprise commonly used global variables. Other profiles can either inherit or override the global variables stored in the default one. You may have multiple profiles for executing your tests, for QA, Dev, and UAT profiles. It would be convenient to set a profile as your default one in every execution of a project. Right-click on your desired execution profile and select Set as default Execution Profile.

![image](https://user-images.githubusercontent.com/11056300/159320925-207b2ef1-4a6f-4991-aba7-9612bb3b0222.png)

Use a profile
By default, Katalon Studio uses the default profile for executing tests, as indicated on the screen's top right corner. You can select any available execution profiles in the drop-down menu.
The following section shows you a usage example. There are three profiles based on testing environments: Dev Environment, UAT Environment, and QA Environment.
For test cases or test suites: Select your desired profile on the top right > all Global Variables within your current project automatically uses these values.

![image](https://user-images.githubusercontent.com/11056300/159321200-9c619b20-7bf4-4daa-b7a8-6fc51825c057.png)
