# 🎬 Movie EDA Visualizer

A complete Exploratory Data Analysis (EDA) project that dives into trends, insights, and patterns in the film industry. Using Python, the project analyzes features like genres, IMDb ratings, runtime, votes, and gross revenue to better understand what drives a movie’s popularity and success.

## 📌 Project Description

This project performs data cleaning, transformation, and insightful visualizations on a movie dataset. It explores trends across genres, ratings, votes, revenue, and other features, revealing hidden patterns in the film domain. All analysis is performed using Pandas, Matplotlib, and Seaborn.

## 📁 Dataset Columns

The dataset contains the following key columns:

| Column     | Description                                |
|------------|--------------------------------------------|
| MOVIES     | Title of the movie                         |
| YEAR       | Year of release                            |
| GENRE      | Genres associated with the movie           |
| RATING     | IMDb rating (0–10)                         |
| ONE-LINE   | A summary of the movie                     |
| STARS      | Lead actors/actresses                      |
| VOTES      | Number of IMDb votes                       |
| RunTime    | Movie duration in minutes                  |
| Gross      | Gross revenue of the film in USD           |

## 🧼 Data Cleaning Process

- Removed duplicates and irrelevant rows.
- Extracted 4-digit years using regex.
- Handled multiple genres in a single cell.
- Converted `VOTES` and `Gross` columns from strings to numeric values.
- Stripped whitespace and handled null values.
- Saved cleaned data to `cleaned_data.csv`.

## 📊 Exploratory Visualizations

1. IMDb Ratings Distribution – Viewer sentiment breakdown.
2. Most Frequent Genres – Popular genre count.
3. Average Rating by Genre – Which genres get the best reviews?
4. Gross Revenue Histogram – Film revenue distribution.
5. Average Gross per Genre – Revenue comparison across genres.
6. Votes vs Gross Scatterplot – Popularity vs revenue.
7. Gross Over Time – Revenue trends over the years.
8. Correlation Heatmap – Numeric feature relationships.

Each visualization includes analysis and real-world interpretation.

## 📦 Tools & Libraries

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- gdown (for dataset downloads)
- Jupyter Notebook / Google Colab

## 🗂️ Folder Structure

```
Movie-EDA-Visualizer/
│
├── data.csv              # Original raw dataset
├── cleaned_data.csv      # Cleaned and transformed dataset
├── Movie_EDA.ipynb       # Main notebook with full analysis
└── README.md             # Project documentation (this file)
```
## Visualisation

- Distribution of Movie Ratings

 ![My plot](https://github.com/JHK0723/solubility-prediction-ML/blob/f0d532d40e5c62918d467b45854b6c2360d06c65/LRimage.png)

- Count of Movies per Genre

 ![My plot](https://github.com/JHK0723/solubility-prediction-ML/blob/f0d532d40e5c62918d467b45854b6c2360d06c65/LRimage.png)

- Average Movie Rating by Genre

 ![My plot](https://github.com/JHK0723/solubility-prediction-ML/blob/f0d532d40e5c62918d467b45854b6c2360d06c65/LRimage.png)

- Correlation Heatmap of Numeric Features

 ![My plot](https://github.com/JHK0723/solubility-prediction-ML/blob/f0d532d40e5c62918d467b45854b6c2360d06c65/LRimage.png)

- Distribution of Gross Profit

 ![My plot](https://github.com/JHK0723/solubility-prediction-ML/blob/f0d532d40e5c62918d467b45854b6c2360d06c65/LRimage.png)

- Average Gross Profit by Genre

 ![My plot](https://github.com/JHK0723/solubility-prediction-ML/blob/f0d532d40e5c62918d467b45854b6c2360d06c65/LRimage.png)

- Average Gross Profit Over the Years

 ![My plot](https://github.com/JHK0723/solubility-prediction-ML/blob/f0d532d40e5c62918d467b45854b6c2360d06c65/LRimage.png)

- Votes vs Gross Profit

 ![My plot](https://github.com/JHK0723/solubility-prediction-ML/blob/f0d532d40e5c62918d467b45854b6c2360d06c65/LRimage.png)

## 📁 Output

- Cleaned dataset exported as `cleaned_data.csv`
- All graphs and plots are available in the notebook
- Ready-to-use visuals for presentations or reporting

## 🚀 Future Improvements

- Deploy an interactive dashboard using Streamlit or Dash
- Apply clustering to group movies by similarity
- Perform NLP analysis on `ONE-LINE` summaries


## ⚖️ License

This project is licensed under the MIT License.

## 🙏 Acknowledgements

Special thanks to the Python community and open-source contributors.  
Dataset credits go to the original providers (IMDb or Kaggle sources if used).

⭐ If you found this project helpful, feel free to star it on GitHub!

