## Integrating Jenkins with gitHub

## Jenkins Job Creation

We can create the Jenkins Job by following below steps:

1.	Go to Jenkins dashboard and click on new item.

![image](https://user-images.githubusercontent.com/11056300/157046241-d3872039-8146-44c7-941e-578254741e46.png)

2. Enter project name and select project type from list( Select freeStyle for general project and maven for maven related project)and click on Ok button.

![image](https://user-images.githubusercontent.com/11056300/157046470-b154be38-bfee-4410-98c1-115266a034cb.png)

3. Select github project and enter the gitHub repository url.

![image](https://user-images.githubusercontent.com/11056300/157046642-90669a63-0e47-46e9-9ab5-4e0304e7bba7.png)

4. Choose git under source code management and enter url.

![image](https://user-images.githubusercontent.com/11056300/157046914-3d1e990d-6183-4572-b4e2-551cf2014ad4.png)

5.	Select Browser-Stack as build environment and provide the credentials.

![image](https://user-images.githubusercontent.com/11056300/157047054-8a38208c-ebc3-4456-b511-84527be46f5c.png)

6.	Insert commands under pre steps -command text field.

![image](https://user-images.githubusercontent.com/11056300/157047226-66d083f5-8bd6-4297-a8c4-30ba643f798f.png)

7.	Insert command under Build section.

![image](https://user-images.githubusercontent.com/11056300/157047471-6d52dec4-ace3-4ae4-bdfe-17bd66c7e03c.png)

8.	Add Post Build Actions as shown in the picture and enter required details.

![image](https://user-images.githubusercontent.com/11056300/157047658-0b39253d-8b8c-4179-8d23-b0febb78dfe3.png)

![image](https://user-images.githubusercontent.com/11056300/157047688-37d56bda-ea98-43c7-8629-e0a28fdacb7b.png)

9.	Click on apply & save

The Jenkins Job will be created.
