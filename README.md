# FlaskMovieBlog
Project for the Mathesis Flask Course

This Project is a mini Blog with movies, their pictures, description and grade.
It also has users who can see all movies and add movies or delete movies own movies.

## Run through Docker
- Navigate to the folder where the Dockerfile is through the terminal 
- Run: docker build -t <your-image-name>:<optional-tag> . (with the dot)
- Run:  docker run -it -p <port-of-your-choise>:5000 -v "$(pwd)/flaskMoviesApp/flask_movies_database.db:/usr/src/app/flaskMoviesApp/flask_movies_database.db" <your-image-name>:<optional-tag>
- Go to browser and use the addresse localhost:<port-of-your-choise>


