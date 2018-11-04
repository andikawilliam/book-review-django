# Book_Review_Django
Making a book review website using Django for a class assignment
This file serves as an explanation for the website

### Instructions and Requirements
In this project, you’ll build a book review website. Users will be able to register for your website and then log in using their username and password. Once they log in, they will be able to search for books, leave reviews for individual books, and see the reviews made by other people.

***

## Getting Started

In making this website, no special tools/IDE such as Pycharm or Anaconda were used. Instead every configuration was installed 'raw' through the command line (CMD) for both python and django

The specific tools that were used were: <br>
Text-Editor : Notepad++ <br>
Browser     : Google Chrome


## The Website

The book review website is named **Andi's Book**.
<br>
Here we will demonstrate the whole process of starting the website and how it operates.

We start by running the django server.
```
python manage.py runserver
```
And then accesssing the *localhost:8000/reviews*.

We should arrive at **Andi's Book** website homepage which displays recent reviews made by other users.


On the nav-bar we can see a few options :
- **Book List**: This bar will take you to the catalog of books that is already registered registered
- **Login**: This bar allows existing users to login
- **Register**: This bar allows new users to register

On the **Book List** webpage we can see a list of books. Each book has an author and an average number of rating that it has.
By clicking one of the Books, we will arrive at the book detail webpage which shows the details of the book as well as the reviews made by previous users


## Deployment

Add additional notes about how to deploy this on a live system


## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
