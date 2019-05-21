# erasmus-sds
This project consisted in building a Web Application that would allow Erasmus students to fill the Learning Agreement easily. 
They'll be able to insert information on their own or choose from pre-programed one (which is the case of the faculties and courses from Politechnika Poznanska).
We used an MVC (Model-View-Controller) pattern with C# (.net core 2.2), HTML, CSS, and SQLite as our database (where we store all the information regarding the courses, faculties and learning agreements).
All this information can be found within the project.

## Roles and responsabilities
- William (Product Owner) is responsible for:
  - Detailed description of what the Product Backlog will be 
  - Ordering the Product Backlog items
  - Ensuring every member of the Development Team understands the items in the Product Backlog
  - Ensuring that the Product Backlog is visible, transparent and clear to every member
  
- Ânia Morgadinho (Scrum Master/Development Team) is responsible for:
  - Promoting and supporting Scrum 
  - Enable communication through all Team Members
  - Organize and schedule meetings (Sprint Planings, Weekly Scrum, Sprint Review and Sprint Retrospective)
  - Facilitating Scrum events as requested or needed
  - Ensure that the Product Owner knows how to arrange the Produt Backlog to maximize value
  - Implementing the functionalities presented in the Sprint Backlog
  - Provide a potentially releasable Increment of "Done" at the end of each Sprint
  - Testing the application

- Zeynep Endes (Development Team) is responsible for:
  - Implementing the functionalities presented in the Sprint Backlog
  - Provide a potentially releasable Increment of "Done" at the end of each Sprint
  - Testing the application
  
- Yakup Gokyildiz (Development Team) is responsible for:
  - Implementing the functionalities presented in the Sprint Backlog
  - Provide a potentially releasable Increment of "Done" at the end of each Sprint 
  - Testing the application

## Project Strategy 
Our strategy to this project consists in an iterative and incremental approach, which means that for each Sprint we would define the Sprint goal, the strategies to achieve those goals and try to deliever a "Done" product" that ensures that a potentially useful version of a working product is always available.

## Communication Stratagies
Our Scrum Team will be using different strategies of comunication:
  - Whatsapp as a frequent way of comunication among the Team Members to share and discuss ideas and expose doubts and difficulties concerning the evolution of the project.
  - Meetings (in here it's included the Sprint Planing, a weekly meeting to check on the progress and discuss what should be done next, the Srint Retrospective and the Sprint Review) as a way to discuss what should be done, what can be improved, what was previously done, to check the improvement of the solution as a whole and also to check on the different items that lead to the final solution
  - GitHub as a way to ensure that every member has access to the different stages of the project

## Installation Manual
In order to run our project one requirement needs to be fulfilled:
  - The user must have the version 2.2 of .Net Core installed (if that's not your case please install it through this link: https://dotnet.microsoft.com/download/dotnet-core/2.2)

After this is installed on your machine, you can simply go to our masters Repository and proceed to download the SDS.zip file. After this you will have to extract the content of the zip file.

Once you have completed the previous step you have two different ways you can use to run the application:
  1. User has Visual Studio 2019 installed in his/hers machine
    If this is your case, you only need to open the SDS.sln file and then run SDS using Visual Studio.
    
  2. User doesn't have Visual Studio 2019 installed in his/hers machine
    If this is your case, you can use the terminal to run the application. 
    You need to open the terminal/command line and move to the directory of the project (SDS/SDS/). 
    Once you're in SDS/SDS you need to execute "dotnet run" command. After this step the server will be running and can be access through the use of a url.
    Open a web browser and paste one of the following urls: "https://localhost:5000/" or "https://localhost:5001/" to access the server.
    
If you followed all the previous steps, you should now be in our Welcome page! 
Here you should click on "Start your Learning Agreement" in order to start creating you Learning Agreement.
    

## Development Work done so far (per each member of the Development Team)
- Ânia Morgadinho
  - Creating the database (containing two tables, one for the courses and another for the faculties)
  - Filling the database with the information about the courses and faculties belonging to Politechnika Poznanska
  - Creating the MVC pattern 
  - Creating various Views containing the forms used to receive the information that the user inputs into the system 
  - Creating the mechaninsm used by the user to access all the information regarding the courses and faculties
  - Integrating the HTML version of the Learning Agreement in the MVC pattern (which means filling the fiels with the information provided by the user)

- Yakup Gokyildiz
  - Transpose the Learning Agreement document in to a digital format that uses HTML so that this document can be integrated in the remaining project

- Zeynep Endes
  - Creating of the design of the Application

