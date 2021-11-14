# EduSmart


The system's overall goal is to simplify tutors' interactions with their students and make it easier for them to assess their pupils' performance using a cutting-edge AI model that can not only generate tests based on subject content, but also help match and pair students with the appropriate teacher for such best customizable and personally tailored teaching learning experience.

### Technology stack

 - Frontend -ReactJS, Redux state management
 - Backend  - NodeJS, Flask
 - ML - NLP tools


### Installation and usage

#### Frontend
 - Navigate into the `frontend` folder
 - Run `yarn` or `npm install`
 - After the insatllation is over , run `yarn start` to start the server.Open browser and navigate to `http://localhost:3000` 

#### Backend
 - Create `.env` file (`.env -sample` has been given as reference) and mention the url of the hosted apis and MongoDB url in the variables
 - Navigate into the `backend` folder
 - Run `yarn` or `npm install`
 - After the insatllation is over , run `yarn start` to start the server

 #### NLP apis 
 - Run the cells of jupyter notebooks given in the `nlp` folders and copy-paste the ngrok urls in the `.env` files
