# Spotify Track Data Analysis 🎵

This repository contains an Exploratory Data Analysis (EDA) project on Spotify track data. The project explores various audio features of tracks across 125 genres, aiming to uncover interesting patterns and insights.

---

## About the Dataset

The dataset consists of Spotify tracks with the following features:

### **Columns Description**
- `track_id`: Spotify ID for the track.
- `artists`: Names of artists (separated by `;` if multiple).
- `album_name`: Album in which the track appears.
- `track_name`: Name of the track.
- `popularity`: Popularity score (0-100), influenced by total and recent plays.
- `duration_ms`: Track length in milliseconds.
- `explicit`: Whether the track has explicit lyrics (`True` or `False`).
- `danceability`: Measure of how suitable a track is for dancing (0.0 to 1.0).
- `energy`: Perceived intensity and activity of a track (0.0 to 1.0).
- `key`: Musical key using Pitch Class notation.
- `loudness`: Overall loudness of the track (in dB).
- `mode`: Musical modality (1 = major, 0 = minor).
- `speechiness`: Presence of spoken words in a track (0.0 to 1.0).
- `acousticness`: Confidence that the track is acoustic (0.0 to 1.0).
- `instrumentalness`: Likelihood of no vocals in the track (0.0 to 1.0).
- `liveness`: Presence of an audience in the recording (0.0 to 1.0).
- `valence`: Musical positiveness of the track (0.0 to 1.0).
- `tempo`: Tempo of the track (in BPM).
- `time_signature`: Estimated time signature (e.g., 3/4, 4/4, etc.).
- `track_genre`: Genre of the track.

---

## Project Highlights

1. **Popular Artists and Tracks**:
   - Analyzed the distribution of track popularity.
   - Identified top artists and albums.

2. **Genre Analysis**:
   - Explored the diversity of audio features across genres.
   - Insights into danceability, energy, and acousticness by genre.

3. **Audio Feature Correlations**:
   - Relationship between tempo, loudness, and energy.
   - Insights into track valence (positiveness) and its impact on popularity.

4. **Visualization**:
   - Clear and insightful visualizations using Matplotlib and Seaborn.

---

## Installation and Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/spotify-eda-project.git
   
2. Install required Python libraries:
   pip install -r requirements.txt
   
4. Open the notebook and run it:
   jupyter notebook "Spotify Track Data Analysis.ipynb"

   
## Tools and Libraries Used
- Pandas: For data manipulation and cleaning.
- Matplotlib & Seaborn: For data visualization.
- NumPy: For numerical computations.

## Contributing
Contributions are welcome! If you have ideas to enhance the project or build additional features, feel free to fork this repository and submit a pull request.

## License
This project is licensed under the MIT License.
