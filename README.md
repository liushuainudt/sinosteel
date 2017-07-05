# Introduction
This is a personal developed full-stack framework for conventional web application development, using Spring Boot for server side and React/Node.js for client side.

# Demo
Address: http://47.93.233.254:9016

username: admin  
password: admin  

This demo is a real-world application developed for China Metallurgical Engineering Co. Ltd, which is currently under testing. 

# Features
## Server side:  
Server/Client separation  
Stateless  
Service oriented architecture  
Annotated style  
Json styled communication  
Provision of basic model for object oriented development  
Multiple ORMs for different scenarios  
Security and data authorization mechanisms included   
Self defined annotation for data authorization  
Encapsulated mechanisms for http message, pagination, file upload and cache etc          

## Client side:
ES6       
Object oriented development style        
Tabbed page presentation style        
Universal presentations of models         
Common tools and components for request, file upload and authorizations etc        
Nginx for proxy          
Hot Deployment       

# Technology Stack  
## Server side         
Foundation: Spring Boot       
ORM: Spring Data Jpa & MyBatis        
Cache: Redis       
Security: Apache Shiro (stateless utilization)          
Build: Apache Maven     
JSON: FastJson       

## Client side
react + ant design + react-redux-router + redux-thunk + webpack + nginx

# Usage
This repository contains two folders: "server" folder is for the server side, and "client" folder is for the client side, both of which are able to run dependently. 

## Server side:
In the "server" folder, there are 2 folders called "framework" and "framework-example" respectively, both of which are Java projects. "framework" serves as a dependency of "framework-example".  
The project "framework-example" shows an example server side project using this framework.

To run the server:
`
$ cd framework-example
$ mvn package
$ cd framework-example/target
$ java -jar framework-example-1.0.0.jar
`

## Client side:
The "client" folder is a react based project that could run in node.js development.

To run the client for development usage:
`
$ cd framework-webclient
$ npm install
$ npm run dev
`

For production usage:
`
$ cd framework-webclient
$ npm install
$ npm run build
$ Copy the generated `dist` folder into nginx
`

# Development Guidance
To be continued