# Data Dictionary

## Identifier

`movie_id`: IMDB Movie ID.

`movie_name`: Name of the movie.

`description`: Description of the movie.

## Features

`year`: *(numeric)*: Release year.

`certificate`: *(categorical)*: Certificate, or age rating, of the movie.
- Such as PG, PG-13, etc.

`run_time`: *(numeric\*)*: Total movie run time.
- Stored as "\[number\] min" - can be converted to numeric.

`genre`: *(categorical\*)*: Genre of the movie.
- Stored as a list of categories such as "Action, Adventure" - can be converted to categorical.

`director`: *(categorical\*)*: Name(s) of the director of the movie.
- Stored as a list of names such as "Alice, Bob" - can be converted to categorical.

`director_id`: *(categorical\*)*: IMDB id of the director(s).
- Stored as a list of IDs such as "001, 002" - can be converted to categorical.

`star`: *(categorical\*)*: Name(s) of the star of the movie.
- Stored as a list of names such as "Alice, Bob" - can be converted to categorical.

`star_id`: *(categorical\*)*: IMDB id of the star(s).
- Stored as a list of IDs such as "001, 002" - can be converted to categorical.

`votes`: *(numeric)*: Number of votes on the IMDB website.

`gross(in $)`: *(numeric)*: Gross Box Office of the movie.

## Output variable

`rating`: *(numeric)*: IMDB rating of the movie.
- Scale of 0-10.