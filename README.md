# EMS - Exam Proctor

This Examination Proctor is made up on top of MERN stack.

Features of EMS:

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
- Auto submit test on completetion of test duration
- Can check the latest assigned test to the student
- Can flag a particular question during attempting the test
- Can Clear the question answer during attempting the test
- One attempt per test ( Second attempt prohibited )
- Automatic logout on token expiration
- Show warning popup on no Internet Connection
- Pointer events get's disabled on an offline connection

👨‍🏫 TEACHER Features

- Sign Up
- Sign In
- Sign Out
- Email Confirmation
- Create Test for the students
- Can see his profile
- Can assigned test to the students ( using Class eg. IX, XI etc)
- Can see the all the assigned tests
- Can see all the registered class in EMS
- Can see the students who attempted a particular test
- Can see the students marks analysis in detail
- Automatic logout on token expiration
- Show warning popup on no Internet Connection
- Pointer events get's disabled on an offline connection

### Features To Be Added

The following features are under development/open for contributions.Please first
create a feature issue to discuss about the feature you would like to take up.

- [ ] Profile Updation ( Student & Teacher )
- [ ] Update Test ( Teacher )
- [ ] Delete Test ( Teacher )
- [ ] Automatic Logout on expiration of token
- [ ] Display error message on failed Request to server
- [ ] Warning Popup on moving out of test ( Student )

Valid Feature Requests will be added to the above list over time.

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
