# SQLBolt Exercise 1

1. Find the title of each film.
SELECT Title FROM movies;

2.Find the director of each film.
SELECT Director FROM movies;

3.Find the title and director of each film.
SELECT Title, Director FROM movies;

4.Find the title and year of each film.
SELECT Title, year FROM movies;

5.Find all the information about each film.
SELECT * FROM movies;

#Exercise 2

1.Find the movie with a row id of 6.
SELECT Title FROM movies where id = 6;

2.Find the movies released in the years between 2000 and 2010.
SELECT Title FROM movies where year > 1999 and year < 2011;

3.Find the movies not released in the years between 2000 and 2010.
SELECT Title FROM movies where year <2000 or year >2010;

4.Find the first 5 Pixar movies and their release year.
SELECT * FROM movies where id < 6;

#Exercise 3

