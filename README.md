
You can download the project from here, its working perfectly fine.

This project is created using Microsoft Visual Studio 2010, You can open and run this project on any new versions of visual studio, but for the proper working of the project I'll recommand to use Microsoft Visual Studio 2010. 

**If you are getting database connection error,**

Open the project in Microsoft Visual Studio 2010, on the left side you'll see Sever Explore option.

open server explorer, and click on SchoolDb.mdf, on the right side you'll see Connection String option after that the complete data source link will be there, copy that link and paste it in SqlConnection Con(inside "" after @ symbol) wherever you'll see inside the project.

SqlConnection Con = new SqlConnection(@"Data Source=.\SQLEXPRESS;AttachDbFilename=C:\Users\ASUS\onedrive\documents\visual studio 2010\Projects\SchoolManagementSystem\SchoolManagementSystem\SchoolDb.mdf;Integrated Security=True;Connect Timeout=30;User Instance=True");
