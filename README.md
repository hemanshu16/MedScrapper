# MedScrapper
 A project on Medicine Information Scrapping
 
 - MedScrapper is a Website that helps users to find alternative medicines of a particular medicine. It scrapes medicine information from onemg, netmeds, and pharmeasy websites,  and gives relevant information.
 
 - Project Demo Link :- https://youtu.be/5-yiMt9RwyM

# Project Setup
- Required to have python and pip installed on computer
# Create virtual enviroment from powershell
```
virtualenv myEnv
```
# Go to command prompt and activate enviroment
```
 myEnv\Scripts\activate
```
# Install beautifulsoup and playwright
```
pip install beautifulsoap4 
```
```
pip install playwright
```
```
playwright install
```
# Install Django And Related Packeges
```
pip install Django
```
```
pip install Django-environ
```
```
pip install Psycopg2
```
```
pip install Django-cors-headers
```
- Create Environment Variable file in MedServer .env
  - Add credentials like DATABASE_NAME, DATABASE_USER, DATABASE_PASS

# Migrate Database
```
python manage.py makemigrations
```
```
python manage.py migrate
```

# Go to server folder and run servre
```
python manage.py runserver
```

