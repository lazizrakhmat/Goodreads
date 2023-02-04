# Goodreads
Goodreads Clone

A simple and easy-to-use application that allows users to track, discover and share books they are reading, have read and want to read. This is a clone of the popular book-reviewing website Goodreads.

Features

User authentication and authorization
Add, edit and delete books to reading lists (currently reading, want to read, read)
Search for books by title, author and ISBN
View details about a book, including reviews and ratings from other users
Write and share reviews about books
Follow other users and see their reading activity

Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

Prerequisites

Python 3
Django
PostgreSQL

Installation

1. Clone the repository
   shell
   Copy code
   $ git clone https://github.com/YOUR-USERNAME/Goodreads-Clone.git

2. Create a virtual environment and activate it
   shell
   Copy code
   $ python -m venv myenv
   $ source myenv/bin/activate

3. Install dependencies
   ruby
   Copy code
   $ pip install -r requirements.txt

4. Set up the database
   ruby
   Copy code
   $ createdb goodreads-clone
   $ python manage.py migrate
   
5. Start the development server
   ruby
   Copy code
   $ python manage.py runserver
   
Built With

Django - The web framework used
PostgreSQL - The database used
Bootstrap - The CSS framework used

Contributing

Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests.

License

This project is licensed under the MIT License - see the LICENSE.md file for details.
