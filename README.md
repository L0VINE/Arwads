## Description
This is a web application that allows different developers to post their projects and peers can review the same by grading the projects in terms of userbility, design and content.

### User Stories
These are the behaviours/features that the application implements for use by a user.

Users would like to:

* View all projects submitted by any user.
* Click on links to visit a live site.
* Search for users.
* Must be signed up to vote
* See averages for the three grading criterias
* Grade Projects.

### Admin Abilities
These are the behaviours/features that the application implements for use by the admin.

### Admin should:

* Sign in to the application
* Add, Edit and Delete projects
* Delete projects
* Manage the application.


## SetUp / Installation Requirements

### Prerequisites

* python3.8
* pip
* virtualenv
* Requirements.txt
* Cloning
In your terminal:

  * $ git clone https://github.com/Arwads
  * $ cd Arwads

## Running the Application
### Creating the virtual environment

  * $ python3.8
   -m venv --without-pip virtual
  * $ source virtual/bin/activate
  * $ curl https://bootstrap.pypa.io/get-pip.py | python
## Installing Django and other Modules

  $ see Requirements.txt
## To run the application, in your terminal:

  $ python3.8 manage.py runserver

## Testing the Application

To run the tests for the class files:

  $ python3.8 manage.py test Awwards

## Technologies Used

* Python3.8
* Django framework and postgresql database


## License
Copyright (c) 2021 LOVINE 

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sub-license, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.