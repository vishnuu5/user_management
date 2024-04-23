# Welcome to MERN Login System

Hello everyone, In this project, we are going to create **MERN Stack App with Login System**. 
We will take a look at how to create login, registration, profile, reset password routes and learn
how to send Mail from the Node.js backend application.

## Working with the Project

Download this project from above link. Create two configaration files into the project.
First in the client and second in the server.

In the Client Folder create .env file and put this code inside it.

.env
```
REACT_APP_SERVER_DOMAIN='http://localhost:8080'
```


After that create a file in the Server Folder with the name config.js and put the below code inside it.

config.js
```
export default {
    JWT_SECRET : "LjGLIISK3E7SRbhITO+hyPokdcLFwodyT35j1rTG9x8=",
    EMAIL: "vishnuathmakuru20@gmail.com", // testing email & password
    PASSWORD : "mpcgypjarjnjbexu",
    ATLAS_URI: "mongodb+srv://admin:admin123@cluster0.9s5ufum.mongodb.net/User_management"
}
```

> **Note:** The **ATLAS_URI** is important to work this project.

Now, create all these variables in the project and make sure you set ATLAS_URI variable.
Otherwise, the project will not work.
