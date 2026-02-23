#  Dockerized Application Project

##  Overview
This project demonstrates how to containerize an application using Docker.  
It solves the common problem:  
👉 “It works on my machine but not on yours!”  

With Docker, the application runs consistently across all environments.

---

##  Features
- Containerized application using Docker  
- Easy to run on any system  
- Consistent environment  
- Lightweight & fast deployment  

---

## ⚙️ Tech Stack
- Docker  
- Docker Compose
- jenkins 
- Django , mysql , javascipt ,Nginx, python

---

# Simple Notes App 
This is a simple notes app built with React and Django.

## Requirements
1. Python 3.9
2. Node.js
3. React

## Installation
1. Clone the repository
```
git clone https://github.com/LondheShubham153/django-notes-app.git
```

2. Build the app
```
docker build -t notes-app .
```

3. Run the app
```
docker run -d -p 8000:8000 notes-app:latest
```

## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`
`sudo apt install nginx`


