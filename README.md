# Steve Movies

Steve is a Move Trailer Website where anyone can browse through Steve's favourite movies and watch trailers.

## Setup

You can run this project with two different options - via cloning from GitHub or executing `entertainment_center.py`:

## GitHub
Source Code: It is available on github. Clone the project using `git clone` command or fork the project to provide contributions.
  > ### Cloning project directly 
  > $ git clone https://github.com/StephenOrgan/movie-trailer-miniproject 
  > ### Cloning forked project `
  > $ git clone https://github.com/your-github-username/movie-trailer-miniproject 

## Executing entertainment_center.py

To generate the HTML file for the website, type the following command.

` $ python entertainment_center.py `

This will generate a html file named stevemovies.html in the same folder and it will overwrite the existing file if one already exits. 

## Modules

There are three modules in the projects

entertainment_center.py: You can this module as the driving one because it creates movie and actor objects and then calls the movie generator to create html file

fresh_tomatoes.py: This is some what relates to views means this module creates the html for the website.

media.py: Provides the data model for Movies in addition to defining the behaviour for opening youtube trailers.
