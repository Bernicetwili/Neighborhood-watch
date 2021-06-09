# Gallery
## Author  
  
>[Bernice Twili](https://github.com/Bernicetwili)  
  
# Description  
This is a Django application that allows users to be in the loop about everything happening in their neighborhoods. From contact information of different handyman to meeting announcements or even alerts.
  
##  Live Link  
 Click [View Site](https://neighbor1.herokuapp.com/)  to visit the site
  
## Screenshots 
###### Home page
 
[![Screenshot-from-2021-06-09-03-20-27.png](https://i.postimg.cc/R09KPD4t/Screenshot-from-2021-06-09-03-20-27.png)](https://postimg.cc/CRPR5JZM)
 
## User Story  
  
* Sign up or log in
* Edit your profile
* Join a hood and add a post or business concerning the respective hood.
* Get health and police numbers from a hood.
* Leave a hood 

  
## BDD  
  
  
  
## Setup and Installation  
To get the code..  
  
##### Cloning the repository:  
 ```bash 
 https://github.com/Bernicetwili/Neighborhood-watch.git
```
##### Navigate into the folder and install requirements  
 ```bash 
cd Gallery pip install -r requirements.txt 
```
##### Install and activate Virtual  
 ```bash 
- python3 -m venv virtual - source virtual/bin/activate  
```  
##### Install Dependencies  
 ```bash 
 pip install -r requirements.txt 
```  
 ##### Setup Database  
  SetUp your database User,Password, Host then make migrate  
 ```bash 
python manage.py makemigrations 
 ``` 
 Now Migrate  
 ```bash 
 python manage.py migrate 
```
##### Run the application  
 ```bash 
 python manage.py runserver 
``` 
##### Running the application  
 ```bash 
 python manage.py server 
```
##### Testing the application  
 ```bash 
 python manage.py test 
```
Open the application on your browser `127.0.0.1:8000`.  
  
  
## Technology used  
  
* [Python3.6](https://www.python.org/)  
* [Django 1.11](https://docs.djangoproject.com/en/2.2/)  
* [Heroku](https://heroku.com)  
  
  
## Known Bugs  
* There are no known bugs currently but pull requests are allowed incase you spot a bug  
  
## Contact Information   
If you have any question or contributions, please email me at [bernicetwili0@gmail.com]  
  
## License & Copyright
© Bernice Twili

Licensed under [MIT License](LICENSE)