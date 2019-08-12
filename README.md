# udacity-linux-server-configuration

### IP address

3.221.150.123


### URL

http://3.221.150.123


### Software installed

* finger
* apache2
* Flask
* sqlite3 
* python-pip
* libapache2-mod-wsgi


### Configurations

* Updated and upgraded Ubuntu 
* Added ```grader``` user
* Secured user login
  * ```ssh grader@3.221.150.123 -i .ssh/udacity -p 2200 ```
* app dir: ```/var/www/FlaskApp/FlaskApp```
* wsgi file: ```/var/www/FlaskApp/flaskapp.wsgi```
* config file: ```/etc/apache2/sites-available/FlaskApp.conf```
* app database (sqlite): ```/var/www/FlaskApp/FlaskApp/bikeparts.db```
* to populate databse: ```sudo python /var/www/FlaskApp/FlaskApp/populate_database.py```
* to run app lolcally: ```sudo python /var/www/FlaskApp/FlaskApp/application.py```

### Third-party resources

* Amazon Lightsail
