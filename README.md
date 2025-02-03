# Movie Recommender System - TMDB Dataset

A content-based movie recommender system using cosine similarity.

## Overview
This project is a simple movie recommendation system built using Python, Streamlit, and the TMDB dataset. It recommends movies based on content similarity using cosine similarity.

## Features
- **Movie Recommendations**: Get top 5 similar movies based on your selected movie.
- **Movie Posters**: Fetches and displays posters of recommended movies using the TMDB API.
- **User-Friendly Interface**: Built using Streamlit for an interactive experience.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/movie-recommender-system.git
   cd movie-recommender-system
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
1. Run the Streamlit app:
   ```sh
   streamlit run app.py
   ```
2. Select a movie from the dropdown and click **"Show Recommendation"**.
3. View the recommended movies along with their posters.

## Dependencies
- `streamlit`
- `requests`
- `pandas`
- `numpy`
- `pickle5`

## TMDB API Key
To fetch movie posters, this project uses The Movie Database (TMDB) API. Ensure you have a valid API key and update the `fetch_poster` function if needed.

## File Structure
```
movie-recommender-system/
│── model/
│   ├── movie_list.pkl
│   ├── similarity.pkl
│── app.py
│── requirements.txt
│── README.md
```

## Contributing
Feel free to open issues or submit pull requests for improvements!

## License
This project is licensed under the MIT License.

