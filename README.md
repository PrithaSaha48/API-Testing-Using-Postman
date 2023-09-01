# API-Testing-Using-Postman
How to run this project

1.Clone this project

2.Open with Postman / Command Shell

3.Run Command:

newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json 

Run Command for Report:

newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json -r cli,htmlextra

Technology used:

1.Postman

2.Newman

Prerequisite:

1.Jdk

2.Node Js

3.Newman

4.Html Report Library

Newman and Report Installation Process:

npm install -g newman-reporter-htmlextra

Newman Html Report Install Command:

npm install -g newman-reporter-htmlextra

API Documentation:

https://documenter.getpostman.com/view/28938877/2s9Y5csf89
