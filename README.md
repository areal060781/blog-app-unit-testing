# A clon of Blogger

* User authentication
* User roles
* User profiles
* Blog posts

### Requirements
* Python 3.7
* Virtualenv

### Notes
Configure your system so FLASK_APP and FLASK_DEBUG are set by default.

### Installation
```sh
git clone https://github.com/areal060781/social-blog.git
cd social-blog
python3 -m venv venv
pip install -r requirements/common.txt
flask db upgrade
```

Run the application as usual
```sh
(venv) $ flask run
```