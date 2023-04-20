# Telesnooze by Group 34

## Requirements for running 
- an recent version of the node package manager (npm)
- support for go-lang

## steps for running
- clone the repo from github
- cd into frontend directory and use "npm i" to install all necessary frontend node packages
- cd into backend directory and use "go get" all 
- use npm run start in frontend directory to start frontend and go to http://localhost:4200/
- use go run . in backend directory to package and run the main package, which starts the server instance
- have fun!

### Description:
Telesnooze is a web app that will act as a wake up call service. The user can set dates/times to receive a call, 
set snooze paramaters, and set custom questions/codes. Each user will have a profile that keeps track of their data
and preferences. 


### Core Features: 
  #### Frontend: 
  Login page
  User Dashboard: 
  - wakeup time/date selections, timezone selection
  - success rate/number of attempts to wakeup
  - snooze/call N times UI 
  - user profile

 
   #### Backend: 
   - Authentication and session tokens
   - CRUD for wakeup time/dates and user info
   - Twilio / Telnyx integration for VOIP calling and DTMF handling, 
      which will track successful wakeups/ number of attempts
 
### Auxilary features if time permits: 
  - User defined questions 
  - Upload MP3 to play during wakeup
  - More advanced statistics regarding attemped wakeups/graphing
  - Random multiple choice questions, integrated with https://quizapi.io/


### Frontend Developers: 
- Jesse Maki 
- Andy Perez

### Backend Developers: 
- Ethan Shover
- Sean Hernandez
