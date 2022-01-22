<p align="center">
    <h2 align="center">Lucas Amorim Lima</h2>
</p> 
<p align="center">Personal Expense Management</p>

## :rocket: Quick start

**Run the site locally**

_NOTE: The default branch for this repo is `master`, when you push or pull make sure you specify the correct branch_

### Step 1: Clone The Repo

Fork the repository. then clone the repo locally by doing -

```bash
https://github.com/LucasAmorimLima/Tindin-Challenger-Fase2
```

### Step 2: Install Dependencies

cd into the directory

```bash
cd Tindin-Challenger-Fase2
```

install all the dependencies
```bash
npm install
```

### Step 3: Start Development Server

Then start the development Server
```
npm run dev
```

After running the development server the site should be running on https://localhost:3333


## :open_file_folder: What's inside?

A quick look at the folder structure of this project.

    .
    ├── api
    │   ├───controller
    │   ├───model
    │   └───services
    ├── config
    ├── routes
    |── tests

## Tools Used

1. Express
2. Mongoose
3. JWT
4. Lodash
5. Swagger
6. Jest
7. typescript
8. Joi
9. Axios

## :v: Contributing

*NOTE: if you want to change the [project content](./content) or fix any typo you can do that from github's ui without cloning the repo locally*

After cloning & setting up the local project you can push the changes to your github fork and make a pull request.

## Explication for the tools

1. Express
  
 Express is a minimaland flexible framework for node .js web application that provides a robust set of features for web and mobile applications.
  It is simple to use and fulfil the requirements for a web api, it's also possible to find some more advanced features, but there are some cases thats Express is requested.
  
2. Mongoose

  Mongoose is a Nodejs library that provides a schema-based solution for modeling your application data. It has a system of converting types, validating, creating queries, and hooks for business logic.
  Mongoose provides a mapping of MongoDB objects similar to Object Relational Mapping (ORM), or Object Data Mapping (ODM) in the case of Mongoose. This means that Mongoose translates the database data into JavaScript objects so that it can be used by your application.
  
3. JWT

  Json web token is a way to verify if a particular person has access to the REST API developed, is widely used in application development.
  
4. lodash

  Is a library for handling arrays, I like to use it because array operations become more concise and avoid additional code.
  
5. Swagger

  Simplify API development for users, teams, and enterprises with the Swagger open source and professional toolset. Find out how Swagger can help you design and document your APIs at scale.
  I use it because it is an efficient way to assemble a documentation and can also do tests, check types of returns, among other features.
  
6. Jest

  Jest is a test library that can be used in conjunction with other utilities such as supertest to perform http requests.
  
7. Typescript

  TypeScript is a superset of JavaScript, that is, a set of tools and more efficient ways to write JavaScript code, adding features that are not natively present in the language.
  
8. Joi

 Joi serves to validate endpoints in a more secure and concise way, abstracting the responsibility of writing validation logics, such as an email or CPF.
    
9. Axios

 Axios is a lightweight HTTP client based on the $http service inside Angular.js v1.x and is similar to JavaScript's native Fetch API.
 Axios is promise-based, which gives you the ability to leverage JavaScript's async and await for more readable asynchronous code.
    
## Swagger

Once the application is started, you can see the documentation produced in swagger by the endpoint http://localhost/3333/api-docs

## Tests

Once the application is started, you can make the test of application running the command:

```
npm test
```

## Integration with unsplash

First I tried to integrate with Libraries & SDKs available by unsplash
(https://github.com/unsplash/unsplash-js)
,but as the project was developed in typescript some errors arose because the integration is not 100%
(https://github.com/unsplash/unsplash-js/issues/186)
,So I decided to make the connection with the axios library, after all at the end of the process it is still a formatted endpoint, at first I felt a little difficult to manage the access key, but I managed to do the integration.

## Insomnia 

You can download the insomnia documentation used in the project by accessing the button below, need to have installed insomnia.

[![Run in Insomnia}](https://insomnia.rest/images/run.svg)](https://insomnia.rest/run/?label=TinDin%202&uri=https%3A%2F%2Fgithub.com%2FLucasAmorimLima%2FLucasAmorimLima%2Fblob%2Fmain%2Ftindin%25202)

## Project in Nestjs

Project developed in nestjs in order to show my skills in the development framework nodejs.

```
https://github.com/LucasAmorimLima/Tindin-Challenger-Fase2-nestjs
```
