===============================================
   MUSIC PLAYLIST GENERATOR USING COLLABORATIVE FILTERING AND LAST.FM
===============================================

This project demonstrates how to generate personalized music playlists for users using collaborative filtering techniques and real listening history fetched from the Last.fm API.

🔍 Project Overview  
Goal: Recommend music tracks to users by analyzing their top artists and interaction data using user-based and item-based collaborative filtering.  

Data Source: Spotify listening history via the Last.fm API  

Recommendation Methods Used: User-Based Collaborative Filtering, Item-Based Collaborative Filtering  

Similarity Metric: Cosine Similarity

🧠 Key Features  
- Fetch real user listening data from the Last.fm API  
- Generate music recommendations using user-item interaction data  
- Calculate similarity between users or items using cosine similarity  
- Recommend top N tracks or artists based on similarity  
- Display recommended songs in the console and optionally save to CSV

🛠️ Technologies Used  
- Python 3  
- Last.fm API  
- Pandas  
- NumPy  
- Scikit-learn  
- Requests  
- Jupyter Notebook

📦 Installation  
pip install pandas numpy scikit-learn requests

🚀 How to Run  
1. Add your Last.fm API key in the script  
2. Provide one or more Last.fm usernames  
3. Run the notebook:  
   jupyter notebook Music_Playlist_Generator_Develop_a_system_that_creates_personalized_music_playlists_for_users_using_collaborative_filtering.ipynb

This will:  
- Fetch user listening data (e.g., top artists) from Last.fm  
- Build a user-item interaction matrix  
- Compute user-user or item-item similarity using cosine similarity  
- Generate music recommendations  
- Display the recommendations in the notebook output

📄 Sample Output  
Recommendations for User 0 (zeden1):
Artist: Gavn!, Score: -340282346638528859811704183484516925440.00

Artist: Bella, Score: -340282346638528859811704183484516925440.00

Artist: B.o.B, Score: -340282346638528859811704183484516925440.00

Artist: AKano, Score: -340282346638528859811704183484516925440.00

Artist: 347aidan, Score: -340282346638528859811704183484516925440.00

✅ Use Cases  
- Music recommendation systems based on real-world user listening behavior  
- Projects involving collaborative filtering or recommender system research  
- Last.fm-based user profiling  
- Personalized playlist generators for music apps

🧑‍💻 Author  
Mohammad Aman  
