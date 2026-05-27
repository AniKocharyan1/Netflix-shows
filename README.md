
# Netflix Content Analytics — ETL, SQL & Exploratory Data Analysis Pipeline

A production-style ETL and analytics project built around the Netflix Titles dataset. Raw CSV data is cleaned and transformed using Python, loaded into a structured SQLite database, and analyzed with SQL and visualization techniques to uncover trends in streaming content, genre distribution, ratings, and platform growth.

This project demonstrates practical skills in:

* Data extraction and preprocessing
* Relational database design
* Data normalization (3NF)
* SQL analytics
* Exploratory Data Analysis (EDA)
* Business insight generation
* Data visualization and storytelling

---

## 1. Project Overview

The project answers analytical questions such as:

* Which genres dominate Netflix's catalogue?
* How has Netflix content evolved over time?
* What proportion of the platform consists of Movies versus TV Shows?
* Which years experienced the largest growth in content releases?
* Which genres and ratings appear most frequently?
* How does genre popularity shift over time?

The raw dataset contains inconsistencies commonly found in real-world scraped data — missing values, duplicate entries, inconsistent formatting, mixed units in duration fields, and date parsing issues. The pipeline cleans and standardizes this data before loading it into a queryable SQLite database for analysis.

---

## 2. Dataset

Source: Netflix Titles Dataset from Kaggle

Files include metadata for Netflix Movies and TV Shows:

* Title
* Type (Movie / TV Show)
* Director
* Cast
* Country
* Date Added
* Release Year
* Rating
* Duration
* Genre / Listed In
* Description

The dataset contains thousands of Netflix titles and provides a strong foundation for exploratory data analysis, SQL querying, and visualization workflows.

---

## 3. Pipeline Description

The project follows a standard ETL workflow:

| File / Component               | Role                                                                                          |
| ------------------------------ | --------------------------------------------------------------------------------------------- |
| `netflix_shows_analysis.ipynb` | Main notebook containing extraction, transformation, SQL analysis, and visualization workflow |
| Pandas                         | Data cleaning and preprocessing                                                               |
| SQLite3                        | Relational database storage and SQL analytics                                                 |
| Matplotlib / Seaborn           | Visualization and trend analysis                                                              |

### Cleaning & Transformation Steps

The raw dataset required several preprocessing steps before analysis:

* Handling missing and null values
* Removing duplicate entries
* Standardizing categorical fields
* Parsing and formatting dates
* Cleaning inconsistent duration formats
* Separating Movies and TV Shows for comparative analysis
* Preparing normalized SQL-ready structures

The cleaning stage simulates real-world preprocessing workflows commonly required in analytics and data engineering projects.

---

## 4. Database & Analytical Workflow

After preprocessing, the cleaned data is loaded into SQLite for structured querying and analysis.

The analytical workflow includes:

* Exploratory Data Analysis (EDA)
* SQL aggregations
* Trend analysis
* Genre frequency analysis
* Comparative analysis between Movies and TV Shows
* Temporal analysis of release years and content additions

The project demonstrates practical use of:

* `GROUP BY`
* Filtering and sorting
* Aggregate functions
* Ranking and comparative analysis
* Time-based trend exploration

---

## 5. SQL Analysis

The notebook includes analytical queries and transformations designed to answer questions such as:

* Which genres are most common on Netflix?
* Which release years produced the most content?
* What is the ratio of Movies to TV Shows?
* Which titles were added most recently?
* Which ratings appear most frequently?
* How has Netflix content growth evolved over time?

The SQL analysis section focuses on analytical querying and insight generation using SQLite.

---

## 6. Data Visualization

The project generates multiple visualizations to communicate findings clearly, including:

* Genre distribution charts
* Content growth trends
* Release-year frequency plots
* Movie vs TV Show comparisons
* Heatmaps for genre evolution over time
* Rating distribution analysis

These visualizations support both exploratory analysis and business-style reporting.

---

## 7. Summary of Findings

### Requirements

* Python 3.10+
* Jupyter Notebook
* pandas
* matplotlib
* seaborn

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/netflix-content-analytics.git
cd netflix-content-analytics

# Install dependencies
pip install pandas matplotlib seaborn

# Launch Jupyter Notebook
jupyter notebook
```

Open:

```bash
netflix_shows_analysis.ipynb
```

---

## 10. Professional Relevance

This project demonstrates practical skills relevant to:

* Data Analytics
* SQL Development
* Exploratory Data Analysis (EDA)
* Data Cleaning & Transformation
* Business Intelligence
* Relational Database Workflows
* Data Visualization & Reporting

The repository is suitable for:

* Portfolio projects
* Internship applications
* Junior Data Analyst roles
* Academic submissions
* GitHub showcases

---

## 11. Future Improvements

## Clone the Repository

```bash
git clone https://github.com/your-username/netflix-content-analytics.git
cd netflix-content-analytics
```

## Install Required Libraries

```bash
pip install pandas matplotlib seaborn kagglehub
```

## Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```bash
netflix_shows_analysis.ipynb
```

---

Possible future enhancements include:

* Interactive dashboards using Plotly or Power BI
* Machine learning recommendation systems
* NLP-based sentiment and description analysis
* Predictive modeling for content trends
* Cloud database integration
* Automated ETL pipelines

---

---

## 12. Author

Developed as a portfolio data analytics project focused on ETL workflows, SQL analysis, and visualization using Python and SQLite.

---

# License

This project is licensed under the MIT License.


## License

This project is open-source and available under the MIT License.
