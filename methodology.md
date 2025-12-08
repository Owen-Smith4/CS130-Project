# Methodology
## Data Sources
Music.csv file from Corgis
## Data Preparation and Cleaning
I prepared my data by separating it by commas and formatting it into a dataframe where I could make sub sections based on things like artist.terms, song.hotttnesss, and artist.name by using .loc on my dataframe
## Assumptions
I made the assumption that my data was being collected based on a large scale of users interacting with it. For example, the artist.hotttnesss variable would be pretty useless if it had a small sample size because it wouldn't tell me how popular the artist is among a large audience. Also, I assumed that there was a varying audience from all generations and music tastes otherwise the artists that were ranked the highest on popularity would be skewed towards the largest group of users
## Limitations
I was limited by the number of songs in the dataset. It is not possible to have every song ever made on a single dataset so there can be songs and artists that are misrepresented just because their most popular songs weren't on the list so they weren't mentioned among the top percent of artists. Also I am limited by the time period of the data, the songs only span between a specific amount of time so songs before and after the scope of the data will not be represented
