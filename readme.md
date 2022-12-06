# ChatApp

**Realtime Chatting Web Application using Django**

This is a realtime chatting web application build using Django Framework

## Find my project at

Github Repository- _`https://github.com/HimangiV/ChatApp`_

Live on railway.app- _`https://himangi-chatapp.up.railway.app/`_

## Technologies Used

- PYTHON
- DJANGO
- SQLITE
- HTML, CSS
- JAVASCRIPT AJAX

## Prerequisites

- DJANGO and PYTHON installed

## Clone Repository-

Clone the github repository using the below command-
_`git clone https://github.com/HimangiV/ChatApp.git`_

## Create and run the application

Run the below commands on CLI-

- create django project named djangochatapp-
  _`django-admin startproject djangochatapp`_
- create the chat application named chat-
  _`python manage.py startapp chat`_
- run django project on server-
  _`python manage.py runserver`_

## Database Connectivity

To connect to the database, two steps are required-
Run the below commands in your CLI-

1. _`python manage.py makemigrations`_
   This will save any changes you made in the models file
2. _`python manage.py migrate`_
   This will send all the changes into the sqlite database

_NOTE_-

- Anytime we make changes in this file, we need to repeat the above steps.
- To see the database, go to django admin panel-
  local-server-url/admin, eg: http://127.0.0.1:8000/admin
- When you open this site, its gonna ask you to login.
- To get the credentials, run the below command in your CLI-
  _`python manage.py createsuperuser`_
  It's gonna ask you to create admin username and password which you can use to login

## Features

- You can enter a chatroom using your username and the name of the chatroom you want to enter
- If the chatroom does not exist, a new chatroom will be created
- It uses sqlite to store the user messages and chatroom data
- When the user enters a chatroom, all the pre existing messages are fetched from the database and displayed in the chatroom
- Sender's name, respective message, and timestamp is displayed per chat message

## Limitations

- Messages cannot be deleted, or edited
- Messages can only be sent and displayed

> This project is inspired from [Python Backend Web Development Course (with Django) by freeCodeCamp](https://youtu.be/jBzwzrDvZ18).
