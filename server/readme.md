# AUTHREACT

Hi everyone!! I'm Following a tutorial from Stephen Grider if you are interesting to learning check his classes here
Udemy tutorial: [Redux](https://www.udemy.com/react-redux/)

It is a practice project to learn and understand better **React, Redux with previous elements that I've been studying like: Route, HOC, etc**. Now the new element to study is **Redux Thunk**. Also this project is to get an idea how to work as a Fullstack (My backend skills are still low, right now I'm focus to try to be better on Frontend, but I realize that backend I don't have to put far away - A reminder to myself jajajaja xD).

The project as entire thing is an authentication form (Sign In, Sign Up and Sign Out). This will be divided in two part.

## Server Part

For this part you have to install all the dependencies. So for that you can type this 

```
npm install
```

The server part will going to handle the local routes that we going to use when we connect with the client part. Also will handle the data as an user going to use to Sign In or Sign Up, with MongoDB as DataBase. The server will check the data we get in the form and that way will give us an authentication to continue. Also the server part will be in charge to get or create token and that way you can have a sure authentication

### Requirements 

* NodeJs
* MongoDB
* RoboMongo - *This is optional (This one is to the an UI to check the DB and see the data is recived and working well)
* Postman or Insomnia (What you prefer to check the endpoints) To check if the request that you want give the right answer
* Don't Forget install the Project depencies

Once you installed all the dependencies on terminal to make work the server you have to type this

```
mongod
```
This on will activate the Database

```
npm run dev
```
After run the mongo command you have to open other terminal or just open other tab (**Don't close the tab or terminal where is mongo running**) this script you can watch it on **package.json**. This one is for to run the server locally and keep watching the changes that will make on it. 