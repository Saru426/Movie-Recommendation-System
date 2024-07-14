# Movie Recommendation System

This project is a Movie Recommendation System developed using collaborative filtering techniques. The system recommends movies to users based on their ratings and preferences.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Data](#data)
- [Features](#features)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Installation

To install the necessary dependencies, run:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/Saru426/movie-recommendation-system.git
    cd movie-recommendation-system
    ```

2. Run the Jupyter Notebook:
    ```bash
    jupyter notebook "Movie Recommendation System.ipynb"
    ```

## Project Structure

```
movie-recommendation-system/
├── data/
│   ├── movies.csv
│   └── ratings.csv
├── Movie Recommendation System.ipynb
└── README.md
```

## Data

The dataset used in this project includes two files:
- `movies.csv`: Contains movie information (movieId, title, genres)
- `ratings.csv`: Contains user ratings (userId, movieId, rating, timestamp)

## Features

- **Data Loading and Exploration**: Importing necessary libraries and loading the dataset.
- **Data Preprocessing**: Cleaning and transforming the data for analysis.
- **Collaborative Filtering**: Implementing a recommendation algorithm using Nearest Neighbors.
- **Visualization**: Visualizing data and results using Matplotlib and Seaborn.

## Results

The recommendation system effectively suggests movies to users based on their historical ratings. Detailed results and visualizations are provided in the notebook.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.

---
