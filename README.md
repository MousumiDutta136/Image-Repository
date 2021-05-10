# Image-Repository
Shopify Backend Developer Intern Challenge – Fall 2021

My Project is based on building an Image Repository. I have used ASP.Net Core MVC application to implement the challenge.
Link for the challenge in Github is https://github.com/MousumiDutta136/Image-Repository.git

How to use the application:
•	Please open the project in Visual studio (I have used Visual Studio 2019 version). Open SQL server and connect to it.  My Database name is “ImageRepos” and 
the table used to store images is “Images”.
•	While someone wants to run the application they need to change the server name as below:
Go to appsettings.Development.json and change the server name to own server name. 
After opening the SQL server management studio there server name could be found out while connecting to the server. 
•	In Package Manager Console two commands have to be written for creating the migration database. The commands are ‘Add-Migration migration name’ and 
‘Update-Database’.
•	Last step is to execute the application.
•	In the web browser it would find a menu as Image Repository. Click on this button to perform required operation. 

Test Casses
In this project users can perform Add/Delete operation.
Test1: Add new image to the repository
Step 1: Execute the application with the help of below steps.

Step 2: Click on the ‘Image Repository’.
 
Step 3: Add new image to the repository. 

Step 4: Give the title and choose the file. Press Create button.

Step 5. Go to program and database to check the image to be uploaded.


Test2: Delete new image from the repository.
Step 1: Click on the ‘Delete’.

In program, go to the folder Image under wwwroot and check. The image has been deleted. 


