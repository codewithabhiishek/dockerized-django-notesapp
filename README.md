Simple Notes App

A simple Notes App built with React and Django, containerized using Docker.

Requirements
Python 3.9
Node.js
Docker
Nginx (for reverse proxy)

Installation-

Clone the repository: 
'''
git clone https://github.com/codewithabhiishek/dockerized-django-notesapp.git
'''

Build the Docker image:
'''
docker build -t notes-app .
'''

Run the app:
'''
docker run -d -p 8000:8000 notes-app:latest
'''



