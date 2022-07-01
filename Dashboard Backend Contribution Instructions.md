# Contributing Instructions for the Dashboard Backend

## Prerequisites
1. NodeJS Version ^16.10.0 [Download NodeJS](https://nodejs.org/en/download/)
2. NPM(will come with NodeJS download)
3. MongoDB Community Server installed and running on your device. [Download MongoDB Community Version Windows](https://fastdl.mongodb.org/windows/mongodb-windows-x86_64-5.0.9-signed.msi). FOR OTHER PLATFORMS HEAD TO THE MONGODB WEBSITE TO FIND DOWNLOAD LINK.
5. [OPTIONAL] Install MongoDB Compass for easy development. [Download MongoDB Compass Windows](https://downloads.mongodb.com/compass/mongodb-compass-1.32.2-win32-x64.exe). FOR OTHER PLATFORMS HEAD TO THE MONGODB WEBSITE TO FIND DOWNLOAD LINK.

## Instructions
1. Fork the repo
2. run `npm install` or `npm i`
3. create a `.env` in the root of the backend folder
4. `cd` into the utils folder and run twice `node secretKey.utils.js` copy the result each time, after each copy do #5.
5. in the `.env` file create two constants `TOKEN_SECRET` and `COOKIE_SECRET` and set them equal to the key copied in #4. THE VALUES **MUST** BE DIFFERENT.
6. `cd` back to the root.
7. run `npm start` to start the server. THE BACKEND SERVER **MUST** BE STARTED BEFORE THE FRONTEND SERVER.
8. when finished, check that you have formatted all files with the `prettier` extension in VS Code.
9. create a pull request in the backend repo.
10. provide detailed comments on changes you made.
11. we will review the PR and merge when ready.

## Thanks for Contributing and Happy Hacking!
