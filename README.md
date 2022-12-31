# Views On News
Views On News is a polling app that allows news organizations to connect with their viewers. News organizations can post polls on trending topics and their viewers can vote and view public's opinions regarding that matter. It is implemented with Python's Django Framework along with sqlite database to store information on polls, users, and their votes. HTML and CSS were used to design the webpages.
<br />
![Quote](https://github.com/kannikakabilar/Views-On-News/blob/main/screenshots/Screen%20Shot%202022-12-29%20at%2010.13.12%20PM.png)
<br />
# Features
Users can create an account by signing up and their account information will be stored in the accounts database table.
<br />
![Quote](https://github.com/kannikakabilar/Views-On-News/blob/main/screenshots/Screen%20Shot%202022-12-29%20at%2010.13.24%20PM.png)
<br />
The stored information in the accounts database table will be used to validate users when they try to login.
<br />
![Quote](https://github.com/kannikakabilar/Views-On-News/blob/main/screenshots/Screen%20Shot%202022-12-29%20at%2010.13.57%20PM.png)
<br />
Users can view the trending polls and select it to follow and vote. Their votes are stored in the polls database. When a poll is closed by the owner(a News Organization), it's stats will be revealed to the viewers.
<br />
![Quote](https://github.com/kannikakabilar/Views-On-News/blob/main/screenshots/Screen%20Shot%202022-12-31%20at%205.00.51%20PM.png)
<br />
![Quote](https://github.com/kannikakabilar/Views-On-News/blob/main/screenshots/Screen%20Shot%202022-12-29%20at%2010.14.24%20PM.png)
<br />
![Quote](https://github.com/kannikakabilar/Views-On-News/blob/main/screenshots/Screen%20Shot%202022-12-29%20at%2010.14.40%20PM.png)
<br />
![Quote](https://github.com/kannikakabilar/Views-On-News/blob/main/screenshots/Screen%20Shot%202022-12-29%20at%2010.14.50%20PM.png)
<br />
<br />
# How To Run
- Requirements; the following needs to be installed
```md
> python3 --version
> pip --version
```
- Using an existing virtual environment with test records <br />
Navigate to the application's directory and type the following commands. 
```md
> source newenv/bin/activate
> python3 manage.py runserver
``` 
- Running it from scratch <br />
Navigate to the application's directory and type the following commands. 
```md
> python3 -m venv myvirenv
> source myvirenv/bin/activate
> python3 -m pip install Django
> python3 manage.py makemigrations members
> python3 manage.py migrate
> python3 manage.py runserver
``` 
- Create a superuser for admin purposes 
```md
> python3 manage.py createsuperuser
``` 
<br />
To view application go to: http://127.0.0.1:8000/
<br />
