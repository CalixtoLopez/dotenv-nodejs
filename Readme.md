#Install dotenv

## npm i dotenv

## yarn add dotenv

#Create .env
$mkdir .env
$cd .env

- Add new variable env (example COMMAND:FIRST_COMMAND)

#Create file index.js
$touch index.js
$nano index.js

- Add code [require("dotenv").config();
  console.log(process.env);]

#Run start
$node ./index.js
