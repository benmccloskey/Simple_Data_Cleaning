# Olympics_datacleaning
Data cleaning for a dataset containing past Olympic performance by country.

Function: process_olympic_data(input_filename, output_filename)

Input File:

The 'olympics.csv' file contains 14 different entries that are needed to be processed in clean. 
 Columns (In order)
-'name' - the name of the country
'-? Summer' - number of summer games a country played in
  -'01 !' - number of gold medals won in the summer games
  -'02 !' - number of silver medals won in the summer games
  -'03 !' - number of bronze medals won in the summer games
-' Total' - number of total medals won in the summer games
-'? Winter' - number of total medals won in the summer games
  -'01 !' - number of gold medals won in the summer games
  -'02 !' - number of gold medals won in the summer games
  -'03 !'	- number of gold medals won in the summer games
  -'Total' - number of gold medals won in the summer games
-'? Games' - number of gold medals won in the summer games
  -'01 !' - number of gold medals won in the summer games
  -'02 !' - number of gold medals won in the summer games
  -'03 !' -number of gold medals won in the summer games
-'Combined total' - number of total medals won at the summer and winter games.


Output File: 
The cleaned CSV that will be outputted from the process_olympic_data() function. 

