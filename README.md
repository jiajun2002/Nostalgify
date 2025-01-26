 # Nostalgify
 Nostalgify is a web application that generates a users top tracks or artists in a retro aesthetic. 

 ## Creating your own credentials
 1. Go to https://developer.spotify.com/dashboard/login and create an account and  project
 2. go to your project and add your "Redirect URIs" 

 ## How to run locally
 This application utilises Flask. 
 1. Create and activate a virtual environment
```
# On Windows
python -m venv venv
venv\Scripts\activate

# On macOS/Linux
python -m venv venv
source venv/bin/activate
```
  2. Install dependencies
  ```
  pip install -r requirements.txt
  ```
  3. Ensure that your virtual environment is activated and start Flask
  ```
  flask run
  ```
