# watchlist
Repository for movie watchlist
## Setup
*Clone repo
*Navigate to folder destination
*Install the necessary virtual environment dependencies
*Create start.sh file and add the following:
  export MOVIE_API_KEY='Your API key'
  export SECRET_KEY='Your Secret key'
  export MAIL_USERNAME='Your email address'
  export MAIL_PASSWORD='Your email password'
  export SQLALCHEMY_DATABASE_URI='DATABASE_URL'
  python3.6 manage.py server
 *Run ./start.sh file to run local server and view application
