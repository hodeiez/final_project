# Final Project for school
###### if you want to clone this repository keep in mind this is a repository with submodules so you need the flag --recursive when you clone it (git clone --recursive <this repo>)
 
  ## About
  The project is a web application for tracking and anlayze the morale status of a team. Takes inputs from each team member, while they meet up in their every day team review, stand up meeting. When a member goes to a team "live" page can send the personal status and can see what status updates send the teammates. A prototipe can be found in https://teammorale.netlify.app/  
  You can use docker-compose too if you want to test it locally (check docker-compose file for details).
  ## Project structure
  The project at the moment is divided in a client service (the web client), an email service (a service which send emails from the system) and the core service (core system linked with the database and with the main endpoints)
## Purpose of project
  This project was created to experiment and learn more about Server Sent Events (SSE), Reactor and R2DBC.
