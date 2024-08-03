# Music_Recommendation_System_Using_Spotify_Dataset 

A music recommendation system built using the Spotify dataset and Python.

#Description
This project uses the Spotify dataset to build a music recommendation system. The system takes a user's listening history and recommends songs based on their preferences. The recommendation algorithm uses a combination of natural language processing (NLP) and collaborative filtering to suggest songs.

#Features
User-based recommendation: recommends songs to a user based on their listening history
Song-based recommendation: recommends songs that are similar to a given song
Artist-based recommendation: recommends songs by artists that are similar to a given artist
Genre-based recommendation: recommends songs from a specific genre

#Requirements
Python 3.x
pandas library (install using pip install pandas)
numpy library (install using pip install numpy)
scikit-learn library (install using pip install scikit-learn)
spotipy library (install using pip install spotipy)

#Usage
#User-based Recommendation

from music_recommendation import MusicRecommender

user_id = "your_spotify_user_id"
recommender = MusicRecommender()
recommended_songs = recommender.user_based_recommendation(user_id)
print(recommended_songs)


#Song-based Recommendation

from music_recommendation import MusicRecommender

song_id = "your_spotify_song_id"
recommender = MusicRecommender()
recommended_songs = recommender.song_based_recommendation(song_id)
print(recommended_songs)

#Artist-based Recommendation

from music_recommendation import MusicRecommender

artist_id = "your_spotify_artist_id"
recommender = MusicRecommender()
recommended_songs = recommender.artist_based_recommendation(artist_id)
print(recommended_songs)

#Genre-based Recommendation

from music_recommendation import MusicRecommender

genre = "your_preferred_genre"
recommender = MusicRecommender()
recommended_songs = recommender.genre_based_recommendation(genre)
print(recommended_songs)

#Dataset
The Spotify dataset used in this project can be found here.

#Installation
Clone the repository using git clone https://github.com/your-username/music-recommendation-system.git
Install the required libraries using pip install -r requirements.txt
Run the script using python music_recommendation.py

#Contributing
Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request.

#License
This project is licensed under the MIT License. See the LICENSE file for details.

I hope this helps
