# Spotify
Project Proposal - Brandon &amp; Rudy 
Title: Artist Collaboration Network Analysis

Background information:
This project will use network analysis to explore how artists are linked on Spotify. Artists often work together on songs, which can help them reach new audiences and boost their popularity. We want to see which artists are the most connected and how groups or clusters of artists form.

What we hope to learn: 
Who are the most influential or central artists in the collaboration network? Are there clear groups of artists who often work together? These are the questions we hope to answer in this network analysis project.

Potential datasets:
https://www.kaggle.com/datasets/jfreyberg/spotify-artist-feature-collaboration-network 
Around 20,000 artists who appeared on the Spotify weekly charts
About 136,000 more artists who were featured with the charting artists
Over 300,000 connections (edges) representing collaborations between these artists on the same track
Over 135,000 total artists (nodes)
The data was collected from Spotify's weekly charts and song metadata, including information about featured artists.


Barriers/Challenges:

Since this is a large dataset, it might take a long time for R to process the data, especially when making the graphs. To overcome this we should make sure that the code looks good before running it. Another problem we may encounter is that the dataset may include Null value. To overcome this we would only use the rows that contain values in them and are not missing any.

