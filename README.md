# API-Test
Newman_HTML_Report using postman
Dmoney api testing with newman report

How to run to this project

1.Clone this project

2.open vs code inside project folder

3.Give command

4.Run collection using newman

open the command prompot and hit the command
```
npm iniit -y
```
6.iInstall newman by giving this command in cmd
```
npm i newman
```
Now give this command:
```
npx newman run .\collection\Dmoney_Collection.json -e .\collection\Dmoney_Env.json -n 1
```
#HTML report generate using Newman Install following package by this command:

npm i newman-reporter-htmlextra

Now hit this command:

npm test

## Report

![newman](https://user-images.githubusercontent.com/76903243/175825663-217bdc1b-aa67-4a8d-a645-6584ba0d0d60.PNG)
