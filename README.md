
# Netflix Shows Analysis

Exploratory data analysis of Netflix’s catalog using SQL, including data cleaning, 3NF normalization, and visualization of content trends.

## Project Overview

This project analyzes the Netflix titles dataset to uncover trends in:

* Content distribution (Movies vs TV Shows)
* Genre popularity
* Release year patterns
* Ratings distribution
* Recently added content
* Longest-running TV shows
* Genre evolution over time

The workflow includes:

1. Data extraction
2. Data cleaning
3. Data normalization (3NF)
4. SQL analysis with SQLite
5. Data visualization

---

## Technologies Used

* Python
* Pandas
* SQLite3
* Matplotlib
* Seaborn
* KaggleHub
* Jupyter Notebook

---

## Dataset

The dataset contains information about Netflix titles including:

* Title
* Type (Movie / TV Show)
* Director
* Cast
* Country
* Date Added
* Release Year
* Rating
* Duration
* Genre
* Description

Dataset source: Netflix Titles Dataset from Kaggle.

---

## Project Structure

```bash
.
├── netflix_shows_analysis.ipynb
├── README.md
└── generated_outputs/
```

---

## Project Phases

### Phase 1 — Data Extraction

* Download dataset using KaggleHub
* Load CSV into a Pandas DataFrame
* Preview raw dataset

### Phase 2 — Data Understanding

* Explore dataset structure
* Identify missing values
* Inspect data types

### Phase 3 — Data Cleaning

* Handle missing values
* Remove duplicates
* Strip whitespace
* Parse date columns

### Phase 4 — Data Normalization (3NF)

The dataset is transformed into normalized relational tables for efficient SQL querying.

### Phase 5 — SQL Analysis

Example analytical queries include:

* Recent movies released after 2021
* Most recently added titles
* Content type distribution
* Most productive release years
* Top genres by title count
* Rating breakdowns
* Longest-running TV shows
* Genre trends over time

### Phase 6 — Data Visualization

Visualizations include:

* Genre density bar plots
* Movie vs TV Show comparisons
* Genre evolution heatmaps
* Ingestion trends over time

### Phase 7 — Finalization

* SQLite connection cleanup
* Artifact and workflow summary

---

## Key Insights

Some insights discovered during the analysis:

* Movies significantly outnumber TV Shows on Netflix.
* Certain genres dominate the platform across multiple years.
* Content ingestion increased rapidly after 2015.
* TV Shows tend to have broader rating distributions.

---

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/netflix-shows-analysis.git
cd netflix-shows-analysis
```

### 2. Install Dependencies

```bash
pip install pandas matplotlib seaborn kagglehub
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```bash
netflix_shows_analysis.ipynb
```

---

## Example Visualizations

The notebook generates several charts and analytical outputs including:

* Genre popularity comparisons
* Heatmaps of genre evolution
* Content growth trends
* Distribution plots

---

## Future Improvements

Possible future enhancements:

* Interactive dashboards with Plotly or Power BI
* Recommendation system integration
* NLP analysis on title descriptions
* Time-series forecasting for content trends
* Advanced genre clustering

---

## Author

Created by GitHub user.

---

## License

This project is open-source and available under the MIT License.
