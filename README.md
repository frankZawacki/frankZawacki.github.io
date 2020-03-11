# PROFESSIONAL SELF-ASSESSMENT

I am completing my BS in CS at SNHU and hope to get into software engineering. I have a pretty diverse background. I completed a software engineering internship while working towards this degree. I have also done a great deal of traveling while I have been in school. Currently I have been doing some IT work for a small healthcare company. I think that one of the most important things that I can say about myself is that I love to figure things out and learn new things. Most of my programming experience is with C#, Python, C++, Java. I also have some experience with JavaScript. I have worked with MySQL, MSSQL Server, and MongoDB. The tools that I have experience with include, MS Visual Studio, Visual Studio Code, and Eclipse IDE.  I also have experience using GitHub and BitBucket. I have recently decided that I would like to learn about Azure and/or AWS.

I learned a great deal and was exposed to a wide variety of different technologies throughout my computer science journey. I learned about working together with a team on a collaboration project. Everyone on the team contributing to the same project by using Atlassian git tools, for source and version control. I learned about software testing and looking at things through the eyes of a tester, trying find different ways to break or crash the software. I learned about the SDLC and communicating with stakeholders and agile development methodologies. My experience with data structures and algorithms included linked lists, binary search trees, hash tables, merge sort, quick sort, and more. I explored different databases including traditional SQL databases and NoSQL databases including MongoDB. I explored ways to increase security in applications such as: using a sessions and login and logout.

Originally, I was planning on using 3 distinct artifacts for this project, but later realized that it might be more effective and efficient if I was able to demonstrate a range of skills and fulfill the requirements of the assignment using one artifact. This is what I decided to do. The original artifact I started with was from CS-340, it was an API that connected to an instance of MongoDB. It was written in Python using the Bottle microframework. The final artifact substantially covered all three categories: 
  1. Software Design and Engineering; 
  2. Data Structures and Algorithms; 
  3. Databases.
  
For the first category, software design and engineering, I adapted the original project to a different framework, Flask. I also changed it from a single file to a modular application. The modular design allows for better code reusability and better scalability. I added security for the application by adding a login and logout with password hashing.

There are several demonstrations of the second category of data structures and algorithms. One example is that the passwords are hashed. Another example would be that the data being passed to and from the database is being parsed in and out of JSON format.

The third category, databases, was the original reason I used this artifact. I added a user collection that is used for the sign in process and includes a ‘user_id’, email, password, and first and last name. New users can be added using the registration page. The original application’s functionality is maintained using the stock collection. There is also an interface. I also added a subscribe collection, this is basically a junction table (collection). This collection includes the ‘user_id’ and the ticker, but on the subscribe page it uses the ticker as a foreign key and looks up the stock and lists the other information for that stock connected to the ‘user_id’. I also learned about using postman to test things that uses http requests. I also set up a MongoDB cloud database in atlas and connected the application to that instead of a local instance of MongoDB.



(Picture of my daughter, wife, and myself.)
![Image](family1.jpg)



## SOFTWARE DESIGN AND ENGINEERING

The original artifact the I am working with is from CS-340. It was an API built in Python, using Bottle microservice framework and MongoDB as the database. The project that I am using as a starting point is a single file Python API that implements CRUD on a MongoDB database. It is a simple application and does what it intends on a very basic level.

This first category is to show my abilities in software design and engineering. I accomplished this by adapting the original application to a different framework, from bottle (the original framework, to flask, the new framework). I also made the application modular; the original application was a single file. I also included an html interface for the application. I also added security to the application by creating a login and using sessions.

I had no previous experience using Flask. I had read about it in passing and got the idea to use it here while looking into Bottle and trying look for things to add to this same project, but in reference to the database prompt. I realized that other frameworks were much more commonly used and had greater functionality and it might be interesting to learn more about them and it that I could adapt the original Bottle application to Flask. I decided that this was a good direction to go. I watched a lot of videos about Flask and read a lot of the documentation for Flask as well as documentation for other libraries that I used in the project.

I was originally planning on going in an entirely different direction with the final project and all the milestones. However, after realizing that I could meet all the requirements with this one project, I decided that would be the new direction I would take. 

[Click this link to see the code for this project.](https://github.com/frankZawacki/finalProject)



## DATA STRUCTURES AND ALGORITHMS


I selected this item for this second category because I was already using it for the other two categories, and it seemed to make more sense to continue with the same artifact. I was able to show my abilities with algorithms and data structures with this project in a few different ways. For example, the data from the application interface is parsed into JSON format to insert it into the database. Then the application retrieves the data from MongoDB, it receives the data in JSON format. That data is then parsed into the format for display. Another example is the login process including the hashing of the password.

I had no previous experience using Flask. I had read about it in passing and got the idea to use it here while looking into Bottle and trying look for things to add to this same project, but in reference to the database prompt. I realized that other frameworks were much more commonly used and had greater functionality and it might be interesting to learn more about them and it that I could adapt the original Bottle application to Flask. I decided that this was a good direction to go. I watched a lot of videos about Flask and read a lot of the documentation for Flask as well as documentation for other libraries that I used in the project.

I was originally planning on going in an entirely different direction with the final project and all the milestones. However, after realizing that I could meet all the requirements with this one project, I decided that would be the new direction I would take.

I learned a great deal while working on this project. I learned about the flask framework, and I learned about a lot of the libraries that are available to use with it. I learned how to use documentation to learn about a language, library, or extension. I learned about using a virtual environment in python. There were some challenges that I faced in this process. One challenge was that I was having trouble with the stocks database. It was not displaying correctly, I figured out that this had to do with the fact that there were a lot of fields in the database for a stock, but I was only using about 6 of them. I resolved this issue by using ‘db.DynamicDocument’ in the model instead of ‘db.Document’. 


[Click this link to view the code for the project.](https://github.com/frankZawacki/finalProject)



## DATABASES


I originally planned on using this project for this third category, however, I did not expect to end up using it for all the categories. I chose it for this category because it is one of the few projects that included databases. I used this because I wanted to learn more about MongoDB, and NoSQL databases in general. I added a user collection that is used for the sign in process and includes a ‘user_id’, email, password, and first and last name. New users can be added using the registration page. The original application’s functionality is maintained using the stock collection. There is also an interface. An aggregate collection or junction collection (table) is also added, called subscribe. This collection includes the ‘user_id’ and the ticker, but on the subscribe page it uses the ticker as a foreign key and looks up the stock and lists the other information for that stock. I also learned about using postman to test things that uses http requests. I also set up a MongoDB cloud database in atlas, and connected the application to that instead of a local instance of MongoDB.

I had no previous experience using Flask. I had read about it in passing and got the idea to use it here while looking into Bottle and trying look for things to add to this same project, but in reference to the database prompt. I realized that other frameworks were much more commonly used and had greater functionality and it might be interesting to learn more about them and it that I could adapt the original Bottle application to Flask. I decided that this was a good direction to go. I watched a lot of videos about Flask and read a lot of the documentation for Flask as well as documentation for other libraries that I used in the project.

I was originally planning on going in an entirely different direction with the final project and all the milestones. I was planning on using separate projects for each of the requirements. However, I realized that I could demonstrate each of the different skills much more effectively and efficiently using just one project. Upon realizing this I decided that would be the new direction I would take.

I learned a great deal while working on this project. I learned about the flask framework, and I learned about a lot of the libraries that are available to use with it. I learned how to use documentation to learn about a language, library, or extension. I learned about using a virtual environment in python. There were some challenges that I faced in this process. One challenge was that I was having trouble with the stocks database. It was not displaying correctly, I figured out that this had to do with the fact that there were a lot of fields in the database for a stock, but I was only using about 6 of them. I resolved this issue by using ‘db.DynamicDocument’ in the model instead of ‘db.Document’. Another issue is that the ‘add’ button from the stocks page does not seem to be working correctly. This button should add a stock to the list that displays on the subscribe page.


[Click this link to see the code for this project.](https://github.com/frankZawacki/finalProject)


[Click this link to watch the code review.](https://youtu.be/Lhxd6PvEmTA)

### Following are screenshots of the project running, using a browser and Postman


![Image](\images\screenshots\Screenshot1.png)

![Image](\images\screenshots\Screenshot2.png)

![Image](\images\screenshots\Screenshot3.png)

![Image](\images\screenshots\Screenshot4.png)

![Image](\images\screenshots\Screenshot5.png)

![Image](\images\screenshots\Screenshot6.png)

![Image](\images\screenshots\Screenshot7.png)

![Image](\images\screenshots\Screenshot8.png)

![Image](\images\screenshots\Screenshot9.png)

![Image](\images\screenshots\Screenshot10.png)

![Image](\images\screenshots\Screenshot11.png)

![Image](\images\screenshots\Screenshot12.png)

![Image](\images\screenshots\Screenshot13.png)

![Image](\images\screenshots\Screenshot14.png)

![Image](\images\screenshots\Screenshot15.png)

![Image](\images\screenshots\Screenshot16.png)

![Image](\images\screenshots\Screenshot17.png)

