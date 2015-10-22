# _Jordan's Book Barn_

##### _A Drupal site for a fictitious bookstore, 10/16/2015_

### By _**Jordan Johansen**_

## Description

_This is the website for a fake bookstore by the name of Jordan's Book Barn, formerly Jordan's World of Books (And Other Forgotten Relics).  It contains some basic pages (an "About Us" and a "Locations" page) and a "Book Review" custom content type.  It also utilizes a few contrib modules: "Views" for creating a block that displays the top 3 most recent book reviews, Strongarm for tracking changes to various site configuration settings, and a Features module for saving these customizations to modules, as opposed to the database.  There is also a user role for "Reviwer" (username: Reviewer, password: readingrainbow) that allows the user to create, edit, and delete their own Book Reviews._

## Setup

* _Clone the repository from GitHub._

* _On Mac:
Set the MAMP root directory to the project folder.  Navigate to MAMP's phpmyAdmin page and import the database zip file found in sites/database_backup. (bookstore_database.sql.zip)_

* _After selecting the newly imported database, click on the "Privileges" tab and add create a user with these settings:
User Name: pagemaster
host: localhost
Password: readingrainbow_

* _On Windows:
Do the same as above, but through WAMP, or whatever server you're using.

* Open your browser and go to localhost:8888.

* The site administrator account information is:
User Name: admin
Password: readingrainbow_

## Technologies Used

_Drupal.  Contrib Modules Used: Features, Views, Strongarm._

### Legal

Copyright (c) 2015 **_Jordan Johansen_**

This software is licensed under the MIT license.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
