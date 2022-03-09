# Prison Break Project: Analyzing Helicopter Escapes
On multiple occassions, prisoners have tried to break out of prison with the aid of helicopters. The aim of this project was to answer the following questions:

- In which year did the most attempts at breaking out of prison with a helicopter occur?
- In which countries did the most attempted helicopter prison escapes occur?

To answer these questions, I scraped and analyzed data from [this](https://en.wikipedia.org/wiki/List_of_helicopter_prison_escapes) Wikipedia page. It covers the details of attempted helicopter prison escapes over a 50-year period (1971-2020). I used Python programming and Jupyter notebook for this project.


## Preparing the Data
Step 1: I imported the modules and libraries I would need.

Step 2: I loaded the data into the notebook using Pandas. 
Step 3: I explored the dataset. The data contained six fields:
1. The date of the attempted prison break
2. The name of the prison
3. The country where it happened
4. Whether the attempt was successful or not
5. The names of the escapees
6. More details about the case

There were a total 48 attempted helicopter escapes, although some of the escapess tried to break out multiple times. I made a copy of the dataset and drop the details and escapees column, because they were not needed for the analysis. The rest of the data did not contain any errors, so I moved on to analysis.

## Analysis and Visualization
Step 4: To answer the first question, "In which year did the most attempts at breaking out of prison with a helicopter occur?", I made a pivot table, to count how many helicopter escapes occured in each year. I found that each year had three or less attempts, and 1986, 2001, 2007 and 2009 had the highest number of attempted helicopter escapes (3). I then created a bar chart visualizing the results.

To determine the country with the highest number of attempts, I also used a pandas pivot table. France had the highest number of attempts, 15, while th US had the second highest (8), the other countries on the list had four or less attempts between 1971 and 2020. I also visualized these results with a bar chart. I used a bar chart for these visualizations because the classes of observations were too many for other types of charts (like a pie chart). A barchart was the best for readability and interpretation.

## Extra
I wanted to know more about the cases, so I decided to find out how many of the escapes were successful (were the escapees able to leave the prisons with the helicopters?) and how many of the successful escapees were able to stay out of prison. To do these, I had to do some online research and read news articles to find out which of the successful escapees were later caught. I then updated the dataset with the new information, used pivot tables to count the successful escapees, and visualized the results using pie charts. 
