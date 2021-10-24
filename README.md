# TimeManagementAppTask2
#### ============TABLE OF CONTENTS===============

1. Feedback and implementation from task 1
2. Overview.
3. Features of the project.
4. Development dependencies.
5. Technology + software required.
6. Running of the project.
7. Contributors and sources.

#### =================FEEDBACK AND IMPLEMENTATION FROM TASK 1========================
In task 1 according to the feedback  had recieved there was a bit of an issue with regards to the fact that I did not include any LINQ functionalities. To rectify that problem all I did was include the LINQ within my tuple list, in which all of the user data/ modules are stored. The LINQ I added was in the form of the "elemenetAt" function for the tuple that essentially fetches all of the user data and stores it within the tuple list. This is the only feedback I had recieved with regards to my project.


#### =================OVERVIEW===================
This is an interactive time management application that is used to solve the problem of students not being able to efficiently manage their time correctly, so that they are able to plan their schedules ahead and submit their tasks on time. This application provides a seamless way to allow students to store the amount of hours they spend on a module and how many hours would remain after the hours they have spent prior, this provides a gauge on how much time you actually need in order to finish that task and submit it on time. The application makes use of user input which then takes the users input to provided a calculated measure of how many hours remain of their self study time for the week. All of the data the user puts into the application will essentially get stored internally within a database so that they will always have that information and be able to update their information if they need to.

The motivation behind this application was to create something students can use, considering I am a student myself that will give me quick calculated answers of how much time I actually have left in order to submit tasks for certain modules. As a student time is something that is not on our side, so with this appliaction I wanted to make something fairly quick and easy to use to provide better time management for students. A little something to make life easier.

#### ============FEATURES OF THE PROJECT==============
This project includes the following:

1. A login page, provided the user has already registered, if not they will be redirected to a registration page.
2. Window that requests the user to enter their module code, name, number of credits, class hours per week, number of weeks and the start date for the first week.(This is where the user can add multiple modules if they have more than one module). All of this stored will be stored in the database and displayed in the data grid.
3. Multi-threading to handle the database queries/ processes.
4. Window that requests the user to enter the number of hours they have spent of a specific module.
5. Custom library that calculates the hours of self study for each module the user entered and the number of hours remain after they have entered how many hours they spent on a module.(This uses LINQ)
6. User input validation to make sure the correct type of data is entered.
7. Displaying of the students modules and the hours that remain of self study..

#### ============DEVELOPMENT DEPENDENCIES=============
1. Microsoft.NETCore.App
2. ADO.NET connected layer.
3. Visual studio 2019.
4. Visual studio windows presentation framework.
5. Class library (WPF.NET Framework).
6. SQL server management studio 2019.

#### ===========TECHNOLOGY + SOFTWARE REQUIRED==========
1. A laptop that supports windows10 and microsoft with atleast 2GB of RAM space.
2. Not supported on: 
   Linux 
   MS-DOS (IBM PC DOS) 
   Windows 3.1 
   Windows NT 3.51 
   Windows 9x 
   Windows NT 4.0.
3. Microsoft visual studio 2019 version 16.9.4.
4. Microsoft.NET framework version 4.8.04084..
5. Windows presentation framework.
6. Class library(WPF.NET Framework).
7. SQL server management studio 2019.

#### ============RUNNING OF THE PROJECT===================
1. Download the zipped folder(TimeManagementApp.zip)
2.  In the file explorer unzip the zipped file by extracting it.
3.  Open the unzipped file.
4.  Click the TimeManagementApp file to open it.
5.  Open the folder that says TimeManagementApp.Sln.
6.  Visual studio 2019 will open now.
7.  Once the project is open in visual studio go to server explorer on the left hand side, under data connections click on the data connection called laptop-  d2phaf11.userDeatails to open the connection. There should be a green plug next to the connection to illustrate it is connected.
8.  Go to the MainWindow.xaml.cs and click the green button called start on the visual studio toolbar to run the program.
9.  The programme starts with a login page the redirect you to window 1 it will also ask you to input data.

#### =============CONTRIBUTORS + SOURCES===================
1. Reneilwe-Kutlwano Motlhabi.
2. https://www.geeksforgeeks.org/.
3. Troelsen, A. and Japikse, P. 2017. Pro C# 7 with .NET and .NET Core. 8th ed. Minnesota and Ohio: Andrew and Philip.
4. https://www.tutorialsteacher.com/csharp/csharp-tuple.
