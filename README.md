# Advanced Node.js

## This repository
> In this course we created an IoT app using light real time protocols (MQTT) and websockets, integrating the apps with relational DB.

## Introduction
#### What is Node.js?
> Node.js is a platform built on Chrome's JavaScript runtime for easily building fast and scalable network applications. Node.js uses an event-driven, non-blocking I/O model that makes it lightweight and efficient, perfect for data-intensive real-time applications that run across distributed devices.

#### What is nodemon?
> nodemon is a tool that helps develop node. js based applications by automatically restarting the node application when file changes in the directory are detected.


## Main Concepts
> - `Modules`: in Node.js is a simple or complex functionality organized in single or multiple JavaScript files which can be reused throughout the Node.js application.
> - `AVA`: is a test runner for Node.js with a concise API, detailed error output, embrace of new language features and process isolation that lets you develop with confidence.
> - `Mocks`: are objects that replace real objects while simulating their functions. A mock also has expectations about how the functions being tested will be used.
> - `EvenEmitter`: is a module that facilitates communication/interaction between objects in Node. EventEmitter is at the core of Node asynchronous event-driven architecture.
> - `Vue`:  is a progressive framework for building user interfaces. Unlike other monolithic frameworks, Vue is designed from the ground up to be incrementally adoptable.
> - `Websockets`: It is a stateful protocol, which means the connection between client and server will keep alive until it is terminated by either party.
> - `MQTT`: is an OASIS standard messaging protocol for the Internet of Things (IoT). It is designed as an extremely lightweight publish/subscribe messaging transport that is ideal for connecting remote devices with a small code footprint and minimal network bandwidth.
> - `PostgreSQL`: is a powerful, open source object-relational database system that uses and extends the SQL language combined with many features that safely store and scale the most complicated data workloads.
> - `Vagrant`: is a tool for building and managing virtual machine environments in a single workflow. With an easy-to-use workflow and focus on automation

## More information
> [EventEmitter]:(https://github.com/JasanHdz/backendnodejs/tree/master/notes#event-emiter)
> [Vagrant]:(https://www.vagrantup.com/intro)


## Dependencies
> - Install [VS Code](https://code.visualstudio.com/download)
> - Install [Node.js](https://nodejs.org/en/)
> - Install nodemon (Optional)
>   * Cloning with git or by using npm (the recommended way):
> ```
> npm install -g nodemon
> ```
>   * You can also install nodemon as a development dependency:
>   ```
>   npm install --save-dev nodemon
>   ```
> - Install nvm 
>   * Download and Install the .exe that is in nvm-setup.zip from [repo](https://github.com/coreybutler/nvm-windows/releases)
> - When we execute the project for first time, we'll need to create the DB and a user with permission to feed the DB.
> - Install [postgreSQL](https://www.postgresql.org/download/)

## Run Code
> - Use `npm i` to install the project dependencies
> - For Windows use the command `cd [path]` and `npx nodemon [script]` to run the project automatically
> - MongoDB Atlas
> 1- Create mongo database: I used the [mongodb altas](https://www.mongodb.com/cloud/atlas) platform for creating and managing one.Later you will need to create a user/password in order to connect the server with the DB.
> 
> 2- Create `.env` in the root path `/` file and your variables

```
DB_NAME=core-xyz.gcp.mongodb.net
DB_USER=db_user_value
DB_PASSWORD=db_password_value
```

## Technologies
> - JavaScript

_Created by Nara Peña Gámez._

