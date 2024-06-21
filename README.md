# Music Recommendation System

This repository contains a Python-based Music Recommendation System built using Jupyter Notebook, Streamlit, and Spotipy. The system recommends music based on similarity metrics calculated from a dataset of songs and artists.

## Features

- **Song Recommendation**: Input a song name and get recommendations based on similarity.
- **Interactive UI**: Built using Streamlit for easy interaction and visualization.
- **Integration with Spotify API**: Utilizes Spotipy to fetch album covers and enhance user experience.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/music-recommendation-system.git
   cd music-recommendation-system

2. Install dependencies:
    ```bash
    pip install -r requirements.txt

3. Spotify API Credentials:
- Obtain Spotify API credentials from Spotify for Developers. Update config.py with your CLIENT_ID and CLIENT_SECRET.

## Usage
1. Run the Streamlit app:
   ```bash
   streamlit run app.py
   
2. Open your web browser and navigate to http://localhost:8501 (or the URL provided by Streamlit).

3. Select a song from the dropdown menu or enter the song name directly.

4. Click on "Show Recommendation" to see recommended songs and their album covers.

## File Structure
- **app.py**: Main application file using Streamlit.
- **config.py**: Configuration file for Spotify API credentials.
- **notebooks/**: Jupyter Notebooks for data preprocessing and similarity calculations.
- **data/**: Directory for dataset files (e.g., df.pkl, similarity.pkl).

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your proposed changes.

- Fork the project.
- Create your feature branch (git checkout -b feature/AmazingFeature).
- Commit your changes (git commit -m 'Add some AmazingFeature').
- Push to the branch (git push origin feature/AmazingFeature).
- Open a pull request.
