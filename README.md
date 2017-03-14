# Steve Movies

Steve Movies is a Move Trailer Website where anyone can browse through Steve's favourite movies and watch trailers.

## Setup

You can run this project with either of two different options - via cloning from GitHub or executing `entertainment_center.py` with Python:

## GitHub
Source Code: It is available on github. Clone the project using `git clone` command or fork the project to provide contributions.
 
 ``` 
   # Clone the repository directly 
   $ git clone https://github.com/StephenOrgan/movie-trailer-miniproject 
   # Clone a forked repository
   $ git clone https://github.com/your-github-username/movie-trailer-miniproject 

   ```

## Executing entertainment_center.py via Python

To generate the HTML file for the website, type the following command.

` $ python entertainment_center.py `

This will generate an html file named stevemovies.html in the same folder and it will overwrite an existing file if one with the same name already exists. 

## Modules

There are three modules in this project:

entertainment_center.py: Contains the instances of the Movie object and the data for Steve's favourite movies as an array.

steve_movies.py: Provides the view for the website composed for HTML/CSS/and Javascript.  This file was derived from fresh_tomatoes.py.

media.py: Provides the data model for Movies in addition to defining the behaviour for opening youtube trailers.
