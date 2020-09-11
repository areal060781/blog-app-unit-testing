# A Blogger clone
A blogging and social networking application made with Flask, include an Application Programming Interface and implements different unit testing strategies

### Includes
* Presents an application structure that is appropriate for mediums and large applications.
* Database migrations and data seeder
* Email support
* User authentication system
* User roles and permissions
* Blogging interface
* Profile pages
* Followers
* User comments for blog posts
* RESTful webservices
  * Error handling
  * User authentication (HTTPAuth, JWT)
  * Serializing resources
  * Pagination
  * Tests
* Code coverage reports
* Web application testing
* Web services testing
* End to end testing with **Selenium**


### Requirements
* Python 3.7
* Virtualenv

### Notes
Configure your system so FLASK_APP and FLASK_DEBUG are set by default.

### Installation
Inside the project directory, create the environment, activate it and install the requirements
```sh
python3 -m venv venv
. twittervotes/bin/activate
pip install -r requirements/common.txt
pip install -r requirements/dev.txt
```

Run the migrations
```
flask db upgrade
```

Create the following environment variables:
SECRET_KEY, MAL_USERNAME, MAIL_PASSWORD

Run the application as usual
```sh
(venv) $ flask run
```

The unit tests can be executed as follows
```sh
(venv) $ flask test --coverage
```
