# Pandas Data Analysis on Spotify Dataset

![Spotify Logo](https://i.ytimg.com/vi/g5NpxSR6OD0/hq720.jpg?sqp=-oaymwE7CK4FEIIDSFryq4qpAy0IARUAAAAAGAElAADIQj0AgKJD8AEB-AHUBoAC4AOKAgwIABABGB0gZSg1MA8=&rs=AOn4CLBAlqV9kq5EQmBIpFQHrXBmDVH-2A)

As a music lover, I've often wanted to dive into the world of music for data analysis. After spending some time exploring potential music related I came across the Spotify Top Hits dataset on Kaggle which I thought was perfect for my first music related data analysis.

Link to original dataset: [Click Here](https://www.kaggle.com/datasets/paradisejoy/top-hits-spotify-from-20002019)

## Questions to Answer

Below are questions I wanted to answer regarding the dataset:

1. What are the top 5 most popular songs?
2. What are the top 5 artists based on most hits?
3. What are the top 5 most popular genres?
   - 3.1 What is the trend of each of these genres over time?
   - 3.2 How danceable is each of these genres?
4. How has the average duration of songs changed over time?
5. How has the mood of songs changed over time?

## Approach

#### Data Cleaning
- Performed data cleaning tasks using Pandas in a Jupyter Notebook
- Identified and removed outlier values
- Eliminated duplicate data entries
- Conducted a thorough check for null values to ensure data integrity

Visit the Data section to learn more about the data cleaning process

#### Data Analysis
- Performed analysis on the cleaned dataset using Pandas in a Jupyter Notebook
- Employed data visualization libraries like Matplotlib and Seaborn to create informative plots and graphs on insights
- Utilized Python libraries like NumPy and scikit-learn for linear regression to identify possible trends in data

## Files in this Repo
Data Folder
- original_spotify_data.csv: The original dataset downloaded from Kaggle. NOTE: I renamed the dataset to original_spotify_data so don't be confused if the file name is different for you if you download the data from Kaggle
- cleaning_spotify_data.ipynb: The data cleaning code
- cleaned_spotify.csv: The cleaned version of the dataset

Analysis Folder
- spotifyAnalysis.ipynb: The analysis code on the cleaned_spotify.csv data

Charts Folder: The folder contains all the visualizations that were created in the analysis code as image files
