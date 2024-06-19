# NYC-ELA-Scores

Breaks down third grade performance on the 2022-23 New York State English Language Arts exam by 1) New York City school district and 2) District 9 school.

Across the five boroughs, District 9, which covers Highbridge, Concourse and adjacent neighborhoods in the Bronx, had the lowest percentage of third grade students reading at their grade level.

Both of the normalized bar charts are created using Altair and illustrate aggregate performance by “level” achieved, where student scores are organized into four discrete ranges or “levels.” Students performing at Level 3 or higher (i.e., Level 4) are considered proficient in standards for their grade. Each chart is sorted highest to lowest by student population proficiency.

The dataset is obtained via the [NYC OpenData API](https://data.cityofnewyork.us/Education/English-Language-Arts-ELA-Test-Results-2013-2023/iebs-5yhr/data) and read in as a csv file using Pandas.

Note that the charts are interactive. Select a bar to isolate exam outcomes for a specific district or school. Double click on the selected bar to return to city or district-wide results. To navigate the figure, hover over the charts for a textbox overview of the embedded data. 
