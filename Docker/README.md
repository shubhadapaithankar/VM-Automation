# Emart-App

The application is designed using microservice architecture. This is the e-commerce containerized application using vagrant.
The purpose is to use containers to enable rapid deployment, patching, and scaling of applications. Containerizing  applications make deployment faster and a lot easier.

## Architecture Diagram 

![image](https://user-images.githubusercontent.com/99461999/179873942-7e92cbbd-1ef8-4256-9505-08609d326db4.png)

## Tools:


1. Nginx API gateway  (3 end points /,/api and /webapi) --->frontend
2. Client application : Angular ---> / api --> smartapi of Node JS
    /webapi -----> Books api (java)
3. Docker-compose,Docker
4. Database: MySql , MongoDb
5. Vagrant --> VM automation

## Sources

Enspire from udemy https://www.udemy.com/ 
