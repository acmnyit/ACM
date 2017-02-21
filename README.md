# ACM NYIT Chapter
This is the website created by <a href="https://github.com/denisolt">president</a> and <a href="https://github.com/msdocs">founder</a>
for Association for Computing Machinery at NYIT manhattan campus <br/>
Website is build on Django, users are capable of adding events to the calendar, add blog posts and has a custom form for signup <br/>
Signed up users are being stored in the DB together with Events and Posts. </br>

Check out the website: <a href="http://acm-nyit.org">acm-nyit.org</a> </br>
![alt tag](https://github.com/Denisolt/acm/blob/master/readmeimage.png?raw=true)

Installation
-----------------------------------------
Activation of virtual environment:
```
source local/bin/activate
pip install -r /path/to/requirements.txt
```
Configuring and running Django:
```
#creating a super user
./manage.py createsuperuser 
#creating a migration
./manage.py makemigrations
#run the server
./manage.py runserver
```
Capabilities
-----------------------------------------
By going to the admin page (localhost/admin) and entering superuser login and password </br>
Admin can create events, posts, and access the db of signedup users </br>
Creation of the event:
![alt tag](https://github.com/Denisolt/acm/blob/master/mainpage.png?raw=true)
Creation of the blog post:
![alt tag](https://github.com/Denisolt/acm/blob/master/mainpage.png?raw=true)
Accessing the db of signed up users:
![alt tag](https://github.com/Denisolt/acm/blob/master/mainpage.png?raw=true)
