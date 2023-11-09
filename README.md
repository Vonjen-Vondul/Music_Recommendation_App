# Spotify Song Recommender

This repository contains code for analyzing and recommending songs based on Spotify data. The analysis includes clustering genres, visualizing feature correlations, and recommending songs similar to a given list.

## Prerequisites

Before running the code, make sure you have the following:

- Spotify Developer credentials (Client ID and Client Secret)
- Spotify API access
- Python environment with necessary packages (see `requirements.txt`)

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/spotify-song-recommender.git
   cd spotify-song-recommender
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Set up your Spotify Developer credentials:

   ```python
   # Add your Spotify Client ID and Client Secret as environment variables
   export SPOTIFY_CLIENT_ID='your_client_id'
   export SPOTIFY_CLIENT_SECRET='your_client_secret'
   ```

4. Run the main script:

   ```bash
   python main.py
   ```

## Project Structure

- `main.py`: Main script for running the song recommender.
- `data_preprocessing.py`: Data loading and preprocessing.
- `analysis_visualization.py`: Analysis and visualization functions.
- `song_recommender.py`: Song recommendation functions.
- `Spotify_Data/`: Directory containing Spotify data files.

## Usage

Follow the steps in `main.py` to analyze the Spotify data, visualize correlations, and generate song recommendations based on input songs.

Feel free to customize and explore the code to suit your preferences and use cases.

## Results

After running the recommender with sample input songs ('lose yourself' from 2002 and 'brand new' from 2023), the output suggests similar songs:

```python
[{'name': 'No Promises',
  'year': 2017,
  'artists': "['A Boogie Wit da Hoodie']"},
 {'name': 'Ex Calling', 'year': 2016, 'artists': "['6LACK']"},
 {'name': 'Lucky Ass Bitch', 'year': 2013, 'artists': "['Mac Miller']"},
 {'name': 'Rockstar Chainz', 'year': 2020, 'artists': "['Future']"},
 {'name': 'Long Time', 'year': 2018, 'artists': "['Lil Tjay']"},
 {'name': 'India', 'year': 2017, 'artists': "['Lil Durk']"},
 {'name': 'Ocean Drive',
  'year': 2016,
  'artists': "['21 Savage', 'Metro Boomin']"},
 {'name': 'Lonely', 'year': 2014, 'artists': "['Speaker Knockerz']"},
 {'name': 'Trophies', 'year': 2014, 'artists': "['Young Money', 'Drake']"},
 {'name': 'Where Ya At (feat. Drake)',
  'year': 2015,
  'artists': "['Future', 'Drake']"}]
```
