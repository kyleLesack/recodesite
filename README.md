* Clone heroku code
* copy heroku env vars into a .env file at project root
* comment out any lines in the .env file related to python and paths
* add a SECRET_KEY entry in the .env file set to any random string of characters
* create a virtual environment and activate it
* `pip install -r requirements.txt`
* `heroku local web`

To get hot reloading on the server so you can see your changes without restarting the server, go the bottom of app.py and turn debugging on. 


LOGS
---
04/2020 - User reported being unable to submit translation
Cause: outdated code
Fixes: 
* updated python runtime version
* updated failing function calls
* updated boto s3 connection function names
* created new AWS access key and updated Heroku config vars
