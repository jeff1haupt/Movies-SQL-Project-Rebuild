# Promineo Tech - Back-end Program - MySQL Week 6 - Group Project
## Contributors
* Clair Gustafson
* Zach Beecher 
* Jeff Haupt

## Table of Contents
* [General info](#general-info)
* [Technologies](#technologies)

## General Info
The purpose of this homework assignment is to create a menu driven application that utilizes JDBC and utilizes Java to execute CRUD commands on a database.  To start the project I created a database with one table, run_training.  Run_training has four columns, an id, run_date, run_distance, and total_time_minutes. 

The Java program has five classes: Application, Menu, RunDao, DBConnection, and Runs.

* Applications is the class containing the "main" method and is rather simple as it creates a new instance of the Menu class and then runs the .start() method on the Menu class. 
* Menu creates the menu using the printMenu() method. Depending on the users selection a variety of methods can be run at this point. The first is the displayRuns() method.  The displayRuns() method connects to the RunDao to display the entire table in run_training. The displayRun() method requires the user to enter which record they would like to see and then only one record is returned. The addRun() method allows the user to enter the date of their run, the distance of the run, and the time of the run.  This data is then inserted into the database.  Finally, the deleteRun() method deletes a user-specified row in the table.  
* RunDao handles the Queries that come through the Menu methods and returns or prints the results depending on the method selected
* DBConnection handles all the initial connection between JDBC and the database. 
* Runs class is used to create instances of a record in the database
## Screenshots

### Console ouput - running application screenshots


### Application.java code 

![image](https://user-images.githubusercontent.com/66330433/90987699-efba4200-e55a-11ea-83c4-dff0fac12199.png)

### Menu.java code

![image](https://user-images.githubusercontent.com/66330433/90987716-111b2e00-e55b-11ea-8737-bf9c2b9ee6c3.png)

![image](https://user-images.githubusercontent.com/66330433/90987743-30b25680-e55b-11ea-804f-814f72901f0c.png)

![image](https://user-images.githubusercontent.com/66330433/90987755-50497f00-e55b-11ea-97b4-c233bb60e6f5.png)

![image](https://user-images.githubusercontent.com/66330433/90987766-69eac680-e55b-11ea-8afb-9fb3bbcf06a8.png)

![image](https://user-images.githubusercontent.com/66330433/90987783-7ff88700-e55b-11ea-9dfc-4a900ac14d61.png)

![image](https://user-images.githubusercontent.com/66330433/90987792-97377480-e55b-11ea-8f1f-d1045b6c196a.png)

![image](https://user-images.githubusercontent.com/66330433/90987800-ad453500-e55b-11ea-8bb9-60dab892072d.png)

![image](https://user-images.githubusercontent.com/66330433/90987818-c51cb900-e55b-11ea-8183-79618c33f51c.png)

![image](https://user-images.githubusercontent.com/66330433/90987824-d8c81f80-e55b-11ea-8e80-a2e1680f9900.png)

![image](https://user-images.githubusercontent.com/66330433/90987831-f0070d00-e55b-11ea-8e15-824de9d84ae4.png)

### Entities - Movie.java 

![image](https://user-images.githubusercontent.com/66330433/90987880-6ad02800-e55c-11ea-9a69-5f828f93ffb9.png)

![image](https://user-images.githubusercontent.com/66330433/90987887-7b809e00-e55c-11ea-8c70-7c37e2a896ce.png)

![image](https://user-images.githubusercontent.com/66330433/90987896-8affe700-e55c-11ea-8735-0dc28bb7ac78.png)

### Entities - Genre.java

![image](https://user-images.githubusercontent.com/66330433/90987907-a1a63e00-e55c-11ea-90fe-58c5aa0dbebd.png)

### Entities - Ratings.java

![image](https://user-images.githubusercontent.com/66330433/90987915-b5ea3b00-e55c-11ea-84ec-684358bb1408.png)

### Dao - MoviesDao.java

![image](https://user-images.githubusercontent.com/66330433/90987950-02357b00-e55d-11ea-8b1e-17c8a15a546d.png)

![image](https://user-images.githubusercontent.com/66330433/90987966-18433b80-e55d-11ea-97f3-e118ed7f4750.png)

![image](https://user-images.githubusercontent.com/66330433/90987980-31e48300-e55d-11ea-91b3-8ba364fe4389.png)

## Technologies
* mySQL 8
* Java 12
* Eclipse IDE
* dBeaver 7
* phpmyadmin 
* JDBC
* Git and GitHub


