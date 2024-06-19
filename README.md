# NYC-ELA-Scores

The html file includes code for developing figures that breakdown third grade scores on the New York State English Language Arts assessment by 1) New York City school district and 2) District 9 school for the 2022-23 school year. 

The purpose of this analysis was to better understand how the city's handling the ongoing literacy crisis in the Bronx. Across the five boroughs, District 9, which covers Highbridge, Concourse and adjacent neighborhoods in the Bronx, had the lowest percentage of third grade students reading at their grade level, according to the latest state assessment results.

The dataset is obtained via the [NYC OpenData API](https://data.cityofnewyork.us/Education/English-Language-Arts-ELA-Test-Results-2013-2023/iebs-5yhr/data) and read in as a csv file using Pandas.

Both of the normalized bar charts are created using Altair. They detail assessment outcomes by "Level" achieved, showing the percentage of students in a district or school that received a score aligned to one of four levels. Students performing at Level 3 or higher (i.e., Level 4) are considered proficient in standards for their grade. The charts are sorted highest to lowest by student population proficiency.
