Music Recommendation System
 Overview

This project is a machine learning-based music recommendation system built using Spotify track data. It analyzes audio features to classify songs into genres and recommends similar songs using a content-based filtering approach.

 Features
Processed and analyzed a dataset of 114,000+ songs
Cleaned data by removing missing values and unnecessary columns
Reduced classification complexity to top 20 genres
Built a Random Forest classifier for genre prediction
Developed a content-based recommendation system using cosine similarity
Enabled song search by name for instant recommendations

Python
Pandas
Matplotlib
Seaborn
Scikit-learn

Achieved ~48% accuracy on a multi-class classification problem (20 genres)
Successfully generated real-time song recommendations
Identified key relationships between audio features using correlation analysis
⚙️ How It Works
Data Cleaning
Removed unnecessary columns
Handled missing values
Filtered dataset to top 20 most frequent genres
Feature Selection
Selected key audio features:
Danceability
Energy
Loudness
Speechiness
Acousticness
Instrumentalness
Valence
Tempo
Model Training
Split data into training and testing sets
Trained a Random Forest classifier
Evaluated model performance using accuracy
Recommendation System
Sampled dataset to optimize performance
Computed cosine similarity between songs
Recommended top 5 similar songs based on:
Song index
Song name (user input)


Install required libraries:

pip install pandas matplotlib seaborn scikit-learn
Place spotify-tracks-dataset.csv in the project folder

Run the script:

python main.py
 Example Functionality
Displays:
Top genres by popularity (bar chart)
Feature correlation heatmap
Outputs:
Recommended songs by index
Recommended songs by name (e.g., "Smooth Criminal")
 Future Improvements
Build an interactive UI using Streamlit
Improve recommendation accuracy with advanced models
Incorporate user preferences for personalized recommendations

Sujal Ponnaluri
