# Spotify Recommendation System 🎶🎼📗

![206826750-ca6c97f1-56d7-4fab-9a9d-8ecc09776774](https://github.com/SyedsProjectPortfolio45/Spotify-Recommendation-System/assets/147240839/f76cd3b1-d792-4cb5-86c8-6bdb8e679b94)

#### Tools used🛠: Python, Machine Learning, NumPy, Pandas, Sci-kit learn, SpotiPy

## 🚧You see the detailed code with visualizations by clicking on the Google Colab logo when you open the ipynb file

# Objective
To build a Music Recommendation System using the Spotify API to collect real-time music data from Spotify.

# What is Spotify API
The Spotify API is a set of rules and protocols provided by Spotify developers. It enables developers to interact with Spotify’s vast music catalogue and collect music-related data. Through the Spotify API, developers can access information such as tracks, albums, artists, playlists, user profiles, and play history, among other features, empowering them to build innovative applications and services that integrate seamlessly with the Spotify platform.

# Below is the process you can follow to sign up for the Spotify developer account and get your credentials:

**Step 1**: Create a Spotify Account
For a Spotify developer account, you need an account at Spotify. If you don’t use Spotify, create an account. You don’t need to purchase any subscription to get your credentials. Once you have created an account at Spotify (or you already have one) log in to your account from your web browser.

**Step 2**: Go to Your Spotify Developer Dashboard
Once you have created an account at Spotify, you need to log in to your Spotify developer dashboard. As you will be using this developer account for the first time, sign the agreement and verify your email.

**Step 3**: Create an App
Once you have verified an email, you will see an option to create an app in your dashboard, as shown in the image below.
![IMG_1003](https://github.com/SyedsProjectPortfolio45/Spotify-Recommendation-System/assets/147240839/86f2a1f5-b995-4aeb-891c-90cb3e57c39d)
Click “Create app” and move to the next step.

**Step 4**: App Description
Fill in the app description, as shown in the image below.
![IMG_1004](https://github.com/SyedsProjectPortfolio45/Spotify-Recommendation-System/assets/147240839/d41ed08b-338d-4706-97a6-20028ded5768)

**Step 5**: Copy Your Client ID and Client Secret
After filling in the app description, you will be redirected to your id and password. If you click “View client secret”, you will see your password. Copy your credentials so that you can use them while building a Music Recommendation System using Python.

## Now let's build a music recommendation system using Python

- To get started with building a Music Recommendation System, we first need to have an access token. The access token serves as a temporary authorization credential, allowing the code to make authenticated requests to the Spotify API on behalf of the application. The Client ID identifies the application, while the Client Secret is a confidential key used for authentication.
- With the access token, the application can now make authorized requests to retrieve music data, such as tracks, albums, artists, and user information, which is fundamental for building a music recommendation system using the Spotify API and Python.
- Install the **Spotipy** library, which is a Python library providing access to Spotify’s web API
- Defining a function responsible for collecting music data from any playlist on Spotify using the Spotipy library
- The extracted information for all tracks is stored in the music_data list. The function then creates a DataFrame from the music_data list. The DataFrame organizes the music data in a tabular format, making it easier to analyze and work with the collected information.
- Check if the data has any null values or not
- Import the necessary Python libraries now
- While providing music recommendations to users, it is important to recommend the latest releases. For this, we need to give more weight to the latest releases in the recommendations.
- We will create a hybrid recommendation system for music recommendations. The first approach will be based on recommending music based on music audio features, and the second approach will be based on recommending music based on weighted popularity
- The hybrid approach aims to provide more personalized and relevant recommendations by considering both the content similarity of songs and their weighted popularity. The function takes input_song_name as the input, representing the name of the song for which recommendations are to be generated.
- The hybrid_recommendations DataFrame is then sorted in descending order based on the weighted popularity score. This step ensures that the most popular and relevant songs appear at the top of the recommendations. The input song is then removed from the recommendations to avoid suggesting the same song as part of the recommendations.

# Output
![Screenshot (2445)](https://github.com/SyedsProjectPortfolio45/Spotify-Recommendation-System/assets/147240839/f12a5fec-4f3f-4848-a7ab-31ba94040b80)





















