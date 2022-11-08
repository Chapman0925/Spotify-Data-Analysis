# Spotify-Data-Analysis-Project

In this project, I will be analyzing the Spotify Databse by utilizing the python libraries such as panda, numpy, matplotlib.pyplot and seaborn. The dataset consists of all the songs from the spotify dataset from 1922 - 2021. During the project, I will go thorugh some real life business questions and answer these questions by analyzing and visualizing the data. 

The Dataset can be found in Kaggle: 1. https://www.kaggle.com/datasets/zaheenhamidani/ultimate-spotify-tracks-db
                                    2. https://www.kaggle.com/datasets/lehaknarnauli/spotify-datasets?select=artists.csv
                                    
1. Top 10 songs in the spotify platform with over 90 popularity
      
      - Utlizied sort_values(), query() in order to filter out the dataset
      - Illustrated the dataset via Seaborn Bar Chart.
2. Date Preprocessing
      
      - Changing the index to release date and convert release date data type to panda's datetime 
      - Adding new column for song's duration until from millisecond to second
      - Dropping col

3. Correlation between each song's feature
      
      - Demonstrated the correlation between each feature by using Seaborn Heatmap and correlation function.
      - Utilized sample function and regression plot from seaborn to examine the accuracy of our data.
      -In conclusion we can tell that as loudness increases, the energy level of the song will also increase which indicates of a positive correlation and from our            heatmap, loudness and energy share a correlation of 0.76 which is a positive correlation.

4. Total number of songs that are produced during each year of 1922-2021

       - Using a distribution plot to find out how many songs are produced during each year
       - 2020 has the most songs produced!

5. Average Duration of song in each year
       
       - Utilized a Bar plot to demonstrate the difference of songs' duration in each year

6. Duration of different type of songs
       
       - Converting the ms to s for duration time
       
       - Illustrated the duration of different type of songs by using barplot, we can see that Classical music and world music have the higher duration compared to            children's music.

7. Type of Song that attracted most audience to listen to

       - Utilized sort-value function to filter out the top 10 most popular song within the dataset and look into the genre type of the song 
       
       - Concluded that the top 10 songs in spotify database are dance,pop,rap,hiphop and reggaeton.

