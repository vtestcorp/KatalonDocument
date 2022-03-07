# BrowserStack-Environment Variables

## UI allows user to navigate to Privacy Policy by clicking on Privacy Policy link

The BrowserStack Jenkins plugin sets the following environment variables:

BROWSERSTACK_USERNAME

BROWSERSTACK_ACCESS_KEY

BROWSERSTACK_BUILD_NAME

BROWSERSTACK_LOCAL

BROWSERSTACK_LOCAL_IDENTIFIER

Use these environment variables to set the capabilities in your tests. For example:

	Java
	Node.js
	C#
	PHP
	Python
	Ruby
	Perl

String username = System.getenv("BROWSERSTACK_USERNAME");

String accessKey = System.getenv("BROWSERSTACK_ACCESS_KEY");

String buildName = System.getenv("BROWSERSTACK_BUILD_NAME");

String browserstackLocal = System.getenv("BROWSERSTACK_LOCAL");

String browserstackLocalIdentifier = System.getenv("BROWSERSTACK_LOCAL_IDENTIFIER");

DesiredCapabilities capabilities = new DesiredCapabilities();

capabilities.setCapability("os", "Windows");

capabilities.setCapability("os_version", "10");

capabilities.setCapability("browser", "chrome");

capabilities.setCapability("browser_version", "latest");

capabilities.setCapability("name", "BStack-[Java] Sample Test"); // test buildName

capabilities.setCapability("build", buildName); // CI/CD job name using BROWSERSTACK_BUILD_NAME env variable

capabilities.setCapability("browserstack.local", browserstackLocal);

capabilities.setCapability("browserstack.localIdentifier", browserstackLocalIdentifier);

driver = new RemoteWebDriver(new URL("https://" + username + ":" + accessKey + "@hub.browserstack.com/wd/hub"), capabilities);

Note:

You must pass browserstack.local and browserstack.localIdentifier capabilities to test on your local development servers.
