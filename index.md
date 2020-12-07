## Welcome to My Capstone Project 

This ePortfolio has helped me to highlight the skills I have gained through the Computer Science program at Southern New Hampshire University. To be able to go through my past projects and select the ones that highlight and enhance the skills of my choice will help me to start my career. Putting all of thee projects together in a portfolio that is housed in GitHub has also given me more experience and knowledge in the collaborative environment that will help me work with members of my future team. The narratives helped me practice explaining projects in non-technical terms. I was able to pick projects that really highlighted my skills in data structures, algorithms, databases and software design and engineering. Revisiting these projects also helped me to find ways to make my programs more secure.  

I picked three separate projects to include in my portfolio. To highlight my abilities in software design and engendering I picked my mobile app. This project helps to demonstrate my software design abilities. To showcase my skills with data structures and algorithms, I created a program that has three different data structures, each with multiple different algorithms to load and sort information from a spreadsheet. Along with creating my own MySQL database, I also created an SQLite database to store user information in my mobile app. These two programs show my abilities to not only create but interact with different types of databases.   

### Software Design and Engineering:

		This artifact was created in the class Mobile Architecture & Programing during the 20EW4 term. 
	It is an app that works as a portfolio. It creates a user profile, that has user and login 
	information stored in a SQlite database. It opens a few websites the user enters in their profile. 
	It also uses the google maps API, it is also connected to the users LinkedIn profile. It also gives 
	the user the ability to write and load text files, intended to be used as a bio for the user. Also, 
	it lets the user enter events into the calendar already on their phone. 
		I included this item because it showcases a lot of different skills. From design to implementation 
	to refinement I created everything from scratch. Starting with the creation of the database to creating 
	the program to interact with it. This database can create, search, and delete an entry. It also displays 
	a security mindset as it checks all user input and user credentials before it lets the user access the app. 
	It also shows my ability to work with different API’s. I made several improvements to this app. Ranging 
	from general functionality and flow improvements to major security issues. During the enchantments I 
	found a bug where once logged in the user could edit other database entries if the user knew the name 
	entered. This was corrected so that the user can only edit their information. 
		I met all the planned improvements for this project, and I also made some enhancements to 
	additional aspects of the project I found while testing the program mentioned above. There is one thing I 
	have left to do with this project. I found a bug in the program where if a user tries to log in with a 
	deleted profile, the project crashes. I suspect this is caused from the deleteUser() function from the 
	file PDHandler.jave file not functioning properly. I have a temporary fix in place where if that event 
	happens it starts a new activity. Essentially just reloading the same page. This is not ideal, but it 
	keeps the program from crashing. 
		I really enjoyed revisiting this project. This project was about halfway through my degree program. 
	To come back to it now really helped me to realize how much I have improved as a developer. One thing I 
	learned while improving this was to keep the design simple. It started off to complicated, now that I have 
	simplified it, it has improved greatly. My main challenge also came from changing the design. The base code 
	was mainly all already there. However, moving different functions to different pages, things got a lot more 
	complicated then I was anticipating. I overcame this by getting organized. I made a flowchart in a note pad 
	and used that as my reference. This project really helped me to practice and improve my ability to design 
	and plan out a project. 

[Portfolio Mobile App](https://github.com/btoulouse/mobileEPortfolio.git)

### Algorithm and Data Structures:
	This artifact was made up of different lessons, labs and assignments from my Algorithms and Data Structures class. I took several different assignments and combined them into a bigger project. What it does is loads information from a csv file into different data structures which the user can pick. They can pick between a vector, a binary tree, and a hash table. Then depending on the data structure there are different actions they can take. Such as sorting in different ways, searching for a specific item etc. All these actions have a timer that tracks how long each action takes. This is so the user can compare the different data structures and different algorithms against one another. 
	As I have mentioned in previous journals and assignments my goal is to become a back-end developer. And a huge part of that is dealing with data structures and algorithms. That is why I chose this artifact to show my skills in the area. This entire program is made up of data structures and different algorithms that work with them to complete different goals. This artifact was improved by putting these different components together. It is made up from several different assignments and put together so they can be easily compared for efficiency. 
	I did meet all the goals I set out to when I originally selected the enhancement. There is one piece now that I have made the enhancements that I want to improve upon. Right now, the whole program is on one file. I want to figure out how to break these up into different files for each data structure and then have the main function in its own file. I think this would greatly help the organization of project and help the readability greatly. 
	The main issue I faced while working on this enhancement was not having access to the resource files. There was an issue of me unexpectedly losing access to the virtual desktop. I had all the cpp files I needed. But without the resource files I was not able to load any of the information into the data structures or test the program at all. I created the program as best as I could without being able to run it or do any testing. This really made me focus on what I was doing and why I was doing it. Then I went through the program testing it on paper, without really being able to run it. This was a tremendous learning opportunity, it forced me to work and look at the program in a new way. I was able to catch and fix a bunch of bugs so by the time I actually got the resource files I needed, everything worked pretty smoothly. 

[Data Structures and Algorithms](https://github.com/btoulouse/DataBaseandAlg)

### Database: 
	This artifact was originally created in the class DAD-220 Intro to SQL. It was created in the codio environment. It is a messaging database. It includes a few different tables some of which are joined to share information. It includes a person table, a contact table, a message table, and an image table. This was originally created in term 19EW3. I took this database and recreated it onto my local machine.
	I selected this artifact because it displays a verity of skills. It shows a command of essential SQL subsets. Such as DDL (Data Definition Language, which is commands like Create, Alter, and delete. It also shows my ability to use the DML (Data manipulation Language) subset. This uses commands such as insert, update, delete and retrieve data from the database. And finally, it displays skills in DCL (Data Control Language) this involves granting and removing user permissions. 
	I did meet all the objectives I planned to meet with this enhancement. I was able to fully recreate the databased. I do not have any update to my outcome coverage plan. 
	I really enjoyed working on this artifact. It was nice to go back and work with MySQL again, it reinforced what I learned in that course. The main thing I learned working on this was installing and working with the MYSQL Workbench. Through most of my time at SNHU I worked on a remote desktop or through some online environment. I have learned a lot by having to go back to these old projects and install and learn how to work the environments on my local machine. 



# END END END END
Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Software Design and Engineering:
## Algorithm and Data Structures:
### Database:

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/btoulouse/Portfolio/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
