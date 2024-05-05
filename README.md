# Movie Recommendation System

This project is a movie recommendation system built using machine learning techniques. It analyzes user preferences and movie data to provide personalized movie recommendations.

## Features

- **Collaborative Filtering**: Utilizes collaborative filtering algorithms to analyze user ratings and behavior patterns to make recommendations based on similar users' preferences.
- **Content-Based Filtering**: Employs content-based filtering techniques to analyze movie metadata (genre, director, actors, plot summary, etc.) to recommend movies similar to those a user has enjoyed in the past.
- **Hybrid Approach**: Combines both collaborative and content-based filtering methods for more accurate and diverse recommendations.

## Dataset

The project uses a custom dataset consisting of movie data from a CSV file (`movies.csv`). The dataset is loaded into a pandas DataFrame using the following code:

```python
import pandas as pd

movies = pd.read_csv("/content/drive/MyDrive/movies.csv")
```

## Technologies Used

- Python
- pandas
- scikit-learn
- numpy

## Getting Started

1. Clone the repository: `git clone https://github.com/Mster9/Movie-Recommendation-System.git`
2. Navigate to the project directory.
3. Install the required dependencies: `pip install -r requirements.txt`
4. Run the main script: `Movie-Recommendation-System.py`

## Usage

- Input your data into the system.
- The system will analyze your input data and generate personalized movie recommendations based on the movie database and the analysis of your input.
- Recommended movies will be presented to you by the system.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
