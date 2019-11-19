## DATA STRUCTURES AND ALGORITHMS

The original artifact the I am working with is from CS-340. It was an API built in Python, using Bottle microservice framework and MongoDB as the database. The project that I am using as a starting point is a single file Python API that implements CRUD on a MongoDB database. It is a simple application and does what it intends on a very basic level.

I selected this item for this second category because I was already using it for the other two categories, and it seemed to make more sense to continue with the same artifact. I was able to show my abilities with algorithms and data structures with this project in a few different ways. For example, the data from the application interface is parsed into JSON format to insert it into the database. Then the application retrieves the data from MongoDB, it receives the data in JSON format. That data is then parsed into the format for display. Another example is the login process including the hashing of the password.

I had no previous experience using Flask. I had read about it in passing and got the idea to use it here while looking into Bottle and trying look for things to add to this same project, but in reference to the database prompt. I realized that other frameworks were much more commonly used and had greater functionality and it might be interesting to learn more about them and it that I could adapt the original Bottle application to Flask. I decided that this was a good direction to go. I watched a lot of videos about Flask and read a lot of the documentation for Flask as well as documentation for other libraries that I used in the project.

I was originally planning on going in an entirely different direction with the final project and all the milestones. However, after realizing that I could meet all the requirements with this one project, I decided that would be the new direction I would take.

I learned a great deal while working on this project. I learned about the flask framework, and I learned about a lot of the libraries that are available to use with it. I learned how to use documentation to learn about a language, library, or extension. I learned about using a virtual environment in python. There were some challenges that I faced in this process. One challenge was that I was having trouble with the stocks database. It was not displaying correctly, I figured out that this had to do with the fact that there were a lot of fields in the database for a stock, but I was only using about 6 of them. I resolved this issue by using ‘db.DynamicDocument’ in the model instead of ‘db.Document’. 


[Click this link to view the code for the project.](https://github.com/frankZawacki/finalProject)

