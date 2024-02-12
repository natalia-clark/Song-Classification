# Song-Classification
Classification model using Random Forest and XGBoost.

Goal: Bin track popularity and create a classification model to predict track popularity of a song based on key features.

Dataset:
2300 records from Spotify including data features for track popularity including:
1. year - year
2. track name
3. track_popularity - 0 to 100 (Target variable)
4. album_name - the track appears on
5. artist name
6. artist_genres - list of the Genres the artist is associated with
7. artist_popularity - from 0 to 100
8. danceability - a value of 0.0 is least danceable and 1.0 is most danceable
9. energy - a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity, being 1.0 the maximum
10. key - key the track is in; integers map to pitches using standard Pitch Class notation - E.g. 0 = C,  1 = C♯/D♭,  2 = D  and so on
11. loudness - overall loudness of a track in decibels (dB)
12. mode - modality (major or minor) of a track; Major = 1 and minor = 0
13. speechiness - detects the presence of spoken words in a track; more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the attribute value
14. acousticness - confidence measure from 0.0 to 1.0 of whether the track is acoustic from 0 to 1
15. instrumentalness - predicts whether a track contains no vocals from 0 to 1
16. liveness - detects the presence of an audience in the recording from 0 to 1
17. valence - a measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track
18. tempo - overall estimated tempo of a track in beats per minute (BPM)
19. duration_msThe duration of the track in milliseconds


Files:
Notebook_asPDF.pdf -> the Jupyter Notebook as a PDF (incase you just want contents)
RF_Boosting_Notebook.ipynb -> the Jupyter Notebook with the used models
Songs_2024.xlsx -> the original dataset
genre_clustered.xlsx -> clustering of genres created by segmentation (by the notebook)
Songs_2024_cleaned.xlsx -> cleaned version of the dataset (saved by notebook)
