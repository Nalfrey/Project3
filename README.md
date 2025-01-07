Our overall project is housed in a Jupyter Notebook (JN) and runs as a normal JN runs using a SQL database. The first 7 cells should be executed as a normal Jupyter Notebook. In our repository you will find a Project proposal which we used in our ideation phase of this project, a readme, an initial CSV that was used for the data, a jupyter notebook for the execution of analysis, the html for our hover design, and a total steams with the hover design. 

For the Jupyter Notebook:

For the first visualization we showed the top 10 songs that were streamed for 2023, you must import plotly express, reset the indices, and then create the bar chart with the hover functionality. 

For the second visualization we looked at the streams by song released year, we grouped the data by the year the song was released(released_year) and then by the number of streams(streams). We made sure that the graph was more easily readable by showing only songs that were released after the year 2000. 

For our last visualization we compared the dataset information on the number of times a song was found in a Spotify playlist and the number of times a song was found in an Apple playlist. We created an aggregation of the data columns “in_spotify_playlists” and “in_apple_playlists”. Those were then compared by platform and playlist count. These were presented in a pie chart.

Lastly for user interaction we created a user feedback box that allows the user to input their favorite artist to see if they had songs that were part of the most streamed songs of 2023. We created a function to get the list of songs by the artist, we also considered that if the artists name was in collaboration with another artist, it would pull as well. We then printed an if, else statement that if the artist name was not found, JN would print that there were no songs found for the artist. If songs were found then it would iterate through the rows and print all songs that that artist had in the most streamed songs of 2023, the corresponding number of streams, and what date the song was released. In the next cell we created the functionality to execute this dataset. 

