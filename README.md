# billboard-music-epigenetics
Applications of the Epigenetic effects of listening to Music within the evolving music world
Overview
A data analysis project examining the evolution of musical diversity in the Billboard Top 100 charts from 2015-2023, with a focus on the impact of social media platforms like TikTok on music consumption patterns. This project implements machine learning techniques to analyze song features and track the changing landscape of popular music.
Key Features

Data Collection:
- Billboard Top 100 songs data from 2015-2023
- Song feature extraction using Spotify's Web Developer API
- TikTok sound analysis from random 15-minute sampling periods

Technical Implementation
Machine Learning:
- Unsupervised K-means clustering to categorize songs
- Principal Component Analysis (PCA) for dimensionality reduction
- Feature analysis across multiple musical attributes

Song Features Analyzed:
- Danceability
- Energy
- Speechiness
- Loudness
- Tempo
- Valence (emotional positivity)
- Instrumentalness
- Acousticness

Results:
The analysis revealed several key findings:
- Increased genre diversity post-2016 (TikTok's release)
- Evolution from 4 distinct song clusters in 2015 to 5 stable clusters by 2023
- Greater dispersion and stabilization of genre clusters over time

![plot_output](https://github.com/user-attachments/assets/04f783f5-bb90-42b2-8ed7-9b0819837bce)
![box_plot_output](https://github.com/user-attachments/assets/0fb2c08a-7b20-465f-b8fc-23df3ffc9ab2)


Technologies Used:
- Python
- Spotify Web API
- Pandas for data manipulation
- Scikit-learn for machine learning
- Matplotlib/Seaborn for visualization
