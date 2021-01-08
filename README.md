## python-microservices-fcc-repo

# Python Microservices by freeCodeCamp - Reproduced by Alexandre Paes

#### Learn About Python Microservices by Building an App Using Django, Flask, and React

###### Credit to:  Beau Carnes - DECEMBER 22, 2020 and freeCodeCamp

Using Python microservices allows you to break up your apps into smaller parts that communicate with each other. This can make it simpler to scale the application based on the traffic. Also, the separation of concerns makes it easier to work on just one part of the app at a time.

We've released a course on the freeCodeCamp.org YouTube channel that help you learn about Python microservices by teaching you to build a web app using Django, Flask, and React.

Antonio from Scaleable Scripts created this course. Antonio has a lot of experience creating software courses.

#### Here are the topics covered in this course:

- What are Microservices?
- Project Introduction
- Django Setup
- Adding Docker Files
- Connect Django with MySQL with Docker
- Models & Serializers
- Rest APIs with ViewSets
- User Endpoint with APIView
- Flask Setup with Docker
- Connect Flask with Mysql
- Models
- Flask Migrations
- RabbitMQ
- Django Producer and Consumer
- Flask Producer and Consumer
- Queue Service
- Data Consistency
- Internal Http Requests
- Finishing the python apps
- React Setup
- Products CRUD
- Completing the Main App

Watch the full course on the https://youtu.be/0iB5IPoTDts (2 hours watch).

#### Command line being used in order to build it up:

- python -m venv venv3
- source venv3/Scripsts/activate (git bash as the terminal)
- pip install django
- pip install djangorestframework
- pip install django-mysql
- pip install mysqlclient
- pip install django-cors-headers
- pip install pika
- django-admin startapp admin
- django-admin startapp products
- docker-compose up
- pip freeze
- pip freeze > requirements.txt
- docker-compose exec backend sh
- #python manage.py makemigrations
- #python manage.py migrate
- mkdir main
- cd main
- touch main.py
- Copy and paste Dockerfile and also docker-compose.yml from the admin folder and change a few parameters as seen on the updated now. Just compare then will see the changes.
- pip install Flask==1.1.2 Flask-SQLAlchemy==2.4.4 SQLAlchemy==1.3.20 Flask-Migrate==2.5.3 Flask-Script==2.0.6 Flask-Cors==3.0.9 requests==2.25.0
- python main.py (just for initial flask testing)
- crtl + c
- docker-compose up (just for initial flask testing with docker...)


### Referencies

- https://www-freecodecamp-org.cdn.ampproject.org/v/s/www.freecodecamp.org/news/python-microservices-course/amp/?amp_js_v=a6&amp_gsa=1&usqp=mq331AQFKAGwASA%3D#csi=0&referrer=https%3A%2F%2Fwww.google.com&amp_tf=Fonte%3A%20%251%24s&ampshare=https%3A%2F%2Fwww.freecodecamp.org%2Fnews%2Fpython-microservices-course%2F

- https://youtu.be/0iB5IPoTDts

