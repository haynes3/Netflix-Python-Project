#netflix

![image](https://github.com/user-attachments/assets/15bbf113-5f9f-4690-b7a7-010a3217e553)

This project aims to analyze movie duration time on Netflix.

Netflix! What started in 1997 as a DVD rental service has since exploded into the largest entertainment/media company by market capitalization, boasting over 200 million subscribers as of January 2021. However, we would like to dig deeper into the average duration of movies. In order to properly analyze the csv file data, the following steps needed to be taken:

Read in the CSV as a DataFrame

Subset the DataFrame for type "Movie"

Select only the columns of interest

Create a scatter plot of duration versus year

Filter for durations shorter than 60 minutes

Define an empty list

Iterate over rows of netflix_movies_col_subset

Set the figure style and initalize a new figure

Create a scatter plot of duration versus release_year

Not all movies are shorter, but according to the data, it does appear that the volume of short movies is increasing. There are also more movies generally being made and an increase in documentaries which are generally short.
