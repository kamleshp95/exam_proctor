# EMS - Exam Proctor

This Examination Proctor is made up on top of MERN stack.

Features of Exam Proctor:

👨‍🎓 STUDENT Features

- Sign Up
- Sign In
- Sign Out
- Email Confirmation
- Can see his profile
- Can see the assgined tests by the teacher
- Can attempt the assgined test
- Can see the results of attempted test
- Resumable Test
- Test Countdown timer
- Show warning popup on no Internet Connection
- Pointer events get's disabled on an offline connection

👨‍🏫 TEACHER Features

- Sign Up
- Sign In
- Sign Out
- Email Confirmation
- Create Test for the students
- Can see his profile

### Running The Project

Prerequisites For Running The Project Locally:

- Node
- NPM
- Git

To clone this repository run:

```sh
$ git clone https://github.com/kamleshp95/exam_proctor
```

Head inside the cloned folder and install the dependencies using NPM

```sh
$ cd backend
$ npm install
```

Next create a .env file in the root of the project directory, this is where you
will put all your EMS config keys, take each
property of the provided object and put it inside of the .env file like this:

```
GMAIL_USER =
GMAIL_PASS =
JWT_SECRET =
MONGODB_DATABASE_NAME =
MONGODB_USERNAME =
MONGODB_PASSWORD =
```

[![](https://i.ibb.co/SR06H2S/image.png)]

[![](https://i.ibb.co/m9cHftr/image.png)]

To start the server run :

```sh
$ node index.js
```

Now go to the client Side

```sh
$ cd client
$ npm install
```

For the final step run:

```sh
$ npm start
```

Wait for a few minutes after which it should automatically spin up a development
server for you on the PORT:3000 & backend server on the PORT 5000 and take you to the login page
