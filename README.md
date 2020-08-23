# Promineo Tech - Back-end Program - MySQL Week 6 - Group Project
## Contributors
* Clair Gustafson
* Zach Beecher 
* Jeff Haupt

## Table of Contents
* [General info](#general-info)
* [Technologies](#technologies)

## General Info
The purpose of this homework assignment was to work as a group to create a menu driven application that utilizes JDBC and utilizes Java to execute CRUD commands on a database.  Initially, we divided things up randomly, but then that started to not necessarily create great workflow.  Clair handled the initial DDL creation, worked on the MoviesDao, and created the entities. Zach developed a rather large database initially, but we ended up having to make changes and are putting the implimentation of that database on hold for now.  Zach handled GenreDao and related menu applications.  Jeff handled RatingsDao and the related menu applications.  Each of us took turns troubleshooting different problems that the code was handling as well as working on cleaning up the menu and some of the Git and GitHub related problems we were having.  

The Java program has three different Packages set up: Daos, Entities, and Application

The Daos Package has the following classes: DBConnection, GenreDao, MovieDao, and RatingsDao

The Entity Package contains the following files: Movie.java, Genre.java, and Rating.java

Finally, the Application package contains: Application and Menu.  Menu is where most of the Methods in this application are written and calls to the Daos and Entities get made.  

We did use external Database storage for our movies database.  

## Screenshots

### Console ouput - running application screenshots

![image](https://user-images.githubusercontent.com/66330433/90988037-97387400-e55d-11ea-90a0-09e7399da7db.png)

![image](https://user-images.githubusercontent.com/66330433/90988058-cd75f380-e55d-11ea-9ba0-1577aa28581b.png)

![image](https://user-images.githubusercontent.com/66330433/90988072-ea122b80-e55d-11ea-9340-3929d68310e3.png)

![image](https://user-images.githubusercontent.com/66330433/90988094-1463e900-e55e-11ea-85c3-d7e251368b96.png)

![image](https://user-images.githubusercontent.com/66330433/90988107-2e9dc700-e55e-11ea-963c-c142c7ef9aa2.png)

![image](https://user-images.githubusercontent.com/66330433/90988115-4c6b2c00-e55e-11ea-8b93-7b5637c932f3.png)


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


