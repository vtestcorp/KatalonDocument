# KatalonStudio-Checkpoints

Checkpoint is the snapshot of test data taken at a specific time. A checkpoint is used to verify whether the current state of the data source is different from its previous taken state. An example where Checkpoints proves to be helpful are database validation cases where value usually changes constantly.
Create a Checkpoint from Test Data
1.	Select File > New > Checkpoint from the main menu. The New Checkpoint dialog will be displayed. 
2. Enter the name for your checkpoint and select Test Data as Data Type. Click Next.

![image](https://user-images.githubusercontent.com/11056300/159322450-ca6062c1-08e8-4c4d-b1c4-030cf2f013c0.png)

3.	In the next dialog, click Browse to select from the list of existing Data Files defined in Katalon Studio. Click Finish.

![image](https://user-images.githubusercontent.com/11056300/159322834-79cdd320-dd30-4f12-a3ac-525fe045677e.png)

4.	The state of the selected data source will be captured and displayed in preview section below. The checkboxes for the data cells indicate whether they will be used 
5.	when verifying against other states of this data source later.

![image](https://user-images.githubusercontent.com/11056300/159323869-e1f72c2f-f1fb-46bf-8c16-3f6645889b8c.png)

6.	Save the Checkpoint when you're done. The data snapshot taken here can be used to compare with the state of the data source later. Refer to [Common] Verify Checkpoint keyword for more details.

**Create an Excel Checkpoint**

1.	Select File > New > Checkpoint from the main menu. The New Checkpoint dialog will be displayed. Enter the name for your checkpoint and select Excel File as Data Type. Click Next.

![image](https://user-images.githubusercontent.com/11056300/159324548-d91917fe-22ce-4a9e-b307-3e43ba025725.png)

2.	In the next dialog, click Browse to select the excel file. Specify the excel sheet to be loaded as needed then click Finish.

![image](https://user-images.githubusercontent.com/11056300/159324819-366efb40-afc7-49c8-980e-bd6fee3a841e.png)

3.	The state of the selected data source will be captured and displayed in preview section below. The checkboxes for the data cells indicate whether they will be used when verifying against other states of this data source later.

![image](https://user-images.githubusercontent.com/11056300/159325188-c61e023c-c61d-4df5-8898-ce6b577ddb6b.png)

4.	Save the Checkpoint when you're done. The data snapshot taken here can be used to compare with the state of the data source later. Refer to [Common] Verify Checkpoint keyword for more details.
