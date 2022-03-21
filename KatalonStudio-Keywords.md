# KatalonStudio-Keywords

1.	WebUI Keywords
2.	Mobile Keywords
3.	Windows Keywords
4.	Cucumber Keywords
5.	Utilities Keywords
6.	Web Service Keywords
7.	Common Assertions
8.	Visual based Web Testing Keywords

**1.	WebUI Keywords: ** This Keywords are only used for Web Based UI. All web UI actions we can perform using WebUI Keywords
**2.	Mobile Keywords: ** All mobile related actions we can perform using mobile keywords

# Custom Keywords

In Katalon Studio we can see different types of keywords available to perform different types of action on objects or elements.
It May happen some time we required custom action perform on object or elements and we don’t find suitable action/keywords at that we need to create our own custom keywords and used in our project

 ## Custom Keywords Creation
 
 1.	In Our Project explorer keywords folder is available
 2. Right Click on Keywords folder -> New -> Package

![image](https://user-images.githubusercontent.com/11056300/159283716-ec56df8e-6596-4101-b5f8-5667849f9d06.png)

2.	Enter Package Name and click on OK Button

![image](https://user-images.githubusercontent.com/11056300/159283770-9cf96e4f-c893-4bca-9a0c-2901900eca4c.png)

3.	Right Click on Package Name -> Click On New -> Keywords

![image](https://user-images.githubusercontent.com/11056300/159283903-440f5dcb-d6f0-40c8-808a-fc95c67c2c61.png)

4.	Enter Class Name -> Click on OK button

![image](https://user-images.githubusercontent.com/11056300/159283982-5a88c394-9733-4999-9348-2f70ec196781.png)

Keyword file created with .groovy extension
In that file we need to write required/custom action we can specify keyword using @Keyword annotation

![image](https://user-images.githubusercontent.com/11056300/159311461-f46373d2-0d67-472b-a53f-038720f39cdf.png)

5.	Now we can used this keyword in our test case
6.	Click on Add -> Custom Keyword

![image](https://user-images.githubusercontent.com/11056300/159311578-5fbd5aac-dac6-4285-b32a-57a878076418.png)

7.	Select our newly created custom keyword and Save Testcase execute testcase
