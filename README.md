# mapping-data
## Coursera Lesson 2: Mapping Data to Python

I have applied method *`read_csv`* of the `pandas` library to open the dataset file in `csv`. I observed the names of the columns and the first one ('Unnamed: 0') lead me to drop it since we already have an ID created by the pandas for each record, so I considered it redundant. After this, I applied some filters to choose desired data and the procedure taught in the lessons to convert the resulting data frame into JSON format. Finally, I have implemented the procedure learned in the course lessons to create a JSON file that contains the resulting data frame.

### Additional Coding: Statistical parameters
Also, I have extracted some statistical parameters from the column "rating" using `pandas` and I observed it: We can see a similar pattern in the Carnival scores given in the Carnival teams contest in the Brazilian context. In this context, there is an implicit rule to score the teams with values higher than 9.0, in other words, it is a social fact (Emile Durkheim would say it, I guess...). There were some cases in which scores below this value were given, and they caused discomfort in the community involved in this contest.
