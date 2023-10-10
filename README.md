# FlaskMovieBlog
Project for the Mathesis Flask Course

This Project is a mini Blog with movies, their pictures, description and grade.
It also has users who can see all movies and add movies or delete own movies.

## Run through Docker
1. Navigate to the folder where the Dockerfile is through the terminal 
2. Run: docker build -t \<your-image-name\>:\<optional-tag\> . (with the dot)
3. Run:  docker run -it -p \<port-of-your-choise\>:5000 -v "$(pwd)/flaskMoviesApp/flask_movies_database.db:/usr/src/app/flaskMoviesApp/flask_movies_database.db" \<your-image-name\>:\<optional-tag\>
4. Go to browser and use the addresse localhost:\<port-of-your-choise\>

## Run in local Virtual Enviroment
1. Create virtual enviroment with: python -m virtualenv <name of your choise>
2. Run the activate (for windows) file in the enviroment folder through terminal.
3. Navigate with the same terminal to the FlaskMovieBlog folder.
4. Install packages with: pip install -r requirements.txt
5. Run the app with: flask run --host=0.0.0.0
6. Open browser in localhost:5000 or at the address found in the terminal logs


