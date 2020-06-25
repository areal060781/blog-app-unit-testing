# A Social Blogging Application

* User authentication
* User roles

### Requirements
* Python 3.7
* Virtualenv

### Notes
Configure your system so FLASK_APP and FLASK_DEBUG are set by default.

### Installation
```sh
git clone https://github.com/areal060781/social-blog.git
cd social-blog
virtualenv env
pip install -r requirements.txt
flask db upgrade
```

Run the application as usual
```sh
(venv) $ flask run
```