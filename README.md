# Merging-Cleaning-Transforming-Data-Movies-Dataset-

### Introduction / Getting the Datasets
#### 1.	Load and inspect the datasets "movies_clean.csv" and "credits.csv". Identify stringified/nested json columns in the credits dataset.

### Preparing the Data for Merge
#### 2 Drop Duplicates in the credits datasets

### Merging the Data
#### 3.	Merge/Join the datasets movies_clean and credits. -> Add the features cast and crew to the movies_clean dataset.

### Cleaning and Transforming the new "Cast" Column
#### 4.	Evaluate Python Expressions in the stringified column "cast" and remove quotes ("") where possible.
#### 5.	Determine the cast size for all movies (number of actors) and add the additional column "cast_size".
#### 6.	Extract all actor names from the column "cast" and overwrite "cast". If a movie has more than one actor, seperate names by a pipe "|".
For example: The value in the first row (Toy Story) should be 'Tom Hanks|Tim Allen|Don Rickles|Jim Varney|Wallace Shawn|John Ratzenberger|Annie Potts|John Morris|Erik von Detten|Laurie Metcalf|R. Lee Ermey|Sarah Freeman|Penn Jillette'.
#### 7.	Inspect cast with value_counts(). Do you see anything strange? Take reasonable measures!

### Cleaning and Transforming the new "Crew" Column
#### 8.	Evaluate Python Expressions in the stringified column "crew" and remove quotes ("") where possible.
#### 9.	Determine the crew size for all movies (size of the crew) and add the additional column "crew_size".
#### 10.	Extract the director name from the column "crew" and create the new column "director".
For example: The value in the first row (Toy Story) should be 'John Lasseter'.

### Final Step
#### 11.	Drop the column "crew" and save the dataset in a csv-file.


