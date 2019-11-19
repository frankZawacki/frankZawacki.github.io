## PROFESSIONAL SELF-ASSESSMENT
I learned a great deal and was exposed to a wide variety of different technologies throughout my computer science journey. I learned about working together with a team on a collaboration project. Everyone on the team contributing to the same project by using Atlassian git tools, for source and version control. I learned about software testing and looking at things through the eyes of a tester, trying find different ways to break or crash the software. I learned about the SDLC and communicating with stakeholders and agile development methodologies. My experience with data structures and algorithms included linked lists, binary search trees, hash tables, merge sort, quick sort, and more. I explored different databases including traditional SQL databases and NoSQL databases including MongoDB.
Originally, I was planning on using 3 distinct artifacts for this project, but later realized that it might be more effective and efficient if I was able to demonstrate a range of skills and fulfill the requirements of the assignment using one artifact. This is what I decided to do. The original artifact I started with was from CS-340, it was an API that connected to an instance of MongoDB. It was written in Python using the Bottle microframework. The final artifact substantially covered all three categories: 
  1. Software Design and Engineering; 
  2. Data Structures and Algorithms; 
  3. Databases.
For the first category, software design and engineering, I adapted the original project to a different framework, Flask. I also changed it from a single file to a modular application. The modular design allows for better code reusability and better scalability. I added security for the application by adding a login and logout with password hashing.
There are several demonstrations of the second category of data structures and algorithms. One example is that the passwords are hashed. Another example would be that the data being passed to and from the database is being parsed in and out of JSON format.
The third category, databases, was the original reason I used this artifact. I added a user collection that is used for the sign in process and includes a ‘user_id’, email, password, and first and last name. New users can be added using the registration page. The original application’s functionality is maintained using the stock collection. There is also an interface. I also added a subscribe collection, this is basically a junction table (collection). This collection includes the ‘user_id’ and the ticker, but on the subscribe page it uses the ticker as a foreign key and looks up the stock and lists the other information for that stock connected to the ‘user_id’. I also learned about using postman to test things that uses http requests. I also set up a MongoDB cloud database in atlas and connected the application to that instead of a local instance of MongoDB.
## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/frankZawacki/frankZawacki.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/frankZawacki/frankZawacki.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
