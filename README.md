# Movie Data Analysis

A data analysis project that explores movie metadata using Python, Pandas, NumPy, Matplotlib, Seaborn, and Plotly. The project cleans and analyzes movie data, explores genre-wise popularity, and visualizes the relationship between movie popularity and ratings.

## Project Overview

This project performs exploratory data analysis (EDA) on a movie dataset. It includes:
- Loading and inspecting the movie dataset
- Checking and handling duplicate and missing values
- Extracting the main genre from genre data
- Analyzing average popularity by main genre
- Visualizing the distribution of movie ratings
- Exploring genre-wise popularity with a heatmap
- Creating an interactive popularity-versus-rating scatter plot

## Dataset

The notebook expects the dataset at:

```text
data/movies.csv
```

The dataset appears to be based on Kaggle's **TMDB 5000 Movie Dataset**. The original Kaggle file is commonly named `tmdb_5000_movies.csv`; rename it to `movies.csv` and place it in the `data` folder to match the notebook's file path.

Kaggle: https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

## Project Structure

```text
Movie-Data-Analysis/
├── data/
│   └── movies.csv
├── notebook.ipynb
├── interactive_movie_plot.html
├── README.md
└── requirements.txt
```

The HTML plot is generated when the relevant notebook cell is run. Other plots may be displayed or saved according to the notebook cells.

## Requirements

- Python 3.9 or later
- Jupyter Notebook or JupyterLab

Install the required packages:

```bash
pip install -r requirements.txt
```

## How to Run

1. Clone or download this repository.
2. Download the dataset from Kaggle and place `movies.csv` inside the `data/` folder.
3. (Recommended) Create and activate a virtual environment:

   ```bash
   python -m venv venv
   ```

   **Windows PowerShell:**
   ```powershell
   .\venv\Scripts\Activate.ps1
   ```

   **macOS/Linux:**
   ```bash
   source venv/bin/activate
   ```

4. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Open the notebook:

   ```bash
   jupyter notebook notebook.ipynb
   ```

6. Run the notebook cells from top to bottom.

## Tools and Libraries

- **Pandas** — data loading, cleaning, and analysis
- **NumPy** — numerical operations
- **Matplotlib** and **Seaborn** — static visualizations
- **Plotly** — interactive visualization
- **Jupyter** — notebook environment

## Outputs

The notebook explores movie ratings, genre popularity, and the relationship between popularity and ratings. It also exports an interactive Plotly visualization as `interactive_movie_plot.html`.

## Notes

- Ensure the CSV path matches `data/movies.csv`.
- This is an exploratory data analysis project; the notebook does not train a machine-learning prediction model.
- The exact dataset version and license should be confirmed on the Kaggle dataset page before redistribution.
