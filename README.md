# CafeManagementSystem

this is an exercise of a full stack application for the management of a coffe market

## How to run the application

**Required SW**
- My SQL 8.0 https://dev.mysql.com/downloads/mysql/
- Node 16.13.2 https://nodejs.org/en/blog/release/v16.13.2
- npm 8.1.2 https://www.npmjs.com/package/npm/v/8.1.2
- Angular/cli 15.2.4 https://www.npmjs.com/package/@angular/cli/v/15.2.4

### Backend

1. go to Backend-Cafe-Nodejs folder
```
cd ./Backend-Cafe-Nodejs
```
2. run the npm install command
```
npm install
```
3. create your own mysql DB with the commands in the table.sql file under Backend-Cafe-Nodejs folder
4. under the folder Backend-Cafe-Nodejs create a file named '.env' the structure will be like this:
```
//Server
PORT= 8080

//Connection
DB_PORT = "your DB PORT"
DB_HOST= localhost
DB_USERNAME = "your DB USERNAME"
DB_PASSWORD = "your DB PASSWORD"
DB_NAME = "your DB NAME"

ACCESS_TOKEN = d1253bf6a0b1fc277b4ebc05720ede2f79a4657536f5c5063b5a681024b37a080d07c680181392f0ccd47811172a77d4a3e5ff03dd742d89c908b42713dfc1ed

EMAIL = "An email used for the password reset"
PASSWORD = "A genereted App Password, gmail guide: https://www.youtube.com/watch?v=lSURGX0JHbA"

USER = user
```
5. start the BE server
```
npm start
```

### Frontend

1. go to frontend folder
```
cd ./frontend
```
2. run the npm install command
```
npm install
```
4. start the FE client
```
ng s
```

**__THE ORIGINAL PROJECT IS OF BTech Days__** https://youtu.be/SqSN6sqbdMQ
