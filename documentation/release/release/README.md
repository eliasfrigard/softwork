# Softwork

The system is divided into three applications, each responsible for its own part. 

Frontend - Client side code / user interface in Vue.
Service - Fetches and filters job ads from different API providers.
Backend - Responsible for connecting the two above, as well as handling user information and routing.

## Run Locally

To run Softwork locally, you need to start all three applications. Navigate to the directory of each application and follow the instructions contained in each README.md file. 

The order in which you start the applications should not matter. You might however need to update .env variables if you decide to run applications on non-default addresses.

## Deployment

The applcation is deployed on the following URL.

https://trusting-tereshkova-141673.netlify.app/

__OBS!__ Please note that the first time you use the application, there will be a 10 second delay. This is due to Heroku (where the backend is deployed), puts the backend to sleep if it has been unused for some amount of time. After the initial delay the application will function as intended.