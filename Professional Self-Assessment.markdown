# PROFESSIONAL SELF-ASSESSMENT

Professionally, I am completing my BS in CS at SNHU and hope to get into software engineering. I have a pretty diverse background. I completed a software engineering internship while working towards this degree. I have also done a great deal of traveling while I have been in school. Currently I have been doing some IT work for a small healthcare company. I think that one of the most important things that I can say about myself is that I love to figure things out and learn new things. Most of my programming experience is with C#, Python, C++, Java. I also have some experience with JavaScript. I have worked with MySQL, MSSQL Server, and MongoDB. As for tools, I am most comfortable with MS Visual Studio and Visual Studio Code, although I have been learning more about, and using Eclipse IDE.  I have also been learning more about using GitHub and BitBucket. I have recently decided that I would like to learn about Azure and/or AWS and I have found some online classes to start learning.

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
