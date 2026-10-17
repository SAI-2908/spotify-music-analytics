# Spotify Music Analytics

## Project Overview
This project explores Spotify music data using Python to identify patterns in track popularity, release years, artist performance, song duration, album types, and explicit content.

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow
1. Loaded and inspected the datasets.
2. Handled missing artist names and genre values.
3. Converted album release dates into datetime format and extracted release years.
4. Explored track popularity and artist performance.
5. Created visualizations to identify patterns and relationships.
6. Compared average popularity across album types and explicit-content categories.

## Key Findings
- The cleaned dataset contains 8,579 tracks.
- The dataset contains more tracks from recent release years, with 2025 having the highest count.
- Track duration has a very weak positive correlation with popularity (0.106).
- Album tracks have higher average popularity than singles and compilations in this dataset.
- Explicit tracks have higher average popularity than non-explicit tracks in this dataset.

These findings describe the dataset analyzed and should not be generalized to all music on Spotify. The observed relationships do not establish causation.

## Dataset Source
The data comes from the [Spotify Global Music Dataset (2009–2025) on Kaggle](https://www.kaggle.com/datasets/wardabilal/spotify-global-music-dataset-20092025).

The CSV files are not included in this repository. Please refer to the original dataset page for access and usage terms.

## How to Run
1. Download the CSV files from the original dataset source, subject to its usage terms.
2. Place the CSV files in the location expected by the notebook.
3. Install the required Python libraries: `pandas`, `numpy`, `matplotlib`, and `seaborn`.
4. Open `Spotify_Music_Analytics.ipynb` in Jupyter Notebook or JupyterLab.
5. Run the notebook cells from top to bottom.

## Author
Sai Kale
https://www.linkedin.com/in/sai-kale-b9b28532a/?isSelfProfile=true
